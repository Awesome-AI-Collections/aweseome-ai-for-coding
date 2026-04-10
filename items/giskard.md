---
title: "Giskard"
slug: "giskard"
info_type: "awesome-ai-for-coding"
entity_type: "tool"
category: "测试"
featured: false
last_reviewed_at: "2026-04-10T00:00:00+00:00"
---

# Giskard

## 一句话总结

一个开源 AI 测试与红队工具库，适合给 Agent、RAG 和 LLM 应用做评测、漏洞扫描和测试集生成。

## 它解决什么问题

- 很多 AI 团队能写 demo，但缺少系统化测试、漏洞发现和数据集生成能力。
- Agent 和 RAG 应用越来越复杂，传统单轮测试已经不够用。
- 工程团队需要兼顾质量回归、RAG 测试和安全漏洞扫描，但不想维护多套分裂工具链。

## 适合谁

- 负责 AI 质量和回归测试的工程团队
- 做 Agent、RAG 和多轮交互系统的 AI 平台团队
- 负责 AI 红队测试和漏洞扫描的安全团队

## 核心能力

- 测试与评测：支持多种 eval、LLM-as-a-judge 和场景化测试。
- 红队扫描：可用于挖掘注入、泄露和其他 AI 应用漏洞。
- 测试集生成：为 RAG 和 AI 应用自动生成更系统的评测集。

## 典型使用场景

- 给客服、RAG 和 Agent 产品建立回归测试和质量基线。
- 在上线前做自动漏洞扫描和安全测试。
- 给知识库问答系统生成测试集并持续验证回答可靠性。

## 为什么值得关注

- 它把测试、红队和测试集生成组合在一起，适合真实 AI 产品团队。
- 2026 年仍在推进 v3 重构，说明项目并没有停在旧架构上。
- 对多轮 Agent 系统特别有价值，不只是简单 Prompt 测试。

## 类似项目

- [Promptfoo](./promptfoo.md) - 更偏开发者工作流、CI 和红队门禁。
- [DeepTeam](./deepteam.md) - 更聚焦 LLM 红队，而 Giskard 更强调完整测试工具链。

## 官方链接

- **官网:** https://www.giskard.ai/
- **GitHub:** https://github.com/Giskard-AI/giskard
- **文档:** https://docs.giskard.ai/oss
- **更新记录:** https://github.com/Giskard-AI/giskard/releases

## 标签

- `评测`, `红队测试`, `RAG`, `Agent测试`, `testset-generation`

## 更新观察点

- 继续观察 v3 对漏洞扫描和 RAG 测试能力的补齐速度。
- 重点看 giskard-checks、giskard-scan 和后续模块拆分是否稳定。
- 后续维护时优先重抓 releases、roadmap 和 OSS 文档。
