---
title: "METATRON"
slug: "metatron"
info_type: "aweseome-ai-for-coding"
entity_type: "tool"
category: "测试"
featured: true
last_reviewed_at: "2026-04-09T00:00:00+00:00"
---

# METATRON

## 一句话总结

一个把侦察工具链和本地 LLM 串起来的 AI 渗透测试助手，可离线跑扫描、分析漏洞并导出报告。

## 它解决什么问题

- 手工跑 `nmap`、`whois`、`nikto` 等工具后还得自己汇总判断，安全测试链路很碎
- 很多 AI 安全工具依赖云 API，敏感目标不适合外发
- 一轮扫描信息不够时，人工补扫和来回分析很耗时间

## 适合谁

- 想把基础渗透测试流程自动化的安全研究者
- 希望用本地模型辅助漏洞分析的开发者
- 做内网或敏感环境实验、不能把数据发到云端的人

## 核心能力

- 本地 AI 分析：通过 Ollama 运行本地模型，不依赖云端 API
- 自动侦察：串联 `nmap`、`whois`、`whatweb`、`curl`、`dig`、`nikto`
- Agentic loop：AI 觉得信息不够时可继续请求更多工具扫描
- 结果沉淀：把扫描记录、漏洞、修复建议和总结存进 MariaDB
- 报告导出：支持导出 PDF 和 HTML 报告

## 典型使用场景

- 对测试环境做一次本地化的自动侦察和漏洞初判
- 把常见 Web 目标的信息收集和 AI 分析流程串成统一入口
- 在离线实验环境里验证“本地模型 + 安全工具链”的可行性

## 为什么值得关注

- 它不是只包装单个扫描命令，而是在做一个可迭代的本地安全 Agent
- 对不想把扫描数据交给第三方服务的人来说，本地运行是很大的优势
- 对学习渗透测试流程的人，也能更直观看到工具链如何协同

## 官方链接

- **GitHub:** https://github.com/sooryathejas/METATRON
- **更新记录:** https://github.com/sooryathejas/METATRON/releases

## 标签

- `安全测试`, `渗透测试`, `本地模型`, `Ollama`, `自动侦察`

## 更新观察点

- 后续重点看它新增了哪些扫描工具和分析回路
- 优先观察 README 与 releases，跟踪模型、数据库结构和报告导出能力的迭代
- 如果后续补了更强的 exploit 验证或沙箱隔离能力，值得补进正文
