---
title: "Helicone"
slug: "helicone"
info_type: "awesome-ai-for-coding"
entity_type: "tool"
category: "Engineering Workflows"
featured: false
last_reviewed_at: "2026-04-10T00:00:00+00:00"
---

# Helicone

## 一句话总结

一个开源 AI Gateway 与 LLM 可观测性平台，适合统一接入多模型、追踪成本延迟并管理 Prompt。

## 它解决什么问题

- 团队同时使用多个模型和供应商时，接口、路由和监控容易分散。
- AI 应用上线后，成本、延迟、会话和回退策略需要统一追踪。
- 很多团队既想做观测，也想把模型访问收口成一个网关层。

## 适合谁

- 负责内部 AI 平台和模型接入的工程团队
- 同时接多个模型供应商的 LLM 应用团队
- 需要统一成本、Prompt 和路由策略的企业团队

## 核心能力

- AI Gateway：通过统一接口接入多家模型服务，并支持回退和路由。
- 可观测性：追踪成本、延迟、trace、sessions 和质量信号。
- Prompt 管理：支持围绕生产数据做 Prompt 版本与部署管理。

## 典型使用场景

- 在企业内部统一管理 OpenAI、Anthropic、Gemini 等模型访问入口。
- 给多模型应用建立统一监控面板，追踪成本和性能。
- 为聊天机器人、文档处理和 Agent 应用做会话级观测与 Prompt 迭代。

## 为什么值得关注

- 它和一般观测平台的区别在于把“网关层”也一起做了。
- 对模型供应商多、成本敏感的团队尤其有价值。
- 近一年的 release 和功能面都说明它仍是活跃项目。

## 类似项目

- [OpenLIT](./openlit.md) - 更偏完整 AI 工程平台，不以统一网关为核心。
- [Langfuse](./langfuse.md) - 更偏 tracing 与评测，不负责多模型统一接入层。

## 官方链接

- **官网:** https://www.helicone.ai/
- **GitHub:** https://github.com/Helicone/helicone
- **文档:** https://docs.helicone.ai/
- **更新记录:** https://github.com/Helicone/helicone/releases

## 标签

- `AI-Gateway`, `可观测性`, `成本追踪`, `Prompt管理`, `多模型路由`

## 更新观察点

- 继续观察 Gateway、fallback 和路由策略是否继续增强。
- 重点看自托管能力和企业数据所有权相关能力是否更成熟。
- 后续维护时优先重抓 releases、agents/claude 配置和官方文档。
