---
title: "CodePilot"
slug: "codepilot"
info_type: "awesome-ai-for-coding"
entity_type: "tool"
category: "Engineering Workflows"
featured: false
last_reviewed_at: "2026-04-10T00:00:00+00:00"
---

# CodePilot

## 一句话总结

一个多模型 AI Agent 桌面客户端，支持多 provider、MCP、Skills、文件浏览、Git 面板和远程桥接，适合把编码型 Agent 作为日常桌面工作台来用。

## 它解决什么问题

- 纯 CLI 形态的编码 Agent 对很多人来说不够直观，日常切模型、切会话和看工作区状态比较分散
- 同时接多个 provider、MCP server 和技能时，配置入口和运行状态不容易统一管理
- 想把桌面端、手机端和项目工作区串起来时，常常需要自己拼很多零散工具

## 适合谁

- 想把 Claude Code 类能力放进桌面 GUI 的开发者
- 需要统一管理多模型、MCP、技能和项目工作区的人
- 希望把编码 Agent 扩展成日常桌面工作台的重度用户

## 核心能力

- 多 provider 接入：可连接 17+ AI provider，并在对话中切换模型与 provider
- MCP 与 Skills：支持 MCP server、技能市场和自定义技能扩展
- 工作区能力：带文件树、语法高亮预览、Git 面板和会话检查点
- 桌面体验：Electron + Next.js，支持分屏会话、成本统计、深浅色主题
- 远程桥接：可通过 Telegram、Feishu、Discord、QQ、WeChat 等渠道做手机端控制

## 典型使用场景

- 在桌面 GUI 中统一管理多个编码 Agent 会话和不同模型提供商
- 给本地项目接上 MCP、技能和 Git 视图，形成更完整的开发工作台
- 在手机上发消息远程驱动桌面端 Agent，适合长任务或不在工位时查看结果
- 用 Assistant Workspace 维护 persona、memory 和 daily check-in，让 Agent 更贴近日常使用

## 为什么值得关注

- 它不是单纯把聊天窗口套个桌面壳，而是在往“AI Agent 操作系统”方向走
- README、AGENTS 和 CHANGELOG 对功能边界、开发规则和最近迭代写得比较完整
- 对想把 Claude Code 之外的 provider、MCP 与技能统一到一个桌面入口的人很有参考价值

## 类似项目

- [CC-Switch CLI](cc-switch-cli.md) - 更偏多 AI CLI 的配置管理；CodePilot 更强调桌面 GUI 和运行工作台体验
- [claude-squad](claude-squad.md) - 更偏多会话协作管理；CodePilot 还补了文件浏览、Git、桥接和 Assistant Workspace

## 官方链接

- **官网:** https://www.codepilot.sh/docs
- **GitHub:** https://github.com/op7418/CodePilot
- **更新记录:** https://github.com/op7418/CodePilot/releases

## 标签

- `桌面客户端`, `AI Agent`, `MCP`, `Skills`, `Claude Code`, `Electron`

## 更新观察点

- 后续重点看它对 Claude Code CLI、MCP 和 Skills 市场的整合深度
- 优先观察 README、CHANGELOG 和 releases，跟踪桌面工作区、远程桥接和 provider 兼容性更新
- 如果后续继续强化 Git、文件编辑和多会话编排，值得进一步提升在 coding repo 的权重
