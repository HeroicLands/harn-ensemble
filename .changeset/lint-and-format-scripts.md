---
"harn-ensemble": patch
---

Lint the content tree: add the `lint` and `format` scripts this repository never
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
