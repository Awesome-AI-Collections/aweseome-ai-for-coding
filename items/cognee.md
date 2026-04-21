---
title: "Cognee"
entity_type: "tool"
category: "Engineering Workflows"
last_reviewed_at: "2026-04-21"
---

# Cognee

## 一句话总结

一个把向量检索、知识图谱和持久记忆组合起来的开源知识引擎，适合给 AI agents 建长期可学习 memory 层。

## 它解决什么问题

- 很多 RAG 或 agent 系统只能“临时检索”，很难把长期记忆、关系结构和反馈学习连起来
- 当多个 agent 共享知识、上下文和用户偏好时，单一向量库经常不够表达关系与演化
- 开发者想给 Claude Code、OpenClaw 或自建 agent 配 memory 时，通常得自己拼图谱、向量检索和记忆策略

## 适合谁

- 正在搭建 AI memory / RAG / knowledge graph 基础设施的开发者
- 需要跨会话、跨 agent 共享上下文的团队
- 想把长期记忆接进 Claude Code、Hermes Agent 或自建 agent 的工程团队

## 核心能力

- 知识引擎：把数据摄入、图谱关系和语义检索放进同一套 memory 叙事里
- 持久记忆 API：提供 `remember / recall / forget / improve` 这类更接近 memory 操作的接口
- Agent 集成：README 已明确给出 Claude Code 插件和 Hermes Agent 的接入方式
- 本地与服务化兼容：既可本地运行，也支持接 Cognee Cloud

## 典型使用场景

- 给 AI agent 增加长期记忆和跨会话知识继承
- 把文档、用户偏好和工具调用结果沉淀到统一 memory 层
- 在 RAG 系统里补上图谱关系和记忆演化逻辑，而不只做向量召回

## 为什么值得关注

- 它不是单纯向量库，也不是单纯图数据库，而是在做 memory engine 这一层的产品定义
- README 已经明确把 Claude Code 作为集成对象之一，和当前 agent 工作流高度相关
- 对想做“会学习的 agent”团队来说，它提供了比传统 RAG 更完整的记忆叙事

## 类似项目

- [LlamaIndex](llama-index.md) - 更偏通用数据连接与 RAG 编排，而 Cognee 更强调 memory engine 和长期记忆
- [LanceDB](lancedb.md) - 更偏底层向量检索库，而 Cognee 试图把图谱、记忆和 agent 集成一起做出来

## 官方链接

- **官网:** https://cognee.ai
- **GitHub:** https://github.com/topoteretes/cognee
- **文档:** https://docs.cognee.ai/
- **更新记录:** https://github.com/topoteretes/cognee/releases

## 标签

- `Memory`, `Knowledge Graph`, `RAG`, `Agent`, `Python`

## 更新观察点

- 后续重点观察 Claude Code 插件、OpenClaw 插件和核心 memory API 是否继续增强
- 持续跟踪 README、文档站和 releases
- 如果后续把多租户隔离、可观测性和反馈学习机制讲得更清楚，值得继续更新条目
