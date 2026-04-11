---
title: "openapi-to-mcpserver"
slug: "openapi-to-mcpserver"
info_type: "awesome-ai-for-coding"
entity_type: "tool"
category: "Engineering Workflows"
featured: false
last_reviewed_at: "2026-04-10T00:00:00+00:00"
---

# openapi-to-mcpserver

## 一句话总结

一个把 OpenAPI 文档自动转换成远程 MCP server 配置的工具，特别适合把已有平台 API 快速接进 Claude、Cursor 或自建 agent。

## 它解决什么问题

- 很多业务系统已经有 OpenAPI，但还没有 AI 可直接调用的 MCP 工具层。
- 手工把每个平台 API 改写成 MCP server，重复劳动很重。
- 业务接口经常涉及鉴权、参数位置和响应结构，纯手写封装容易出错。

## 适合谁

- 做 agent 工具层和接口编排的工程团队
- 想把 Amazon、Alibaba、Shopify 或内部 API 接进 AI 的开发者
- 需要快速验证“现有 OpenAPI 能否直接变成 MCP 能力”的团队

## 核心能力

- OpenAPI 转 MCP：自动把接口路径转换成 MCP tools。
- 参数与安全方案转换：能处理参数位置与 security schemes。
- 新版协议支持：支持 MCP Protocol `2025-06-18` 的 output schema 和 structured content。

## 典型使用场景

- 把现有商城、ERP、CRM 或供应链 API 直接转成 AI 工具接口。
- 给 Claude Desktop 或 Cursor 快速接入企业 REST API。
- 与 Higress 组合，做远程 MCP server 托管与发布。

## 为什么值得关注

- 它非常符合“中间连接工具”的定义。
- 不是停留在概念层，而是明确面向 OpenAPI 实战。
- 对已经有 API 资产的团队来说，能明显缩短接 AI 的路径。

## 类似项目

- [Higress](./higress.md) - 更偏 AI 网关与托管层，`openapi-to-mcpserver` 更偏转换器。
- [Composio](./composio.md) - 更偏现成 SaaS 工具生态，不像这个项目这样聚焦已有 OpenAPI 资产。

## 官方链接

- **GitHub:** https://github.com/higress-group/openapi-to-mcpserver
- **文档:** https://higress.cn/en/ai/mcp-quick-start/
- **更新记录:** https://github.com/higress-group/openapi-to-mcpserver/releases

## 标签

- `OpenAPI`, `MCP`, `API连接`, `Agent 工具层`, `Higress`

## 更新观察点

- 重点看更多安全方案和复杂响应结构的转换能力是否继续增强。
- 持续观察 MCP 新协议特性是否继续跟进。
- 后续维护时优先重抓 README 和 releases。
