# AI快讯 · hot.foxnan.com

<p align="center">
  <a href="https://hot.foxnan.com/"><img src="https://hot.foxnan.com/og/site.png" alt="AI快讯" width="720"></a>
</p>

<p align="center">
  <b><a href="https://hot.foxnan.com/">https://hot.foxnan.com</a></b><br>
  一个持续运行的中文 AI 资讯站：自动采集 · 人工把关 · 干净阅读
</p>

## 这是什么

**AI快讯**是一个面向中文读者的 AI 资讯站。它不是另一个"AI 新闻聚合"，而是一条完整的**内容生产线**：

> 自动抓取海内外信源 → 大模型逐条理解与评分 → 自动归类与去重 → 精选上首页 → 日报/周报/月报自动成稿

本仓库是站点的**展示页**（介绍与截图），不含运行源码。

## 核心功能

| 模块 | 说明 |
|---|---|
| 📰 资讯时间轴 | 精选 + 全部动态双视图，按天分组；六个分类：模型 / 产品 / 行业 / 论文 / 教程 / 观点 |
| 📅 AI 日报 · 周报 · 月报 | 从当天精选内容自动成稿，历史归档可查 |
| 📮 日报订阅 | 邮箱订阅，每天早上把最新一期日报送到收件箱，随时可退订 |
| ⬇️ 模型下载库 | 主流开源模型下载源聚合与排行 |
| 📊 模型榜 | 汇总多个公开榜单的成绩折算成统一分数，按维度排行，不同厂商的模型可横向比较 |
| 🔧 AI 工具库 | 常用 AI 工具收录与统计 |
| 🤖 Agent Skill 精选库 | Claude/Agent Skills 精选 + GitHub Skill 仓库排行榜（总榜/周增速/本周新） |
| 🗓️ 活动日历 | AI 大会、发布会、峰会、智驾活动预告（自动采集 + 人工审核） |
| 🔌 Agent 接入 | 提供 RSS 全文订阅、REST API、MCP，支持 Agent 与自动化接入（见 [Agent 页](https://hot.foxnan.com/agent)） |
| 💬 讨论社区 | 登录注册、帖子讨论、反馈通道 |

## 技术一览

- **前端**：React Router 8（SSR）+ 自绘 SVG 图表，零图表库依赖
- **后端**：Node 24 原生 TypeScript + PostgreSQL 17 + PM2
- **内容管线**：多信源采集（RSS / X / 网页列表 / 公众号）→ 大模型逐条评分（双独立评分 + 分级门槛）→ 聚类去重 → 定时发布
- **基础**：基于开源框架 [AIHOT](https://github.com/KKKKhazix/AIHOT)（MIT）深度定制，感谢上游作者 [@数字生命卡兹克](https://github.com/KKKKhazix)

## 浏览

- 主站：<https://hot.foxnan.com/>
- 全部动态：<https://hot.foxnan.com/all>
- Agent 接入（RSS / API / MCP）：<https://hot.foxnan.com/agent>
- Agent Skill 精选库：<https://hot.foxnan.com/skills>
- 模型榜：<https://hot.foxnan.com/leaderboard>
- 下载库：<https://hot.foxnan.com/downloads>
- 活动日历：<https://hot.foxnan.com/events>

## License

本仓库内容（介绍文案与截图）仅供展示。站点运行代码未公开。

---

*AI快讯 © 2026 · 由 [foxnangang](https://github.com/foxnangang) 运营*
