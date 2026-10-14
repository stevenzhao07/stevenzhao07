# Contributing to the Medical-AI Toolkit

Thanks for considering a contribution. This guide is shared across all `@stevenzhao07` medical-AI repositories.

## 1. Before you start

- **Check the [portal issue tracker](https://github.com/stevenzhao07/medical-ai-toolkit/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22)** if you are new — look for issues labelled `good first issue` (scoped, claimable tasks).
- **Search existing Issues/PRs** to avoid duplication.
- For anything touching **regulatory content, medical-risk logic, or license/IP**, open an Issue first and wait for maintainer confirmation. We do not accept silent changes to those areas.

## 2. Branch & PR workflow (mandatory)

> **No direct pushes to `main`.** Every change goes through a branch + pull request.

```bash
# 1. fork or branch from main
git checkout -b fix/<short-name>        # or feature/<name> / docs/<name>

# 2. make your change, keep it focused

# 3. run the module self-test if one exists
python <module>.py --selftest

# 4. open a PR against stevenzhao07/<repo>:main
```

- PR title prefix: `fix:` / `feat:` / `docs:` / `test:` / `chore:`.
- Fill the PR template checklist — especially the **verification tier** you can honestly claim.

## 3. Verification tiers — claim only what you did

We separate four levels and never conflate them (see the project's attribution note for the full convention, pending a separate PR):

- 🟢 **CI** — automated checks pass in GitHub Actions.
- 🟡 **Functional self-test** — you ran the module's own self-test and it passed.
- 🔵 **Expert review** — a domain expert signed off (rare; most code is *not* yet expert-reviewed).
- ⚪ **Official source verification** — a regulatory constant is traced to a dated official source.

Do **not** mark 🔵 or ⚪ unless it is actually true. When unsure, write "⚠️ 待核实 (verify before use)".

## 4. Code conventions

- **Zero external dependencies** for tool modules (Python standard library only) unless the repo explicitly allows otherwise.
- Keep CLIs runnable offline.
- Add/extend a `--selftest` path for any logic change.
- Bilingual (English + 中文) docstrings/comments are welcome but not required.

## 5. License & contributor credit

- By contributing, you agree your contribution is licensed under the repository's own `LICENSE`. Across the account the licenses are **mixed per repository** (Apache-2.0 / CC BY 4.0 / CC0 / MIT) — see each repo's `LICENSE` for the authoritative terms.
- You will be credited in the module README's contributor list and in release notes.
- Maintainers may request a short CLA confirmation for large contributions.

## 6. Code of conduct

All participants must follow this repository's [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md).
