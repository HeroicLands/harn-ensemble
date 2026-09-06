---
"harn-ensemble": patch
---

Author every SoHL system field under `sohl.system`, at the path the compiled
document stores it at.

**2,502 notes, 7,491 key moves, 2,517 null keys dropped.** The 2,497 being notes
move `body` (and its ten nested paths), `currentMoveMedium` and
`movementProfiles`; the 5 affiliation notes have no non-null system field to
move and only shed dropped keys.

The move list is derived from the field declarations the compiler itself obeys
(`ITEM_FIELDS[type]`'s `name` → `to`), never from a hand-written list, so a note
now says what the document holds and a key it does not declare is an error
rather than a silent drop.

**A key authored as `null` is dropped, not moved.** At the legacy position the
compiler reads `value ?? default`, so `null` never reached a document — a
being's `defaultCombatGroup: null` was omitted from `system` entirely. Moved to
the destination it _would_ arrive, because that position returns the value as
authored. That is 2,517 keys: `defaultCombatGroup` on 2,497 beings, and
`society` / `office` / `title` / `level` on each of the 5 affiliations.

Each file was verified by parsing before and after and comparing the whole
frontmatter against the intended result, refusing to write on any other
difference: 0 refusals, and 0 values normalised.

**No note in this tree carries a content-table query naming a moved field**, so
no column silently stops resolving. `sohl.kbcat` stays put, as do the generators
`sohl.items` and `sohl.attributes`.

**Verification.** `format`, `markdown`, `lint`, `links` and `labels` report
identical findings before and after — same kinds, same counts (170 markdown,
2,513 address findings) — differing only in the line and column numbers that
moving a frontmatter key necessarily shifts. The packs cannot be the evidence
here: this tree still compiles zero documents (#21), so `build/packs-json` is
empty on both sides. The **content index** is emitted from the frontmatter and
is, so it stands in: all 2,535 records compared field by field, every value
under `sohl.system` equal to the value it moved from, exactly 2,517 null keys
gone, and **no other field of any record changed**.
