---
title: "DeepTeam"
slug: "deepteam"
info_type: "aweseome-ai-for-coding"
entity_type: "tool"
category: "测试"
featured: false
last_reviewed_at: "2026-04-10T00:00:00+00:00"
---

# DeepTeam

## 一句话总结

一个面向 LLM 系统的开源红队框架，可对客服、销售、RAG 和 AI Agent 做越狱、提示词注入、泄露和权限绕过类安全压测。

## 它解决什么问题

- 很多 AI 客服、销售助手和知识库问答产品上线前没有系统化红队流程。
- 一般评测框架更关心“答得好不好”，但不一定能覆盖安全、隐私和越权风险。
- 团队需要本地可运行、可编排的红队框架，而不是只靠人工脑暴测试。

## 适合谁

- 负责 AI 安全和合规的安全团队
- 维护客服、销售、RAG 和 Agent 产品的 QA 团队
- 想把 AI 红队测试流程标准化的工程团队

## 核心能力

- 漏洞模板库：覆盖 PII 泄露、Prompt 泄露、越权、注入、毒性等多类风险。
- 对抗攻击方法：支持多种单轮和多轮攻击策略做压测。
- 本地运行：可在本地和内部环境执行，不必把测试数据交给外部平台。

## 典型使用场景

- 给 AI 客服和销售机器人做上线前安全压测，避免泄露敏感信息。
- 在 RAG 或 Agent 系统中测试注入、越权和系统提示词暴露问题。
- 把安全测试加入 AI 应用的开发与发布流程中。

## 为什么值得关注

- 它不是泛 eval 框架，而是明确站在红队和渗透测试视角设计。
- 对客户-facing AI 工具尤其重要，适合实际业务场景里的风险验证。
- 能和 DeepEval 等评测链路衔接，利于形成更完整的 AI 质量与安全体系。

## 类似项目

- [Promptfoo](./promptfoo.md) - 更偏开发者测试和 CI/CD 门禁，也做红队但范围更通用。
- [Evidently](./evidently.md) - 更偏质量评测与监控，不专注安全红队。

## 官方链接

- **官网:** https://www.trydeepteam.com/
- **GitHub:** https://github.com/confident-ai/deepteam
- **文档:** https://www.trydeepteam.com/docs/
- **更新记录:** https://github.com/confident-ai/deepteam/releases

## 标签

- `红队测试`, `LLM安全`, `越狱测试`, `Prompt注入`, `Agent安全`

## 更新观察点

- 继续观察攻击模板和漏洞覆盖是否延展到更多 Agent 场景。
- 重点看 guardrails 和生产风险管理能力是否持续增强。
- 后续维护时优先重抓 releases 与 vulnerability 文档，确认框架成熟度。
