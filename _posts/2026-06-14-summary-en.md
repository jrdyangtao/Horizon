---
layout: default
title: "Horizon Summary: 2026-06-14 (EN)"
date: 2026-06-14
lang: en
---

> From 59 items, 20 important content pieces were selected

---

1. [US Government Suspends Access to Anthropic's Fable 5 and Mythos 5](#item-1) ⭐️ 10.0/10
2. [ROI-Based KV Cache Allocation Achieves 80% Compression with Minimal Loss](#item-2) ⭐️ 9.0/10
3. [Rio's Homegrown LLM Exposed as Weight-Space Merge of Existing Models](#item-3) ⭐️ 8.0/10
4. [2014 Talk Foresaw JavaScript as Compilation Target and Global Crisis](#item-4) ⭐️ 8.0/10
5. [Jane Street Blog Post Sparks Debate on Formal Methods and Future Programming](#item-5) ⭐️ 8.0/10
6. [Hacker News Thread Challenges the AI for Everything Hype](#item-6) ⭐️ 8.0/10
7. [Pyodide Now Supports Publishing WASM Wheels Directly to PyPI](#item-7) ⭐️ 8.0/10
8. [75 US Data Center Projects Worth $130B Blocked in Q1 2026](#item-8) ⭐️ 8.0/10
9. [Huawei Open-Sources Pangu 2.0: 505B and 92B Models with 512K Context](#item-9) ⭐️ 8.0/10
10. [Caddy compatibility for zeroserve: 3x throughput and 70% lower latency](#item-10) ⭐️ 7.0/10
11. [Indexing 669 GB GoPro Videos Locally on M1 Max with ML](#item-11) ⭐️ 7.0/10
12. [Introducing the Verifier Tax: Safety-Success Tradeoffs in Tool-Using LLM Agents](#item-12) ⭐️ 7.0/10
13. [Kage: Package Websites into a Single Binary for Offline Viewing](#item-13) ⭐️ 6.0/10
14. [luau-wasm 0.1a0: Pre-Alpha Library for Luau Scripting in Pyodide WebAssembly](#item-14) ⭐️ 6.0/10
15. [Mapping SQLite result columns back to source tables](#item-15) ⭐️ 6.0/10
16. [Simon Willison Upgrades OpenAI WebRTC Tool with GPT-Realtime-2 and Document Context](#item-16) ⭐️ 6.0/10
17. [Free Bilingual English/Persian ML Notebook Course Seeks Feedback](#item-17) ⭐️ 6.0/10
18. [PaddleOCR v3-v6 Implemented in C++ with ncnn for Lightweight Deployment](#item-18) ⭐️ 6.0/10
19. [Derivative-Free MDP Method Trains Neural Network on MNIST, Beats Adam](#item-19) ⭐️ 6.0/10
20. [Telegram to Launch Extended Markdown Support This Month](#item-20) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [US Government Suspends Access to Anthropic's Fable 5 and Mythos 5](https://simonwillison.net/2026/Jun/13/us-government-directive-to-suspend-access/#atom-everything) ⭐️ 10.0/10

On June 13, 2026, the US government issued an export control directive forcing Anthropic to abruptly disable its latest Fable 5 and Mythos 5 models for all customers worldwide, citing national security concerns over a potential jailbreak. This unprecedented government action to restrict access to widely available AI models raises significant concerns about AI regulation, export controls, and the balance between safety and innovation, potentially setting a precedent for future AI restrictions. The directive targets any foreign national, including Anthropic employees, and was based on a purported jailbreak that Anthropic claims is not unique to its models, with comparable capabilities in other models like GPT-5.5. Only Fable 5 and Mythos 5 were affected, while other Anthropic models remain available.

rss · Simon Willison · Jun 13, 01:01

**Background**: Fable 5 is the public release of Anthropic's Mythos-class models, known for advanced reasoning and coding. Mythos 5 is the more powerful restricted version. AI jailbreaking refers to techniques that bypass model safeguards to elicit unintended behaviors. The US government can impose export controls under national security authorities.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/news/claude-fable-5-mythos-5">Claude Fable 5 and Claude Mythos 5 - Anthropic</a></li>
<li><a href="https://www.reddit.com/r/Anthropic/comments/1u4wjbi/fable_5_was_the_best_model_out_there_anyone_think/">Fable 5 was the best model out there — anyone think it's actually coming back after the gov directive? : r/Anthropic - Reddit</a></li>
<li><a href="https://en.wikipedia.org/wiki/AI_jailbreaking">AI jailbreaking</a></li>

</ul>
</details>

**Discussion**: On Reddit, users widely lament the loss of Fable 5, calling it the best model, and question whether the jailbreak justification was sufficient. Many express concern about government overreach and doubt the model will return.

**Tags**: `#AI regulation`, `#export controls`, `#Anthropic`, `#national security`, `#Fable 5`

---

<a id="item-2"></a>
## [ROI-Based KV Cache Allocation Achieves 80% Compression with Minimal Loss](https://mp.weixin.qq.com/s?__biz=MzIzNjc1NzUzMw==&mid=2247897349&idx=2&sn=14ceeec45a2f6803e40bc7b029964120) ⭐️ 9.0/10

Baidu and Fudan researchers propose a return-on-investment (ROI) strategy for reallocating KV cache, achieving 80% compression with only 0.52% performance loss. This work has been accepted at ICML 2026. This ROI-driven approach challenges the conventional practice of retaining entire KV caches, offering a principled method to drastically reduce memory overhead in LLM inference without significant performance degradation. It could enable more efficient deployment of large models and impact the design of inference serving systems. The method frames KV cache allocation as an investment problem, dynamically retaining only high-ROI tokens. It achieves 80% compression with a mere 0.52% performance drop, indicating near-lossless efficiency gains.

rss · 量子位 · Jun 14, 04:00

**Background**: The KV cache is a standard optimization in Transformer-based LLMs that stores previously computed key and value vectors to speed up token generation. As sequence length grows, the cache memory becomes a bottleneck. Most compression methods use fixed rules or simple importance scores. This work treats cache management as a resource allocation problem under a budget, using an ROI metric to evaluate which entries are worth keeping.

<details><summary>References</summary>
<ul>
<li><a href="https://magazine.sebastianraschka.com/p/coding-the-kv-cache-in-llms">Understanding and Coding the KV Cache in LLMs from Scratch</a></li>
<li><a href="https://arxiv.org/abs/2603.20397">[2603.20397] KV Cache Optimization Strategies for Scalable and Efficient LLM Inference</a></li>

</ul>
</details>

**Tags**: `#KV Cache`, `#LLM Optimization`, `#ICML 2026`, `#Model Compression`, `#Inference Efficiency`

---

<a id="item-3"></a>
## [Rio's Homegrown LLM Exposed as Weight-Space Merge of Existing Models](https://github.com/nex-agi/Nex-N2/issues/4) ⭐️ 8.0/10

The municipality of Rio de Janeiro released Rio-3.5-Open-397B as a novel fine-tune, but analysis reveals it is a weight-space merge of approximately 60% Nex-N2 Pro and 40% Qwen3.5-397B-A17B, with no novel training. This incident highlights ethical concerns around misattributed model releases and demonstrates the surprising effectiveness of simple weight interpolation, which could influence how open-source models are developed and credited. Every weight tensor matches the 0.6/0.4 blend to thousands of standard deviations across all layers, confirming a direct merge with no fine-tuning; Rio-3.5-Open-397B was released shortly after Nex-N2 Pro, and benchmarks show merged performance can surpass individual models.

hackernews · unrvl22 · Jun 14, 15:37 · [Discussion](https://news.ycombinator.com/item?id=48528371)

**Background**: Model merging via weight averaging combines parameters from multiple fine-tuned models sharing a common architecture and initialization. This simple interpolation often works well for tasks like mixing capabilities, as the models operate in a shared loss landscape. The Nex-N2 Pro model was released about a week before Rio's model, and both are based on the Qwen architecture.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/html/2412.12153v1">Revisiting Weight Averaging for Model Merging</a></li>

</ul>
</details>

**Discussion**: Commenters express amazement at the robustness of deep learning models that a linear blend enhances performance, while others note the attribution issue of profiting without credit; there is curiosity about the technical process of weight merging versus distillation.

**Tags**: `#LLM`, `#model merging`, `#open source`, `#attribution`, `#AI ethics`

---

<a id="item-4"></a>
## [2014 Talk Foresaw JavaScript as Compilation Target and Global Crisis](https://www.destroyallsoftware.com/talks/the-birth-and-death-of-javascript) ⭐️ 8.0/10

A 2014 talk by Destroy All Software titled 'The Birth and Death of JavaScript' has recently been revisited by the community, highlighting its humorous yet prescient forecast that JavaScript would become the dominant compilation target and that a global catastrophe would occur between 2020-2025. This retrospective underscores the talk's uncanny accuracy in foreseeing key trends such as the rise of asm.js, WebAssembly, and Electron, and it prompts reflection on JavaScript's pervasive role in modern software development despite predictions of its demise. The talk specifically predicted asm.js as a compilation target, which later evolved into WebAssembly; it even joked about a global disaster in 2020-2025, which some see as a nod to the COVID-19 pandemic. Community members note that while WebAssembly lacks direct DOM access, JavaScript remains essential as glue code, and Electron has brought web technologies to desktop apps.

hackernews · subset · Jun 14, 12:38 · [Discussion](https://news.ycombinator.com/item?id=48526661)

**Background**: asm.js, introduced in 2013, was a strict subset of JavaScript optimized for compiling C/C++ code to run near-natively in browsers, developed by Mozilla. It was later superseded by WebAssembly, a portable binary-code format that enables high-performance execution on web pages. Electron is a framework that allows developers to build desktop applications using web technologies like HTML, CSS, and JavaScript. The talk humorously traced a fictional history from JavaScript's creation to its eventual replacement, touching on these concepts before they became mainstream.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Asm.js">Asm.js</a></li>
<li><a href="http://asmjs.org/">asm.js</a></li>

</ul>
</details>

**Discussion**: Commenters express admiration for the talk's foresight, with one noting the global disaster prediction was correct in timing but wrong in type. Others highlight the progression from asm.js to WebAssembly, the use of Electron, and the ongoing role of JavaScript as glue code. Some express disappointment that WebAssembly hasn't advanced as quickly for direct DOM manipulation, requiring continued reliance on JavaScript or rendering to canvas.

**Tags**: `#JavaScript`, `#WebAssembly`, `#programming-languages`, `#retrospectives`, `#future-predictions`

---

<a id="item-5"></a>
## [Jane Street Blog Post Sparks Debate on Formal Methods and Future Programming](https://blog.janestreet.com/formal-methods-at-jane-street-index/?from_theconsensus=1) ⭐️ 8.0/10

Jane Street's recent blog post on formal methods ignited a lively discussion on Hacker News, exploring the role and limitations of formal verification, practical tools like Lean, and the impact of AI on code generation and verification. The debate underscores the tension between formal methods' promise of correctness and their practical limits, particularly as AI-driven code generation increases the need for robust verification techniques. The discussion referenced tools like the Lean framework for verified frontends and historical provers such as Boyer-Moore. Key limitations noted include the difficulty of matching formal specifications to messy real-world domains and the challenge of lemma generation in automated proofs.

hackernews · eatonphil · Jun 14, 12:35 · [Discussion](https://news.ycombinator.com/item?id=48526633)

**Background**: Formal methods are mathematically based techniques for specifying, developing, and verifying software and hardware systems. They employ logic, formal semantics, and automated theorem proving to ensure correctness. While highly effective in domains like financial trading and aerospace, their use is often limited by the complexity of modeling real-world systems and the effort required.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Formal_methods">Formal methods</a></li>
<li><a href="https://www.reddit.com/r/compsci/comments/sh9owb/formal_verification_methods_in_industry/">Formal Verification Methods in industry : r/compsci - Reddit</a></li>

</ul>
</details>

**Discussion**: Community members expressed mixed views: some were skeptical about formal methods' practicality beyond deterministic algorithms, while others shared tools like a Lean framework for frontend verification. Historical insights highlighted the difficulty of lemma generation, and some commenters argued that AI-generated code will increase the need for formal verification. A common concern was that formal specs often feel like duplicating work.

**Tags**: `#formal-methods`, `#software-verification`, `#programming`, `#ai`, `#software-engineering`

---

<a id="item-6"></a>
## [Hacker News Thread Challenges the AI for Everything Hype](https://gabrielweinberg.com/p/people-are-consuming-ai-like-they) ⭐️ 8.0/10

A Hacker News thread shares real-world experiences that counter the narrative of universal AI adoption, revealing hesitant employers, literacy barriers, and cases where replacing deterministic systems with LLMs made things worse. This discussion challenges the prevailing AI hype by highlighting significant adoption barriers, and underscores that the rush to integrate LLMs can degrade user experience, affecting both job seekers and businesses. Notable points include companies replacing deterministic support flows with slower, worse LLM versions, and a comment noting that 27% of U.S. working-age adults have very low literacy (PIAAC Level 1 or below), limiting AI usability. Additionally, LLM code generation for native Swift apps required significant human oversight.

hackernews · yegg · Jun 14, 14:44 · [Discussion](https://news.ycombinator.com/item?id=48527700)

**Background**: Large language models (LLMs) are a type of AI that can generate and understand text, powering chatbots and code assistants. In recent years, there has been a narrative that 'everyone is using AI for everything,' but this thread provides a reality check. The PIAAC (Program for the International Assessment of Adult Competencies) measures adults' literacy skills, with Level 1 indicating very basic reading ability.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Large_language_model">Large language model - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters expressed a mix of caution and skepticism. One described the difficulty of discussing LLM use in job interviews due to unknown employer attitudes. Others highlighted that low adult literacy rates make AI adoption challenging, and noted frustration with companies degrading deterministic systems with LLMs. Some shared personal mixed experiences, finding LLMs helpful for coding but requiring heavy human oversight, especially for native app development.

**Tags**: `#AI adoption`, `#LLM skepticism`, `#technology hype`, `#user experience`, `#hacker news discussion`

---

<a id="item-7"></a>
## [Pyodide Now Supports Publishing WASM Wheels Directly to PyPI](https://simonwillison.net/2026/Jun/13/publishing-wasm-wheels/#atom-everything) ⭐️ 8.0/10

Pyodide 314.0 introduces the ability for package maintainers to publish WebAssembly (WASM) wheels directly to PyPI, eliminating the previous requirement for manual review and hosting by the Pyodide team. This allows any Python package built for the PyEmscripten platform to be distributed via PyPI and installed at runtime using micropip. This change significantly reduces the maintenance burden on Pyodide maintainers and removes a major bottleneck for the ecosystem, enabling decentralized publishing and faster growth. It also aligns Pyodide with standard Python packaging practices, making it easier for developers to support browser-based Python environments. The support relies on the PyEmscripten platform tag defined in PEP 783, and the PyPI infrastructure update (PR #19804) landed on April 21st. The author demonstrated the process by publishing 'luau-wasm', a 276KB wheel that bundles a Luau interpreter compiled to WASM.

rss · Simon Willison · Jun 13, 23:55

**Background**: WebAssembly (Wasm) is a portable binary code format that enables high-performance applications on web pages. Pyodide is a port of CPython to WebAssembly/Emscripten, allowing Python to run in the browser. Previously, distributing Python packages with C extensions for Pyodide required manual intervention from maintainers.

<details><summary>References</summary>
<ul>
<li><a href="https://pyodide.org/">Pyodide</a></li>
<li><a href="https://pyodide.org/en/stable/development/abi.html">The PyEmscripten Platform — Version 0.29.4</a></li>
<li><a href="https://webassembly.org/">WebAssembly</a></li>

</ul>
</details>

**Tags**: `#WebAssembly`, `#Pyodide`, `#Python`, `#PyPI`, `#packaging`

---

<a id="item-8"></a>
## [75 US Data Center Projects Worth $130B Blocked in Q1 2026](https://www.tomshardware.com/tech-industry/artificial-intelligence/more-than-75-data-center-build-outs-worth-usd130-billion-have-been-successfully-blocked-in-the-first-four-months-of-2026-bipartisan-opposition-mounts-nationwide-over-fears-of-soaring-power-and-water-costs) ⭐️ 8.0/10

In the first quarter of 2026, over 75 data center construction projects across the United States, valued at approximately $130 billion, were blocked or delayed, equaling the total number blocked in all of 2025. This wave of opposition, driven by concerns over soaring energy and water consumption, signals a major regulatory and community pushback that could significantly constrain the expansion of AI and cloud infrastructure in the US. Grassroots opposition groups surged from 396 to 833 in three months across 49 states, and numerous state and federal regulatory bills have been introduced, including proposals to pause data center construction.

telegram · zaihuapd · Jun 14, 03:03

**Background**: Data centers are essential for modern AI and cloud computing, housing thousands of servers that require enormous amounts of electricity for operation and cooling. A single large data center can consume as much power as a small city. Additionally, many data centers use millions of gallons of water daily for cooling, straining local water resources. This has led to growing environmental and community concerns, especially as the AI boom accelerates data center construction.

**Tags**: `#data centers`, `#regulation`, `#energy`, `#AI infrastructure`, `#environment`

---

<a id="item-9"></a>
## [Huawei Open-Sources Pangu 2.0: 505B and 92B Models with 512K Context](https://t.me/zaihuapd/41948) ⭐️ 8.0/10

At Huawei Developer Conference 2026, Huawei open-sourced the Pangu 2.0 large language models, including a 505B-parameter Pro version and a 92B-parameter Flash version, both supporting a 512K context window and optimized for Ascend hardware and HarmonyOS, with pretraining code and other components to be released starting June 30. This release strengthens China's domestic AI ecosystem by providing large-scale models optimized for Huawei's own hardware and software stack, potentially reducing reliance on foreign technologies and accelerating the adoption of Ascend and HarmonyOS in AI development. The models feature up to 512K context length; the Pro version excels in complex reasoning while the Flash version offers faster inference; pretraining code release is scheduled from June 30, along with other components. Yu Chengdong noted that Huawei's own compute resources are limited due to supporting other domestic companies.

telegram · zaihuapd · Jun 14, 08:05

**Background**: Huawei's Ascend series (e.g., Ascend 910) are AI processors designed for training and inference, competing with NVIDIA GPUs. HarmonyOS is Huawei's distributed operating system used across smartphones, tablets, and other devices. Open-sourcing Pangu 2.0 enables developers to build and deploy AI applications natively on this hardware-software stack, fostering a self-reliant ecosystem.

<details><summary>References</summary>
<ul>
<li><a href="https://www.sciencedirect.com/book/9780128234884/ascend-ai-processor-architecture-and-programming">Ascend AI Processor Architecture and Programming | ScienceDirect</a></li>
<li><a href="https://en.wikipedia.org/wiki/HarmonyOS">HarmonyOS</a></li>

</ul>
</details>

**Tags**: `#Huawei`, `#large language model`, `#open-source`, `#Ascend`, `#HarmonyOS`

---

<a id="item-10"></a>
## [Caddy compatibility for zeroserve: 3x throughput and 70% lower latency](https://su3.io/posts/zeroserve-caddy-compat) ⭐️ 7.0/10

The post highlights a performance breakthrough: zeroserve achieves 3x throughput and 70% lower latency with Caddy configuration compatibility. However, it lacks crucial features like ACME. The performance improvements demonstrate the potential of eBPF and io_uring in web servers, challenging traditional servers like NGINX, while the missing ACME support highlights the trade-offs in adopting new technologies. zeroserve runs sandboxed eBPF scripts JIT-compiled to native code and uses io_uring for asynchronous I/O, but the current Caddy compatibility omits ACME, plugins, and other standard features, making it less practical for production.

hackernews · losfair · Jun 14, 13:43 · [Discussion](https://news.ycombinator.com/item?id=48527145)

**Background**: zeroserve is an experimental web server that leverages eBPF to sandbox request-handling scripts, combined with io_uring for efficient asynchronous I/O. eBPF (extended Berkeley Packet Filter) is a Linux kernel technology that safely executes user-supplied programs in the kernel without risking stability. Caddy is a popular web server that simplifies HTTPS management through ACME (Automatic Certificate Management Environment), a protocol for automating TLS certificate lifecycle. Traditional servers like NGINX have long dominated the market with battle-tested performance and extensive feature sets.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/losfair/zeroserve">GitHub - losfair/zeroserve: Zero-config, fast `io_uring`-based HTTPS server.</a></li>
<li><a href="https://en.wikipedia.org/wiki/EBPF">EBPF</a></li>

</ul>
</details>

**Discussion**: The discussion reveals mixed sentiment: many users consider the lack of ACME a dealbreaker, labeling the Caddy compatibility as hollow without essential features and arguing that NGINX remains superior. Others express surprise at NGINX's enduring performance, and one commenter questions eBPF's Turing-completeness due to verifier limitations.

**Tags**: `#performance`, `#web-servers`, `#ebpf`, `#caddy`, `#networking`

---

<a id="item-11"></a>
## [Indexing 669 GB GoPro Videos Locally on M1 Max with ML](https://news.ycombinator.com/item?id=48528029) ⭐️ 7.0/10

A developer indexed 628 GoPro cycling videos, totaling 668.68 GB, using local ML models on an M1 Max. This enables natural language search and clip extraction directly to DaVinci Resolve. This project shows that powerful video indexing and semantic search can be achieved on consumer-grade hardware using open-source models, offering a private, offline alternative to cloud-based video AI services. The M1 Max's ARM-based SoC shows CPU performance akin to an 11th-gen Intel i9 for local ML tasks. Frame-level embedding, while effective for object and scene search, can overlook action dynamics, highlighting a limitation compared to clip-level embeddings.

hackernews · iliashad · Jun 14, 15:13

**Background**: Video indexing uses machine learning models to analyze and tag visual content, enabling text-based search across large collections. GoPro cameras generate high-quality but often unstructured footage, making manual review tedious. Running ML models locally on devices like the M1 Max keeps data private and avoids cloud subscription fees, while still leveraging AI capabilities for tasks like object detection and scene classification.

<details><summary>References</summary>
<ul>
<li><a href="https://aws.amazon.com/blogs/machine-learning/implement-semantic-video-search-using-open-source-large-vision-models-on-amazon-sagemaker-and-amazon-opensearch-serverless/">Implement semantic video search using open source large vision models on Amazon SageMaker and Amazon OpenSearch Serverless | Artificial Intelligence</a></li>
<li><a href="https://github.com/czarinagluna/ml-powered-video-library">GitHub - czarinagluna/ml-powered-video-library: Machine learning-powered video library that returns accurate results given search queries based on the features: audio, onscreen text, and image objects</a></li>

</ul>
</details>

**Discussion**: Commenters noted the similarity to a recent HN post about the same machine and techniques, and highlighted that DaVinci Resolve Studio already offers AI-based indexing. There was discussion about M1 Max's ARM-based CPU performance compared to Intel, and a lighthearted query about adult video collections.

**Tags**: `#local-ml`, `#video-indexing`, `#gopro`, `#m1-max`, `#personal-project`

---

<a id="item-12"></a>
## [Introducing the Verifier Tax: Safety-Success Tradeoffs in Tool-Using LLM Agents](https://www.reddit.com/r/MachineLearning/comments/1u58mkq/the_verifier_tax_horizondependent_safetysuccess/) ⭐️ 7.0/10

A new framework separates outcomes into safe success, unsafe success, and failure for tool-using LLM agents. It identifies a horizon-dependent tradeoff termed the 'Verifier Tax,' where verification reduces unsafe successes but also lowers task completion as interaction turns increase. As LLM agents are increasingly deployed in real-world tool-use scenarios, safety is critical. This work uncovers a fundamental tradeoff that developers must navigate: adding verification improves safety but may impair agent effectiveness, directly impacting high-stakes applications. Experiments on the τ-bench benchmark reveal model-dependent interaction horizons (15–30 turns). The proposed two-tier verification architecture applies deterministic policy/tool checks first, then an LLM-based verifier for context-sensitive safety cases.

reddit · r/MachineLearning · /u/AccomplishedLeg1508 · Jun 14, 02:09

**Background**: Tool-using LLM agents are AI systems that call external tools (e.g., APIs, databases) to perform tasks. Evaluating them is challenging because task completion alone can hide safety violations. τ-bench is a benchmark simulating realistic tool-agent-user conversations with domain policies. The ACM Conference on AI in Society (CAIS) focuses on societal impacts of AI, providing a venue for safety research.

<details><summary>References</summary>
<ul>
<li><a href="https://www.caisconf.org/program/2026/papers/the-verifier-tax-horizon-dependent-safety-success-tradeoffs-in-tool-using-llm-ag/">The Verifier Tax: Horizon Dependent Safety–Success Tradeoffs in Tool Using LLM Agents</a></li>
<li><a href="https://dl.acm.org/doi/full/10.1145/3786335.3813160">The Verifier Tax: Horizon Dependent Safety--Success Tradeoffs in Tool Using LLM Agents</a></li>
<li><a href="https://arxiv.org/abs/2406.12045">[2406.12045] $τ$-bench: A Benchmark for Tool-Agent-User Interaction in Real-World Domains</a></li>

</ul>
</details>

**Tags**: `#LLM agents`, `#AI safety`, `#safety evaluation`, `#verification`, `#tool use`

---

<a id="item-13"></a>
## [Kage: Package Websites into a Single Binary for Offline Viewing](https://github.com/tamnd/kage) ⭐️ 6.0/10

Kage is a new Go-based CLI tool that downloads an entire website and bundles it into a single, self-contained binary for offline viewing, with JavaScript stripped out. It simplifies offline archiving of web content, making it trivial to share or deploy websites in environments without internet access, such as remote documentation or in-flight reading. The tool is built in Go, packages all assets into one binary, and strips JavaScript by default. However, it currently lacks rate-limiting, which could impose heavy load on target sites, and does not support partial crawling.

hackernews · tamnd · Jun 14, 17:25 · [Discussion](https://news.ycombinator.com/item?id=48529990)

**Background**: Web archiving tools capture websites for preservation or offline use. Kage uses Go to produce a self-contained executable that includes an HTTP server, so the archived site can be viewed without extra dependencies. Similar tools like SingleFile also create offline copies but store them as single HTML files.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/tamnd/kage">GitHub - tamnd/kage: Shadow any website for offline viewing, with the JavaScript stripped out · GitHub</a></li>

</ul>
</details>

**Discussion**: Users noted SingleFile as a more robust alternative, suggested use cases like offline company wikis, and raised concerns about server load. Some appreciated the single-binary approach but desired features like limiting crawl speed and scope.

**Tags**: `#web-archiving`, `#offline-first`, `#cli`, `#golang`, `#developer-tools`

---

<a id="item-14"></a>
## [luau-wasm 0.1a0: Pre-Alpha Library for Luau Scripting in Pyodide WebAssembly](https://simonwillison.net/2026/Jun/13/luau-wasm/#atom-everything) ⭐️ 6.0/10

The pre-alpha library luau-wasm 0.1a0 has been released, enabling the execution of Luau scripts within WebAssembly environments via Pyodide, a Python distribution for the browser. This integration allows developers to leverage Luau's scripting capabilities in web-based Python applications, extending the reach of the Luau language beyond gaming platforms into broader web development contexts. The release is in pre-alpha stage, meaning it is not production-ready and may have limited functionality. It includes support for publishing WASM wheels to PyPI, facilitating distribution for Pyodide projects.

rss · Simon Willison · Jun 13, 23:14

**Background**: Luau is a scripting language derived from Lua 5.1, developed by Roblox, featuring gradual typing and sandboxing. Pyodide is a Python distribution that runs in browsers and Node.js via WebAssembly, allowing Python code to execute in web environments. WASM wheels are packages compiled to WebAssembly, enabling native-speed execution of code in browser contexts. This library combines these technologies to enable Luau scripting within Pyodide's Python ecosystem.

<details><summary>References</summary>
<ul>
<li><a href="https://luau.org/">Luau | Luau</a></li>
<li><a href="https://pyodide.org/">Pyodide — Version 314.0.0</a></li>

</ul>
</details>

**Tags**: `#lua`, `#webassembly`, `#pyodide`, `#python`, `#scripting`

---

<a id="item-15"></a>
## [Mapping SQLite result columns back to source tables](https://simonwillison.net/2026/Jun/13/sqlite-column-provenance/#atom-everything) ⭐️ 6.0/10

Simon Willison explores techniques to map columns in SQL query results to their originating tables, a feature needed for enhancing Datasette's arbitrary query capabilities. This could allow Datasette to enrich query results with context like column descriptions and foreign key relationships, improving data exploration for users. Solutions include using the apsw library, calling the SQLite C function sqlite3_column_table_name via ctypes, and analyzing EXPLAIN output; the work was assisted by Claude Code (Opus 4.8).

rss · Simon Willison · Jun 13, 23:05

**Background**: Datasette is an open-source tool for exploring and publishing data, often using SQLite databases. In SQL, a Common Table Expression (CTE) is a temporary result set that can simplify complex queries. Mapping result columns back to their source tables is a form of data lineage, helping users understand the origin of data.

<details><summary>References</summary>
<ul>
<li><a href="https://datasette.io/">Datasette: An open source multi-tool for exploring and publishing data</a></li>
<li><a href="https://www.reddit.com/r/SQL/comments/1353051/can_someone_explain_to_me_in_a_way_like_im/">Can someone explain to me in a way (like I'm literally 5) what a CTE does? : r/SQL - Reddit</a></li>

</ul>
</details>

**Tags**: `#sqlite`, `#datasette`, `#sql`, `#column-provenance`, `#research`

---

<a id="item-16"></a>
## [Simon Willison Upgrades OpenAI WebRTC Tool with GPT-Realtime-2 and Document Context](https://simonwillison.net/2026/Jun/12/openai-webrtc/#atom-everything) ⭐️ 6.0/10

Simon Willison updated his browser-based OpenAI WebRTC tool to support the new GPT-Realtime-2 model, which boasts GPT-5-class reasoning, and added a document context feature allowing users to paste text for audio conversations about it. This update demonstrates early adoption of OpenAI's latest voice model, enabling rich, context-aware audio interactions without waiting for official app integration, lowering the barrier for developers and users to experiment with document-based conversational AI. The tool uses the WebRTC API for low-latency audio, and the document context is pasted as plain text before starting a session; the model has a knowledge cutoff of September 30, 2024, and supports voice selection like 'Coral'.

rss · Simon Willison · Jun 12, 23:53

**Background**: WebRTC (Web Real-Time Communication) enables direct audio, video, and data exchange in browsers without plugins. OpenAI's Realtime API uses WebRTC to stream audio to and from its models for low-latency voice interactions. Document context means providing additional text so the model can ground its responses in that information.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/WebRTC">WebRTC - Wikipedia</a></li>
<li><a href="https://www.reddit.com/r/OpenAI/comments/1t8awh4/notes_from_testing_gptrealtime2_with_a/">Notes from testing GPT-Realtime-2 with a context-heavy voice app : r/OpenAI - Reddit</a></li>

</ul>
</details>

**Discussion**: On Reddit and OpenAI forums, users note that GPT-Realtime-2 handles context and follow-up questions better, though some report overly long or slow responses; overall sentiment is positive about its semantic improvements.

**Tags**: `#OpenAI`, `#WebRTC`, `#voice AI`, `#tools`, `#real-time communication`

---

<a id="item-17"></a>
## [Free Bilingual English/Persian ML Notebook Course Seeks Feedback](https://www.reddit.com/r/MachineLearning/comments/1u4zbld/im_building_a_free_bilingual_machinelearning/) ⭐️ 6.0/10

A developer has created an open-source, bilingual English/Persian machine learning tutorial repository in Jupyter Notebook format, and is asking the community for feedback on its structure, content coverage, and practicality. This project addresses the lack of free, accessible ML education for non-native English speakers by providing parallel bilingual notebooks, potentially lowering language barriers and promoting inclusive learning. The GitHub repository covers classical ML topics such as data preprocessing, regression, classification, clustering, and MLOps concepts, with separate English and Persian notebook versions. The author specifically requests input on chapter order, missing topics, and the balance between theory and hands-on practice.

reddit · r/MachineLearning · /u/abolfazl1363 · Jun 13, 19:07

**Background**: Jupyter Notebook is an interactive web-based environment widely used for data science and machine learning education, allowing inline code, visualizations, and explanatory text. Bilingual resources are uncommon in the field, and this project aims to make ML learning more accessible to Persian-speaking learners who may face language obstacles with English-only materials.

**Tags**: `#machine-learning`, `#education`, `#bilingual`, `#open-source`, `#jupyter-notebook`

---

<a id="item-18"></a>
## [PaddleOCR v3-v6 Implemented in C++ with ncnn for Lightweight Deployment](https://www.reddit.com/r/MachineLearning/comments/1u4hy2x/paddleocr_v3v4v5v6_implemented_in_c_with_ncnn_p/) ⭐️ 6.0/10

A C++ implementation of PaddleOCR using the ncnn inference framework now supports PP-OCR models from v3 to v6, enabling lightweight and fast deployment without the complex dependencies of the official Paddle runtime. This tool simplifies deploying PaddleOCR models in resource-constrained environments, making OCR more accessible for mobile, embedded, or edge devices and reducing integration effort compared to the heavy official runtime. The implementation leverages Tencent's ncnn, a high-performance inference framework optimized for mobile platforms with no third-party dependencies. It is hosted on GitHub and supports the latest PP-OCR v6 models.

reddit · r/MachineLearning · /u/Knok0932 · Jun 13, 05:06

**Background**: PaddleOCR is a popular open-source OCR toolkit by Baidu, known for high accuracy and multilingual support. PP-OCR is its series of ultra-lightweight models. ncnn, developed by Tencent, is a lightweight neural network inference engine designed for mobile and embedded deployment. The official Paddle deployment often requires heavyweight dependencies like PaddlePaddle, making it less suitable for lightweight scenarios.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/tencent/NCNN">GitHub - Tencent/ncnn: ncnn is a high-performance neural network inference framework optimized for the mobile platform · GitHub</a></li>
<li><a href="https://github.com/PADDLEPADDLE/PADDLEOCR">GitHub - PaddlePaddle/PaddleOCR: Turn any PDF or image document into structured data for your AI. A powerful, lightweight OCR toolkit that bridges the gap between images/PDFs and LLMs. Supports 100+ languages. · GitHub</a></li>

</ul>
</details>

**Tags**: `#PaddleOCR`, `#ncnn`, `#C++`, `#OCR`, `#deployment`

---

<a id="item-19"></a>
## [Derivative-Free MDP Method Trains Neural Network on MNIST, Beats Adam](https://www.reddit.com/r/MachineLearning/comments/1u4fc16/derivativefree_neural_network_optimization_mnist/) ⭐️ 6.0/10

A derivative-free optimization method called MDP was used to directly optimize the 25,450 parameters of a 784-32-10 neural network on MNIST, achieving 93.4% test accuracy with 1 million function evaluations, surpassing Adam's 91.7%. This demonstrates that derivative-free methods can train neural networks without backpropagation, which is valuable when gradients are unavailable or costly to compute, and may open new approaches for optimization in high-dimensional spaces. The experiment used only 5,000 training images and converged after 1 million function evaluations. The MDP method achieved a loss of 0.0004083, while the network has 25,450 total parameters. The code is available on GitHub.

reddit · r/MachineLearning · /u/Mis4318 · Jun 13, 02:51

**Background**: Derivative-free optimization does not rely on gradient information; instead, it directly searches the parameter space. This is an alternative to gradient-based methods like Adam, which are standard in deep learning. MNIST is a well-known dataset of handwritten digits for benchmarking machine learning models. The network architecture 784-32-10 refers to an input layer of 784 neurons (28x28 pixels), one hidden layer of 32, and an output layer of 10 digits.

<details><summary>References</summary>
<ul>
<li><a href="https://www.reddit.com/r/MachineLearning/comments/1u4fc16/derivativefree_neural_network_optimization_mnist/">Derivative-Free Neural Network Optimization: MNIST Case [R] : r/MachineLearning - Reddit</a></li>
<li><a href="https://medium.com/@joragasy/optimize-neural-network-with-gradient-free-methods-using-pytorch-and-nevergrad-399a9f4a5c21">Optimize Neural Network With Gradient-Free Methods Using Pytorch and Nevergrad. | by Maheritiana Jonathan Jeremie Randriarison | Medium</a></li>

</ul>
</details>

**Tags**: `#derivative-free optimization`, `#neural networks`, `#MNIST`, `#MDP`, `#optimization`

---

<a id="item-20"></a>
## [Telegram to Launch Extended Markdown Support This Month](https://x.com/durov/status/2065899497289392440) ⭐️ 6.0/10

Telegram founder Pavel Durov announced that extended Markdown formatting—including tables, nested lists, inline media, formulas, and headers—will roll out to users this month after bot-side testing. This upgrade significantly enhances message formatting for both users and bot developers, making Telegram more competitive with other rich-text messaging platforms and improving content presentation. The extended Markdown features are currently available to bots for testing; the full rollout to all users is expected by the end of this month.

telegram · zaihuapd · Jun 14, 11:08

**Background**: Telegram already supports basic Markdown in messages. The extended Markdown will introduce advanced formatting commonly used in documentation or rich-text editors, particularly useful for bots that generate structured content like reports or tables. The announcement was made by founder Pavel Durov on his official channel.

**Tags**: `#telegram`, `#markdown`, `#messaging`, `#formatting`, `#bot-development`

---