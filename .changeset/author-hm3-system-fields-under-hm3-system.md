---
"harn-ensemble": patch
---

Author the HM3 system fields under `hm3.system`, and stop stating a being's
species twice.

**2,512 notes: one key deleted, two moved.** `hm3.species` goes; `hm3.sunsign`
and `hm3.move` move under `hm3.system`, the path the compiled document stores
them at. `hm3.attributes` and `hm3.items` are generators — they produce embedded
documents rather than fields — so they stay directly under `hm3:`.

**`hm3.species` was a duplicate, and the compiler already prefers the other
one.** Every being carries both `data.species` and `hm3.species`, and they are
equal on all 2,512 — zero disagreements — ever since #49 moved `traits.species`
onto `data:`. HM3's actor declaration names the shared source explicitly
(`name: "data.species"`, with the in-block key as a legacy fallback), so
`data.species` is what is read and deleting the copy changes no document.

**The sunsign and the movement rate, by contrast, reached nothing at all.**
Neither has a field declaration and neither has a shared source, so the only
route from a note into an HM3 actor's `system` is the verbatim passthrough,
which reads `hm3.system` — a key no note in this tree wrote. Asked directly, the
compiler's own reader returns `{}` for the old position and
`{"sunsign": "ulandus", "move": 15}` for the new one.

**So this change is deliberately not output-preserving.** Every HM3 character
compiled from these notes gains a sunsign and a movement rate it should always
have had. Nothing is lost: the SoHL side is untouched, and the two fields were
being dropped, not stored.

Each file was verified by parsing before and after and comparing the whole
frontmatter against an independently constructed intended result — and the body
byte for byte — refusing to write on any other difference: **0 refusals**.

**Verification.** The packs cannot be the evidence here: this tree still
compiles zero documents (#21, #45), and the compile log is identical before and
after, down to the same 2,519 errors. The content index stands in — all 2,535
records compared field by field. 23 are unchanged, 2,512 differ, and on every
one of those the difference is **exactly four paths**: `hm3.species`,
`hm3.sunsign` and `hm3.move` gone, `hm3.system` arrived, carrying the same
values. No other field of any record moved, `hm3.attributes` included.
`format`, `markdown`, `lint`, `links` and `labels` report identical output
before and after.

The HM3 actors still do not compile — no note declares `hm3.type` (#48) — so
the gained fields cannot yet be shown on a pack entry. That is a separate gap,
and this change is what makes the two fields worth resolving it for.

Closes #51
