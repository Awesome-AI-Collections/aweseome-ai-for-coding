---
title: "Evidently"
slug: "evidently"
info_type: "aweseome-ai-for-coding"
entity_type: "tool"
category: "测试"
featured: false
last_reviewed_at: "2026-04-10T00:00:00+00:00"
---

# Evidently

## 一句话总结

一个开源 ML 与 LLM 评测、测试和监控框架，适合 AI 工程团队把质量检查接进实验、回归测试和生产监控流程。

## 它解决什么问题

- 很多 AI 项目上线前缺少系统化评测，往往只靠人工抽样判断质量。
- 实验阶段和生产阶段使用的质量指标不统一，难以持续追踪退化。
- 团队想做数据漂移、LLM 输出质量和 RAG 效果监控时，常常缺少一套统一框架。

## 适合谁

- 需要做模型回归测试和评测基线的 AI 工程团队
- 关注数据质量、漂移和线上监控的数据科学团队
- 正在搭建 LLM eval 流程的 AI 平台与质量团队

## 核心能力

- 报告与测试套件：既能做一次性评测，也能把评测转成带阈值的测试。
- LLM 与传统 ML 评测：同时支持文本、RAG、漂移检测和常见模型质量指标。
- 监控界面：可自托管监控 UI，持续观察测试结果和质量变化趋势。

## 典型使用场景

- 给 AI 应用增加发布前回归测试，防止提示词、模型或数据变更导致质量下滑。
- 在实验阶段快速跑一组评测报告，比较不同模型、检索方案或 Prompt 版本。
- 在生产环境持续跟踪数据漂移、文本质量和 LLM 输出异常。

## 为什么值得关注

- 它覆盖从离线评测到线上监控的完整链路，不是单一 eval 脚本集合。
- 同时支持传统 ML 和 LLM，用一套框架就能服务混合型 AI 产品团队。
- 社区成熟、指标丰富，适合做团队级质量基线而不是一次性 demo。

## 类似项目

- [LangWatch](./langwatch.md) - 更偏 LLM 测试协作和平台化评测。
- [OpenLIT](./openlit.md) - 更偏 AI 工程平台与可观测性，不以测试框架为核心。

## 官方链接

- **官网:** https://www.evidentlyai.com/
- **GitHub:** https://github.com/evidentlyai/evidently
- **文档:** https://docs.evidentlyai.com/
- **更新记录:** https://github.com/evidentlyai/evidently/releases

## 标签

- `评测`, `测试`, `监控`, `data-drift`, `LLMOps`

## 更新观察点

- 继续观察 LLM judge、RAG 和实时监控相关指标是否继续扩展。
- 重点看测试套件、云版与开源版边界是否发生变化。
- 后续维护时优先重抓 releases 和 docs，确认评测能力和 API 变化。
