---
"harn-ensemble": patch
---

Author the template-priority number as `data.templatePriority` rather than
`archetype`, the name it shared with an unrelated idea (package-build#266).

**2,502 notes, one key each, the value unchanged.** `sohl.archetype: N` becomes
a top-level `data.templatePriority: N` — the position the compiler specifies,
and the one both system blocks read.

**It is one statement now, not a SoHL-only one.** At its old in-block position
the number was read only for the block it sat in, so 2,497 dual-system notes
told SoHL they were templates and told HârnMaster nothing. At the shared
position both read it, so an HM3 document that compiles from one of these notes
will carry the priority it always meant.

**Verification.** The packs cannot be the evidence: this tree still compiles
zero documents (#21, #45), so `build/packs-json` is empty on both sides. The
content index stands in — all 2,535 records compared field by field, and on
every one the only change is `archetype` leaving `sohl` and `templatePriority`
arriving under `data` **with the same value**; nothing else moved. Resolving the
priority through the compiler's own reader gives an identical answer on all
2,535 notes for the SoHL block. `format` is clean and the address check now
exits 0, down from 2,502 errors to advisory findings only.
