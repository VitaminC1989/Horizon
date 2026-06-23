---
layout: default
title: "Horizon Summary: 2026-06-23 (EN)"
date: 2026-06-23
lang: en
---

> From 66 items, 28 important content pieces were selected

---

1. [Valve Launches New Steam Machine with Randomized Reservation System](#item-1) ⭐️ 8.0/10
2. [GLM-5.2 Local Inference: Hardware Requirements and Community Insights](#item-2) ⭐️ 8.0/10
3. [Handling BC Time Zone Changes in PostgreSQL](#item-3) ⭐️ 8.0/10
4. [Flock Surveillance Used by Police to Stalk Women, Warrants Needed](#item-4) ⭐️ 8.0/10
5. [Prompt Injection as Role Confusion: Why Benchmarks Fail](#item-5) ⭐️ 8.0/10
6. [Deno Now Supports Desktop App Development with Webview Backends](#item-6) ⭐️ 8.0/10
7. [Mitchell Hashimoto Pledges Another $400K to Zig Software Foundation](#item-7) ⭐️ 8.0/10
8. [Porting Moebius 0.2B inpainting model to browser via WebGPU with Claude Code](#item-8) ⭐️ 8.0/10
9. [sqlite-utils 4.0rc1 Adds Migrations and Nested Transactions](#item-9) ⭐️ 8.0/10
10. [Red-Teaming after Mythos: AI Security Beyond Traditional Cybersecurity](#item-10) ⭐️ 8.0/10
11. [OpenAI Launches ‘Patch the Planet’ to Secure Open-Source Software](#item-11) ⭐️ 8.0/10
12. [0.5B Causal Diffusion Model Turns Any Image Into a Playable Game Locally](#item-12) ⭐️ 8.0/10
13. [48 Chinese Developers Accuse Apple of Monopoly and Unfulfilled Fee Promises](#item-13) ⭐️ 8.0/10
14. [Nearly Half of LG Smart TV Apps Contain Residential Proxy SDKs](#item-14) ⭐️ 8.0/10
15. [OpenAI's AI-Generated Animated Film 'Critterz' Under $30M Budget](#item-15) ⭐️ 8.0/10
16. [Polymarket Staged Viral Winning-Bet Videos, Investigation Finds](#item-16) ⭐️ 7.0/10
17. [Moebius: 0.2B Inpainting Model Claims 10B-Level Performance](#item-17) ⭐️ 7.0/10
18. [Job Application Asks for SAT Scores, Sparks Debate on Hiring](#item-18) ⭐️ 7.0/10
19. [Chevron and Microsoft ink 20-year power deal for Texas data center](#item-19) ⭐️ 7.0/10
20. [Cloudflare Launches Temporary Accounts for 60-Minute Worker Deployments](#item-20) ⭐️ 7.0/10
21. [GLM-5.2 Marks a Breakthrough for Open-Source AI Agents](#item-21) ⭐️ 7.0/10
22. [US Restricts Anthropic, China Blacklists 56 Firms](#item-22) ⭐️ 7.0/10
23. [Practical Guide to Codex-maxxing for Long-Running Projects](#item-23) ⭐️ 7.0/10
24. [Samsung Electronics Deploys ChatGPT Enterprise and Codex Globally](#item-24) ⭐️ 7.0/10
25. [Run Krea 2 Turbo in ComfyUI with FP8 Weights Halving VRAM](#item-25) ⭐️ 7.0/10
26. [New Masking Mode for Identity Feature Transfer in ComfyUI](#item-26) ⭐️ 7.0/10
27. [Nvidia CEO Praises Huawei, Calls Underestimation Naive](#item-27) ⭐️ 7.0/10
28. [Ex-Meituan PM Criticizes Organizational Culture Hindering Innovation](#item-28) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Valve Launches New Steam Machine with Randomized Reservation System](https://store.steampowered.com/news/group/45479024/view/685257114654870245) ⭐️ 8.0/10

Valve has launched a new Steam Machine gaming PC, featuring a randomized reservation system designed to ensure fairness and an open platform allowing users to install any software or operating system. This launch marks Valve's renewed push into living room gaming hardware with an open philosophy, directly competing with locked-down consoles and addressing the bot-scalping problem with its novel reservation system. The Steam Machine is built from components sourced worldwide, with pricing tied to component costs; Valve began sourcing in 2023 and acknowledges that price fluctuations are possible. The reservation signup is open for several days, and selection is random rather than first-come-first-served.

hackernews · theschwa · Jun 22, 17:09 · [Discussion](https://news.ycombinator.com/item?id=48632884)

**Background**: Steam Machines are pre-built gaming PCs running SteamOS, first introduced by Valve in 2015 but discontinued after limited success. The new model, internally named 'Newell Nucleus,' revives the concept with updated hardware. The randomized reservation system is a response to scalpers and bots that plague high-demand product launches, similar to lottery systems used for concert tickets or sneaker releases.

**Discussion**: Community response is highly positive, praising the fair reservation system and open platform stance. Some users note the transparency in pricing tied to component costs. The humorous Cuphead gameplay video also garnered attention, with one commenter simply stating 'I want to buy one j' reflecting high demand.

**Tags**: `#steam`, `#gaming`, `#hardware`, `#valve`, `#consumer-electronics`

---

<a id="item-2"></a>
## [GLM-5.2 Local Inference: Hardware Requirements and Community Insights](https://unsloth.ai/docs/models/glm-5.2) ⭐️ 8.0/10

A Hacker News discussion revealed practical hardware configurations for running the open-weight GLM-5.2 model locally, with users reporting successful setups using consumer GPUs and large RAM, and sharing quantization techniques like Q4_K_XL. This development is significant as it brings cutting-edge AI capabilities to individuals, bypassing cloud APIs and fostering a shift toward decentralized, private AI usage. It also signals that open-source models are increasingly competing with closed-source alternatives in performance. Running GLM-5.2 requires 24GB of VRAM and 256GB of system RAM for Mixture of Experts (MoE) offloading; a build with dual RTX 3090 GPUs and 512GB RAM using Q4_K_XL quantization achieves about 6 tokens per second, but prompt processing can be 20-50 times slower without dedicated GPU clusters, making interactive use impractical for setups without multiple high-end GPUs.

hackernews · TechTechTech · Jun 22, 21:21 · [Discussion](https://news.ycombinator.com/item?id=48636377)

**Background**: GLM-5.2 is an open-weight large language model from Z.AI, noted for top-ranked design benchmarks and multi-token prediction. Quantization reduces model precision (e.g., from 16-bit to 4-bit) to cut memory usage and speed up inference, often with minimal quality loss. The model uses a MoE architecture, activating only a subset of parameters per token, which allows offloading inactive experts to system memory. Community builds frequently employ llama.cpp, a framework optimized for running LLMs on consumer hardware.

<details><summary>References</summary>
<ul>
<li><a href="https://www.reddit.com/r/technology/comments/1uc5hjh/what_is_glm52_another_opensource_chinese_ai_model/">r/technology on Reddit: What is GLM-5.2? Another open-source Chinese AI model has Silicon Valley's attention.</a></li>
<li><a href="https://docs.z.ai/guides/llm/glm-5.2">GLM-5.2 - Overview - Z.AI DEVELOPER DOCUMENT</a></li>
<li><a href="https://www.ibm.com/think/topics/quantization">What is Quantization? | IBM</a></li>

</ul>
</details>

**Discussion**: The overall sentiment is enthusiastic yet pragmatic: users are excited about closing the gap between local and cloud AI, but many highlight that practical usability depends on costly multi-GPU setups to avoid extremely slow prompt processing. Some share successful budget builds, while others emphasize that quantized local runs remain significantly slower than APIs for interactive tasks. There is widespread optimism that future hardware and improved quantization will make local deployment more viable.

**Tags**: `#AI`, `#open-source`, `#local-llm`, `#hardware`, `#quantization`

---

<a id="item-3"></a>
## [Handling BC Time Zone Changes in PostgreSQL](https://www.crunchydata.com/blog/british-columbia-and-time-zone-changes) ⭐️ 8.0/10

A Crunchy Data blog post detailed practical strategies for managing potential time zone changes in British Columbia within PostgreSQL, sparking community discussions on best practices like storing local time for future events and using bitemporal data models. This guidance is critical for developers of time-sensitive applications, as legislative time zone shifts can cause scheduling errors and data inconsistencies; the post and discussion offer robust, real-world techniques to mitigate such risks. Key advice includes storing future appointments with local date/time/timezone to preserve context, using UTC for past events, and adopting bitemporal data structures to handle rule changes retroactively. The importance of relying on the tzdata library rather than custom timezone logic is strongly emphasized.

hackernews · sprawl_ · Jun 22, 19:21 · [Discussion](https://news.ycombinator.com/item?id=48634787)

**Background**: British Columbia has been considering time zone changes, potentially adopting permanent daylight saving time, prompting database administrators to review temporal data handling. Temporal databases distinguish between valid time (when a fact is true) and transaction time (when recorded); bitemporal models track both, essential for accurate history after retroactive changes like timezone recalibrations.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Bitemporal_data">Bitemporal data</a></li>
<li><a href="https://martinfowler.com/articles/bitemporal-history.html">Bitemporal History</a></li>

</ul>
</details>

**Discussion**: Commenters reinforced storing future events with local timezone for context, using bitemporal modeling for historical precision, and leaning on the tzdata library. They noted BC's multi-timezone complexity, the fragility of homegrown timezone code, and the broader applicability of bitemporal approaches to any changing assumptions.

**Tags**: `#timezone`, `#postgres`, `#databases`, `#temporal-data`, `#hackernews`

---

<a id="item-4"></a>
## [Flock Surveillance Used by Police to Stalk Women, Warrants Needed](https://ipvm.com/reports/police-chiefs-track) ⭐️ 8.0/10

An investigation by IPVM reveals that police chiefs have misused the Flock automated license plate reader system to stalk women, highlighting the urgent need for warrants and oversight. This case exemplifies the broader risks of unregulated mass surveillance technologies, demonstrating how they can enable abuse of power and violate individual privacy without proper legal safeguards. Flock Safety's ALPR network captures license plate data across the U.S., and while the company claims abuse is rare, internal documents suggest that officer misuse, particularly for personal tracking, is the most common form of abuse.

hackernews · jhonovich · Jun 22, 19:13 · [Discussion](https://news.ycombinator.com/item?id=48634694)

**Background**: Flock Safety is a private company that installs automated license plate readers and cameras on public roads, creating a nationwide surveillance network that tracks vehicle movements over time. This has raised significant privacy concerns, leading communities to push back and some cities to cancel contracts due to potential abuses.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cnet.com/home/security/when-flock-comes-to-town-why-cities-are-axing-the-controversial-surveillance-technology/">When Flock Surveillance Comes to Your Town: Everything to... - CNET</a></li>
<li><a href="https://www.eff.org/deeplinks/2025/12/effs-investigations-expose-flock-safetys-surveillance-abuses-2025-review">EFF's Investigations Expose Flock Safety's Surveillance Abuses...</a></li>

</ul>
</details>

**Discussion**: Commenters emphasize the dangers of dating police due to their access to surveillance tools, note the normalization of mass surveillance, and point out contradictions in Flock's characterization of abuse as both rare and the most common form.

**Tags**: `#surveillance`, `#privacy`, `#law-enforcement`, `#technology-ethics`, `#abuse-of-power`

---

<a id="item-5"></a>
## [Prompt Injection as Role Confusion: Why Benchmarks Fail](https://role-confusion.github.io/) ⭐️ 8.0/10

A new paper reframes prompt injection attacks as 'role confusion,' showing that language models infer speaker identity from the style of text rather than labeled role tags. The study demonstrates that static benchmarks are ineffective, while human red-teamers can achieve near-100% attack success against frontier models. This exposes a critical weakness in LLM security: relying on static benchmarks gives a false sense of safety, as they do not reflect the adaptive nature of real-world attacks. The near-100% success rate by human red-teamers underscores the urgency for more robust, dynamic defense mechanisms. The paper identifies that current models do not truly understand designated roles; instead, they are sensitive to textual patterns that mimic instructions. Static benchmarks fail because they contain patterns that models have already been trained to recognize and block, while human red-teamers can iteratively adapt their attacks to trick the model.

hackernews · x312 · Jun 22, 15:48 · [Discussion](https://news.ycombinator.com/item?id=48631888)

**Background**: Prompt injection attacks exploit the inability of language models to distinguish between trusted developer instructions and user inputs. Most current defenses rely on special formatting or tags to demarcate roles, but this paper argues that models are actually relying on the writing style, making them vulnerable to stylistic manipulation. Static benchmarks are collections of fixed test prompts used to evaluate model safety, but they often become outdated as models are updated.

<details><summary>References</summary>
<ul>
<li><a href="https://letsdatascience.com/news/researchers-demonstrate-prompt-injection-as-role-confusion-40c29edb">Researchers Demonstrate Prompt Injection as Role Confusion | Let's Data Science</a></li>
<li><a href="https://en.wikipedia.org/wiki/Prompt_injection">Prompt injection - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters praised the blog-style write-up for making the research more accessible. Some pointed out that while serialized markers like `<think>` are used, internally models may have separate representations, but the paper's core insight about stylistic cues remains valid. One user shared their own experiment with role embeddings, and there was agreement that static benchmarks are insufficient.

**Tags**: `#prompt-injection`, `#llm-security`, `#ai-safety`, `#role-confusion`, `#academic-paper`

---

<a id="item-6"></a>
## [Deno Now Supports Desktop App Development with Webview Backends](https://docs.deno.com/runtime/desktop/) ⭐️ 8.0/10

Deno has introduced official support for building desktop applications, allowing developers to create native binaries with webview, Chromium Embedded Framework (CEF), or raw backends. This new capability expands Deno beyond servers and CLIs into the desktop app space. This positions Deno as a lightweight alternative to Electron and Tauri, potentially reducing app sizes and leveraging Deno's secure permission model for desktop apps. It could attract developers seeking a modern, secure runtime for cross-platform desktop development. The permission system allows permissions to be baked into the binary at compile time, though not yet dynamically user-adjustable. A shared CEF runtime is planned to further reduce per-app binary size from hundreds of MB to a few MB.

hackernews · GeneralMaximus · Jun 22, 05:38 · [Discussion](https://news.ycombinator.com/item?id=48626137)

**Background**: Deno is a secure JavaScript/TypeScript runtime built on V8. Webview backends use the system's built-in web rendering engine (like Edge WebView2 on Windows, WebKit on macOS) instead of bundling a full Chromium browser, resulting in smaller app sizes. CEF allows embedding Chromium for more consistent behavior, but typically bundles a large binary. Electron and Tauri are popular frameworks for building desktop apps with web technologies, but they either bundle a browser or rely on system webviews.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/webview/webview">GitHub - webview/webview: Tiny cross-platform webview library for C/C++. Uses WebKit (GTK/Cocoa) and Edge WebView2 (Windows). · GitHub</a></li>
<li><a href="https://en.wikipedia.org/wiki/Chromium_Embedded_Framework">Chromium Embedded Framework - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Overall community sentiment is positive, with enthusiasm for smaller app sizes and Deno's ecosystem growth. Concerns were raised about shared CEF versioning, the need for dynamic permission surfacing to end users, and a desire for a 'launch in browser' development option. The feature is seen as a strategic and welcome addition.

**Tags**: `#deno`, `#desktop-apps`, `#webview`, `#cef`, `#javascript-runtime`

---

<a id="item-7"></a>
## [Mitchell Hashimoto Pledges Another $400K to Zig Software Foundation](https://mitchellh.com/writing/zig-donation-2026) ⭐️ 8.0/10

Mitchell Hashimoto, creator of Ghostty, has committed an additional $400,000 donation to the Zig Software Foundation, further supporting the development of the Zig programming language. This significant financial backing reinforces Zig's sustainability and may encourage other donors, while highlighting the success of the Zig-based terminal emulator Ghostty and the growing ecosystem around the language. The pledge follows prior donations from Hashimoto and comes as the Zig Software Foundation continues to rely on community funding for full-time development; the community also discussed Zig's policy of rejecting LLM-generated contributions to maintain language coherence.

hackernews · tosh · Jun 22, 13:43 · [Discussion](https://news.ycombinator.com/item?id=48630020)

**Background**: Zig is a systems programming language designed as an improvement over C, featuring manual memory management and compile-time generics. Ghostty is a GPU-accelerated cross-platform terminal emulator built with Zig, known for its performance. Mitchell Hashimoto is a prominent open-source developer who previously created Vagrant and Terraform.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Zig_(programming_language)">Zig (programming language)</a></li>
<li><a href="https://ziglang.org/">Home ⚡ Zig Programming Language</a></li>
<li><a href="https://ghostty.org/">Ghostty</a></li>

</ul>
</details>

**Discussion**: Overall sentiment is highly positive, with praise for Hashimoto's philosophy on embracing individuality on the internet. Some commenters highlighted Ghostty's remarkable utility compared to multi-million-dollar acquisitions, while others endorsed Zig's stance against LLM-generated contributions as vital for preserving language design integrity. A developer shared their positive experience modifying Ghostty's codebase.

**Tags**: `#zig`, `#open-source-funding`, `#ghostty`, `#programming-languages`, `#community`

---

<a id="item-8"></a>
## [Porting Moebius 0.2B inpainting model to browser via WebGPU with Claude Code](https://simonwillison.net/2026/Jun/22/porting-moebius/#atom-everything) ⭐️ 8.0/10

Simon Willison ported the Moebius 0.2B image inpainting model to run entirely in the browser using WebGPU, with the assistance of Claude Code, enabling client-side GPU-accelerated inpainting without CUDA dependencies. This demonstrates the growing feasibility of running AI models directly in the browser, lowering barriers for accessible, private image editing and reducing reliance on cloud GPU servers. The implementation uses ONNX Runtime Web with WebGPU backend for accelerated inference; the model uses letterboxing for non-square images and operates with a lightweight 0.2B parameter size.

rss · Simon Willison · Jun 22, 23:43

**Background**: Moebius is a lightweight image inpainting model with just 200 million parameters, yet achieves quality comparable to 10B+ models. WebGPU is a low-level graphics API that enables web applications to run computationally intensive tasks on the user's GPU. Claude Code, an AI-powered coding tool, was used to assist in porting the model from a CUDA-dependent Python implementation to a browser-based JavaScript environment.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/papers/2606.19195">Paper page - Moebius : 0 . 2 B Lightweight Image Inpainting Framework...</a></li>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/API/WebGPU_API">WebGPU API - Web APIs | MDN</a></li>
<li><a href="https://en.wikipedia.org/wiki/Claude_Code">Claude Code</a></li>

</ul>
</details>

**Tags**: `#image-inpainting`, `#webgpu`, `#browser-based-ai`, `#model-porting`, `#claude-code`

---

<a id="item-9"></a>
## [sqlite-utils 4.0rc1 Adds Migrations and Nested Transactions](https://simonwillison.net/2026/Jun/21/sqlite-utils/#atom-everything) ⭐️ 8.0/10

sqlite-utils 4.0rc1, a release candidate for the popular Python SQLite library, introduces database migrations via a port of the sqlite-migrate package and support for nested transactions. Migrations allow developers to version control database schema changes, easing team collaboration and deployment. Nested transactions provide finer-grained control over complex operations, enhancing reliability. The migration system is deliberately minimal: it does not support reverse migrations, so errors must be fixed with new forward migrations. Nested transactions are implemented using savepoints, as SQLite lacks true nested transaction support.

rss · Simon Willison · Jun 21, 23:30

**Background**: sqlite-utils is a Python library and CLI tool that provides high-level operations for SQLite databases, such as table transformations and JSON data insertion. Migrations are a common feature in web frameworks like Django that allow incremental schema changes. Nested transactions enable a transaction within a transaction, often simulated via savepoints in SQLite.

<details><summary>References</summary>
<ul>
<li><a href="https://practicaldev-herokuapp-com.freetls.fastly.net/aharmaz/database-migrations-from-manual-to-automated-management-5ffj">Database Migrations : From Manual to Automated Management.</a></li>
<li><a href="https://colinchsql.github.io/2023-10-13/09-59-46-569035-sqlite-transactions/">SQLite Transactions</a></li>

</ul>
</details>

**Tags**: `#sqlite`, `#python`, `#tools`, `#database`, `#release`

---

<a id="item-10"></a>
## [Red-Teaming after Mythos: AI Security Beyond Traditional Cybersecurity](https://www.latent.space/p/gray-swan) ⭐️ 8.0/10

Zico Kolter (OpenAI board member) and Matt Fredrikson (Gray Swan CEO) discussed on the Latent Space podcast why AI security demands novel approaches, emphasizing that it is not merely cybersecurity augmented by AI. The conversation, featuring an OpenAI insider, signals high-level recognition of AI-specific adversarial threats and could reshape red-teaming practices across the industry. The discussion was framed by Anthropic's recent Mythos model, which autonomously solved a 32-step corporate network attack simulation, highlighting the inadequacy of conventional cybersecurity for AI systems.

rss · Latent Space · Jun 22, 21:06

**Background**: Latent space is a compressed, lower-dimensional representation of data used in machine learning to extract essential features. Adversarial AI exploits model vulnerabilities by feeding maliciously crafted inputs. Mythos, an unreleased Anthropic model, demonstrated alarming offensive cybersecurity capabilities, leading to restricted access under Project Glasswing.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Latent_space">Latent space - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Adversarial_machine_learning">Adversarial machine learning - Wikipedia</a></li>
<li><a href="https://www.scientificamerican.com/article/what-is-mythos-and-why-are-experts-worried-about-anthropics-ai-model/">What is Mythos and why are experts worried about Anthropic’s AI model</a></li>

</ul>
</details>

**Tags**: `#AI security`, `#red-teaming`, `#adversarial AI`, `#Gray Swan`, `#Latent Space`

---

<a id="item-11"></a>
## [OpenAI Launches ‘Patch the Planet’ to Secure Open-Source Software](https://openai.com/index/patch-the-planet/) ⭐️ 8.0/10

OpenAI announced the Patch the Planet initiative, expanding its Daybreak cybersecurity program to use AI and expert review for finding and fixing vulnerabilities in open-source software. It released GPT-5.5-Cyber (85.6% on CyberGym), the Codex Security plugin, and government partnerships with Australia, Canada, Japan, and the EU's ENISA. This initiative represents a significant AI-driven approach to securing the open-source ecosystem, directly aiding maintainers and reducing supply chain risks. By integrating AI into vulnerability detection and patching at scale, it could shift industry practices in cybersecurity. The program has already covered over 30 projects (cURL, Go, Python), found hundreds of security issues, and merged dozens of patches. Validated vulnerabilities include those in Linux, OpenBSD, Chrome, Safari, and Firefox. GPT-5.5-Cyber is restricted to vetted defenders; the Codex Security plugin acts as an application security agent for code review.

telegram · OpenAI Blog · Jun 23, 01:01

**Background**: Open-source software is essential to modern infrastructure but often lacks resources for thorough security audits. OpenAI's Daybreak initiative was previously launched to apply AI to cybersecurity challenges. The Patch the Planet effort extends this by collaborating with security firms like Trail of Bits and directly engaging with open-source maintainers to accelerate vulnerability remediation.

<details><summary>References</summary>
<ul>
<li><a href="https://openai.com/index/patch-the-planet/">Patch the Planet : a Daybreak initiative to support open... | OpenAI</a></li>
<li><a href="https://cryptobriefing.com/openai-patch-planet-open-source-security/">OpenAI launches Patch the Planet initiative to enhance open source...</a></li>
<li><a href="https://trailofbits.com/patch-the-planet/">Patch the Planet · Trail of Bits</a></li>

</ul>
</details>

**Tags**: `#AI`, `#cybersecurity`, `#open-source`, `#vulnerability`, `#OpenAI`

---

<a id="item-12"></a>
## [0.5B Causal Diffusion Model Turns Any Image Into a Playable Game Locally](https://www.reddit.com/r/StableDiffusion/comments/1uc55ix/diffusion_model_that_can_turn_any_image_into_a/) ⭐️ 8.0/10

A researcher trained a 0.5B-parameter causal diffusion model from scratch that simulates real-time, playable games from a single image on a consumer GPU (RTX 5090), accepting keyboard input for interactivity. This breakthrough demonstrates that real-time game generation is possible locally, without expensive datacenter hardware, potentially democratizing AI-driven interactive entertainment and reducing cloud dependency. The model operates autoregressively with a causal transformer, leveraging KV-caching for frame generation. It runs in bf16 with no quantization, currently showing motion artifacts and lacking classifier-free guidance; an 0.8B version is in training.

reddit · r/StableDiffusion · /u/lucidml_lover · Jun 21, 23:58

**Background**: Diffusion models generate data by iterative denoising. Causal diffusion processes frames sequentially like autoregressive language models, enabling a KV cache to store past computations and accelerate new frame generation. Classifier-free guidance is commonly used in image generation to improve prompt alignment but is computationally expensive; here it is omitted for speed. Most video generation models are too large to run in real time on consumer hardware.

<details><summary>References</summary>
<ul>
<li><a href="https://magazine.sebastianraschka.com/p/coding-the-kv-cache-in-llms">Understanding and Coding the KV Cache in LLMs from Scratch</a></li>
<li><a href="https://grokipedia.com/page/Classifier-free_guidance">Classifier-free guidance</a></li>

</ul>
</details>

**Tags**: `#diffusion models`, `#game generation`, `#real-time AI`, `#local inference`, `#autoregressive models`

---

<a id="item-13"></a>
## [48 Chinese Developers Accuse Apple of Monopoly and Unfulfilled Fee Promises](https://m.nbd.com.cn/articles/2026-06-22/4433380.html) ⭐️ 8.0/10

On June 22, 48 Chinese iOS developers filed an antitrust complaint with China's State Administration for Market Regulation, alleging that Apple abused its market dominance and failed to fulfill its promise that App Store commission rates in China would not exceed those in other markets. This moves the 'Apple tax' and the imbalance in market openness to the forefront of regulatory scrutiny in China, the world's second-largest iOS market, potentially influencing global App Store policies and developer rights. The complaint demands that Apple immediately open third-party app distribution, in-app alternative payments, and out-of-app payment links, and proposes a 'global policy auto-alignment monitoring mechanism'; it contrasts China's situation with markets like Brazil that already allow third-party stores.

telegram · zaihuapd · Jun 22, 14:57

**Background**: Apple's App Store is the sole distribution channel for iOS apps, charging up to 30% commission on in-app purchases. Under global antitrust pressure, some regions have forced Apple to allow alternative payment systems or third-party app stores. In March 2023, Apple adjusted rates in some markets; however, developers argue that without parallel reforms, China's effective costs remain high.

**Tags**: `#Antitrust`, `#Apple`, `#App Store`, `#China`, `#Developer Advocacy`

---

<a id="item-14"></a>
## [Nearly Half of LG Smart TV Apps Contain Residential Proxy SDKs](https://spur.us/blog/smart-tv-apps-residential-proxy-sdks) ⭐️ 8.0/10

A scan of 6,038 LG and Samsung smart TV apps found that 2,058 apps, nearly half on LG's platform, contain residential proxy SDKs that can enroll devices into proxy networks without user consent. This exposes a widespread privacy threat where users' home IP addresses can be exploited for malicious activities, highlighting a critical lack of platform-level restrictions on LG and Samsung TVs compared to Amazon and Roku. The affected apps include screensavers, clocks, and mini-games, and the proxy functionality can persist even after the app is closed. Amazon and Roku have already banned such third-party proxy services, while LG and Samsung have not.

telegram · zaihuapd · Jun 23, 02:26

**Background**: Residential proxies route traffic through IP addresses assigned to real home broadband connections, making them appear as ordinary users. They are used for web scraping, ad verification, and bypassing geo-restrictions, but can be misused for fraud, credential stuffing, or spreading misinformation. Smart TV apps embedding residential proxy SDKs can quietly turn millions of devices into proxy nodes, often without clear disclosure or user consent.

<details><summary>References</summary>
<ul>
<li><a href="https://www.bright.cn/proxy-types/residential-proxies">购买住宅代理 - 起价 $2.94/GB - 免费试用</a></li>
<li><a href="https://www.lunaproxy.com/hk/blog/the-best-residential-proxy-in-2023.html">2023年最佳住宅代理</a></li>

</ul>
</details>

**Tags**: `#privacy`, `#security`, `#IoT`, `#smart-tv`, `#proxy-networks`

---

<a id="item-15"></a>
## [OpenAI's AI-Generated Animated Film 'Critterz' Under $30M Budget](https://t.me/zaihuapd/42125) ⭐️ 8.0/10

OpenAI is producing an animated feature film titled 'Critterz' using its own AI tools, including GPT-5, with a budget under $30 million and a nine-month production timeline, aiming to premiere at the Cannes Film Festival in 2026. This showcases AI's potential to drastically reduce the cost and time of animation production, potentially disrupting the traditional Hollywood model and making high-quality filmmaking more accessible. The film leverages GPT-5, a multimodal large language model launched in August 2025, for tasks such as scriptwriting and character design, though specific integration methods are undisclosed. The nine-month cycle contrasts sharply with the typical 4-5 years for animated features.

telegram · zaihuapd · Jun 23, 03:11

**Background**: GPT-5 is OpenAI's latest generative pre-trained transformer model, excelling in multimodal tasks like text, image, and code generation. Traditional animated films often exceed $100 million in budget and require years of manual artistry. OpenAI's move into filmmaking follows experimentation with AI-generated shorts, signaling a push into mainstream creative industries.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GPT-5">GPT-5</a></li>
<li><a href="https://openai.com/gpt-5/">GPT-5 is here | OpenAI</a></li>

</ul>
</details>

**Tags**: `#AI`, `#animation`, `#OpenAI`, `#film production`, `#GPT-5`

---

<a id="item-16"></a>
## [Polymarket Staged Viral Winning-Bet Videos, Investigation Finds](https://arstechnica.com/tech-policy/2026/06/polymarkets-viral-videos-showed-people-winning-big-but-the-bets-were-fake/) ⭐️ 7.0/10

An investigation revealed that Polymarket staged viral videos showing people winning large sums by using a copycat website to fake the wins. The platform instructed content creators to present these staged wins as genuine, misleading viewers. This exposes deceptive advertising tactics by a major prediction market, raising ethical concerns and intensifying calls for stricter regulation of crypto gambling platforms. It also damages trust in platforms that claim to offer transparent, crowd-sourced insights. The Wall Street Journal uncovered that Polymarket used a duplicate site to simulate high-profit trades, with content creators instructed to share these as real user wins. This was part of a broader influencer campaign to promote Polymarket's supposed accuracy, and the platform has a history of posting misleading social media content.

hackernews · pseudolus · Jun 23, 00:47 · [Discussion](https://news.ycombinator.com/item?id=48638660)

**Background**: Polymarket is a cryptocurrency-based prediction market founded in 2020, allowing users to bet on real-world events like elections and conflicts. It has faced bans in several countries and regulatory scrutiny due to offering bets on sensitive topics and allegations of insider trading. The platform claims to aggregate collective wisdom, but researchers have questioned its accuracy and transparency.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Polymarket">Polymarket</a></li>
<li><a href="https://en.wikipedia.org/wiki/Prediction_market">Prediction market</a></li>

</ul>
</details>

**Discussion**: Commenters were largely critical, with many calling for regulation of gambling apps and expressing shock at how easily bets can be placed. Some noted that fake advertising is common in other industries, but others questioned whether this specific act constitutes fraud, emphasizing the unique harms of gambling-related deception.

**Tags**: `#prediction markets`, `#gambling`, `#advertising ethics`, `#regulation`, `#tech policy`

---

<a id="item-17"></a>
## [Moebius: 0.2B Inpainting Model Claims 10B-Level Performance](https://hustvl.github.io/Moebius/) ⭐️ 7.0/10

Moebius, a new 0.2-billion-parameter image inpainting model from HUSTVL, has been released, claiming performance comparable to models ten times its size. Interactive demos are available via Hugging Face Spaces and community ONNX browser implementations. This model demonstrates how efficient architectures can drastically reduce computational cost while maintaining high-quality inpainting, making advanced image editing more accessible on consumer devices and in browsers. The model is limited to a 512x512 output resolution, and community tests show it struggles with novel objects and produces visibly smoother inpainted regions. It has been successfully converted to ONNX, requiring a ~1.3GB download for browser inference.

hackernews · DSemba · Jun 22, 13:53 · [Discussion](https://news.ycombinator.com/item?id=48630171)

**Background**: Image inpainting is a technique to fill in missing or damaged parts of images, traditionally used in art restoration. Modern AI-based inpainting models learn to reconstruct plausible content from context. Moebius uses a lightweight architecture with only 0.2 billion parameters, aiming to challenge much larger models in this task.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Image_inpainting">Image inpainting</a></li>

</ul>
</details>

**Discussion**: The community is impressed by the efficiency but notes it does not truly match 10B models, with issues on novel objects and 512x512 limitation. Simon Willison's browser demo works well but requires a large download, while some users encountered failures on Hugging Face Spaces. There is interest in manga inpainting applications.

**Tags**: `#image-inpainting`, `#deep-learning`, `#model-efficiency`, `#computer-vision`, `#huggingface`

---

<a id="item-18"></a>
## [Job Application Asks for SAT Scores, Sparks Debate on Hiring](https://mrmarket.lol/job-application-asked-for-my-sat-scores/) ⭐️ 7.0/10

A job applicant reported being asked for SAT scores during a hiring process, prompting widespread discussion about the relevance of standardized testing in tech industry recruitment. The incident highlights ongoing tensions around using standardized tests like the SAT as a hiring filter, especially when college degrees no longer guarantee foundational skills, and reflects broader debates about equity and bias in recruitment. Comments referenced the University of California faculty's recent call to reinstate the SAT to address a learning gap, while others argued that SAT scores poorly correlate with engineer qualities like consistency, curiosity, and communication.

hackernews · seltzerboys · Jun 22, 20:55 · [Discussion](https://news.ycombinator.com/item?id=48636062)

**Background**: The SAT is a standardized test long used for U.S. college admissions. In 2020, the University of California system stopped requiring it, a move some now feel has lowered academic preparedness. Employers occasionally request SAT scores when they distrust grade inflation or degree signaling.

**Discussion**: Opinions varied: one commenter noted UC faculty warned that dropping the SAT would widen ability gaps; another said listing college achievements in job ads signals cultural conformity, dissuading diverse applicants. Others stressed that managers value traits like consistency and communication over test scores, and that hiring often relies on 'similar-to-me' bias.

**Tags**: `#hiring`, `#standardized-testing`, `#bias`, `#tech-industry`, `#education`

---

<a id="item-19"></a>
## [Chevron and Microsoft ink 20-year power deal for Texas data center](https://www.chevron.com/newsroom/2026/q2/chevron-signs-20-year-power-agreement-with-microsoft-for-west-texas-data-center) ⭐️ 7.0/10

Chevron has signed a 20-year power purchase agreement to supply electricity to a Microsoft data center in West Texas, tapping the region's abundant natural gas. The deal highlights the tension between big tech's carbon pledges and its growing energy needs, as Microsoft relies on natural gas while aiming to be carbon negative, with negative gas prices in the Permian Basin adding complexity. Power will come mainly from GE Vernova and Solar Turbines (a Caterpillar subsidiary making industrial gas turbines, despite its 'solar' name). Waha hub natural gas prices have been negative, recently hitting -$9/MCF due to oversupply from oil drilling.

hackernews · cdrnsf · Jun 22, 13:43 · [Discussion](https://news.ycombinator.com/item?id=48630029)

**Background**: The Permian Basin in West Texas is a major oil region where natural gas is often a byproduct, and flaring or negative prices occur due to limited pipeline capacity. Power purchase agreements (PPAs) are long-term contracts enabling buyers like Microsoft to lock in electricity rates. Microsoft has a public goal to be carbon negative by 2030.

<details><summary>References</summary>
<ul>
<li><a href="https://naturalgasintel.com/news/negative-natural-gas-spot-prices-pepper-permian-basin/">Negative Natural Gas Spot Prices Pepper Permian Basin</a></li>
<li><a href="https://en.wikipedia.org/wiki/Power_purchase_agreement">Power purchase agreement</a></li>

</ul>
</details>

**Discussion**: Commenters noted the irony of Microsoft using fossil fuels despite its carbon-negative pledge, with some surprised given Texas' cheap solar and battery options. Others pointed out Solar Turbines' misleading name and the region's persistent negative gas prices, questioning the deal's sustainability and economics.

**Tags**: `#energy`, `#data-centers`, `#natural-gas`, `#microsoft`, `#sustainability`

---

<a id="item-20"></a>
## [Cloudflare Launches Temporary Accounts for 60-Minute Worker Deployments](https://simonwillison.net/2026/Jun/21/temporary-cloudflare-accounts/#atom-everything) ⭐️ 7.0/10

Cloudflare now allows developers to deploy a Cloudflare Workers project to a temporary, ephemeral environment without creating an account, using the command `npx wrangler deploy --temporary`. The deployment stays live for 60 minutes and can be claimed for permanent use via a provided link. This dramatically lowers the barrier for testing serverless applications, enabling instant prototyping and iteration without sign‑up friction. It is particularly valuable for automated agent workflows but is broadly useful for any quick deployment scenario. The temporary project is given an auto‑generated name (e.g., “Educated Celery”), and the command outputs a claim link that allows the user to transfer the project to a permanent Cloudflare account. The feature respects existing Workers free tier limits.

rss · Simon Willison · Jun 21, 22:01

**Background**: Cloudflare Workers is a serverless platform that runs code on Cloudflare’s edge network. Wrangler is the official CLI for managing Workers projects. Normally, deploying a Worker requires a Cloudflare account and authentication; the new `--temporary` flag bypasses this for short‑lived tests.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.cloudflare.com/temporary-accounts/">Temporary Cloudflare Accounts for AI agents</a></li>
<li><a href="https://simonwillison.net/2026/Jun/21/temporary-cloudflare-accounts/">Temporary Cloudflare Accounts for AI agents</a></li>
<li><a href="https://developers.cloudflare.com/workers/wrangler/">Wrangler · Cloudflare Workers docs</a></li>

</ul>
</details>

**Discussion**: The Hacker News discussion acknowledged the practicality of the feature but many commenters felt the “AI agent” framing was marketing hype, noting it is valuable for all developers doing quick experiments or sharing demos.

**Tags**: `#cloudflare`, `#serverless`, `#developer-tools`, `#ai-agents`, `#cloud-computing`

---

<a id="item-21"></a>
## [GLM-5.2 Marks a Breakthrough for Open-Source AI Agents](https://www.interconnects.ai/p/glm-52-is-the-step-change-for-open) ⭐️ 7.0/10

GLM-5.2, an open-source language model from Z.ai, represents a major leap for open-source AI agents, as highlighted by AI commentator Nathan Lambert. The model features an improved MTP layer for speculative decoding and demonstrates strong performance on long-horizon tasks. This advancement could accelerate the development of open-source agentic AI systems, making them more capable and accessible while challenging proprietary models. It signals a growing maturity in openly available AI agents. The MTP layer improvement boosts speculative decoding acceptance length by up to 20%, and on the SWE-Marathon ultra-long-horizon benchmark, GLM-5.2 trails only Opus 4.8 by 13 points. It is released under the permissive MIT license with no regional restrictions.

rss · Interconnects · Jun 22, 14:52

**Background**: GLM is a family of large language models developed by Chinese AI company Z.ai (formerly Zhipu AI). The company open-sourced the model under the MIT license in July 2025, aiming to foster global innovation. AI agents use such models to autonomously perform complex, multi-step tasks, and open-source releases reduce dependence on proprietary APIs.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GLM-5.2">GLM-5.2</a></li>
<li><a href="https://huggingface.co/zai-org/GLM-5.2">zai-org/ GLM - 5 . 2 · Hugging Face</a></li>
<li><a href="https://registry.ollama.ai/library/glm-5.2">GLM - 5 . 2 is Z.ai’s flagship model for the era of long-horizon tasks.</a></li>

</ul>
</details>

**Tags**: `#GLM`, `#open-source`, `#language-models`, `#AI-agents`, `#agentic-AI`

---

<a id="item-22"></a>
## [US Restricts Anthropic, China Blacklists 56 Firms](https://aiweekly.co/issues/washington-blocked-one-ai-lab-china-blacklisted-56-companies) ⭐️ 7.0/10

Washington restricted export of Anthropic's most advanced AI models, and ten days later Beijing retaliated by blacklisting 56 American companies. This marks the AI export war becoming mutual, escalating US-China tech tensions and threatening to fragment global AI research and trade. Anthropic admitted a routine coding request triggered the restriction, while Microsoft's CEO warned that concentrating power in a few AI models is politically unsustainable.

rss · AI Weekly · Jun 22, 00:00

**Background**: The US frequently imposes export controls to limit foreign access to critical technologies, and China maintains an 'entity list' to sanction foreign firms. Tensions over AI have grown as both nations view advanced models as strategic assets.

**Tags**: `#AI policy`, `#geopolitics`, `#export controls`, `#US-China`, `#Anthropic`

---

<a id="item-23"></a>
## [Practical Guide to Codex-maxxing for Long-Running Projects](https://openai.com/index/codex-maxxing-long-running-work) ⭐️ 7.0/10

OpenAI published a whitepaper by Jason Liu detailing strategies for using Codex as a persistent workspace that preserves context across long, multi-step software engineering tasks. This guide addresses a key limitation of large language models—losing context over time—by showing how Codex can handle complex, evolving projects, potentially boosting developer productivity and enabling more ambitious AI-assisted workflows. The whitepaper introduces 'Codex-maxxing' as a method for reusing skills and maintaining context via a shared workspace; it covers practical tips like using the browser surface and integrating with local tools.

rss · OpenAI Blog · Jun 22, 00:00

**Background**: OpenAI's Codex is an AI coding agent designed for software engineering tasks, from planning to refactoring. LLMs normally process single prompts, but long-running development requires sustained context. Codex-maxxing refers to maximizing Codex's ability to manage such persistent, multi-step work.

<details><summary>References</summary>
<ul>
<li><a href="https://openai.com/codex/">Codex | AI Coding Partner from OpenAI | OpenAI</a></li>
<li><a href="https://jxnl.github.io/blog/writing/2026/05/10/codex-maxxing/">Codex - maxxing - Jason Liu</a></li>
<li><a href="https://openai-dotcom-git-main-openai.vercel.app/index/codex-maxxing-long-running-work/">Codex - maxxing for long-running work | OpenAI</a></li>

</ul>
</details>

**Tags**: `#Codex`, `#LLM-prompting`, `#software-engineering`, `#AI-tools`, `#context-management`

---

<a id="item-24"></a>
## [Samsung Electronics Deploys ChatGPT Enterprise and Codex Globally](https://openai.com/index/samsung-electronics-chatgpt-codex-deployment) ⭐️ 7.0/10

Samsung Electronics has begun rolling out OpenAI's ChatGPT Enterprise and Codex to its employees worldwide, marking one of the largest enterprise-scale deployments of generative AI tools. This move signals growing corporate confidence in generative AI and could accelerate adoption across other multinational companies, potentially transforming workplace productivity and innovation. The deployment includes both ChatGPT Enterprise for general-purpose tasks and Codex for code generation, though the exact number of employees covered and specific implementation details have not been disclosed.

rss · OpenAI Blog · Jun 21, 23:00

**Background**: ChatGPT Enterprise is a business-focused version of OpenAI's conversational AI with enhanced security and privacy controls. Codex is an AI system that translates natural language into code, originally powering tools like GitHub Copilot. Samsung Electronics, as a global technology leader, adopting these tools underscores the practical utility and scalability of generative AI in large organizations.

<details><summary>References</summary>
<ul>
<li><a href="https://grokipedia.com/page/OpenAI_Codex">OpenAI Codex</a></li>

</ul>
</details>

**Tags**: `#enterprise-ai`, `#openai`, `#samsung`, `#chatgpt`, `#codex`

---

<a id="item-25"></a>
## [Run Krea 2 Turbo in ComfyUI with FP8 Weights Halving VRAM](https://www.reddit.com/r/StableDiffusion/comments/1ud2nyq/krea_2_turbo_native_comfyui_workflow_fp8_weights/) ⭐️ 7.0/10

A Reddit post distributes an FP8-quantized Krea 2 Turbo model (from ~26GB to ~12GB VRAM) and a ready-to-use drag-and-drop workflow for ComfyUI 0.25.0, which includes native Krea2 support. This dramatically lowers the hardware requirement, allowing users with consumer GPUs (16–24GB VRAM) to run the 12.9B-parameter Krea 2 Turbo at high resolutions with minimal quality loss, while streamlining setup. Only 2D weight matrices are quantized to float8_e4m3fn; biases, norms, and modulation layers stay in full precision. The workflow uses stock CLIPLoader (type: krea2) and UNETLoader, with recommended settings of 1024×1024, 8 steps, CFG 1.0, and er_sde sampler.

reddit · r/StableDiffusion · /u/LightAppropriate624 · Jun 23, 00:58

**Background**: Krea 2 Turbo is a fast variant of Krea’s image generation model, built on a 12.9B-parameter transformer. FP8 quantization stores model weights in 8-bit floating-point (specifically float8_e4m3fn) to cut memory usage nearly in half while preserving quality. ComfyUI is a node-based interface for Stable Diffusion that, as of version 0.25.0, natively loads Krea2 models without extra nodes.

<details><summary>References</summary>
<ul>
<li><a href="https://www.krea.ai/blog/krea-2-turbo">Introducing Krea 2 Turbo - Krea</a></li>
<li><a href="https://www.spheron.network/blog/fp8-quantization-inference-performance-hardware-explained/">What is FP8 Quantization? AI Inference Performance, Accuracy, and Hardware Support Explained (2026) | Spheron Blog</a></li>

</ul>
</details>

**Discussion**: Users confirm the workflow works, generating images in ~5 seconds on RTX 5090. They appreciate the halved VRAM requirement for consumer cards and share additional model details like the 12.9B parameter count and component sizes.

**Tags**: `#stable-diffusion`, `#comfyui`, `#image-generation`, `#fp8-quantization`, `#deep-learning-tools`

---

<a id="item-26"></a>
## [New Masking Mode for Identity Feature Transfer in ComfyUI](https://www.reddit.com/r/StableDiffusion/comments/1uch5tq/identity_feature_transfer_quick_update_new/) ⭐️ 7.0/10

A second masking mode called 'zero_unmasked_tokens' has been added to the identity feature transfer node. Unlike the original 'focus_only' mode, it blocks unmasked reference tokens from acting as attention sources, strictly isolating the masked region. This update gives users finer control over feature transfer, enabling cleaner outfit swaps, multi-reference workflows, and handling of distracting backgrounds. It is particularly useful for precise image generation tasks in ComfyUI. The new mode, 'zero_unmasked_tokens', is recommended over the old 'focus_only'. The node documentation should be consulted for proper usage, and masking only necessary regions is advised for cleaner results.

reddit · r/StableDiffusion · /u/Capitan01R- · Jun 22, 10:44

**Background**: Identity feature transfer in diffusion models refers to techniques that can transfer a person's identity or specific features from a reference image to a generated image, often using cross-attention mechanisms. In ComfyUI, nodes like this allow users to blend facial features, outfits, or other attributes from multiple sources. Masking helps limit which visual elements are considered, improving precision.

<details><summary>References</summary>
<ul>
<li><a href="https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/ipr2.13324">Face de‐morphing based on identity feature transfer - Zhang - 2025 - IET Image Processing - Wiley Online Library</a></li>
<li><a href="https://en.wikipedia.org/wiki/Attention_(machine_learning)">Attention (machine learning) - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#StableDiffusion`, `#ImageGeneration`, `#FeatureTransfer`, `#Masking`, `#ComfyUI`

---

<a id="item-27"></a>
## [Nvidia CEO Praises Huawei, Calls Underestimation Naive](https://t.me/zaihuapd/42107) ⭐️ 7.0/10

On July 16 in Beijing, Nvidia founder and CEO Jensen Huang stated that underestimating Huawei and Chinese manufacturing is extremely naive. He praised Huawei's strong capabilities in chip design, system engineering, networking, and cloud services, and declared Nvidia would learn from Huawei. The statement from the leader of the dominant AI chip company signals recognition of Huawei as a serious competitor, especially given U.S. export restrictions that have pushed China to develop domestic alternatives. It highlights a potential shift in global tech dynamics and the growing importance of Huawei's in-house AI ecosystem. Huang highlighted Huawei's 'excellent' chip design and noted its excellence in system engineering, network engineering, and cloud services. He also pointed out that Huawei's AI ecosystem is not yet ready to replace Nvidia, and many developers face difficulties with Huawei's platform.

telegram · zaihuapd · Jun 22, 09:05

**Background**: Jensen Huang is the CEO of Nvidia, the world's leading provider of GPUs and AI accelerators. Huawei, a Chinese tech giant, has been a target of U.S. sanctions that restrict its access to advanced chips and technology. In response, Huawei developed its own Ascend series of AI processors and a comprehensive cloud and networking portfolio, positioning itself as a Nvidia rival in China's AI infrastructure market.

<details><summary>References</summary>
<ul>
<li><a href="https://www.zaobao.com.sg/realtime/china/story20250422-6223868">路透： 华 为 最快5月大规模出货 AI 晶 片 910C | 联合早报</a></li>
<li><a href="https://m-robo.datayes.com/feed/detail?id=376625">910C渐近： 华 为 昇 腾 计算产业及供应商全景梳理</a></li>

</ul>
</details>

**Tags**: `#Nvidia`, `#Huawei`, `#AI chips`, `#China tech`, `#Jensen Huang`

---

<a id="item-28"></a>
## [Ex-Meituan PM Criticizes Organizational Culture Hindering Innovation](https://t.me/zaihuapd/42110) ⭐️ 7.0/10

A former Meituan product manager publicly criticized the company's organizational culture, pointing out that product roles have become passive, data is underutilized, and AI is applied superficially. These issues perpetuate inertia and stifle innovation. The insider critique highlights systemic barriers that can prevent tech giants from innovating, despite having vast data and resources. It serves as a cautionary tale for companies navigating digital transformation. The author, a former junior product manager for Meituan's in-store dining, specifies that staff must guess leadership's intentions, business decisions rely on manual experience despite abundant transaction data, and AI is touted as a cure-all but only replaces grunt work without redefining problems.

telegram · zaihuapd · Jun 22, 11:40

**Background**: Meituan is a dominant Chinese platform for local services like food delivery and in-store dining. It historically succeeded through aggressive execution and cost efficiency, but as the market matures, it requires more innovative approaches. The author’s criticism reflects a common struggle: large companies often fall into path dependency, relying on past strengths rather than fostering new ideas.

**Tags**: `#Meituan`, `#organizational culture`, `#product management`, `#innovation barriers`, `#AI implementation`

---