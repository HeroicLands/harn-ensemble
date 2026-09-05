---
"harn-ensemble": minor
---

**The retired top-level `aliases:` field is gone from all 2,517 notes.** It
listed names the bare `[[Alias]]` wikilink form could cite, and that form is
retired — every wikilink is an address now, written `[[type-shortcode|Text]]`.
Nothing else ever read the list.

**Nothing is moved to `name.aliases`, because nothing in the list was a name.**
Every one of the 2,517 values was byte-identical to the note's own
`name.full`. A further 159 notes carried a second value, and those were
catalogue labels rather than sobriquets — `322-1 Ostler` beside a `name.full`
of `Dersory of Talkene`. That code is already carried by the note's filename,
by its `img`, `portrait` and `tokenImg` paths, and the occupation by
`social.occupation`, so deleting it loses nothing.

`name.aliases` is untouched in all 2,517 notes. It is a different key, nested
and reserved, and nothing reads it today.

Deletion only: 5,193 lines removed, none added.
