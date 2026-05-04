---
title: "Trellis"
entity_type: "tool"
category: "Engineering Workflows"
last_reviewed_at: "2026-05-04"
---

# Trellis

## 一句话总结

一个面向团队 AI coding 的项目层与 workflow layer，把 specs、tasks、workspace memory 和多 agent 适配串成可持续协作流程，减少把整份 `AGENTS.md` / `CLAUDE.md` 全塞进每次会话的做法。

## 快速判断

- 如果你正在解决“多种 coding agent 共用同一套项目规则、任务上下文和长期记忆”这个问题，它值得优先看
- 如果你只想找一个给 agent 调用的第三方 CLI / MCP 工具面，而不是研发流程产品，先看别的方案
- 它更像开发者直接使用的 coding workflow 产品，不是给 agent 暴露第三方工具面的 CLI 本体

## 你会怎么用它

- 接进 AI 开发流：在仓库里初始化 `.trellis/`，把 spec、task、review、workspace memory 和 handoff 统一交给 Claude Code、Codex、Cursor、OpenCode 等 agent 读取
- 接进日常工作流：把 PRD、任务状态、团队规范和会话交接从零散 prompt 升级成仓库内长期维护的项目层
- 最小落地方式：先在一个真实代码仓里跑 `trellis init -u your-name`，只试 `spec`、`tasks` 和 `workspace` 三层是否真的减少上下文混乱

## 它解决什么问题

- 团队同时使用多种 coding agent 时，项目规则、决策和任务状态很容易散落在不同 prompt、不同工具和不同人脑子里
- 把所有背景都堆进 `AGENTS.md`、`CLAUDE.md` 或 `.cursorrules`，会让上下文越来越臃肿，也不利于按需加载
- AI coding 进入长期协作后，缺少任务级上下文、handoff 和记忆沉淀，会让后续 session 重复摸索

## 适合谁

- 正在用 Claude Code、Codex、Cursor、OpenCode 等工具做真实工程交付的个人和团队
- 想把 spec、task、review、workspace memory 和 handoff 固化成项目层结构的工程负责人
- 希望减少 AI coding 漂移、跨工具切换成本和上下文膨胀的开发者

## 核心能力

- 渐进式上下文加载：把原本容易膨胀成单大文件的规则拆进 `.trellis/spec/`、`.trellis/tasks/`、`.trellis/workspace/` 等分层目录
- 多平台适配：README 明确支持 Claude Code、Cursor、Codex、OpenCode、Pi Agent 等多种 coding agent
- 任务闭环：围绕 PRD、任务状态、review notes、acceptance criteria 和 session continuity 组织协作流程
- workflow 入口统一：通过 `/start`、`/trellis:start`、`continue`、`finish-work` 等入口把 agent 行为拉回同一套流程
- 项目内知识沉淀：把团队标准、决策、runbooks 和 session memory 留在仓库里，而不是只存在临时对话中

## 能力边界

- 明显可用：想给 AI coding 建立长期项目结构、任务上下文和多 agent 共识层的场景
- 效果一般：只想快速装一个命令行工具就开跑，或者只在单次 prompt 里轻量试用 AI 编码的场景
- 不要误用：不要把它当成“给 agent 接第三方能力的 CLI / MCP 工具面”；它的主价值不是暴露外部工具，而是组织研发流程本身

## 集成方式

- 作为单独工具：用 npm 安装后初始化到目标代码仓，把 `.trellis/` 作为项目层直接维护
- 作为 AI 工作流组件：放在 coding workflow 的 context / task / memory 层，而不是执行层或外部工具接入层
- 作为团队流程节点：适合承接 spec 编写、任务推进、handoff、review 前检查和经验回灌

## 上手建议

- 第一步先在一个真实项目里建立 `.trellis/`，不要先在空仓里只看概念
- 最值得先试的是“把一个正在做的真实任务写成 PRD，再让不同 agent 共用这份任务上下文”
- 如果你们团队目前还没有稳定的 task / review / handoff 习惯，先轻量试一个 repo，不要一开始大范围推广

## 选型建议

- 如果你的主需求是把 AI coding 从 prompt 协作升级成项目级 workflow，适合看它
- 如果你的主需求是 spec-first 开发方法论骨架，先对比 [Spec Kit](spec-kit.md)
- 如果你的主需求是给 agent 增加浏览器、Office、命令执行之类第三方工具面，它不是那类 CLI 仓项目

## 典型使用场景

- 给 Claude Code、Codex 和 Cursor 共享同一套项目规范、任务上下文和 workspace memory
- 在多人协作里用结构化 task / handoff 代替临时口头同步
- 把 session 决策和复盘沉淀回项目层，减少后续 agent 重复摸索

## 为什么值得关注

- 它关注的是“怎样让团队长期稳定地用 AI 写软件”，而不是单次生成效果
- 把 spec、task、memory、workflow 和多平台适配放进同一套项目层结构，比单纯补 prompt 更接近真实工程协作
- README、`AGENTS.md` 和 `CLAUDE.md` 都在强调行为边界与项目结构，说明它不是随意堆功能的工具集合

## 类似项目

- [Spec Kit](spec-kit.md) - 更偏 spec-driven development 方法论和命令入口；Trellis 更偏项目层、任务层和长期记忆层。
- [Context Infrastructure](context-infrastructure.md) - 更像面向 coding agents 的 context / memory 参考实现；Trellis 更偏可直接装进仓库的团队 workflow 产品。
- [Everything Claude Code](everything-claude-code.md) - 更偏跨 harness 的系统化配置与基础设施；Trellis 更聚焦任务、spec 和 session continuity 的项目层组织。

## 官方链接

- **文档:** https://docs.trytrellis.app/
- **GitHub:** https://github.com/mindfold-ai/Trellis
- **Quick Start:** https://docs.trytrellis.app/start/install-and-first-task
- **更新记录:** https://github.com/mindfold-ai/Trellis/releases

## 标签

- `AI Coding`, `Engineering Workflows`, `Specs`, `Tasks`, `Memory`, `Claude Code`, `Codex`, `Cursor`

## 参考依据

- 这条说明主要依据项目 README、`AGENTS.md`、`CLAUDE.md` 和 releases 页面整理而成
- 关于“归入 coding 而不是 CLI”的判断，基于它的主产品形态是开发者直接使用的 spec / task / workspace memory / workflow layer，而不是给 agent 调用的第三方工具面
- GitHub releases 页面当前为空，因此更新节奏更值得优先观察 README、文档站和 npm 安装入口

## 更新观察点

- 优先关注 `.trellis/` 目录结构、workflow 命令入口和多平台适配说明是否继续收敛
- 持续看 docs、README、`AGENTS.md`、`CLAUDE.md` 和 npm 包说明是否同步更新
- 如果后续 GitHub releases 仍然为空，要额外关注文档 changelog 与安装方式的变化，避免只靠仓库首页判断成熟度
