---
title: "bb-browser"
slug: "bb-browser"
info_type: "aweseome-ai-for-coding"
entity_type: "tool"
category: "编程 Agent"
featured: true
last_reviewed_at: "2026-04-09T00:00:00+00:00"
---

# bb-browser

## 一句话总结

一个把真实已登录浏览器直接变成 API / CLI / MCP 接口的工具，核心价值是让 AI Agent 用“你正在用的浏览器”而不是另起一个容易被识别的自动化环境。

## 它解决什么问题

- 很多网站没有 API，或者 API 不完整、不便宜、不容易拿权限
- Headless 浏览器或纯抓取方案在登录态、反爬和复杂页面上经常不稳定
- Agent 想读取真实平台内容时，最缺的是能直接借用用户现成浏览器上下文

## 适合谁

- 想复用已登录浏览器直接给 Agent 读内容的开发者
- 需要从 Twitter/X、Reddit、Zhihu、Bilibili、YouTube 等平台取数据的团队
- 想把浏览器能力以 CLI / MCP 方式接给 OpenClaw、Claude Code 或自定义 Agent 的用户

## 核心能力

- 浏览器即 API：直接利用真实浏览器上下文获取网页内容与交互能力
- 登录态复用：天然带上用户已有账号状态，减少重新认证成本
- CLI / MCP 兼容：适合作为 Agent 的统一调用接口层
- 多平台适配：覆盖多个主流内容平台与常见搜索场景

## 典型使用场景

- 让 Agent 读取带登录限制的平台内容而不重新模拟整套登录流程
- 在 OpenClaw 数据采集工作流里，把浏览器作为统一内容入口
- 给研究、监测和自动化流程提供稳定的“人类浏览器代理”

## 为什么值得关注

- 它对“Agent 读网”问题的回答很直接：别重新造浏览器，直接用真实浏览器
- 这种路线对需要登录和反爬严格的平台尤其有效
- 对搭 MCP / Agent 工具栈的人来说，bb-browser 很像浏览器访问层的基础模块

## 类似项目

- [OpenCLI](opencli.md) - 更强调统一的网站、桌面应用和本地命令调用中枢
- [Agent Reach](agent-reach.md) - 更强调给 Agent 安装一整套互联网能力包，而不是把浏览器本身变成 API

## 官方链接

- **GitHub:** https://github.com/epiral/bb-browser
- **更新记录:** https://github.com/epiral/bb-browser/releases

## 标签

- `浏览器即API`, `MCP`, `登录态复用`, `数据获取`, `CLI`

## 更新观察点

- 后续重点看支持的平台数量、适配器生态和 MCP 接口是否继续扩展
- 优先持续跟踪 README、相关适配器生态和 releases，观察登录态复用和稳定性策略演进
- 如果后续新增更明确的 OpenClaw / Claude Code 集成示例，值得补进正文
