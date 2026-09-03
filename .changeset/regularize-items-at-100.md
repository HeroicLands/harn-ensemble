---
"harn-ensemble": patch
---

Fold `sohl.attributes` into `sohl.items`, and restyle every item entry.

**Attributes become items.** `sohl.attributes` was a compact map that the
exporter expanded into `attribute` documents, which meant the character's stats
were the one part of a note spelled in a form nothing else used. They are now
ordinary entries at the top of `sohl.items`:

```yaml
items:
  - { shortcode: str, type: attribute, system: { scoreBase: 16 } }
  - { shortcode: end, type: attribute, system: { scoreBase: 14 } }
```

This is **provably output-preserving**, not merely equivalent-looking:
`sohl/actors.mjs` builds each attribute as
`{system: {scoreBase: Number(value) || 0}}` with type `attribute` and the map key
as shortcode, and pushes them _before_ the `sohl.items` entries. Placing them at
the head of the array emits the same documents in the same order.

It also removes a special case worth removing. The attribute set is not fixed —
`sohl-thalorna` carries anywhere from 3 to 14 — so the map's structural
justification never held, and the compact form could express only `scoreBase`
where `Item.attribute` declares four fields. As items they also pass through the
same emitted-versus-declared check as everything else.

**Every entry is now flow style where it fits.** One line when the rendering is
100 columns or fewer, block style otherwise — which is why the compact form
could be dropped without losing reviewability: an attribute is still one line.

Of 318,030 entries across the trees, **349,361 render in flow and 15,585 in
block**, and the widest flow line is exactly 100.

**Verification.** Every file was parsed before and after and its whole
frontmatter compared against the intended result, refusing rather than writing
on any other difference — **zero refusals across 3,184 files**. `content-build`
then confirms the tree still resolves: 2,517 addresses across 2,518 notes, every
anchor link landing and every qualified address resolving.

Also adopts `@heroiclands/package-build` 9.0.0, whose shared `printWidth` is 100
— the width this restyling is measured against — and sweeps six files that
`content-build format` had left unformatted.

**Bump**

_Patch._ Authoring form only. The compiled documents are identical.
