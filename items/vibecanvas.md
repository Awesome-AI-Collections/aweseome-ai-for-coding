---
title: "Vibecanvas"
slug: "vibecanvas"
info_type: "awesome-ai-for-coding"
entity_type: "tool"
category: "工程工作流"
featured: false
last_reviewed_at: "2026-04-10T18:10:00+00:00"
---

# Vibecanvas

## 一句话总结

一个本地优先的无限画布式 Agent 工作台，允许用户和 AI 通过同一套 CLI 命令共同编辑画布，并用 CRDT 做实时协作同步。

## 它解决什么问题

- 很多 agent 工作流还是以聊天或终端为主，缺少更直观的空间化协作界面
- 视觉画布类工具常难以和 CLI、自动化和 agent 编辑动作统一起来
- 多人 / 多 agent 协作时，状态同步、冲突处理和本地优先体验往往不够好

## 适合谁

- 想把 AI agent 放进无限画布工作流的开发者
- 需要本地优先、可协作的视觉化 agent 工作台的人
- 对 CLI、画布 UI 和 AI 共创交互感兴趣的工具作者

## 核心能力

- 无限画布 UI：支持绘制、选择、变形、分组等空间化操作
- Agent 可编辑画布：AI 可以调用同一套 canvas CLI 来修改画布内容
- 实时协作同步：基于 Automerge CRDT 做冲突自由协作
- 本地优先工作台：原生二进制、SQLite、本地运行、自动更新

## 典型使用场景

- 把 AI 代理接进一个可视化画布界面里共同组织内容和想法
- 用 CLI 和画布 UI 混合方式驱动画布类应用或工作流
- 研究更适合 agent 的空间化交互界面，而不局限在聊天窗里

## 为什么值得关注

- 它把“Agent + Infinite Canvas + CLI”这三件事真正合到了一起
- 本地优先和 CRDT 组合，让它比很多云端 demo 更接近实际工具形态
- 对 AI 原生创作和协作界面探索很有代表性

## 类似项目

- [MindFS](mindfs.md) - 更偏远程访问本地编码 Agent 和文件系统，而 Vibecanvas 更偏空间化 agent 协作工作台。
- [Superconductor](superconductor.md) - 更偏并行 coding agents 的桌面编排，而 Vibecanvas 更强调画布和视觉协作。

## 官方链接

- **GitHub:** https://github.com/vibecanvas/vibecanvas
- **文档:** https://vibecanvas.dev/docs/faq
- **更新记录:** https://github.com/vibecanvas/vibecanvas/releases

## 标签

- `Infinite Canvas`, `AI Agent`, `CLI`, `CRDT`, `Collaboration`, `Local-First`

## 更新观察点

- 后续重点看 agent 技能、画布 CLI 和协作同步是否继续增强
- 关注插件 / skill 生态是否逐步丰富
- 持续观察它如何平衡本地优先、原生分发和多端协作体验
