---
"harn-ensemble": patch
---

Strip the retired `package:` frontmatter key from every content note.

All 2517 notes under `assets/content/` declared `package: harnensemble` — the
same value every time, because this repository authors exactly one package's
content. A note's package is now the repository's configured `contentPackage`,
so restating it per note is redundant.

**Why it needed `@heroiclands/package-build` 3.3.0 first.** On 3.2.0 and earlier
the field was a _selector_: `fm.package !== contentPackage()` skipped the note,
so an absent `package:` filtered the note out silently and the build still
exited 0. 3.3.0 makes the field optional and derives the package from
`contentPackage`, declining — with a diagnostic, not a silent skip — only a note
that names a _different_ package. The dependency bump therefore ships with the
sweep rather than after it.

Only the `package:` line was removed; no other frontmatter key and no note body
was touched. Compiled pack output is unchanged.
