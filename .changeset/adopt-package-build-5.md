---
"harn-ensemble": patch
---

Adopt `@heroiclands/package-build` 5.0.0, switch `publish.site` to `homepage`,
and author the package homepage.

**The boolean is gone.** `publish.site` is now a mode — `homepage` or `content`
— and both boolean spellings are refused at config load rather than mapped onto
the nearest mode (HeroicLands/package-build#51, HeroicLands/package-build#55).
The refusal is the point: `false` read as _this package has no web presence_,
which now describes no package at all. Every package publishes an authored
homepage at `/<contentPackage>/`, and the mode says how much _else_ goes with
it. This repository's `site: false` becomes `site: homepage` — the floor, and
the whole of what it publishes.

Verified positively before the edit: on 5.0.0 the unchanged `site: false`
produced the documented `TypeError` naming `homepage` as the mode to write.

**A `site:` block, because `out` has no safe default.** 5.0.0 requires
`site.out` in _both_ modes. The output root is wiped on every run, and an unset
value resolves to the repository root — so rather than default it, the build
refuses to continue. `out: site/content` matches the sibling convention in
`sohl-thalorna`, and the directory is gitignored: it is generated, and nothing
in it is authored.

**The homepage.** `assets/content/homepage.md` is a `type: homepage` note — the
whole envelope is that one key, plus an optional `title` this note omits so the
page inherits `packageBuild.manifest.title` ("Ensemble of Hârn NPCs") rather
than restating it. It compiles into no compendium document, appears in no pack
and in no link manifest, and is addressed by the package rather than by its own
name. There was no published page to port, so it was written from `README.md`
and the manifest block: what the module is, the manifest URL Foundry installs
and updates from, the repository, and the licence.

It also states the property that makes this module unusual, and which nothing on
the web previously said: it is the only package in the organisation serving
**two** game systems, shipping `actors-hm3` and `actors-sohl` alongside a
`journals` pack that declares no system at all.

**How it was verified.** By the site build, which is the surface this change
affects. `npx content-build site` exits 0 and reports _"wrote 1 homepage(s) + 0
content page(s) + 0 tree page(s) + 0 landing(s) to site/content"_, emitting
exactly one file — `site/content/_index.md`, carrying the derived `package:
harnensemble` and the inherited title.

That it runs at all is a property of the mode, not luck: `buildSite` collects
homepages and then returns early when the package publishes no content pages,
before the content tree is ever walked. So the site build is independent of this
repository's packs, which do **not** compile — a pre-existing gap untouched
here, and unrelated to the bump: no `itemBuilders` is declared, and the beings'
embedded items address the `sohl` and `hm3` catalogues rather than this
package's (HeroicLands/package-build#49, HeroicLands/package-build#58).
`npm run build:noci` still fails at _"Actors compiler requires
`itemsSourceDirs`"_, exactly as it did before, so a pack diff would prove
nothing.

Formatting is likewise unchanged: `content-build format --check` reports the
same five pre-existing failures under `assets/content/Affiliations/` and no
others — the new note is clean.
