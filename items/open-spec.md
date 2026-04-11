---
title: "OpenSpec"
slug: "open-spec"
info_type: "awesome-ai-for-coding"
entity_type: "tool"
category: "Engineering Workflows"
featured: true
last_reviewed_at: "2026-04-10T12:47:00+00:00"
---

# OpenSpec

## 一句话总结

一个面向 AI 编码助手的 spec-driven development 框架，通过 `openspec` CLI 和 `/opsx:*` 命令把 proposal、spec、design、tasks、apply 和 archive 串成轻量可迭代研发流程。

## 它解决什么问题

- AI 编码助手很强，但如果需求只存在聊天上下文里，最后容易出现理解偏差和实现漂移
- 很多 spec-first 工具偏重或太僵硬，不适合在已有项目里快速落地
- 团队想把提案、设计、任务和实现过程收进同一条流程，但又不想被某个 IDE 或单一模型绑定

## 适合谁

- 想给现有 AI 编码工作流加一层轻量规格管理的开发者
- 希望在 brownfield 项目中引入 spec-first 过程的团队
- 想在多种 AI 工具之间复用同一套变更提案与任务流程的人

## 核心能力

- 变更目录工作流：为每个需求创建 proposal、specs、design 和 tasks 等独立工件
- 命令驱动流程：通过 `/opsx:propose`、`/opsx:apply`、`/opsx:archive` 等命令推进完整生命周期
- 轻量集成：使用 `openspec init` 和 `openspec update` 接入现有项目与 AI 工具
- 多工具支持：支持 20+ AI assistants，并强调不绑定某个专有 IDE

## 典型使用场景

- 在已有代码库中为新功能建立可讨论、可追踪的变更规格
- 让 AI 在编码前先产出 proposal、design 和 tasks，而不是直接动手实现
- 在团队里建立一套更轻量、更灵活的 spec-first AI 开发习惯

## 为什么值得关注

- 相比更“重”的 spec 工具，它主打 fluid not rigid，强调可迭代而非瀑布式流程
- 明确面向 brownfield 项目，这点对真实团队落地很关键
- 把命令流、CLI、工件目录和工具适配结合在一起，比较接近日常 AI 编码使用场景

## 类似项目

- [Spec Kit](spec-kit.md) - 也是 spec-driven development 工具，但更强调完整规范流程和命令骨架；OpenSpec 更突出轻量、流动式和 brownfield 适配。
- [Superpowers](superpowers.md) - 更强调编码 Agent 的技能系统、TDD 纪律和子代理执行，而 OpenSpec 更聚焦规格工件和变更生命周期管理。

## 官方链接

- **GitHub:** https://github.com/Fission-AI/OpenSpec
- **文档:** https://github.com/Fission-AI/OpenSpec/tree/main/docs
- **更新记录:** https://github.com/Fission-AI/OpenSpec/releases

## 标签

- `Spec-Driven Development`, `AI 编码助手`, `CLI`, `工作流`, `Requirements`, `Slash Commands`

## 更新观察点

- 后续重点观察 `/opsx:*` 命令流是否继续扩展更多协作和验证能力
- 关注支持的 AI 工具清单是否持续增加，以及不同工具的接入体验是否趋于统一
- 持续看 releases 和 docs，判断它是保持轻量 spec 框架定位，还是继续往更完整平台演化
