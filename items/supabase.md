---
title: "Supabase"
slug: "supabase"
info_type: "awesome-ai-for-coding"
entity_type: "tool"
category: "Engineering Workflows"
featured: false
last_reviewed_at: "2026-04-11T00:00:00+00:00"
---

# Supabase

## 一句话总结

一个围绕 Postgres 构建的开发平台，把数据库、认证、API、实时订阅、函数、存储和 AI 向量能力打包在一起，适合做 AI 产品和全栈应用的后端底座。

## 它解决什么问题

- 做 AI 应用时，数据库、认证、文件、实时同步和 API 常常要分别拼装，工程复杂度很高。
- 团队既想保留 Postgres 的开放性，又不想自己从零维护整套后端基础设施。
- 很多 AI 产品需要向量检索、边缘函数和实时数据，但不希望额外接多套服务。

## 适合谁

- 在做 AI 产品、SaaS 或全栈 Web 应用的开发者
- 想用 Postgres 做统一后端底座的工程团队
- 需要数据库、Auth、Storage、Functions 和 AI 能力一体化方案的人

## 核心能力

- Postgres 平台：提供托管或自托管的数据库能力，并保持 Postgres 生态兼容性。
- 后端基础设施一体化：内置认证、自动生成 API、实时订阅、文件存储和函数执行。
- AI 能力扩展：官方文档已经把向量、Embedding 和 AI toolkit 作为一等能力提供。
- 本地与云端兼容：既可直接在云端开箱使用，也支持本地开发和自托管部署。

## 典型使用场景

- 为 AI SaaS 产品快速搭后端，包括用户认证、数据库、文件存储和 API。
- 给 RAG 或 agent 产品准备向量检索和 Edge Functions 能力。
- 让小团队用一套平台覆盖从原型到生产的大部分后端需求。

## 为什么值得关注

- 它不是单点数据库服务，而是一整套面向应用开发的工程底座。
- 对 AI 产品来说，Supabase 把“数据层 + 身份层 + AI 能力层”压缩在一起，集成成本低。
- 本仓已经收录 `supabase-mcp`，而 Supabase 本体是理解那条工具链的上游基础设施。

## 类似项目

- [supabase-mcp](supabase-mcp.md) - 更偏把 Supabase 能力暴露给 Claude 等客户端，而 `Supabase` 是底层平台本体。
- [Firebase](https://firebase.google.com/) - 同样提供一体化后端体验，但 `Supabase` 更强调 Postgres 和开源生态。

## 官方链接

- **官网:** https://supabase.com
- **GitHub:** https://github.com/supabase/supabase
- **文档:** https://supabase.com/docs
- **更新记录:** https://github.com/supabase/supabase/releases

## 标签

- `Backend`, `Postgres`, `Authentication`, `Realtime`, `AI`

## 更新观察点

- 后续重点看 AI / vector toolkit、Edge Functions 和本地开发体验是否继续增强。
- 持续观察官方对 Postgres 生态、GraphQL、Realtime 和 Storage 的整合深度。
- 优先重抓 README、AI docs、local development 文档和 releases。
