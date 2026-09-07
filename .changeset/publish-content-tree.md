---
"harn-ensemble": patch
---

Publish the content tree at `https://www.heroiclands.org/harnensemble/`, not just
the homepage.

`publish.site` moves from `homepage` to `content`, and `site.sections` names the
two sections the tree publishes. That is the whole of the behavioural change —
one key and one block, with no new script, workflow input or dependency. A second
file changes comments only, noted at the end.

**Why the tree and not only the page.** A note here is an NPC and its properties
— a name, an occupation, the numbers a GM reads off at the table — and a roster
of two and a half thousand of those is a reference work. It is as useful on the
web as it is in a compendium, and the previous comment's reasoning (that nothing
in this tree is meant for the web) held only while the module was the sole thing
that shipped. The mode is also the switch the release PDF is fenced behind
(HeroicLands/package-build#316), so publishing the pages and publishing the
document stay one decision rather than two that could come to disagree.

**Where a page lands.** `publish.address` is absent, so the prefix keeps its
default `""` — this package's content _is_ its site, so the tree mounts at the
package root and a page publishes at `/harnensemble/<type>-<shortcode>/` rather
than under a subdirectory.

**Two sections, declared so their landings have titles.** A section is a note's
own `type` (`sectionOf`), not a directory name, so `sections` names `being`
(2,512 notes, titled _Characters_) and `affiliation` (5, titled _Affiliations_).
A section left undeclared still gets a landing, but an untitled one, so
`/harnensemble/being/` would answer with an unnamed directory listing instead of
a titled index. The 17 `folder` notes are structure for the compendium, not
pages, and address nothing on the web — they are deliberately absent.

**The deploy changes only its comments.** `deploy-site.yml` passes no `min-pages`
/ `max-pages` and never did — the shared workflow reads `publish.site` from
`package-build.config.yaml` and derives the bound itself — so the page count
follows the mode with no input to update. What did need updating is what the file
_said_: its header called this deployment the package's homepage, and its
comment asserted `publish.site` is `homepage` and the bound therefore exactly
one. Both are now false, so both are gone; the remaining note states the general
rule without restating a mode this file does not own.

Part of #53
