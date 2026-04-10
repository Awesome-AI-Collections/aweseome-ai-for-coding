---
title: "Superconductor"
slug: "superconductor"
info_type: "awesome-ai-for-coding"
entity_type: "tool"
category: "工程工作流"
featured: true
last_reviewed_at: "2026-04-10T18:10:00+00:00"
---

# Superconductor

## 一句话总结

一个原生 macOS 多 Agent 编排工作台，可在隔离 git worktree 中并行运行 Claude Code、Codex、Gemini CLI 等编码代理，并集中做 diff 审查、分支管理和交付。

## 它解决什么问题

- 多个编码 Agent 并行工作时，终端、worktree、分支和 PR 状态很容易散落在不同窗口里
- Web 技术栈做的 orchestration 工具在性能、终端体验和并发规模上经常受限
- 开发者希望把 agent 运行、审查和交付收进同一个高响应原生工作台

## 适合谁

- 想并行运行多个编码 Agent 的开发者
- 需要在一个界面里管理 worktree、diff 和 agent 会话的重度用户
- 偏好原生桌面性能和键盘驱动工作流的 AI 工程用户

## 核心能力

- 并行 Agent 编排：支持 Claude Code、Codex、Gemini CLI 等多种 CLI Agent 同时运行
- Worktree 管理：自动在隔离 git worktree 中启动会话，减少分支互相污染
- 审查与交付：集中查看 diff、跟踪 PR 状态并完成 merge / ship 流程
- 原生桌面体验：100% Rust、GPU 渲染终端、丰富布局和会话恢复能力

## 典型使用场景

- 同时让多个编码 Agent 并行推进不同任务，再统一审查结果
- 在桌面端高效切换 worktree、会话和分支，而不是手动拼多终端
- 给 AI 原生研发流程提供一个更强的本地 orchestrator

## 为什么值得关注

- 方向很明确：不是再包一层聊天界面，而是做真正的并行 agent 工作台
- 原生性能和无限并发定位，在同类产品里差异比较明显
- 对大量使用 Claude Code / Codex 这类 CLI Agent 的人很贴合

## 类似项目

- [Multica](multica.md) - 更偏团队级任务协作平台，而 Superconductor 更像本地并行 Agent 桌面工作台。
- [MindFS](mindfs.md) - 更偏浏览器远程接入本地 Agent，而 Superconductor 更强调原生桌面并行 orchestration。

## 官方链接

- **官网:** https://super.engineering/

## 标签

- `Multi-Agent`, `Worktrees`, `Claude Code`, `Codex`, `macOS`, `Workflow`

## 更新观察点

- 后续重点看 Windows / Linux 支持是否落地
- 关注并行 agent 数量、审查流和交付流是否继续增强
- 持续观察它是否扩展到更完整的团队协作或云端能力
