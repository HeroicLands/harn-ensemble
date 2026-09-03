# Contributing to the Harn Ensemble module

This repository ships the `harn-ensemble` package: **unofficial Hârn fan material**
under [Keléstia's Fan Material Guidelines](https://www.kelestia.com/faq#n86),
distributed as Foundry compendium packs.

## Filing an issue

**This repository tracks its own work.** File Harn Ensemble issues here, not in
any other system repository.

Every issue is classified on four axes — **type**, **priority**, **labels**, and
**milestone**. The standard defines each one, and the issue forms pre-fill the
body shape for the type you pick:

- [Issue Reporting standard](.github/ISSUE_REPORTING.md)
- [Open an issue](https://github.com/HeroicLands/harn-ensemble/issues/new/choose)

Exploitable weaknesses go to a **private advisory**, never a public issue — see
[SECURITY.md](SECURITY.md). A **licence** breach is a public `bug`, not an
advisory.

## Making a change

`main` is protected: it takes no direct pushes. Every change lands through a pull
request.

1. **Find or file the tracking issue.** Pure repo housekeeping (`chore/*`) may skip
   this; anything else gets an issue first, so you have its number for the branch.
2. **Branch off current `main`**, named `<type>/<issue_#>_<short-kebab-summary>` —
   e.g. `feat/12_western-kingdoms`, `bug/19_dead-deity-link`. Issue-free
   housekeeping is `chore/<slug>`.

   **Git refuses a commit on `main`.** Hooks in `.githooks/` — `pre-commit`
   and `pre-merge-commit` — decline it, so the mistake surfaces before the
   commit exists rather than at push time. `npm install` activates them. To
   commit on `main` anyway, `git commit --no-verify`; to opt this checkout out
   entirely, `git config hooks.allowCommitOnMain true`.

3. **Make the change**, keeping it small and focused — one feature, one fix, or one
   documentation improvement per pull request.
4. **Verify it.** `npm run lint` must pass, and `npm run build` must compile every
   note into its pack.
5. **Commit** in Conventional-Commits style, and **open a pull request** with
   `Closes #<n>` and a what/why description.

## Prohibited content

Under no circumstances commit material that the Fan Material Guidelines do not
cover: art, maps, or illustrations owned by Keléstia Productions, Columbia Games,
or any third party; verbatim rulebook text or tables; or trade dress. Game mechanics
may be implemented, but the specific creative expression used to describe them
may not be reproduced. If you are unsure whether material is permissible, ask
before contributing it.
