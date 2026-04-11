---
title: "Promptfoo"
slug: "promptfoo"
info_type: "awesome-ai-for-coding"
entity_type: "tool"
category: "Testing"
featured: false
last_reviewed_at: "2026-04-10T00:00:00+00:00"
---

# Promptfoo

## 一句话总结

一个面向 LLM 应用的开源评测与红队测试工具，适合把提示词质量、安全扫描和回归检查接进 CI/CD。

## 它解决什么问题

- 很多团队在改 Prompt、模型或工具调用链时，没有稳定的自动化测试门槛。
- AI 应用上线前常常缺少系统性的红队测试，容易忽视提示词注入、越狱和合规风险。
- 安全团队和工程团队需要一套能在本地和 CI 里复用的评测工具，而不是只看在线面板。

## 适合谁

- 需要给 AI 应用建立回归测试的工程团队
- 负责 GenAI 安全审查和红队测试的安全团队
- 维护客服机器人、RAG、Agent 和内部 Copilot 的 QA 团队

## 核心能力

- 自动评测：批量比较 Prompt、模型和输出结果。
- 红队测试：针对注入、越狱和常见漏洞做系统化安全扫描。
- CI/CD 集成：支持命令行、本地运行和流水线接入，便于做发布门禁。

## 典型使用场景

- 每次改 Prompt 或切模型时，自动跑一套评测矩阵，防止质量回退。
- 给 AI 客服、RAG 和 Agent 产品做上线前安全压测。
- 在代码审查和发布流程里加入 AI 功能专属测试环节。

## 为什么值得关注

- 它的差异点不是“又一个 eval 平台”，而是把红队测试和 CI 集成做得非常工程化。
- 支持本地运行，对重视隐私和内部测试环境的团队更友好。
- 2026 年仍在高频发版，说明项目远不只是早期 demo。

## 类似项目

- [Evidently](./evidently.md) - 更偏评测与监控框架，不主打红队和安全门禁。
- [DeepTeam](./deepteam.md) - 更聚焦 LLM 红队框架本身，不像 Promptfoo 这样强调 CI/CD 流水线接入。

## 官方链接

- **官网:** https://www.promptfoo.dev
- **GitHub:** https://github.com/promptfoo/promptfoo
- **文档:** https://www.promptfoo.dev/docs/
- **更新记录:** https://github.com/promptfoo/promptfoo/releases

## 标签

- `评测`, `红队测试`, `CI/CD`, `LLM安全`, `Prompt测试`

## 更新观察点

- 继续观察红队能力是否覆盖更多 AI Agent 和代码助手场景。
- 重点看和 CI、代码扫描、合规检查的集成是否继续增强。
- 后续维护时优先重抓 releases、agents.md 和文档里的 red team 模块。
