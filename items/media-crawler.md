---
title: "MediaCrawler"
slug: "media-crawler"
info_type: "aweseome-ai-for-coding"
entity_type: "tool"
category: "工程工作流"
featured: false
last_reviewed_at: "2026-04-09T00:00:00+00:00"
---

# MediaCrawler

## 一句话总结

一个基于 Playwright 登录态的多平台自媒体数据采集工具，覆盖小红书、抖音、B 站、微博、贴吧、知乎等主流中文平台。

## 它解决什么问题

- 做中文平台内容采集时，经常要分别处理登录态、签名参数和平台风控
- 单平台脚本维护成本高，多平台需求会迅速变成一堆碎片化工程
- 团队想先做学习或研究型抓取，但不一定有能力维护复杂逆向链路

## 适合谁

- 需要采集国内主流内容平台公开信息的开发者
- 做自媒体调研、舆情研究和内容监测的数据团队
- 想给 OpenClaw 或 Claude Code 准备中文平台数据入口的用户

## 核心能力

- 多平台覆盖：支持小红书、抖音、快手、B 站、微博、贴吧、知乎等
- 登录态复用：基于 Playwright 和保留登录态的浏览器上下文
- 搜索与评论抓取：覆盖关键词搜索、帖子抓取和评论等常见场景
- 门槛降低：尽量避免直接做复杂 JS 逆向

## 典型使用场景

- 为中文互联网内容做多平台样本抓取
- 搭建内部研究或监测工作流的原型阶段
- 给 Agent 准备一个“先能抓、再优化”的国内平台数据入口

## 为什么值得关注

- 国内平台覆盖广，是这类项目最直接的稀缺价值
- 对研究型或原型型需求来说，能先拿到数据常常比架构完美更重要
- README 已经明确提到 OpenClaw / Claude Code / Cursor 的安装方向，和你当前场景高度相关

## 类似项目

- [wechat_articles_spider](wechat-articles-spider.md) - 更聚焦微信公众号，小而专
- [XCrawl](xcrawl.md) - 更偏托管 API 服务路线，不要求自己长期维护整套抓取栈

## 官方链接

- **GitHub:** https://github.com/NanmiCoder/MediaCrawler
- **更新记录:** https://github.com/NanmiCoder/MediaCrawler/releases

## 标签

- `自媒体爬虫`, `Playwright`, `国内平台`, `数据采集`, `OpenClaw`

## 更新观察点

- 后续重点关注平台覆盖、登录态稳定性和 IP / 账号策略是否继续增强
- 优先观察 README、issues 与 releases，判断哪些平台能力仍在积极维护
- 同时要持续留意项目自己的合规与免责声明边界，不把学习型工具误当成可随意商用的稳定服务
