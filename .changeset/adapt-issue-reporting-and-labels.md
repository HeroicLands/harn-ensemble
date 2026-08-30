---
"harn-ensemble": patch
---

Adapt the issue-reporting standard and the label registry to this repository, and
give the package homepage a `site` label.

`.github/ISSUE_REPORTING.md` and `.github/labels.yml` arrived as copies from
`sohl-kethira-basic` and were never adapted. They are the two documents a
contributor reads before filing, and they described a different repository: the
document was titled `Issue Reporting — sohl-kethira-basic`, the `content` label
read _"Kethira material"_ on a repository holding Hârn NPCs, and §9's "which
repository" table listed this repository nowhere while naming `sohl-kethira-basic`
as "**This repository**".

**One claim had become actively false.** Both files reasoned from _"this
repository ships Foundry compendium packs and nothing else — no system code, no
test suite, and no site"_ to the conclusion that the `site` label is absent. The
homepage work removed the premise: `publish.site` is `homepage`, and the package
publishes a page at `https://www.heroiclands.org/harnensemble/` that is built and
deployed from here. Because the registry is a **closed set** — `labels-sync`
deletes any label not listed — that stale reasoning did not merely misdescribe the
repository, it prevented a label existing for work the repository actually does.
So `site` is added, and the reasoning is rewritten to say why `system`, `tests`
and `thalorna` are still absent and why `site` no longer is.

**Also corrected, all repository-specific claims rather than process:**

| Claim                                                      | Was                     | Now                                                                  |
| ---------------------------------------------------------- | ----------------------- | -------------------------------------------------------------------- |
| Registry/table are kept in sync by `npm run lint:labels`   | asserted in both files  | stated as kept in step by hand — no such script exists here          |
| `documentation` label covers `CLAUDE.md`                   | asserted                | dropped; this repository has no `CLAUDE.md`                          |
| Bug reports name a "SoHL system version"                   | asserted                | game system and version, `hm3` or `sohl` — the module ships both     |
| Work here was tracked in `Song-of-Heroic-Lands-FoundryVTT` | a "historical note"     | removed; it was never true of this repository                        |
| §9 repository table                                        | omitted this repository | lists it first, plus `harn-adventures` and `HarnMaster-3-FoundryVTT` |

The carve-out note is restated for this module's own licensing — Keléstia's Fan
Material Guidelines, CC BY-NC-SA 4.0 — and now distinguishes the content, which is
never published, from the homepage, which is. The worked examples are re-cast in
this repository's material.

The registry's header also now records GitHub's 100-character cap on a label
description. The labels action checks it in `check` mode, so an over-long one
fails the pull request rather than the sync — a fact worth writing down where
the next person editing a description will read it.

The four-axis standard itself is untouched: types, priorities, milestones and the
label-registry mechanism are org-wide and were already correct.
