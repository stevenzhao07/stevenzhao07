# 👋 MedXpert · 医疗 AI 开源工具链

> 骨科医疗器械合规 + AI 治理的可插拔开源模块集合，由 [@stevenzhao07](https://github.com/stevenzhao07) 维护。
> Pure technical input · 关联披露：[MedXpert](https://www.medxpert.cn)

![License](https://img.shields.io/badge/license-Apache--2.0%20%7C%20CC--BY--4.0%20%7C%20CC0-blue)
![Modules](https://img.shields.io/badge/modules-10-brightgreen)
![Contract](https://img.shields.io/badge/contract-lgd--skeleton%2F1.0-purple)

## 🧭 我是谁
医疗器械注册（RA）与 AI 治理一线从业者，专注把「合规到临床落地」的能力沉淀为可复用、可插拔的开源模块。
本账号是 **MedXpert 医疗 AI 工程门面**——所有仓库均为纯技术实现，关联 MedXpert 但独立署名。

## 🗂 作品集（10 仓 · lgd-skeleton/1.0 可插拔契约）

| 仓库 | 层 | 一句话 |
|---|---|---|
| [medxpert-medai-landing](https://github.com/stevenzhao07/medxpert-medai-landing) | 门户 | 总入口 · 路由 9 个子模块 |
| [medxpert-delivery-guard](https://github.com/stevenzhao07/medxpert-delivery-guard) | L4 | 18 道确定性合规门禁 + 双 SHA-256 指纹 |
| [medxpert-multilingual-ifu](https://github.com/stevenzhao07/medxpert-multilingual-ifu) | L5 | 12 语种骨科 IFU 语料（护城河） |
| [medxpert-a3-laws](https://github.com/stevenzhao07/medxpert-a3-laws) | L2 | A³ Laws 运行时约束（权限 / 自主 / 追责） |
| [medxpert-ai-passport](https://github.com/stevenzhao07/medxpert-ai-passport) | L2/L3 | AI 护照签发 / 验证 + 指纹 |
| [medxpert-samd-ra-kit](https://github.com/stevenzhao07/medxpert-samd-ra-kit) | L1 | SaMD 监管映射（NMPA / MDR / FDA / PMDA） |
| [medxpert-ai-governance](https://github.com/stevenzhao07/medxpert-ai-governance) | L2 | 治理检查清单 + 模型卡 / 数据卡模板 |
| [medxpert-fhir-ortho](https://github.com/stevenzhao07/medxpert-fhir-ortho) | L3 | 骨科 UDI FHIR R4 资源 |
| [medxpert-omop-ortho](https://github.com/stevenzhao07/medxpert-omop-ortho) | L3 | 骨科 → OMOP 概念集 |
| [medxpert-ml-validation](https://github.com/stevenzhao07/medxpert-ml-validation) | L4 | ML 性能 / 校准 / 公平性校验（零依赖） |

## 🔗 双线协调
- **开源实现线（本账号）**：代码与模板，社区可署名 MedXpert。
- **治理理念线**：医疗 AI 信任方法论（治理守护者 / 立法者 / 护照官 / 共存倡导），以个人专家身份对外分享，CC BY 4.0。

## 📜 合规披露
所有仓库遵循 **lgd-skeleton/1.0** 可插拔契约；许可以各仓 LICENSE 为准（Apache-2.0 / CC-BY-4.0 / CC0）。
纯技术贡献，不主张标准制定权，关联机构仅作署名披露。

## 🛠 技术栈
Python 3.8+（零依赖标准库为主） · JSON 契约 · FHIR R4 · OMOP CDM · GitHub REST API

---
⭐ 若这些模块对你有用，欢迎 star / fork / 提 PR。
