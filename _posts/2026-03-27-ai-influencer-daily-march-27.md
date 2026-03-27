---
layout: post
title: AI博主动态日报 - 3月27日精选
subtitle: 来自13位AI意见领袖的最新动态
bigimg: /img/path.jpg
tags: AI, Claude Code, OpenClaw, Agent, GStack, Vibe Coding, 博主动态
---

2026年3月27日，汇总来自 news-scout 关注列表中13位 AI 博主的最新动态，涵盖 Claude Code 生态、Vibe Coding、Agent 工程与行业趋势。

---

## 一级重点：Claude Code / OpenClaw 生态

### 归藏 guizang.ai [@op7418](https://x.com/op7418)

**Claude Code 新增 `/loop` 定时任务命令**
`/loop` 命令现已支持最长连续三天的重复任务执行，最细粒度可达每5分钟一次。配合 Feishu/Telegram Skill，可实现定时总结、PR 审查等自动化工作流。

**Claude Code 官方推出 Telegram / Discord / WeChat 远程连接插件**
`claude-plugins-official` 支持通过 Telegram BotFather 一键配置远程控制 Claude Code；微信连接插件 `Claude-to-IM-Skills` 已更新，扫码即可接入，配置极为简便。

**Codepilot 0.38.3 支持小米 MiMo-V2-Pro 与 MiniMax M2.7**
新模型可通过填入 API Key 在 Codepilot 中直接使用，小米模型本周免费开放。

**OpenClaw 3.22 → 3.23 紧急修复**
3.22 版本打包时漏掉了网页模块，导致无法打开网页。已紧急更新 3.23，建议立即升级。

---

### 宝玉 [@dotey](https://x.com/dotey)

**解析：Claude Skills 为何在2026年1月才突然爆发？**
Skills 功能早在2025年10月就已上线，但生态启动有延迟效应。宝玉详细拆解了爆发背后的社区与工具链成熟度原因。

**推荐：Learn Claude Code 开源项目**（作者 @baicai003）
用12节课从零搭建一个类 Claude Code 的 AI Agent，深入讲解其工作原理，适合想理解 Agent 底层机制的开发者。
[查看原文](https://x.com/dotey/status/2032613262525644985)

**Anthropic「Claude for Open Source」计划**
向开源社区的维护者和核心贡献者免费提供 6 个月 Claude Max 20x 订阅（正常售价不菲）。
[查看原文](https://x.com/dotey/status/2027204661179044003)

**Dario Amodei：海啸已在地平线上，但没人在看**
宝玉转述 Anthropic CEO 的警示：AI 能力跃迁的冲击已近在眼前，但社会尚未准备好。
[查看原文](https://x.com/dotey/status/2027265200781402351)

**Claude Code 新版本 auto-compact 问题**
据 Cline 创始人反映，最近更新后 auto-compact 更激进，可用上下文空间减少，部分用户甚至被迫进入长达4天的冷却期。

---

### 向阳乔木 [@vista8](https://x.com/vista8)

**微信龙虾 Clawbot 体验测评**
- **优点**：离中国普通用户最近，原生支持语音输入
- **缺点**：仅支持手机、不支持 Mac；Bug 较多，不支持流式输出，Markdown 渲染极差，链接无法点击

[查看原文](https://x.com/vista8/status/2035588381426757983)

**推荐 Skill：planning-with-files**（作者 Ahmad Othman）
参考 Manus（已以20亿美元被收购）的 Agent 方法论所写，适用于多步骤复杂任务，可用作其他 Skill 的调度协调层。
[查看原文](https://x.com/vista8/status/2009049757109637364)

---

## 二级重点：Vibe Coding / AI 辅助开发

### Garry Tan [@garrytan](https://x.com/garrytan)

**GStack 正式开源（MIT 协议）**
Garry Tan 发布 GStack，一个为 Claude Code 添加8个工作流 Skill 的开源框架，覆盖产品规划、工程 Review、代码审查、发布等场景。他本人最近7天平均每天产出 17,000 行代码（含35%测试）。
[查看原文](https://x.com/garrytan/status/2033893184972157370)

**"AGI 已经来了"——90小时重建2008年创业公司**
用 AI 在90小时内写出7万行代码，重现了当年用500万美元和5名工程师花了两年才完成的产品。

**回应 Workday CEO "寄生虫" 言论**
Workday CEO 在财报电话会上称 AI Agent 创业公司为"寄生虫"。Garry 反击：用户数据属于用户本人，AI 创业公司的战争才刚开始。
[查看原文](https://x.com/garrytan/status/2034310924107219178)

---

### 郭宇 guoyu.eth [@turingou](https://x.com/turingou)

**wanman ai 实验：200循环，50分钟自动创业**
深夜研读 wanman ai 的实验报告：以 Claude Opus 4.6（同时担任 CEO + CTO 角色）为核心，运行200个工作日循环，50分钟内输出了一份针对日本汽车用户市场的完整软件公司计划。郭宇的结论：*"下个月我可能不需要亲自 vibe 写任何代码了。"*
[查看原文](https://x.com/turingou/status/2032092892047511687)

---

## 三级：Agent 工程 / 研究趋势

### Simon Willison [@simonw](https://x.com/simonw)

**发布 Showboat + Rodney：帮助 coding agents 展示工作成果**
两个新工具，让 AI Coding Agent 能在自动化测试之外，通过可视化文档证明其工作过程。配套工具 Chartroom（CLI 图表）和 datasette-showboat 随后上线。
[查看原文](https://x.com/simonw/status/2021280918204228082)

**提出 "terminal agents" 新类别命名**
将 Claude Code、OpenAI Codex CLI、Gemini CLI 统称为 "terminal agents"（终端代理），呼吁社区统一这一概念。

**AI Agent 安全警示：致命三要素**
当 Agent 同时具备「访问私有数据 + 暴露于不可信内容 + 能对外通信」时，攻击者可通过 prompt injection 窃取数据，需格外注意。

---

*本文由 Claude Code 通过 news-scout skill 自动抓取整理，发布于2026年3月27日。*
