---
title: "gstack"
slug: "gstack"
info_type: "awesome-ai-for-coding"
entity_type: "tool"
category: "Engineering Workflows"
featured: true
last_reviewed_at: "2026-04-11T06:20:00+00:00"
---

# gstack

## 一句话总结

一个把 Claude Code 组织成虚拟工程团队的 agentic skills 与软件工厂框架，用一组 slash commands 把产品思考、规划、评审、QA、安全审计和发布串成端到端研发流程。

## 它解决什么问题

- 很多 Claude Code 用法仍然停留在“开个会话直接写”，缺少角色分工和阶段边界
- 开发者想把产品判断、工程评审、浏览器 QA 和发布流程都交给 AI，却没有统一工作台
- 即使有多 agent，没有流程的话也容易变成并行混乱而不是并行产出

## 适合谁

- 想把 Claude Code 用成完整研发工作台的开发者
- 希望把 AI 编码流程角色化、流程化的个人和小团队
- 重视 review、QA、ship 和安全检查闭环的 AI 原生构建者

## 核心能力

- 多角色技能系统：把 CEO、工程经理、设计师、QA、安全和发布等角色做成可调用技能
- 端到端流程链路：覆盖 `/office-hours`、规划评审、实现、review、QA、ship、retro 等完整环节
- 浏览器与验证能力：强调真实浏览器 QA、部署检查和发布前验证
- 可复制的软件工厂：通过 Markdown 技能和命令，把个人经验转成可复用流程

## 典型使用场景

- 在一个 Claude Code 体系里同时处理产品方向、编码实现、QA 和发布
- 给个人开发者建立“像团队一样工作”的多角色 AI 流程
- 把经验性的工程判断沉淀成 slash commands，而不是反复口头提示

## 为什么值得关注

- 它不是单点提示词合集，而是完整的软件工厂打法
- 公开透明地展示了一个重度 AI 原生开发者如何高频交付
- 对想把 Claude Code 从“助手”升级成“工程系统”的人很有参考价值

## 类似项目

- [Superpowers](superpowers.md) - 同样强调技能系统和软件工程纪律，但 Superpowers 更偏方法论与执行约束；gstack 更像一套高频实战的软件工厂。
- [Get Shit Done](get-shit-done.md) - 同样重视 context engineering 和流程稳定性，但 GSD 更偏上下文治理；gstack 更强调多角色工作流与实际 ship 链路。

## 官方链接

- **GitHub:** https://github.com/garrytan/gstack
- **文档目录:** https://github.com/garrytan/gstack/tree/main/docs
- **更新记录:** https://github.com/garrytan/gstack/releases

## 标签

- `Claude Code`, `Skills`, `Engineering Workflow`, `QA`, `Code Review`, `Agentic Development`

## 更新观察点

- 持续看技能集是否继续扩展到更多工程环节
- 关注 `/browse`、QA、ship 相关工作流是否进一步产品化
- 也值得观察它会不会从 Claude Code 重度绑定逐步扩展到更多 agent runtime
