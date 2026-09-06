---
"harn-ensemble": minor
---

**The top-level `traits:` block is gone from all 2,512 being notes; every field
it carried is authored under `data:` instead.** `traits:` was never a key the
content format declared. Top level is deliberately open — unrecognised keys pass
straight through to Hugo — so nothing checked what was written there: a
misspelling arrived on the page as a theme parameter rather than as a finding.
`data:` is the format's closed container for a note's own type-specific facts,
and `being` declares every one of these fields in it.

Nine fields move verbatim — `gender`, `species`, `age`, `birthday` and the five
`appearance.*` leaves. Three change shape as well as place, because the format
declares them flatter than they were authored:

| authored             | now                                            |
| -------------------- | ---------------------------------------------- |
| `traits.height.m`    | `data.height` — a bare number, still metres    |
| `traits.weight.kg`   | `data.weight` — a bare number, still kilograms |
| `traits.build.frame` | `data.frame` — a property in its own right     |

**No value is rewritten.** Three `frame` values sit outside the vocabulary the
format names — `heavy` on 377 notes, and one each of `huge` and `average` — and
they are carried across exactly as authored. Correcting them is a separate
editorial decision about the material, not part of moving where it is written.

**Nothing downstream changes.** None of these fields is compiled into a Foundry
document, so the packs are unaffected. `lint` reports the same findings in kind
and count, and the published homepage is byte-identical. The rendered being
sidebar is byte-identical too, across all 2,354 pages the tree compiles to —
`@heroiclands/hugo-theme` reads `data:` from HeroicLands/heroiclands-hugo-theme#55
onward, and reads the old block underneath it while the other trees convert.

Conversion only: 12,565 lines added, 20,101 removed, across 2,512 files.
