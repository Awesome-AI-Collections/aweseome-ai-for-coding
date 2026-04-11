---
title: "Keep"
slug: "keep"
info_type: "awesome-ai-for-coding"
entity_type: "tool"
category: "Engineering Workflows"
featured: false
last_reviewed_at: "2026-04-10T00:00:00+00:00"
---

# Keep

## 一句话总结

一个开源 AIOps 与告警管理平台，适合 SRE、平台工程和运维团队把分散告警统一收口，并用 AI 做去重、关联、富化和事故摘要。

## 它解决什么问题

- Datadog、Grafana、CloudWatch、Prometheus 等多套监控同时存在时，告警入口容易碎片化。
- 值班团队常常被重复告警和上下文缺失拖慢响应速度。
- 很多团队有自动化和告警编排需求，但不想只依赖单一商业告警平台。

## 适合谁

- 负责 on-call 与告警治理的 SRE 团队
- 维护多云、多监控栈的基础设施和平台工程团队
- 想把事故响应自动化的互联网运维团队

## 核心能力

- 告警统一汇总：把多种监控与事件源集中到一个工作台里处理。
- 去重与关联：对重复或相关告警做过滤、聚合和关联，减少值班噪音。
- AI 富化与摘要：结合 LLM 做事故上下文收集、相关信息补全和摘要生成。

## 典型使用场景

- 把来自多个监控平台的告警统一接入，建立一个面向值班团队的告警入口。
- 在高噪音环境里做告警去重和相关事件关联，降低 on-call 压力。
- 基于工作流与双向集成，把告警自动同步到工单、聊天和事故响应系统。

## 为什么值得关注

- 它不是只做告警展示，而是把告警聚合、自动化和 AI 上下文处理做成了一套完整平台。
- 支持的监控与协作系统很多，适合互联网公司复杂的运维工具链。
- 从近期 release 节奏看，项目仍在高频迭代，不是停在概念阶段的 AIOps 壳子。

## 类似项目

- [Langfuse](./langfuse.md) - 更偏 LLM 应用 tracing 与评测，不负责基础设施告警汇总。
- [OpenLIT](./openlit.md) - 更偏 AI 应用可观测性与评测，不是通用告警管理平台。

## 官方链接

- **官网:** https://www.keephq.dev
- **GitHub:** https://github.com/keephq/keep
- **文档:** https://docs.keephq.dev
- **更新记录:** https://github.com/keephq/keep/releases

## 标签

- `AIOps`, `告警管理`, `SRE`, `incident-response`, `运维自动化`

## 更新观察点

- 继续观察 AI 关联、RCA 辅助和事故摘要能力是否更深入。
- 重点看与主流监控、IM 和工单系统的双向集成是否持续扩展。
- 后续维护时优先重抓 releases 和 provider 文档，确认平台迭代速度。
