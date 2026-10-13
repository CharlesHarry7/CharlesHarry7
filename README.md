# charles

### AI 工具 · Web 应用 · 云端自动化

这里记录我的公开项目实践：把 AI 能力做成可交互的工具，用 Web 应用串起完整流程，再用自动化处理重复工作。

项目主要涉及 **Python、JavaScript / TypeScript、Next.js、Cloudflare 和 GitHub Actions**。下面按用途整理了项目入口，并标明复刻、原型和 Fork 的来源与状态。

## AI 与 Web 应用实践

| 项目 | 做什么 | 技术与状态 |
| --- | --- | --- |
| **[DreamUtopia Clone](https://github.com/CharlesHarry7/dreamutopia-clone)** | 图像与视频生成工具站，包含账号、上传、任务轮询和结果下载流程 | Cloudflare Pages · D1 / KV / R2 · KIE API；学习与复刻项目 |
| **[MagicRemover Clone](https://github.com/CharlesHarry7/magicremover-clone)** | 画笔标记图片中的物体，调用图像修复模型，比较前后效果并下载 | Next.js · TypeScript · Replicate · Cloudflare Workers；学习与复刻项目 |
| **[PlainDoc](https://github.com/CharlesHarry7/plaindoc)** | 将租约、账单和 Offer 整理成白话总结、条款与费用说明 | JavaScript · Vercel / Cloudflare；原型，支持规则演示与可选模型调用 |

[DreamUtopia 展示站](https://dreamutopia-clone.pages.dev) · 各项目的环境配置、功能边界和运行方法见对应 README。

## 云端自动化

### [Laoma Price Watch｜美股价格监控](https://github.com/CharlesHarry7/laoma-price-watch)

让 GitHub Actions 在云端运行 Python 脚本，将自定义档位的到价提醒、持仓异动和存储板块日报发送到 Telegram。提醒状态持久化，支持去重与手动快照。

**技术：** Python · GitHub Actions · Telegram Bot · yfinance。工具只发送提醒，不执行交易。

## 开源工具与模板 · Fork

这些仓库是上游开源项目的个人 Fork，单独列出，便于查找源码和学习入口。项目作者、许可证及安装说明以各自上游为准。

| 我的 Fork | 关注的能力 | 上游来源 |
| --- | --- | --- |
| [ai-site-template](https://github.com/CharlesHarry7/ai-site-template) | AI SaaS 的认证、订阅、积分账本与生图流程 | [nikandr-surkov/ai-saas-starter](https://github.com/nikandr-surkov/ai-saas-starter) |
| [rea](https://github.com/CharlesHarry7/rea) | 用 CLI 与 MCP 分析应用行为、JavaScript 和原生二进制 | [morluto/rea](https://github.com/morluto/rea) |
| [CCBaga](https://github.com/CharlesHarry7/CCBaga) | Claude 本地身份、浏览器指纹与系统环境核验 | [liseami/CCBaga](https://github.com/liseami/CCBaga) |
| [deepseek-harness](https://github.com/CharlesHarry7/deepseek-harness) | 基于 Cordis 插件架构的智能体框架与 Web UI | [deepseek-ai/deepseek-harness](https://github.com/deepseek-ai/deepseek-harness) |

---

[浏览全部公开仓库](https://github.com/CharlesHarry7?tab=repositories&type=public) · 在对应项目的 Issues 中交流实现与使用问题
