---
title: "OpenCode"
slug: "opencode"
info_type: "awesome-ai-for-coding"
entity_type: "tool"
category: "Coding Agents"
featured: false
last_reviewed_at: "2026-04-11T05:00:00+00:00"
---

# OpenCode

## 一句话总结

一个开源 AI 编码 Agent，可在终端、桌面应用或 IDE 插件中运行，支持多会话并行、LSP 自动接入，并允许连接多家模型提供商。

## 它解决什么问题

- 许多编码 Agent 要么是闭源 SaaS，要么限制在单一入口，难以自由部署
- 多会话并行和多模型切换往往需要自己拼工具，学习成本高
- 开发者希望在终端、桌面和 IDE 之间自由选择最合适的交互方式

## 适合谁

- 想要开源、可自托管的编码 Agent 的开发者
- 需要在终端或桌面环境里并行跑多个 agent 会话的人
- 希望在不同模型和 provider 间自由切换的工程团队

## 核心能力

- 多入口运行：支持终端、桌面应用与 IDE 插件形态
- 多会话并行：可同时启动多个 agent 会话处理同一项目
- LSP 自动接入：自动加载语言服务提升上下文质量
- 多模型支持：可接入多家模型与 provider，并支持自带订阅

## 典型使用场景

- 在同一项目里让多个 agent 并行处理不同任务
- 在 CLI 环境里快速运行 agent，再在桌面端进行更细粒度审查
- 对比不同模型效果，选出更适合当前任务的 provider

## 为什么值得关注

- 作为开源编码 Agent 代表，覆盖入口丰富，适合不同使用习惯
- 多 provider 与多会话并行是其显著差异点
- 对重视可控性和私有化部署的团队有明显吸引力

## 类似项目

- [Claude Squad](claude-squad.md) - 更偏多会话与协作管理；OpenCode 强调开源与多入口运行。
- [CC-Switch CLI](cc-switch-cli.md) - 更偏多 CLI/Provider 配置管理；OpenCode 是具体的 agent 运行时。

## 官方链接

- **官网:** https://opencode.ai/
- **GitHub:** https://github.com/anomalyco/opencode
- **文档:** https://opencode.ai/docs
- **更新记录:** https://opencode.ai/changelog
- **下载:** https://opencode.ai/download

## 标签

- `Open Source`, `Coding Agent`, `CLI`, `Desktop App`, `Multi-Session`, `LSP`

## 更新观察点

- 关注桌面端与 IDE 插件是否持续增强
- 观察多模型与 provider 生态的扩展速度
- 如果其多会话与协作能力继续提升，可能进一步靠近工程工作流类产品
