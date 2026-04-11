---
title: "Ragas"
slug: "ragas"
info_type: "awesome-ai-for-coding"
entity_type: "tool"
category: "Testing"
featured: false
last_reviewed_at: "2026-04-10T00:00:00+00:00"
---

# Ragas

## 一句话总结

一个开源 LLM 应用评测工具包，擅长 RAG 测试集生成、客观指标评估和反馈闭环构建。

## 它解决什么问题

- 很多 RAG 和问答项目没有高质量测试集，评估往往靠人工感觉。
- 团队想持续比较检索、Prompt 和模型变更效果，但缺少统一指标体系。
- 生产数据回流后，很多团队不知道怎么把它转成可复用的评测资产。

## 适合谁

- 负责 RAG 和知识库问答的 AI 工程团队
- 想建立评测闭环的研究与平台团队
- 需要为企业内部问答和搜索系统做质量验证的团队

## 核心能力

- 客观评测指标：支持 LLM 和传统指标结合评估输出质量。
- 测试集生成：可自动生成更贴近生产场景的测试数据。
- 反馈闭环：帮助团队把生产数据转成持续优化的评测资产。

## 典型使用场景

- 对知识库问答、客服机器人和内部搜索系统做系统化评测。
- 在切检索器、切模型或调 Prompt 之后快速验证效果变化。
- 从线上真实问题中生成测试集，建立更贴近业务的评测闭环。

## 为什么值得关注

- 它在 RAG 评测这个细分上非常实用，不是泛泛的 eval 框架。
- 对做企业知识库、客服问答和文档检索的团队尤其贴合。
- 今年 1 月仍有正式 release，项目活跃度足够。

## 类似项目

- [Evidently](./evidently.md) - 更偏通用 ML/LLM 评测与监控。
- [Giskard](./giskard.md) - 更偏完整测试与红队工具链，而 Ragas 更专注 RAG 评测和测试集。

## 官方链接

- **官网:** https://docs.ragas.io/
- **GitHub:** https://github.com/explodinggradients/ragas
- **文档:** https://docs.ragas.io/
- **更新记录:** https://github.com/explodinggradients/ragas/releases

## 标签

- `RAG`, `评测`, `测试集生成`, `反馈闭环`, `知识库问答`

## 更新观察点

- 持续观察 agent_evals、prompt_evals 等模板是否正式补齐。
- 重点看测试集生成和生产数据闭环能力是否继续增强。
- 后续维护时优先重抓 releases 和 docs 的 quickstart / metrics 部分。
