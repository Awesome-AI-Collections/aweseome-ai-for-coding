---
title: "jina-cli"
slug: "jina-cli"
info_type: "aweseome-ai-for-coding"
entity_type: "tool"
category: "工程工作流"
featured: true
last_reviewed_at: "2026-04-09T00:00:00+00:00"
---

# jina-cli

## 一句话总结

一个把任意网页转换成 LLM 友好内容的 CLI，支持网页读取、网络搜索，并可直接接入 Claude Code 或 OpenClaw。

## 它解决什么问题

- 网页原始 HTML 太脏，不适合直接喂给 LLM 或 Agent
- 想把读网页、搜网页统一成终端能力时，往往要自己封装 API
- 在 Claude Code、OpenClaw 这类环境里，需要一个更稳定的网页内容入口

## 适合谁

- 需要给 AI Agent 增加网页阅读能力的开发者
- 想把网页解析和搜索能力接入 CLI 工作流的人
- 做资讯采集、文档抓取和 research automation 的团队

## 核心能力

- `read`：读取任意 URL，输出 Markdown、Text 或 JSON
- `search`：调用搜索接口并处理结果，减少二次清洗
- 配置管理：支持超时、代理、输出格式和 API Key 配置
- 多入口安装：可作为 CLI 二进制、Claude Code Skill 或 OpenClaw Skill 使用

## 典型使用场景

- 在 Claude Code 里快速读取博客、新闻、X 链接和文档页
- 给自动化脚本增加“网页转 LLM 输入”的标准步骤
- 用统一命令处理网页抓取和搜索，而不是每次手写 API 调用

## 为什么值得关注

- 它把“网页内容清洗”做成了适合 Agent 调用的最小表面
- 对终端型 AI 工作流来说，这种轻量 CLI 很容易嵌进现有流程
- 同时兼容 Skill 和二进制安装，对不同使用方式都比较友好

## 类似项目

- [r.jina.ai](r-jina-ai.md) - 更偏极简 URL 转 Markdown 服务入口
- [OpenCLI](opencli.md) - 更偏统一网站、桌面应用和本地命令的自动化总线

## 官方链接

- **GitHub:** https://github.com/geekjourneyx/jina-cli
- **更新记录:** https://github.com/geekjourneyx/jina-cli/releases

## 标签

- `网页转Markdown`, `LLM输入`, `CLI`, `Jina AI Reader`, `OpenClaw`

## 更新观察点

- 后续重点看它对搜索、批处理和复杂页面提取的支持是否继续增强
- 优先观察 README 与 releases，跟踪 Skill 安装、CLI 参数和输出格式迭代
- 如果后续补了更强的批量抓取或更丰富的选择器能力，值得补进正文
