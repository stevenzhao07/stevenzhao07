# Xinghua Zhao — medical-device RA & AI governance

Open-source, zero-dependency tooling for the **full lifecycle of medical-device AI**, organised as a plugin matrix on **LGD**. Medical devices are the reference domain; the skeleton is industry-neutral.

[![License: Apache-2.0 / CC BY 4.0 / CC0](https://img.shields.io/badge/license-Apache--2.0%20%7C%20CC%20BY%204.0%20%7C%20CC0-blue)](#licence)
[![Modules](https://img.shields.io/badge/modules-21-brightgreen)](https://github.com/stevenzhao07/medical-ai-toolkit)
[![Contract](https://img.shields.io/badge/contract-lgd--skeleton%2F1.0-purple)](https://github.com/stevenzhao07/medical-ai-toolkit)
[![Dependencies](https://img.shields.io/badge/third--party%20deps-none-success)](https://github.com/stevenzhao07/medical-ai-toolkit)

**Portal and routing table:** [medical-ai-toolkit](https://github.com/stevenzhao07/medical-ai-toolkit) · [live site](https://stevenzhao07.github.io/medical-ai-toolkit/)

## What this account is

I work in medical-device registration (RA) and AI governance, and publish the parts of that work that are generalisable as open modules: regulatory mappings, quality-system structures, validation gates, and interoperability profiles. Every repository is a pure technical contribution — zero third-party dependencies, runnable offline, auditable years later. MedXpert is disclosed as an affiliation, not promoted as a product.

## The matrix — 21 repositories

**AI-governance layer (9)**

| Repository | Covers | Standards referenced |
|---|---|---|
| [samd-ra-toolkit](https://github.com/stevenzhao07/samd-ra-toolkit) | SaMD/AIaMD registration and quality system | NMPA · EU MDR · FDA · PMDA · IEC 62304 · ISO 14971 |
| [ai-governance-checklist](https://github.com/stevenzhao07/ai-governance-checklist) | Governance self-check; model/data cards | — |
| [ai-a3-laws](https://github.com/stevenzhao07/ai-a3-laws) | Runtime constraints: authority / autonomy / accountability | — |
| [ai-model-passport](https://github.com/stevenzhao07/ai-model-passport) | Model identity, provenance, verification | — |
| [fhir-ortho-toolkit](https://github.com/stevenzhao07/fhir-ortho-toolkit) | UDI profiles for HL7 FHIR R4 | HL7 FHIR R4 |
| [omop-ortho-toolkit](https://github.com/stevenzhao07/omop-ortho-toolkit) | Concept-set and ETL toward OMOP | OHDSI OMOP CDM v5.4 |
| [ml-validation-toolkit](https://github.com/stevenzhao07/ml-validation-toolkit) | Performance, calibration, subgroup fairness | — |
| [delivery-guard](https://github.com/stevenzhao07/delivery-guard) | 17 pre-delivery gates; dual SHA-256 provenance | — |
| [multilingual-ifu](https://github.com/stevenzhao07/multilingual-ifu) | IFU template in 14 language versions | — |

**Device-lifecycle layer (11)**

| Repository | Stage | Standards referenced |
|---|---|---|
| [design-controls-toolkit](https://github.com/stevenzhao07/design-controls-toolkit) | Design controls | ISO 13485 §7.3 · 21 CFR 820.30 · IEC 62366-1 |
| [iso14971-risk-file](https://github.com/stevenzhao07/iso14971-risk-file) | Risk management | ISO 14971 · TR 24971 |
| [iec62304-software](https://github.com/stevenzhao07/iec62304-software) | Software lifecycle | IEC 62304 (A/B/C, SOUP) |
| [device-regulatory-map](https://github.com/stevenzhao07/device-regulatory-map) | Classification and route mapping | NMPA · EU MDR · FDA · PMDA |
| [clinical-evaluation](https://github.com/stevenzhao07/clinical-evaluation) | Clinical evaluation | MDR Art.61 · MDCG · CER + PMCF |
| [biocompatibility-iso10993](https://github.com/stevenzhao07/biocompatibility-iso10993) | Biocompatibility | ISO 10993-1 |
| [sterilization-validation](https://github.com/stevenzhao07/sterilization-validation) | Sterilisation and cleaning | ISO 11135 · 11137 · 17665 |
| [manufacturing-gmp](https://github.com/stevenzhao07/manufacturing-gmp) | Production quality | GMP 2025 revision · IQ/OQ/PQ |
| [udi-assignment](https://github.com/stevenzhao07/udi-assignment) | UDI assignment | GS1 · HIBCC · ICCBBA · 21 CFR 830 · EUDAMED |
| [pms-vigilance](https://github.com/stevenzhao07/pms-vigilance) | Post-market surveillance | NMPA Order No.1 & No.29 · MDR Art.87 |
| [cybersecurity-medical](https://github.com/stevenzhao07/cybersecurity-medical) | Cybersecurity | IEC 81001-5-1 · SBOM · STRIDE |

**Portal (1)** — [medical-ai-toolkit](https://github.com/stevenzhao07/medical-ai-toolkit): routing, machine-discoverable manifests, self-test harness.

## LGD

LGD is the governance framework underneath the matrix: an industry-neutral core (`router.py`, `harness.py`, `config/`) plus pluggable domain modules described by a declarative `module.json`. The medical matrix is the worked example, not the boundary — the ordering, the gates and the audit trail are the reusable parts. A worked non-medical example lives in [`examples/domains/legal-compliance`](https://github.com/stevenzhao07/medical-ai-toolkit/tree/main/examples/domains/legal-compliance).

## How to participate

Corrections are the highest-value contribution: regulations change, so a value that was right a year ago may be wrong today. Open an issue on the relevant repository with the source that contradicts it, try a module on your own data, contribute a fix — or claim one of the 21 modules as maintainer. Other industries are explicitly welcome: keep the core, add your own `domains/` modules.

## Licence

Apache-2.0 / CC BY 4.0 / CC0 as stated in each repository's LICENSE. Pure technical contribution; no standard-setting claim is made; affiliation is disclosed, not promoted.

---
## 中文

医疗器注册（RA）与 AI 治理从业者。把其中可通用的部分，做成**零依赖、可离线审计**的开源模块，按 **LGD** 插件矩阵组织 —— 医疗器械是参考示例领域，骨架本身与行业无关。

**门户与路由表：** [medical-ai-toolkit](https://github.com/stevenzhao07/medical-ai-toolkit) · [在线站点](https://stevenzhao07.github.io/medical-ai-toolkit/)

### 这个账号是什么

我在医疗器械注册与 AI 治理一线工作，把其中能通用的部分公开成模块：法规映射、质量体系结构、验证门禁、互操作轮廓。每个仓库都是纯技术贡献 —— 无第三方依赖、可离线运行、多年后可复现。MedXpert 作为关联披露，不作为产品推广。

### 矩阵 —— 21 个仓库

**AI 治理层（9）**：`samd-ra-toolkit`（跨辖区注册映射）、`ai-governance-checklist`（治理自检 / 模型卡·数据卡）、`ai-a3-laws`（权限–自主–追责运行时约束）、`ai-model-passport`（模型身份与溯源）、`fhir-ortho-toolkit`（FHIR R4 UDI 轮廓）、`omop-ortho-toolkit`（OMOP 概念集与 ETL）、`ml-validation-toolkit`（性能 / 校准 / 公平性）、`delivery-guard`（17 道交付门禁 + 双 SHA-256 权属台账）、`multilingual-ifu`（IFU 14 个语言版本）。

**器械生命周期层（11）**：`design-controls-toolkit`（设计控制）、`iso14971-risk-file`（风险管理）、`iec62304-software`（软件生命周期）、`device-regulatory-map`（分类与路径映射）、`clinical-evaluation`（临床评价与 PMCF）、`biocompatibility-iso10993`（生物相容性）、`sterilization-validation`（灭菌与清洁）、`manufacturing-gmp`（生产质量 / IQ·OQ·PQ）、`udi-assignment`（UDI 赋码）、`pms-vigilance`（上市后警戒）、`cybersecurity-medical`（网络安全）。

**门户（1）**：`medical-ai-toolkit` —— 路由、机器可发现清单、自检测试框架。

（各仓引用的标准与法规见英文表格。）

### LGD

LGD 是矩阵底下的治理框架：与行业无关的内核（`router.py`、`harness.py`、`config/`）+ 由声明式 `module.json` 描述的领域插件。医疗矩阵只是已经做出来的样例，不是边界 —— 可复用的是顺序、门禁与审计轨迹。跨行业最小示例见 [`examples/domains/legal-compliance`](https://github.com/stevenzhao07/medical-ai-toolkit/tree/main/examples/domains/legal-compliance)。

### 如何参与

纠错是价值最高的贡献：法规在变，去年正确的值今年可能已过时。请在对应仓库提 Issue 并附上与你所指相矛盾的来源；也可以在用自己的数据试用后反馈、提交修复，或**认领 21 个模块中的一个作为维护者**。其他行业同样欢迎：保留内核，加自己的 `domains/` 模块即可。

### 许可

各仓 LICENSE 声明（Apache-2.0 / CC BY 4.0 / CC0）。纯技术贡献，不主张标准制定权；关联机构仅作署名披露。
