---
title: "HappyClaw"
slug: "happyclaw"
info_type: "awesome-ai-for-coding"
entity_type: "tool"
category: "Coding Agents"
featured: false
last_reviewed_at: "2026-04-08T00:00:00+00:00"
---

# HappyClaw

## 一句话总结

一个基于 Claude Code 运行时构建的自托管多用户 AI Agent 系统，重点在于把编程 agent 能力接入团队协作环境，并支持 Web 与多种即时通信渠道。

## 它解决什么问题

- 团队想把 Claude Code 这类编程 agent 用在真实协作中，但缺少适合多用户与多渠道接入的运行环境
- 个人终端型 agent 工具不容易直接接入飞书、Telegram、微信等团队沟通场景
- 自托管用户需要更强的权限隔离、运行时控制与统一接入层，而不是只依赖单机本地使用

## 适合谁

- 希望把 Claude Code 接入团队协作流的开发者和技术团队
- 对自托管、多用户隔离和消息渠道接入有明确需求的组织
- 想把 AI agent 放进 Web 和 IM 协作入口里的高级用户

## 核心能力

- 多用户自托管：适合在团队内部统一部署，并对不同用户做隔离
- 多渠道接入：支持 Web 界面以及飞书、Telegram、QQ、钉钉、微信等消息渠道
- 运行时能力复用：基于 Claude Agent SDK 与 Claude Code 运行时能力构建
- 工具调用扩展：支持文件读写、终端操作、浏览器自动化、定时任务和记忆系统等能力

## 典型使用场景

- 在企业或团队内部部署一个可多人共用的编程 agent 系统
- 把编程 agent 能力通过飞书、Telegram 等沟通入口暴露给团队成员
- 为自托管环境建立统一的 agent 运行层，而不是每个人只在本地单独使用

## 为什么值得关注

- 它不是单纯的“本地 CLI 工具”，而是在做面向团队使用的自托管 agent 系统
- 多渠道接入能力让编程 agent 更容易进入真实协作环境，而不是只停留在终端里
- 对关心自托管、安全边界和团队接入方式的人来说，这类项目比单机工具更有长期观察价值

## 类似项目

- [Multica](multica.md) - 更偏向研发任务分发、执行跟踪和团队技能沉淀，协作流程更强，消息渠道接入不是主轴
- [CC-Switch CLI](cc-switch-cli.md) - 更偏向本地工具链与 provider/MCP 配置管理，适合作为底层工作流工具，不是多用户 agent 系统

## 官方链接

- **GitHub:** https://github.com/riba2534/happyclaw
- **更新记录:** https://github.com/riba2534/happyclaw/releases

## 标签

- `Claude Code`, `编程 Agent`, `自托管`, `多用户`, `IM 集成`

## 更新观察点

- 后续重点关注支持的消息渠道、权限模型和团队管理能力是否继续扩展
- 优先重新抓取 README、CLAUDE.md 与 releases，观察运行时能力和部署方式是否有明显演进
- 如果后续出现更明确的插件生态、工作流编排或企业级治理能力，值得补充进正文
