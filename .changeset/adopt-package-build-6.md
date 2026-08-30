---
"harn-ensemble": patch
---

Adopt `@heroiclands/package-build` 6.0.0 — the last of the six content packages
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
