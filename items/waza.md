---
title: "Waza"
slug: "waza"
info_type: "awesome-ai-for-coding"
entity_type: "tool"
category: "工程工作流"
featured: false
last_reviewed_at: "2026-04-11T00:00:00+00:00"
---

# Waza

## 一句话总结

一个把需求思考、设计、检查、调试、研究和写作等工程习惯打包成 Claude Code skills 的技能集合，帮助开发者把方法论直接嵌进日常工作流。

## 它解决什么问题

- 很多团队知道“先想清楚、再动手、交付前验证”这些好习惯，但很难长期稳定执行。
- AI 能提高速度，但不天然保证需求判断、调试纪律和交付质量。
- 过于庞杂的 skill 套装和规则体系会让开发者学习成本过高，最后反而不用。

## 适合谁

- 想给 Claude Code 安装一组高频工程习惯技能的开发者
- 希望把思考、调试、review 和研究方法沉淀成稳定工作流的团队
- 偏好轻量技能包而不是庞大 agent 框架的人

## 核心能力

- 习惯技能化：把 think、design、check、hunt、learn、read、health 等工程动作封装成明确触发的技能。
- 轻量安装：通过 `npx skills add` 快速装进 Claude Code 或其他兼容宿主。
- 方法论落地：每个技能都围绕一个具体习惯，而不是一个泛泛的大而全平台。
- 配套增强：除技能外还提供 statusline、英文写作辅助等实用增强项。

## 典型使用场景

- 在写新功能前先用 `/think` 压测问题定义和架构方向。
- 在 bug 排查时用 `/hunt` 强制先找 root cause 再动手修。
- 在任务结束前用 `/check` 做 diff review、验证和风险拦截。

## 为什么值得关注

- 它强调的不是模型能力，而是“让工程习惯可重复执行”。
- 相比大而全的 skill 体系，Waza 更明显地追求轻量、少而精和清晰触发条件。
- 对想提升 Claude Code 使用质量的人来说，这类 workflow layer 往往比再换一个模型更有长期价值。

## 类似项目

- [NetEase Skills](netease-skills.md) - 更偏具体服务能力的技能分发，而 `Waza` 更偏软件工程方法论技能包。
- [Superpowers](superpowers.md) - 同样围绕工程习惯与技能体系，但 `Waza` 更强调轻量和最小必要集合。

## 官方链接

- **GitHub:** https://github.com/tw93/waza
- **更新记录:** https://github.com/tw93/waza/releases

## 标签

- `Skills`, `Claude Code`, `Engineering Workflow`, `Debugging`, `Code Review`

## 更新观察点

- 后续重点看技能数量是否继续克制，以及核心技能是否在真实项目里持续打磨。
- 持续关注对非 Claude 宿主的兼容边界，尤其 `/check`、`/read`、`/health` 这类带平台依赖的能力。
- 优先重抓 README、具体 skill 目录和 releases，确认技能触发条件与内容有没有明显变化。
