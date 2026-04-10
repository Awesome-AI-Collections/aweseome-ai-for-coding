---
title: "AgentHandover"
slug: "agenthandover"
info_type: "awesome-ai-for-coding"
entity_type: "tool"
category: "工程工作流"
featured: false
last_reviewed_at: "2026-04-10T19:55:41+00:00"
---

# AgentHandover

## 一句话总结

一个在 macOS 上录制真实工作流程、自动生成可自我改进 skills，并交给 Claude Code、Codex、OpenClaw、Hermes 等 agent 执行的工作交接工具。

## 它解决什么问题

- 很多 coding agent 只能依赖一次性的 prompt，难以稳定复现你真实的做事方式。
- 团队里大量隐性的流程知识藏在人的操作细节里，换人或换 agent 时很容易丢失。
- 手写 skill 往往只能描述步骤，难以完整保留为什么这么做、遇到什么情况该跳过或改写。

## 适合谁

- 想把重复编程任务录成可复用技能的开发者。
- 正在使用 Claude Code、Codex、OpenClaw 等 coding agent 的个人或小团队。
- 希望把 workflow knowledge 从口头提示变成可执行资产的 AI 原生构建者。

## 核心能力

- 观察式技能生成：记录你在 Mac 上的真实操作，再补 1 到 3 个问题，生成结构化 skill。
- 技能审批与复用：可以先审阅步骤、策略、选择标准和 guardrails，再批准给 agent 使用。
- Agent 连接能力：支持通过命令把 skill 交给 Claude Code、Codex、OpenClaw、Hermes 等兼容 agent。
- 反馈式演进：执行后会回收成功、偏差和失败信息，让 skill 逐步补充分支与修正逻辑。

## 典型使用场景

- 把日常代码库巡检、发布检查、支持排障等重复任务录成可复用 skill。
- 把个人积累的工程判断交接给 coding agent，而不是每次重新写 prompt。
- 给团队里的多个 agent 建立共享的做事方式，减少“会调用模型但不会按你方式做事”的落差。

## 为什么值得关注

- 它抓的是“你如何做决定”，而不只是“你点击了哪些步骤”。
- 相比手写技能库，这种观察式录制更接近真实工作流，也更适合长期迭代。
- 它把 skill capture、批准、连接和执行反馈串成了闭环，而不是单一导出工具。

## 类似项目

- [Superpowers](superpowers.md) - 同样强调把经验沉淀成可复用技能，但 Superpowers 更偏手写方法论与执行约束；AgentHandover 更偏从真实操作里自动生成技能。
- [oh-my-claudecode](oh-my-claudecode.md) - 同样围绕 Claude Code 工作流增强，但 oh-my-claudecode 更像命令和工作流集合；AgentHandover 更强调录制、学习和交接。

## 官方链接

- **GitHub:** https://github.com/sandroandric/AgentHandover
- **Quickstart:** https://github.com/sandroandric/AgentHandover?tab=readme-ov-file#quickstart
- **更新记录:** https://github.com/sandroandric/AgentHandover/releases
- **演示视频:** https://youtu.be/3nGH3rYbgfY

## 标签

- `Skill Capture`, `Claude Code`, `Codex`, `MCP`, `Workflow Automation`, `macOS`

## 更新观察点

- 继续看它是否把当前偏 macOS 的录制和权限模型扩展到更多桌面环境。
- 关注 skill 审批、回放和失败修正链路是否越来越清晰，而不是只停留在录制 demo。
- 观察它和 Claude Code、Codex、Hermes 这类 agent runtime 的连接方式会不会继续标准化。
