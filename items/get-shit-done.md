---
title: "Get Shit Done"
slug: "get-shit-done"
info_type: "awesome-ai-for-coding"
entity_type: "tool"
category: "Engineering Workflows"
featured: true
last_reviewed_at: "2026-04-10T12:50:00+00:00"
---

# Get Shit Done

## 一句话总结

一个面向 Claude Code、Codex、Cursor 等编码助手的 meta-prompting、context engineering 和 spec-driven development 系统，重点解决长任务里的 context rot，让 AI 编码流程更稳。

## 它解决什么问题

- 编码助手在长上下文和多轮任务里容易逐步跑偏，出现上下文衰减和执行质量下降
- 很多 AI 编程流程只有 prompt，没有把规划、质量门禁、验证和状态管理整合成一套系统
- 个人开发者不想引入过重的企业流程，但又希望 AI 开发结果足够可靠

## 适合谁

- 重度依赖 Claude Code、Codex、Cursor 等工具写代码的开发者
- 想用更轻但更稳的方式管理 AI 编码长任务的人
- 希望把 context engineering、spec 流程和质量门禁合在一起的个人或小团队

## 核心能力

- 上下文工程：通过 meta-prompting、上下文结构和状态管理降低 context rot
- 规格与规划流程：围绕项目初始化、需求、路线图、阶段讨论和执行建立完整规划链路
- 质量门禁：内置 schema drift、安全、scope reduction 等质量检查机制
- 多工具接入：支持 Claude Code、Codex、Copilot、Cursor、Gemini CLI、OpenCode 等多种运行时

## 典型使用场景

- 在复杂新项目里让 Claude Code 或 Codex 先建立规划结构，再分阶段执行
- 在已有代码库中用 `/gsd-map-codebase` 重建上下文，再继续推进长期功能开发
- 给 AI 编码工作流增加状态管理、门禁验证和更稳定的多轮协作过程

## 为什么值得关注

- 它把“AI 会不会写代码”升级成“AI 能不能长期稳定把项目做完”
- 相比更偏规范文档的框架，它更强调 context engineering 和真实长任务执行稳定性
- 明确面向个人开发者和小团队，不强迫用户进入重型企业流程

## 类似项目

- [OpenSpec](open-spec.md) - 更聚焦 proposal/spec/design/tasks 的轻量 spec 生命周期，而 GSD 更强调 context engineering、质量门禁和长期执行稳定性。
- [Superpowers](superpowers.md) - 更强调 skills 体系、TDD 纪律和子代理开发方法论，而 GSD 更突出上下文治理和项目级状态管理。

## 官方链接

- **GitHub:** https://github.com/gsd-build/get-shit-done
- **文档:** https://github.com/gsd-build/get-shit-done/tree/main/docs
- **更新记录:** https://github.com/gsd-build/get-shit-done/releases

## 标签

- `Claude Code`, `Codex`, `Context Engineering`, `Spec-Driven Development`, `工作流`, `Meta Prompting`

## 更新观察点

- 后续重点观察 quality gates 和 verifier / planner 相关机制是否继续增强
- 关注它对不同编码运行时的安装与技能接入方式是否持续统一
- 持续跟踪 changelog，判断它是继续深耕 context engineering，还是往更完整的 agent 平台延展
