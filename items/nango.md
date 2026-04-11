---
title: "Nango"
slug: "nango"
info_type: "awesome-ai-for-coding"
entity_type: "tool"
category: "Engineering Workflows"
featured: false
last_reviewed_at: "2026-04-10T00:00:00+00:00"
---

# Nango

## 一句话总结

一个把 AI agents、产品集成和 700+ SaaS/API 连接到一起的开源集成平台，适合把 CRM、邮箱、客服和业务系统真正接进 Agent 工作流。

## 它解决什么问题

- 很多 AI agent 想接 CRM、工单、邮件或内部系统，但真正难的是 OAuth、权限、重试、限流和多租户管理。
- 做外贸和互联网业务自动化时，团队常常不是缺模型，而是缺稳定的系统接入层。
- 只靠脚本拼接第三方 API 很容易变成脆弱的临时方案，后期维护成本很高。

## 适合谁

- 负责 AI 自动化和系统集成的工程团队
- 想把 Agent 接入 CRM、邮件、客服和 SaaS 工具的产品团队
- 需要给销售、运营、客服或财务搭建稳定自动化底座的团队

## 核心能力

- 700+ API 接入：提供大量现成集成，减少自己重写 OAuth 和连接逻辑的工作量。
- AI tool calling 与 MCP：可把外部系统能力暴露给 AI agents 调用。
- 生产运行时：内置认证、执行、重试、可观测性和多租户管理。

## 典型使用场景

- 让销售 Agent 自动读取 CRM 联系人、写回跟进记录并同步邮件状态。
- 让客服助手接入工单系统、知识库和消息渠道做自动流转。
- 为外贸或互联网团队搭一层统一的 SaaS 集成底座，再往上接 LLM 和业务工作流。

## 为什么值得关注

- 它不是泛泛“连接器目录”，而是把 AI agent 接系统这件事做成了可运行平台。
- 2026 年 4 月还有 release 和提交，说明活跃度和维护节奏都很强。
- 对业务岗位真正有价值，因为它解决的是 AI 落地时最常见的“系统接不上”问题。

## 类似项目

- [Composio](./composio.md) - 同样面向 Agent 接系统，但 Composio 更偏工具包和 agent framework 生态。
- [Automagik Omni](./automagik-omni.md) - 更偏消息渠道统一入口，而 Nango 更偏通用 SaaS/API 集成。

## 官方链接

- **官网:** https://nango.dev
- **GitHub:** https://github.com/NangoHQ/nango
- **文档:** https://nango.dev/docs/
- **更新记录:** https://github.com/NangoHQ/nango/releases

## 标签

- `集成平台`, `Agents`, `MCP`, `CRM`, `API自动化`

## 更新观察点

- 持续观察 AI builder 与 MCP 相关能力是否继续增强。
- 重点看 CRM、邮件和客服类常用集成是否继续扩展。
- 后续维护时优先重抓 releases 和 integrations 文档页。
