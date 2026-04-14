---
title: "con"
entity_type: "tool"
category: "AI IDEs / Editors"
last_reviewed_at: "2026-04-15"
---

# con

## 一句话总结

一个带内置 AI harness 的原生终端应用，适合把 SSH、tmux 和 agent-native workflows 收进同一套开发者工作台。

## 快速判断

- 如果你本来就是 terminal-first 开发者，但希望在不牺牲真实 PTY 和 shell 可见性的前提下按需接入 AI，它值得看
- 如果你只想找成熟稳定的传统终端，而不需要内置 AI harness，不一定要优先选它
- 它更像开发者直接使用的终端工作台，而不是纯 CLI 工具集合

## 你会怎么用它

- 接进 AI 开发流：把 Claude Code、SSH、tmux 和其他 agent-native workflow 都放进同一个带 AI harness 的终端环境里
- 接进日常工作流：让终端保持主入口，同时在需要时调用 AI 读取上下文、辅助判断或执行可见操作
- 最小落地方式：先把一个你最常开的 coding agent 会话和一个远程 / tmux 会话迁进去试

## 它解决什么问题

- 很多带 AI 的终端产品会把 shell 感做弱，老派终端用户不愿意为 AI 失去 PTY 可见性和控制感
- 开发者经常在普通终端、SSH、tmux 和 agent CLI 之间来回切换，AI 辅助也缺少统一落点
- 如果终端本身不够稳，AI coding workflow 的实际体验很容易被窗口和会话摩擦拖垮

## 适合谁

- 把终端当主工作台、但希望按需接入 AI harness 的开发者
- 重视 SSH、tmux 和 agent-native workflow 的终端重度用户
- 想把传统终端体验和 AI coding 辅助合在一起的人

## 核心能力

- 原生终端工作台：提供 macOS 原生窗口、标签页和分屏终端体验
- 内置 AI harness：AI 能力直接接进终端，而不是另开一个聊天壳子
- terminal-first 取向明确：强调真实 PTY、可见 shell 和可追责的 agent 行为
- agent-native workflow 友好：README 明确围绕 SSH、tmux 和 coding-agent CLI 设计
- GPU 加速与本地优先：更接近长期使用的开发工作台，而不是临时 demo

## 能力边界

- 明显可用：terminal-first AI coding、SSH / tmux 开发、需要 AI 但又不想失去终端控制感的场景
- 效果一般：只偶尔开 shell、或更偏浏览器 / IDE 中心工作的场景
- 不要误用：它不是 provider 路由器、也不是多 agent orchestration 平台；核心仍是终端本身

## 集成方式

- 作为单独工具：直接把它作为你的默认终端应用使用
- 作为 AI 工作流组件：承载 Claude Code、SSH、tmux、日志窗口和其他 terminal-native agent workflow
- 作为团队流程节点：适合团队成员统一一套更贴近 AI coding 的终端工作台习惯

## 上手建议

- 第一步先别全量迁移，把一个主力 coding agent 会话和一个远程会话切进去试
- 最值得先试的是“既要 shell 透明度，又要 AI harness”的长会话工作
- 如果你当前已经在 iTerm2 / Ghostty 上有很重配置，先轻量试用，不要一开始就全部切换

## 选型建议

- 如果你的主需求是“终端优先，但要内建 AI harness”，适合看它
- 如果你的主需求是最成熟的传统终端生态，iTerm2 一类工具可能更稳
- 如果你的主需求是多 agent 编排和任务 orchestration，应该继续看 Octogent、Conductor 一类产品

## 为什么值得关注

- 它试图回答一个很实用的问题：AI 该怎么进终端，而不是把终端替掉
- 产品叙事很克制，强调“AI help only when it earns its place”，对重度终端用户比较有吸引力
- 对 terminal-first 的 AI coding 用户来说，这类“少做一点、但做对位”的产品很值得持续观察

## 类似项目

- [Ghostty](ghostty.md) - 同样是终端工作台，但更偏现代终端体验；con 更强调内置 AI harness 和 terminal-first 取舍。
- [iTerm2](iterm2.md) - 同样是 macOS 终端底座，但 iTerm2 更偏成熟稳定传统方案；con 更偏“原生终端 + AI harness”。

## 官方链接

- **GitHub:** https://github.com/nowledge-co/con
- **更新记录:** https://github.com/nowledge-co/con/releases

## 标签

- `Terminal`, `AI Harness`, `macOS`, `SSH`, `tmux`

## 参考依据

- 这条说明主要依据项目 README、CHANGELOG、AGENTS.md、CLAUDE.md 和 releases 页面整理而成
- 关于“归入 coding 而不是 CLI”的判断，基于它首先是开发者直接使用的终端工作台，而不是单纯命令面集合

## 更新观察点

- 后续优先观察 AI harness 的能力边界是否继续扩展，而不只是终端壳子
- 关注 macOS 之外的平台支持、SSH / tmux 体验和 agent-native workflow 细节是否继续增强
- 如果它后续更强调编排层而不再是终端本体，需要重新复核 repo 归属
