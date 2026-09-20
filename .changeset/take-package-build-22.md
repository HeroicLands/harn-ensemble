---
"harn-ensemble": patch
---

The website at `https://www.heroiclands.org/harnensemble/` publishes the
character and affiliation roster — 2,540 pages — for the first time. The
configuration already asked for this, but the build could not reach it: a
missing `systems:` declaration refused the configuration outright before a
single note was read.

**The header navigation is the organisation's shared menu**, fetched at build
time rather than authored here, so it now matches every other
heroiclands.org page rather than the fixed links this site carried before.
