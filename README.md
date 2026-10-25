# Charles

### AI 工具 · Web 应用 · 云端自动化

我的做法一般是先复刻一个已经跑通的产品，把它的每一步都拆开看明白，再换成自己的实现；顺手能自动化的重复劳动，就交给 GitHub Actions 在云端跑。

主要技术栈：Python、TypeScript / Next.js、Cloudflare（Workers、Pages、D1 / KV / R2）、GitHub Actions。

## 自己写的

| 项目 | 做什么 | 技术与状态 |
| --- | --- | --- |
| **[laoma-price-watch](https://github.com/CharlesHarry7/laoma-price-watch)** | 云端盯盘：自定义价格档位到价、持仓止损与异动、纳指 / VIX 大盘警报、存储板块日报，全部推到 Telegram | Python · GitHub Actions · yfinance；**在跑**，2026-09 起持续运行 |
| **[magicremover-clone](https://github.com/CharlesHarry7/magicremover-clone)** | 上传照片，用画笔涂抹要移除的物体，调图像修复模型生成结果，前后对比并可下载 | Next.js · TypeScript · Replicate · Cloudflare Workers（OpenNext）；**学习复刻**，不含支付 |
| **[plaindoc](https://github.com/CharlesHarry7/plaindoc)** | 粘贴租约、账单或 Offer，输出一句话总结、条款与费用、潜在风险和下一步 | 静态前端 + Vercel / Cloudflare Pages 双 API 适配；**原型**，Stripe 回调尚未闭环 |
| **[CharlesHarry7](https://github.com/CharlesHarry7/CharlesHarry7)** | 本页，项目索引 | Markdown |

图 / 视频生成那套流程的展示站还在 [dreamutopia-clone.pages.dev](https://dreamutopia-clone.pages.dev)，对应仓库暂未公开。

## 上手改过的上游

这两个 fork 不是镜像，是为了跑通业务改过的分支：

| 仓库 | 我改了什么 | 上游 |
| --- | --- | --- |
| **[videofly-template](https://github.com/CharlesHarry7/videofly-template)** | 修登录系统崩溃、Apimart 视频生成流程与多项前端问题，让工具页的语言切换在首屏可见 | [zifeixu85/videofly-template](https://github.com/zifeixu85/videofly-template) · MIT |
| **[ai-site-template](https://github.com/CharlesHarry7/ai-site-template)** | Paper & Clay 主题、三档一次性积分包、关键词落地页 `/tools/[slug]` 与结构化数据 | [nikandr-surkov/ai-saas-starter](https://github.com/nikandr-surkov/ai-saas-starter) · MIT |

## 只跟踪的上游

这些只用来读源码，一般不动：

| 仓库 | 关注的能力 | 上游 |
| --- | --- | --- |
| [CCBaga](https://github.com/CharlesHarry7/CCBaga) | Claude 本地身份加密归档、指纹浏览器与系统环境核验 | [liseami/CCBaga](https://github.com/liseami/CCBaga) · MIT |
| [deepseek-harness](https://github.com/CharlesHarry7/deepseek-harness) | Cordis 插件架构的智能体框架与 Web UI | [deepseek-ai/deepseek-harness](https://github.com/deepseek-ai/deepseek-harness) · MIT |
| [DeepSeek-Bot](https://github.com/CharlesHarry7/DeepSeek-Bot) | 长驻 bot、bot 之间通信与群聊编排 | [Fei2411/DS-Bot](https://github.com/Fei2411/DS-Bot) · Apache-2.0 |
| [rea](https://github.com/CharlesHarry7/rea) | 用 CLI 与 MCP 分析应用行为、JavaScript 与原生二进制 | [morluto/rea](https://github.com/morluto/rea) · MIT |
| [yichen-skills](https://github.com/CharlesHarry7/yichen-skills) | Agent Skill 的组织方式与远端调研流程 | [mcncarl/yichen-skills](https://github.com/mcncarl/yichen-skills) |
| [jianying-headless](https://github.com/CharlesHarry7/jianying-headless) | 剪映草稿的原生结构、隔离编辑与导出自动化 | [GdLinkLock/jianying-headless](https://github.com/GdLinkLock/jianying-headless) |

## 关于这些复刻

复刻项目是为了学习和验证工程路径，不是对应产品的官方版本，也不代表上游立场。代码授权与使用条件以上游为准；调用的第三方模型按各家计费规则由使用者自付。上游作者要求下架时我会直接删除仓库。

---

[浏览全部公开仓库](https://github.com/CharlesHarry7?tab=repositories) · 具体用法、环境变量和已知限制都写在每个仓库自己的 README 里。
