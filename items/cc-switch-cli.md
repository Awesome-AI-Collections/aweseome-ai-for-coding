---
title: "CC-Switch CLI"
slug: "cc-switch-cli"
info_type: "aweseome-ai-for-coding"
entity_type: "tool"
category: "工程工作流"
featured: true
last_reviewed_at: "2026-04-08T00:00:00+00:00"
---

# CC-Switch CLI

## 一句话总结

一个面向 AI CLI 重度用户的跨平台配置管理工具，核心价值是统一管理 Claude Code、Codex、Gemini、OpenCode 与 OpenClaw 的 provider、MCP 与相关工作流配置。

## 它解决什么问题

- 同时使用多个 AI CLI 工具时，provider、MCP、prompt、代理和环境检查容易散落在多套命令与配置文件里
- 切换不同 provider 或不同应用时，经常需要手工改配置，成本高且容易出错
- 多个工具共存时，临时切换运行环境和排查本地配置状态会变得繁琐

## 适合谁

- 同时使用 Claude Code、Codex、Gemini 等多种 AI CLI 的开发者
- 需要经常切换 provider、MCP 或代理路由的 AI CLI 重度用户
- 想把本地 AI 编程工具链管理得更统一、更少手工操作的工程团队

## 核心能力

- 多应用统一管理：同一套 CLI/TUI 下管理 Claude、Codex、Gemini、OpenCode 与 OpenClaw
- Provider 切换：统一查看、切换与检查不同 provider 的状态
- MCP 与提示词管理：帮助同步 MCP servers、查看提示词和相关配置
- 环境与路由检查：集中处理本地代理路由、工具状态和环境检查问题
- 临时启动能力：可在不改全局当前 provider 的前提下临时启动 Claude 或 Codex

## 典型使用场景

- 在本地同时维护多种 AI CLI 工具，并希望统一管理 provider 与 MCP
- 频繁切换不同 relay/provider，但又不想反复手工修改配置文件
- 排查本地 AI CLI 环境、代理和工具状态是否正常

## 为什么值得关注

- 它关注的是 AI CLI 工具链管理这个高频但长期被低估的问题
- 随着开发者同时使用多个模型与多个 CLI，统一配置层会越来越重要
- 它已经不只是单纯切换 provider，而是在向更完整的 AI CLI 运维工作流演进

## 类似项目

- [Multica](multica.md) - 更偏向团队级编程 agent 协作与任务编排，不负责本地多 CLI 配置治理
- [HappyClaw](happyclaw.md) - 更偏向自托管多用户 agent 系统与消息渠道接入，不是本地 CLI 配置管理层

## 官方链接

- **GitHub:** https://github.com/SaladDay/cc-switch-cli
- **更新记录:** https://github.com/SaladDay/cc-switch-cli/blob/main/CHANGELOG.md

## 标签

- `Claude Code`, `Codex`, `Gemini`, `MCP`, `CLI`

## 更新观察点

- 后续重点观察它是否继续扩展到更多 AI CLI 宿主与更深的配置治理能力
- 优先重新抓取 README、CHANGELOG 与 releases，跟踪临时启动、MCP 编辑和多应用支持的演进
- 如果后续出现更明确的团队协作能力、配置同步策略或插件机制，值得补入正文
