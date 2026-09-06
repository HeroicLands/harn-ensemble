---
"harn-ensemble": minor
---

**This tree's folders are notes** (#40).

`assets/content/actor-folders.yaml` is gone. Each of the 17 folders is a
`type: folder` note under `assets/content/Folders/`, and the 2,517 notes that
named a folder by its Foundry id name it by address instead — 2,512 converted,
and five that carried a valueless `folder:` now carry nothing, which is the same
statement.

**Every folder keeps its authored `id`**, so a world already holding these
folders goes on resolving them — this is a build change, not a world migration.

**The folder file was dead configuration.** No pack declared `folders:`, so it
was never loaded and none of the 17 folders was ever emitted. Under derived
materialisation a folder reaches a pack because something in that pack
references it (HeroicLands/package-build#257), so these folders start working
rather than staying inert.

Requires the folder-note support in `@heroiclands/package-build`
(HeroicLands/package-build#276).
