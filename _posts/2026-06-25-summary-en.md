---
layout: default
title: "Horizon Summary: 2026-06-25 (EN)"
date: 2026-06-25
lang: en
---

> From 72 items, 29 important content pieces were selected

---

1. [OpenAI and Broadcom Launch Jalapeño, First Custom AI Chip](#item-1) ⭐️ 9.0/10
2. [Krea 2: SOTA Open-Weights 12B Image Model Released](#item-2) ⭐️ 9.0/10
3. [Qualcomm to Acquire Modular for $4 Billion](#item-3) ⭐️ 8.0/10
4. [Modern GitHub PR Spam Mirrors Early 2000s Email Spam](#item-4) ⭐️ 8.0/10
5. [Elastic lays off 7% of employees in AI-driven restructuring](#item-5) ⭐️ 8.0/10
6. [Nub: Bun-like All-in-One Toolkit for Node.js Using Preload Hook](#item-6) ⭐️ 8.0/10
7. [John Carmack Acknowledges Early Leadership Mistakes at id Software](#item-7) ⭐️ 8.0/10
8. [AI Resumes Create Accidental Anonymity](#item-8) ⭐️ 8.0/10
9. [Datasette 1.0a35 Adds Table Creation and Alteration UI/API](#item-9) ⭐️ 8.0/10
10. [TRM Reward Model Quantifies LLM Reasoning Quality – ICML 2026 Oral](#item-10) ⭐️ 8.0/10
11. [Databricks Leaders: Open Ecosystems Key to Scalable Agent Clouds](#item-11) ⭐️ 8.0/10
12. [Claude Slackbot Upgrade: Multiplayer, Proactive, and Persistent](#item-12) ⭐️ 8.0/10
13. [GPT-5 Pro Helps Immunologist Solve 3-Year T-Cell Mystery](#item-13) ⭐️ 8.0/10
14. [Unlimited-OCR: 3.3B Multilingual OCR Model Released on ModelScope under MIT License](#item-14) ⭐️ 8.0/10
15. [GLM-5.2 MTP Speculative Decode Running on 4× DGX Spark with Reconstructed Build](#item-15) ⭐️ 8.0/10
16. [Cloudflare, Browsers Propose PACT to Replace CAPTCHAs with Tokens](#item-16) ⭐️ 8.0/10
17. [Anthropic Accuses Alibaba of Large-Scale Distillation Attack](#item-17) ⭐️ 8.0/10
18. [RubyLLM: Unified Ruby Framework for AI APIs](#item-18) ⭐️ 7.0/10
19. [NVIDIA's 45°C Cooling Cuts Data Center Water Use to Near Zero](#item-19) ⭐️ 7.0/10
20. [Swiss Supreme Court Tests Abliterated Model Heretic for Legal Use](#item-20) ⭐️ 7.0/10
21. [Gefen Optimizer Offers 8x Memory Reduction as Drop-in AdamW Replacement](#item-21) ⭐️ 7.0/10
22. [Bank of Korea: AI Saves Time but Not Productivity](#item-22) ⭐️ 7.0/10
23. [AMD Strix Halo NPUs Now Usable for Hybrid LLM Inference](#item-23) ⭐️ 7.0/10
24. [SDXL Runs Locally in Browser via WebGPU Extension](#item-24) ⭐️ 7.0/10
25. [GLM5.2 Inference Speedup from 2.5 to >50 tok/s via Weight Merging and vLLM Patching](#item-25) ⭐️ 7.0/10
26. [用生成式 AI 写作业或降低中国学生考试成绩](#item-26) ⭐️ 7.0/10
27. [ByteDance, Broadcom said to co-develop 5nm AI chip; ByteDance denies](#item-27) ⭐️ 7.0/10
28. [Micron Q3 Revenue Soars 346% to $414.6B on AI Demand](#item-28) ⭐️ 7.0/10
29. [Google Play Expands External Billing to US, UK, Europe](#item-29) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [OpenAI and Broadcom Launch Jalapeño, First Custom AI Chip](https://techcrunch.com/2026/06/24/openai-unveils-its-first-custom-chip-built-by-broadcom/) ⭐️ 9.0/10

On June 24, 2026, OpenAI announced Jalapeño, its first custom inference chip designed in partnership with Broadcom and fabricated by TSMC, completed in just nine months. This move signals a strategic effort by OpenAI to reduce dependency on Nvidia GPUs, potentially lowering inference costs and improving performance for its AI services. The chip is purpose-built for large language model inference, not training, and its rapid nine-month development was reportedly aided by OpenAI's own models, though this claim draws skepticism.

hackernews · jamdesk · Jun 24, 17:47 · [Discussion](https://news.ycombinator.com/item?id=48663324)

**Background**: AI inference chips are specialized processors optimized to run trained AI models efficiently. Unlike GPUs, which are general-purpose, these chips offer higher performance-per-watt for specific tasks. Major tech companies like Google with TPUs and Amazon with Trainium have developed custom chips to reduce reliance on Nvidia.

<details><summary>References</summary>
<ul>
<li><a href="https://openai.com/index/openai-broadcom-jalapeno-inference-chip/">OpenAI and Broadcom unveil LLM-optimized inference chip</a></li>
<li><a href="https://www.cnbc.com/2026/06/24/openai-and-broadcom-reveal-jalapeno-first-ai-chip-in-partnership.html">OpenAI and Broadcom reveal Jalapeno, first AI chip in partnership - CNBC</a></li>
<li><a href="https://uvation.com/articles/ai-inference-chips-latest-rankings-who-leads-the-race">AI Inference Chips 2025: Rankings & Leaders - uvation.com</a></li>

</ul>
</details>

**Discussion**: Overall sentiment is enthusiastic but cautious, with skepticism around the AI-accelerated design claim and interest in more radical chip architectures. Some note the strategic importance and compare to Google's TPUs.

**Tags**: `#AI`, `#custom-silicon`, `#inference`, `#OpenAI`, `#Broadcom`

---

<a id="item-2"></a>
## [Krea 2: SOTA Open-Weights 12B Image Model Released](https://www.krea.ai/blog/krea-2-technical-report) ⭐️ 9.0/10

Krea has released open weights for Krea 2, a 12-billion-parameter text-to-image model that achieves state-of-the-art results among locally hostable models, along with a fast distilled Turbo variant that generates images in seconds. A detailed technical report accompanies the release, covering training infrastructure, data curation, and RL pipelines. This release sets a new benchmark for open-weights image generation, combining top-tier quality with local hostability. It empowers researchers and developers to customize and deploy powerful generative AI without relying on closed APIs, accelerating innovation and democratization. The Turbo model uses guidance and timestep distillation for 8-step inference, offering speed rivaling much larger systems, though it struggles with some known tricky prompts like nine-pointed stars. Weights are available for local hosting in formats like GGUF.

hackernews · mattnewton · Jun 23, 15:31 · [Discussion](https://news.ycombinator.com/item?id=48646659)

**Background**: Open-weights models make their learned parameters publicly available, allowing users to fine-tune or run them on their own hardware. Model distillation, pioneered by Hinton et al., transfers knowledge from a large teacher model to a smaller student model, reducing inference cost while retaining quality. This technique is key to making high-performance AI accessible on consumer devices.

<details><summary>References</summary>
<ul>
<li><a href="https://www.oracle.com/artificial-intelligence/ai-open-weights-models/">"Open-weights" AI models offer transparency and control. - Oracle</a></li>
<li><a href="https://en.wikipedia.org/wiki/Model_distillation">Model distillation</a></li>

</ul>
</details>

**Discussion**: HN commenters praised the detailed technical report and the model's strong performance, especially the Turbo variant's speed. Some noted it still fails on certain challenging test prompts, but overall it surpassed all other locally hostable models except the slower Ideogram 4. A few saw the pure text-to-image focus as 'fighting the last war' given recent agentic image-to-image advances, but others appreciated its wide style range.

**Tags**: `#text-to-image`, `#open-weights`, `#generative-AI`, `#machine-learning`, `#AI`

---

<a id="item-3"></a>
## [Qualcomm to Acquire Modular for $4 Billion](https://www.reuters.com/business/qualcomm-buy-ai-startup-modular-2026-06-24/) ⭐️ 8.0/10

Qualcomm announced the acquisition of Modular, the AI startup behind the Mojo programming language and MAX platform, in a deal valued at $4 billion. This acquisition merges Qualcomm's hardware expertise with Modular's AI compiler stack, potentially competing with NVIDIA's CUDA and accelerating AI inference on edge devices. Modular's Mojo, built on the MLIR compiler framework, targets CPUs, GPUs, and accelerators; a Mojo 1.0 beta was recently released, and open-sourcing is planned for fall 2026.

hackernews · timmyd · Jun 24, 13:49 · [Discussion](https://news.ycombinator.com/item?id=48659798)

**Background**: Modular was founded by Chris Lattner, creator of LLVM and Swift. Mojo aims to combine Python's ease of use with systems-level performance, while MAX is a high-performance AI inference framework. The company's technology is built on MLIR, a modern compiler infrastructure that enables advanced optimizations across diverse hardware.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mojo_(programming_language)">Mojo (programming language)</a></li>
<li><a href="https://github.com/modular/modular">GitHub - modular/modular: The Modular Platform (includes MAX & Mojo) · GitHub</a></li>
<li><a href="https://www.modular.com/max">MAX: A high-performance inference framework for AI</a></li>

</ul>
</details>

**Discussion**: Commenters expressed surprise at the speed of the acquisition and mixed feelings about Mojo's focus on Python compatibility. Some highlighted the strategic potential for Qualcomm's ARM-based chips to run AI inference using Mojo/MAX, while others noted Qualcomm's broader portfolio moves toward RISC-V and AI infrastructure.

**Tags**: `#AI`, `#acquisition`, `#compiler`, `#hardware`, `#edge computing`

---

<a id="item-4"></a>
## [Modern GitHub PR Spam Mirrors Early 2000s Email Spam](https://www.greptile.com/blog/prs-on-openclaw) ⭐️ 8.0/10

A growing discussion highlights that spam pull requests on GitHub have become as pervasive as email spam in the early 2000s, posing significant challenges for open source maintainers. The article explores community-driven reputation systems as a potential mitigation. This trend threatens the quality and sustainability of open source projects by overwhelming maintainers with low-quality contributions. Addressing it could improve the contributor experience and safeguard the health of the open source ecosystem. GitHub recently introduced configurable PR limits for maintainers, but the problem differs from email spam because PR spam relies on individual user accounts rather than server reputation. Some projects now require maintainers to interact with contributors in non-textual formats before merging PRs.

hackernews · dakshgupta · Jun 24, 14:32 · [Discussion](https://news.ycombinator.com/item?id=48660579)

**Background**: Email spam in the early 2000s was combated through IP reputation, blacklists, and laws like CAN-SPAM. GitHub PR spam involves unsolicited or trivial pull requests, often from events like Hacktoberfest, where participants create low-quality contributions for rewards. Unlike email, where server reputation could be monitored, GitHub lacks built-in user reputation systems, making it harder to filter out spam. A community-driven reputation system could assign trust scores to contributors based on past behavior, similar to email sender reputation.

<details><summary>References</summary>
<ul>
<li><a href="https://socket.dev/blog/express-js-spam-prs-commoditization-of-open-source">Express.js Spam PRs Incident Highlights the Commoditization ... - Socket</a></li>
<li><a href="https://github.com/orgs/community/discussions/53233">What should I do about spam issues or pull requests?</a></li>

</ul>
</details>

**Discussion**: Commenters note that GitHub's new configurable limits are a step forward but insufficient, as PR spam is based on individual accounts, unlike email spam's server-based reputation. Some suggest reputation infrastructure similar to email's, while others propose requiring non-textual interactions before merging PRs. Overall, there is support for exploring reputation-based solutions.

**Tags**: `#open-source`, `#spam`, `#github`, `#maintainer-experience`, `#reputation-systems`

---

<a id="item-5"></a>
## [Elastic lays off 7% of employees in AI-driven restructuring](https://www.elastic.co/blog/ceo-ash-kulkarni-announcement-to-elastic-employees) ⭐️ 8.0/10

Elastic announced a layoff of 7% of its workforce, approximately 245 employees, as part of a reorganization aimed at simplifying its structure and shifting resources toward AI-driven growth areas. This move highlights the growing trend of tech companies leveraging AI not only in products but also to reshape their workforce, raising concerns about job displacement and the strategic rationale behind such cuts. The layoffs were disclosed in a CEO blog post; a parallel SEC filing indicated plans to increase headcount in go-to-market roles, contrasting with the 2022 layoffs blamed on economic conditions.

hackernews · dakrone · Jun 24, 21:57 · [Discussion](https://news.ycombinator.com/item?id=48666100)

**Background**: Elastic is the company behind Elasticsearch, a widely used open-source search and analytics engine. It provides enterprise solutions for search, observability, and security. The company previously laid off employees in 2022 amid economic tightening, and now cites AI advances as a driver of organizational change.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Elastic_NV">Elastic NV - Wikipedia</a></li>
<li><a href="https://www.elastic.co/about">Hi, we're Elastic</a></li>
<li><a href="https://en.wikipedia.org/wiki/Elasticsearch">Elasticsearch</a></li>

</ul>
</details>

**Discussion**: Community reactions included sadness from a former employee, criticism of the CEO's focus on future growth over the human impact, and accusations of mismanagement. Some noted that layoffs were once seen as a sign of company failure but have become normalized.

**Tags**: `#layoffs`, `#Elastic`, `#AI`, `#corporate-restructuring`, `#tech-industry`

---

<a id="item-6"></a>
## [Nub: Bun-like All-in-One Toolkit for Node.js Using Preload Hook](https://github.com/nubjs/nub) ⭐️ 8.0/10

Nub introduces a preload hook that adds fast TypeScript transpilation via oxc, module resolution hooks, and polyfills for APIs like Worker and Temporal to stock Node.js, providing a Bun-like developer experience without replacing the runtime. This approach brings the convenience of Bun's integrated tooling to the Node.js ecosystem, allowing developers to enjoy modern DX while staying on the stable, widely-supported Node.js runtime. It could reduce the need for separate build tools and polyfills. The toolkit uses a `--require` preload hook (not `--import`), which might lead to ESM edge case limitations like top-level await. It relies on oxc, a fast Rust-based transpiler, and is purely additive, preserving Node.js internals.

hackernews · colinmcd · Jun 24, 14:14 · [Discussion](https://news.ycombinator.com/item?id=48660267)

**Background**: Bun is a JavaScript runtime that natively supports TypeScript, JSX, and includes built-in tools like bundlers and test runners. Node.js traditionally requires separate tools (e.g., ts-node for TypeScript). Nub fills this gap by injecting these capabilities directly into Node via hooks, using oxc (a fast JavaScript/TypeScript transpiler) and polyfilling newer APIs like Temporal (a modern date-time API replacing `Date`).

<details><summary>References</summary>
<ul>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Temporal">Temporal - JavaScript | MDN - MDN Web Docs</a></li>
<li><a href="https://git.hubp.de/topics/transpiler">transpiler · GitHub Topics · GitHub</a></li>

</ul>
</details>

**Discussion**: Commenters praised the innovative idea and noted the creator's background (Colin McDonnell of Zod and Bun). Some questioned the use of `--require` over `--import` for ESM, and whether TypeScript support is already in Node. Others reported rapid adoption with zero issues, while some asked why not just use Bun, suggesting competition or overlap.

**Tags**: `#nodejs`, `#toolkit`, `#bun`, `#typescript`, `#developer-experience`

---

<a id="item-7"></a>
## [John Carmack Acknowledges Early Leadership Mistakes at id Software](https://twitter.com/ID_AA_Carmack/status/2069799283369345247) ⭐️ 8.0/10

John Carmack publicly acknowledged his early leadership mistakes at id Software, particularly pushing his teams too hard. His candid reflection, shared on Twitter, ignited a wide-ranging discussion on management and the evolution of the game industry. This reflection from a legendary figure in game development offers rare insight into the human costs of relentless startup intensity. It resonates with ongoing conversations about sustainable work practices and leadership in the tech industry. Carmack specifically mentioned the development of Quake as a period where intense pressure may have damaged the company. Subsequent comments from former colleagues like Sandy Petersen provide a more complex picture of the interpersonal dynamics during that era.

hackernews · shadowtree · Jun 24, 15:56 · [Discussion](https://news.ycombinator.com/item?id=48661825)

**Background**: John Carmack co-founded id Software and was the lead programmer on landmark games such as Doom and Quake. The company was known for a 'crunch' culture where long hours were common, a practice that has since been debated in the industry. Carmack's admission comes long after his departure from id Software, as he now focuses on artificial general intelligence research.

**Discussion**: The community largely respects Carmack's honesty but remains split: some argue that the groundbreaking results justified the means, while others emphasize the toll on developers. Comments also highlight differing accounts, such as Sandy Petersen's perspective, and debate whether the company's later decline stemmed from early burnout.

**Tags**: `#tech leadership`, `#game development`, `#management`, `#startup culture`, `#john carmack`

---

<a id="item-8"></a>
## [AI Resumes Create Accidental Anonymity](https://simonwillison.net/2026/Jun/24/tom-macwright/#atom-everything) ⭐️ 8.0/10

Tom MacWright observes that job applications are now often co-written by LLMs, featuring AI-generated portfolios and GitHub projects with AI-generated commit messages, making candidates indistinguishable. This trend undermines the hiring process by erasing personal authenticity, making it harder for employers to assess real skills, and ultimately hurting candidates who rely on AI shortcuts. LLM-generated materials are polished but generic, lacking the personal voice and truthfulness needed to reveal a candidate’s genuine experience or personality.

rss · Simon Willison · Jun 24, 18:13

**Background**: Large language models (LLMs) like GPT-4 can generate coherent text for documents. In job applications, candidates may use them to write resumes, create portfolio sites, and generate code repositories, but the output often becomes generic and fails to showcase individuality.

**Tags**: `#careers`, `#ai`, `#llm`, `#job-applications`, `#authenticity`

---

<a id="item-9"></a>
## [Datasette 1.0a35 Adds Table Creation and Alteration UI/API](https://simonwillison.net/2026/Jun/23/datasette/#atom-everything) ⭐️ 8.0/10

Datasette 1.0a35 introduces a new "Create table" interface and JSON API for defining columns, constraints, defaults, and foreign keys, along with an "Alter table" feature that allows changing existing tables, backed by JSON APIs. These features turn Datasette into a more complete database management tool, enabling users to directly manage schema through a web UI or API, which is valuable for data exploration and lightweight applications. The APIs are at /<database>/-/create and /<database>/<table>/-/alter; creation supports custom column types, NOT NULL, literal and expression defaults, and single-column foreign keys. Alter table allows adding, renaming, reordering, and dropping columns, changing types, defaults, and constraints, plus a drop table button.

rss · Simon Willison · Jun 23, 21:34

**Background**: Datasette is an open-source tool by Simon Willison for exploring and publishing SQLite databases through a web UI and JSON API. Previously, schema modifications required external SQLite tools. This release integrates basic schema management, making Datasette more self-sufficient for data projects.

**Tags**: `#datasette`, `#data-management`, `#web-tools`, `#json-api`, `#database`

---

<a id="item-10"></a>
## [TRM Reward Model Quantifies LLM Reasoning Quality – ICML 2026 Oral](https://mp.weixin.qq.com/s?__biz=MzIzNjc1NzUzMw==&mid=2247899199&idx=3&sn=b0d6764e50d881295fd85b75f8f9434a) ⭐️ 8.0/10

The Thinking-supervised Reward Model (TRM) has been introduced to evaluate the quality of reasoning processes in large language models, not just final answers. Accepted as an Oral at ICML 2026, it has already gained 4.2k GitHub stars. This work addresses a critical gap in AI evaluation by quantifying the reasoning behind answers, which can improve LLM reliability and guide the development of more robust reasoning systems. TRM employs intermediate reasoning steps and multi-stage training; it assesses answer faithfulness by checking each sentence against supporting documents, then evaluates sentence-level correctness. The open-source repository has received 4.2k stars.

rss · 量子位 · Jun 24, 04:00

**Background**: Large language models often produce correct answers with flawed reasoning, making outputs hard to trust. Traditional reward models only evaluate final answers, ignoring the process. The International Conference on Machine Learning (ICML) is a top AI venue, and an Oral presentation denotes high impact. TRM aims to supervise reasoning faithfully.

<details><summary>References</summary>
<ul>
<li><a href="https://www.emergentmind.com/topics/thinking-supervised-reward-model-trm">Thinking-supervised Reward Model (TRM) - emergentmind.com</a></li>
<li><a href="https://eu.36kr.com/en/p/3866659734279170">TRM Thinking Reward Model Launched: Large Models' Reasoning Quality Can ...</a></li>
<li><a href="https://github.com/Martin-qyma/TRM">GitHub - Martin-qyma/TRM: From Faithfulness to Correctness: Generative ...</a></li>

</ul>
</details>

**Tags**: `#large language models`, `#reasoning`, `#reward modeling`, `#ICML`, `#AI evaluation`

---

<a id="item-11"></a>
## [Databricks Leaders: Open Ecosystems Key to Scalable Agent Clouds](https://www.latent.space/p/databricks) ⭐️ 8.0/10

In a rare joint interview, Databricks co-founders Matei Zaharia and Reynold Xin argued that an open ecosystem is essential for enterprises to build scalable agent clouds, advocating for interoperability and avoidance of vendor lock-in. This perspective influences enterprise AI strategy, promoting open standards that can accelerate adoption of agent-based automation while reducing dependence on proprietary platforms. They likely highlighted Databricks' open-source projects such as Delta Lake and MLflow as critical components for building robust agent clouds, and discussed technical challenges like agent orchestration and secure data access.

rss · Latent Space · Jun 24, 18:53

**Background**: Databricks is a data and AI platform founded by the creators of Apache Spark. Matei Zaharia is the original creator of Spark and CTO at Databricks; Reynold Xin is a co-founder and chief architect. The term 'agent clouds' refers to cloud infrastructure designed to host and manage AI agents that can autonomously perform tasks, integrating with enterprise data and tools.

**Tags**: `#ai-agents`, `#databricks`, `#open-source`, `#cloud-computing`, `#machine-learning`

---

<a id="item-12"></a>
## [Claude Slackbot Upgrade: Multiplayer, Proactive, and Persistent](https://www.latent.space/p/ainews-claude-tag-multiplayer-proactive) ⭐️ 8.0/10

Anthropic has upgraded Claude to function as a multiplayer, proactive, and persistent AI agent within Slack, enabling collaborative, autonomous, and context-aware interactions. This upgrade integrates AI agents more deeply into daily workflows, potentially transforming team productivity by allowing multiple AI agents to collaborate proactively and maintain context over time. The Slackbot allows users to tag Claude in channels to invoke agent actions, supporting persistent memory across sessions and proactive suggestions based on context.

rss · Latent Space · Jun 24, 07:14

**Background**: Claude is Anthropic's AI assistant, known for safety and large context windows. Slack is a widely used team collaboration platform. AI agents are software entities that perform tasks autonomously; multiplayer agents collaborate, proactive agents anticipate needs, and persistent agents maintain state over time.

<details><summary>References</summary>
<ul>
<li><a href="https://slack.com/blog/productivity/proactive-ai-agents-definition-core-components-and-business-value">Proactive AI Agents: Definition, Core Components, and Business Value | Slack</a></li>
<li><a href="https://www.lyzr.ai/glossaries/proactive-ai-agents/">Proactive AI Agents</a></li>

</ul>
</details>

**Tags**: `#AI agents`, `#Claude`, `#Slack`, `#Anthropic`, `#Collaboration`

---

<a id="item-13"></a>
## [GPT-5 Pro Helps Immunologist Solve 3-Year T-Cell Mystery](https://openai.com/index/gpt-5-immunology-mystery) ⭐️ 8.0/10

GPT-5 Pro assisted immunologist Derya Unutmaz in resolving a three-year-old mystery about T cell behavior, offering new insights that could advance cancer and autoimmune research. This demonstrates AI's growing ability to accelerate complex biological research, potentially leading to faster development of therapies for cancer and autoimmune diseases. The specific mechanism by which GPT-5 Pro contributed remains undisclosed, but it likely involved advanced data analysis or hypothesis generation capabilities of the model.

rss · OpenAI Blog · Jun 23, 17:00

**Background**: T cells are a crucial part of the adaptive immune system, responsible for recognizing and attacking infected or cancerous cells. Understanding their behavior is key to developing immunotherapies. GPT-5 Pro is a state-of-the-art language model capable of processing and synthesizing vast amounts of scientific data.

**Tags**: `#AI`, `#GPT-5`, `#immunology`, `#scientific discovery`, `#healthcare`

---

<a id="item-14"></a>
## [Unlimited-OCR: 3.3B Multilingual OCR Model Released on ModelScope under MIT License](https://www.reddit.com/r/LocalLLaMA/comments/1ue51uk/unlimitedocr_is_now_on_modelscope_a_33b/) ⭐️ 8.0/10

Unlimited-OCR, a 3.3B-parameter multilingual OCR model, has been released on ModelScope under the MIT license. It features full-document parsing for single images, multi-page documents, and PDFs, with 32K output length and OpenAI-compatible streaming via SGLang. This release makes advanced document-level OCR accessible to the open-source community, enabling efficient, one-shot parsing of long documents without cropped regions. Its MIT license and efficient serving stack lower barriers for local deployment and integration into AI pipelines. The model supports 'Base' and 'Gundam' image modes inherited from DeepSeek-OCR, optimizing for different document layouts, and achieves 32K token output for long sequences. It can be run using Transformers for inference or SGLang for high-throughput serving with OpenAI-compatible streaming requests.

reddit · r/LocalLLaMA · /u/Sporeboss · Jun 24, 05:53

**Background**: OCR (Optical Character Recognition) extracts text from images. Traditional OCR systems often work by cropping image regions, but recent models like DeepSeek-OCR enable end-to-end document parsing. ModelScope is a Chinese platform for sharing AI models. SGLang is a high-performance serving framework supporting multimodal models with OpenAI-compatible APIs. 'Gundam' mode is designed for complex layouts, while 'Base' mode handles standard images.

<details><summary>References</summary>
<ul>
<li><a href="https://www.explainx.ai/blog/baidu-unlimited-ocr-one-shot-long-horizon-parsing-2026">Baidu Unlimited-OCR: One-Shot Long-Horizon Document Parsing ...</a></li>
<li><a href="https://huggingface.co/deepseek-ai/DeepSeek-OCR/discussions/100">deepseek-ai/DeepSeek-OCR · How to use Large/Gundam mode with ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/SGLang">SGLang</a></li>

</ul>
</details>

**Tags**: `#OCR`, `#multilingual`, `#document-parsing`, `#MIT-license`, `#LocalLLaMA`

---

<a id="item-15"></a>
## [GLM-5.2 MTP Speculative Decode Running on 4× DGX Spark with Reconstructed Build](https://www.reddit.com/r/LocalLLaMA/comments/1ueqfzl/got_glm52_mtp_speculative_decode_running_on_4_dgx/) ⭐️ 8.0/10

The user successfully reconstructed missing Docker image modifications from a public recipe and deployed GLM-5.2 with MTP speculative decoding on four DGX Spark (GB10) devices, achieving approximately 9.4 tokens per second decoding speed. This accomplishment enables efficient local inference for a large model on edge AI hardware, demonstrating a 2× speedup over existing solutions and providing a reproducible build process for the community, which lowers the barrier for running advanced LLMs locally. The missing Docker modifications were reconstructed via a script that patches deep_gemm.py, sparse_attn_indexer.py, and applies a flashmla-to-Triton monkeypatch. Building vLLM at the exact pinned commit is mandatory; otherwise, the AWQ-INT4 weights crash with an async CUDA error. The deterministic 15% expert prune reduces the model size to fit on the devices, and single-rail RoCE achieves ~9.4 tok/s, with dual-rail potentially doubling throughput.

reddit · r/LocalLLaMA · /u/anvarazizov · Jun 24, 21:23

**Background**: GLM-5.2 is a large language model. Multi-Token Prediction (MTP) is a speculative decoding technique where the model predicts multiple future tokens at once, accelerating generation without a separate draft model. Sparse Multi-head Latent Attention (sparse-MLA) is a transformer variant that uses latent representations and selective token re-evaluation to reduce computational cost, as pioneered by DeepSeek. AWQ (Activation-aware Weight Quantization) compresses model weights to 4-bit integers while preserving accuracy. The NVIDIA DGX Spark is a compact AI computer powered by a GB10 Grace Blackwell Superchip, suitable for local AI workloads.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.vllm.ai/en/latest/features/speculative_decoding/mtp/">MTP (Multi-Token Prediction) - vLLM</a></li>
<li><a href="https://sebastianraschka.com/llm-architecture-gallery/deepseek-sparse-attention/">DeepSeek Sparse Attention | Sebastian Raschka, PhD</a></li>
<li><a href="https://www.spheron.network/blog/awq-quantization-guide-llm-deployment/">AWQ Quantization Guide: Deploy LLMs at Half the GPU Cost ...</a></li>

</ul>
</details>

**Tags**: `#vLLM`, `#GLM-5.2`, `#speculative-decoding`, `#local-llm`, `#sparse-mla`

---

<a id="item-16"></a>
## [Cloudflare, Browsers Propose PACT to Replace CAPTCHAs with Tokens](https://www.techtimes.com/articles/318891/20260623/cloudflare-chrome-firefox-plan-replace-captchas-cryptographic-tokens.htm) ⭐️ 8.0/10

Cloudflare, Chrome, Firefox, Edge, and Shopify have proposed the PACT protocol, which replaces website CAPTCHAs with anonymous cryptographic tokens obtained after user verification at trusted sites. This could eliminate frustrating CAPTCHA puzzles while preserving user privacy and preventing tracking, representing a major shift in web authentication. The protocol is based on the IETF’s Privacy Pass and uses blind signature technology; it also addresses distinguishing legitimate AI agents from malicious crawlers. However, governance of token issuers and Apple’s absence remain open issues.

telegram · zaihuapd · Jun 24, 06:30

**Background**: CAPTCHAs are challenges (e.g., image recognition) used to verify human users. Blind signatures allow a signer to sign a message without knowing its content, providing unlinkability. The IETF’s Privacy Pass protocol leverages blind signatures to issue anonymous authentication tokens, enabling websites to verify users without tracking them.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Blind_signature">Blind signature</a></li>

</ul>
</details>

**Tags**: `#cryptography`, `#web standards`, `#privacy`, `#authentication`, `#CAPTCHA`

---

<a id="item-17"></a>
## [Anthropic Accuses Alibaba of Large-Scale Distillation Attack](https://www.cnbc.com/2026/06/24/anthropic-alibaba-distillation-campaign.html) ⭐️ 8.0/10

Anthropic revealed that Alibaba conducted the largest known distillation attack against it, using 25,000 fraudulent accounts to generate 28.8 million Claude interactions between April 22 and June 5, 2026. This accusation intensifies U.S.-China AI tensions and raises urgent questions about model extraction attacks, likely prompting tighter export controls and security measures across the AI industry. The attack employed black-box distillation; Alibaba's AI lab Qwen was involved. The timing coincides with U.S. export restrictions on Anthropic's Mythos and Fable models and Alibaba's addition to a Pentagon military company list.

telegram · zaihuapd · Jun 25, 01:36

**Background**: Distillation is a technique where a 'student' model learns by mimicking a 'teacher' model's outputs, often used in model extraction attacks to replicate proprietary AI capabilities. As advanced AI becomes critical IP, governments are imposing export controls to curb unauthorized access. Anthropic's Claude Mythos family represents state-of-the-art models, with Mythos Preview excelling in cybersecurity tasks.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/news/detecting-and-preventing-distillation-attacks">Detecting and preventing distillation attacks \ Anthropic</a></li>
<li><a href="https://en.wikipedia.org/wiki/Model_extraction">Model extraction</a></li>

</ul>
</details>

**Discussion**: Community comments highlighted the irony of Anthropic's complaint, given its own use of web data without explicit permission. Some argued that model distillation is standard competitive practice, while others acknowledged the scale and fraudulent methods as serious security issues.

**Tags**: `#AI Security`, `#Model Extraction`, `#Anthropic`, `#Alibaba`, `#US-China Relations`

---

<a id="item-18"></a>
## [RubyLLM: Unified Ruby Framework for AI APIs](https://rubyllm.com/) ⭐️ 7.0/10

RubyLLM, a Ruby framework, provides a unified API to interact with major AI providers, emphasizing ease of use and flexibility. It recently introduced native support for the Responses API. It lowers the barrier for Ruby developers to build AI-powered applications by abstracting provider differences, fostering AI adoption in the Ruby ecosystem. Caching does not consistently work for some providers like xAI, and maintainer responsiveness and code quality (e.g., vibe-coded PRs) have been points of concern.

hackernews · doener · Jun 24, 14:41 · [Discussion](https://news.ycombinator.com/item?id=48660711)

**Background**: RubyLLM is an open-source Ruby library that abstracts interactions with multiple AI providers under a single interface. It is inspired by the JavaScript AI SDK from Vercel and aims to provide a developer-friendly experience. This allows Ruby developers to integrate AI features without juggling different API specifications.

**Discussion**: The community finds RubyLLM surprisingly good and easy to use, comparing it favorably to Vercel's AI framework. However, concerns include inconsistent caching for xAI, maintainer engagement issues, and limited trace observability. Some users are excited about the new native Responses API support and a related gem, Raix, built on top of it.

**Tags**: `#ruby`, `#ai`, `#llm`, `#framework`, `#open-source`

---

<a id="item-19"></a>
## [NVIDIA's 45°C Cooling Cuts Data Center Water Use to Near Zero](https://blogs.nvidia.com/blog/liquid-cooling-ai-factories/) ⭐️ 7.0/10

NVIDIA introduced a direct-to-chip liquid cooling architecture that operates at 45°C, drastically reducing water consumption compared to traditional evaporative cooling systems. This innovation addresses the growing environmental concern of water usage in AI data centers and could enable waste heat reuse for district heating, benefiting local communities. The system uses direct-to-chip cooling with coolant temperatures up to 45°C, but its efficiency depends on favorable climates; warmer environments may still require additional cooling or water use.

hackernews · nitin_flanker · Jun 24, 14:10 · [Discussion](https://news.ycombinator.com/item?id=48660178)

**Background**: Traditional data centers often rely on air cooling or evaporative cooling, which consume large amounts of water and energy. Liquid cooling is more efficient but typically operates at lower temperatures, like 30-35°C, to manage heat. By raising the coolant temperature to 45°C, NVIDIA reduces the need for chillers and enables easier waste heat reuse, as higher temperature heat is more useful for district heating.

<details><summary>References</summary>
<ul>
<li><a href="https://www.guru3d.com/story/nvidia-unveils-liquid-cooling-design-for-ai-data-centers/">NVIDIA Unveils 45 ° C Liquid Cooling Design for AI Data Centers</a></li>
<li><a href="https://www.techbuzz.ai/articles/nvidia-s-45-c-liquid-cooling-redefines-ai-data-center-energy">NVIDIA's 45 ° C Liquid Cooling Redefines AI Data Center Energy</a></li>
<li><a href="https://www.sciencedirect.com/science/article/pii/S1364032125005362">Data center waste heat for district heating networks: A ...</a></li>

</ul>
</details>

**Discussion**: Commenters noted synergy with district heating, noting 45°C is workable but low, and questioned the innovation's novelty, pointing to similar approaches like NASA's facility. Some asked about climate dependency and requested more details on efficiency in different conditions.

**Tags**: `#data-center`, `#liquid-cooling`, `#energy-efficiency`, `#sustainability`, `#ai-infrastructure`

---

<a id="item-20"></a>
## [Swiss Supreme Court Tests Abliterated Model Heretic for Legal Use](https://www.reddit.com/r/LocalLLaMA/comments/1ueeund/the_swiss_federal_supreme_court_is_evaluating/) ⭐️ 7.0/10

The Swiss Federal Supreme Court is evaluating the abliterated model Heretic to mitigate over-alignment, which causes LLMs to refuse legitimate legal queries, as reported in a new research paper. This marks a significant real-world application of abliteration in a judicial setting, highlighting practical needs to balance AI safety with utility and potentially influencing how courts adopt LLMs. The paper 'Measuring & Mitigating Over-Alignment for LLMs in Multilingual Criminal Law Courts' evaluates Heretic in Section 5.2, noting it minimizes refusals while retaining model capability through co-minimization of refusal count and KL divergence.

reddit · r/LocalLLaMA · /u/-p-e-w- · Jun 24, 14:19

**Background**: Abliteration is a technique that identifies and removes a 'refusal direction' from an LLM's neural activations, making it less prone to refuse prompts. Over-alignment occurs when safety training causes models to excessively refuse even harmless or legitimate requests, posing problems in domains like law where precise, uncensored responses are often required.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/blog/mlabonne/abliteration">Uncensor any LLM with abliteration</a></li>
<li><a href="https://github.com/p-e-w/heretic">GitHub - p-e-w/heretic: Fully automatic censorship removal ...</a></li>
<li><a href="https://docs.bswen.com/blog/2026-03-10-heretic-vs-abliterated-models/">Heretic vs Abliterated LLM Models: Key Differences Explained</a></li>

</ul>
</details>

**Tags**: `#abliteration`, `#LLM alignment`, `#legal AI`, `#over-alignment`, `#Swiss court`

---

<a id="item-21"></a>
## [Gefen Optimizer Offers 8x Memory Reduction as Drop-in AdamW Replacement](https://www.reddit.com/r/LocalLLaMA/comments/1uep96s/gefen_is_a_dropin_replacement_for_the_adamw/) ⭐️ 7.0/10

Gefen is a new stochastic optimizer that can directly replace AdamW in PyTorch training loops, achieving up to 8x memory savings in optimizer states. This development significantly lowers the memory barrier for training large models on consumer GPUs, potentially democratizing access to large-scale deep learning. Gefen shares second-moment estimates across parameter blocks and quantizes the first moment using a learned codebook, but it introduces slight modifications to the update rule.

reddit · r/LocalLLaMA · /u/indicava · Jun 24, 20:39

**Background**: AdamW is a widely used optimizer that maintains per-parameter first and second moment estimates, requiring two additional buffers per parameter. This overhead can dominate memory usage when training large neural networks, limiting batch sizes and model scale on hardware with limited VRAM.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2606.13894">[2606.13894] Gefen : Optimized Stochastic Optimizer</a></li>
<li><a href="https://pypi.org/project/gefen/">Gefen optimizer for memory-efficient PyTorch training</a></li>
<li><a href="https://nefut.com/article/996-csai-gefen-optimized-stochastic-optimizer-with-8x-memory-reduction">[CS.AI] Gefen : Optimized Stochastic Optimizer with 8x Mem... - Nefut</a></li>

</ul>
</details>

**Tags**: `#optimizer`, `#deep-learning`, `#memory-efficiency`, `#AdamW`, `#training`

---

<a id="item-22"></a>
## [Bank of Korea: AI Saves Time but Not Productivity](https://www.reddit.com/r/LocalLLaMA/comments/1uecytz/the_bank_of_korea_just_released_a_report_about_ai/) ⭐️ 7.0/10

The Bank of Korea's report finds that AI tools reduce workers' weekly workload by about 3.8% (roughly one hour), yet overall productivity does not increase because the saved time is consumed by writing more reports. This challenges the prevailing hype around AI-driven productivity gains with credible data from a central bank deeply connected to the AI supply chain, suggesting that task-level efficiency may not translate to bottom-line business profits. The report notes that AI accelerates report writing but leads to higher report volumes; even in a perfect scenario, maximum real productivity gain is just 1%.

reddit · r/LocalLLaMA · /u/UsedMorning9886 · Jun 24, 13:04

**Background**: The Bank of Korea is South Korea's central bank, a credible source. South Korea is a major exporter of AI-related semiconductors, giving its perspective unique weight. Productivity measures output per unit of input; the report implies AI simply shifts work rather than boosting net output.

**Tags**: `#AI`, `#productivity`, `#economics`, `#South Korea`, `#research`

---

<a id="item-23"></a>
## [AMD Strix Halo NPUs Now Usable for Hybrid LLM Inference](https://www.reddit.com/r/LocalLLaMA/comments/1uegdu0/big_news_for_amd_strix_halo_owners/) ⭐️ 7.0/10

AMD Strix Halo owners can now run LLMs in hybrid mode, using the NPU for fast prompt processing in parallel with the iGPU for token generation, thanks to improved ROCm support and tools like Lemonade. This unlocks previously underutilized hardware on Strix Halo APUs, significantly improving local LLM inference speed and efficiency for enthusiasts and developers running models on unified memory systems. The NPU excels at prompt processing (time-to-first-token), while the iGPU handles token generation; Lemonade server provides a bare-bones testbed, and future work aims to support multi-token prediction (MTP) hybrid models.

reddit · r/LocalLLaMA · /u/CSEliot · Jun 24, 15:16

**Background**: AMD Strix Halo (Ryzen AI Max+ 395) is a high-end APU with an NPU (Neural Processing Unit) and integrated GPU on a unified memory architecture. ROCm is AMD's open-source GPU software stack. Hybrid inference splits LLM workloads between NPU and iGPU to leverage each component's strengths.

<details><summary>References</summary>
<ul>
<li><a href="https://www.amd.com/en/blogs/2025/amd-ryzen-ai-max-395-processor-breakthrough-ai-.html">AMD Ryzen™ AI MAX+ 395 Processor: Breakthrough AI Performance ...</a></li>
<li><a href="https://www.amd.com/en/developer/resources/technical-articles/2025/hybrid-npu-igpu-optimized-agent-on-amd-ryzen-ai-powered-pc-.html">Hybrid NPU/iGPU Optimized Agent on AMD Ryzen AI Powered PC</a></li>
<li><a href="https://sleepingrobots.com/dreams/lemonade-server-npu-strix-halo/">Running LLMs on the AMD NPU with Lemonade Server</a></li>

</ul>
</details>

**Tags**: `#local-llm`, `#amd`, `#npu`, `#rocm`, `#hybrid-inference`

---

<a id="item-24"></a>
## [SDXL Runs Locally in Browser via WebGPU Extension](https://www.reddit.com/r/LocalLLaMA/comments/1uemzsb/sdxl_running_locally_in_the_browser_on_webgpu/) ⭐️ 7.0/10

A new browser extension loads SDXL models as ONNX graphs, running text encoders, UNet, and VAE on WebGPU to generate images entirely locally without complex setup. It supports SDXL-Lightning fp16 and a 4-bit quantized version, enabling offline use. This approach dramatically simplifies local AI image generation by avoiding Python environments and heavy desktop apps, making it accessible directly from the browser. It showcases the potential of WebGPU for running large models on consumer hardware with privacy. The extension uses ONNX Runtime for inference, requiring a WebGPU-capable browser like Chrome 122+ or the latest Firefox. Shader compilation causes freezes (~10s on load), and generation takes 50–60 seconds on an M4 MacBook; model sizes are ~7 GB (fp16) and ~3.6 GB (4-bit).

reddit · r/LocalLLaMA · /u/xoqq · Jun 24, 19:15

**Background**: WebGPU is a modern web standard giving browsers low-level GPU access for computation and graphics. ONNX is an open format for machine learning models, enabling portability across frameworks. SDXL is a high-resolution text-to-image model, and SDXL-Lightning is a distilled version that generates images in few steps, suitable for local deployment.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/WebGPU">WebGPU</a></li>
<li><a href="https://en.wikipedia.org/wiki/ONNX">ONNX</a></li>
<li><a href="https://huggingface.co/ByteDance/SDXL-Lightning">ByteDance/SDXL-Lightning · Hugging Face</a></li>

</ul>
</details>

**Tags**: `#SDXL`, `#WebGPU`, `#browser-extension`, `#image-generation`, `#ONNX`

---

<a id="item-25"></a>
## [GLM5.2 Inference Speedup from 2.5 to >50 tok/s via Weight Merging and vLLM Patching](https://www.reddit.com/r/LocalLLaMA/comments/1uedlas/i_did_some_model_hacks_and_got_glm52_from_about/) ⭐️ 7.0/10

By combining the MTP head from zai's GLM-5.2-FP8 repo with CyanKiwi's AWQ quantized version and applying a custom vLLM patch, inference speed on a GH200 system jumped from about 2.5 tok/s to a best case of 55 tok/s. This demonstrates a practical method to dramatically accelerate large model inference on local hardware, making advanced models more accessible without requiring high-end setups. It highlights the power of creative model surgery and community collaboration in the local LLM ecosystem. The approach involved grafting the MTP head from an FP8 model to an AWQ quantized version, then patching vLLM for compatibility. The system uses two H100 GPUs with 96 GB HBM3 each and 480 GB LPDDR5X per Grace CPU. Best-case throughput reached 55 tok/s at 4x concurrency, and single-stream streaming from RAM to VRAM achieved ~45 tok/s.

reddit · r/LocalLLaMA · /u/Reddactor · Jun 24, 13:30

**Background**: GLM5.2 is Z.ai's flagship large language model for coding and long-horizon tasks, supporting up to 1M tokens context. AWQ (Activation-aware Weight Quantization) is a low-bit weight compression technique that reduces memory footprint with minimal accuracy loss. FP8 is an 8-bit floating-point format for efficient model storage and computation. MTP (Multi-Token Prediction) heads allow the model to predict multiple future tokens per step, boosting throughput. vLLM is a high-throughput LLM serving system.

<details><summary>References</summary>
<ul>
<li><a href="https://www.datacamp.com/blog/glm-5-2">GLM-5.2: Features, Setup, Benchmarks, and Model Switching ...</a></li>
<li><a href="https://arxiv.org/abs/2306.00978">[2306.00978] AWQ: Activation-aware Weight Quantization for LLM Compression and Acceleration</a></li>
<li><a href="https://www.spheron.network/blog/multi-token-prediction-mtp-gpu-cloud-deployment-guide/">Multi-Token Prediction on GPU Cloud: Deploy MTP ... | Spheron Blog</a></li>

</ul>
</details>

**Tags**: `#local-llm`, `#model-optimization`, `#vLLM`, `#quantization`, `#inference-performance`

---

<a id="item-26"></a>
## [用生成式 AI 写作业或降低中国学生考试成绩](https://cepr.org/publications/dp21577) ⭐️ 7.0/10

A 30-month study of 26,811 Chinese students found that using generative AI for homework improved assignment scores but lowered exam scores, especially in social sciences and among younger, high-achieving, and male students.

telegram · zaihuapd · Jun 24, 05:15

**Tags**: `#education`, `#generative AI`, `#academic performance`, `#China`, `#longitudinal study`

---

<a id="item-27"></a>
## [ByteDance, Broadcom said to co-develop 5nm AI chip; ByteDance denies](https://t.me/zaihuapd/42153) ⭐️ 7.0/10

Unverified reports claim ByteDance is working with Broadcom on a 5nm AI processor to secure high-end chip supply, but ByteDance has publicly denied the rumor. The chip design is reportedly at an advanced stage but has not yet taped out. If true, the collaboration would mark a significant move by ByteDance to reduce dependence on Nvidia and Huawei's AI chips, potentially reshaping China's AI hardware landscape amid U.S. export controls. However, as a denied rumor, its impact remains uncertain. The processor would be fabricated on TSMC's 5nm process, but tape-out—the final design phase before manufacturing—has not yet occurred. ByteDance previously spent $2 billion on Nvidia GPUs and also purchased Huawei's Ascend 910B chips.

telegram · zaihuapd · Jun 24, 07:01

**Background**: Tape-out is the point in chip design when the final layout is sent to a foundry for production. A 5nm process node offers high performance and energy efficiency, crucial for AI workloads. Broadcom is a U.S.-based fabless semiconductor company known for custom ASIC designs. Chinese tech firms, facing U.S. export restrictions on advanced chips, have sought alternative suppliers like Huawei, whose Ascend 910B is fabricated on a 7nm-class process by SMIC.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Tape-out">Tape-out - Wikipedia</a></li>
<li><a href="https://www.tomshardware.com/tech-industry/artificial-intelligence/huaweis-homegrown-ai-chip-examined-chinese-fab-smic-produced-ascend-910b-is-massively-different-from-the-tsmc-produced-ascend-910">Huawei's homegrown AI chip examined — Chinese fab SMIC-produced Ascend 910B is massively different from the TSMC-produced Ascend 910 | Tom's Hardware</a></li>

</ul>
</details>

**Tags**: `#ByteDance`, `#Broadcom`, `#AI chips`, `#semiconductor`, `#rumor`

---

<a id="item-28"></a>
## [Micron Q3 Revenue Soars 346% to $414.6B on AI Demand](https://www.globenewswire.com/news-release/2026/06/24/3317151/14450/en/micron-technology-inc-reports-record-results-for-the-third-quarter-of-fiscal-2026.html) ⭐️ 7.0/10

Micron Technology reported record Q3 FY2026 revenue of $414.6 billion, a 346% year-over-year increase, and net income of $282.4 billion, driven by strong AI data center demand. The company has begun mass production of HBM4 memory and expects HBM4E to enter production in 2027. The explosive growth underscores the critical role of high-bandwidth memory in AI infrastructure and signals a sustained shortage that could impact technology costs and availability across industries. Non-GAAP gross margin reached 84.9%, and operating margin 81.2%. Micron has secured 16 long-term agreements locking in orders for the next 3-5 years, and expects memory shortages to persist beyond 2027.

telegram · zaihuapd · Jun 24, 22:22

**Background**: High Bandwidth Memory (HBM) is a specialized type of DRAM designed for AI accelerators and data center GPUs, offering much higher data transfer rates than conventional memory. HBM4 is the latest generation, with speeds exceeding 2.8 TB/s per stack, and HBM4E is an upcoming enhanced version expected to double bandwidth. Micron is one of the three major HBM suppliers alongside SK Hynix and Samsung.

<details><summary>References</summary>
<ul>
<li><a href="https://www.micron.com/products/memory/hbm/hbm4">HBM4 | Micron Technology Inc.</a></li>
<li><a href="https://en.wikipedia.org/wiki/HBM_memory_shortage">HBM memory shortage</a></li>

</ul>
</details>

**Tags**: `#semiconductors`, `#AI hardware`, `#earnings`, `#memory`, `#Micron`

---

<a id="item-29"></a>
## [Google Play Expands External Billing to US, UK, Europe](https://android-developers.googleblog.com/2026/06/play-expanded-billing.html) ⭐️ 7.0/10

Starting June 30, 2026, Google Play will allow developers in the US, UK, and EEA to offer third-party in-app billing or external payment links, with a new service fee structure that separates billing costs. This policy shift responds to regulatory demands like the EU's Digital Markets Act and gives developers more payment flexibility, potentially lowering costs and fostering competition in the mobile app ecosystem. Service fees are 10% for the first $1M annual revenue and auto-renewing subscriptions; using Google Play Billing incurs an additional 5% settlement fee, while alternative billing methods avoid it. Developers in the Level Up or Apps Experience programs get further reduced rates from September.

telegram · zaihuapd · Jun 25, 02:33

**Background**: Google Play previously required all in-app digital purchases to use its own billing system, charging a standard service fee. Regulatory scrutiny, particularly in the EU, has pushed app stores to allow alternative billing. The new structure unbundles the service fee from billing charges, and programs like Level Up and Apps Experience offer further incentives for high-quality apps.

<details><summary>References</summary>
<ul>
<li><a href="https://play.google.com/console/about/levelup/">Google Play Games Level Up | Google Play Console</a></li>
<li><a href="https://developer.android.com/distribute/aep">Apps Experience Program | Android Developers</a></li>
<li><a href="https://support.google.com/googleplay/android-developer/answer/16954621?hl=en">Understanding Google Play's lower service fees</a></li>

</ul>
</details>

**Tags**: `#Google Play`, `#mobile app development`, `#in-app billing`, `#app store policy`, `#digital markets`

---