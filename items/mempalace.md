---
title: "MemPalace"
slug: "mempalace"
info_type: "awesome-ai-for-coding"
entity_type: "tool"
category: "工程工作流"
featured: false
last_reviewed_at: "2026-04-11T00:00:00+00:00"
---

# MemPalace

## 一句话总结

一个面向 Claude Code、Cursor、Gemini CLI 等 AI 助手的本地记忆系统，会把项目资料、历史对话和知识图谱接回开发工作流，让 agent 不必每次都从零开始。

## 它解决什么问题

- 很多关键的设计讨论、调试过程和技术取舍都留在聊天窗口里，过一段时间就很难再找回。
- AI coding agent 缺少长期记忆时，经常重复问同样背景，或者忘掉过去的决定和约束。
- 团队想给 AI 助手接记忆层，但又不想把所有对话和项目语境交给云端订阅服务。

## 适合谁

- 重度使用 Claude Code、Cursor、Gemini CLI 等工具的开发者
- 想给 AI coding agent 接长期记忆层的个人开发者和小团队
- 希望沉淀项目对话、决策、排障过程和 agent 专家经验的人

## 核心能力

- 本地记忆采集：可挖掘项目代码、文档、对话导出和通用资料，把历史上下文存回本机。
- MCP 工具接入：可通过插件或 MCP server 把搜索、知识图谱、agent diary 等能力接给 AI 助手。
- 知识图谱与时间线：支持围绕实体关系、时间窗口和历史事件做查询与回溯。
- Specialist agents：可给 reviewer、architect、ops 这类角色维护独立 diary，让不同 agent 形成长期专长。

## 典型使用场景

- 让 Claude Code 回答“上个月为什么换掉这套鉴权方案”这类依赖历史讨论的问题。
- 把代码库、设计文档和聊天记录统一挖掘后，给 Cursor 或 Gemini CLI 做长期上下文支持。
- 为 code review、架构决策、运维事故等不同角色维护分开的 agent 记忆与经验库。

## 为什么值得关注

- 它抓的是 AI coding workflow 里最痛的一层: 对话和决策会消失，agent 缺少长期记忆。
- README 不只讲概念，还给了 Claude Code plugin、MCP tools、CLI search 和 specialist agents 的实际路径。
- 项目公开承认并修正了 benchmark 和 AAAK 描述里的问题，这让后续维护时更容易区分已验证能力与实验特性。

## 类似项目

- [MindFS](mindfs.md) - 更偏浏览器远程接入本地编码 Agent 工作台，而 `MemPalace` 更专注长期记忆与知识图谱层。
- [agent-file](agent-file.md) - 更关注 Agent 状态和能力的可移植封装，而 `MemPalace` 更强调对话、项目资料和记忆检索闭环。

## 官方链接

- **GitHub:** https://github.com/milla-jovovich/mempalace
- **Benchmark 文档:** https://github.com/milla-jovovich/mempalace/blob/main/benchmarks/BENCHMARKS.md
- **Gemini CLI 集成说明:** https://github.com/milla-jovovich/mempalace/blob/main/examples/gemini_cli_setup.md
- **更新记录:** https://github.com/milla-jovovich/mempalace/releases

## 标签

- `AI Memory`, `Claude Code`, `MCP`, `LongMemEval`, `Agent Workflow`

## 更新观察点

- 后续重点看 README 里已经承认的修正项是否真正落地，比如 benchmark 模式说明、`fact_checker.py` 接线和安全问题修复。
- 持续观察 Claude Code plugin、Gemini CLI 集成和 MCP tools 是否继续扩展，而不只是停留在 benchmark 叙事。
- AAAK 目前仍应视为实验层，后续维护时要分开确认 raw mode 的稳定能力和压缩层的真实收益。
