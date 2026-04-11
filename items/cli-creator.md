---
title: "cli-creator"
slug: "cli-creator"
info_type: "awesome-ai-for-coding"
entity_type: "tool"
category: "工程工作流"
featured: false
last_reviewed_at: "2026-04-11T00:00:00+00:00"
---

# cli-creator

## 一句话总结

OpenAI 提供的 Codex 技能，用来从 API 文档、OpenAPI、SDK、curl 样例或现有脚本快速设计并构建可长期复用的 CLI。

## 它解决什么问题

- 很多团队都有“这个内部系统应该有个 CLI”这种需求，但缺少一套稳定的构建方法
- agent 临时写的一次性脚本通常不够耐用，难以沉淀成可安装、可复用工具
- 从资料源到命令面设计、认证策略、JSON 契约和 companion skill，工程化细节很容易遗漏

## 适合谁

- 想让 Codex 为内部系统或第三方 API 构建正式 CLI 的开发者
- 需要把一次性脚本升级成长期可复用命令工具的团队
- 在做 agent-native 工具层、内部运维 CLI 或自动化接口封装的人

## 核心能力

- 来源适配：支持从 API docs、OpenAPI、SDK、curl 示例、现有脚本和网页流程出发构建 CLI
- 命令面设计：强调 discovery、resolve、read、write、raw escape hatch 和 `doctor --json`
- 工程化约束：明确认证优先级、JSON 输出策略、安装到 PATH、跨目录 smoke test 和验证步骤
- 技能联动：要求 CLI 可配套 companion skill，方便未来 Codex 线程正确调用

## 典型使用场景

- 给内部后台、SaaS 平台或第三方 API 生成正式的终端 CLI
- 把一段已经可跑的 shell / curl 流程收敛成稳定命令工具
- 为 Codex 工作流补齐一个可跨 repo 复用的 durable command

## 为什么值得关注

- 它不是单纯“写个脚本”，而是在定义 agent 构建 CLI 的工程标准
- 对重度使用 Codex 的团队来说，这种技能能直接提升长期复用性
- 它把命令设计、认证、安装、验证和 skill 配套都纳入同一方法里

## 类似项目

- [CLI-Anything](cli-anything.md) - 更偏把软件或工具快速封成 agent-native CLI 框架
- [CC-Switch CLI](cc-switch-cli.md) - 是一个具体可安装 CLI，而 `cli-creator` 更像构建这类 CLI 的方法型技能

## 官方链接

- **GitHub:** https://github.com/openai/skills/tree/main/skills/.curated/cli-creator
- **文档:** https://developers.openai.com/codex/skills

## 标签

- `Codex`, `CLI`, `Skill`, `Automation`, `Tooling`

## 更新观察点

- 后续重点观察它对命令契约、JSON 输出和 companion skill 的规范是否继续细化
- 优先重新抓取 `SKILL.md` 与 Codex skills 官方文档
- 如果后续新增更完整的 runtime 选型、测试或安装分发建议，值得补进正文
