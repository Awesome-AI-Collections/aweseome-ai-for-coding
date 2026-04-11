---
title: "pua"
slug: "pua"
info_type: "awesome-ai-for-coding"
entity_type: "tool"
category: "Engineering Workflows"
featured: false
last_reviewed_at: "2026-04-10T13:04:00+00:00"
---

# pua

## 一句话总结

一个面向 Claude Code、Codex、Cursor 等编码 Agent 的技能插件，用高压话术、调试方法论和主动性约束来减少放弃、甩锅和无效打转。

## 它解决什么问题

- 编码 Agent 遇到复杂问题时，常会过早放弃、重复尝试同一路径，或者把问题推回给用户
- AI 在调试、验证和排查时容易停留在表面修补，缺少系统化 checklist 和主动调查意识
- 即使有能力完成任务，很多 Agent 仍会因为行为模式太“懒”而交付不稳定

## 适合谁

- 想提高 Claude Code、Codex 等编码 Agent 调试韧性的开发者
- 经常遇到 AI 提前放弃、甩锅或不做验证的人
- 希望给编码 Agent 加上更强行为约束和故障排查纪律的用户

## 核心能力

- 失败升级机制：根据失败次数触发不同等级的话术压力和动作要求
- 调试方法论：内置检查清单、根因分析和验证约束，逼着 Agent 不要原地打转
- 主动性强化：鼓励先搜索、先验证、先扩展检查，而不是等用户继续指挥
- 多平台技能接入：支持 Claude Code、Codex、Cursor、OpenClaw、OpenCode 等多个编码 Agent 平台

## 典型使用场景

- 在复杂 bug 排查中防止 Agent 重复试错后直接投降
- 给编码 Agent 增加“修完必须验证、发现一个问题要扫一类问题”的工作纪律
- 当默认行为太保守时，用技能插件强化 AI 的执行主动性和完成闭环能力

## 为什么值得关注

- 它关注的是 Agent 行为层，而不是再加一个模型或 IDE 壳
- 方向很明确：通过技能约束把“会做”变成“更不容易半途而废”
- 对重度使用 Claude Code、Codex 的用户来说，这类行为增强插件很有代表性

## 类似项目

- [Superpowers](superpowers.md) - 更强调完整的软件开发流程、TDD 和子代理协作，而 pua 更聚焦行为约束、调试韧性和主动性强化。
- [Get Shit Done](get-shit-done.md) - 更偏 context engineering 和项目级规划执行系统，而 pua 更像一个直接干预 Agent 行为风格的技能插件。

## 官方链接

- **官网:** https://openpua.ai
- **GitHub:** https://github.com/tanweai/pua
- **更新记录:** https://github.com/tanweai/pua/releases

## 标签

- `Claude Code`, `Codex`, `Agent Skill`, `Debugging`, `Proactivity`, `Workflow`

## 更新观察点

- 后续重点看不同平台的技能安装方式是否进一步统一
- 观察行为升级规则、benchmark 和调试方法论是否持续迭代
- 持续跟踪 releases，判断它是继续做行为增强插件，还是扩展成更完整的 agent 管理层
