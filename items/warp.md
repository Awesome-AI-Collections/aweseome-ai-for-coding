---
title: "Warp"
entity_type: "tool"
category: "AI IDEs / Editors"
last_reviewed_at: "2026-04-15"
---

# Warp

## 一句话总结

一个把终端、AI agent、代码审查和远程协作收进同一工作台的开发者终端应用，现已对 Claude Code、Codex、OpenCode 和 Gemini CLI 提供一等支持。

## 快速判断

- 如果你长期在终端里跑多个 coding agent，并希望把审查、通知和输入体验一起升级，它值得优先看
- 如果你只需要一个最朴素的 shell 窗口，不一定需要它这套 AI workbench 叙事
- 它更像开发者直接使用的 AI 终端工作台，而不是被 agent 调用的 CLI 基础设施

## 你会怎么用它

- 接进 AI 开发流：把 Claude Code、Codex、Gemini CLI、OpenCode 等 agent 直接跑在 Warp 里，并利用集成代码审查、通知和富输入提高多会话效率
- 接进日常工作流：把终端、标签页、审查、远程提醒和手机端查看统一到一个开发工作台里
- 最小落地方式：先把你最常开的 1 到 2 个 agent CLI 会话迁进去，观察通知、输入编辑和 review 体验是否真能减少切换成本

## 它解决什么问题

- 多个 AI coding CLI 同时运行时，普通终端往往缺少针对 agent 交互优化的提醒、输入和审查体验
- 开发者在终端里做 agent 协作时，常常还要额外切去别的工具看 diff、收通知或远程盯状态
- terminal-first 工作流越来越像主战场，但传统终端对 agent-native 场景支持还不够完整

## 适合谁

- 长期在终端里跑 Claude Code、Codex、Gemini CLI、OpenCode 等 agent 的开发者
- 想把终端、审查、通知和远程协作收进同一工作台的人
- 把 terminal-first 开发环境当作日常主工作台的团队

## 核心能力

- 多 agent 一等支持：官方已明确支持 Claude Code、Codex、OpenCode 和 Gemini CLI
- 集成代码审查：可直接在终端工作台里查看和处理代码审查相关流程
- agent 通知与呼叫感知：当 agent 需要你介入时，能更及时把人拉回当前任务
- 富输入体验：提供更适合长 prompt、结构化输入和多行编辑的输入界面
- 远程控制：可从移动端远程查看和控制终端会话

## 能力边界

- 明显可用：把多个 coding agent CLI 长时间跑在终端里的日常开发场景
- 效果一般：如果你的主工作台始终是传统 IDE，终端只偶尔打开一次，它的价值会没那么明显
- 不要误用：它不是 coding agent 本体，也不是 provider 路由器或通用 MCP 平台

## 集成方式

- 作为单独工具：直接把它作为主终端应用，用来承载日常 shell、tmux 和 agent CLI 会话
- 作为 AI 工作流组件：放在最外层工作台，承载多 agent 运行、人工介入和审查动作
- 作为团队流程节点：适合统一一套更贴近 agent-native 开发的终端协作环境

## 上手建议

- 第一步先迁移最常驻的 agent 会话，而不是一次性替换全部终端习惯
- 最值得先试的是长时间运行的 coding agent 和需要频繁人工接力的任务
- 如果你当前主要痛点不是终端层，而是模型、上下文或工作流本身，可以先轻量试用

## 选型建议

- 如果你的主需求是给 AI coding CLI 找一个更完整的开发工作台，它很合适
- 如果你的主需求是“获得一个新 agent”或“统一 provider 路由”，先看别的项目
- 如果你在比较的是终端型 AI 工作台，而不是纯终端性能本身，它比传统终端更有参考价值

## 典型使用场景

- 同时运行多个 Claude Code、Codex 或 Gemini CLI 会话，并在需要时接收提醒
- 在终端里直接做代码审查和人工接力，而不是在多工具间反复切换
- 出门时通过移动端远程查看 agent 进度或做轻量控制

## 为什么值得关注

- 终端正在从“命令入口”变成 AI coding 的主工作台之一，Warp 明显在顺着这个方向做产品
- 它不是单纯把 AI 按钮加进终端，而是在重做 agent-native 的输入、提醒和审查体验
- 对重度 Claude Code / Codex 用户来说，这一层工作台摩擦会直接影响每天的真实效率

## 类似项目

- [Ghostty](ghostty.md) - 同样是开发者终端工作台，但 Ghostty 更偏现代终端体验与性能；Warp 更强调 AI agent 支持和工作台能力
- [iTerm2](iterm2.md) - 更偏成熟稳定的传统终端底座；Warp 更主动朝 AI coding workbench 方向延伸

## 官方链接

- **官网:** https://warp.dev

## 标签

- `Terminal`, `Developer Workspace`, `Claude Code`, `Codex`, `Gemini CLI`, `OpenCode`

## 参考依据

- 主要依据官方产品页与官方对第三方 CLI agents 支持的公开说明整理
- 用户补充的功能点包括 vertical tabs、notifications、integrated code review、mobile remote control 与 rich input editor，已与官方叙事方向一致

## 更新观察点

- 后续重点看它对第三方 agent CLI 的支持范围是否继续扩大
- 优先关注官网产品页、更新日志和 AI 功能说明，而不是只看转发摘要
- 如果它进一步增强 review、remote control 或多 agent orchestration，值得补充条目边界
