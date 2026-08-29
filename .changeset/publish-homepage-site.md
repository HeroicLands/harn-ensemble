---
"harn-ensemble": patch
---

Publish the package homepage at `https://www.heroiclands.org/harnensemble/`.

The homepage note already compiled to a page and nothing served it. Four things
close that, and no more: the shared Hugo theme, a Hugo root, a `build:site`
script, and a deploy workflow.

**The theme, not a layout.** `@heroiclands/hugo-theme` 0.2.0 carries
`layouts/partials/landing.html`, the package-landing shape every published
package renders through — selected automatically by the `type: homepage` the
generated `_index.md` declares. Six packages publish one of these, so the shape
lives in the theme and this repository supplies only its own words and
addresses. It ships no CSS and no layout of its own.

**`site/hugo.toml`.** The Hugo root is `site/`, and `content/` beneath it is what
`content-build site` writes — one file, wiped and rewritten on every run.
`publishDir` is `../build/site/harnensemble`, so the deployed tree carries its
own prefix physically: the router proxies `/harnensemble/…` straight through
without rewriting the path, and the same deployment behaves identically at the
hosting project's own address. `baseURL` derives from `contentPackage`
(`harnensemble`), not from the repository name (`harn-ensemble`), and is the one
place the address is written down.

Two settings are there for reasons worth stating. `params.cdnBaseURL` points the
theme at the shared asset host: the theme carries layout, not addresses, so the
header logo and the 404 banner resolve through it, and with it unset they would
resolve against this site — which publishes no imagery and would answer 404 for
both. And `disableKinds` switches off everything that is not the landing: Hugo's
defaults would emit taxonomy roots for `tags` and `categories`, neither of which
this one page authors, plus an RSS feed and a sitemap. In homepage mode that is
not untidiness but a build failure, because the deploy's guard fixes the page
count at exactly one.

`disableKinds` sits above the first table header, and has to. TOML binds a bare
key to the table most recently opened, so the same line written further down —
after `[params]` or `[menu]` — parses as `menu.disableKinds`, which Hugo neither
reads nor rejects. The setting then silently does nothing and the taxonomy roots
come back: three pages, and a red deploy.

**The deploy calls the shared workflow.** The runner, the completeness guard, the
hosting project, the custom domain and the upload are identical for every package
publishing a subtree of www.heroiclands.org, so they live once in
`HeroicLands/.github` and this repository calls them with one input. It passes no
`min-pages` / `max-pages`: in `homepage` mode the shared workflow reads
`publish.site` from `package-build.config.yaml`, fixes the bound at exactly one,
and fails the run if a caller passes either — the bound is a property of what the
package publishes, not a knob. No `_headers` file either; HeroicLands/.github#7
is making the shared workflow supply the default rather than have four
repositories each carry the same six lines.

**How it was verified.** `npm run build:site` runs end to end and writes seven
files under `build/site/`, of which exactly one is an `index.html`:
`harnensemble/index.html` and `harnensemble/404.html`, plus the theme's five
static assets under `css/`, `fonts/` and `img/`. The rendered landing carries the
shared header and nav, the hero band, the whole authored body — the two-systems
table, the manifest URL, the licence — and the shared footer.

That it runs at all is the interesting property, and it is structural rather than
lucky. This repository's packs do **not** compile: it declares no `itemBuilders`
and its beings address the `sohl` and `hm3` catalogues rather than this
package's, so `npm run build:noci` fails at _"Actors compiler requires
`itemsSourceDirs`"_ (HeroicLands/package-build#49, HeroicLands/package-build#58).
That is untouched here and still fails identically. The site build is unaffected
because `buildSite` writes the homepage and returns before the content tree is
ever walked for pages — the same fence that guarantees the one-page bound also
makes the site independent of the pack build.
