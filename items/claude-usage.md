---
title: "claude-usage"
slug: "claude-usage"
info_type: "awesome-ai-for-coding"
entity_type: "tool"
category: "工程工作流"
featured: true
last_reviewed_at: "2026-04-09T00:00:00+00:00"
---

# claude-usage

## 一句话总结

一个把 Claude Code 本地 JSONL 日志转成可视化仪表盘的工具，可统计 token、模型分布和 API 价格口径下的成本估算。

## 核心场景

- 把 Claude Code 进度条背后的真实 usage 明细可视化
- 统计 input/output token、缓存读写、模型分布和项目消耗
- 按天、按项目、按模型查看成本估算，判断 Max 或 Pro 的使用效率

## 为什么值得关注

- 它直接补上了官方界面没有给出的消费和 token 视角
- 完全读取本地日志，不依赖外部服务，适合想看清真实使用习惯的人
- 零依赖、纯 Python 标准库启动，部署门槛很低

## 类似项目

- [CodeIsland](codeisland.md) - 更偏实时查看会话状态和授权交互，不做历史成本分析
- [OpenLogs](openlogs.md) - 更偏面向 Agent 系统的行为日志监控与可观测性

## 官方链接

- **GitHub:** https://github.com/phuryn/claude-usage
- **更新记录:** https://github.com/phuryn/claude-usage/releases

## 标签

- `Claude Code`, `Usage Dashboard`, `Token统计`, `成本估算`, `本地日志`

## 更新观察点

- 后续重点看它对更多 Claude 会话来源、筛选维度和成本模型的支持
- 优先观察 README 与 releases，跟踪 dashboard、增量扫描和统计口径变化
- 如果后续补了更细的导出或团队视图，值得补进正文
