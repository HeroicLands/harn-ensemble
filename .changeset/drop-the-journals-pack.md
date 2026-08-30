---
"harn-ensemble": patch
---

Drop the `journals` pack, which had no source and failed every build.

**What was wrong.** `journals` was declared in the initial commit and never had a
note to compile. The journals pass selects a note whose `type` is `doc`, or one
of the doc-carrying types — every item type, plus `macro` and the map types. This
tree holds 2,512 `being` notes, 5 `affiliation` notes and one `homepage` note,
and has held no `doc` note in any commit. The pass therefore walked all 2,518
notes, rejected every one, emitted nothing, and failed:

```text
[ERROR]: Pack "journals" compiled 0 entries from a non-empty content tree.
[ERROR]: Pack JSON generation reported 1 error(s); refusing to compile packs from incomplete output.
```

The compiler was right to refuse. A pack that ships nothing is a pack that should
not be declared, and the empty `assets/content/Journals/` directory — untracked,
so it never reached a clone — was the only thing that ever suggested otherwise.

**Nothing is lost.** A being's `{#appearance}` and `{#dossier}` sections are
rendered into the Actor document itself, so the character prose ships in the
Actor packs, where a reader meets the character. It was never going to appear in
a JournalEntry, whatever `README.md` still says about the original distribution.
`journal-folders.yaml` goes with the pack: it was a verbatim copy of
`actor-folders.yaml`, no pack declared `folders:` to read it, and it can only rot
once the pack it named is gone.

The pack comes back if this module ever ships journal prose of its own — with
notes to fill it, the way the items pack will. Marking it `mayBeEmpty` instead
would have kept the build green while shipping an empty compendium, which is the
kind of silence this repository has had enough of.

**What this does not fix.** The Actor passes still fail — they require
`itemsSourceDirs`, and this package declares no Item pack. That is a separate
defect and a coupling decision, tracked in the same issue.

Refs #21
