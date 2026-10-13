# Contributing to the Medical-AI Toolkit

Thanks for considering a contribution. This guide is shared across all `@stevenzhao07` medical-AI repositories.

## 1. Before you start

- **Check [GOOD_FIRST_ISSUES.md](./GOOD_FIRST_ISSUES.md)** if you are new — these are scoped, claimable tasks.
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

We separate four levels and never conflate them (see `PROJECT_ATTRIBUTION.md`):

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

- By contributing, you agree your contribution is licensed under the repo license (**Apache-2.0** code / **CC BY 4.0** content).
- You will be credited in the module README's contributor list and in release notes.
- Maintainers may request a short CLA confirmation for large contributions.

## 6. Code of conduct

All participants must follow [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md).
