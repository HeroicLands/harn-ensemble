---
"harn-ensemble": patch
---

Declare `systems:` for `hm3` and `sohl` so `packs.actors-hm3.system` and
`packs.actors-sohl.system` resolve to a stamped version instead of refusing
the configuration outright. Every compiled Actor now carries a real
`_stats.systemId` and `systemVersion` instead of never compiling at all, and
`content-build lint` reaches the notes themselves rather than aborting first.
