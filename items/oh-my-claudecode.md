---
title: "oh-my-claudecode"
slug: "oh-my-claudecode"
info_type: "awesome-ai-for-coding"
entity_type: "tool"
category: "Engineering Workflows"
featured: false
last_reviewed_at: "2026-04-11T06:20:00+00:00"
---

# oh-my-claudecode

## 一句话总结

一个面向 Claude Code 的零学习曲线多 Agent 编排插件，提供 `/team`、`/autopilot`、`/deep-interview` 等技能和 CLI worker 流程，把规划、执行、验证和多模型协作收进统一工作流。

## 它解决什么问题

- Claude Code 新用户常常不知道从哪些命令和工作流开始，学习曲线不低
- 多 agent 协作、tmux worker 和跨模型支援通常需要自己手动拼装
- 团队想让 Claude Code 更像“可直接上手的自动化团队”，而不是一堆零散命令

## 适合谁

- 想快速把 Claude Code 用成多 Agent 工作台的开发者
- 需要 tmux worker、跨模型协作和自动化执行的重度用户
- 希望降低团队采用 Claude Code 门槛的人

## 核心能力

- 会话内技能入口：通过 `/team`、`/autopilot`、`/deep-interview` 等技能组织不同工作模式
- CLI worker 编排：支持 `omc team` 启动 tmux worker，接入 Codex、Gemini 等外部 CLI
- 插件化安装：支持 Claude Code marketplace/plugin 流程，也支持 npm CLI 路径
- 自然语言工作流：强调“不要学一堆命令，直接开始用”

## 典型使用场景

- 给 Claude Code 增加开箱即用的多 agent 编排体验
- 用 `/deep-interview` 先梳理需求，再让 `/autopilot` 或 `/team` 推进实现
- 在 Claude Code 主流程外，引入 Codex 或 Gemini 做外部审查与并行执行

## 为什么值得关注

- 它抓住了 Claude Code 最常见的痛点：强大但门槛不低
- 会话内技能和 CLI worker 两套入口并存，适合不同用户习惯
- 对“如何把 Claude Code 做成团队产品”这件事有比较清晰的答案

## 类似项目

- [claude-squad](claude-squad.md) - 同样关注多会话和多 agent 协作，但 oh-my-claudecode 更强调插件式上手和 `/team` 流程。
- [gstack](gstack.md) - 同样把 Claude Code 拉升成完整工作流系统，但 gstack 更像软件工厂；oh-my-claudecode 更像易上手的多 agent 编排层。

## 官方链接

- **GitHub:** https://github.com/Yeachan-Heo/oh-my-claudecode
- **文档站:** https://yeachan-heo.github.io/oh-my-claudecode-website
- **更新记录:** https://github.com/Yeachan-Heo/oh-my-claudecode/releases

## 标签

- `Claude Code`, `Multi-Agent`, `Plugin`, `tmux`, `Workflow`, `Autopilot`

## 更新观察点

- 关注 `/team` 和 CLI worker 两套运行时是否继续收敛
- 持续看 Codex、Gemini 等外部 worker 的集成稳定性
- 也值得观察它会不会继续扩展成更完整的 Claude Code 团队工作台
