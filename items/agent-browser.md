---
title: "agent-browser"
slug: "agent-browser"
info_type: "awesome-ai-for-coding"
entity_type: "tool"
category: "工程工作流"
featured: true
last_reviewed_at: "2026-04-10T12:54:00+00:00"
---

# agent-browser

## 一句话总结

Vercel Labs 开源的浏览器自动化 CLI，专门给 AI agents 提供网页导航、点击、填写表单、截图、网络拦截和批处理能力。

## 它解决什么问题

- 很多编码 agent 擅长写代码，但缺少稳定的浏览器交互层，难以直接操作网页和真实界面
- 传统浏览器自动化工具更偏脚本工程，不一定适合被 CLI 型 agent 直接调用
- 在 AI 工作流里做页面验证、抓取、表单提交或 Web QA 时，往往缺少一个足够轻量的统一入口

## 适合谁

- 想让 Claude Code、Codex 等 agent 直接操控浏览器的开发者
- 需要网页抓取、表单自动化或页面 QA 能力的 AI 工程团队
- 想把浏览器能力接入已有 agent workflow 的工具作者

## 核心能力

- 浏览器控制：支持 open、click、fill、hover、scroll、drag、upload 和截图等常见交互
- AI 友好输出：支持 `snapshot` 生成带引用的可访问性树，方便 agent 读取页面结构
- 网络与状态控制：支持 cookies、storage、network route、offline、headers、viewport 等能力
- 批处理执行：支持一条命令里串多个浏览器动作，减少多步工作流的进程开销

## 典型使用场景

- 让编码 agent 自动完成网页操作、表单填写和页面验证
- 在 AI 测试流程里做浏览器截图、元素定位和状态检查
- 把网页交互能力接到自定义 agent、CLI 工具或 MCP 风格工作流中

## 为什么值得关注

- 明确面向 AI agents 设计，不只是把传统浏览器自动化包装成 CLI
- 命令面覆盖很全，从交互、信息提取到网络拦截和批处理都比较完整
- 由 Vercel Labs 开源，适合作为 agent 浏览器能力层的基础组件

## 类似项目

- [bb-browser](bb-browser.md) - 更强调把真实已登录浏览器直接变成 API / CLI / MCP 接口，而 agent-browser 更偏标准化浏览器自动化 CLI。
- [OpenCLI](opencli.md) - 更像把网站、浏览器和本地应用统一暴露给 agent 的自动化中枢，而 agent-browser 更专注浏览器这一层。

## 官方链接

- **GitHub:** https://github.com/vercel-labs/agent-browser
- **更新记录:** https://github.com/vercel-labs/agent-browser/releases

## 标签

- `Browser Automation`, `AI Agent`, `CLI`, `Web Testing`, `网页交互`, `Vercel`

## 更新观察点

- 后续重点关注 AI 友好的 `snapshot`、`chat` 和 batch 能力是否继续增强
- 观察它与 Chrome for Testing、CDP 和多平台安装的兼容性是否持续优化
- 持续跟踪 releases，判断它是否进一步往 agent 原生浏览器 runtime 方向演化
