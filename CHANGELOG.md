# harn-ensemble

## 0.1.0

### Minor Changes

- 102d8ab: **Every build now emits this package's content index.** `build:db` gains
  `build:content-index`, so `build/content-index/harnensemble.jsonl` is produced
  whenever the content is built rather than whenever someone remembers to run the
  command by hand.
  
  Nothing generated it before — in this repository or any other — so the artifact
  existed only where a person had run `content-build content-index` themselves,
  and was as fresh as the last time they did. The editor tooling reads it, and
  compiled JournalEntry links resolve through it, so "as fresh as someone
  remembered" is not a state it can be in.
  
  2518 note(s), and the file lands under `build/`, which is gitignored.
- 5a72a07: **The retired top-level `aliases:` field is gone from all 2,517 notes.** It
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
- 18be69b: **This repository moves to `@heroiclands/package-build@^17.2.0`**, the version
  whose content-index records carry a `foundry` block.
  
  Each record gains the UUID and anchor map the link manifest holds, and an item
  note emits a second record for its documentation journal — a document in its own
  right, with its own canonical address, so it is addressable by the same lookup
  as anything else rather than nested inside the item's record.
  
  `build/content-index/harnensemble.jsonl` is already emitted on every build; this is
  what makes it carry Foundry addresses as well as content.
  
  Verified: 2,518 records, all beings, which carry no documentation entry by design.
- 7c3a42d: **This repository moves to `@heroiclands/package-build@^17.0.0`**, seven majors
  on from `^10.0.0`, and `assets/content/homepage.md` gains `shortcode: root`.
  
  A `type: homepage` note is an ordinary addressed note since 11.0.0 — published
  at `/<package>/homepage-<shortcode>/`, which is where
  `[[homepage-<shortcode>|Text]]` lands — so it carries a shortcode like every
  other note.
  
  **`lint:addresses` is red on 2,517 findings after this**, and every one is a
  note carrying the retired top-level `aliases:` field. None is introduced here:
  the field was retired in the toolchain and this tree has not been swept. It is
  tracked separately, and `lint:content-links` stays green.

### Patch Changes

- e7dc0ed: Adapt the issue-reporting standard and the label registry to this repository, and
  give the package homepage a `site` label.
  
  `.github/ISSUE_REPORTING.md` and `.github/labels.yml` arrived as copies from
  `sohl-kethira-basic` and were never adapted. They are the two documents a
  contributor reads before filing, and they described a different repository: the
  document was titled `Issue Reporting — sohl-kethira-basic`, the `content` label
  read _"Kethira material"_ on a repository holding Hârn NPCs, and §9's "which
  repository" table listed this repository nowhere while naming `sohl-kethira-basic`
  as "**This repository**".
  
  **One claim had become actively false.** Both files reasoned from _"this
  repository ships Foundry compendium packs and nothing else — no system code, no
  test suite, and no site"_ to the conclusion that the `site` label is absent. The
  homepage work removed the premise: `publish.site` is `homepage`, and the package
  publishes a page at `https://www.heroiclands.org/harnensemble/` that is built and
  deployed from here. Because the registry is a **closed set** — `labels-sync`
  deletes any label not listed — that stale reasoning did not merely misdescribe the
  repository, it prevented a label existing for work the repository actually does.
  So `site` is added, and the reasoning is rewritten to say why `system`, `tests`
  and `thalorna` are still absent and why `site` no longer is.
  
  **Also corrected, all repository-specific claims rather than process:**
  
  | Claim                                                      | Was                     | Now                                                                  |
  | ---------------------------------------------------------- | ----------------------- | -------------------------------------------------------------------- |
  | Registry/table are kept in sync by `npm run lint:labels`   | asserted in both files  | stated as kept in step by hand — no such script exists here          |
  | `documentation` label covers `CLAUDE.md`                   | asserted                | dropped; this repository has no `CLAUDE.md`                          |
  | Bug reports name a "SoHL system version"                   | asserted                | game system and version, `hm3` or `sohl` — the module ships both     |
  | Work here was tracked in `Song-of-Heroic-Lands-FoundryVTT` | a "historical note"     | removed; it was never true of this repository                        |
  | §9 repository table                                        | omitted this repository | lists it first, plus `harn-adventures` and `HarnMaster-3-FoundryVTT` |
  
  The carve-out note is restated for this module's own licensing — Keléstia's Fan
  Material Guidelines, CC BY-NC-SA 4.0 — and now distinguishes the content, which is
  never published, from the homepage, which is. The worked examples are re-cast in
  this repository's material.
  
  The registry's header also now records GitHub's 100-character cap on a label
  description. The labels action checks it in `check` mode, so an over-long one
  fails the pull request rather than the sync — a fact worth writing down where
  the next person editing a description will read it.
  
  The four-axis standard itself is untouched: types, priorities, milestones and the
  label-registry mechanism are org-wide and were already correct.
- 2266403: Adopt `@heroiclands/package-build` 4.0.0.
  
  The major carries two retirements, and this repository was already clean for
  both. A note declaring `package:` is now a hard build error rather than a
  tolerated key (HeroicLands/package-build#56) — the sweep that removed it from
  all 2,517 notes landed first, in #1. And the `draft:` capability is **removed
  entirely**: rejected on sight, with no reader honouring it
  (HeroicLands/package-build#69). Nothing here declared either, so the bump is a
  dependency change and no content change.
  
  **How it was verified.** This repository's packs do not compile — a pre-existing
  gap, unrelated to the bump: it declares no `itemBuilders`, and its beings'
  embedded items address the `sohl` and `hm3` catalogues rather than its own
  (HeroicLands/package-build#49, HeroicLands/package-build#58). `build/packs-json`
  therefore holds zero documents, and diffing it across the bump would compare two
  empty trees.
  
  Verification used a _temporary, uncommitted_ probe configuration instead — one
  Item pack and one designated Actor default — which gets the compiler past the
  bail so it walks every note and emits per-note diagnostics. That stream is the
  check that discriminates, because a silently skipped note emits no note-level
  diagnostic at all. Both sides produced **170,756 diagnostics with an identical
  md5** (`d8ac4e90b558d18cae6b2b96f4672576`), and the pass-level log lines matched
  line for line. The probe configuration was reverted; nothing about it is
  committed.
  
  Both new rejections were then confirmed positively, by temporarily giving one
  note `package:` and another `draft:`: each produced a located
  `file:line:column: error:` diagnostic naming the retired field and what to do
  instead. Both edits were reverted.
- f305908: Adopt `@heroiclands/package-build` 5.0.0, switch `publish.site` to `homepage`,
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
- 92990d6: Adopt `@heroiclands/package-build` 6.0.0 — the last of the six content packages
  still on 5.x.
  
  `^5.0.0` → `^6.0.0`, resolved in the lockfile as **6.0.0**. That is the only
  entry the lockfile moves: 6.0.0 declares the same nineteen dependencies at the
  same ranges as 5.0.0, so nothing transitive moves: the lockfile holds the same
  393 entries before and after, and only that one package's version, tarball URL
  and integrity hash change.
  
  **Nothing this repository emits changes.** Every pass was run on the same tree
  at 5.0.0 and at 6.0.0 and the emitted trees compared by content hash rather than
  by counts: **337 files, 13 directories, every SHA-256 identical**, with no file
  added or removed. Each pass's log is identical too, modulo its timestamp. The
  337 are 335 staged assets, the generated `module.json` (15 keys, 3 packs) and
  the one emitted homepage — because **no pack compiles here**, a pre-existing gap
  untouched by this bump and unrelated to it (HeroicLands/package-build#49,
  HeroicLands/package-build#58). `build:noci` fails at _"Actors compiler requires
  `itemsSourceDirs`"_ on both versions, with byte-identical output, as it has
  since before 4.0.0.
  
  **`packFolders` is clean, and the check was proved to fire rather than merely
  observed silent** (HeroicLands/package-build#81). The one declared folder names
  all three shipped packs, so the manifest writes with no finding. Silence is weak
  evidence on its own, so each severity was forced by a throwaway edit to
  `package-build.config.yaml` and the file restored byte-identically:
  
  ```text
  package-build.config.yaml:76:21: error: packFolders: folder "Hârn Ensemble" names pack
    "nosuchpack", which this package does not ship (packs: actors-hm3, actors-sohl, journals)
                                                                                      (exit 1)
  
  package-build.config.yaml:69:13: warning: packFolders: pack "journals" is named by no folder,
    so it ships outside every folder this package declares                            (exit 0)
  ```
  
  Both severities behave as documented — an unresolvable name is fatal and
  `build/stage/module.json` is **not** written; an ungrouped pack warns and the
  manifest still writes — and both diagnostics carry the line and column of the
  offending scalar.
  
  **`isEquipped` was measured, not reasoned about**
  (HeroicLands/package-build#68). This package ships 2,518 notes, so its shape
  settles nothing. Measured: the compiled output holds **0 documents** and
  therefore **0 `isEquipped` keys**, on both versions — no pack compiles. The
  string appears **0 times** in the source tree as well, which is expected: the
  field was never authorable. The change is latent rather than irrelevant, though.
  The tree's beings reference **66,957** embedded items of the six types
  `GEAR_COMMON` is spread into — 29,427 `armorgear`, 19,291 `miscgear`, 10,064
  `containergear`, 8,078 `weapongear`, 81 `projectilegear`, 16 `concoctiongear` —
  so when the actors packs do compile, they will resolve against a foreign
  catalogue whose share of the key clears only when its upstream republishes.
  
  **No "order is load-bearing" claim exists here to correct**
  (HeroicLands/package-build#73). Grepped across the whole repository, not just
  the configuration: the `packs:` list carries no comment about ordering, and no
  document in the tree makes the claim. The derived order also matches the
  declared one — the build logs a derived order only when it differs, and logged
  none — which is unsurprising, since this package declares no Item pack for the
  actors passes to wait on.
  
  **The homepage's own links are checked now** (HeroicLands/package-build#54), and
  `assets/content/homepage.md` passes: `content-build links` gains the clause
  _"every homepage address resolvable"_. Every link on that page is external —
  GitHub and Creative Commons — which the check deliberately does not resolve, so
  it has nothing to reject; the clause was confirmed live by breaking it twice.
  `content-build lint` gains its missing noun in the same release
  (HeroicLands/package-build#77) — _"2517 address(es) across 2518 note(s)"_. Those
  two summary lines are the only observable difference the bump produces.
  
  **#75 has nothing to reach.** The configuration declares no
  `site.passOptions.symbolMap` and this repository has no API documentation, so
  the reversed licence in that change cannot bite it.
  
  The pre-existing lint backlog is unchanged, as required: `lint:format` reports
  the same 5 unformatted files under `assets/content/Affiliations/` and
  `lint:markdown` the same 170 findings, both byte-identical to their 5.0.0
  output. Only the denominator moves, 2,549 files to 2,550, for the changeset this
  paragraph is in. The two checks the pull-request gate
  actually runs — `lint:addresses` and `lint:content-links` — are green across all
  2,518 notes.
- 90a599b: Adopt package-build 7.0.0.
  
  `stats.systemId` was removed from this repository's configuration because
  7.0.0 derives it (HeroicLands/package-build#48) — but the pin was still
  `^6.1.0`, where the key is merely _optional_. Under 6 the deletion resolves
  to `systemId: null` beside a real `systemVersion`: a version stamped with no
  id, silently, which is the "plausible lie" the upstream change exists to
  prevent.
  
  ```text
  under ^6.1.0, systemId deleted: { "systemId": null, "systemVersion": "0.8.2" }
  ```
  
  Bumping the pin closes the window. Verified: every pack stamps exactly the
  `systemId` and `systemVersion` it stamped before the deletion.
- dc0e701: Drop `hm3.attributes.end` from all 2,512 character notes.
  
  Endurance is calculated in HM3, not stored. The system's data model defines
  thirteen abilities — `strength`, `stamina`, `dexterity`, `agility`,
  `intelligence`, `aura`, `will`, `eyesight`, `hearing`, `smell`, `voice`,
  `comeliness`, `morality` — and every note authored fourteen, the extra one being
  `end`. It corresponds to no field, so it was never going to become anything: a
  value Foundry discards without a word, which is the failure this content tree's
  toolchain has spent a week making impossible to hide.
  
  It surfaced by comparing what the notes author against what the HM3 DataModels
  declare, once HM3 began publishing its field sets as data
  (HeroicLands/HarnMaster-3-FoundryVTT#443).
  
  **`sohl.attributes.end` is deliberately untouched.** It sits at the same
  indentation, in a block that begins fourteen lines away, and holds a _different_
  value — but it is not the same thing at all: `sohl/actors.mjs` builds one
  embedded attribute item per key, so SoHL's Endurance is a real document that
  notes are the source of. Only the HM3 block was edited, and the two are still
  2,497 and 0 respectively.
  
  The edit was made textually rather than by rewriting the frontmatter, so each
  file's diff is the single removed line and nothing else — verified by parsing
  every note before and after and comparing the whole frontmatter with only that
  one key removed, and independently by the diff itself: 2,512 files, 2,512
  deletions, no insertions, no file with more than one changed line.
- e38a62f: Drop the `journals` pack, which had no source and failed every build.
  
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
- 964b06c: Lint the content tree: add the `lint` and `format` scripts this repository never
  had, and gate pull requests on the two checks that pass today.
  
  This repository defined no `lint` and no `format` script at all, so its 2,518
  notes — the largest content tree in the organisation — were validated by
  nothing. HeroicLands/package-build#36 named this case exactly: a repository that
  ships no website must still lint its notes, or the carve-out repository silently
  opts out of validation. This one ships no site (`publish.site: homepage`
  publishes one authored page and nothing the content tree compiles to), and it is
  that case.
  
  **Six scripts, each a thin call into the installed toolchain.** Nothing here is
  new tooling; `@heroiclands/package-build` already provides all of it, and the
  sibling content repositories call it the same way, under the same names, so the
  script surface is one surface everywhere:
  
  | script               | command                        | what it checks                                  |
  | -------------------- | ------------------------------ | ----------------------------------------------- |
  | `lint:format`        | `content-build format`         | the shared Prettier configuration               |
  | `format`             | `content-build format --write` | rewrites what `lint:format` reports             |
  | `lint:markdown`      | `content-build markdown`       | the shared markdownlint rule set                |
  | `lint:markdown:fix`  | `content-build markdown --fix` | applies the fixes markdownlint can make         |
  | `lint:addresses`     | `content-build lint`           | every note's address and frontmatter            |
  | `lint:content-links` | `content-build links`          | every anchor link lands, every address resolves |
  | `lint`               | `run-s` over the four checks   | —                                               |
  
  **Two of the siblings' scripts are deliberately absent.** `lint:lang` checks a
  `lang/` directory, and this repository has none — it ships content, not code.
  `lint:labels` is a local `utils/check-labels.mjs`, not a toolchain call, and the
  label registry it would read is itself an unadapted copy (#9); wiring it here
  would gate on a known-wrong file.
  
  **The baseline, recorded rather than repaired.** A lint change that also edits
  content can be reviewed as neither, so no note is modified. Measured on this
  commit:
  
  | check                | result                                                                                   |
  | -------------------- | ---------------------------------------------------------------------------------------- |
  | `lint:addresses`     | **clean** — 2,517 addresses across 2,518 notes                                           |
  | `lint:content-links` | **clean** — every anchor lands, every qualified address resolves                         |
  | `lint:format`        | **5 findings** — all five notes under `assets/content/Affiliations/`                     |
  | `lint:markdown`      | **170 findings** in 161 files — 168 `MD034/no-bare-urls`, 2 `MD024/no-duplicate-heading` |
  
  The bare URLs are overwhelmingly one shape in one place: 148 of them are in
  `assets/content/Characters/FFF/v1`, a further 15 in `.../FFF/part-13`. Four are
  in `README.md` and the rest are stragglers. That is a mechanical backlog, and
  `lint:markdown:fix` exists to clear it — in its own change.
  
  **CI gates the green half, and only the green half.** A `Lint` workflow now runs
  on every pull request, calling `lint:addresses` and `lint:content-links`. It does
  not call `npm run lint`, because the chain is red on the 175 findings above and a
  gate that cannot go green is worse than no gate — it teaches everyone to merge
  past a red check. The two it does run pass clean today and guard what this
  repository actually is: the addresses its documents are cited by, and the links
  between them. Those are the failures that corrupt a build silently; formatting
  and bare URLs are ugly and harmless. When the backlog clears, both steps collapse
  into one `npm run lint`.
  
  **`build:noci` is left alone.** The sibling repositories run `lint` as its first
  stage, and this one should end up there too — but it does not build at present
  for an unrelated reason (it declares no `itemBuilders` and its beings address the
  `sohl` and `hm3` catalogues, so the pack compile fails at _"Actors compiler
  requires `itemsSourceDirs`"_ — HeroicLands/package-build#49 and #58). Prepending
  a red gate to an already-red build moves the failure without fixing either, and
  would mask the compile error behind a lint error. It joins the chain when both
  are green.
  
  Worth noting while it is in view: `release.yml` already claims `build:noci` "runs
  the lint chain and the pack compile". Until now it ran neither — that sentence,
  like the job's `Version and release sohl-kethira-basic` name, arrived with the
  workflow rather than describing this repository.
- 55b6138: Publish the package homepage at `https://www.heroiclands.org/harnensemble/`.
  
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
- 96e802d: Read the output name `changesets/action@v2` actually emits, so the release
  workflow can cut a release at all.
  
  `release.yml` pins `changesets/action@v2` and read a **v1** output name.
  `changesets/action` renamed every output to kebab-case at v2:
  
  | v1                  | v2                   |
  | ------------------- | -------------------- |
  | `hasChangesets`     | `has-changesets`     |
  | `publishedPackages` | `published-packages` |
  | `pullRequestNumber` | `pr-number`          |
  | `published`         | `published`          |
  
  GitHub evaluates a nonexistent property to the empty string rather than
  failing, so `steps.changesets.outputs.hasChangesets == 'false'` was
  `'' == 'false'` — always false. "Decide whether to release" never ran, its
  `release` output was never set, and every step gated on it was skipped. The job
  reported green while producing nothing, which is the worst property of the
  defect: the repository has **no tags and no Releases at all**, and nothing said
  so.
  
  **The whole audit, not just the one name.** Every `steps.<id>.outputs.*`
  reference in the repository was checked against the manifest of the major it
  reads. There are seven, in this one file: the one corrected here, and six
  `steps.decide.outputs.release` / `.tag` references that read a `run` step's own
  `$GITHUB_OUTPUT` writes and were already right. The other three workflows
  reference no step outputs.
  
  **The duplicate-release guard now works for the case it was written for.** Its
  second half — "this version is not already tagged" — has never executed, because
  the first half never let it. `git ls-remote --exit-code` reports `0` for a match
  and `2` for no match, but any other status is a _failed lookup_: `128` for an
  unreachable or unauthenticated remote. The old `if` treated every non-zero
  status alike, so a transient network failure would have read as "untagged" and
  re-released a version that is already released — and because
  `softprops/action-gh-release` updates an existing release rather than refusing,
  that would have overwritten it silently. Only `2` is now allowed to mean the tag
  is absent; anything else fails the step.
  
  Two comments carried over from `sohl-kethira-basic` and were false here: this
  repository has no hand-cut tags up to `v0.5.3` to inherit — it has never
  released — and the comment above the step named the v1 output.
  
  _The publish half of this path cannot be exercised without cutting a real
  release, so it stays untested by construction. What to watch on the first run is
  recorded on the pull request._
- dfdf204: Fold `sohl.attributes` into `sohl.items`, and restyle every item entry.
  
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
- 8d7775f: Route this repository's private security reports and issue-standard links to this
  repository, and add the `SECURITY.md` that `CONTRIBUTING.md` already links.
  
  `.github/ISSUE_TEMPLATE/` arrived as a copy from `sohl-kethira-basic` and was
  never adapted, so the issue chooser addressed a different repository. With
  `blank_issues_enabled: false` the chooser is the only entry point, which made
  the misrouting unavoidable rather than merely available.
  
  **The security link sent advisories to the wrong repository.** "Report a security
  vulnerability (private)" pointed at
  `HeroicLands/sohl-kethira-basic/security/advisories/new`. A reporter following
  this repository's own documented private-disclosure path filed their advisory
  against the Kethira module, where it is not about that codebase and where a
  different set of watchers receives it. It now points here.
  
  **Corrected in the same directory, same cause:**
  
  | File                                | Was                                                | Now                                |
  | ----------------------------------- | -------------------------------------------------- | ---------------------------------- |
  | `config.yml`                        | advisories at `sohl-kethira-basic`                 | advisories here                    |
  | `config.yml`                        | _"This tracker is for the Kethira content module"_ | describes the Harn Ensemble module |
  | `epic.yml`, `spike.yml`, `task.yml` | issue standard at `sohl-kethira-basic/blob/main/…` | this repository's own copy         |
  
  **The chooser now routes both systems.** The module ships an Actor pack for
  `hm3` as well as one for `sohl`, so a reporter whose defect is really in the
  game system had one destination where the package has two. The existing
  Song of Heroic Lands entry is unchanged and a HarnMaster 3 entry sits beside it.
  
  **`SECURITY.md` is added.** `CONTRIBUTING.md` links `SECURITY.md` and no such
  file existed, so the link 404'd; both sibling content repositories carry one and
  the organization publishes no default. Its scope section is written for what this
  repository actually ships — journal and actor packs, no application code — and it
  points a system-level weakness at the two systems' own advisories.
  
  Left alone deliberately: the Song of Heroic Lands system tracker and the Discord
  link, which correctly address other places, and every `HeroicLands/.github`
  reference in the workflows, which is the shared organization repository.
  
  _Enabling private vulnerability reporting is a repository **setting**, not a file,
  and it is currently off here — so the corrected link is necessary but not
  sufficient until it is turned on in Settings → Advanced Security._
- ef4cb0b: Strip the retired `package:` frontmatter key from every content note.
  
  All 2517 notes under `assets/content/` declared `package: harnensemble` — the
  same value every time, because this repository authors exactly one package's
  content. A note's package is now the repository's configured `contentPackage`,
  so restating it per note is redundant.
  
  **Why it needed `@heroiclands/package-build` 3.3.0 first.** On 3.2.0 and earlier
  the field was a _selector_: `fm.package !== contentPackage()` skipped the note,
  so an absent `package:` filtered the note out silently and the build still
  exited 0. 3.3.0 makes the field optional and derives the package from
  `contentPackage`, declining — with a diagnostic, not a silent skip — only a note
  that names a _different_ package. The dependency bump therefore ships with the
  sweep rather than after it.
  
  Only the `package:` line was removed; no other frontmatter key and no note body
  was touched. Compiled pack output is unchanged.
