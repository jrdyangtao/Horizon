---
layout: default
title: "Horizon Summary: 2026-07-16 (EN)"
date: 2026-07-16
lang: en
---

> From 74 items, 35 important content pieces were selected

---

1. [Moonshot AI Releases Kimi K3, a Frontier Open-Weight Model](#item-1) ⭐️ 9.0/10
2. [Claude web_fetch prompt injection leaks private data](#item-2) ⭐️ 9.0/10
3. [Japan to Buy 27,500 Nvidia Rubin Chips for Robot Sovereign AI](#item-3) ⭐️ 9.0/10
4. [Rust-to-Zig Rewrite: Progress and Pitfalls](#item-4) ⭐️ 8.0/10
5. [GPT-5.6/Codex Bug Can Delete Files Without Sandboxing](#item-5) ⭐️ 8.0/10
6. [Inkling: Open-weights multimodal MoE model from Thinking Machines Lab](#item-6) ⭐️ 8.0/10
7. [Linus Torvalds Declares Linux Not Anti-AI](#item-7) ⭐️ 8.0/10
8. [xAI open-sources Grok Build after privacy backlash](#item-8) ⭐️ 8.0/10
9. [Lobste.rs Migrates from MariaDB to SQLite](#item-9) ⭐️ 8.0/10
10. [AI Weekly Issue #514: 159 Real AI Deployments Library Released](#item-10) ⭐️ 8.0/10
11. [ExTernD: Ternary Decomposition for Accurate LLM Quantization](#item-11) ⭐️ 8.0/10
12. [PnP-CoSMo: Plug-and-Play Multi-Contrast MRI Reconstruction](#item-12) ⭐️ 8.0/10
13. [All Major Robotics Papers Ranked on Papers with Code](#item-13) ⭐️ 8.0/10
14. [xAI Sues User for Generating Child Abuse Deepfakes with Grok](#item-14) ⭐️ 8.0/10
15. [CNKI to Remove Papers Listing AI as Authors](#item-15) ⭐️ 8.0/10
16. [US Launches 337 Investigation on DRAM Devices Targeting Samsung, Google, Nvidia](#item-16) ⭐️ 8.0/10
17. [TSMC Invests $100B More in US, Q2 Profit Surges 77%](#item-17) ⭐️ 8.0/10
18. [1Password's Claude Integration Lets AI Log In Without Seeing Passwords](#item-18) ⭐️ 8.0/10
19. [Microsoft Comic Chat open-sourced](#item-19) ⭐️ 7.0/10
20. [OnePlus stops new product launches in Europe and North America](#item-20) ⭐️ 7.0/10
21. [GOES-19 weather satellite enters Safe Hold mode](#item-21) ⭐️ 7.0/10
22. [The Lost Joy of Music Piracy](#item-22) ⭐️ 7.0/10
23. [Sony Deletes Purchased Movies from User Accounts Again](#item-23) ⭐️ 7.0/10
24. [QLoRA default learning rate 2e-4 criticized for small datasets](#item-24) ⭐️ 7.0/10
25. [Seeking Critical Views on JEPA for Robot Learning](#item-25) ⭐️ 7.0/10
26. [Disentangling a Convolutional Neuron via Hadamard Product](#item-26) ⭐️ 7.0/10
27. [170x PyTorch slowdown on T4 vs A100 baffles ML engineer](#item-27) ⭐️ 7.0/10
28. [China's CXMT to Nearly Match Micron DRAM Capacity by 2026](#item-28) ⭐️ 7.0/10
29. [EU Draft Requires Google to Open Android AI Assistant Access](#item-29) ⭐️ 7.0/10
30. [Building PlanetScale from Scratch: Incomplete Replication](#item-30) ⭐️ 6.0/10
31. [Ente Publishes Revenue Data, But Critics Question Full Transparency](#item-31) ⭐️ 6.0/10
32. [Simon Willison ports Grok CLI Mermaid renderer to WebAssembly](#item-32) ⭐️ 6.0/10
33. [Should AI Memory Focus on Reasoning Patterns Over Facts?](#item-33) ⭐️ 6.0/10
34. [First RTCA Workshop at NeurIPS 2026 on Real-Time Multimodal Agents](#item-34) ⭐️ 6.0/10
35. [Apple Rumored to Launch Smart Home Hub, New Apple TV, HomePod in Fall](#item-35) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Moonshot AI Releases Kimi K3, a Frontier Open-Weight Model](https://www.kimi.com/en) ⭐️ 9.0/10

Moonshot AI has launched Kimi K3, a 2.8-trillion-parameter open-weight model with a 1M-token context window, claiming performance second only to Claude Fable 5 and GPT-5.6 Sol. The model weights are scheduled for release by July 27, along with a technical report. This release pushes the boundaries of open-weight models, offering frontier-level capabilities to the community and intensifying competition with proprietary models. It also signals Moonshot AI's ambition to become a major player in the global AI landscape. Kimi K3 features a 2.8 trillion-parameter count, making it one of the largest open-weight models. Pricing is set at $3/15 per 1M tokens (cache at $0.3), matching Anthropic's Sonnet series, and it includes a dedicated reasoning token system.

hackernews · vincent_s · Jul 16, 14:46 · [Discussion](https://news.ycombinator.com/item?id=48935342)

**Background**: Open-weight models are AI models whose trained parameters (weights) are publicly released for anyone to download and use. The 1M context window allows the model to process very long documents or conversations in a single instance. This release comes amid a trend of increasingly capable open models challenging proprietary frontier models.

<details><summary>References</summary>
<ul>
<li><a href="https://hai.stanford.edu/ai-definitions/what-is-an-open-weight-model">What is an Open-Weight Model? - Stanford HAI</a></li>
<li><a href="https://www.ai21.com/glossary/foundational-llm/open-weights-model/">What is an Open-Weights Model? | AI21</a></li>

</ul>
</details>

**Discussion**: The community is impressed by Kimi K3's performance and scale, but notes that pricing is high for a Chinese open-weight model. Some commenters highlight the 1M context, reasoning tokens, and the upcoming weight release, while others compare it to existing models like DeepSeek-V4-Pro.

**Tags**: `#AI`, `#large language models`, `#machine learning`, `#open-weight`, `#Moonshot AI`

---

<a id="item-2"></a>
## [Claude web_fetch prompt injection leaks private data](https://simonwillison.net/2026/Jul/15/claude-web-fetch-exfiltration/#atom-everything) ⭐️ 9.0/10

Researcher Ayush Paul discovered a prompt injection attack that bypasses Claude web_fetch tool protections, allowing exfiltration of user private data such as name, city, and employer. Anthropic has since patched the vulnerability. This attack demonstrates a critical vulnerability in AI agent security, especially when tools have access to sensitive data and external content. It highlights the persistent threat of prompt injection and the need for robust safeguards. The attack exploited a loophole where web_fetch could follow links within fetched pages. The attacker used a honeypot site with nested links that tricked Claude into navigating letter by letter to exfiltrate data. Anthropic declined to pay a bug bounty, claiming they already identified the issue internally.

rss · Simon Willison · Jul 15, 14:21

**Background**: Prompt injection attacks occur when an AI model receives instructions from untrusted content that override its original directives. The 'lethal trifecta' refers to the combination of private data access, untrusted content processing, and exfiltration capability, which enables such attacks. Claude's web_fetch tool is designed to only navigate to user-specified URLs or search results, but the attack found a way around this.

<details><summary>References</summary>
<ul>
<li><a href="https://www.osohq.com/learn/lethal-trifecta-ai-agent-security">Understanding the Lethal Trifecta of AI Agents</a></li>
<li><a href="https://anthropic.mintlify.app/en/docs/agents-and-tools/tool-use/web-fetch-tool">Web fetch tool - Claude Docs</a></li>
<li><a href="https://simonwillison.net/2025/Jun/16/the-lethal-trifecta/">The lethal trifecta for AI agents: private data, untrusted content, and external communication</a></li>

</ul>
</details>

**Tags**: `#security`, `#prompt injection`, `#AI safety`, `#Claude`, `#data exfiltration`

---

<a id="item-3"></a>
## [Japan to Buy 27,500 Nvidia Rubin Chips for Robot Sovereign AI](https://www.bloomberg.com/news/articles/2026-07-16/japan-to-buy-nvidia-rubin-chips-to-build-sovereign-ai-for-robots) ⭐️ 9.0/10

Japan plans to purchase 27,500 Nvidia Rubin chips, led by new company Noetra, to build a large-scale data center and develop a domestic AI model for robotics, backed by $2.4 billion in government funding. This initiative aims to create a 'third option' beyond US and China, reducing Japan's reliance on foreign AI technologies and positioning the country to capture over 30% of the global robotics market by 2040. Noetra president Hironobu Tamba stated the first AI model is expected by March 2027, with a robot-specific version in a few years. Companies including SoftBank, Preferred Networks (backed by Toyota), and NEC are involved.

telegram · zaihuapd · Jul 16, 10:59

**Background**: Nvidia's Rubin platform, announced at Computex 2024, is the next-generation GPU architecture featuring a 3nm process and HBM4 memory, scheduled for release in Q3 2026. Sovereign AI refers to a nation's full control over its AI lifecycle, from infrastructure to models, ensuring national security and economic independence.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Rubin_(microarchitecture)">Rubin (microarchitecture) - Wikipedia</a></li>
<li><a href="https://www.mckinsey.com/featured-insights/mckinsey-explainers/what-is-sovereign-ai">What is sovereign AI? | McKinsey</a></li>

</ul>
</details>

**Tags**: `#Nvidia`, `#Rubin`, `#Japan`, `#AI`, `#Robotics`

---

<a id="item-4"></a>
## [Rust-to-Zig Rewrite: Progress and Pitfalls](https://rtfeldman.com/rust-to-zig) ⭐️ 8.0/10

Richard Feldman published a detailed report on rewriting the Roc compiler from Rust to Zig, highlighting unexpected gains in compile times and ergonomics. This real-world case study challenges the assumption that Rust is always the best choice for systems programming, especially when memory safety can be traded for simplicity and build performance. The rewrite faced challenges with Zig's lack of some high-level abstractions and debugging tools, but achieved visibly faster incremental builds compared to Rust.

hackernews · jorangreef · Jul 16, 11:39 · [Discussion](https://news.ycombinator.com/item?id=48933149)

**Background**: Rust and Zig are both modern systems programming languages. Rust emphasizes memory safety without a garbage collector using its ownership system, while Zig aims to be a simpler, more flexible replacement for C with manual memory management and compile-time code execution.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Zig_(programming_language)">Zig (programming language)</a></li>
<li><a href="https://ziglang.org/">Home ⚡ Zig Programming Language</a></li>

</ul>
</details>

**Discussion**: Steve Klabnik argued that memory-unsafe operations are not as central to code generation as the post implied, while others questioned whether Zig's incremental builds justify giving up Rust's memory safety guarantees.

**Tags**: `#rust`, `#zig`, `#programming-languages`, `#systems-programming`, `#memory-safety`

---

<a id="item-5"></a>
## [GPT-5.6/Codex Bug Can Delete Files Without Sandboxing](https://simonwillison.net/2026/Jul/16/bad-codex-bug/#atom-everything) ⭐️ 8.0/10

A bug in GPT-5.6 (Codex) can cause accidental file deletion when full access mode is used without sandboxing, due to an error where the model mistakenly deletes the $HOME environment variable instead of overriding it. This bug highlights a critical safety risk in AI agents with file system access: even a seemingly simple mistake by the model can lead to irreversible data loss. It underscores the need for robust sandboxing and auto-review features before granting AI agents full autonomy. The bug occurs when Codex runs in full access mode without sandboxing or auto-review enabled, and attempts to override the $HOME environment variable to set a temporary directory. Instead, it mistakenly deletes $HOME, causing unintended file deletions.

rss · Simon Willison · Jul 16, 17:45

**Background**: Codex is an AI coding agent developed by OpenAI, released in April 2025 as Codex CLI, designed for software engineering tasks like writing and fixing code. Sandboxing is a security technique that isolates an AI agent's operations to prevent it from affecting the host system; without it, an agent can directly modify files, as in this bug.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Codex_(AI_agent)">Codex (AI agent) - Wikipedia</a></li>
<li><a href="https://www.explainthis.io/en/ai/ai-sandboxing">What is Sandboxing? Why Do AI Agents Need Sandboxes?</a></li>

</ul>
</details>

**Tags**: `#codex`, `#gpt-5.6`, `#AI safety`, `#file deletion`, `#bug`

---

<a id="item-6"></a>
## [Inkling: Open-weights multimodal MoE model from Thinking Machines Lab](https://simonwillison.net/2026/Jul/16/inkling/#atom-everything) ⭐️ 8.0/10

Mira Murati's Thinking Machines Lab released Inkling, their first open-weights model, a Mixture-of-Experts transformer with 975B total parameters (41B active), licensed under Apache-2.0 and trained on 45 trillion tokens of text, images, audio, and video. This release strengthens the US open-weights ecosystem with a competitive contender alongside NVIDIA Nemotron and Gemma 4, and is notable for being Apache-2.0 licensed, allowing broad use and customization via their Tinker fine-tuning platform. Inkling is not a frontier model but a strong base for fine-tuning; they also plan to release Inkling-Small (276B total, 12B active) later. The model card and training data documentation are notably sparse, disclosing only that data comes from public internet and third-party sources.

rss · Simon Willison · Jul 16, 15:35

**Background**: Mixture-of-Experts (MoE) is an architecture that decouples total parameter count from per-token compute by activating only a subset of parameters (experts) for each input, enabling larger models without proportional cost. Open-weights models publicly release the trained weights under permissive licenses like Apache-2.0, allowing modification and fine-tuning without full open-source transparency, which is distinct from true open-source software.

<details><summary>References</summary>
<ul>
<li><a href="https://datanorth.ai/blog/what-is-mixture-of-experts-moe-and-why-does-it-matter">What is mixture of experts ( MoE ) and why does it matter?</a></li>
<li><a href="https://www.ai21.com/glossary/foundational-llm/open-weights-model/">What is an Open-Weights Model? | AI21</a></li>

</ul>
</details>

**Tags**: `#open-weights`, `#mixture-of-experts`, `#multimodal`, `#Mira Murati`, `#AI model release`

---

<a id="item-7"></a>
## [Linus Torvalds Declares Linux Not Anti-AI](https://simonwillison.net/2026/Jul/16/linus-torvalds/#atom-everything) ⭐️ 8.0/10

Linus Torvalds, the top Linux maintainer, publicly stated on the Linux Media Mailing List that Linux is not an anti-AI project and that AI is a clearly useful tool, telling critics to fork or walk away. This definitive stance from the leading maintainer of the Linux kernel profoundly impacts the open-source community's direction regarding AI integration, potentially accelerating AI adoption in kernel development and setting a precedent for other projects. Torvalds acknowledged that doubts about AI's utility were understandable a year ago but are no longer valid today, though he noted other open questions about AI's economy.

rss · Simon Willison · Jul 16, 13:26

**Background**: Linux is a widely used open-source operating system kernel, and Linus Torvalds is its original creator and long-time maintainer. Recently, debates have emerged in the open-source community about incorporating AI tools into development workflows, with some voicing strong opposition.

**Tags**: `#Linux`, `#AI`, `#Open Source`, `#Linus Torvalds`, `#Software Development`

---

<a id="item-8"></a>
## [xAI open-sources Grok Build after privacy backlash](https://simonwillison.net/2026/Jul/15/grok-build/#atom-everything) ⭐️ 8.0/10

xAI has open-sourced the entire Grok Build codebase under the Apache 2.0 license following a severe community backlash over privacy concerns, where the CLI tool was found uploading entire directories—including SSH keys and password databases—to cloud storage. This incident underscores critical data privacy vulnerabilities in mainstream AI coding tools, potentially affecting thousands of developers. By open-sourcing the code and deleting retained data, xAI aims to restore trust, setting a precedent for transparency in the AI tool ecosystem. The Grok Build repository contains 844,530 lines of Rust code (with only about 3% vendored) and was released as a single commit, providing no historical insight. The release includes system prompts and a Mermaid diagram renderer.

rss · Simon Willison · Jul 15, 23:59

**Background**: Grok Build is xAI's terminal-based AI coding agent that runs as a full-screen TUI, capable of editing files, executing commands, and managing tasks. The privacy issue emerged when users discovered that running the 'grok' command in a directory would upload its entire contents to xAI's Google Cloud buckets, leading to a public outcry and Musk's promise to delete all uploaded data.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/xai-org/grok-build">GitHub - xai-org/grok-build: SpaceXAI's coding agent harness ...</a></li>
<li><a href="https://x.ai/cli">Grok Build | SpaceXAI</a></li>

</ul>
</details>

**Discussion**: Community comments on the original report expressed shock and anger, with users sharing stories of sensitive data exposure. Many welcomed the open-source release but remained cautious, questioning why the upload behavior was ever a default setting.

**Tags**: `#privacy`, `#open source`, `#AI tools`, `#security`, `#xAI`

---

<a id="item-9"></a>
## [Lobste.rs Migrates from MariaDB to SQLite](https://simonwillison.net/2026/Jul/14/lobsters-sqlite/#atom-everything) ⭐️ 8.0/10

Lobste.rs, a community link-aggregation site, has successfully migrated its database from MariaDB to SQLite, completing a long-planned move that began in 2018. The site now runs on a single VPS with multiple SQLite databases, reporting lower CPU and memory usage, faster page loads, and reduced hosting costs. This migration serves as a real-world case study demonstrating SQLite's viability as a production database for moderately-trafficked web applications, challenging the assumption that a client-server RDBMS like MariaDB or PostgreSQL is always necessary. It could encourage other small-to-medium Rails applications to consider SQLite to simplify infrastructure and reduce costs. The primary SQLite database file is about 3.8 GB, with separate files for cache (1.1 GB), queue (218 MB), and Rack::Attack rate-limiting (555 MB). The migration was implemented via pull request #1927, adding 735 lines and removing 593 lines across 30 commits, building on several earlier PRs.

rss · Simon Willison · Jul 14, 19:44

**Background**: SQLite is an embedded, file-based database engine that does not require a separate server process, making it simple to deploy and manage. Traditionally, SQLite has been used for local or low-concurrency applications, but recent improvements in WAL mode and Rails adapters have made it more suitable for production web use with moderate traffic. Lobste.rs is a community-driven link aggregator similar to Hacker News, built with Ruby on Rails.

<details><summary>References</summary>
<ul>
<li><a href="https://sqlite.org/whentouse.html">Appropriate Uses For SQLite</a></li>
<li><a href="https://medium.com/data-science/sqlite-in-production-dreams-becoming-reality-94557bec095b">SQLite in Modern Web Production: Dreams Becoming Reality | by Ed Izaguirre | TDS Archive | Medium</a></li>

</ul>
</details>

**Tags**: `#SQLite`, `#database migration`, `#Rails`, `#web performance`, `#production experience`

---

<a id="item-10"></a>
## [AI Weekly Issue #514: 159 Real AI Deployments Library Released](https://aiweekly.co/issues/applied-ai-is-here-whats-working-what-got-pulled-back-and) ⭐️ 8.0/10

AI Weekly released a free library of 159 real, named AI deployments across 21 industries, including tools, vendors, outcomes for 77 cases, and 6 halted or reversed projects. This curated resource provides actionable insights for practitioners to inform budget and strategy decisions before committing to AI investments, highlighting both successes and failures. The library is freely accessible without signup, and it covers a wide range of industries, with the halted cases noted as potentially the most useful entries for learning what to avoid.

rss · AI Weekly · Jul 15, 00:00

**Background**: AI deployment libraries compile real-world examples to help organizations understand what works and what doesn't. They are valuable for decision-makers seeking evidence-based guidance before allocating resources to AI projects. The AI Use-Case Library by AI Weekly is a practical resource that includes both successful and failed deployments to provide a balanced perspective.

**Tags**: `#AI applications`, `#case studies`, `#industry use cases`, `#deployment insights`, `#AI failures`

---

<a id="item-11"></a>
## [ExTernD: Ternary Decomposition for Accurate LLM Quantization](https://www.reddit.com/r/MachineLearning/comments/1uy2zb3/externd_expandedrank_ternary_decomposition/) ⭐️ 8.0/10

Researchers propose ExTernD, a post-training ternary matrix factorization method that decomposes each weight matrix into two ternary matrices and a diagonal scaling matrix. This expanded-rank approach allows accuracy to approach any quantization level while requiring only slightly more VRAM than existing methods. ExTernD could enable highly efficient LLM inference with ternary arithmetic, dramatically reducing memory and computation costs while maintaining accuracy comparable to higher-bit quantization. This is significant for deploying large language models on resource-constrained devices. The method is a post-training quantization (PTQ) technique that does not require retraining. By increasing the inner rank, accuracy can be arbitrarily improved, though at the cost of slightly more VRAM.

reddit · r/MachineLearning · /u/LMTLS5 · Jul 16, 13:31

**Background**: Post-training quantization (PTQ) reduces model size and speeds up inference by converting weights from floating-point to low-bit representations. Ternary quantization (values -1, 0, +1) is extremely efficient but typically suffers significant accuracy loss. ExTernD addresses this by factoring each weight matrix into two ternary matrices, effectively expanding the representational capacity without abandoning the ternary structure.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2607.13511">[2607.13511] ExTernD : Expanded-Rank Ternary Decomposition ...</a></li>
<li><a href="https://arxiv.org/html/2607.13511">ExTernD : Expanded-Rank Ternary Decomposition Ternary LLM...</a></li>

</ul>
</details>

**Discussion**: The Reddit post author explains the core idea of decomposing matrices to achieve arbitrary accuracy with modest VRAM overhead. There are no other comments in the thread, so overall community reaction is not yet available.

**Tags**: `#LLM`, `#quantization`, `#ternary`, `#post-training`, `#efficiency`

---

<a id="item-12"></a>
## [PnP-CoSMo: Plug-and-Play Multi-Contrast MRI Reconstruction](https://www.reddit.com/r/MachineLearning/comments/1uy2h66/pnpcosmo_a_multicontrast_mri_reconstruction/) ⭐️ 8.0/10

Researchers introduced PnP-CoSMo, a plug-and-play framework for multi-contrast MRI reconstruction that models contrast-invariant content and style, achieving state-of-the-art performance without requiring raw k-space training data. This work addresses a major data bottleneck in deep learning-based MRI by eliminating the need for raw k-space data, and its generalizability across contrasts and forward operators could accelerate clinical adoption of AI-assisted imaging. The method operates in two stages: first learning a content/style model from image-domain data only, then freezing it as a prior for iterative reconstruction. It was published in Medical Image Analysis and includes code.

reddit · r/MachineLearning · /u/void_gear · Jul 16, 13:10

**Background**: In MRI, images are reconstructed from raw k-space data, which is often undersampled to speed up scans. Traditional deep learning methods require large amounts of k-space data for training, creating a bottleneck. Multi-contrast MRI acquires multiple images with different contrasts (e.g., T1, T2) of the same anatomy, which share common structural content. PnP-CoSMo leverages this shared content to improve reconstruction.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/K-space_(MRI)">K-space (MRI)</a></li>
<li><a href="https://arxiv.org/abs/2105.08949">[2105.08949] Multi-Contrast MRI Super-Resolution via a Multi-Stage Integration Network</a></li>
<li><a href="https://arxiv.org/abs/2512.03020">[2512.03020] Unrolled Networks are Conditional Probability Flows in MRI Reconstruction</a></li>

</ul>
</details>

**Discussion**: No comments were available for this news item.

**Tags**: `#MRI reconstruction`, `#deep learning`, `#medical imaging`, `#generative modeling`, `#plug-and-play`

---

<a id="item-13"></a>
## [All Major Robotics Papers Ranked on Papers with Code](https://www.reddit.com/r/MachineLearning/comments/1uxa7ak/all_major_robotics_and_vla_papers_ranked_and/) ⭐️ 8.0/10

A dedicated Robotics page on Papers with Code now aggregates major benchmarks, trending papers, and open-source models, providing a centralized resource for the robotics community. This makes it easier for researchers and practitioners to track progress, compare methods, and access open-source artifacts, accelerating robotics research and development. The page currently lists about 110 entries per benchmark, including LIBERO, SimplerEnv WidowX, and RoboTwin, and shows which models are open source. Benchmarks' progress is visualized over time.

reddit · r/MachineLearning · /u/NielsRogge · Jul 15, 16:05

**Background**: Vision-Language-Action (VLA) models combine vision, language, and action to enable robots to understand and execute tasks. Benchmarks like LIBERO focus on lifelong learning for robot manipulation, while SimplerEnv provides simulation environments for evaluating generalist policies.

<details><summary>References</summary>
<ul>
<li><a href="https://libero-project.github.io/main.html">LIBERO – LIBERO</a></li>
<li><a href="https://github.com/simpler-env/SimplerEnv">GitHub - simpler-env/SimplerEnv: Evaluating and reproducing ...</a></li>
<li><a href="https://arxiv.org/abs/2306.03310">[2306.03310] LIBERO: Benchmarking Knowledge Transfer for ... LIBERO · Hugging Face LIBERO: Benchmarking Knowledge Transfer for Lifelong Robot ... Zxy-MLlab/LIBERO-PRO - GitHub LIBERO-Safety: A Comprehensive Benchmark for Physical and ...</a></li>

</ul>
</details>

**Discussion**: The Reddit post received a positive response, with the author (NielsRogge, ML Engineer at Hugging Face) inviting feedback and suggestions for additional tasks or features. The community appreciated the centralized resource.

**Tags**: `#robotics`, `#benchmarks`, `#papers-with-code`, `#VLA`, `#opensource`

---

<a id="item-14"></a>
## [xAI Sues User for Generating Child Abuse Deepfakes with Grok](https://www.reuters.com/legal/litigation/musks-xai-sues-grok-user-over-sexualized-deepfakes-2026-07-15/) ⭐️ 8.0/10

xAI has filed a lawsuit against South Carolina man Terry Harwood, alleging he used its Grok chatbot to generate child sexual abuse material and non-consensual adult deepfakes, violating the terms of service. This case is one of the first where an AI company sues a user for generating illegal deepfakes, potentially setting a legal precedent for holding users accountable for misusing AI tools. xAI reports that it has suspended 52,222 accounts, reported 73,604 incidents to the National Center for Missing & Exploited Children, and facilitated at least 244 arrests. The lawsuit seeks damages and a permanent injunction against Harwood using Grok.

telegram · zaihuapd · Jul 16, 01:45

**Background**: Grok is a generative AI chatbot developed by xAI, launched in November 2023. It has been criticized for generating inappropriate content, including nonconsensual sexualized images of women and children. Child sexual abuse material deepfakes are illegal and a growing concern as AI image generation advances.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Grok_(chatbot)">Grok (chatbot)</a></li>

</ul>
</details>

**Tags**: `#AI safety`, `#deepfakes`, `#legal`, `#xAI`, `#child protection`

---

<a id="item-15"></a>
## [CNKI to Remove Papers Listing AI as Authors](https://www.zaobao.com.sg/news/china/story20260716-9371836) ⭐️ 8.0/10

China National Knowledge Infrastructure (CNKI) announced it will remove papers that list AI models such as DeepSeek as co-authors, stating that AI lacks civil legal capacity and cannot assume responsibility for academic integrity. This policy reinforces the principle that AI models cannot be held accountable for research integrity, setting a precedent for academic publishing in China and globally. It will affect researchers who have listed AI as co-authors and may influence other platforms to adopt similar rules. CNKI specifically stated that AI tools are not accepted as signed authors of papers, and authors who use AI in research or writing must disclose it in the methodology or acknowledgments section.

telegram · zaihuapd · Jul 16, 07:45

**Background**: CNKI is a major Chinese academic database and publishing platform. DeepSeek is a Chinese AI model developed by DeepSeek AI. In recent months, some researchers listed AI models as co-authors on papers, sparking debate about AI authorship and accountability. CNKI's announcement aligns with positions taken by many international publishers and journals.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek">DeepSeek - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#AI`, `#academic integrity`, `#publishing policy`, `#DeepSeek`, `#China`

---

<a id="item-16"></a>
## [US Launches 337 Investigation on DRAM Devices Targeting Samsung, Google, Nvidia](https://www.cls.cn/detail/2428105) ⭐️ 8.0/10

The U.S. International Trade Commission (USITC) voted on July 15 to initiate a 337 investigation (337-TA-1511) into certain DRAM devices and downstream products, following a patent infringement complaint by Netlist. Named respondents include Samsung, Google, Super Micro, Nvidia, Broadcom, and others. This investigation could disrupt supply chains for AI servers, cloud services, and high-performance computing if infringement is found and imports are restricted. It directly affects major tech companies integral to AI and cloud infrastructure, potentially raising costs or causing delays for enterprise customers. The investigation covers DDR5 DIMMs, High Bandwidth Memory (HBM), and servers, computing, and storage systems using these memories. Netlist, a memory subsystem designer, alleges patent infringement; a final decision could lead to exclusion orders barring infringing products from the U.S. market.

telegram · zaihuapd · Jul 16, 08:34

**Background**: A Section 337 investigation is conducted by the USITC to determine unfair competition in import trade, often involving intellectual property infringement. Netlist is a California-based company that designs high-performance memory modules and SSDs. HBM is a 3D-stacked memory technology providing high bandwidth, critical for AI and GPU workloads. The investigation targets key players in the AI hardware ecosystem, including memory makers and cloud service providers.

<details><summary>References</summary>
<ul>
<li><a href="https://www.usitc.gov/press_room/us337.htm">Understanding Investigations Of Intellectual Property Infringement And Other Unfair Practices In Import Trade (Section 337) | United States International Trade Commission</a></li>
<li><a href="https://en.wikipedia.org/wiki/Netlist,_Inc.">Netlist , Inc. - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/High_Bandwidth_Memory">High Bandwidth Memory - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#DRAM`, `#337 investigation`, `#supply chain`, `#AI hardware`, `#patent infringement`

---

<a id="item-17"></a>
## [TSMC Invests $100B More in US, Q2 Profit Surges 77%](https://www.reuters.com/world/asia-pacific/tsmcs-second-quarter-profit-seen-hitting-record-ai-boom-2026-07-15/) ⭐️ 8.0/10

TSMC announced an additional $100 billion investment in its Arizona fab, bringing total US investment to $165 billion, and reported a record Q2 2026 net profit of NT$706.6 billion ($22 billion), up 77% year-over-year. This underscores TSMC's commitment to US chip manufacturing amid geopolitical tensions and highlights the sustained AI-driven demand that continues to boost semiconductor profits, affecting global supply chains and tech industry dynamics. The Q2 profit far exceeded market expectations of NT$632.6 billion; TSMC raised its 2026 capital expenditure forecast to $60-64 billion and expects full-year USD revenue to grow slightly over 40%.

telegram · zaihuapd · Jul 16, 12:29

**Background**: TSMC is the world's largest dedicated independent semiconductor foundry, producing chips for companies like Apple and AMD. The AI boom has dramatically increased demand for advanced chips, benefiting TSMC. The US has been encouraging semiconductor manufacturing through the CHIPS Act to reduce reliance on Asia.

**Tags**: `#TSMC`, `#semiconductor`, `#AI`, `#investment`, `#chip manufacturing`

---

<a id="item-18"></a>
## [1Password's Claude Integration Lets AI Log In Without Seeing Passwords](https://9to5mac.com/2026/07/16/1password-now-lets-claude-sign-in-to-websites-without-seeing-your-passwords/) ⭐️ 8.0/10

1Password has launched an integration with Claude for Mac that allows the AI assistant to log into websites on behalf of users via secure credential injection, without the passwords or TOTP codes ever entering Claude's context or memory. The feature requires biometric approval for each session and is available for business, family, and personal plans. This integration addresses a critical security and privacy concern by enabling AI agents to authenticate on web services without exposing credentials, paving the way for more autonomous and secure AI-assisted workflows. It sets a new standard for how password managers can safely interact with AI systems. Credentials are injected directly into the target web page via a secure channel, and the permission granted is limited to the current session only. If auto-fill submission fails, the filled content is immediately erased; the feature also plans to support payment cards and identity information in the future.

telegram · zaihuapd · Jul 16, 15:54

**Background**: Credential injection is a security technique where credentials are inserted directly into a remote session or application without exposing them to intermediate agents or user memory. In this case, 1Password uses a secure channel to inject passwords into the browser page, ensuring that even if the AI agent is compromised, it cannot extract the credentials. This approach contrasts with less secure methods like environment variable injection.

<details><summary>References</summary>
<ul>
<li><a href="https://nono.sh/credential-injection">Credential Injection - Proxy-Based Secret Management for AI... | nono</a></li>
<li><a href="https://nhimg.org/glossary/credential-injection/">What Is Credential Injection ? Definition & Examples</a></li>
<li><a href="https://www.xonasystems.com/glossary/credential-injection">Credential Injection</a></li>

</ul>
</details>

**Tags**: `#1Password`, `#Claude`, `#AI Integration`, `#Password Security`, `#Browser Extension`

---

<a id="item-19"></a>
## [Microsoft Comic Chat open-sourced](https://opensource.microsoft.com/blog/2026/07/16/microsoft-comic-chat-is-now-open-source/) ⭐️ 7.0/10

Microsoft open-sourced Comic Chat (later Microsoft Chat) on July 16, 2026, making the source code of this 1990s graphical IRC client available on GitHub. This open-sourcing preserves a piece of internet history and allows developers to study or revive a unique chat experience that combined IRC with comic-style avatars, impacting retro computing and software preservation communities. Comic Chat was originally developed by Microsoft researcher David Kurlander and first released with Internet Explorer 3.0 in 1996. It extended the IRC protocol with commands for character appearance and emoting, rather than relying solely on text context.

hackernews · jervant · Jul 16, 16:06 · [Discussion](https://news.ycombinator.com/item?id=48936426)

**Background**: IRC (Internet Relay Chat) is a text-based chat protocol created in 1988, operating on a client-server model. Microsoft Comic Chat was a graphical IRC client that rendered conversations as comic strips with customizable characters, making it a notable experiment in social user interfaces during the early web era.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Microsoft_Comic_Chat">Microsoft Comic Chat</a></li>
<li><a href="https://en.wikipedia.org/wiki/IRC_protocol">IRC protocol</a></li>

</ul>
</details>

**Discussion**: Robert Standefer, who orchestrated the open-sourcing, shared the six-year story behind it and acknowledged original developer DJ Kurlander. Commenters reminisced about Comic Chat's cultural impact and technical quirks, noting its extended IRC protocol and inspiration for later projects like the comic creation web app Chogger.

**Tags**: `#open source`, `#Microsoft`, `#IRC`, `#retro computing`, `#software history`

---

<a id="item-20"></a>
## [OnePlus stops new product launches in Europe and North America](https://community.oneplus.com/thread/2170715118587871237) ⭐️ 7.0/10

OnePlus announced it will stop launching new products in Europe and North America, but will continue software support for existing devices. This marks a significant retreat from key markets for OnePlus, affecting its user base and signaling a shift in strategy towards focusing on other regions. The announcement was clarified by community members to mean no new product rollouts, not a complete halt of operations. OnePlus, backed by OPPO, will continue to provide software updates and security patches for existing devices within committed support periods.

hackernews · pilililo2 · Jul 16, 10:14 · [Discussion](https://news.ycombinator.com/item?id=48932539)

**Background**: OnePlus started as a 'flagship killer' brand with an invite system, gaining a loyal following among enthusiasts for its stock Android experience, unlocked bootloaders, and competitive pricing. Over time, it shifted away from these principles, leading to disappointment among early adopters. The brand is a subsidiary of OPPO, and its co-founder Carl Pei left to start Nothing.

**Discussion**: Commenters expressed nostalgia for OnePlus's early days and lamented its decline. Some corrected the misleading title, emphasizing that only new product launches are ceasing, not operations. Others noted that OnePlus has become just another Chinese phone brand.

**Tags**: `#OnePlus`, `#smartphones`, `#consumer electronics`, `#business strategy`

---

<a id="item-21"></a>
## [GOES-19 weather satellite enters Safe Hold mode](https://www.spaceweather.gov/news/goes-19-safe-hold) ⭐️ 7.0/10

NOAA's GOES-19 satellite, the primary weather satellite for tracking Atlantic hurricanes, entered safe hold mode on July 23, 2025, due to an onboard anomaly, suspending its data collection. This disruption comes during the peak of hurricane season, potentially impairing real-time hurricane tracking and forecasting capabilities for the Atlantic, Caribbean, and Gulf of Mexico. Safe hold mode is a standard spacecraft safety protocol that stabilizes the satellite by orienting solar panels toward the sun and minimizing non-essential operations. Engineers are working to prepare for restart of onboard instruments, but a recovery timeline has not yet been announced.

hackernews · yabones · Jul 16, 13:30 · [Discussion](https://news.ycombinator.com/item?id=48934286)

**Background**: The GOES series (Geostationary Operational Environmental Satellites) are NOAA's fleet of weather satellites positioned in geostationary orbit, providing continuous imagery and data for weather monitoring. Safe hold mode is triggered automatically when the onboard computer detects a critical anomaly, such as a power or thermal issue, to protect the satellite's hardware. This event is notable because GOES-19 is the primary satellite for hurricane tracking, and previous GOES satellites have experienced similar anomalies (e.g., GOES-17's loop heat pipe issue).

<details><summary>References</summary>
<ul>
<li><a href="https://asibiont.com/en/blog/sputnik-goes-19-pereshel-v-bezopasnyy-rezhim-chto-eto-znachit-dlya-meteorologii-i-kosmicheskoy-avtomatizatsii">GOES-19 Weather Satellite Enters Safe Hold Mode ... — ASI Biont Blog</a></li>
<li><a href="https://news.ycombinator.com/item?id=48934286">Goes-19 weather satellite enters Safe Hold mode | Hacker News</a></li>

</ul>
</details>

**Discussion**: A former GOES engineer commented that problems with GOES satellites are not uncommon, citing past issues like GOES-17's loop heat pipe anomaly. Another user noticed the outage in real-time while monitoring wildfire smoke imagery. A commenter also provided a link to a local news article explaining the impact on hurricane tracking.

**Tags**: `#satellites`, `#weather`, `#NOAA`, `#space`

---

<a id="item-22"></a>
## [The Lost Joy of Music Piracy](https://www.pigeonsandplanes.com/read/music-piracy-what-cd-oink-nine-inch-nails-streaming) ⭐️ 7.0/10

A reflective article eulogizes the era of music piracy, contrasting its communal, serendipitous discovery with the algorithm-driven, subscription-based streaming model that dominates today. It highlights a cultural and emotional loss for music enthusiasts who valued the social curation and deep engagement of piracy communities like Oink and What.cd, and questions whether streaming truly satisfies all listener needs. The article specifically references the shutdown of Oink and What.cd as symbolic ends of an era, and notes that music discovery through friends' iPod collections created unique personal soundtracks.

hackernews · mcgin · Jul 16, 04:46 · [Discussion](https://news.ycombinator.com/item?id=48930454)

**Background**: Music piracy flourished in the early 2000s through peer-to-peer networks and private trackers like Oink and What.cd, where users curated vast libraries and engaged in passionate forum discussions. The rise of legal streaming services like Spotify and Apple Music provided convenience but also centralized control over music access, reducing the sense of community and ownership that piracy fostered.

**Discussion**: Commenters unanimously express nostalgia, with devonsolomon mourning the loss of social curation from friend groups, while eisa01 points out that streaming still lacks a complete catalog, forcing continued piracy. Another user highlights the ironic synergy between iPod storage capacity and P2P sharing, and postalcoder praises the article and misses the deep forum discussions on What.cd.

**Tags**: `#music piracy`, `#streaming`, `#digital culture`, `#nostalgia`, `#media consumption`

---

<a id="item-23"></a>
## [Sony Deletes Purchased Movies from User Accounts Again](https://www.techdirt.com/2026/07/15/sony-deletes-a-bunch-more-movies-from-the-accounts-of-people-who-bought-them/) ⭐️ 7.0/10

Sony has deleted movies from the accounts of users who believed they had purchased them, continuing a pattern of revoking access to digital content. This incident highlights the fragility of digital ownership and fuels debate over consumer rights, as users lose access to content they paid for without compensation. The deletions affect movies that users thought they owned, and similar incidents have occurred multiple times before, indicating a systemic issue with digital storefronts labeling purchases as 'buy' when they are effectively long-term rentals.

hackernews · nekusar · Jul 16, 12:13 · [Discussion](https://news.ycombinator.com/item?id=48933419)

**Background**: Digital ownership is a contentious issue: when consumers 'buy' digital media, they often only receive a license that can be revoked by the seller. Sony's actions underscore the lack of consumer protections in digital marketplaces, where terms of service allow companies to remove access.

**Discussion**: Commenters expressed frustration and called for legal changes, with some advocating for mandatory refunds when access is revoked. Others noted that this is a recurring issue and suggested that physical media or piracy are more reliable alternatives.

**Tags**: `#digital rights`, `#consumer protection`, `#Sony`, `#digital ownership`

---

<a id="item-24"></a>
## [QLoRA default learning rate 2e-4 criticized for small datasets](https://www.reddit.com/r/MachineLearning/comments/1uy1z8b/the_qlora_2e4_default_is_wrong_under_10k_samples/) ⭐️ 7.0/10

A Reddit user argues that the commonly recommended default learning rate of 2e-4 for QLoRA fine-tuning is too high for datasets with fewer than 10,000 samples, and lowering it to 1e-4 yields significantly better evaluation results after increasing epochs. This insight can save practitioners from weeks of wasted effort by providing a simple, actionable adjustment, and it challenges the one-size-fits-all default hyperparameters commonly used in the machine learning community. The author spent weeks debugging data and prompts before finding that changing only the learning rate from 2e-4 to 1e-4 (and increasing epochs from 3 to 5) produced the largest evaluation improvement, suggesting a rule of thumb: use 2e-4 above 30k samples, start at 1e-4 or lower under 10k, and tune in between.

reddit · r/MachineLearning · /u/Pretty-Ad774 · Jul 16, 12:50

**Background**: QLoRA (Quantized Low-Rank Adaptation) is a parameter-efficient fine-tuning technique that combines 4-bit quantization with Low-Rank Adaptation (LoRA) to reduce memory usage for large language models. The default learning rate of 2e-4 originates from fine-tuning on the Alpaca dataset, which contains 52,000 instruction-response pairs. However, many practitioners fine-tune on smaller custom datasets, where a lower learning rate may prevent overfitting and improve generalization.

<details><summary>References</summary>
<ul>
<li><a href="https://grokipedia.com/page/QLoRA">QLoRA</a></li>
<li><a href="https://arxiv.org/abs/2305.14314">[2305.14314] QLoRA: Efficient Finetuning of Quantized LLMs</a></li>
<li><a href="https://huggingface.co/datasets/tatsu-lab/alpaca">tatsu-lab/alpaca · Datasets at Hugging Face</a></li>

</ul>
</details>

**Tags**: `#qlora`, `#learning-rate`, `#fine-tuning`, `#machine-learning`, `#practical-tips`

---

<a id="item-25"></a>
## [Seeking Critical Views on JEPA for Robot Learning](https://www.reddit.com/r/MachineLearning/comments/1uxcryc/looking_for_jepa_devil_advocates_r/) ⭐️ 7.0/10

A researcher posted on Reddit asking for devil's advocate perspectives on Joint Embedding Predictive Architecture (JEPA) models compared to other world model approaches in robot learning. This discussion is significant because JEPA, championed by Yann LeCun, is a polarizing approach that challenges dominant paradigms like LLMs and RL, and critical analysis helps the community assess its true potential and limitations. The poster mentions that LeCun's talks present JEPA as 'the only next big thing' while dismissing other methods, prompting a need for balanced critique. The request is for downsides compared to other world model approaches.

reddit · r/MachineLearning · /u/Amazing-Coat5160 · Jul 15, 17:34

**Background**: JEPA (Joint Embedding Predictive Architecture) is a self-supervised learning method that learns to predict abstract representations (embeddings) of data rather than reconstructing pixels or tokens. It is being explored for world models in robot learning, aiming to build an internal model of how the world works. Yann LeCun has been a prominent advocate, positioning JEPA as an alternative to generative models and reinforcement learning.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Joint_Embedding_Predictive_Architecture">Joint Embedding Predictive Architecture</a></li>
<li><a href="https://www.turingpost.com/p/jepamap">All JEPA Models : 14 Milestones From I- JEPA to ThinkJEPA</a></li>

</ul>
</details>

**Tags**: `#JEPA`, `#world models`, `#robot learning`, `#Yann LeCun`, `#ML debate`

---

<a id="item-26"></a>
## [Disentangling a Convolutional Neuron via Hadamard Product](https://www.reddit.com/r/MachineLearning/comments/1uwya70/mechanistic_interpretability_a_first_paper_on/) ⭐️ 7.0/10

A novel technique uses the Hadamard product of a neuron's receptive field and its weights to analyze a single 1x1 convolution in the Inceptionv1 model, revealing monosemantic clusters like cars, cats, and dogs, as well as lower-valued activations for letters and human faces. This work advances mechanistic interpretability by providing a method to understand what features individual convolutional neurons detect, offering insights into how gradient descent distributes weights to suppress certain patterns, which could improve model transparency and trust. The analysis found that low-valued clusters, such as letters, have all dependent neurons firing on the same concept, with positive and negative weights evenly distributed to reduce the net activation, suggesting deliberate suppression by gradient descent.

reddit · r/MachineLearning · /u/narang_27 · Jul 15, 06:59

**Background**: Mechanistic interpretability aims to reverse-engineer neural networks to understand internal computations. The Hadamard product is an element-wise matrix multiplication; applying it to a neuron's receptive field and weights isolates the patterns the neuron detects. Monosemantic clusters refer to groups of inputs that consistently activate a neuron for a single concept.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Hadamard_product_(matrices)">Hadamard product (matrices) - Wikipedia</a></li>
<li><a href="https://transformer-circuits.pub/2024/scaling-monosemanticity/">Scaling Monosemanticity: Extracting Interpretable Features from...</a></li>

</ul>
</details>

**Tags**: `#mechanistic interpretability`, `#convolutional neural networks`, `#neuron analysis`, `#interpretability`, `#deep learning`

---

<a id="item-27"></a>
## [170x PyTorch slowdown on T4 vs A100 baffles ML engineer](https://www.reddit.com/r/MachineLearning/comments/1ux6a9x/pytorch_model_running_170x_slower_on_t4_vs_a100/) ⭐️ 7.0/10

A machine learning engineer reports a 170x slowdown when running a point-tracking PyTorch model on an NVIDIA T4 GPU compared to an A100, despite both GPUs being fully utilized and the model using pure FP32 precision. This extreme performance gap highlights that raw hardware specifications alone cannot explain such discrepancies, underscoring the need for deeper profiling of memory bandwidth, tensor core availability, and model architecture inefficiencies on less powerful GPUs. The model builds local 4D correlation volumes for dense matching between frames and uses transformer layers for temporal context, all in pure FP32. Two independent T4 machines showed the same behavior, ruling out driver or setup issues, and enabling cudnn.benchmark had no effect.

reddit · r/MachineLearning · /u/Future-Structure-296 · Jul 15, 13:44

**Background**: NVIDIA T4 and A100 GPUs differ significantly in memory bandwidth (320 GB/s vs 1.6 TB/s), tensor core capability, and compute units. Point-tracking models like CoTracker and LocoTrack often rely on 4D correlation volumes and transformers, which can be memory-bandwidth-bound on T4, especially in FP32 where A100's tensor cores accelerate matrix operations but T4 lacks tensor core support for FP32. The 170x gap suggests an extreme case of such bottlenecks.

<details><summary>References</summary>
<ul>
<li><a href="https://voxel51.com/blog/cotracker3-enhanced-point-tracking-with-less-data">CoTracker3: Enhanced Point Tracking with Less Data - Voxel51</a></li>

</ul>
</details>

**Tags**: `#PyTorch`, `#GPU performance`, `#A100`, `#T4`, `#debugging`

---

<a id="item-28"></a>
## [China's CXMT to Nearly Match Micron DRAM Capacity by 2026](https://www.tomshardware.com/pc-components/dram/cxmt-close-to-matching-microns-memory-capacity-in-2026-research-claims-would-put-china-on-track-to-become-worlds-second-largest-dram-producer) ⭐️ 7.0/10

Citrini Research predicts that ChangXin Memory Technologies (CXMT) will reach approximately 350,000 wafers per month of DRAM capacity by the end of 2026, nearly matching Micron's 375,000 wafers per month, potentially making China the world's second-largest DRAM producer. This expansion could reshape global DRAM supply, enhance China's semiconductor self-sufficiency, and put pressure on existing players like Samsung, SK Hynix, and Micron. It also raises geopolitical concerns over technology export controls. Total Chinese DRAM capacity could reach 600,000 wafers per month by 2026 excluding foreign fabs in China, and 1.41 million wafers per month by 2030. However, restrictions on advanced immersion DUV lithography equipment under the U.S. MATCH Act could hinder short-term expansion.

telegram · zaihuapd · Jul 16, 02:30

**Background**: DRAM (Dynamic Random Access Memory) is a type of volatile memory widely used in computers, servers, and mobile devices. The global DRAM market is currently dominated by three companies: Samsung, SK Hynix, and Micron. China has been striving to build its own DRAM industry to reduce reliance on imports, with CXMT as a key player.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ChangXin_Memory_Technologies">ChangXin Memory Technologies - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#DRAM`, `#China`, `#semiconductor`, `#memory`, `#supply chain`

---

<a id="item-29"></a>
## [EU Draft Requires Google to Open Android AI Assistant Access](https://t.me/zaihuapd/42615) ⭐️ 7.0/10

The European Union is drafting a requirement that would force Google to grant rival AI assistants, such as ChatGPT and Claude, the same system-level access on Android as its own Gemini assistant. This could significantly reshape competition in the AI assistant market on mobile platforms, potentially increasing user choice and lowering barriers for new entrants. The draft requirement is still in early stages and its publication may be delayed; Google has expressed concerns that such openness could compromise user security and privacy.

telegram · zaihuapd · Jul 16, 13:19

**Background**: Currently, Google's Gemini assistant on Android has privileged access to system functions like voice activation, screen reading, and app integration. Rival assistants must rely on more limited APIs or accessibility services. The EU's draft aims to mandate equal access to these system-level capabilities, citing antitrust concerns.

<details><summary>References</summary>
<ul>
<li><a href="https://developer.android.com/ai/overview">Find the right AI/ML solution for your app | Android Developers</a></li>
<li><a href="https://blog.google/products-and-platforms/platforms/android/gemini-intelligence/">Gemini Intelligence brings proactive AI to Android - The Keyword</a></li>

</ul>
</details>

**Tags**: `#antitrust`, `#AI assistants`, `#Android`, `#regulation`, `#Google`

---

<a id="item-30"></a>
## [Building PlanetScale from Scratch: Incomplete Replication](https://onatm.dev/2026/07/16/homescale-part-1/) ⭐️ 6.0/10

A developer published a technical walkthrough titled 'Homescale Part 1' that aims to build a PlanetScale-like database infrastructure from scratch, but the article omits critical features such as sharding and connection pooling. The article misrepresents the complexity of PlanetScale, which took many developers months or years to build, and may mislead readers about the effort required to achieve production-grade scalability and zero-downtime operations. The walkdown covers compute-storage separation using Postgres and EBS, but omits horizontal sharding (a core Vitess feature) and a bouncer/gateway for zero-downtime migrations, as noted by commenters.

hackernews · onatm · Jul 16, 11:58 · [Discussion](https://news.ycombinator.com/item?id=48933303)

**Background**: PlanetScale is a serverless database platform built on Vitess, offering MySQL-compatible databases with automated horizontal sharding, database branching, and zero-downtime schema changes. It provides high scalability and reliability for cloud applications. The article attempts to replicate this infrastructure but misses essential components that make PlanetScale production-ready.

<details><summary>References</summary>
<ul>
<li><a href="https://grokipedia.com/page/PlanetScale">PlanetScale</a></li>
<li><a href="https://planetscale.com/">PlanetScale - the world’s fastest and most scalable cloud ...</a></li>

</ul>
</details>

**Discussion**: Commenters criticized the article for confusing PlanetScale's primary goal of easy horizontal scaling, noting the omission of sharding and a connection proxy. Some appreciated the walkdown as a learning resource but stressed it only covers a fraction of the actual product.

**Tags**: `#database`, `#infrastructure`, `#planetscale`, `#postgres`, `#scaling`

---

<a id="item-31"></a>
## [Ente Publishes Revenue Data, But Critics Question Full Transparency](https://ente.com/open/) ⭐️ 6.0/10

Ente, a privacy-focused photo storage service, published its revenue and account numbers on its website to demonstrate financial transparency. This move highlights the growing trend of startup transparency but also sparks debate about what constitutes meaningful openness, as critics argue that revenue alone does not reflect business health. The published data includes total revenue and number of paid accounts, but omits profit, operating expenses, and free cash flow, which community members note are crucial for assessing business viability.

hackernews · Sherex · Jul 16, 10:37 · [Discussion](https://news.ycombinator.com/item?id=48932697)

**Background**: Ente is an end-to-end encrypted photo storage service that positions itself as a privacy-focused alternative to Google Photos. Financial transparency, where companies share internal metrics publicly, is sometimes adopted by startups to build trust, but full transparency typically includes expenses and profit.

<details><summary>References</summary>
<ul>
<li><a href="https://ente.com/">Ente Photos: Store and share your photos with absolute privacy</a></li>
<li><a href="https://ente.com/download/">Ente - Download</a></li>
<li><a href="https://www.androidauthority.com/ente-photos-hands-on-3542198/">I tried Ente, a great privacy-focused Google Photos alternative</a></li>

</ul>
</details>

**Discussion**: Community comments are largely critical, with users like gortok calling it a "vanity blog post" that shows limited openness. Others, like pseufaux, appreciate the product but want to see profit and retention data for a fuller picture.

**Tags**: `#startup transparency`, `#financial openness`, `#privacy`, `#photo storage`

---

<a id="item-32"></a>
## [Simon Willison ports Grok CLI Mermaid renderer to WebAssembly](https://simonwillison.net/2026/Jul/16/grok-mermaid/#atom-everything) ⭐️ 6.0/10

Simon Willison created a web tool that converts Mermaid diagram code into Unicode box art by compiling a Rust component from the open-sourced Grok CLI into WebAssembly. The tool runs entirely in the browser without a server. This showcases practical reuse of AI-agent code (Grok CLI) for a standalone visualization tool, demonstrating how WebAssembly enables running Rust libraries in the browser. It lowers the barrier for developers to embed diagram rendering without external dependencies. The Rust module from xai-grok-markdown crate renders Mermaid diagrams to terminal-compatible Unicode art. Willison compiled it to WASM using Claude Code for web and published it on his tools site. The tool supports copying output as text and sharing diagrams via link.

rss · Simon Willison · Jul 16, 00:33

**Background**: Mermaid is a text-based diagramming tool that generates flowcharts, sequence diagrams, and more from Markdown-like syntax. WebAssembly (WASM) allows code written in languages like Rust to run in web browsers at near-native speed. Grok CLI is an open-source coding agent from xAI that uses models to assist in terminal-based development. The Rust Mermaid renderer was originally part of Grok CLI's markdown processing pipeline.

<details><summary>References</summary>
<ul>
<li><a href="https://mermaid.js.org/">Mermaid | Diagramming and charting tool</a></li>
<li><a href="https://github.com/superagent-ai/grok-cli">GitHub - superagent-ai/ grok - cli : An open-source coding agent for the...</a></li>
<li><a href="https://x.ai/cli">Grok Build | SpaceXAI</a></li>

</ul>
</details>

**Tags**: `#WebAssembly`, `#Mermaid`, `#Unicode`, `#Rust`, `#tool`

---

<a id="item-33"></a>
## [Should AI Memory Focus on Reasoning Patterns Over Facts?](https://www.reddit.com/r/MachineLearning/comments/1uy6yht/are_current_ai_memory_architectures_optimizing/) ⭐️ 6.0/10

A Reddit post challenges the current design of AI memory systems, suggesting they should shift from storing descriptive facts to inferring higher-level reasoning patterns and explanatory frameworks. This perspective could reshape how AI agents maintain long-term context, potentially leading to more adaptable and insightful interactions rather than simple fact recall. The author distinguishes between current persistent context (e.g., conversation summaries, user preferences) and a hypothetical system that continuously refines reasoning styles and abstraction preferences.

reddit · r/MachineLearning · /u/Boris_Ljevar · Jul 16, 16:00

**Background**: Current AI memory architectures, such as those in LLM agents, primarily store descriptive facts via mechanisms like summarization, retrieval-augmented generation, and persistent context files. These systems help models remember user facts but do not explicitly model reasoning patterns. Emerging research, such as Google's Titans architecture, explores more dynamic memory updating during inference.

<details><summary>References</summary>
<ul>
<li><a href="https://research.google/blog/titans-miras-helping-ai-have-long-term-memory/">Titans + MIRAS: Helping AI have long-term memory</a></li>
<li><a href="https://zylos.ai/research/2026-04-05-ai-agent-memory-architectures-persistent-knowledge/">AI Agent Memory Architectures: From Context Windows to ...</a></li>

</ul>
</details>

**Tags**: `#AI Memory`, `#Abstractions`, `#Persistent Context`, `#Reasoning Patterns`

---

<a id="item-34"></a>
## [First RTCA Workshop at NeurIPS 2026 on Real-Time Multimodal Agents](https://www.reddit.com/r/MachineLearning/comments/1uy8e0v/cfp_rtca_neurips_2026_r/) ⭐️ 6.0/10

The inaugural Real-Time Conversational Agents (RTCA) Workshop at NeurIPS 2026 has issued a call for papers and demos, focusing on real-time multimodal conversational agents including streaming speech, video, and language generation. This workshop addresses the critical gap in benchmarks and methodology for interactive naturalness in real-time multimodal systems, which is essential for advancing conversational AI beyond offline generation. The workshop is non-archival, with submission deadlines in August 2026 and topics including turn-taking, full-duplex models, and evaluation of live systems. It will be held in Sydney, Australia on December 11 or 12, 2026.

reddit · r/MachineLearning · /u/Few-Ferret9700 · Jul 16, 16:51

**Background**: Real-time conversational agents aim to interact naturally via speech, video, and gestures simultaneously, requiring full-duplex communication where both parties can speak and listen at once. Unlike offline generation, these systems must handle latency, interruptions, and cross-modal alignment, which remain unsolved challenges in the field. The RTCA workshop provides a dedicated venue for researchers from speech, vision, language, HCI, and ML systems to collaborate on these issues.

<details><summary>References</summary>
<ul>
<li><a href="https://duplexio.ai/">duplexio - Full - Duplex Conversational AI</a></li>
<li><a href="https://dl.acm.org/doi/10.1145/3536221.3556601">Real - Time Multimodal Emotion Recognition in Conversation for...</a></li>

</ul>
</details>

**Tags**: `#NeurIPS`, `#conversational AI`, `#multimodal interaction`, `#real-time systems`, `#workshop`

---

<a id="item-35"></a>
## [Apple Rumored to Launch Smart Home Hub, New Apple TV, HomePod in Fall](https://www.macrumors.com/2026/07/15/apple-smart-home-lineup-rumors/) ⭐️ 6.0/10

Apple is expected to launch a multi-product smart home lineup this fall, including a 7-inch screen-equipped Home Hub priced around $350, a new Apple TV 4K with A17 Pro chip, updated HomePod and HomePod mini with new chips, and its first home security camera supporting 4K recording and AI summaries. This lineup would significantly expand Apple's presence in the smart home market, creating a more integrated ecosystem that competes directly with Amazon and Google. The new products could accelerate adoption of Matter and Thread protocols, benefiting the broader smart home industry. The Home Hub features a square screen, wall-mountable or with a hemispherical speaker base, a built-in camera for video calls and facial recognition, and runs Safari, Calendar, and Home apps. The new Apple TV 4K may include an N1 network chip supporting Wi-Fi 7, Bluetooth 6, and Thread, enabling Apple Intelligence and Siri AI.

telegram · zaihuapd · Jul 16, 03:50

**Background**: Apple already offers HomePod, HomePod mini, and Apple TV as home hubs that let users control smart home accessories remotely and automate tasks. Thread is a low-power, mesh networking protocol that provides secure, reliable connectivity for smart home devices, while Apple Intelligence is a suite of AI features that enhance Siri and other system functions. These new products would likely leverage both technologies.

<details><summary>References</summary>
<ul>
<li><a href="https://www.macrumors.com/2025/11/05/apple-smart-home-hub-2026-rumors/">Apple's 2026 Smart Home Revamp: All the Rumors - MacRumors</a></li>
<li><a href="https://www.smarthomeperfected.com/thread/">Thread Protocol Explained: The Smart Home Guide (2026) Matter vs Thread vs Zigbee: Smart Home Protocol Comparison 2026 What Is Thread? Matter’s Smart Home Network Protocol ... Smart Home Protocols 2026: Matter, Thread, Zigbee, Z-Wave Matter & Thread: Smart Home | Thread Border | Beyond Tomorrow Thread Images</a></li>
<li><a href="https://en.wikipedia.org/wiki/Apple_Intelligence">Apple Intelligence</a></li>

</ul>
</details>

**Tags**: `#苹果`, `#智能家居`, `#Home Hub`, `#Apple TV`, `#HomePod`

---