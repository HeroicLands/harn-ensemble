---
"harn-ensemble": patch
---

Adopt `@heroiclands/package-build` 4.0.0.

The major carries two retirements, and this repository was already clean for
both. A note declaring `package:` is now a hard build error rather than a
tolerated key (HeroicLands/package-build#56) — the sweep that removed it from
all 2,517 notes landed first, in #1. And the `draft:` capability is **removed
entirely**: rejected on sight, with no reader honouring it
(HeroicLands/package-build#69). Nothing here declared either, so the bump is a
dependency change and no content change.

**How it was verified.** This repository's packs do not compile — a pre-existing
gap, unrelated to the bump: it declares no `itemBuilders`, and its beings'
embedded items address the `sohl` and `hm3` catalogues rather than its own
(HeroicLands/package-build#49, HeroicLands/package-build#58). `build/packs-json`
therefore holds zero documents, and diffing it across the bump would compare two
empty trees.

Verification used a _temporary, uncommitted_ probe configuration instead — one
Item pack and one designated Actor default — which gets the compiler past the
bail so it walks every note and emits per-note diagnostics. That stream is the
check that discriminates, because a silently skipped note emits no note-level
diagnostic at all. Both sides produced **170,756 diagnostics with an identical
md5** (`d8ac4e90b558d18cae6b2b96f4672576`), and the pass-level log lines matched
line for line. The probe configuration was reverted; nothing about it is
committed.

Both new rejections were then confirmed positively, by temporarily giving one
note `package:` and another `draft:`: each produced a located
`file:line:column: error:` diagnostic naming the retired field and what to do
instead. Both edits were reverted.
