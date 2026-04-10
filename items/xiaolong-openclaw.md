---
title: "小龙 OpenClaw 语音助手"
slug: "xiaolong-openclaw"
info_type: "aweseome-ai-for-coding"
entity_type: "tool"
category: "工程工作流"
featured: false
last_reviewed_at: "2026-04-10T00:00:00+00:00"
---

# 小龙 OpenClaw 语音助手

## 一句话总结

一个把 OpenClaw 变成语音交互的离线唤醒助手，支持 ASR + TTS + 工具调用，让你用语音驱动编码类 Agent。

## 它解决什么问题

- 代码 Agent 主要靠键盘操作，做长流程任务时交互成本高
- 语音助手往往需要联网或设备依赖，难以本地离线使用
- 想把“唤醒词 + 语音指令 + 结果播报”串成稳定工作流很麻烦

## 适合谁

- 想用语音操控 OpenClaw 或编码类 Agent 的开发者
- 需要离线唤醒、流式语音交互的 CLI 重度用户
- 想把语音输入、工具调用与 TTS 输出统一成一个流程的人

## 核心能力

- 离线唤醒词：SenseVoice + Silero VAD，本地运行无需联网
- 语音交互：支持连续对话、语音打断与上下文指令拼接
- OpenClaw 能力接入：文件操作、命令执行、联网搜索与技能扩展
- TTS 三级回退：在线 Edge TTS、本地 Matcha-TTS、Windows SAPI 兜底
- 蓝牙全双工支持：兼顾边说边听与设备自动检测

## 典型使用场景

- 说一句“帮我把那个项目重构一下”，让 OpenClaw 在后台执行并语音汇报
- 在不盯屏幕的情况下，完成一轮代码检索、命令执行和结果确认
- 需要边写边听反馈的语音驱动开发或远程办公场景

## 为什么值得关注

- 把 OpenClaw 的能力前置到语音入口，降低了调用门槛
- 设计了从唤醒词到 TTS 的完整闭环，适合做本地语音助手底座
- 在工程化细节上有考虑，比如并行启动、超时策略和蓝牙兼容

## 类似项目

- [OpenCLI](opencli.md) - 更偏 OpenClaw 的桌面/浏览器自动化底座，小龙更偏语音交互入口
- [cc-switch-cli](cc-switch-cli.md) - 更偏多 AI CLI 配置管理，小龙更关注语音驱动执行

## 官方链接

- **GitHub:** https://github.com/yu20103983/xiaolong-openclaw
- **更新记录:** https://github.com/yu20103983/xiaolong-openclaw/releases

## 标签

- `语音助手`, `OpenClaw`, `ASR`, `TTS`, `唤醒词`, `编程 Agent`

## 更新观察点

- 重点关注唤醒词识别与 ASR 模型的迭代
- 优先观察 README 与 releases，跟踪安装流程与语音交互体验的变化
- 如果后续扩展更多技能或多平台支持，值得补充到正文
