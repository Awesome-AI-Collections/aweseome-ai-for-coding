---
title: "NetEase Skills"
slug: "netease-skills"
info_type: "awesome-ai-for-coding"
entity_type: "tool"
category: "工程工作流"
featured: false
last_reviewed_at: "2026-04-11T00:00:00+00:00"
---

# NetEase Skills

## 一句话总结

网易云音乐团队维护的 agent skills 仓库，提供可供 Claude Code 等工具安装的技能包，包括 `ncm-cli` 等音乐相关能力。

## 它解决什么问题

- 很多 AI agent 集成即使有 CLI，本身也缺少可发现、可安装的 skill 层
- 团队想把服务能力接给 Claude Code、OpenClaw 等宿主时，需要更标准的技能分发方式
- 如果没有统一 skills 仓库，终端能力很难沉淀成稳定的 agent 使用入口

## 适合谁

- 想给 Claude Code 或 OpenClaw 安装网易云相关技能的开发者
- 在做 agent skill 分发和工具接入的团队
- 需要把具体 CLI 能力包装成 agent 可直接调用技能的人

## 核心能力

- Skills 分发：提供可安装的技能包仓库入口
- 音乐能力接入：围绕 `ncm-cli` 等能力组织 agent 使用路径
- 多宿主兼容：在提供材料中已明确提到 Claude Code 与 OpenClaw 集成
- 工程化复用：把“具体工具能力”提升成“agent 可复用技能”

## 典型使用场景

- 用 `npx skills add https://github.com/NetEase/skills` 给 Claude Code 安装技能
- 给 OpenClaw 安装网易云相关的 assistant / CLI skills
- 把终端工具和自然语言控制串成统一的 agent 工作流

## 为什么值得关注

- 它补的是 CLI 之上的 skill 分发层，这对 agent 生态很关键
- 对中文场景来说，这类官方 skills 仓库比零散教程更容易长期维护
- 它也说明网易云这类消费级服务开始认真做 agent 接入路径

## 类似项目

- [Superpowers](superpowers.md) - 更偏软件工程方法论和技能框架，不聚焦单一服务接入
- [cli-creator](cli-creator.md) - 更偏如何构建 durable CLI，而 `NetEase Skills` 更偏技能分发与接入

## 官方链接

- **GitHub:** https://github.com/NetEase/skills

## 标签

- `Skills`, `Agent`, `Claude Code`, `OpenClaw`, `NetEase`

## 更新观察点

- 后续重点看 skills 数量、支持宿主和安装路径是否继续扩展
- 优先重新抓取仓库 README、技能目录和 releases / tags
- 如果后续出现更通用的 skill schema 或更多服务能力，值得补进正文
