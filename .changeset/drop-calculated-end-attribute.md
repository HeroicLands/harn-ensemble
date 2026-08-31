---
"harn-ensemble": patch
---

Drop `hm3.attributes.end` from all 2,512 character notes.

Endurance is calculated in HM3, not stored. The system's data model defines
thirteen abilities — `strength`, `stamina`, `dexterity`, `agility`,
`intelligence`, `aura`, `will`, `eyesight`, `hearing`, `smell`, `voice`,
`comeliness`, `morality` — and every note authored fourteen, the extra one being
`end`. It corresponds to no field, so it was never going to become anything: a
value Foundry discards without a word, which is the failure this content tree's
toolchain has spent a week making impossible to hide.

It surfaced by comparing what the notes author against what the HM3 DataModels
declare, once HM3 began publishing its field sets as data
(HeroicLands/HarnMaster-3-FoundryVTT#443).

**`sohl.attributes.end` is deliberately untouched.** It sits at the same
indentation, in a block that begins fourteen lines away, and holds a _different_
value — but it is not the same thing at all: `sohl/actors.mjs` builds one
embedded attribute item per key, so SoHL's Endurance is a real document that
notes are the source of. Only the HM3 block was edited, and the two are still
2,497 and 0 respectively.

The edit was made textually rather than by rewriting the frontmatter, so each
file's diff is the single removed line and nothing else — verified by parsing
every note before and after and comparing the whole frontmatter with only that
one key removed, and independently by the diff itself: 2,512 files, 2,512
deletions, no insertions, no file with more than one changed line.
