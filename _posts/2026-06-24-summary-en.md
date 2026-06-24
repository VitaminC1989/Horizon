---
layout: default
title: "Horizon Summary: 2026-06-24 (EN)"
date: 2026-06-24
lang: en
---

> From 73 items, 24 important content pieces were selected

---

1. [Prompt Injection as Role Confusion](#item-1) ⭐️ 9.0/10
2. [DeepSeek Raises $7.4B at $60B Valuation, Founder Invests $3B](#item-2) ⭐️ 9.0/10
3. [China's LineShine Reclaims TOP500 Top Spot After 8 Years](#item-3) ⭐️ 9.0/10
4. [Vulnerability Reports Lose Special Status Amid LLM Spam](#item-4) ⭐️ 8.0/10
5. [FUTO Swipe: A New Privacy-Focused Swipe Typing Model](#item-5) ⭐️ 8.0/10
6. [Swift Package Index Joins Apple](#item-6) ⭐️ 8.0/10
7. [WYSIWYG TikZ Editor for LaTeX Figures](#item-7) ⭐️ 8.0/10
8. [The Coming Loop: AI-Assisted Coding Erodes Human Understanding](#item-8) ⭐️ 8.0/10
9. [Vitamin D's Worthlessness Exaggerated, Balanced Analysis Finds](#item-9) ⭐️ 8.0/10
10. [AI Security Is Not Just Cybersecurity: Zico Kolter & Matt Fredrikson Discuss](#item-10) ⭐️ 8.0/10
11. [GPT-5 Pro Helps Solve 3-Year Immunological T-Cell Mystery](#item-11) ⭐️ 8.0/10
12. [Mimo 2.5 Excels at Large Context on Dual RTX Pro 6000](#item-12) ⭐️ 8.0/10
13. [LLM Medical Scribe Benchmark: Omissions Outnumber Hallucinations](#item-13) ⭐️ 8.0/10
14. [Samsung Unveils UFS 5.0: Up to 10.8 GB/s for On-Device AI, Q4 Mass Production](#item-14) ⭐️ 8.0/10
15. [Critical FFmpeg MagicYUV Vulnerability Allows Remote Code Execution](#item-15) ⭐️ 8.0/10
16. [Elden Ring's Low-Tech AI: Behavior Trees in Action](#item-16) ⭐️ 7.0/10
17. [Google Fires Engineer Over Unauthorized Workspace CLI](#item-17) ⭐️ 7.0/10
18. [Datasette 1.0a35 Adds Create and Alter Table UIs and APIs](#item-18) ⭐️ 7.0/10
19. [GLM-5.2 Marks a Step Change for Open-Source AI Agents](#item-19) ⭐️ 7.0/10
20. [OpenAI Joins Appia Foundation for Shared AI Safety Standards](#item-20) ⭐️ 7.0/10
21. [OpenAI Launches Daybreak: AI Security Suite with Codex and GPT-5.5-Cyber](#item-21) ⭐️ 7.0/10
22. [7 Chinese companies shipping H100/H200-class AI chips](#item-22) ⭐️ 7.0/10
23. [US Humanoid Robots Rely on Chinese Components](#item-23) ⭐️ 7.0/10
24. [LastPass Customer Support Data Stolen in Klue Breach](#item-24) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Prompt Injection as Role Confusion](https://simonwillison.net/2026/Jun/22/prompt-injection-as-role-confusion/#atom-everything) ⭐️ 9.0/10

A new paper by Charles Ye, Jasmine Cui, and Dylan Hadfield-Menell shows that LLMs rely on text style rather than explicit role tags to determine text origin, making prompt injection jailbreaks trivial and revealing a fundamental flaw in current safety mechanisms. This finding undermines the entire approach of using role-based tags to secure LLM applications, showing that attackers can craft jailbreaks by mimicking the style of privileged instructions, and that defense will remain a 'whack-a-mole' game until models achieve genuine role perception. The paper introduces 'destyling' as a technique to rewrite prompt injections to not match expected role styles, which caused average attack success to drop from 61% to 10%, highlighting that models classify based on stylistic features rather than semantic content.

rss · Simon Willison · Jun 22, 23:59

**Background**: Prompt injection is a security attack where an attacker crafts input to an LLM that contains hidden instructions, causing the model to perform unintended actions. Jailbreaking is a type of prompt injection aimed at bypassing safety filters. Many LLM APIs and chat interfaces use special tokens like <system> and <user> to separate trusted system prompts from user-provided data, but this research indicates that models cannot reliably distinguish these based on content alone.

<details><summary>References</summary>
<ul>
<li><a href="https://role-confusion.github.io/">Prompt Injection as Role Confusion</a></li>
<li><a href="https://www.ibm.com/think/topics/prompt-injection">What Is a Prompt Injection Attack? | IBM</a></li>

</ul>
</details>

**Tags**: `#prompt-injection`, `#AI-safety`, `#LLM`, `#security`, `#research`

---

<a id="item-2"></a>
## [DeepSeek Raises $7.4B at $60B Valuation, Founder Invests $3B](https://www.reddit.com/r/LocalLLaMA/comments/1ucwyes/deepseek_raises_74b_usd_at_60b_valuation/) ⭐️ 9.0/10

DeepSeek has raised $7.4 billion in a new funding round at a $60 billion valuation, with founder Liang Wenfeng personally investing $3 billion. This massive funding round signals strong investor confidence in open-source AI, potentially accelerating DeepSeek's challenge to US-based AI giants and reshaping the competitive landscape. Founder Liang Wenfeng committed $3 billion of his own capital, showing deep personal conviction. DeepSeek's models achieve high performance at a fraction of the cost of competitors like GPT-4, using techniques such as mixture of experts.

reddit · r/LocalLLaMA · /u/FullOf_Bad_Ideas · Jun 22, 21:03

**Background**: DeepSeek is a Chinese AI company founded in 2023 by Liang Wenfeng, co-founder of hedge fund High-Flyer. It gained fame in January 2025 with the DeepSeek-R1 model, which rivaled OpenAI's GPT-4 while reportedly costing less than $6 million to train versus GPT-4's $100 million. Its open-weight models are released under the MIT license, boosting the open-source LLM ecosystem.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek">DeepSeek</a></li>
<li><a href="https://www.bbc.com/future/article/20250131-what-does-deepseeks-new-app-mean-for-the-future-of-ai">DeepSeek : What lies under the bonnet of the new AI chatbot?</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Funding`, `#DeepSeek`, `#LLM`, `#Open-source`

---

<a id="item-3"></a>
## [China's LineShine Reclaims TOP500 Top Spot After 8 Years](https://news.mydrivers.com/1/1131/1131573.htm) ⭐️ 9.0/10

On June 23, the TOP500 list announced that China's 'LineShine' (灵晟) supercomputer, deployed at the National Supercomputing Center in Shenzhen, ranked first with a LINPACK performance of 2.198 ExaFLOPS, becoming the world's first pure-CPU system to exceed 2 ExaFLOPS. This achievement marks a significant milestone in China's indigenous supercomputing efforts, demonstrating fully autonomous chip design and pure-CPU architecture that also led the HPCG benchmark and ranked 4th in HPL-MxP mixed-precision test, showcasing comprehensive HPC capabilities. LineShine is built on the domestic Lingkun platform and LX2 processors, featuring 20,480 nodes each with two ARMv9-based LX2 processors (304 cores each), using only CPU cores with no GPUs, supporting SVE/SME vector extensions, and achieving 60.3 TFLOPS (FP64) per processor. It uses a high-speed interconnect with 1.6 Tb/s per node.

telegram · zaihuapd · Jun 23, 15:30

**Background**: The TOP500 list ranks the world's most powerful supercomputers based on the HPL benchmark (LINPACK), which solves dense linear equations. ExaFLOPS (10^18 floating-point operations per second) is a key milestone in high-performance computing. HPCG is a complementary benchmark that stresses memory bandwidth and communication, while HPL-MxP tests mixed-precision performance crucial for AI workloads. China last topped the list in 2017 with Sunway TaihuLight.

<details><summary>References</summary>
<ul>
<li><a href="https://www.ijiwei.com/n/1037138">中国推出无GPU超算“灵晟”，搭载245万个国产CPU核心 - 集微网</a></li>
<li><a href="https://www.sigmaintell.com/news.php?cid=29&id=23918">国产全CPU超算发布：2 Exaflops算力 - 群智咨询-Sigmaintell</a></li>

</ul>
</details>

**Tags**: `#supercomputing`, `#TOP500`, `#exascale`, `#HPC`, `#China`

---

<a id="item-4"></a>
## [Vulnerability Reports Lose Special Status Amid LLM Spam](https://words.filippo.io/vuln-reports/) ⭐️ 8.0/10

Filippo Valsorda argues that vulnerability reports are no longer special for open source maintainers, as they are inundated with low-quality, LLM-generated spam and extortion attempts, forcing a shift in maintainer mindset. This shift impacts the security posture of open source projects; maintainers may overlook critical vulnerabilities amidst the noise, while genuine researchers face delays or legal threats, undermining community trust and software safety. LLM-generated reports often contain hallucinated vulnerabilities or trivial issues like CSS bugs, while extortion attempts mimic serious reports. Maintainers are advised to treat vulnerability reports like any other issue, not as obligations.

hackernews · goranmoomin · Jun 23, 23:42 · [Discussion](https://news.ycombinator.com/item?id=48653216)

**Background**: Traditionally, vulnerability reports in open source were treated with high priority and confidentiality, as they could indicate serious security flaws. However, recent advances in large language models (LLMs) have enabled automated generation of plausible-sounding but often false or low-quality vulnerability reports. Bug bounty programs and open-source projects alike are receiving a surge of such AI-generated submissions, blurring the line between genuine security research and noise. This deluge is causing maintainer burnout and forcing a reevaluation of how vulnerability reports should be handled.

<details><summary>References</summary>
<ul>
<li><a href="https://techcrunch.com/2025/07/24/ai-slop-and-fake-reports-are-exhausting-some-security-bug-bounties/">AI slop and fake reports are coming for your bug bounty programs | TechCrunch</a></li>

</ul>
</details>

**Discussion**: HN commenters widely confirm the spam problem, with one noting 2-5 unsolicited reports per week, half from LLMs. Some remain hopeful that as LLMs improve at fixing bugs, the noise will subside; others emphasize the need for engineering solutions like memory-safe languages rather than relying on vulnerability reports.

**Tags**: `#security`, `#open-source`, `#vulnerability-reports`, `#maintainer-burnout`, `#LLM-spam`

---

<a id="item-5"></a>
## [FUTO Swipe: A New Privacy-Focused Swipe Typing Model](https://swipe.futo.tech/) ⭐️ 8.0/10

FUTO just introduced a new swipe typing model, trained with community input, that significantly improves accuracy and responsiveness, rivaling Google's keyboard while keeping privacy intact. This advancement provides a tangible, privacy-respecting alternative to proprietary keyboard apps, reducing reliance on data-hungry tech giants and empowering users with a high-quality open-source option. The inference library is released under GPLv3, while the model itself is under the FUTO Model License; the Android keyboard combines both, but some users report minor issues like random capitalization and subpar contextual prediction.

hackernews · futohq · Jun 23, 17:50 · [Discussion](https://news.ycombinator.com/item?id=48648619)

**Background**: Swipe typing allows users to input words by sliding a finger over letters without lifting, offering speed and one-handed use. Google's Gboard popularized it, but its closed-source nature raises privacy concerns. FUTO is an organization that develops open-source keyboard and voice input tools focused on privacy.

<details><summary>References</summary>
<ul>
<li><a href="https://swipe.futo.tech/">FUTO Swipe</a></li>
<li><a href="https://swipe.futo.org/">FUTO Keyboard Swipe Training</a></li>

</ul>
</details>

**Discussion**: Overall, comments are enthusiastic; long-time users praise the jump in swipe quality, with one saying it feels as good as Gboard. However, there are concerns about licensing (FUTO License vs. GPLv3), some functionality gaps like incorrect apostrophe handling, and ideas for a dedicated swipe-optimized keyboard layout. One user notes that Nintype on iOS set a high bar that hasn't been matched.

**Tags**: `#keyboard`, `#swipe-typing`, `#privacy`, `#mobile`, `#input-methods`

---

<a id="item-6"></a>
## [Swift Package Index Joins Apple](https://swiftpackageindex.com/blog/swift-package-index-joins-apple) ⭐️ 8.0/10

The Swift Package Index, a community-run central discovery site for Swift packages, has joined Apple, transitioning from an independent project to an Apple-owned service. This marks a major shift in Swift ecosystem tooling, as Apple now directly controls a key developer resource, potentially improving integration but raising concerns about Apple's influence on open-source package discovery and possible future regulation. The index currently tracks metadata from over 11,000 packages and was previously open-source and community-led. The blog post hints at developer identity as a future direction, suggesting deeper integration with Apple ID, though specific terms of the deal remain undisclosed.

hackernews · JDevlieghere · Jun 23, 18:00 · [Discussion](https://news.ycombinator.com/item?id=48648779)

**Background**: Swift Package Manager (SPM) is Apple's tool for managing Swift project dependencies. The Swift Package Index (SPI) was a community-built website that indexed packages compatible with SPM, offering search and quality information. It became a popular resource for discovering and evaluating Swift packages. Apple now owns and will continue to operate the service.

<details><summary>References</summary>
<ul>
<li><a href="https://swiftpackageindex.com/">Swift Package Index</a></li>
<li><a href="https://www.swift.org/packages/">Packages | Swift.org</a></li>
<li><a href="https://github.com/SwiftPackageIndex">Swift Package Index · GitHub</a></li>

</ul>
</details>

**Discussion**: Community sentiment is mixed: many congratulate the SPI creators on their success, while others express concern over Apple's open-source track record and the potential for future package regulation. Some see an opportunity to build alternatives, reflecting cautious optimism combined with worries about Apple's influence.

**Tags**: `#swift`, `#apple`, `#package-management`, `#open-source`, `#developer-tools`

---

<a id="item-7"></a>
## [WYSIWYG TikZ Editor for LaTeX Figures](https://tikz.dev/editor/) ⭐️ 8.0/10

A new open-source WYSIWYG editor for TikZ allows users to visually drag and resize elements while the LaTeX source code updates in real time. Built almost entirely with the Codex AI coding agent, it parses TikZ code to map objects to source locations for precise editing. It bridges visual and code-based editing for academic figures, potentially saving researchers hours of manual coordinate tweaking and recompilation. This could make TikZ, a staple in scientific publishing, more accessible to a wider audience. The editor reimplements large parts of TikZ, including a LaTeX hyphenation algorithm for multiline nodes, and includes format converters for SVG, pptx, and ipe. However, generated code uses absolute coordinates, which some users find suboptimal compared to relative positioning.

hackernews · DominikPeters · Jun 23, 14:24 · [Discussion](https://news.ycombinator.com/item?id=48645437)

**Background**: TikZ is a LaTeX package for programmatically creating vector graphics, widely used in academic papers. Unlike drawing tools, it requires manual coding with commands like \draw, making precise adjustments tedious. A WYSIWYG editor simplifies this by enabling visual design while keeping the source code editable.

<details><summary>References</summary>
<ul>
<li><a href="https://www.overleaf.com/learn/latex/TikZ_package">TikZ package - Overleaf, Online LaTeX Editor</a></li>

</ul>
</details>

**Discussion**: Comments praised the UI and concept but criticized the reliance on absolute coordinates in generated code. Alternatives like Inkscape with SVG+pdf_tex or AI-assisted TikZ code generation were discussed. The creator shared that the project used 700M tokens via Codex, costing only $500 in subscriptions.

**Tags**: `#tikz`, `#latex`, `#wysiwyg`, `#visual-editor`, `#academic-tools`

---

<a id="item-8"></a>
## [The Coming Loop: AI-Assisted Coding Erodes Human Understanding](https://lucumr.pocoo.org/2026/6/23/the-coming-loop/) ⭐️ 8.0/10

Armin Ronacher warns of a self-reinforcing loop where AI-assisted coding tools cause developers to merge code they cannot fully explain. This erodes human understanding and creates unmaintainable codebases that may eventually require machine co-maintenance. This trend threatens the long-term sustainability of software development, potentially causing widespread atrophy of deep programming skills and leaving behind codebases that are impossible for humans to maintain independently, which could undermine the reliability of critical systems. LLMs excel at completing tasks but lack aesthetic judgment, often producing functional but poorly structured code. The loop intensifies when developers also use AI for code review and summarization, further reducing human engagement and understanding.

hackernews · ingve · Jun 23, 11:06 · [Discussion](https://news.ycombinator.com/item?id=48643180)

**Background**: AI-assisted coding uses large language models (LLMs) like GPT-4 to generate, review, or explain code. Software maintainability refers to how easily code can be understood and modified. The 'coming loop' describes a vicious cycle where increased AI reliance reduces developer understanding, which then forces even more AI reliance, jeopardizing the codebase's long-term health.

**Discussion**: Community comments largely agree, noting that AI causes developers to merge unexplainable code and rely on AI for communication. Commenters stress that clear specifications are crucial but taxing, and that LLMs lack 'taste,' yielding ugly yet functional code. One user argues that the essential iteration for deep learning cannot be accelerated by AI, reinforcing concerns about superficial knowledge.

**Tags**: `#llm`, `#software-engineering`, `#ai-coding`, `#maintainability`, `#human-ai-interaction`

---

<a id="item-9"></a>
## [Vitamin D's Worthlessness Exaggerated, Balanced Analysis Finds](https://dynomight.net/vitamin-d/) ⭐️ 8.0/10

A new balanced analysis of vitamin D research clarifies that supplementation offers modest benefits primarily for those who are severely deficient, while critiquing exaggerated health claims and exposing statistical flaws in deficiency studies. This analysis matters because vitamin D supplementation is widely promoted for various health benefits, yet the evidence is often overstated; it helps set realistic expectations and could influence public health guidelines. Key details: The strongest evidence supports vitamin D for severely deficient individuals; many studies have methodological issues such as seasonal sampling bias and misinterpretation of confidence intervals. Some community members note that supplementing without measuring blood levels and combining with K2 may affect outcomes.

hackernews · surprisetalk · Jun 23, 16:30 · [Discussion](https://news.ycombinator.com/item?id=48647486)

**Background**: Vitamin D, often considered a vitamin but actually a hormone precursor, is essential for bone health and calcium regulation. Observational studies have linked low vitamin D levels to numerous health problems, prompting widespread supplementation. However, randomized controlled trials often show limited benefits, leading to debate over its true efficacy and optimal dosing.

**Discussion**: Community discussion appreciates the article's balanced approach, with users highlighting specific methodological issues in studies (e.g., NHANES seasonal bias), the need for trials combining D3 with K2 and measuring serum levels, and a historical note that current recommendations may be based on statistical errors. Some debate whether vitamin D is truly a vitamin or a hormone, reflecting ongoing complexity in the field.

**Tags**: `#vitamin-d`, `#health`, `#evidence-based-medicine`, `#statistics`, `#science-communication`

---

<a id="item-10"></a>
## [AI Security Is Not Just Cybersecurity: Zico Kolter & Matt Fredrikson Discuss](https://www.latent.space/p/gray-swan) ⭐️ 8.0/10

In this Latent Space podcast, OpenAI board member Zico Kolter and Gray Swan CEO Matt Fredrikson discuss AI security, asserting that it is fundamentally different from traditional cybersecurity. They share insights from their pioneering work on indirect prompt injections and real-world AI red-teaming. As AI is increasingly deployed in critical systems, understanding its unique security challenges is vital to prevent novel exploits. This expert discussion informs developers and companies on the need for specialized red-teaming to safeguard AI applications. The conversation references the 'Indirect Prompt Injection' paper and Anthropic's red teaming tool Shade. It emphasizes that AI security must account for emergent model behaviors stemming from training data and architecture, which traditional cybersecurity does not address.

rss · Latent Space · Jun 22, 21:06

**Background**: AI red-teaming is the systematic probing of AI models to find vulnerabilities, akin to adversarial testing in cybersecurity. Indirect prompt injection is an attack where malicious instructions are embedded in external content that an AI model later processes, causing unintended behavior. Gray Swan is a company spun out of Carnegie Mellon University, offering specialized AI red-teaming services and founded by researchers who discovered many AI security flaws. The podcast appears on Latent Space, a platform for in-depth AI engineering discussions.

<details><summary>References</summary>
<ul>
<li><a href="https://www.latent.space/p/gray-swan">Red-Teaming after Mythos — Zico Kolter & Matt Fredrikson, Gray Swan</a></li>
<li><a href="https://www.grayswan.ai/solutions/ai-red-teaming">AI Red-Teaming as a Service</a></li>
<li><a href="https://www.grayswan.ai/about">About Gray Swan</a></li>

</ul>
</details>

**Tags**: `#AI security`, `#red-teaming`, `#AI safety`, `#podcast`, `#Latent Space`

---

<a id="item-11"></a>
## [GPT-5 Pro Helps Solve 3-Year Immunological T-Cell Mystery](https://openai.com/index/gpt-5-immunology-mystery) ⭐️ 8.0/10

GPT-5 Pro, an advanced AI model from OpenAI, assisted immunologist Derya Unutmaz in resolving a three-year-old mystery about T cell behavior, offering new insights into cancer and autoimmune disease research. This breakthrough demonstrates AI's potential to accelerate scientific discovery by unraveling complex biological puzzles, which could lead to novel therapies for cancer and autoimmune conditions. The exact nature of the mystery and how GPT-5 Pro contributed have not been publicly detailed, and the findings have yet to undergo peer review.

rss · OpenAI Blog · Jun 23, 17:00

**Background**: GPT-5 Pro is a reasoning-enhanced variant of OpenAI's GPT-5 large language model, launched in August 2025. T cells are a central part of the adaptive immune system, responsible for recognizing and eliminating infected or cancerous cells. Abnormal T cell behavior can cause autoimmune diseases or allow cancer to evade immune attack, making their study crucial for developing immunotherapies.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GPT-5_Pro">GPT-5 Pro</a></li>
<li><a href="https://openai.com/index/introducing-gpt-5/">Introducing GPT - 5 | OpenAI</a></li>
<li><a href="https://www.sanfoundry.com/immunology-questions-answers-adaptive-immune-cell-behavior/">Immunology Questions and Answers - Adaptive Immune Cell Behavior</a></li>

</ul>
</details>

**Tags**: `#AI`, `#immunology`, `#GPT-5`, `#cancer research`, `#autoimmune disease`

---

<a id="item-12"></a>
## [Mimo 2.5 Excels at Large Context on Dual RTX Pro 6000](https://www.reddit.com/r/LocalLLaMA/comments/1udwabh/mimo_25_is_fast_at_large_context_dual_rtx_pro_6000/) ⭐️ 8.0/10

A user reports that Mimo 2.5 maintains high throughput at large context lengths (up to 150k+ tokens) on dual RTX Pro 6000 GPUs, thanks to its sliding-window attention, while competitors MiniMax M3 and DeepSeek V4 suffer major slowdowns due to missing custom GPU kernels for consumer Blackwell hardware. This finding is significant for local LLM deployment on high-end consumer GPUs, showing that model architecture choices (sliding-window vs custom attention kernels) drastically affect real-world performance, and that newer models may not be practical without proper kernel support. Mimo 2.5 uses a 5-to-1 local/global sliding-window attention similar to Gemma 3; MiniMax M3 falls back to dense attention and DeepSeek V4's ops drop to CPU, reducing speed to 14 t/s. Step 3.7 Flash uses a 3-to-1 hybrid and achieves ~40 t/s at 178k context. SGLang and vLLM with NVFP4 did not resolve the slowdown.

reddit · r/LocalLLaMA · /u/xquarx · Jun 23, 22:55

**Background**: Sliding-window attention is a sparse attention variant where each token attends only to a fixed-size window of recent tokens instead of all previous tokens, drastically reducing compute and memory at long context. GGUF is a file format for running LLMs on consumer hardware with CPU/GPU inference, and missing custom GPU kernels can cause fallback to slower implementations. Blackwell is Nvidia's latest GPU architecture; consumer cards like RTX 5090/RTX PRO 6000 lack the datacenter-optimized kernels that some models require.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Attention_Is_All_You_Need">Attention Is All You Need - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/GGUF">GGUF - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/GeForce_RTX_50_series">GeForce RTX 50 series - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#llm-inference`, `#attention-mechanisms`, `#gpu-performance`, `#local-llm`

---

<a id="item-13"></a>
## [LLM Medical Scribe Benchmark: Omissions Outnumber Hallucinations](https://www.reddit.com/r/LocalLLaMA/comments/1udlrmf/i_benchmarked_8_llms_for_medical_scribing/) ⭐️ 8.0/10

A benchmark of 8 frontier LLMs on medical scribing using 300 synthetic doctor-patient dialogues found that models omitted clinically relevant safety facts 520 times while producing only 12 high-impact hallucinations, highlighting omissions as a far more common error. This finding shifts the medical AI safety focus from hallucinations to omissions, which can directly affect patient safety, and suggests that even strong models need omission-detection wrappers before clinical deployment. Claude Opus had the fewest omissions, GPT-5.4-mini offered best value, DeepSeek combined strong prose with many omissions, and Kimi had zero hallucinations; a follow-up wrapper approach recovered omissions and flagged unsupported claims, making cheap models like DeepSeek safer.

reddit · r/LocalLLaMA · /u/MajesticAd2862 · Jun 23, 16:20

**Background**: SOAP notes (Subjective, Objective, Assessment, Plan) are a standard medical documentation format. Medical scribing AI transcribes clinician-patient conversations into notes. Safety concerns typically center on hallucinations (fabricated information), but omitting clinically relevant details can also harm care. 'Frontier models' refer to the most advanced LLMs available.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/SOAP_note">SOAP note - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek">DeepSeek - Wikipedia</a></li>
<li><a href="https://www.datacamp.com/blog/frontier-models">Frontier Models Explained: What Defines the Cutting Edge of AI</a></li>

</ul>
</details>

**Tags**: `#LLM evaluation`, `#medical AI`, `#AI safety`, `#omissions`, `#benchmark`

---

<a id="item-14"></a>
## [Samsung Unveils UFS 5.0: Up to 10.8 GB/s for On-Device AI, Q4 Mass Production](https://news.samsung.com/global/samsung-unveils-industrys-fastest-ufs-5-0-solution-for-next-gen-on-device-ai-applications) ⭐️ 8.0/10

Samsung announced the industry's fastest UFS 5.0 storage solution, based on the latest JEDEC standard, featuring sequential read speeds up to 10.8 GB/s and write speeds up to 9.5 GB/s, over 40% better power efficiency, and a 16.7% smaller package than UFS 4.1; mass production is planned for Q4 this year. This advance doubles storage speed while improving power efficiency, enabling faster on-device AI processing, real-time data handling in flagship smartphones, XR headsets, and AI wearables, and setting a new benchmark for mobile storage. The new UFS 5.0 achieves sequential read up to 10.8 GB/s and write up to 9.5 GB/s, with over 40% power efficiency gain and a 16.7% package size reduction compared to Samsung's UFS 4.1; capacities reach 1 TB, targeting premium mobile devices.

telegram · zaihuapd · Jun 23, 09:17

**Background**: UFS (Universal Flash Storage) is a mobile storage standard defined by JEDEC, widely used in smartphones and mobile devices. UFS 4.0 was introduced in 2022 with speeds up to 4.2 GB/s; UFS 4.1 followed with minor improvements. UFS 5.0 represents a major leap, doubling sequential read speeds and significantly reducing power consumption, which is critical for on-device AI applications that require rapid access to large models and real-time data processing.

<details><summary>References</summary>
<ul>
<li><a href="https://androidinsider.ru/zhelezo/chto-oznachaet-versiya-pamyati-ufs-v-smartfone-kakaya-ona-dolzhna-byt-i-pochemu-eto-vazhno.html">UFS 2.2, 3.1, 4.0 и 4.1: что это и какая память лучше</a></li>
<li><a href="https://www.mixvale.com.br/2026/04/17/galaxy-s27-ultra-se-ra-mat-bo-luu-tru-ufs-5-0-voi-toc-do-len-toi-108-gb-s-vi/">Galaxy S27 Ultra sẽ ra mắt bộ lưu trữ UFS 5 . 0 với tốc độ lên tới 10...</a></li>
<li><a href="https://en.wikipedia.org/wiki/JEDEC">JEDEC</a></li>

</ul>
</details>

**Tags**: `#UFS`, `#mobile storage`, `#Samsung`, `#on-device AI`, `#semiconductor`

---

<a id="item-15"></a>
## [Critical FFmpeg MagicYUV Vulnerability Allows Remote Code Execution](https://cybernews.com/security/critical-ffmpeg-vulnerability-enables-complete-compromise/) ⭐️ 8.0/10

A critical vulnerability (CVE-2026-8461) in FFmpeg's MagicYUV decoder allows remote code execution when processing malicious video files, affecting media players and devices. The bug, dubbed 'PixelSmash', has a CVSS score of 8.8 and is fixed in FFmpeg 8.1.2. Since FFmpeg is a foundational multimedia library used by countless applications and devices, this vulnerability could affect millions of users. Exploitation can occur through simple actions like playing a video or generating thumbnails, with no user interaction required beyond opening a file. The vulnerability resides in the MagicYUV decoder, a lossless video codec, and can be triggered even during automatic media library scanning. Attackers can achieve full system control with no visible traces, and mitigations include updating to FFmpeg 8.1.2 or disabling MagicYUV at compile time.

telegram · zaihuapd · Jun 23, 15:00

**Background**: FFmpeg is a widely-used open-source library for handling video, audio, and other multimedia files. MagicYUV is a lossless video codec known for high performance, often used for recording and post-production. The decoder is integrated into FFmpeg and thus into many applications like VLC, Kodi, and OBS.

<details><summary>References</summary>
<ul>
<li><a href="https://www.magicyuv.com/">MagicYUV – Lossless video codec</a></li>
<li><a href="https://ffmpeg.org/doxygen/5.1/magicyuv_8c.html">FFmpeg: libavcodec/ magicyuv .c File Reference</a></li>

</ul>
</details>

**Tags**: `#security`, `#vulnerability`, `#ffmpeg`, `#video`, `#cve`

---

<a id="item-16"></a>
## [Elden Ring's Low-Tech AI: Behavior Trees in Action](https://nega.tv/posts/low-tech-ai-of-elden-ring.html) ⭐️ 7.0/10

The article breaks down how Elden Ring uses behavior trees with a stack-based traversal to manage enemy AI, avoiding the need to loop from the root each frame. Community members note this is a standard but clever implementation detail. By explaining the inner workings of a major game's AI, this analysis demystifies how complex, adaptive behaviors emerge from relatively simple systems. It highlights the practical trade-offs in game AI design and sparks conversation about terminology in the era of large-scale AI models. The author claims the stack-based approach improves performance over traditional decision trees, but some commenters dispute this, noting that behavior trees can be compiled to bytecode and that many game scripting languages already evaluate syntax trees efficiently. The analysis may oversimplify the performance comparison.

hackernews · g0xA52A2A · Jun 23, 11:40 · [Discussion](https://news.ycombinator.com/item?id=48643489)

**Background**: Behavior trees are a hierarchical control structure used extensively in game AI to define agent behaviors. They consist of internal nodes (like sequences and selectors) that control flow, and leaf nodes that perform actions or conditions. FromSoftware's Elden Ring is renowned for its challenging enemies and intricate world design, making its AI a critical component of the player experience.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Behavior_tree_(artificial_intelligence,_robotics_and_control)">Behavior tree (artificial intelligence, robotics and control) - Wikipedia</a></li>
<li><a href="https://robohub.org/introduction-to-behavior-trees/">Introduction to behavior trees - Robohub</a></li>

</ul>
</details>

**Discussion**: Commenters largely agree that the system is a standard behavior tree, with one noting that the described stack-based loop is a common optimization. Anecdotes about FromSoftware's inscrutable NPC quests highlight the design's unique feel, while some express frustration over the term 'AI' being diluted by modern hype. Technical debate emerged over the claimed performance advantages, with skepticism about whether the approach is significantly faster than alternatives.

**Tags**: `#behavior trees`, `#game AI`, `#Elden Ring`, `#game development`, `#Hacker News`

---

<a id="item-17"></a>
## [Google Fires Engineer Over Unauthorized Workspace CLI](https://twitter.com/JPoehnelt/status/2069482265953087602) ⭐️ 7.0/10

Justin Poehnelt, a Google engineer, was fired after releasing a CLI tool for Google Workspace under the GitHub organization 'googleworkspace,' which appeared official, sparking controversy over proper open-source release procedures. This incident highlights the tension between corporate control and individual initiative in open-source, and raises questions about how companies manage unofficial projects that gain traction and could be mistaken for official products. The tool, called gws or @googleworkspace/cli, was written in Rust and distributed via npm, providing a unified interface for Google Workspace services. It was released without internal approval, and the GitHub organization name heightened the impression of official endorsement.

hackernews · justinwp · Jun 23, 18:13 · [Discussion](https://news.ycombinator.com/item?id=48649011)

**Background**: Google Workspace is a suite of cloud productivity tools including Gmail, Drive, and Docs. A CLI (command-line interface) allows developers to interact with services programmatically. Google has a history of encouraging employee side projects, but such projects must follow strict open-source release processes.

<details><summary>References</summary>
<ul>
<li><a href="https://grokipedia.com/page/Google_Workspace_CLI">Google Workspace CLI</a></li>
<li><a href="https://medium.com/ai-software-engineer/i-tested-new-google-workspace-cli-and-uncovered-the-hacks-you-should-know-9f4126105985">I Tested (New) Google Workspace CLI (And Uncovered The... | Medium</a></li>

</ul>
</details>

**Discussion**: Comments are divided: some criticized the engineer's poor judgment in using an official-looking organization, while others sympathized, blaming Google's bureaucracy. Some noted that even Google employees in the thread were critical, citing potential conflicts of interest. Others argued that the immediate popularity of the tool should have been a mitigating factor.

**Tags**: `#Open Source`, `#Google`, `#Corporate Policy`, `#CLI`, `#Developer Relations`

---

<a id="item-18"></a>
## [Datasette 1.0a35 Adds Create and Alter Table UIs and APIs](https://simonwillison.net/2026/Jun/23/datasette/#atom-everything) ⭐️ 7.0/10

Datasette 1.0a35 introduces new 'Create table' and 'Alter table' web interfaces and corresponding JSON APIs, allowing users to manage database tables directly from the Datasette UI or via API calls. It also includes new documentation for template context variables. These features transform Datasette from a read-only data exploration tool into a more complete database management interface, enabling schema changes without leaving the tool. This can streamline workflows for developers, data analysts, and teams using Datasette to publish data. The create table interface supports defining columns, primary keys, custom types, NOT NULL constraints, defaults, and foreign keys. The alter table interface allows adding, renaming, reordering, and dropping columns, and changing table names. The template context documentation is auto-generated from code and tested against actual page contexts, ensuring stability.

rss · Simon Willison · Jun 23, 21:34

**Background**: Datasette is an open-source tool developed by Simon Willison for exploring, analyzing, and publishing SQLite databases. It provides a dynamic web interface and a read-only JSON API for querying data. The 1.0a35 alpha release marks a significant step toward a stable 1.0 version, with new write capabilities that extend its functionality beyond read-only access.

**Tags**: `#datasette`, `#sqlite`, `#data-exploration`, `#API`, `#release`

---

<a id="item-19"></a>
## [GLM-5.2 Marks a Step Change for Open-Source AI Agents](https://www.interconnects.ai/p/glm-52-is-the-step-change-for-open) ⭐️ 7.0/10

GLM-5.2, the latest open-source large language model from Chinese AI company Z.ai (formerly Zhipu AI), achieves a breakthrough in long-horizon agentic tasks, significantly closing the gap with closed-source models like Opus 4.8 on the SWE-Marathon benchmark. It also introduces an improved multi-token prediction layer that boosts speculative decoding acceptance length by up to 20%. This release demonstrates that open-source models are rapidly approaching proprietary systems in complex agentic capabilities, potentially democratizing access to advanced AI agents for developers worldwide and intensifying competition, especially in China's AI market. On the SWE-Marathon benchmark—which evaluates ultra-long-horizon software engineering tasks—GLM-5.2 trails Opus 4.8 by only 13%, a very narrow margin for an open model. It is released under the permissive MIT License with no regional restrictions, enabling unrestricted use and modification.

rss · Interconnects · Jun 22, 14:52

**Background**: GLM (General Language Model) is a family of large language models developed by Z.ai, a leading Chinese AI company also known as one of the 'AI tigers'. The company was previously called Zhipu AI until its 2025 rebranding. Open-source AI agents are autonomous systems that can plan and execute multi-step tasks; they are a key frontier in AI development. The SWE-Marathon benchmark tests an agent's ability to handle complex, long-duration programming challenges like building compilers or production services.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GLM-5.2">GLM-5.2</a></li>
<li><a href="https://huggingface.co/zai-org/GLM-5.2">zai-org/ GLM - 5 . 2 · Hugging Face</a></li>
<li><a href="https://registry.ollama.ai/library/glm-5.2">GLM - 5 . 2 is Z.ai’s flagship model for the era of long-horizon tasks.</a></li>

</ul>
</details>

**Tags**: `#AI`, `#agents`, `#open-source`, `#GLM`, `#large language models`

---

<a id="item-20"></a>
## [OpenAI Joins Appia Foundation for Shared AI Safety Standards](https://openai.com/index/helping-build-shared-standards-for-advanced-ai) ⭐️ 7.0/10

OpenAI announced its participation in the Appia Foundation, a new international collaboration focused on developing shared safety practices and evaluation frameworks for advanced AI systems. This promotes global cooperation on AI safety and could establish industry-wide benchmarks that enhance trust and interoperability across the AI supply chain. The Appia Foundation was launched by the Linux Foundation under the Joint Development Foundation to create modular open-source specifications for AI conformity assessments.

rss · OpenAI Blog · Jun 23, 13:00

**Background**: The Appia Foundation is an initiative to build practical methods for verifying that AI systems meet consumer expectations throughout the supply chain. As advanced AI models are deployed globally, shared safety and evaluation standards are increasingly critical. OpenAI's involvement signals a shift from proprietary approaches toward industry-wide collaboration.

<details><summary>References</summary>
<ul>
<li><a href="https://appiafoundation.org/">Appia Foundation</a></li>
<li><a href="https://www.linuxfoundation.org/press/linux-foundation-launches-appia-foundation-to-establish-standardized-conformity-specifications-across-the-ai-value-chain">Linux Foundation Launches Appia Foundation to Establish...</a></li>

</ul>
</details>

**Tags**: `#AI safety`, `#standards`, `#governance`, `#OpenAI`, `#Appia Foundation`

---

<a id="item-21"></a>
## [OpenAI Launches Daybreak: AI Security Suite with Codex and GPT-5.5-Cyber](https://openai.com/index/daybreak-securing-the-world) ⭐️ 7.0/10

OpenAI unveiled Daybreak, a suite of AI-powered cybersecurity tools including Codex Security for agentic vulnerability analysis and GPT-5.5-Cyber, a specialized model for automating threat detection and patching at scale. This marks OpenAI's strategic entry into enterprise cybersecurity, potentially automating complex security tasks that currently require scarce human expertise and reshaping how organizations defend against threats. Codex Security connects to GitHub repositories for context-aware analysis, while GPT-5.5-Cyber shows competitive benchmark performance, but access to GPT-5.5-Cyber is currently limited to vetted defenders.

rss · OpenAI Blog · Jun 22, 10:00

**Background**: Traditional vulnerability detection uses static analysis and manual reviews, which are slow and error-prone. Daybreak leverages advanced language models and agentic AI to understand code semantics and automate the full remediation pipeline, representing a shift to AI-native security operations.

<details><summary>References</summary>
<ul>
<li><a href="https://www.i-scoop.eu/openai-daybreak/">OpenAI Daybreak wants to secure software</a></li>
<li><a href="https://wikiwayne.com/blog/openai-codex-security-tool-2026">OpenAI Codex Security Review: AI Vulnerability Scanner... | WikiWayne</a></li>
<li><a href="https://forums.theregister.com/forum/all/2026/05/01/openai_locks_gpt55cyber_behind_velvet/">OpenAI locks GPT-5.5-Cyber behind velvet rope despite slamming ...</a></li>

</ul>
</details>

**Tags**: `#AI security`, `#vulnerability detection`, `#OpenAI`, `#automated patching`, `#cybersecurity`

---

<a id="item-22"></a>
## [7 Chinese companies shipping H100/H200-class AI chips](https://www.reddit.com/r/LocalLLaMA/comments/1udkxde/7_chinese_companies_are_already_shipping/) ⭐️ 7.0/10

A Reddit user mapped seven Chinese companies currently shipping AI accelerators comparable to NVIDIA's H100 and H200, revealing that most of them recently went public and are advancing rapidly with next-gen designs. This signals China's growing domestic AI chip ecosystem, reducing reliance on NVIDIA and potentially reshaping the global AI hardware landscape amid ongoing export controls. The companies are described as 'three dragons' (Huawei, Alibaba, Baidu) and 'four snakes'; Huawei's Ascend 910D uses a 5nm process with FP8 support, while Alibaba's PG1 server packs 1.5 TB of VRAM for local frontier-model inference.

reddit · r/LocalLLaMA · /u/awfulalexey · Jun 23, 15:50

**Background**: NVIDIA's H100/H200 GPUs are restricted for export to China, leading to the H20 variant. China is fostering domestic AI models like Qwen, DeepSeek, and GLM, creating demand for local hardware. The 'three dragons and four snakes' framework categorizes China's AI chip players into tech giants and specialized startups.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Qwen">Qwen - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek">DeepSeek - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/GLM_(AI)">GLM (AI) - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#AI hardware`, `#Chinese tech`, `#GPU alternatives`, `#AI chips`, `#geopolitics`

---

<a id="item-23"></a>
## [US Humanoid Robots Rely on Chinese Components](https://t.me/zaihuapd/42129) ⭐️ 7.0/10

The Wall Street Journal reports that US humanoid robots increasingly use Chinese-made components like motors, joints, magnets, and sensors, with Disney’s Olaf robot incorporating Unitree parts and Tesla collaborating with Chinese suppliers for Optimus. China launched 28 humanoid models in 2025, nearly triple the US count, and its supply chain can cut manufacturing costs by up to two-thirds. This dependency exposes a critical vulnerability in the US robotics supply chain, raising national security and competitiveness concerns amid US-China tensions. It also highlights China’s cost advantage, which could accelerate humanoid robot adoption but may trigger regulatory scrutiny and supply disruptions. Morgan Stanley estimates that Chinese supply chains can reduce manufacturing costs by up to two-thirds. US lawmakers have proposed a bill to assess American robotics competitiveness and supply chain risks, while China introduced 28 humanoid robot models in 2025, far outpacing US output.

telegram · zaihuapd · Jun 23, 07:47

**Background**: Humanoid robots like Tesla’s Optimus and Unitree’s G1 are designed for general-purpose tasks, requiring precision motors, joints, and sensors. China has become a dominant manufacturer of these components, leveraging its mature electronics supply chain for significant cost benefits. Ongoing US-China trade disputes and export controls on advanced technologies have heightened concerns about over-reliance on foreign-made critical parts.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Optimus_(robot)">Optimus ( robot ) - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Unitree_Robotics">Unitree Robotics - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#robotics`, `#supply-chain`, `#US-China-trade`, `#humanoid-robots`, `#manufacturing`

---

<a id="item-24"></a>
## [LastPass Customer Support Data Stolen in Klue Breach](https://techcrunch.com/2026/06/23/password-manager-maker-lastpass-says-hackers-stole-customer-support-case-data-during-klue-breach/) ⭐️ 7.0/10

Hackers breached LastPass partner Klue and exfiltrated customer support case data and personal details including names, contact information, and support records. LastPass confirmed its own infrastructure and password vaults remain secure. This breach underscores the persistent supply chain risks for widely used services, especially after LastPass's 2022 incident where encrypted vaults were stolen. It affects over 33 million users and could lead to phishing and social engineering attacks. The Icarus ransomware group claimed the Klue breach and threatened to publish the stolen data. Klue discovered the intrusion on June 12, and the exposed data does not include passwords or vault contents.

telegram · zaihuapd · Jun 24, 00:49

**Background**: LastPass is a password management service with over 33 million users and 1.6 million paying customers. In 2022, attackers stole encrypted password vaults in a serious breach. The recent incident involves Klue, a third-party vendor used for customer support data, demonstrating how attackers target partners to access customer information indirectly.

**Tags**: `#cybersecurity`, `#data breach`, `#password manager`, `#third-party risk`, `#LastPass`

---