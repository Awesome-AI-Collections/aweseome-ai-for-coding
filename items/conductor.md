---
title: "Conductor"
slug: "conductor"
info_type: "awesome-ai-for-coding"
entity_type: "tool"
category: "工程工作流"
featured: false
last_reviewed_at: "2026-04-11T03:30:00+00:00"
---

# Conductor

## 一句话总结

一个原生 macOS 编码 Agent 编排工作台，帮助开发者在本机为 Claude Code 和 Codex 创建隔离 worktree，会话可并行运行，并在同一界面里集中查看进度、审查改动与合并结果。

## 它解决什么问题

- 多个编码 Agent 同时跑任务时，终端、分支、worktree 和改动状态很容易散落在不同窗口里
- 直接让 agent 在同一工作区反复改动，容易互相污染上下文和分支历史
- 开发者希望把并行执行、代码审查和合并流程放在一个更直观的桌面界面里

## 适合谁

- 想在本机并行运行多个编码 Agent 的开发者
- 需要在 worktree 级别隔离不同任务和分支的人
- 希望把 agent 执行、审查和 merge 收进一个桌面工作流的重度用户

## 核心能力

- 并行 Agent 调度：支持同时部署 Claude Code 和 Codex 处理不同任务
- 隔离工作区：每个 agent 会话对应独立 git worktree，减少互相污染
- 统一观察面板：可以一眼看到谁在工作、谁需要人工介入、哪些改动值得审查
- 审查与合并：在同一工具里完成 diff review 和 merge，而不是来回切多个窗口

## 典型使用场景

- 同时开多个 agent 处理不同 issue，再统一收敛到人工审查环节
- 在本机用 worktree 隔离并行实验，减少长任务对主分支工作的干扰
- 把 Claude Code / Codex 从“多个独立终端”提升成可管理的并行工作流

## 为什么值得关注

- 它的定位非常聚焦，就是解决“本机并行编码 Agent 编排”这个具体痛点
- 强调完全在本机运行，对偏好本地代码与凭据留在自己机器上的用户很有吸引力
- 产品叙事简洁，功能边界也清楚，适合作为这条赛道的代表项目之一持续观察

## 类似项目

- [Superconductor](superconductor.md) - 同样强调原生桌面和 worktree 并行，但 Superconductor 的叙事更偏完整高性能工作台；Conductor 更像围绕 Claude Code / Codex 的聚焦型编排工具。
- [Acepe](acepe.md) - 同样做多 Agent 工程流程，但 Acepe 覆盖权限队列、checkpoint 和 PR 工作流更广；Conductor 更轻、更聚焦本机并行执行与审查。

## 官方链接

- **官网:** http://conductor.build/
- **更新记录:** https://www.conductor.build/changelog

## 标签

- `Multi-Agent`, `Worktrees`, `Claude Code`, `Codex`, `macOS`, `Workflow`

## 更新观察点

- 后续重点看是否扩展到更多编码 Agent 和模型入口
- 关注审查、merge 和任务分配能力是否继续加深
- 如果将来加入团队协作或云端同步，产品定位可能会进一步外延
