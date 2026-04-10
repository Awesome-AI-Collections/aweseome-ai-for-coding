---
title: "Higress"
slug: "higress"
info_type: "aweseome-ai-for-coding"
entity_type: "tool"
category: "工程工作流"
featured: false
last_reviewed_at: "2026-04-10T00:00:00+00:00"
---

# Higress

## 一句话总结

一个来自阿里体系的 AI Gateway，可统一管理 LLM API 和 MCP API，适合把企业内部接口、第三方平台 API 和 AI 调用层接成一个可控的中间网关。

## 它解决什么问题

- 团队想把 Amazon、Alibaba、Shopify 或内部 OpenAPI 接给 AI agent 时，常常缺一个统一托管和鉴权层。
- 只靠零散 MCP server 很难统一做路由、鉴权、限流和可观测。
- 当 LLM API 和工具 API 分别管理时，工程复杂度会明显上升。

## 适合谁

- 做 AI 平台、中间件和 agent 基础设施的工程团队
- 需要把业务 API 统一接给 AI 应用的企业技术团队
- 想把 MCP server 托管成更稳定生产入口的开发者

## 核心能力

- AI Gateway：统一承接模型调用与工具调用能力。
- MCP 托管：支持通过插件机制托管远程 MCP server。
- OpenAPI 转接：可配合 `openapi-to-mcpserver` 把现有 REST/OpenAPI 快速变成 AI 工具层。

## 典型使用场景

- 给企业内部客服、销售或运营 agent 提供统一的工具接入网关。
- 把阿里云、业务后台或第三方 SaaS API 收敛到一个 AI 调用入口。
- 在多模型、多工具并存的场景里做统一治理与发布。

## 为什么值得关注

- 不是单点 MCP 项目，而是更上层的 AI 中间网关。
- 2026 年 4 月仍有 commit 和 release，维护节奏很强。
- 对“中间连接工具”这个方向非常贴切，尤其适合承接多平台 API。

## 类似项目

- [Composio](./composio.md) - 更偏 agent 的 SaaS 工具包生态，Higress 更偏网关与托管层。
- [openapi-to-mcpserver](./openapi-to-mcpserver.md) - 更偏 API 转 MCP 的转换工具，通常可作为 Higress 的配套组件。

## 官方链接

- **官网:** https://higress.ai/en/
- **GitHub:** https://github.com/alibaba/higress
- **文档:** https://higress.cn/en/docs/latest/overview/what-is-higress/
- **更新记录:** https://github.com/alibaba/higress/releases

## 标签

- `AI Gateway`, `MCP`, `OpenAPI`, `中间件`, `Alibaba`

## 更新观察点

- 持续观察 MCP 托管能力和 AI 网关治理能力是否继续扩展。
- 重点看与 `openapi-to-mcpserver` 的联动是否更顺畅。
- 后续维护时优先重抓 releases、README 和 MCP quick start 文档。
