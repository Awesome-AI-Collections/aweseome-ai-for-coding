---
title: "Agenta"
slug: "agenta"
info_type: "awesome-ai-for-coding"
entity_type: "tool"
category: "工程工作流"
featured: false
last_reviewed_at: "2026-04-10T00:00:00+00:00"
---

# Agenta

## 一句话总结

一个开源 LLMOps 平台，把 Prompt 管理、评测和可观测性整合到同一套产品与工程协作流程里，适合 AI 工程团队和产品团队一起迭代 AI 功能。

## 它解决什么问题

- 工程团队和业务专家在 Prompt 调整、测试和上线时，常常缺少统一协作界面。
- 很多团队把 playground、评测和生产观测拆在不同工具里，迭代成本很高。
- AI 产品要稳定上线时，既要观察质量，也要管理 Prompt 版本和实验记录。

## 适合谁

- 同时需要工程与业务协作的 AI 产品团队
- 想系统化管理 Prompt、实验和评测的 LLM 应用团队
- 需要自托管 LLMOps 工作台的企业内部平台团队

## 核心能力

- Prompt 管理：支持版本控制、环境管理和多模型对比实验。
- 评测框架：可结合自动评测和人工反馈做系统化验证。
- 生产观测：跟踪成本、延迟、调用链和生产行为。

## 典型使用场景

- 产品经理、Prompt 工程师和开发一起在 playground 里对比 Prompt 方案。
- 把生产数据回流成测试集，再对新版本进行评测后上线。
- 为企业内部多个 AI 功能搭建统一的 Prompt 和评测协作台。

## 为什么值得关注

- 它比单纯 tracing 平台更强调 Prompt 协作和产品团队参与。
- 同时覆盖 playground、评测和观测，适合要做内部 AI 平台的团队。
- 从 release 节奏看项目还处在快速打磨期，活跃度很强。

## 类似项目

- [Langfuse](./langfuse.md) - 更偏 tracing、评测和生产观察，Prompt 协作感没那么强。
- [OpenLIT](./openlit.md) - 更偏工程底座与可观测性能力，不像 Agenta 这样突出 Prompt playground。

## 官方链接

- **官网:** https://agenta.ai/
- **GitHub:** https://github.com/agenta-ai/agenta
- **文档:** https://agenta.ai/docs/
- **更新记录:** https://github.com/agenta-ai/agenta/releases

## 标签

- `LLMOps`, `Prompt管理`, `评测`, `可观测性`, `产品协作`

## 更新观察点

- 继续观察 SME 协作、Prompt 分支和环境能力是否更完善。
- 重点看自托管部署、RBAC 和生产观测模块的成熟度。
- 后续维护时优先重抓 releases、agents.md 和 changelog 文档。
