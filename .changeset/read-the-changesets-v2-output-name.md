---
"harn-ensemble": patch
---

Read the output name `changesets/action@v2` actually emits, so the release
workflow can cut a release at all.

`release.yml` pins `changesets/action@v2` and read a **v1** output name.
`changesets/action` renamed every output to kebab-case at v2:

| v1                  | v2                   |
| ------------------- | -------------------- |
| `hasChangesets`     | `has-changesets`     |
| `publishedPackages` | `published-packages` |
| `pullRequestNumber` | `pr-number`          |
| `published`         | `published`          |

GitHub evaluates a nonexistent property to the empty string rather than
failing, so `steps.changesets.outputs.hasChangesets == 'false'` was
`'' == 'false'` — always false. "Decide whether to release" never ran, its
`release` output was never set, and every step gated on it was skipped. The job
reported green while producing nothing, which is the worst property of the
defect: the repository has **no tags and no Releases at all**, and nothing said
so.

**The whole audit, not just the one name.** Every `steps.<id>.outputs.*`
reference in the repository was checked against the manifest of the major it
reads. There are seven, in this one file: the one corrected here, and six
`steps.decide.outputs.release` / `.tag` references that read a `run` step's own
`$GITHUB_OUTPUT` writes and were already right. The other three workflows
reference no step outputs.

**The duplicate-release guard now works for the case it was written for.** Its
second half — "this version is not already tagged" — has never executed, because
the first half never let it. `git ls-remote --exit-code` reports `0` for a match
and `2` for no match, but any other status is a _failed lookup_: `128` for an
unreachable or unauthenticated remote. The old `if` treated every non-zero
status alike, so a transient network failure would have read as "untagged" and
re-released a version that is already released — and because
`softprops/action-gh-release` updates an existing release rather than refusing,
that would have overwritten it silently. Only `2` is now allowed to mean the tag
is absent; anything else fails the step.

Two comments carried over from `sohl-kethira-basic` and were false here: this
repository has no hand-cut tags up to `v0.5.3` to inherit — it has never
released — and the comment above the step named the v1 output.

_The publish half of this path cannot be exercised without cutting a real
release, so it stays untested by construction. What to watch on the first run is
recorded on the pull request._
