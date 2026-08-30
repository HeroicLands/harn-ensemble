---
"harn-ensemble": patch
---

Route this repository's private security reports and issue-standard links to this
repository, and add the `SECURITY.md` that `CONTRIBUTING.md` already links.

`.github/ISSUE_TEMPLATE/` arrived as a copy from `sohl-kethira-basic` and was
never adapted, so the issue chooser addressed a different repository. With
`blank_issues_enabled: false` the chooser is the only entry point, which made
the misrouting unavoidable rather than merely available.

**The security link sent advisories to the wrong repository.** "Report a security
vulnerability (private)" pointed at
`HeroicLands/sohl-kethira-basic/security/advisories/new`. A reporter following
this repository's own documented private-disclosure path filed their advisory
against the Kethira module, where it is not about that codebase and where a
different set of watchers receives it. It now points here.

**Corrected in the same directory, same cause:**

| File                                | Was                                                | Now                                |
| ----------------------------------- | -------------------------------------------------- | ---------------------------------- |
| `config.yml`                        | advisories at `sohl-kethira-basic`                 | advisories here                    |
| `config.yml`                        | _"This tracker is for the Kethira content module"_ | describes the Harn Ensemble module |
| `epic.yml`, `spike.yml`, `task.yml` | issue standard at `sohl-kethira-basic/blob/main/…` | this repository's own copy         |

**The chooser now routes both systems.** The module ships an Actor pack for
`hm3` as well as one for `sohl`, so a reporter whose defect is really in the
game system had one destination where the package has two. The existing
Song of Heroic Lands entry is unchanged and a HarnMaster 3 entry sits beside it.

**`SECURITY.md` is added.** `CONTRIBUTING.md` links `SECURITY.md` and no such
file existed, so the link 404'd; both sibling content repositories carry one and
the organization publishes no default. Its scope section is written for what this
repository actually ships — journal and actor packs, no application code — and it
points a system-level weakness at the two systems' own advisories.

Left alone deliberately: the Song of Heroic Lands system tracker and the Discord
link, which correctly address other places, and every `HeroicLands/.github`
reference in the workflows, which is the shared organization repository.

_Enabling private vulnerability reporting is a repository **setting**, not a file,
and it is currently off here — so the corrected link is necessary but not
sufficient until it is turned on in Settings → Advanced Security._
