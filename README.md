# Xinghua Zhao · 赵兴华 — Medical-Device RA & AI Governance

> Open-source, **zero-dependency** tooling for the **full lifecycle of medical-device AI**, organised as a plugin matrix on **LGD** — a declarative, industry-neutral skeleton in which every capability is an independently loadable module. Medical devices are the reference domain; the skeleton itself is industry-neutral and extensible to AI agents, cybersecurity and other verticals.

**Focus:** open-source tooling for medical-device regulatory affairs & AI governance, published as an individual project by [@stevenzhao07](https://github.com/stevenzhao07). Pure technical input, no commercial promotion.

---

## 🧭 Core entry point

- **[medical-ai-toolkit](https://github.com/stevenzhao07/medical-ai-toolkit)** — the **single navigation portal**. It auto-discovers and routes all modules; **start here**.

## 🗂 Project categories

> Repository count verified via GitHub API on **2026-10-13**: **25 public repositories** under `@stevenzhao07`. (The portal README's older "21-repo" figure is outdated and is being corrected in a pending portal PR.)

| Category | Repositories |
|---|---|
| **Portal / profile** | [medical-ai-toolkit](https://github.com/stevenzhao07/medical-ai-toolkit) · [stevenzhao07](https://github.com/stevenzhao07/stevenzhao07) (this repo) |
| **AI governance & trust methodology** | [ai-a3-laws](https://github.com/stevenzhao07/ai-a3-laws) · [ai-governance-checklist](https://github.com/stevenzhao07/ai-governance-checklist) · [ai-model-passport](https://github.com/stevenzhao07/ai-model-passport) · [delivery-guard](https://github.com/stevenzhao07/delivery-guard) |
| **Medical-device lifecycle (QMS / RA)** | [design-controls-toolkit](https://github.com/stevenzhao07/design-controls-toolkit) · [device-regulatory-map](https://github.com/stevenzhao07/device-regulatory-map) · [iec62304-software](https://github.com/stevenzhao07/iec62304-software) · [iso14971-risk-file](https://github.com/stevenzhao07/iso14971-risk-file) · [manufacturing-gmp](https://github.com/stevenzhao07/manufacturing-gmp) · [clinical-evaluation](https://github.com/stevenzhao07/clinical-evaluation) · [biocompatibility-iso10993](https://github.com/stevenzhao07/biocompatibility-iso10993) · [sterilization-validation](https://github.com/stevenzhao07/sterilization-validation) · [pms-vigilance](https://github.com/stevenzhao07/pms-vigilance) · [udi-assignment](https://github.com/stevenzhao07/udi-assignment) · [cybersecurity-medical](https://github.com/stevenzhao07/cybersecurity-medical) |
| **AI / ML tooling** | [ml-validation-toolkit](https://github.com/stevenzhao07/ml-validation-toolkit) · [samd-ra-toolkit](https://github.com/stevenzhao07/samd-ra-toolkit) |
| **Interop / data / labeling** | [fhir-ortho-toolkit](https://github.com/stevenzhao07/fhir-ortho-toolkit) · [omop-ortho-toolkit](https://github.com/stevenzhao07/omop-ortho-toolkit) · [multilingual-ifu](https://github.com/stevenzhao07/multilingual-ifu) |
| **Cross-domain / ecosystem** | [silent-failure-catalog](https://github.com/stevenzhao07/silent-failure-catalog) · [uibc-core](https://github.com/stevenzhao07/uibc-core) · [awesome-healthcare-agents](https://github.com/stevenzhao07/awesome-healthcare-agents) |

## 🤝 How to contribute

- Read the **[Contributing Guide](https://github.com/stevenzhao07/medical-ai-toolkit/blob/main/CONTRIBUTING.md)** (hosted in the portal).
- Pick a task from **[Good First Issues](https://github.com/stevenzhao07/medical-ai-toolkit/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22)** if you are new.
- Open an Issue or PR against the relevant repository. Every change goes through a branch + pull request; **nothing is merged to `main` without review.**
- Report security or regulatory-accuracy concerns via the portal's **[Security policy](https://github.com/stevenzhao07/medical-ai-toolkit/security)**.

## ✅ Verification status — honest convention

We separate four distinct levels and **never conflate them** (the full convention is documented in the project's attribution note, pending a separate PR):

| Tier | Meaning | Current state (2026-10-13) |
|---|---|---|
| 🟢 **CI** | Automated checks pass in GitHub Actions | `medical-ai-toolkit` harness green (last success 2026-10-13 02:55Z; earlier runs same day failed — see portal PR notes) |
| 🟡 **Functional self-test** | Module ships a runnable self-test | Partial — most CLI modules include a self-test path; coverage varies per module |
| 🔵 **Expert review** | Domain-expert sign-off | **Pending** — these are reference implementations, not clinically validated |
| ⚪ **Official source verification** | Regulatory constants traced to a dated official source | Partial — where annotated (e.g. GMP 2025 #107 verified 2026-10-12); others marked "verify before use" |

> ⚠️ **Nothing here is a medical device, a certified regulatory submission, or clinical advice.** Tools output decision-support references; users remain responsible for confirming against current official texts.

## 📄 License

Declared intent: code primarily **Apache-2.0**, **documentation/content under CC BY 4.0** (some reference texts CC0), where a `LICENSE` file is present. Across the account, licenses are **mixed per repository** (Apache-2.0 / CC BY 4.0 / CC0 / MIT) — see each repo's `LICENSE`. A `LICENSE` file for this profile repo is being added in a pending PR; until filed, the license here is proposed, not yet final.

## 🔗 Related / associated accounts

Some repositories originate from or are mirrored with the associated account **[@zhaoxinghua09-cell](https://github.com/zhaoxinghua09-cell)** (e.g. `uibc-core`, `silent-failure-catalog`, `awesome-healthcare-agents`). They are listed here for discoverability but their upstream ownership is noted in each repo's own README.

## 🤖 Attribution & AI assistance

This account and its documentation were produced with AI assistance. The specification for the account reorganisation was drafted with ChatGPT and reviewed by the account owner; execution was performed by a WorkBuddy agent on the owner's machine. AI is assistive only and does not replace domain-expert review or official-source verification. (Full dated disclosure — author, AI-assistance, license, contributor credit, verification convention — is pending a separate PR.)

---

*Maintained by [@stevenzhao07](https://github.com/stevenzhao07) · Last layout update: 2026-10-13.*
