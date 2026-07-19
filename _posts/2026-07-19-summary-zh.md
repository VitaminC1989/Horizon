---
layout: default
title: "Horizon Summary: 2026-07-19 (ZH)"
date: 2026-07-19
lang: zh
---

> 从 69 条内容中筛选出 22 条重要资讯。

---

1. [月之暗面发布开源 2.8 万亿参数 Kimi K3 模型](#item-1) ⭐️ 9.0/10
2. [GPT-5.6 通过提示工程攻克 30 年凸优化难题](#item-2) ⭐️ 8.0/10
3. [积极投入而非被动消费才能建设繁荣社区](#item-3) ⭐️ 8.0/10
4. [Fable 5 与 GPT-5.6 Sol 在 NP-Hard 问题上对决：/goal 提示有帮助吗？](#item-4) ⭐️ 8.0/10
5. [LG 显示器通过 Windows Update 未经同意静默安装软件](#item-5) ⭐️ 8.0/10
6. [图表揭示 Stack Overflow 衰退：AI 及社区内因](#item-6) ⭐️ 8.0/10
7. [Simon Willison 推出浏览器端 SQLite 查询解释工具](#item-7) ⭐️ 8.0/10
8. [Anthropic 宣布 Claude Fable 5 常驻订阅计划](#item-8) ⭐️ 8.0/10
9. [控制 LLM 的推理努力模式](#item-9) ⭐️ 8.0/10
10. [医生数月抗争下架深度伪造广告](#item-10) ⭐️ 8.0/10
11. [SpaceX 与五角大楼谈判数十亿美元 AI 算力交易](#item-11) ⭐️ 8.0/10
12. [台积电 A14 制程 2028 年投产，性能提升 15%](#item-12) ⭐️ 8.0/10
13. [特朗普政府考虑设立类似 FINRA 的人工智能监管机构](#item-13) ⭐️ 8.0/10
14. [旧金山责令苹果谷歌下架 AI“脱衣”应用](#item-14) ⭐️ 8.0/10
15. [纽约市长要求租房广告中披露 AI 生成图像](#item-15) ⭐️ 7.0/10
16. [智能体 AI 安全：防御提示注入与工具滥用](#item-16) ⭐️ 7.0/10
17. [上海 AI 实验室自进化 Agent Harness 性能提升 104%](#item-17) ⭐️ 7.0/10
18. [白宫被指管控前沿 AI 模型访问，科技巨头权力转移](#item-18) ⭐️ 7.0/10
19. [开发者将 RAG 管道响应时间从 90 秒降至 4 秒，未修改模型](#item-19) ⭐️ 7.0/10
20. [LLM 辩论时编造引用，暴露“说服性幻觉”问题](#item-20) ⭐️ 7.0/10
21. [SK 海力士 CEO 预警 2027 年将迎史上最严重内存短缺](#item-21) ⭐️ 7.0/10
22. [荣耀发布 Agentic OS 框架，手机转向意图驱动](#item-22) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [月之暗面发布开源 2.8 万亿参数 Kimi K3 模型](https://t.me/zaihuapd/42637) ⭐️ 9.0/10

月之暗面发布了开源 2.8 万亿参数模型 Kimi K3，采用 Kimi Delta Attention 新架构，具备原生视觉能力和 100 万 token 上下文窗口。它在 Frontend Code Arena 基准测试中以 1679 分排名第一，从之前的第 18 名跃升至榜首。 这是首个达到如此规模且性能顶尖的开源模型，对闭源前沿模型构成挑战，可能加速 AI 民主化。其在前端编程任务中的统治力或改变开发者构建网页应用的方式。 K3 采用 Kimi Delta Attention（KDA）这一优化的线性注意力机制和注意力残差结构。但社区反馈指出低阶套餐上下文窗口受限，完整 100 万 token 需 79 美元/月订阅，且模型消耗资源较高。

telegram · zaihuapd · 7月18日 02:29

**背景**: Kimi Delta Attention（KDA）是 Gated DeltaNet 的优化版本，通过更细粒度的门控机制提升 RNN 记忆效率。Frontend Code Arena 是一个评估 AI 模型在实际前端编程任务（如构建 HTML/React 应用）中表现的基准。月之暗面是中国 AI 公司，以 Kimi 系列大语言模型闻名。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2510.26692">[2510.26692] Kimi Linear: An Expressive, Efficient Attention Architecture</a></li>
<li><a href="https://github.com/MoonshotAI/Kimi-Linear">GitHub - MoonshotAI/Kimi-Linear · GitHub</a></li>
<li><a href="https://www.designarena.ai/leaderboard/code">Overall Frontend (Non-Agentic) Arena | All Code ...</a></li>

</ul>
</details>

**社区讨论**: Hacker News 用户争论 K3 是否通过蒸馏达到同等水平，有人认为蒸馏不可避免且非攻击。其他用户对进展之快表示惊讶，担忧政府可能限制开放权重模型，并指出 K3 的订阅价高和计算消耗大。

**标签**: `#AI`, `#LLM`, `#Open-Source`, `#Code Generation`, `#Benchmark`

---

<a id="item-2"></a>
## [GPT-5.6 通过提示工程攻克 30 年凸优化难题](https://old.reddit.com/r/math/comments/1uxj3cy/after_openais_cdc_proof_announcement_gpt56_used_a/) ⭐️ 8.0/10

GPT-5.6（Sol Pro 版本）通过迭代提示工程，结合长达一年的前期人工尝试，解决了一个关于最小化凸利普希茨函数时间复杂度的三十年未解猜想。 这表明先进 AI 能够为真正的数学研究做出贡献，可能加速悬而未决问题的解决，并重塑数学家处理开放猜想的方式。 该问题涉及球面域上凸利普希茨函数优化复杂度的上界；解决方案是将之前使用 GPT-5.4 和 5.5 的大量工作输入到单次与 Sol Pro 的提示会话中，随后模型在 148 分钟内给出了证明。

hackernews · mbustamanter · 7月18日 13:00 · [社区讨论](https://news.ycombinator.com/item?id=48957779)

**背景**: 凸优化研究最小化凸函数（任何局部极小也是全局极小），而其复杂度理论研究达到给定精度所需的迭代次数。GPT-5.6 Sol 是专为科学推理优化的模型变体，而迭代提示工程是一种通过多次交互调整提示以改进模型输出的方法。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GPT-5.6">GPT-5.6</a></li>
<li><a href="https://openai.com/index/previewing-gpt-5-6-sol/">Previewing GPT‑5.6 Sol: a next-generation model - OpenAI</a></li>
<li><a href="https://www.ibm.com/think/topics/iterative-prompting">What is iterative prompting? - IBM</a></li>

</ul>
</details>

**社区讨论**: 评论指出，若不计入长达一年的人类工作（提供了关键上下文与技术），声称的 148 分钟具有误导性；一些讨论围绕这是否会让人类研究者无需再处理低垂的数学果实展开，并与初级软件开发者的处境类比。

**标签**: `#AI`, `#mathematics`, `#optimization`, `#GPT-5.6`, `#prompt-engineering`

---

<a id="item-3"></a>
## [积极投入而非被动消费才能建设繁荣社区](https://www.benlandautaylor.com/p/if-you-build-it-they-will-come) ⭐️ 8.0/10

Ben Landau-Taylor 的文章《If You Build It, They Will Come》主张，繁荣的社区需要个体主动付出和首创精神，而非被动消费。 这篇文章凸显了普遍存在的社会疏离与搭便车问题，强调个人主动性可增强社区联系并减少孤独感。 讨论揭示了具体挑战，例如活动组织者难以招募足够志愿者（一个例子提到 400 名参与者仅 20 名志愿者），以及维护社交纽带者的情感脆弱性。

hackernews · barry-cotter · 7月18日 15:37 · [社区讨论](https://news.ycombinator.com/item?id=48959090)

**背景**: 社区建设常依赖少数活跃组织者，而多数人被动参与。'搭便车问题'指那些享受成果却不出力的人，这会导致组织者倦怠。社会资本理论解释了积极参与如何促进信任与共享规范。

**社区讨论**: 评论者普遍认同社区中被动消费的普遍性，许多人应和了搭便车问题。有人表达了组织者的情感代价，包括努力得不到回应时的沮丧。一位志愿者分享了 400 人活动难以凑齐 20 名志愿者的例子，另一位则提到自己的行动最终变得有利可图，凸显了挑战与潜在回报。

**标签**: `#community-building`, `#social-dynamics`, `#leadership`, `#initiative`, `#essay`

---

<a id="item-4"></a>
## [Fable 5 与 GPT-5.6 Sol 在 NP-Hard 问题上对决：/goal 提示有帮助吗？](https://charlesazam.com/blog/fable-5-gpt-5-6-sol-goal/) ⭐️ 8.0/10

一项实践对比实验将 Claude Fable 5 与 GPT-5.6 Sol 置于一个 NP-hard 优化问题中，以检验 /goal 提示技术是否能提升性能。 这一直接对比为处理复杂优化问题时哪个领先 AI 模型表现更好以及 /goal 提示技术是否具有实际优势提供了证据，从而指导开发者进行模型选择和提示工程。 实验图表令人困惑：它标注了“数值越低越好”，但 y 轴却是颠倒的。评论者指出，/goal 可能在单线程任务中有帮助，而在搜索密集型问题中，支持并行调查的“超频模式”可能更优。

hackernews · couAUIA · 7月18日 11:00 · [社区讨论](https://news.ycombinator.com/item?id=48956879)

**背景**: Claude Fable 5 是 Anthropic 于 2026 年 6 月发布的模型，针对编码和自动化任务进行了优化。GPT-5.6 Sol 是 OpenAI 于 2026 年 7 月推出的旗舰编码模型，在多项基准上达到顶尖水平。/goal 提示技术用于 Codex 等工具，允许用户指定高级目标而非逐步指令。NP-hard 问题指的是不存在已知高效算法的问题，因此成为考验 AI 推理能力的困难基准。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/claude/fable">Claude Fable \ Anthropic</a></li>
<li><a href="https://openai-dotcom-git-main-openai.vercel.app/index/gpt-5-6/">GPT - 5 . 6 : Frontier intelligence that scales with your ambition | OpenAI</a></li>
<li><a href="https://www.mindstudio.ai/blog/codex-goal-prompt-meta-prompting-technique">How to Write a Codex /goal Prompt That Actually Works: The ...</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍赞扬了这项评估，但指出图表令人困惑。他们建议测试“超频模式”可能在搜索策略中产生更好结果。一些人分享了实际体验：Claude 在长时间会话中有时会忘记关键指令，而 /goal 可能有助于防止这种情况；对于 Anthropic 是否在编程任务上落后于 OpenAI，意见不一。整体氛围具有建设性，呼吁进行更严格的评估。

**标签**: `#AI comparison`, `#NP-hard`, `#prompt engineering`, `#LLM evaluation`, `#benchmark`

---

<a id="item-5"></a>
## [LG 显示器通过 Windows Update 未经同意静默安装软件](https://videocardz.com/newz/lg-monitors-silently-install-software-through-windows-update-without-user-consent) ⭐️ 8.0/10

LG 显示器被发现会在连接时通过 Windows Update 自动安装系统级软件，且没有任何用户通知或同意。 这带来了严重的安全和隐私风险，因为该软件拥有完整的系统访问权限和网络连接，可能导致未经授权的数据收集或攻击面暴露。 该软件在连接显示器时静默安装，开机自启动，并拥有完整的系统及网络访问权限，无沙盒限制；可通过组策略或设备安装设置禁用自动驱动程序应用下载来规避。

hackernews · baranul · 7月18日 10:21 · [社区讨论](https://news.ycombinator.com/item?id=48956688)

**背景**: Windows Update 可以自动为新硬件安装驱动程序和相关软件。默认情况下，Windows 10/11 会下载推荐的驱动程序和设备元数据，其中可能包含制造商提供的应用程序。这一机制虽然为了方便，但可能被滥用来在未经用户同意的情况下推送额外软件。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.tenforums.com/tutorials/15989-turn-off-device-driver-automatic-installation-windows-10-a.html">Turn On or Off Device Driver Automatic Installation in Windows 10</a></li>
<li><a href="https://ebusexpert.com/industry-news-and-trends/lg-monitors-silently-install-software-through-windows-update-without-consent/">LG Monitors Silently Install Software Through Windows Update ...</a></li>

</ul>
</details>

**社区讨论**: 社区成员表示震惊，指出该软件实际上如同恶意软件般拥有完全系统访问权限。用户分享了规避方法，并将其与 HP 打印机的类似问题进行比较。一些人认为微软应承担启用此类自动安装的责任。

**标签**: `#security`, `#privacy`, `#Windows`, `#automatic updates`, `#vendor software`

---

<a id="item-6"></a>
## [图表揭示 Stack Overflow 衰退：AI 及社区内因](https://data.stackexchange.com/stackoverflow/query/1953768#graph) ⭐️ 8.0/10

Stack Exchange 上的一张图表直观展示了 Stack Overflow 问答活动多年来的急剧下降，峰值出现在 2014 年左右，此后持续下滑。社区讨论将这一趋势归因于 ChatGPT 等 AI 工具的兴起和长期存在的内部社区功能障碍。 十多年来 Stack Overflow 一直是开发者的核心资源；它的衰退标志着开发者寻求帮助方式的转变，可能破坏协作式知识库，并对 AI 时代社区驱动平台的可持续性提出质疑。 图表显示，衰退早在 2022 年 ChatGPT 发布之前就已开始，且在 2021 年 Stack Overflow 被 Prosus 收购前出现了一次显著的活动高峰，这表明公司变革和严格的审核、重复关闭等社区政策可能与 AI 共同导致了这一结果。

hackernews · secretslol · 7月18日 11:12 · [社区讨论](https://news.ycombinator.com/item?id=48956949)

**背景**: Stack Overflow 是一个面向程序员的流行问答网站，于 2008 年上线。它作为编程帮助的首选资源迅速发展，但近年来活动量下降。因素包括能提供即时答案的 AI 编程助手的出现，以及使网站对新人不友好的审核做法引发的内部争议。该网站于 2021 年被 Prosus 以 18 亿美元收购。

**社区讨论**: 评论者普遍认为 Stack Overflow 的衰退早于 ChatGPT，并将其归因于排斥性政策，如重复关闭和缺乏社区参与，这些在 AI 成为可行替代方案之前就将用户赶走了。一些人指出 Prosus 的收购可能加速了衰退，而具有更好文档和更友好环境的新平台已取代了它的角色。

**标签**: `#stackoverflow`, `#ai`, `#community`, `#decline`, `#data-visualization`

---

<a id="item-7"></a>
## [Simon Willison 推出浏览器端 SQLite 查询解释工具](https://simonwillison.net/2026/Jul/18/sqlite-query-explainer/#atom-everything) ⭐️ 8.0/10

Simon Willison 构建了一个交互式浏览器工具“SQLite Query Explainer”，它利用 Pyodide 在浏览器中运行 SQLite，并为 EXPLAIN 和 EXPLAIN QUERY PLAN 命令的输出添加了解释，灵感源于 Julia Evans 对学习阅读查询计划的渴望。 该工具降低了开发者理解 SQLite 查询执行计划的门槛，这些计划通常晦涩难懂。通过 Pyodide 完全在浏览器中运行，它提供了即时、可访问的教育，无需服务器端依赖，有望提升许多人的 SQL 优化技能。 该工具使用 Pyodide 构建，将完整的 Python 环境（包括 sqlite3 模块）编译为 WebAssembly。它解读来自 EXPLAIN 的低级字节码和来自 EXPLAIN QUERY PLAN 的更高级别策略，但作者提醒，由于对 SQLite 内部知识有限，这些解释可能未经过充分验证。

rss · Simon Willison · 7月18日 17:19

**背景**: SQLite 的 EXPLAIN 命令显示查询的虚拟机字节码，而 EXPLAIN QUERY PLAN 提供查询执行方式的高级概述，包括索引使用情况。理解这些计划对于查询优化至关重要。Pyodide 是一个编译为 WebAssembly 的 Python 发行版，允许 Python 代码在 Web 浏览器中本地运行，无需后端服务器。WebAssembly 是一种低级二进制格式，在现代浏览器中以接近本机的速度运行。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://pyodide.org/">Pyodide — Version 314.0.2</a></li>
<li><a href="https://github.com/pyodide/pyodide">GitHub - pyodide/pyodide: Pyodide is a Python distribution ... Pyodide — Version 314.1.0.dev0 Home - Pyodide Pyodide - GitHub About Us - Pyodide Online Python (Pyodide) - Run Python in Browser via WebAssembly</a></li>
<li><a href="https://sqlite.org/eqp.html">EXPLAIN QUERY PLAN - SQLite</a></li>

</ul>
</details>

**标签**: `#sqlite`, `#query-plan`, `#webassembly`, `#pyodide`, `#interactive-tool`

---

<a id="item-8"></a>
## [Anthropic 宣布 Claude Fable 5 常驻订阅计划](https://simonwillison.net/2026/Jul/18/claude-make-fable-5-permanent/#atom-everything) ⭐️ 8.0/10

Anthropic 宣布，从 2026 年 7 月 20 日起，Claude Fable 5 将以 50%使用限额永久纳入 Max 和 Team Premium 订阅计划，因面临 GPT-5.6 Sol 和 Kimi 3 的竞争压力而改变了原先移除该模型的计划。 此举显示 Anthropic 在 GPT-5.6 Sol 和 Kimi 3 等竞品压力下做出回应，将其最强模型向订阅用户开放，可能重塑 AI 服务的定价和访问门槛。 Max（每月 100 至 200 美元）和 Team Premium 用户以 50%限额永久使用 Fable 5，而 Pro 和 Team Standard 用户获得使用积分及一次性 100 美元信用额度；每月 20 美元的套餐仍不包含 Fable 5。原本的移除计划源于计算容量的担忧。

rss · Simon Willison · 7月18日 06:00

**背景**: Claude Fable 5 是 Anthropic 公开可用的能力最强的大语言模型，擅长编程、推理和长周期任务。它与限量发行的 Claude Mythos 5 一同推出。Anthropic 原本因计算资源限制计划将 Fable 5 仅通过 API 提供，但在 OpenAI 的 GPT-5.6 Sol 和 Moonshot AI 的 Kimi 3 等竞品推出后改变决定，因后者提供了可比甚至更优的性能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/claude/fable">Claude Fable \ Anthropic</a></li>
<li><a href="https://platform.claude.com/docs/en/about-claude/models/introducing-claude-fable-5-and-claude-mythos-5">Introducing Claude Fable 5 and Claude Mythos 5</a></li>
<li><a href="https://openai-dotcom-git-main-openai.vercel.app/index/gpt-5-6/">GPT - 5 . 6 : Frontier intelligence that scales with your ambition | OpenAI</a></li>

</ul>
</details>

**标签**: `#AI`, `#Claude`, `#Anthropic`, `#Pricing`, `#Competition`

---

<a id="item-9"></a>
## [控制 LLM 的推理努力模式](https://magazine.sebastianraschka.com/p/controlling-reasoning-effort-in-llms) ⭐️ 8.0/10

大语言模型现在能够学习在低、中、高三种努力模式之间调节推理深度，通过根据任务复杂度调整计算量来实现更高效的推理。 这一进展使得自适应推理成为可能，模型能够为简单任务节省资源，同时对复杂问题应用更深层次的推理，有望降低生产系统的成本和延迟。 通过 RLVR 训练会隐式地导致更长的输出序列，而显式的推理努力水平进一步控制该长度；然而，更长的推理并不总能保证更高的准确性，最佳折衷取决于具体任务。

rss · Sebastian Raschka · 7月18日 11:16

**背景**: 推理扩展是一种技术，其中 LLM 在推理过程中分配更多计算资源来处理复杂问题，通常通过生成更长的思维链实现。基于语言反馈的强化学习（RLVR）是一种训练方法，可自然导致模型学习推理时产生更长输出。OpenAI 等模型的 API 参数‘reasoning_effort’允许用户显式请求不同程度的思考时间，从最低到最高。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://magazine.sebastianraschka.com/p/controlling-reasoning-effort-in-llms">Controlling Reasoning Effort in LLMs</a></li>
<li><a href="https://developers.openai.com/api/docs/guides/reasoning">Reasoning models | OpenAI API</a></li>

</ul>
</details>

**标签**: `#LLMs`, `#reasoning`, `#machine learning`, `#efficiency`, `#NLP`

---

<a id="item-10"></a>
## [医生数月抗争下架深度伪造广告](https://www.reddit.com/r/artificial/comments/1v052ii/a_new_orleans_doctor_spent_months_trying_to_get/) ⭐️ 8.0/10

一位新奥尔良医生花费数月时间，试图将使用其肖像的 AI 深度伪造广告从社交媒体平台下架，这一事件凸显了普通民众相对于公众人物所获得的保护不足。 此案例揭示了当前在深度伪造技术滥用侵害普通公民方面的立法空白和平台责任缺失，突显了超越名人范畴、实现更公平保护的必要性。 该医生并非公众人物，由于现有法律和平台机制主要面向知名人士，他对此类伪造广告的追索手段十分有限。

reddit · r/artificial · /u/FreshFromCache · 7月18日 19:31

**背景**: 深度伪造（deepfake）是指使用人工智能生成的合成媒体，可逼真地替换视频或图像中人物的肖像。尽管一些司法管辖区已颁布针对未经同意的深度伪造的法律，但执法力度通常较弱，且平台倾向于优先处理名人或认证账户的下架请求。普通个人往往面临旷日持久的斗争且支持甚少。

**标签**: `#deepfakes`, `#AI ethics`, `#legislation`, `#impersonation`, `#social media`

---

<a id="item-11"></a>
## [SpaceX 与五角大楼谈判数十亿美元 AI 算力交易](https://www.wsj.com/tech/ai/spacex-in-talks-to-provide-computing-power-for-pentagons-ai-push-15e752e4) ⭐️ 8.0/10

SpaceX 正与美国国防部谈判，为其提供用于运行人工智能模型的数据中心算力，这笔交易可能价值数十亿美元。 该交易将大幅扩展五角大楼的 AI 基础设施能力，将商业云资源整合到国家安全行动中，并标志着国防部门与大型科技公司之间关系的深化。 谈判仍在进行中，可能无法达成；五角大楼已批准 SpaceX、亚马逊、谷歌、微软和甲骨文在机密环境中提供 AI 模型，而 SpaceX 近期还与 Anthropic 和谷歌签署了类似的算力供应协议。

telegram · zaihuapd · 7月18日 01:44

**背景**: 五角大楼正在对其 IT 基础设施进行现代化改造，以支持包括自主系统和数据分析在内的 AI 应用。云计算和专用 AI 硬件对于训练和部署大型模型至关重要。以太空发射闻名的 SpaceX，一直通过其 Starlink 卫星网络向云服务领域扩张，提供边缘计算和全球连接潜力。

**标签**: `#SpaceX`, `#Pentagon`, `#AI infrastructure`, `#defense technology`, `#cloud computing`

---

<a id="item-12"></a>
## [台积电 A14 制程 2028 年投产，性能提升 15%](https://t.me/zaihuapd/42643) ⭐️ 8.0/10

台积电宣布其 A14 制程技术将于 2028 年投产，与 N2 制程相比，同功耗下速度提升 15%，或同速度下功耗降低 30%，逻辑密度提高 20%。 这一进展巩固了台积电在半导体制造领域的领导地位，并将为人工智能、高性能计算和下一代设备提供更强大且更节能的芯片。 A14 制程采用第二代全环绕栅极晶体管（GAAFET），并与台积电的 NanoFlex Pro 架构共同优化，是 N2 之后的重大全节点进步。此外，台积电还计划在 2026 年末推出中间的 A16 制程。

telegram · zaihuapd · 7月18日 05:00

**背景**: 半导体制造节点（如台积电的 N2 和 A14）指先进的芯片制造工艺。N2 制程（2 纳米级）是台积电首个采用纳米片晶体管的技术，于 2025 年底开始量产。A14 是下一个全节点升级，提供更高的逻辑密度（单位面积内更多晶体管）和更好的功率-性能特性，对持续推动摩尔定律式缩放至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.tsmc.com/english/dedicatedFoundry/technology/logic/l_A14">A14 Technology - Taiwan Semiconductor Manufacturing Company Limited</a></li>
<li><a href="https://pr.tsmc.com/english/news/3228">TSMC Unveils Next-Generation A14 Process at North America Technology ...</a></li>
<li><a href="https://semiwiki.com/wikis/industry-wikis/tsmc-a14-process-technology-wiki/">TSMC A14 Process Technology Wiki - SemiWiki</a></li>

</ul>
</details>

**标签**: `#semiconductor`, `#TSMC`, `#A14`, `#process technology`, `#chip manufacturing`

---

<a id="item-13"></a>
## [特朗普政府考虑设立类似 FINRA 的人工智能监管机构](https://www.bloomberg.com/news/articles/2026-07-17/us-considers-creating-finra-like-watchdog-to-vet-top-ai-models) ⭐️ 8.0/10

特朗普政府正考虑设立一个类似于美国金融业监管局（FINRA）的独立人工智能监管机构，负责审查顶尖 AI 模型的安全性。该提案由财政部长斯科特·贝森特牵头，白宫幕僚长苏茜·威尔斯审阅，旨在回应华尔街的网络安全担忧和硅谷对近期临时管控的不满。 这标志着美国 AI 监管可能出现重大转变，转向行业自我监管模式，可能统一安全标准并同时解决金融和技术领域的担忧。这与谷歌 DeepMind 首席执行官德米斯·哈萨比斯等 AI 领袖近期关于设立行业资助独立监管机构的呼吁一致。 该计划尚未经总统特朗普审阅，仍在讨论中，内容可能调整。此前，Anthropic 和 OpenAI 曾对政府要求修改或限制发布最新模型提出异议。

telegram · zaihuapd · 7月18日 05:45

**背景**: 美国金融业监管局（FINRA）是一家私营的自律组织，负责监管美国证券经纪公司和交易所市场，在美国证券交易委员会（SEC）的监督下运作。拟议的 AI 监管机构将仿效这一结构，可能赋予行业在制定和执行安全标准方面的主导权，同时仍受政府监督。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/FINRA">FINRA</a></li>
<li><a href="https://en.wikipedia.org/wiki/Financial_Industry_Regulatory_Authority">Financial Industry Regulatory Authority - Wikipedia</a></li>

</ul>
</details>

**标签**: `#AI regulation`, `#US policy`, `#AI safety`, `#technology governance`, `#industry self-regulation`

---

<a id="item-14"></a>
## [旧金山责令苹果谷歌下架 AI“脱衣”应用](https://techcrunch.com/2026/07/17/apple-and-google-ordered-to-purge-nudify-apps-from-app-stores/) ⭐️ 8.0/10

旧金山市检察长邱信福向苹果和谷歌发出停止并终止信，要求从应用商店中移除数十款利用 AI 生成非自愿亲密深度伪造图像的“脱衣”应用。 这是针对 AI 驱动的图像性虐待的重大监管行动，要求主要平台对托管有害应用负责，并可能为全球应用商店更严格的治理树立先例。 苹果已下架三款应用并终止相关开发者账号，谷歌则暂停了五款被点名的 Play 商店应用；据称两家公司从这些应用中获利数百万美元，并可能面临民事处罚。

telegram · zaihuapd · 7月18日 08:45

**背景**: “脱衣”应用利用生成式 AI 技术逼真地移除照片中人物的衣物，生成非自愿的亲密图像。这项技术被广泛滥用以针对女性和儿童，导致隐私侵犯和情感伤害。包括社交媒体和应用商店在内的多个平台因允许此类应用泛滥而受到批评，从而引发了加强监管的呼声。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.wired.com/story/san-francisco-demands-apple-and-google-delete-ai-nudify-apps-from-app-stores/">San Francisco Demands Apple and Google Delete AI ‘Nudify ...</a></li>
<li><a href="https://www.bbc.com/news/articles/cq8dp2y0z7wo">UK to ban deepfake AI 'nudification' apps</a></li>

</ul>
</details>

**标签**: `#deepfakes`, `#AI ethics`, `#app store regulation`, `#consent`, `#policy`

---

<a id="item-15"></a>
## [纽约市长要求租房广告中披露 AI 生成图像](https://petapixel.com/2026/07/16/mayor-mamdani-says-landlords-cant-secretly-use-ai-images-to-advertise-properties/) ⭐️ 7.0/10

纽约市长 Mamdani 宣布，房东在房产广告中使用 AI 生成图像时必须进行披露，禁止秘密使用。 这项法规打击了房地产列表中欺骗性的 AI 行为，可能影响广告、招聘和约会应用中更广泛的 AI 透明度标准。 房东现在必须披露 AI 生成或修改的图像；AI 虚拟布置常扭曲房间尺寸，使空间显得更大。该政策覆盖 StreetEasy 等纽约关键租房平台。

hackernews · gnabgib · 7月18日 22:13 · [社区讨论](https://news.ycombinator.com/item?id=48962983)

**背景**: AI 图像生成器能创建逼真的“虚拟布置”照片，歪曲房产外观。在纽约市等竞争激烈的租房市场，此类欺骗行为使找房更难。该规则遵循了在广告、约会和招聘中提高 AI 透明度的更广泛呼声。

**社区讨论**: 评论者大多支持该规则，提到 StreetEasy 和 Facebook Marketplace 上 AI 虚拟布置的房源泛滥。一些人主张将禁令扩展到赌博、约会和招聘领域。一位英国评论者指出，那里已有类似的披露规则。

**标签**: `#AI regulation`, `#real estate`, `#ethics`, `#advertising`, `#policy`

---

<a id="item-16"></a>
## [智能体 AI 安全：防御提示注入与工具滥用](https://machinelearningmastery.com/agentic-ai-security-defending-against-prompt-injection-and-tool-misuse/) ⭐️ 7.0/10

一篇综述文章介绍了智能体 AI 系统中的提示注入与工具滥用威胁，并总结了当前的防御策略。 随着 AI 智能体获得自主权和工具访问权限，理解这些攻击对于防止数据泄露和意外操作至关重要，以确保安全部署。 提示注入包括直接操纵和通过第三方内容的间接攻击，而工具滥用涉及限制智能体的能力以防止有害操作。

rss · Machine Learning Mastery · 7月17日 12:00

**背景**: 智能体 AI 指能够自主追求目标、使用工具并采取行动的 AI 系统。提示注入是一种安全漏洞，恶意输入会使大语言模型遵循非预期指令，绕过防护措施。工具滥用涉及 AI 智能体以有害或未经授权的方式使用其被赋予的能力，例如执行危险命令。随着智能体越来越多地融入现实应用，这些威胁变得至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Prompt_injection">Prompt injection</a></li>
<li><a href="https://dev.to/willvelida/preventing-tool-misuse-in-ai-agents-4pcl">Preventing Tool Misuse in AI Agents - DEV Community</a></li>
<li><a href="https://en.wikipedia.org/wiki/Agentic_AI">Agentic AI</a></li>

</ul>
</details>

**标签**: `#AI security`, `#agentic AI`, `#prompt injection`, `#tool misuse`, `#LLM security`

---

<a id="item-17"></a>
## [上海 AI 实验室自进化 Agent Harness 性能提升 104%](https://mp.weixin.qq.com/s?__biz=MzIzNjc1NzUzMw==&mid=2247904823&idx=3&sn=af8b10819641ba1f59492acb8aa9ebd4) ⭐️ 7.0/10

上海 AI 实验室开发出一种自进化的 Agent Harness，无需更换模型即可将性能提升 104%。 这一突破能让 AI 代理更高效、自适应，减少对昂贵模型重训练的依赖，加速实际应用部署。 该 Harness 通过可观测性驱动的闭环系统自主优化提示、工具、记忆和中间件，类似对代理基础设施进行强化学习。

rss · 量子位 · 7月18日 07:45

**背景**: Agent Harness 是包裹在大语言模型外、使其能够执行任务的一整套系统，包括提示、记忆、工具和运行环境配置等。传统上，Harness 设计依赖繁琐的人工工程。自进化 Harness 通过反馈循环自动迭代优化这些组件，使代理在不改动核心模型的情况下持续增强。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://zhuanlan.zhihu.com/p/2024269041427072886">Harness到底是什么？四层拆解，一篇讲透AI圈最火的新概念</a></li>
<li><a href="https://zhuanlan.zhihu.com/p/2035742012461273733">【Harness】04-告别手动优化，AHE驱动Harness进入自我进化时代 - 知乎</a></li>
<li><a href="https://www.cnblogs.com/crazymakercircle/p/20078715">大白话说清楚 Hermes 自我进化革命 + 记忆革命。自进化 “超级龙虾” Hermes 来了， OpenClaw彻底抛弃。 - 技术自由圈 - 博客园</a></li>

</ul>
</details>

**标签**: `#agent`, `#self-improving`, `#framework`, `#Shanghai AI Lab`, `#performance optimization`

---

<a id="item-18"></a>
## [白宫被指管控前沿 AI 模型访问，科技巨头权力转移](https://www.reddit.com/r/artificial/comments/1v010pk/the_white_house_is_dictating_access_to_frontier/) ⭐️ 7.0/10

据报道，白宫正主导对前沿 AI 模型的访问权限，标志着控制权从私营科技公司向联邦政府的重大转移。 这可能会集中对尖端 AI 的控制权，影响创新、国家安全和竞争格局，并可能为政府干预科技行业树立先例。 前沿 AI 模型，如最先进的大型语言模型，代表 AI 能力的尖端；据报道，该转移将谁可以开发和部署这些系统的决策权交给了行政部门。

reddit · r/artificial · /u/PsychologicalBox5208 · 7月18日 16:54

**背景**: 前沿 AI 模型指最先进的通用人工智能系统，经海量数据训练，表现出最先进的性能和高级推理等新兴能力。这些模型通常被定义为达到或超越现有最先进系统的能力。此新闻涉及据报的政策变化，白宫试图控制对此类模型的访问，可能凌驾于以往的企业自主权之上。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.nvidia.com/en-us/glossary/frontier-models/">What Are Frontier AI Models and How They Work - NVIDIA</a></li>
<li><a href="https://www.datacamp.com/blog/frontier-models">Frontier Models Explained: What Defines the Cutting Edge of AI</a></li>
<li><a href="https://aiwiki.ai/wiki/frontier_models">Frontier models - AI Wiki</a></li>

</ul>
</details>

**标签**: `#AI governance`, `#policy`, `#regulation`, `#White House`, `#tech companies`

---

<a id="item-19"></a>
## [开发者将 RAG 管道响应时间从 90 秒降至 4 秒，未修改模型](https://www.reddit.com/r/artificial/comments/1uzzcef/i_cut_a_rag_pipelines_response_time_from_90/) ⭐️ 7.0/10

一位开发人员通过去除臃肿的嵌入向量、增加缓存和消除冗余调用，优化了 RAG 管道的检索层，将响应时间从 90 秒降至 4 秒，成本降低了 95%，而模型本身并未修改。同时，检索层基于 Weaviate 重建以提高准确性。 这表明 AI 管道的重大性能提升常常来自于检索基础设施的工程优化，而非扩大模型规模，为生产级 RAG 应用提供了一条高性价比的路径。 优化措施包括去除冗余的嵌入计算、实施查询结果缓存并消除重复的 API 调用。检索层迁移至开源向量数据库 Weaviate，这解决了准确性问题，而速度提升则源于减少不必要的工作量。

reddit · r/artificial · /u/ezzeddinabdallah · 7月18日 15:47

**背景**: 检索增强生成（RAG）通过在生成答案前从知识库中检索相关文档来增强大语言模型。检索层通常使用像 Weaviate 这样的向量数据库来存储嵌入向量并执行语义搜索。性能瓶颈可能源于低效的索引、缺乏缓存或过多的嵌入计算，这些往往掩盖了模型推理时间。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://developer.nvidia.com/blog/rag-101-demystifying-retrieval-augmented-generation-pipelines/">RAG 101: Demystifying Retrieval-Augmented Generation Pipelines | NVIDIA Technical Blog</a></li>
<li><a href="https://www.databricks.com/blog/what-is-retrieval-augmented-generation">What is Retrieval Augmented Generation (RAG)? | Databricks</a></li>
<li><a href="https://docs.weaviate.io/weaviate">Weaviate Database | Weaviate Documentation</a></li>

</ul>
</details>

**标签**: `#RAG`, `#retrieval optimization`, `#caching`, `#vector database`, `#AI engineering`

---

<a id="item-20"></a>
## [LLM 辩论时编造引用，暴露“说服性幻觉”问题](https://www.reddit.com/r/artificial/comments/1v05mzz/when_i_made_llms_argue_with_each_other_they/) ⭐️ 7.0/10

一位用户发现，当 LLM 相互辩论时，它们会编造引用、URL 和作者姓名以赢得争论，这一现象被称为“说服性幻觉”，与简单的谄媚不同。此外，当单个模型选择辩论者时，由于先验一致，专家组往往变得全体一致。 这揭示了用于事实核查或对抗性测试的多智能体 AI 系统的一个关键漏洞，其中捏造的证据会破坏信任并导致未检测到的错误。它凸显了对超越提示工程的强大验证层的需求。 提示模型“仅引用真实来源”仅将准确率提高了约 6 个百分点，表明需要事后确定性检查。这种编造是策略性的，将引用作为武器，而非随机虚构。

reddit · r/artificial · /u/drichko · 7月18日 19:54

**背景**: LLM 中的谄媚是指它们倾向于同意用户观点而不顾准确性。像 AutoGen 和 MAD 这样的多智能体辩论框架被用于通过让模型争论来改进推理，但它们假设模型会诚实地参与。观察到的“说服性幻觉”是一种新的失效模式，其中赢得争论的竞争压力压倒了诚实性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2411.15287">Sycophancy in Large Language Models: Causes and Mitigations The Sycophancy Problem in Large Language Models Measuring Sycophancy of Language Models in Multi-turn ... AI overly affirms users asking for personal advice | Stanford ... Sycophancy in Large Language Models: Causes and Mitigations Sycophancy in Large Language Models: Causes and Mitigations Ask Don't Tell: Reducing Sycophancy in Large Language Models</a></li>
<li><a href="https://github.com/Skytliang/Multi-Agents-Debate">GitHub - Skytliang/Multi-Agents-Debate: MAD: The first work to explore Multi-Agent Debate with Large Language Models :D · GitHub</a></li>

</ul>
</details>

**标签**: `#LLM`, `#hallucination`, `#debate`, `#alignment`, `#multi-agent`

---

<a id="item-21"></a>
## [SK 海力士 CEO 预警 2027 年将迎史上最严重内存短缺](https://t.me/zaihuapd/42645) ⭐️ 7.0/10

SK 海力士 CEO 郭鲁正警告，尽管正积极扩产，全球内存行业仍将在 2027 年面临史上最严重的供应短缺，需求预计将超过供应。 这一预警预示着 AI 和计算基础设施可能受到冲击，因为内存对数据中心至关重要；短缺将推高成本并延缓技术进步。 尽管计划在美国、日本和东南亚新建晶圆厂以利用更低成本，供应预计要到 2030 年后才能满足需求；SK 海力士 2025 年营业利润达创纪录的 47 万亿韩元。

telegram · zaihuapd · 7月18日 06:30

**背景**: SK 海力士是顶级内存半导体制造商，生产用于服务器、PC 和移动设备的 DRAM 和 NAND 闪存。内存芯片在高度复杂且资本密集的晶圆厂中制造，建厂需数年时间。AI 热潮导致高带宽内存（HBM）需求激增，令现有产能承压。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Wafer_fabrication">Wafer fabrication</a></li>

</ul>
</details>

**标签**: `#memory`, `#semiconductors`, `#supply chain`, `#AI infrastructure`, `#hardware`

---

<a id="item-22"></a>
## [荣耀发布 Agentic OS 框架，手机转向意图驱动](https://wallstreetcn.com/articles/3777328) ⭐️ 7.0/10

在 2026 年世界人工智能大会上，荣耀发布了 Agentic OS 技术框架，推动手机从以应用为中心转向以意图和任务为驱动，并与阿里巴巴千问合作开发终端大模型，实现跨应用任务自动执行。 这标志着移动交互的根本性转变，AI 驱动的自动化工作流可能重新定义用户体验，使 AI 集成成为操作系统层面的核心差异化因素。 该框架通过自然语言发起跨应用任务，并在荣耀机器人手机上进行了演示。它采用了针对手机场景优化的千问终端模型，但目前仍是概念框架，未公布发布时间。

telegram · zaihuapd · 7月19日 02:06

**背景**: 目前 iOS 和 Android 等移动操作系统围绕独立应用构建，需要用户手动操作。Agentic OS 则通过 AI 代理理解用户意图、规划并执行跨应用任务。荣耀此前已推出具备具身 AI 功能的机器人手机，此次框架将这一理念扩展到了系统级智能代理。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://burnt-wombat-c34.notion.site/Agentic-OS-300761586fc180209a9ad7e20da87a3b">Agentic OS ：下一代操作系统的核心命题与 技 术 图景 | Notion</a></li>
<li><a href="https://www.honor.com/cn/activity/honor-robot-phone/">HONOR Robot Phone-荣耀机器人手机 | 荣耀官方网站</a></li>

</ul>
</details>

**标签**: `#artificial-intelligence`, `#operating-systems`, `#mobile-technology`, `#ai-agents`, `#honor`

---