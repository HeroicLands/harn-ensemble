---
"harn-ensemble": minor
---

**This tree's folders are notes, and a note names one by address.**
`assets/content/actor-folders.yaml` is deleted; each of its 17 folders is a
`type: folder` note under `assets/content/Folders/`, and the 2,512 being notes
that named a folder by Foundry id name it by address instead:

```yaml
packFolder: extrasclergy # was: folder: ZVUcnWpJEJxXzWw6
```

**Every folder keeps its authored `id`**, so a world already holding these
folders goes on resolving them. This is a build change, not a world migration.

**Shortcodes are prefixed by their root**, not merely disambiguated. Five of the
seventeen names — Clergy, Mages, Guilded, Unguilded, Nobles — occur under _both_
roots, so a bare name is not an address here. Prefixing only the collisions would
leave `military` and `guards` unqualified and make a later folder of the same
name under the other root a rename, which an address cannot be. The prefixes are
the tree's own abbreviations rather than new coinage: `fff` is what its five
affiliation notes and its `Characters/FFF/` directory already call Friends, Foes,
and Followers, and `extrasserfs` follows `Characters/Extras/Serfs/`.

The five affiliation notes carried an **empty** `folder:`. An empty value is not
an address, so the field is dropped rather than translated — it named no folder
before and names none now.

**Verified by rebuilding the tree either side of the change.** Every one of the
2,497 compiled Actor documents is byte-identical, as are 16 of the 17 folder
documents. The seventeenth, Non-Humans, is not emitted after the change because
the only 15 notes that reference it carry no `sohl:` block, so they compile no
SoHL Actor for it to hold — and a folder note materialises only where something
references it, where the YAML emitted all seventeen unconditionally. That is the
new engine behaviour working as specified, on a tree whose routing is still the
subject of #45.
