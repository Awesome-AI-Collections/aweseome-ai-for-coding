---
title: "OpenLIT"
slug: "openlit"
info_type: "aweseome-ai-for-coding"
entity_type: "tool"
category: "工程工作流"
featured: false
last_reviewed_at: "2026-04-10T00:00:00+00:00"
---

# OpenLIT

## 一句话总结

一个开源 AI 工程平台，把 LLM 可观测性、评测、规则引擎、Prompt 管理和 GPU 监控放到同一套工作流里。

## 它解决什么问题

- 很多 AI 团队在实验、上线和运维阶段要切换多套工具，链路割裂严重。
- 只做 tracing 的平台很难覆盖评测、Prompt 管理、成本和 GPU 监控。
- AI 应用进入生产后，工程团队需要更标准化的 OpenTelemetry 接入方式。

## 适合谁

- 负责内部 AI 平台建设的工程团队
- 正在把 LLM 功能推进到生产环境的应用团队
- 同时关心模型质量、成本和基础设施健康的 AI 工程团队

## 核心能力

- OpenTelemetry 原生可观测性：一行接入 LLM、向量库和 GPU 监控数据。
- 评测与规则引擎：支持多种内置评测类型，并可在运行时按规则触发。
- Prompt 与密钥管理：同时覆盖 Prompt 版本管理、实验和密钥集中管理。

## 典型使用场景

- 给 AI 应用补上 tracing、成本、错误与性能监控，形成统一工程面板。
- 在上线前后做自动评测、规则校验和异常追踪，减少“能跑但不可控”问题。
- 把 Prompt、评测和遥测统一进团队内部 AI 平台，而不是分散在多个 SaaS。

## 为什么值得关注

- 功能面比单点 tracing 工具更完整，适合想自建 AI 工程底座的团队。
- 明确走 OpenTelemetry 原生路线，和现有可观测性体系更容易接轨。
- 最近 release 频率很高，说明项目在快速扩展而不是停滞维护。

## 类似项目

- [Langfuse](./langfuse.md) - 更聚焦 LLM tracing、prompt 和评测，平台面相对更收敛。
- [LangWatch](./langwatch.md) - 更偏 LLM 评测与测试协作，不覆盖这么多 AI 工程底层能力。

## 官方链接

- **官网:** https://openlit.io/
- **GitHub:** https://github.com/openlit/openlit
- **文档:** https://docs.openlit.io/
- **更新记录:** https://github.com/openlit/openlit/releases

## 标签

- `LLMOps`, `可观测性`, `评测`, `Prompt管理`, `GPU监控`

## 更新观察点

- 继续观察 Rule Engine、FleetHub 和 Guardrails 模块是否更成熟。
- 重点看 SDK 覆盖范围和 OTel 语义约定是否持续跟进主流生态。
- 后续维护时优先重抓 releases 和 docs，确认平台模块边界是否继续扩展。
