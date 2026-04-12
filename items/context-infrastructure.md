---
title: "Context Infrastructure"
slug: "context-infrastructure"
info_type: "awesome-ai-for-coding"
entity_type: "tool"
category: "Engineering Workflows"
featured: false
last_reviewed_at: "2026-04-12T00:00:00+00:00"
---

# Context Infrastructure

## 一句话总结

一个面向 AI coding agents 的 context 与 memory 参考实现，提供个人规则、技能、分层记忆和定时观察机制。

## 它解决什么问题

- AI 编码代理在长周期协作里容易丢上下文、忘偏好、重复踩坑
- 团队或个人想沉淀规则、skills 和长期记忆时，常缺少一个清晰的目录结构蓝图
- 很多 agent 工作流只有“当次会话上下文”，缺少可持续积累观察和反思的机制

## 适合谁

- 想给 Claude Code、Cursor、OpenCode 等编码 agent 加入持久上下文的人
- 希望搭建个人规则、技能和记忆系统的开发者
- 研究 AI 编程代理长期协作工作流的人

## 核心能力

- 根路由设计：通过 `AGENTS.md` 规定每次 session 的固定起点和读取顺序
- 规则分层：把身份、用户偏好、沟通方式、workspace 路由和 skills 分开管理
- 记忆系统：用 `contexts/memory/OBSERVATIONS.md` 承接动态记忆，并区分不同层级
- 周期任务：提供 observer / reflector 脚本，用定时任务自动积累观察与反思
- 参考实现定位：既能直接 clone 体验“有 context vs 没 context”的差异，也强调不可直接复制原作者经验

## 典型使用场景

- 为个人 coding agent 工作区搭建可持续进化的记忆与规则系统
- 给团队内的 AI 协作环境建立统一的目录路由和 session 启动规范
- 作为蓝图参考，拆解出自己的 rules、skills、memory 和 heartbeat 机制

## 为什么值得关注

- 它关注的不是单点工具，而是 AI 编程协作的长期基础设施
- README 和 AGENTS.md 把“每次会话先读什么、记忆怎么积累、技能怎么组织”讲得很具体
- 对正在搭建 agent-native coding workspace 的人来说，这类 reference implementation 很有借鉴价值

## 类似项目

- [CC-Switch CLI](cc-switch-cli.md) - 更偏本地 AI CLI / MCP / provider 配置管理；Context Infrastructure 更偏规则、记忆和工作区结构
- [Erduo Skills](../../awesome-ai-for-everything-in-life/items/erduo-skills.md) - 同样强调 skill 资产化，但 Erduo Skills 更偏内容工作流，Context Infrastructure 更偏编码 agent 的长期上下文系统

## 官方链接

- **GitHub:** https://github.com/grapeot/context-infrastructure
- **更新记录:** https://github.com/grapeot/context-infrastructure/releases

## 标签

- `AI Coding Agents`, `Memory`, `Context`, `Rules`, `Skills`, `Workflow`

## 更新观察点

- 后续重点看 `rules/skills/`、记忆结构和周期任务是否继续扩充
- 优先关注 README、`AGENTS.md`、`setup_guide.md` 和 releases 页面
- 如果后续加入更多 agent 适配说明、检索层实现或自动化维护脚本，值得更新条目
