---
layout: default
title: "Horizon Summary: 2026-06-21 (EN)"
date: 2026-06-21
lang: en
---

> From 61 items, 21 important content pieces were selected

---

1. [Light-driven 3D fiber-optic micro-tweezers 100,000x stronger than optical tweezers](#item-1) ⭐️ 9.0/10
2. [Loupe Exposes Data Native iOS Apps Can Access](#item-2) ⭐️ 8.0/10
3. [SMPTE Opens Its Standards Library for Free](#item-3) ⭐️ 8.0/10
4. [Linux kernel removes error-prone strncpy after six years](#item-4) ⭐️ 8.0/10
5. [StartupWiki: A Free Wikipedia-Like Startup Database](#item-5) ⭐️ 8.0/10
6. [Cloudflare launches temporary accounts and 60-minute ephemeral Workers deployments](#item-6) ⭐️ 8.0/10
7. [South Korea's Defense Boom: Cheaper Arms Shake Global Market](#item-7) ⭐️ 8.0/10
8. [Bun PR Adds Shared-Memory Threads to JavaScriptCore](#item-8) ⭐️ 8.0/10
9. [Banning Open Source AI Would Be A Mistake](#item-9) ⭐️ 8.0/10
10. [Unauthorized 'Extreme Alert' with 'Misanthropy' Hits Brazil](#item-10) ⭐️ 7.0/10
11. [F-15 Strike Eagle II Reversing Project Seeks DOS Testers](#item-11) ⭐️ 7.0/10
12. [Webflow Partner Plagiarizes The Dictionary of Obscure Sorrows](#item-12) ⭐️ 7.0/10
13. [Tesco Sues VMware for Breach of Contract Over Licensing](#item-13) ⭐️ 7.0/10
14. [GLM-5.2 Passes Vibe Check, Z.ai Predicts Open Fable by December](#item-14) ⭐️ 7.0/10
15. [SCAIL 2 Workflow Cuts 720p Video Generation from 3 Hours to 40 Minutes](#item-15) ⭐️ 7.0/10
16. [LTX Director 2.0: Free Open-Source AI Video Editor Overhauled for ComfyUI](#item-16) ⭐️ 7.0/10
17. [Desktop App for Ideogram 4 Storyboarding with Drag-and-Drop JSON Editing](#item-17) ⭐️ 7.0/10
18. [IETF Proposes HTTP QUERY Method for Safe Queries with Request Body](#item-18) ⭐️ 7.0/10
19. [LM Studio Demos 1T Kimi K2.6 on Four Mac Studios at WWDC](#item-19) ⭐️ 7.0/10
20. [UK to require social platforms to boost public service news](#item-20) ⭐️ 7.0/10
21. [Tencent to Launch AI Agent in WeChat, Approval This Month](#item-21) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Light-driven 3D fiber-optic micro-tweezers 100,000x stronger than optical tweezers](https://www.stdaily.com/web/gdxw/2026-06/19/content_534836.html) ⭐️ 9.0/10

Researchers from Anhui University and the University of Science and Technology of China have developed a novel 3D fiber-optic micro-tweezers, published in Nature, that uses femtosecond laser manufacturing to integrate photothermal conversion on a fiber tip, achieving forces over 100,000 times greater than traditional optical tweezers. This breakthrough overcomes the force and opacity limitations of optical tweezers and the precision constraints of mechanical grippers, enabling strong, programmable, and low-damage micromanipulation in confined spaces, which could transform single-cell analysis and minimally invasive medicine. The device is fabricated on a commercial fiber end via femtosecond laser composite processing, combining light delivery, photothermal conversion, material deformation, and mechanical output. Force is continuously adjustable by input power, and it can precisely manipulate single cells within spaces of hundreds of microns.

telegram · zaihuapd · Jun 20, 15:19

**Background**: Traditional optical tweezers use a highly focused laser beam to trap transparent micro-particles via gradient forces, but forces are typically in the picoNewton range. Femtosecond laser micromachining uses ultrashort pulses to create precise 3D microstructures with minimal thermal damage. This new tweezers employs photothermal conversion: absorbed light heats the structure, causing thermal expansion and mechanical motion, which generates much larger forces and enables manipulation of opaque objects.

<details><summary>References</summary>
<ul>
<li><a href="https://zh.wikipedia.org/wiki/光鑷">光鑷 - 维基百科，自由的百科全书</a></li>
<li><a href="https://zhuanlan.zhihu.com/p/2020636609284940423">光镊技术：原理、系统、应用与前沿检测方法 - 知乎</a></li>
<li><a href="https://www.researching.cn/ArticlePdf/m00001/2013/40/2/0201001.pdf">researching.cn/ArticlePdf/m00001/2013/40/2/0201001.pdf</a></li>

</ul>
</details>

**Tags**: `#optical tweezers`, `#fiber optics`, `#micromanipulation`, `#biomedical engineering`, `#Nature`

---

<a id="item-2"></a>
## [Loupe Exposes Data Native iOS Apps Can Access](https://github.com/mysk-research/loupe) ⭐️ 8.0/10

The security research team Mysk released Loupe, an iOS app that lets users see the extensive device information accessible to any native app via public APIs, including device setup time and installed app details. This highlights the privacy risks of device fingerprinting on iOS, showing how easily apps can collect unique identifiers to track users, potentially pushing Apple to tighten data access controls. Loupe reads values from public iOS APIs, such as the exact second of device setup or last erase, volume creation date, pasteboard change count, and a probe to detect installed apps without user consent. All data is accessible to any app on iOS without special permissions.

hackernews · Cider9986 · Jun 20, 12:08 · [Discussion](https://news.ycombinator.com/item?id=48608645)

**Background**: Device fingerprinting involves collecting device-specific information to uniquely identify a user. iOS apps run in a sandbox that restricts access to system resources, but certain system APIs are open to all apps for legitimate functionality. However, data like setup timestamps and volume metadata can be combined to create a persistent fingerprint, even after app deletion. This tool exposes that surface to raise awareness.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/mysk-research/loupe">GitHub - mysk-research/loupe: A privacy-focused iOS app that raises awareness about what native apps can see · GitHub</a></li>
<li><a href="https://apps.apple.com/us/app/loupe-what-apps-can-see/id6766152470">Loupe: What Apps Can See App - App Store</a></li>

</ul>
</details>

**Discussion**: Comments express alarm over specific data points like the setup timestamp and installed apps probe, comparing iOS favorably to Android but still demanding better privacy. Users suggest Apple should randomize such identifiers, with some avoiding apps altogether due to trust issues.

**Tags**: `#privacy`, `#iOS`, `#security`, `#mobile-apps`, `#tool`

---

<a id="item-3"></a>
## [SMPTE Opens Its Standards Library for Free](https://www.smpte.org/blog/smpte-makes-its-standards-freely-accessible-openingstandards-library-to-the-global-media-technology-community) ⭐️ 8.0/10

SMPTE has made its library of over 800 technical standards freely accessible to the public, shifting from paid access. The move includes modernizing development with GitHub workflows, issue tracking, and HTML-based authoring. Removing cost barriers encourages global innovation and adoption of open media standards, aligning with industry trends. This can accelerate development in media production and distribution globally. Modernization efforts include adopting GitHub for version control and issue tracking, transitioning to structured HTML authoring, and implementing an integrated publishing pipeline for streamlined document release.

hackernews · zdw · Jun 20, 17:01 · [Discussion](https://news.ycombinator.com/item?id=48610827)

**Background**: SMPTE, founded in 1916, is an internationally recognized standards body for media and entertainment, having published over 800 standards for film, digital cinema, audio, and television. Previously, many standards were only available for purchase.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/SMPTE">SMPTE</a></li>
<li><a href="https://www.smpte.org/standards/overview">Standards Overview | Society of Motion Picture & Television ...</a></li>

</ul>
</details>

**Discussion**: Community sentiment is overwhelmingly positive, celebrating truly open standards. Users recall past purchases and stress that standards organizations should default to open access, citing IETF's success. One comment highlights the technical modernization with GitHub workflows.

**Tags**: `#open-standards`, `#media-technology`, `#SMPTE`, `#standards`, `#video`

---

<a id="item-4"></a>
## [Linux kernel removes error-prone strncpy after six years](https://www.phoronix.com/news/Linux-7.2-Drops-strncpy) ⭐️ 8.0/10

The Linux kernel has finally eliminated the strncpy function, a long-standing source of bugs, after a six-year effort involving 360 patches. The removal was completed in kernel 7.2, as seen in commit 1a3746ccbb0a97bed3c06ccde6b880013b1dddc1. This removal marks a major milestone in kernel security and reliability, as strncpy's counter-intuitive null-termination behavior and performance issues have caused persistent bugs. It reflects the kernel community's commitment to eliminating known error-prone interfaces. The process spanned six years and required 360 patches, with contributions from many developers. The commit explicitly notes that strncpy was a persistent source of bugs due to its confusing semantics and redundant zero-filling.

hackernews · simonpure · Jun 20, 20:59 · [Discussion](https://news.ycombinator.com/item?id=48612943)

**Background**: strncpy is a C standard library function that copies a fixed number of characters from source to destination. Unlike strcpy, it does not guarantee null-termination if the source is longer than the specified limit, leading to buffer overflows and other security vulnerabilities when programmers misunderstand its behavior. The Linux kernel has been moving away from such unsafe functions to improve overall code safety.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Strncpy">Strncpy</a></li>

</ul>
</details>

**Discussion**: Commenters praised the removal as a critical, albeit unglamorous, engineering effort, with one noting that it's 'where the real work of systems engineering is done.' Some pointed out that C-style null-terminated strings are inherently flawed and suggested using length-prefixed strings like Pascal-style or C++ std::string as safer alternatives.

**Tags**: `#linux`, `#kernel`, `#c-programming`, `#security`, `#string-handling`

---

<a id="item-5"></a>
## [StartupWiki: A Free Wikipedia-Like Startup Database](https://startupwiki.tech/) ⭐️ 8.0/10

A developer has launched StartupWiki, a free, ad-free startup database that mimics Wikipedia's open model—no accounts, no subscriptions—currently featuring startup profiles, search, filtering, and a public API under development. It targets the common frustration with paywalled startup databases like Crunchbase, potentially democratizing access to early-stage company information for investors, founders, and researchers. The project is in early stages with limited coverage—one commenter found 0 of 10 searched startups—and data is user-contributed, so accuracy is not guaranteed; a public API is in progress.

hackernews · shpran · Jun 20, 15:59 · [Discussion](https://news.ycombinator.com/item?id=48610224)

**Background**: Crunchbase is a leading startup database but requires expensive subscriptions for detailed access. Wikipedia is a free, community-edited encyclopedia. StartupWiki applies the Wikipedia model to startup data, aiming for open, uncluttered access. Previous open database attempts like OpenCorporates focus on registered companies, not early-stage startups.

**Discussion**: Commenters provided constructive feedback: scrape investor portfolios to fill data, add founder university affiliation, clarify verified badge sources, enable OAuth via OpenRouter, and use a startup.txt file for self-reporting. Overall sentiment is supportive but cautious about coverage and data quality.

**Tags**: `#startups`, `#database`, `#web-app`, `#free`, `#alternative`

---

<a id="item-6"></a>
## [Cloudflare launches temporary accounts and 60-minute ephemeral Workers deployments](https://blog.cloudflare.com/temporary-accounts/) ⭐️ 8.0/10

Cloudflare has introduced temporary accounts and a `--temporary` flag for the Wrangler CLI, allowing anyone to deploy a Worker for free for 60 minutes. The deployment can be claimed to make the account permanent, or it expires automatically. This enables frictionless ephemeral deployments for pull request previews, code review, and AI agent integration, dramatically lowering the barrier to experimenting with serverless functions. It could reshape development workflows by making instant, temporary staging environments universally accessible. Deployments are limited to 60 minutes with abuse prevention like rate limiting on account creation. Notably, Cloudflare still does not offer hard billing caps for paid plans, a feature frequently requested by the community to avoid unexpected charges.

hackernews · farhadhf · Jun 20, 11:19 · [Discussion](https://news.ycombinator.com/item?id=48608394)

**Background**: Cloudflare Workers is a serverless platform that runs code on Cloudflare's edge network, with a free tier capped at 100,000 requests per day. Ephemeral environments are short-lived deployments spun up on demand and destroyed after use, commonly employed in CI/CD pipelines for testing and previews. The new temporary accounts remove the need for upfront registration, enabling rapid, disposable Workers for AI agents and developers alike.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cloudflare.com/products/workers/">Cloudflare Workers - Global Serverless Functions Platform</a></li>
<li><a href="https://developers.cloudflare.com/workers/">Overview · Cloudflare Workers docs</a></li>
<li><a href="https://northflank.com/blog/what-are-ephemeral-environments">What are ephemeral environments? How they work and when to ...</a></li>

</ul>
</details>

**Discussion**: The community is excited about ephemeral deployments for PR previews and code review, but emphasizes the missing hard billing caps as a critical missing feature. Concerns about abuse for malicious hosting and criticism of AI-generated marketing copy also surfaced.

**Tags**: `#cloudflare`, `#workers`, `#serverless`, `#ephemeral deployments`, `#AI agents`

---

<a id="item-7"></a>
## [South Korea's Defense Boom: Cheaper Arms Shake Global Market](https://www.politico.com/news/magazine/2026/06/20/south-korea-weapons-dealer-trump-00959559) ⭐️ 8.0/10

South Korea's defense industry is rapidly expanding, securing major international deals such as a potential $60 billion submarine contract with Canada and large-scale arms agreements with Poland, undercutting Western competitors on price while delivering advanced systems. This expansion challenges the dominance of US and European defense manufacturers, offering more affordable options to allied nations and potentially reconfiguring global arms supply chains and geopolitical alliances. Key platforms include the K9 Thunder self-propelled howitzer, costing half as much as US equivalents; the K239 Chunmoo MLRS; and the KF-21 Boramae fighter jet. South Korea’s Hanwha Ocean is competing for Canada’s largest-ever military procurement, a $60 billion submarine deal.

hackernews · JumpCrisscross · Jun 20, 11:44 · [Discussion](https://news.ycombinator.com/item?id=48608515)

**Background**: South Korea has developed a strong domestic defense industry in response to persistent threats from North Korea. Traditionally, the global arms market has been led by the United States, Russia, and European nations. However, the war in Ukraine and rising security concerns have accelerated demand, allowing South Korea to leverage its advanced manufacturing and lower labor costs to become a major arms exporter.

**Discussion**: Commenters overwhelmingly attribute South Korea’s arms success to its significant cost advantage, with systems 40-60% cheaper than Western equivalents. The potential Canadian submarine deal and Poland’s fast-track procurement are cited as evidence of this competitive edge, though some note risks like corruption and the need for political alignment.

**Tags**: `#defense-industry`, `#south-korea`, `#geopolitics`, `#military-tech`, `#economics`

---

<a id="item-8"></a>
## [Bun PR Adds Shared-Memory Threads to JavaScriptCore](https://github.com/oven-sh/WebKit/pull/249) ⭐️ 8.0/10

An open pull request on Bun's WebKit fork proposes implementing shared-memory threads in JavaScriptCore, enabling true object sharing across threads. The change, partly AI-generated, is based on a design from the WebKit blog. If merged, it could bring native shared-memory multithreading to JavaScript, potentially improving performance for compute-intensive tasks and influencing future language design. The PR spans around 1800 files and is based on the 'Concurrent JavaScript: It can work!' proposal. Concerns have been raised about the AI-generated nature of the code and its suitability for complex threading logic.

hackernews · gr4vityWall · Jun 20, 17:02 · [Discussion](https://news.ycombinator.com/item?id=48610841)

**Background**: Bun is a JavaScript runtime built on WebKit's JavaScriptCore engine, unlike Node.js which uses V8. JavaScript traditionally lacks shared-memory threads; concurrency is handled via message-passing Web Workers. Shared memory, where threads access the same data, could unlock new performance patterns.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Bun_(software)">Bun (software) - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/JavaScriptCore">JavaScriptCore</a></li>

</ul>
</details>

**Discussion**: Discussion is mixed, with many voicing distrust due to the PR's AI-generated nature and large size. Critics stress that runtime code must be 'obviously no bugs', not just 'no obvious bugs'. Supporters point to the soundness of the underlying WebKit design.

**Tags**: `#javascript`, `#webkit`, `#concurrency`, `#bun`, `#shared-memory-threads`

---

<a id="item-9"></a>
## [Banning Open Source AI Would Be A Mistake](https://www.interconnects.ai/p/banning-open-source-ai-would-be-a) ⭐️ 8.0/10

An op-ed titled 'Banning Open Source AI Would Be A Mistake' co-authored by Kevin Xu and published on Interconnected argues against prohibiting open-source AI models. As governments debate AI regulation, this article counters the narrative that open-source AI poses unacceptable dangers, stressing the value of transparency and innovation. The piece is aimed at a non-technical audience and presents arguments that a ban would harm both AI progress and safety. It is co-authored by recognized experts in the field.

rss · Interconnects · Jun 19, 13:02

**Background**: Open-source AI makes model code, weights, and architecture publicly accessible, enabling community collaboration and review. Some policymakers have recently proposed bans or strict limits on open-source AI due to misuse risks, while supporters argue openness accelerates safety research and democratizes technology.

**Tags**: `#Open Source AI`, `#AI Policy`, `#Regulation`, `#Op-ed`, `#Artificial Intelligence`

---

<a id="item-10"></a>
## [Unauthorized 'Extreme Alert' with 'Misanthropy' Hits Brazil](https://www.cnn.com/2026/06/20/americas/brazil-hackers-unauthorized-alert-latam) ⭐️ 7.0/10

On June 20, 2026, an unauthorized 'Extreme Alert' message containing the word 'misanthropy' was broadcast to cell phones across Brazil. The incident exposed vulnerabilities in the country's Cell Broadcast-based public warning system. This breach shows that even critical public safety infrastructure can be compromised, potentially undermining trust in emergency alerts at a time when nations are expanding their use of Cell Broadcast for disasters. It highlights the need for stronger authentication and security measures to prevent malicious spoofing of alerts that could cause widespread panic. The message was sent as an 'Extreme Alert'—the highest severity level—and the word 'misanthropy' (hatred of humanity) suggests a deliberate hack rather than an error. Researchers have previously demonstrated that LTE vulnerabilities allow spoofing of presidential alerts via fake base stations, a likely vector here.

hackernews · zdw · Jun 20, 20:05 · [Discussion](https://news.ycombinator.com/item?id=48612502)

**Background**: Cell Broadcast is a technology that sends short messages to all mobile devices within a geographic area, widely used for public warnings like severe weather or child abductions. Unlike SMS, it does not need phone numbers and triggers a distinct alert tone. Brazil operates a Cell Broadcast-based emergency system, which should only allow authorized authorities to issue alerts.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Cell_Broadcast">Cell Broadcast - Wikipedia</a></li>
<li><a href="https://www.techworm.net/2019/06/presidential-alerts-spoofed.html">Presidential emergency alerts can be easily spoofed using LTE flaws</a></li>
<li><a href="https://arxiv.org/html/2604.24404v1">From Spoofing to Trust: Emergency Alerts Spoofing Testbed and...</a></li>

</ul>
</details>

**Discussion**: Commenters expressed frustration with alert systems, citing frequent false alarms that lead to desensitization, and noted the misuse of the term 'hacker' in media. They referenced past incidents like the 2018 Hawaii false missile alert and highlighted how easy caller ID spoofing enables social engineering, showing a mix of skepticism and technical awareness.

**Tags**: `#security-incident`, `#cellular-alerts`, `#emergency-systems`, `#Brazil`, `#hacker`

---

<a id="item-11"></a>
## [F-15 Strike Eagle II Reversing Project Seeks DOS Testers](https://neuviemeporte.github.io/f15-se2/2026/06/20/needyou.html) ⭐️ 7.0/10

A project to reverse-engineer the 1989 DOS game F-15 Strike Eagle II is converting its assembler code into byte-identical C and is seeking testers to run the DOS version before porting to modern systems. This meticulous decompilation from assembler to identical C advances game preservation, enables native ports, and allows community fixes while serving as a technical case study. The conversion targets a byte-for-byte match on DOS using the original game files (version 451.03); porting to Linux and Windows will only begin after every assembler fragment is replaced.

hackernews · LowLevelMahn · Jun 20, 15:10 · [Discussion](https://news.ycombinator.com/item?id=48609766)

**Background**: Assembly language is a low-level, CPU-specific human-readable form of machine code. Decompilation is the process of translating an executable back into source code, but it often yields code that is not identical to the original. Reverse engineering is the practice of analyzing a system to understand its design. F-15 Strike Eagle II is a classic flight simulator released by MicroProse for DOS in 1989.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Assembly_language">Assembly language</a></li>
<li><a href="https://en.wikipedia.org/wiki/Decompilation">Decompilation</a></li>
<li><a href="https://en.wikipedia.org/wiki/Reverse_engineering">Reverse engineering</a></li>

</ul>
</details>

**Discussion**: Comments range from childhood nostalgia to technical curiosity. Some question the need for decompilation when DOSBox emulates the game, but others note that native ports are far easier. There is also interest in whether AI can help understand decompiled code without original symbol names.

**Tags**: `#reverse-engineering`, `#dos`, `#decompilation`, `#game-preservation`, `#assembler`

---

<a id="item-12"></a>
## [Webflow Partner Plagiarizes The Dictionary of Obscure Sorrows](https://waxy.org/2026/06/the-wholesale-plagiarism-of-obscure-sorrows/) ⭐️ 7.0/10

A Webflow premium partner, Qontour, has been found to have wholesale copied the text of John Koenig's 'The Dictionary of Obscure Sorrows' onto a bootleg site, including verbatim foreword and all 311 neologisms, and monetized via Amazon affiliate links. This case underscores the difficulties creators face in protecting their work from online plagiarism, especially when platforms are unresponsive to DMCA requests without court orders, and it exemplifies how AI tools are being used to rebrand stolen content. The bootleg site monetized through Amazon Associates with the tag 'promptdigital-20', linking to the authentic book on Amazon; meanwhile, a victim of similar theft noted that Google and Apple are ineffective for DMCA without a court order.

hackernews · ridesisapis · Jun 20, 18:05 · [Discussion](https://news.ycombinator.com/item?id=48611411)

**Background**: Webflow is a visual web design platform that allows users to build websites. Its partner program includes agencies and freelancers who create sites for clients. The DMCA (Digital Millennium Copyright Act) enables copyright owners to issue takedown notices to online service providers, but enforcement can be slow without legal action. Amazon Associates is an affiliate program that lets websites earn referral fees by linking to Amazon products.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Webflow">Webflow</a></li>

</ul>
</details>

**Discussion**: Commenters widely condemn the plagiarism, noting that DMCA takedowns are the appropriate remedy but expressing frustration that platforms often require court orders to act. Some point out the affiliate monetization angle, while others share similar experiences of theft. There is debate on whether AI generated the content or simply reproduced it, with suspicions that the text was manually copied.

**Tags**: `#plagiarism`, `#intellectual-property`, `#copyright`, `#AI`, `#DMCA`

---

<a id="item-13"></a>
## [Tesco Sues VMware for Breach of Contract Over Licensing](https://www.theregister.com/software/2025/09/03/supermarket-giant-tesco-sues-vmware-for-breach-of-contract/1420651) ⭐️ 7.0/10

British supermarket giant Tesco filed a lawsuit against VMware for breach of contract in 2025, directly challenging the company over changes to licensing terms after its acquisition by Broadcom. This legal action is a clear signal of enterprise backlash against Broadcom's licensing strategies, and if successful, could set a precedent for other large organizations facing massive cost increases. The suit follows Broadcom's termination of perpetual licenses, shift to subscription-only models, and transition from per-socket to per-core pricing, which particularly penalizes large-scale deployments.

hackernews · wglb · Jun 20, 21:09 · [Discussion](https://news.ycombinator.com/item?id=48613008)

**Background**: After acquiring VMware in 2023, Broadcom aggressively changed licensing to boost recurring revenue, eliminating perpetual licenses and bundling products into fewer, more expensive SKUs. The move to per-core licensing multiplied costs for organizations with high-core-count servers, causing widespread dissatisfaction and migration to alternatives like Nutanix or Proxmox.

<details><summary>References</summary>
<ul>
<li><a href="https://www.nutanix.com/blog/i-made-9-bold-broadcom-predictions-one-year-ago">I Made 9 Bold Broadcom Predictions One Year Ago</a></li>
<li><a href="https://www.linkedin.com/posts/jimschoenle_vmware-broadcom-infrastructurestrategy-activity-7453091566862151680-c8AG">VMware Pricing and Licensing Challenges with Broadcom Acquisition</a></li>
<li><a href="https://www.marcumllp.com/insights/broadcom-acquisition-how-vmware-users-are-taking-a-hit">Broadcom Acquisition : How VMware Users are Taking a Hit</a></li>

</ul>
</details>

**Discussion**: Commenters largely see the lawsuit as a negotiating tactic, with some comparing Broadcom's rent-seeking to the late CA Technologies. Others argue Broadcom is deliberately making on-premise hosting costlier to accelerate cloud adoption, while conceding that VMware's long-term reputation is severely damaged as customers plan exits.

**Tags**: `#VMware`, `#Broadcom`, `#licensing`, `#lawsuit`, `#enterprise-IT`

---

<a id="item-14"></a>
## [GLM-5.2 Passes Vibe Check, Z.ai Predicts Open Fable by December](https://www.latent.space/p/ainews-glm-gpt-glm-52-passes-vibe) ⭐️ 7.0/10

GLM-5.2, a coding-first model with a 1M-token context window launched on June 13, 2026 by Z.ai, is now widely recognized as competitive with GPT models in informal evaluations. Z.ai also forecasts that an open-source implementation of FABLE, called Open Fable, will be available by December 2026. This development signals a narrowing gap between open-source and proprietary models, potentially accelerating innovation and accessibility in AI. It also indicates that Chinese AI firm Z.ai is emerging as a serious competitor to Western labs. GLM-5.2 excels in agentic, repository-scale software engineering tasks and is free, supporting Windows, macOS, and Linux. The Open Fable project appears to be an open-source retrieval engine based on forest-based dual-path LLM-enhanced retrieval, distinct from Anthropic's recently shut-down Claude Fable.

rss · Latent Space · Jun 19, 05:53

**Background**: Z.ai, formerly known as Zhipu AI, is a Chinese AI company developing the GLM series of language models. The term "vibe check" refers to informal, subjective evaluations by users to gauge model performance. FABLE stands for Forest-Based Adaptive Bi-Path LLM-Enhanced Retrieval, a technique for efficient document retrieval. Anthropic's Claude Fable 5, a powerful analytics model, was abruptly shut down in June 2026, spurring interest in open alternatives.

<details><summary>References</summary>
<ul>
<li><a href="https://techsy.io/en/blog/glm-5-2">GLM 5 . 2 Review 2026: 1M-Context Coding Model Explained</a></li>
<li><a href="https://en.wikipedia.org/wiki/Z.ai">Z.ai - Wikipedia</a></li>
<li><a href="https://github.com/alainbrown/openfable">GitHub - alainbrown/openfable: An open-source retrieval ...</a></li>

</ul>
</details>

**Tags**: `#open-source`, `#language models`, `#GLM-5.2`, `#AI benchmarks`, `#GPT competitor`

---

<a id="item-15"></a>
## [SCAIL 2 Workflow Cuts 720p Video Generation from 3 Hours to 40 Minutes](https://www.reddit.com/r/StableDiffusion/comments/1ubagta/yes_this_was_generated_by_scail_2_rtx_5060ti_16gb/) ⭐️ 7.0/10

The new SCAIL 2 workflow for Stable Diffusion reduces the time to generate a 10-second 720p video clip from 3 hours to 40 minutes using an RTX 5060TI 16GB GPU and 48GB system RAM. This breakthrough makes high-quality AI video generation feasible on consumer hardware, lowering the entry barrier for creators and potentially accelerating adoption of AI in video production. The workflow is based on SCAIL-2 Infinity, a single ComfyUI node designed for unlimited-length video generation, and may also run on a 12GB VRAM GPU with at least 48GB system RAM, though performance may vary.

reddit · r/StableDiffusion · /u/TightKnowledge8 · Jun 20, 23:17

**Background**: Stable Diffusion is a widely used open-source image generation model. SCAIL-2 is a workflow built on top of it, specifically for character animation and video generation, enabling consistent motion transfer and long video sequences through a node-based interface in ComfyUI.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/zai-org/SCAIL-2">GitHub - zai-org/SCAIL-2: Official Implementation of SCAIL-2 ...</a></li>
<li><a href="https://huggingface.co/Comfy-Org/SCAIL-2/discussions/1">Comfy-Org/SCAIL-2 · Comfyui workflow - Hugging Face</a></li>

</ul>
</details>

**Tags**: `#stable-diffusion`, `#video-generation`, `#workflow`, `#optimization`, `#AI-art`

---

<a id="item-16"></a>
## [LTX Director 2.0: Free Open-Source AI Video Editor Overhauled for ComfyUI](https://www.reddit.com/r/StableDiffusion/comments/1ub4jpk/ltx_director_20_update_a_free_open_source/) ⭐️ 7.0/10

LTX Director 2.0 has been released as a complete overhaul, adding full AI video editing capabilities inside ComfyUI, including IC-LoRA support, audio inpainting, retake mode, timeline saving/loading, and numerous UI improvements. This update significantly enhances open-source AI video creation by providing an integrated, node-based editing workflow that was previously missing, potentially lowering the barrier for creators and accelerating innovation in AI video generation. IC-LoRA leverages in-context learning by concatenating condition and target images into a composite image with task-specific LoRA tuning; audio inpainting allows blending imported and generated audio seamlessly; Retake Mode is an experimental beta feature for regenerating selected video segments.

reddit · r/StableDiffusion · /u/WhatDreamsCost · Jun 20, 19:00

**Background**: ComfyUI is a modular, node-based GUI for creating AI image and video workflows using diffusion models. IC-LoRA (In-Context LoRA) allows AI models to understand visual tasks from concatenated example images, enabling style transfer and subject consistency with minimal training. Audio inpainting reconstructs missing or corrupted audio segments by analyzing the surrounding sound, ensuring seamless blending. LTX Director 2.0 integrates these technologies into a single, user-friendly tool for ComfyUI.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ComfyUI">ComfyUI</a></li>
<li><a href="https://github.com/ali-vilab/In-Context-LoRA">GitHub - ali-vilab/In-Context-LoRA: Official repository of In-Context LoRA for Diffusion Transformers · GitHub</a></li>
<li><a href="https://en.wikipedia.org/wiki/Audio_inpainting">Audio inpainting</a></li>

</ul>
</details>

**Tags**: `#AI video generation`, `#open-source`, `#ComfyUI`, `#video editing`, `#machine learning`

---

<a id="item-17"></a>
## [Desktop App for Ideogram 4 Storyboarding with Drag-and-Drop JSON Editing](https://www.reddit.com/r/StableDiffusion/comments/1ubd5pa/ideogram_tutorial/) ⭐️ 7.0/10

A new open-source desktop application, ai-storyboard, allows users to visually build storyboards for Ideogram 4 by drawing and dragging bounding boxes to structure JSON prompts, and integrates LLMs to generate image sequences via ComfyUI. This tool simplifies the complex process of crafting structured prompts for Ideogram 4's precise image composition, making advanced AI storyboarding accessible to creators without manual coding, and can accelerate collaborative design workflows. The MIT-licensed tool runs locally, requires a user-provided ComfyUI instance and an OpenAI-compatible LLM endpoint; it exports storyboards as ZIP or PDF, and falls back to plain prompts for non-Ideogram models.

reddit · r/StableDiffusion · /u/FineClassroom2085 · Jun 21, 01:29

**Background**: Ideogram 4 is an open-weight image model that uses structured JSON prompts to control object placement and text via bounding boxes. ComfyUI is a popular node-based interface for running diffusion models. The app leverages these to allow drag-and-drop visual editing of the JSON, with LLMs assisting in narrative generation.

<details><summary>References</summary>
<ul>
<li><a href="https://ideogram.ai/models/4.0/">Ideogram 4.0 | Ideogram</a></li>
<li><a href="https://en.wikipedia.org/wiki/ComfyUI">ComfyUI</a></li>
<li><a href="https://github.com/ideogram-oss/ideogram4">GitHub - ideogram-oss/ideogram4: Ideogram 4: Open image model ...</a></li>

</ul>
</details>

**Tags**: `#Stable Diffusion`, `#Ideogram`, `#ComfyUI`, `#LLM`, `#storyboard`

---

<a id="item-18"></a>
## [IETF Proposes HTTP QUERY Method for Safe Queries with Request Body](https://httpwg.org/http-extensions/draft-ietf-httpbis-safe-method-w-body.html) ⭐️ 7.0/10

The IETF HTTP Working Group is drafting a new QUERY method that allows sending query parameters in the request body, similar to POST, but with safe and idempotent semantics like GET, enabling caching, retries, and automatic recovery. This addresses the limitation of URI length in GET requests and provides a standardized, cache-friendly way to perform complex queries, potentially improving API design, reducing server load, and enhancing user experience in web applications. The draft defines QUERY as safe and idempotent, and introduces the Accept-Query response header to allow servers to declare supported query media types. The current draft expires in December 2026.

telegram · zaihuapd · Jun 20, 06:28

**Background**: In HTTP, GET requests are safe and idempotent but have limited URI length, while POST is not safe or idempotent, making it unsuitable for repeated queries. Safe methods do not modify server state, and idempotent methods produce the same result on repeated identical requests. The QUERY method aims to combine the safety of GET with the flexibility of POST's request body.

<details><summary>References</summary>
<ul>
<li><a href="https://httpwg.org/http-extensions/draft-ietf-httpbis-safe-method-w-body.html">The HTTP QUERY Method</a></li>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/HTTP/Reference/Methods">HTTP request methods - MDN Web Docs</a></li>

</ul>
</details>

**Tags**: `#HTTP`, `#Web Standards`, `#IETF`, `#API`, `#Networking`

---

<a id="item-19"></a>
## [LM Studio Demos 1T Kimi K2.6 on Four Mac Studios at WWDC](https://x.com/lmstudio/status/2067301278976180531) ⭐️ 7.0/10

At WWDC, LM Studio collaborated with Apple to run the 1-trillion-parameter Kimi K2.6 model on a cluster of four Mac Studios, showcasing secure remote access from a MacBook Neo and iPhone using LM Link. This demonstration highlights Apple's hardware capability for large-scale AI inference, promoting local processing over cloud dependency and aligning with the industry shift toward on-device AI and edge computing. The model ran on a preview version of LM Studio via a four-node Mac Studio cluster, with LM Link providing end-to-end encrypted remote access. Kimi K2.6 is known for its strong coding and agent swarm features, but specific hardware configurations (e.g., chip generation, memory) were not disclosed.

telegram · zaihuapd · Jun 20, 07:02

**Background**: LM Studio is a user-friendly tool for running local AI models on personal computers, with a new mobile app that enables remote access. Kimi K2.6 is an open-source large language model from Moonshot AI, optimized for coding and autonomous agents. Mac Studio is Apple's high-performance desktop for professionals. WWDC is Apple's annual conference where it previews new technologies.

<details><summary>References</summary>
<ul>
<li><a href="https://grokipedia.com/page/LM_Studio">LM Studio</a></li>
<li><a href="https://www.linkedin.com/company/lmstudio-ai">LM Studio | LinkedIn</a></li>
<li><a href="https://www.kimi.com/ai-models/kimi-k2-6">Kimi K2.6 | Leading Open-Source Model in Coding & Agent</a></li>

</ul>
</details>

**Tags**: `#AI`, `#LLM`, `#Apple`, `#MacStudio`, `#ClusterComputing`

---

<a id="item-20"></a>
## [UK to require social platforms to boost public service news](https://www.ft.com/content/7f147e35-d2ca-48fe-a886-95721002ce3c?syn-25a6b1a6=1) ⭐️ 7.0/10

The UK government plans to mandate that social media platforms like YouTube and Meta increase the visibility of public service broadcasters' content, such as from the BBC and ITV, with a public consultation expected to launch this month. The policy could reshape algorithmic news curation, counteracting the suppression of local authoritative news by foreign algorithms and the spread of misinformation, while also raising concerns about content diversity and the impact on the creator economy. A green paper also proposes shutting down terrestrial TV signals by 2034 and moving fully to broadband delivery, with tech giants arguing that forced prioritization undermines algorithmic logic and could harm smaller creators.

telegram · zaihuapd · Jun 20, 07:51

**Background**: Public service broadcasters like the BBC and ITV are UK institutions mandated to provide impartial, high-quality news. Younger audiences increasingly consume news on social media, where algorithms may favor engagement-driven content over authoritative sources. The UK government is concerned that foreign-owned algorithms (e.g., from US-based Meta and Google) are sidelining domestic news.

**Tags**: `#UK policy`, `#social media regulation`, `#public service broadcasting`, `#algorithmic curation`, `#content moderation`

---

<a id="item-21"></a>
## [Tencent to Launch AI Agent in WeChat, Approval This Month](https://t.me/zaihuapd/42072) ⭐️ 7.0/10

Tencent is internally testing an AI agent prototype within WeChat, with plans to initiate compliance approval as soon as this month, followed by limited external testing and phased rollout. The agent allows users to swipe right on the main WeChat interface to input natural language commands, which it then executes by invoking relevant mini-programs—for example, ordering coffee based on taste and price preferences. With over a billion users, WeChat's integration of an AI agent could redefine the super-app experience, potentially making AI-powered task execution mainstream in China. This move is a strategic response to competing AI agents from Alibaba and ByteDance, which have already gained rapid user growth. The agent leverages WeChat's mini-program ecosystem for task execution, but Tencent faces significant compute power constraints due to insufficient stockpiling of Nvidia chips and tight domestic semiconductor supply. The high cost of full deployment and uncertain short-term profitability are also key challenges, while the feature is still in the early compliance approval stage.

telegram · zaihuapd · Jun 20, 09:23

**Background**: AI agents are generative AI systems capable of autonomously pursuing goals, using tools, and taking actions. WeChat, Tencent's 'super-app' with over 1.3 billion users, hosts mini-programs—lightweight apps within the platform—that perform various services like food ordering and payments. Competitors Alibaba and ByteDance have already launched AI agents in their respective apps Tongyi and Doubao, driving rapid monthly active user growth and pressuring Tencent to catch up.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/AI_agent">AI agent</a></li>
<li><a href="https://en.wikipedia.org/wiki/WeChat_Mini_Program">WeChat Mini Program</a></li>

</ul>
</details>

**Tags**: `#AI agent`, `#Tencent`, `#WeChat`, `#mini-programs`, `#tech industry`

---