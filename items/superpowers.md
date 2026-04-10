---
title: "Superpowers"
slug: "superpowers"
info_type: "awesome-ai-for-coding"
entity_type: "tool"
category: "工程工作流"
featured: true
last_reviewed_at: "2026-04-10T12:42:00+00:00"
---

# Superpowers

## 一句话总结

一个面向编码 Agent 的技能框架与软件开发方法论，把需求澄清、实现规划、TDD、子代理执行和代码评审串成自动触发的研发流程。

## 它解决什么问题

- 很多 AI 编码助手一上来就直接写代码，缺少先澄清目标、再设计、再规划的过程约束
- 团队即使用上了 Claude Code、Codex 这类工具，也很难把做法沉淀成统一可复用的工程流程
- 多 Agent 并行开发如果没有固定方法论，容易出现计划漂移、测试缺失和交付质量不稳定

## 适合谁

- 想把 AI 编码流程规范化的个人开发者
- 希望给 Claude Code、Codex、Cursor、OpenCode 增加强约束工作流的团队
- 在意 TDD、代码评审和分阶段验证的工程负责人

## 核心能力

- 技能驱动工作流：通过一组可组合 skills，让 agent 在不同阶段自动进入对应流程
- 研发流程编排：覆盖 brainstorming、writing-plans、subagent-driven-development 和 finishing-a-development-branch 等阶段
- 工程纪律约束：强调 true red/green TDD、YAGNI、DRY 和 verification-before-completion
- 多平台接入：支持 Claude Code、Cursor、Codex、OpenCode、Copilot CLI 和 Gemini CLI 的安装与使用

## 典型使用场景

- 给 Claude Code 或 Codex 增加更强的“先设计再开发”流程
- 用统一 skills 规范多人或多 agent 的软件开发协作方式
- 在复杂开发任务里把规划、测试、review 和执行拆成稳定的自动化步骤

## 为什么值得关注

- 它卖点不是单个新模型，而是把编码 Agent 的工作方式工程化
- 把技能系统、测试纪律和子代理协作放进一整套可复用方法论里
- 同时兼顾个人开发者和团队协作，适合做 AI 原生研发流程的基础层

## 类似项目

- [Multica](multica.md) - 更偏团队级任务分发与运行时协作平台，而 Superpowers 更偏编码 Agent 的方法论和技能系统。
- [claude-squad](claude-squad.md) - 更偏多会话协调工具，而 Superpowers 更强调软件开发流程本身的标准化与自动触发。

## 官方链接

- **GitHub:** https://github.com/obra/superpowers
- **更新记录:** https://github.com/obra/superpowers/releases

## 标签

- `编码 Agent`, `软件工程`, `Skills`, `TDD`, `工作流`, `Subagents`

## 更新观察点

- 后续重点看 skills 库是否继续扩展新的工程流程模块
- 观察不同平台安装方式是否继续统一，尤其是 Codex 和 Cursor 的集成体验
- 持续关注 releases 和 README，判断它是继续做方法论框架，还是往更完整插件生态演化
