---
"harn-ensemble": minor
---

**This repository moves to `@heroiclands/package-build@^17.0.0`**, seven majors
on from `^10.0.0`, and `assets/content/homepage.md` gains `shortcode: root`.

A `type: homepage` note is an ordinary addressed note since 11.0.0 — published
at `/<package>/homepage-<shortcode>/`, which is where
`[[homepage-<shortcode>|Text]]` lands — so it carries a shortcode like every
other note.

**`lint:addresses` is red on 2,517 findings after this**, and every one is a
note carrying the retired top-level `aliases:` field. None is introduced here:
the field was retired in the toolchain and this tree has not been swept. It is
tracked separately, and `lint:content-links` stays green.
