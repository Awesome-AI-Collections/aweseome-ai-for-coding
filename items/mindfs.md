---
title: "MindFS"
slug: "mindfs"
info_type: "aweseome-ai-for-coding"
entity_type: "tool"
category: "工程工作流"
featured: true
last_reviewed_at: "2026-04-10T13:01:00+00:00"
---

# MindFS

## 一句话总结

一个把 Claude Code、Codex、Cursor 等本地 Agent CLI 通过浏览器远程接入项目目录和工作站文件的自托管网关，支持多设备访问、实时流式结果和文件联动。

## 它解决什么问题

- 本地编码 Agent 常常被绑在某台开发机或终端里，不方便在手机、平板或另一台电脑上继续同一条会话
- 远程访问项目文件、会话历史和 Agent 输出时，往往缺少统一的浏览器入口和可视化界面
- 多个 Agent、多个项目和文件上下文散落在不同窗口里，切换和管理成本很高

## 适合谁

- 想在浏览器里远程使用本地编码 Agent 的开发者
- 需要跨设备接入项目目录、会话和文件上下文的 AI 编程重度用户
- 希望把 agent 会话、文件浏览和远程访问整合到一个入口的人

## 核心能力

- 多 Agent 网关：自动发现并接入 Claude Code、Codex、Gemini CLI、Cursor、Copilot、OpenClaw 等本地 Agent
- 浏览器工作台：在 Web / PWA 界面里查看会话流、工具调用、权限提示和文件树
- 文件与会话联动：支持文件预览、`@` 文件引用、会话与文件双向跳转
- 远程访问模式：支持本地模式、relay 远程模式和私有网络直连模式

## 典型使用场景

- 在手机或平板上继续查看和跟进桌面机器上的编码 Agent 会话
- 远程访问项目目录，让本地安装的 Claude Code 或 Codex 继续为同一个项目工作
- 把多个项目和多种 Agent 统一收进一个浏览器入口里管理

## 为什么值得关注

- 它不是单个 Agent，而是把本地 Agent CLI 变成一个可远程访问的自托管工作台
- 同时覆盖会话流、文件系统、跨设备同步和移动端使用，比较接近日常真实工作方式
- 对“让编码 Agent 脱离单台终端、变成长期在线工作环境”这个方向很有代表性

## 类似项目

- [CodePilot](codepilot.md) - 更偏桌面 GUI 的多模型 Agent 工作台，而 MindFS 更强调浏览器远程访问和文件系统联动。
- [agent-browser](agent-browser.md) - 更专注浏览器自动化 CLI 能力，而 MindFS 更像远程接入本地编码 Agent 的工作台层。

## 官方链接

- **GitHub:** https://github.com/a9gent/mindfs
- **更新记录:** https://github.com/a9gent/mindfs/releases

## 标签

- `Claude Code`, `Codex`, `Remote Access`, `Agent Gateway`, `PWA`, `File Browser`

## 更新观察点

- 后续重点看远程 relay、移动端体验和多 Agent 会话同步是否继续增强
- 关注插件系统和自定义文件视图是否演化成更完整的 agent 工作台扩展层
- 持续跟踪 releases，判断它是否进一步从远程网关走向完整的 AI 工作空间产品
