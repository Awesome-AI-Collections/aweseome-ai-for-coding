---
title: "MarkItDown"
slug: "markitdown"
info_type: "awesome-ai-for-coding"
entity_type: "tool"
category: "Documentation"
featured: true
last_reviewed_at: "2026-04-10T12:58:00+00:00"
---

# MarkItDown

## 一句话总结

微软开源的文件转 Markdown 工具，可把 PDF、Office 文档、图片、音频、HTML、YouTube 等内容转换成更适合 LLM 和文本分析流水线使用的 Markdown。

## 它解决什么问题

- 文档、表格、网页、音频和图片等资料格式分散，不利于统一送进 LLM 或检索管道
- 很多转换工具更偏“给人看”的高保真排版，不一定适合 AI 消费和下游分析
- 工程团队做 RAG、文档抽取或 agent 上下文准备时，常缺少稳定的通用预处理层

## 适合谁

- 想把多种文件统一转成 LLM 友好文本的开发者
- 在做 RAG、知识抽取或文档处理流水线的工程团队
- 需要把 Office、PDF、媒体和网页内容纳入 AI 上下文处理链路的人

## 核心能力

- 多格式转换：支持 PDF、Word、Excel、PowerPoint、图片、音频、HTML、ZIP、EPub、YouTube 等输入
- CLI 与 Python API：既能命令行批量处理，也能嵌入 Python 流水线
- 插件扩展：支持第三方插件与 OCR 扩展，便于增强特定格式处理能力
- LLM 集成：输出目标明确面向 LLM、文本分析和 MCP 场景，而非纯展示用途

## 典型使用场景

- 为 RAG 和知识库准备统一的 Markdown 语料
- 把复杂文档和媒体资料预处理成适合 agent 使用的上下文
- 在文档分析、结构化抽取或企业资料处理流程里做标准化输入转换

## 为什么值得关注

- 它不是普通文档转换器，而是明确围绕 LLM 语料和文本分析管道设计
- CLI、API、插件和 MCP 方向都比较完整，适合做底层组件
- 由微软 AutoGen 团队维护，适合作为 AI 文档处理基础设施观察对象

## 类似项目

- [Skill Seekers](skill-seekers.md) - 更偏多源资料采集、分析和打包成技能或 RAG 资产，而 MarkItDown 更专注统一转换层。
- [jina-cli](jina-cli.md) - 更偏网页读取与即时 LLM 友好化，而 MarkItDown 处理的文件类型和离线资料范围更广。

## 官方链接

- **GitHub:** https://github.com/microsoft/markitdown
- **更新记录:** https://github.com/microsoft/markitdown/releases

## 标签

- `Markdown`, `Document Conversion`, `LLM`, `RAG`, `Python`, `Microsoft`

## 更新观察点

- 后续重点看插件生态和 OCR / MCP 相关能力是否继续扩展
- 关注支持格式、可选依赖拆分和 Python API 稳定性是否持续演进
- 持续跟踪 releases，判断它是否从转换工具进一步演化成更完整的文档 ingestion 层
