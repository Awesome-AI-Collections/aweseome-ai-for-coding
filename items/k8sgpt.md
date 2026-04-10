---
title: "K8sGPT"
slug: "k8sgpt"
info_type: "awesome-ai-for-coding"
entity_type: "tool"
category: "工程工作流"
featured: false
last_reviewed_at: "2026-04-10T00:00:00+00:00"
---

# K8sGPT

## 一句话总结

一个把 Kubernetes 集群问题翻译成自然语言的开源诊断工具，适合 SRE 和平台团队加速排障、定位异常和补齐上下文。

## 它解决什么问题

- Kubernetes 故障信息分散在事件、状态、日志和资源对象里，新人很难快速看懂。
- 平台团队在排查集群异常时，经常要手动拼接上下文和官方文档。
- 多团队共用集群时，排障知识容易只掌握在少数资深工程师手里。

## 适合谁

- 负责 Kubernetes 平台稳定性的 SRE 团队
- 管理集群、命名空间和工作负载的平台工程团队
- 想提升一线排障效率的互联网运维团队

## 核心能力

- 集群扫描分析：扫描 Kubernetes 集群并找出常见问题模式。
- 自然语言解释：把资源异常、配置问题和事件上下文整理成更容易理解的说明。
- 多模型后端支持：可接 OpenAI、Bedrock、Gemini、Azure 等云模型，也支持本地模型。

## 典型使用场景

- 值班工程师在告警后快速跑一遍分析，缩短从“发现异常”到“看懂异常”的时间。
- 平台团队把它接入日常巡检或 MCP 工作流，让 AI 辅助解释集群问题。
- 新成员排查 Pod、节点、Ingress 或权限问题时，把经验型排障流程标准化。

## 为什么值得关注

- 它不是泛聊天机器人，而是把 Kubernetes/SRE 经验固化到了 analyzers 里。
- 已经提供和 Claude Desktop 配合的 MCP 用法，适合接进 AI 工具链。
- 发布节奏持续，说明社区和维护状态都还在线。

## 类似项目

- [Keep](./keep.md) - 更偏多监控源的告警治理与事故自动化，不专注 Kubernetes 诊断。
- [OpenLIT](./openlit.md) - 更偏 AI 应用可观测性，不负责集群层排障。

## 官方链接

- **GitHub:** https://github.com/k8sgpt-ai/k8sgpt
- **文档:** https://docs.k8sgpt.ai/
- **更新记录:** https://github.com/k8sgpt-ai/k8sgpt/releases

## 标签

- `Kubernetes`, `排障`, `SRE`, `平台工程`, `MCP`

## 更新观察点

- 持续观察 analyzers 是否覆盖更多 Kubernetes 故障类型和生态组件。
- 重点看 MCP、Operator 和持续监控模式是否继续增强。
- 后续维护时优先重抓 releases 与 docs，确认模型后端和诊断能力变化。
