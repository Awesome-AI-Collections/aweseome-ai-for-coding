---
title: "Octogent"
entity_type: "tool"
category: "Engineering Workflows"
last_reviewed_at: "2026-04-15"
---

# Octogent

## 一句话总结

一个面向 Claude Code 的多 agent 编排工作台，用 tentacles、`todo.md`、本地 API 和 UI 把多终端协作、子代理分工与上下文管理收进同一套开发界面。

## 快速判断

- 如果你已经在同时开多个 Claude Code 会话，并且被上下文混乱、任务切换和状态追踪折磨，它值得优先看
- 如果你只需要单会话 coding agent，或者不打算做多 agent 编排，不一定需要它这么重的 orchestration 层
- 它更像开发者直接使用的多 agent 编排产品，而不是单纯被 agent 调用的基础设施

## 你会怎么用它

- 接进 AI 开发流：把文档、数据库、API、前端等不同工作切成 tentacles，让多个 Claude Code 会话并行推进
- 接进日常工作流：用本地 UI 和 API 管理会话、消息、任务、worktree 状态和 handoff，而不是靠多个终端记忆
- 最小落地方式：先拿一个正在并行推进的项目，把最容易混乱的两三个任务拆成 tentacles 试跑

## 它解决什么问题

- 多个 Claude Code 会话一起跑时，开发者很容易忘记每个会话到底在做什么
- 长任务和并行任务缺少可持续的本地上下文容器，容易退化成聊天线程堆积
- 子代理分工、handoff、待办和消息经常散落在终端、笔记和脑内记忆之间

## 适合谁

- 想同时编排多个 Claude Code 会话的开发者
- 需要把多 agent coding workflow 组织成可视、可追踪流程的个人和小团队
- 重视上下文分片、任务委派和子代理协作的 AI coding 实践者

## 核心能力

- Tentacles 模型：给每块工作单独的上下文、笔记和 `todo.md`
- 多会话编排：允许多个 Claude Code 会话并行运行，并按任务切片组织
- 子代理协作：支持从 todo 项委派 child agents，并进行简短消息通信
- 本地 API + UI：不只是多开终端，还提供会话生命周期、消息、状态和持久化观察面
- 文件化上下文：把 agent 可读上下文放进文件，减少单线程 prompt history 依赖

## 能力边界

- 明显可用：多 Claude Code 会话并行、任务切片、handoff、上下文分层、开发者 orchestrator
- 效果一般：单 agent、轻量小项目、你根本不需要专门 orchestration 层的场景
- 不要误用：不要把它看成通用 provider 路由器或通用 CLI harness；当前文档重点仍在 Claude Code

## 集成方式

- 作为单独工具：直接本地运行 Octogent，用 UI 和 CLI 管理 tentacles 与会话
- 作为 AI 工作流组件：放在多 agent coding workflow 的编排层和观察层
- 作为团队流程节点：适合把任务拆分、handoff、子代理协作和状态追踪规范化，而不是继续靠口头同步

## 上手建议

- 第一步先不要把整个项目全搬进去，先试两三个最容易串线的任务切片
- 最值得先试的是“同一个项目里同时有文档、后端、前端在动”的场景
- 如果你现在还是单 agent 为主，先轻量体验 tentacles 和 `todo.md` 模型，不要一开始就重度依赖

## 选型建议

- 如果你的主需求是让多个 Claude Code 会话变得可管理、可分工、可追踪，适合看它
- 如果你的主需求是原生桌面并行 worktree 工作台，也可以同时比较 `Conductor` 和 `Superconductor`
- 如果你的主需求只是 agent CLI 本体或 provider 切换，Octogent 并不是那一层

## 为什么值得关注

- 它抓住了一个真实痛点：多终端 Claude Code 一旦规模上来，开发者心智负担会爆炸
- 它不是只做“多开窗口”，而是给了 tentacles、todo、消息和文件化上下文这一套更完整的工作模型
- 从定位上看，它很接近“AI coding environment 的 orchestration 层”，值得持续跟踪

## 类似项目

- [Conductor](conductor.md) - 同样面向开发者直接使用的多 agent 编排工作台；Conductor 更强调本地 worktree 与审查合并，Octogent 更强调 tentacles、todo 和文件化上下文。
- [Superconductor](superconductor.md) - 同样聚焦多 agent orchestration；Superconductor 更偏高性能原生桌面工作台，Octogent 更突出 Claude Code 协调、上下文分层和 child agent 行为组织。

## 官方链接

- **GitHub:** https://github.com/hesamsheikh/octogent
- **更新记录:** https://github.com/hesamsheikh/octogent/releases

## 标签

- `Claude Code`, `Multi-Agent`, `Orchestration`, `Terminal`, `Developer Workflow`

## 参考依据

- 这条说明主要依据项目 README、AGENTS.md、CLAUDE.md 和 releases 页面整理而成
- 关于“归入 coding 而不是 CLI”的判断，基于开发者会直接把它当多 agent orchestration 产品来使用，而不是只把它当底层控制面

## 更新观察点

- 后续优先观察它是否继续强化多 provider 支持，而不再只围绕 Claude Code
- 关注 tentacles、todo、child agent messaging 这套模型是否继续产品化
- 如果后续更强调终端控制面而弱化开发者工作台属性，需要重新复核 repo 归属
