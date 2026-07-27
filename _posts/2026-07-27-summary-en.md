---
layout: default
title: "Horizon Summary: 2026-07-27 (EN)"
date: 2026-07-27
lang: en
---

> From 51 items, 28 important content pieces were selected

---

1. [Kimi-K3: 3 Trillion Parameter Open-Weight Model Released](#item-1) ⭐️ 8.0/10
2. [Decathlon Germany Adds Wero Payment for European e-commerce](#item-2) ⭐️ 8.0/10
3. [Forum Software Drops React for HTMX in Migration Case Study](#item-3) ⭐️ 8.0/10
4. [Bun's Rust Rewrite Ships in Claude Code, v1.4 Delayed](#item-4) ⭐️ 8.0/10
5. [Investigation Exposes Chinese LLM Token Relay Market Using Open Source Proxies](#item-5) ⭐️ 8.0/10
6. [Ruff v0.16.0 expands default rules from 59 to 413](#item-6) ⭐️ 8.0/10
7. [Proposal: Formal Pre-Training Gate for Training Data Auditing](#item-7) ⭐️ 8.0/10
8. [ARM64 Assembly YOLO26n Inference from Scratch](#item-8) ⭐️ 8.0/10
9. [4B Open-Weight Models Match o3 on Swedish Medical QA](#item-9) ⭐️ 8.0/10
10. [Claude shared links indexed by search engines, exposing user data](#item-10) ⭐️ 8.0/10
11. [SpaceX Stops Falcon 9 Orders Beyond 2028, Bets on Starship](#item-11) ⭐️ 8.0/10
12. [Google's Gemini 4: Most Ambitious Pretraining Yet, Late 2026](#item-12) ⭐️ 8.0/10
13. [Critical RCE vulnerability in Fastjson 1.x without gadget](#item-13) ⭐️ 8.0/10
14. [SMIC Tests China's First Domestic DUV Lithography Machine](#item-14) ⭐️ 8.0/10
15. [Microsoft Unveils MAI-Cyber 1, a Specialized Cybersecurity AI Model](#item-15) ⭐️ 7.0/10
16. [Libsm64: Super Mario 64 repackaged as a reusable library](#item-16) ⭐️ 7.0/10
17. [3DGS Memory Optimization: Survey Identifies Five Key Directions](#item-17) ⭐️ 7.0/10
18. [LLMs on IMO 2026: Frontier models perfect, harness helps others](#item-18) ⭐️ 7.0/10
19. [Qualcomm Announces Across-the-Board Price Hike from September 1](#item-19) ⭐️ 7.0/10
20. [Huawei-CXMT tensions rise as AI data centers drive memory price hikes](#item-20) ⭐️ 7.0/10
21. [China Rejects US Sanctions Over AI Model Distillation](#item-21) ⭐️ 7.0/10
22. [Moonshot AI to Open-Source Kimi-K3, a 3T-Parameter Model](#item-22) ⭐️ 7.0/10
23. [Data-Driven Investigation: Washing Solar Panels Often Unnecessary](#item-23) ⭐️ 6.0/10
24. [Transformer from Scratch in PyTorch for English-Tamil Translation](#item-24) ⭐️ 6.0/10
25. [Open-source end-to-end edge ML platform with auto-labeling](#item-25) ⭐️ 6.0/10
26. [US Schools Reducing Chromebook Use, Returning to Pen and Paper](#item-26) ⭐️ 6.0/10
27. [CXMT surges 471% on STAR Market debut, setting record IPO](#item-27) ⭐️ 6.0/10
28. [Samsung may use Chinese DRAM to cut costs, boost China market share](#item-28) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Kimi-K3: 3 Trillion Parameter Open-Weight Model Released](https://huggingface.co/moonshotai/Kimi-K3) ⭐️ 8.0/10

Moonshot AI has released Kimi-K3, a 3 trillion parameter open-weight model, on Hugging Face. The model uses native mxfp4 precision and is available under a commercial license with revenue-based restrictions. This release is significant because it pushes the frontier of open-weight models to 3 trillion parameters, enabling unprecedented customization and IP sovereignty for enterprises. It also provides a benchmark for the hosting cost and pricing of extremely large models, which will influence the economics of AI deployment. The model requires approximately 1.5 TB of VRAM for inference due to mxfp4 native precision, and realistically needs 16 x B200 GPUs for context and throughput optimization. The commercial license requires companies with over $20 million in aggregate annual revenue to negotiate a separate agreement with Moonshot AI.

hackernews · nateb2022 · Jul 27, 06:18 · [Discussion](https://news.ycombinator.com/item?id=49065752)

**Background**: An open-weight model allows anyone to download the trained parameters and run the model locally, study it, or fine-tune it for specific tasks, unlike closed APIs. Hosting very large models like Kimi-K3 (3 trillion parameters) is extremely expensive, requiring multiple high-end GPUs with large VRAM. The economics of such deployment involve trade-offs between cost, performance, and control, which this release helps illuminate.

<details><summary>References</summary>
<ul>
<li><a href="https://hai.stanford.edu/ai-definitions/what-is-an-open-weight-model">What is an Open-Weight Model? - Stanford HAI</a></li>
<li><a href="https://arxiv.org/html/2509.18101v1">A Cost-Benefit Analysis of On-Premise Large Language Model Deployment: Breaking Even with Commercial LLM Services</a></li>

</ul>
</details>

**Discussion**: The community discussion focuses on three main areas: the high hosting cost (estimated $3/M tokens input, $15/M tokens output from Fireworks AI), the licensing restrictions that may limit commercial use for larger companies, and the advantage of customization and IP sovereignty for startups. Some commenters also lament the lack of prosumer hardware for running such models.

**Tags**: `#AI`, `#large language models`, `#Kimi-K3`, `#Moonshot AI`, `#open-source`

---

<a id="item-2"></a>
## [Decathlon Germany Adds Wero Payment for European e-commerce](https://www.sgieurope.com/e-commerce/decathlon-germany-launches-wero-payment-on-its-website/122397.article) ⭐️ 8.0/10

Decathlon Germany has integrated Wero, a European mobile payment system built on SEPA instant transfers, as a new payment option on its decathlon.de website. This adoption validates Wero as a viable alternative to credit cards and PayPal in European e-commerce, and signals growing merchant trust in pan-European instant payment infrastructure. Wero relies on the SEPA Instant Credit Transfer (SCT Inst) scheme, which ensures funds are available in the payee's account in under 10 seconds, and the payment process uses QR code scanning and bank app confirmation for a smooth UX.

hackernews · doener · Jul 27, 16:49 · [Discussion](https://news.ycombinator.com/item?id=49072310)

**Background**: Wero is a unified mobile payment system launched in July 2024 by the European Payments Initiative (EPI), consolidating various national systems like Giropay and iDEAL. It leverages SEPA Instant Credit Transfer, a pan-European scheme that enables instant euro transfers between bank accounts in 36 countries. The SEPA instant transfer regulation became mandatory in 2024, requiring banks to offer instant transfers at no extra cost, which provided the infrastructure foundation for Wero.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Wero_(payment)">Wero (payment) - Wikipedia</a></li>
<li><a href="https://www.europeanpaymentscouncil.eu/what-we-do/sepa-instant-credit-transfer">SEPA Instant Credit Transfer - European Payments Council</a></li>
<li><a href="https://www.db.com/news/detail/20251217-deutsche-bank-launches-wero-for-more-simple-and-sovereign-digital-payments-in-europe?language_id=1">Deutsche Bank launches Wero for more simple and sovereign digital payments in Europe</a></li>

</ul>
</details>

**Discussion**: The community was largely positive, praising Wero's smooth UX and snappy payment flow via QR code scanning. One user highlighted Wero's potential for AI agent payments, similar to the Polish Blik system, while another noted that Decathlon itself is technologically advanced, using RFID for self-checkout in Eastern European stores.

**Tags**: `#payments`, `#Wero`, `#SEPA`, `#e-commerce`, `#European payments`

---

<a id="item-3"></a>
## [Forum Software Drops React for HTMX in Migration Case Study](https://misago-project.org/t/removing-reactjs-from-the-codebase-and-adapting-htmx-for-ui-interactivity/1267/) ⭐️ 8.0/10

The Misago forum project detailed its decision to remove React.js from the codebase and adopt HTMX for UI interactivity, replacing client-side rendering with server-rendered hypermedia. This migration highlights a growing trend in web development where teams choose simpler, hypermedia-driven tools like HTMX over heavy front-end frameworks like React, especially for content-focused applications where full SPA complexity is unnecessary. HTMX is a small (~16KB minified and gzipped) JavaScript library that extends HTML with AJAX, WebSockets, and Server-Sent Events, and the migration report notes it reduced codebase size by 67% compared to React.

hackernews · Ralfp · Jul 27, 09:58 · [Discussion](https://news.ycombinator.com/item?id=49067301)

**Background**: HTMX is a front-end library that allows developers to build modern user interfaces using HTML attributes, enabling AJAX, CSS transitions, and server events without writing JavaScript. It follows a hypermedia-driven approach, in contrast to React's component-based client-side rendering. This shift is part of a broader discussion about the complexity of modern web development and the merits of returning to simpler, server-centric architectures.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Htmx">htmx - Wikipedia</a></li>
<li><a href="https://htmx.org/">htmx - high power tools for html</a></li>
<li><a href="https://hypermedia.systems/hypermedia-a-reintroduction/">Hypermedia: A Reintroduction</a></li>

</ul>
</details>

**Discussion**: Community comments were mixed: some praised HTMX for its simplicity and suitability for forum software, while others reported performance issues with interactive filterable lists and scroll position problems. There was agreement that HTMX works well for content-heavy sites but struggles with dynamic UIs requiring fine-grained DOM updates.

**Tags**: `#React`, `#HTMX`, `#web development`, `#migration`, `#hypermedia`

---

<a id="item-4"></a>
## [Bun's Rust Rewrite Ships in Claude Code, v1.4 Delayed](https://lockwood.dev/ai/2026/07/27/how-is-the-bun-rewrite-in-rust-going.html) ⭐️ 8.0/10

Bun creator Jarred announced that the Rust rewrite of the runtime was shipped in Claude Code over a month ago, with few users noticing. The upcoming v1.4 release is delayed until a promised number of newly passing Node.js compatibility tests are met, with the target expected to be reached next Tuesday. This rewrite shifts Bun from Zig to Rust, promising better performance and memory safety, but the reliance on LLM-assisted translation and the resulting delay raise questions about the quality and management of such large-scale rewrites. The debate reflects broader tensions in the software community over using AI tools for core infrastructure projects. The Rust rewrite was largely done using LLMs, specifically Claude Code, to translate the original Zig codebase. Bun v1.4 is postponed because Jarred committed to a specific number of newly passing Node.js tests as a compatibility milestone, and those PRs are not yet merged.

hackernews · tomlockwood · Jul 27, 11:12 · [Discussion](https://news.ycombinator.com/item?id=49067854)

**Background**: Bun is a JavaScript runtime, package manager, and test runner designed as a drop-in replacement for Node.js, originally built in Zig for speed. Claude Code is an AI-powered coding assistant by Anthropic that can edit files, run commands, and automate Git workflows, similar to other LLM coding tools. Rewriting a large project like Bun from one systems language to another is a massive undertaking, often justified by performance or safety gains.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Bun_(software)">Bun (software) - Wikipedia</a></li>
<li><a href="https://bun.sh/">Bun — A fast all-in-one JavaScript runtime</a></li>
<li><a href="https://docs.anthropic.com/en/docs/claude-code/overview">Claude Code overview - Anthropic</a></li>

</ul>
</details>

**Discussion**: Some commenters praised the speed of LLM-assisted translation, while others expressed skepticism about the quality of AI-generated code and the wisdom of rewriting a critical tool. A user also pointed to a competing fork called 'buz' that modernized the original Zig codebase, claiming it achieved sub-second build times without rewriting in Rust.

**Tags**: `#bun`, `#rust`, `#javascript`, `#rewrite`, `#llm`

---

<a id="item-5"></a>
## [Investigation Exposes Chinese LLM Token Relay Market Using Open Source Proxies](https://simonwillison.net/2026/Jul/26/relay-market/#atom-everything) ⭐️ 8.0/10

An investigation by Matt Lenhard reveals a thriving Chinese market where LLM token resellers sell discounted access by pooling API keys obtained through free trial abuse, stolen credentials, and chargeback attacks, using open source proxy tools like one-api and new-api. This market poses significant security and financial risks for AI companies and developers, as it incentivizes exploitation of unprotected endpoints and undermines official pricing models, highlighting the urgent need for better API key management and spending caps. Resellers offer discounted LLM tokens by proxying requests through a pool of credentials from free trials, compromised support bots, or stolen credit cards, using legitimate open source proxy software originally designed for load balancing and key management.

rss · Simon Willison · Jul 26, 19:30

**Background**: LLM API providers like OpenAI and Anthropic charge per-token fees for access to their models. Third-party proxy tools such as one-api and new-api allow users to aggregate multiple API keys and route requests across them for load balancing or redundancy. However, these tools can be misused to pool keys obtained through fraudulent means, enabling reselling of cheap tokens. Buyers may seek cheaper access, circumvent geo-restrictions, or collect data for model distillation.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/Mirrowel/LLM-API-Key-Proxy">GitHub - Mirrowel/LLM-API-Key-Proxy: Universal LLM Gateway: One API, every LLM. OpenAI/Anthropic-compatible endpoints with multi-provider translation and intelligent load-balancing. · GitHub</a></li>
<li><a href="https://docs.litellm.ai/docs/simple_proxy">LiteLLM AI Gateway (LLM Proxy) | liteLLM</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#API security`, `#fraud`, `#token reselling`, `#AI infrastructure`

---

<a id="item-6"></a>
## [Ruff v0.16.0 expands default rules from 59 to 413](https://simonwillison.net/2026/Jul/25/ruff/#atom-everything) ⭐️ 8.0/10

Ruff v0.16.0, released on July 23, 2026, increases the default set of enabled lint rules from 59 to 413, adding many checks that catch syntax errors and runtime bugs. This change causes CI failures for projects that use unpinned 'ruff' dev dependencies, as seen in Simon Willison's projects. This expansion significantly raises the baseline code quality checks for all Python projects using Ruff with default settings, catching issues that previously required explicit configuration. It will force many development teams to either pin their Ruff version or update their code to comply with the new rules, impacting most Python CI pipelines. Ruff now has 968 total rules, up from 708 since v0.1.0, and enables 413 by default. A single command with 'uvx ruff@latest check . --fix --unsafe-fixes' can auto-fix many issues, as demonstrated by fixing 1538 out of 1618 errors in the sqlite-utils project.

rss · Simon Willison · Jul 25, 22:44

**Background**: Ruff is an extremely fast Python linter and code formatter written in Rust, designed as a drop-in replacement for tools like Flake8, isort, and Black. An unpinned dependency means the project does not specify an exact version of 'ruff', so a newer version with breaking changes can be installed automatically, causing CI failures. The new rules include checks for naive datetime usage (DTZ005), catching blind exceptions (BLE001), and useless attribute access (B018).

<details><summary>References</summary>
<ul>
<li><a href="https://docs.astral.sh/ruff/linter/">The Ruff Linter | Ruff - Astral</a></li>
<li><a href="https://github.com/astral-sh/ruff">GitHub - astral-sh/ruff: An extremely fast Python linter and ... ruff · PyPI Ruff - Astral Ruff: Complete Guide to Python's Fastest Linter | pydevtools GitHub - sartcod/ruff: An extremely fast Python linter and ... Ruff: A Modern Python Linter for Error-Free and Maintainable ...</a></li>
<li><a href="https://pypi.org/project/ruff/">ruff · PyPI</a></li>

</ul>
</details>

**Tags**: `#Python`, `#linting`, `#Ruff`, `#development tools`, `#code quality`

---

<a id="item-7"></a>
## [Proposal: Formal Pre-Training Gate for Training Data Auditing](https://www.reddit.com/r/MachineLearning/comments/1v8a3nu/training_data_needs_a_real_gonogo_gate_before/) ⭐️ 8.0/10

A Reddit user proposed a formal pre-training gate that audits training artifacts and issues reproducible PASS, WARNING, FAIL, or FAIL_SECURITY verdicts based on explicit evidence metrics such as data leakage, contradictions, redundancy, coverage, and provenance, without relying on an LLM for judgment. If adopted, this approach could close a critical gap in ML training pipelines by replacing subjective, notebook-based checkpoints with transparent, reproducible gates, thereby improving training reliability and security across teams and organizations. The proposed system would produce a repair plan, apply only approved changes to a derived copy while preserving the original, and run a second audit afterward, with everything tied to manifests and checksums to ensure reproducibility.

reddit · r/MachineLearning · /u/jesusmjk · Jul 27, 19:13

**Background**: Data leakage occurs when information from outside the training set influences model building, leading to overly optimistic performance estimates. Data contradictions refer to inconsistent labelings that degrade model robustness. Provenance tracking records the origin and transformations of data, which is crucial for auditing. These are common issues that current training pipelines often detect only after training or through subjective human review.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Leakage_(machine_learning)">Leakage ( machine learning ) - Wikipedia</a></li>
<li><a href="https://arxiv.org/html/2504.00180v1">Contradiction Detection in RAG Systems: Evaluating LLMs as ...</a></li>
<li><a href="https://ckaestne.medium.com/versioning-provenance-and-reproducibility-in-production-machine-learning-355c48665005">Versioning, Provenance, and Reproducibility in Production Machine Learning | by Christian Kästner | Medium</a></li>

</ul>
</details>

**Tags**: `#machine learning`, `#data quality`, `#training pipeline`, `#MLOps`, `#data validation`

---

<a id="item-8"></a>
## [ARM64 Assembly YOLO26n Inference from Scratch](https://www.reddit.com/r/MachineLearning/comments/1v6w394/i_implemented_the_yolo26n_model_inference_from/) ⭐️ 8.0/10

A developer implemented YOLO26n model inference entirely from scratch using ARM64 Assembly language and C, without relying on any existing deep learning frameworks, and deployed it on a Raspberry Pi 4. This project demonstrates a deep understanding of low-level systems and neural network inference optimization, showcasing techniques like NEON SIMD, Winograd convolution, and operator fusion that are crucial for efficient edge AI deployment on resource-constrained devices. The implementation includes custom ARM64 micro-kernels, cache-aware tiling, and a custom binary format for model parameters, and correctly produces object detection results, though the performance improvement was lower than expected.

reddit · r/MachineLearning · /u/Forward_Confusion902 · Jul 26, 06:43

**Background**: YOLO (You Only Look Once) is a popular real-time object detection model family. This project uses YOLO26n, a variant of YOLOv6 tailored for edge devices. ARM64 Assembly is the low-level instruction set for ARM processors like the Raspberry Pi 4's CPU. NEON SIMD (Single Instruction, Multiple Data) enables parallel processing of multiple data points, and Winograd convolution is an algorithm that reduces the number of multiplications in convolutional layers. Operator fusion combines multiple neural network operations into a single kernel to reduce memory traffic and overhead.

<details><summary>References</summary>
<ul>
<li><a href="https://www.emergentmind.com/topics/winograd-convolution">Winograd Convolution in CNNs</a></li>
<li><a href="http://www.aussieai.com/research/kernel-fusion">Kernel Operator Fusion</a></li>

</ul>
</details>

**Tags**: `#YOLO`, `#ARM64`, `#Assembly`, `#Edge AI`, `#Inference Optimization`

---

<a id="item-9"></a>
## [4B Open-Weight Models Match o3 on Swedish Medical QA](https://www.reddit.com/r/MachineLearning/comments/1v71wds/openweight_4b_models_approach_o3level_medical/) ⭐️ 8.0/10

A 4B-parameter open-weight model, Qwen3.5-4B, achieved 87% accuracy on the MedQA-SWE Swedish medical exam dataset using reasoning with an early exit intervention from the S-GRPO paper, approaching OpenAI's o3 model at 88% and surpassing GPT-4 at 84%. This demonstrates that small open-weight models can rival proprietary frontier models on specialized domain tasks in low-resource languages, significantly lowering the barrier for deploying capable medical AI in non-English settings. Qwen3.5-4B required no post-training to reach 77% accuracy, and with reasoning enabled, it reached 87%, with early exit intervention preventing infinite reasoning loops. The model performed all reasoning in English despite the Swedish prompt, confirming that language is not a barrier.

reddit · r/MachineLearning · /u/AccomplishedCat4770 · Jul 26, 11:58

**Background**: Open-weight models are AI systems whose learned parameters (weights) are publicly available, allowing for transparency, fine-tuning, and reproducibility. The MedQA-SWE dataset comprises 3,180 multiple-choice clinical questions in Swedish, derived from exams for foreign doctors seeking a Swedish medical license. S-GRPO is a reinforcement learning method that trains models to exit reasoning early when sufficient thought has been performed, reducing length while maintaining accuracy.

<details><summary>References</summary>
<ul>
<li><a href="https://aclanthology.org/2024.lrec-main.975/">MedQA-SWE - a Clinical Question & Answer Dataset for Swedish</a></li>
<li><a href="https://arxiv.org/abs/2505.07686">S - GRPO : Early Exit via Reinforcement Learning in Reasoning Models</a></li>
<li><a href="https://medium.com/@kimanited73/open-weight-models-f504be677b1c">Open Weight Models . What are they, and why should you... | Medium</a></li>

</ul>
</details>

**Tags**: `#LLMs`, `#Medical AI`, `#Swedish NLP`, `#Open-weight models`, `#Reasoning`

---

<a id="item-10"></a>
## [Claude shared links indexed by search engines, exposing user data](https://search.brave.com/search?q=site%3Aclaude.ai%2Fshare&amp;source=android) ⭐️ 8.0/10

Brave and Bing search engines have indexed publicly shared Claude conversation links because Anthropic failed to add noindex tags, exposing sensitive user data such as API keys and personal information. This security vulnerability puts countless users at risk of data exposure and identity theft, and it mirrors a similar issue that ChatGPT fixed a year ago, highlighting a recurring neglect of basic privacy safeguards in AI chat products. Google has blocked indexing of these links, but Brave and Bing continue to index them; the leaked information includes API keys, cryptocurrency wallet details, résumés, legal consultation records, and Social Security numbers.

telegram · zaihuapd · Jul 26, 11:16

**Background**: The noindex meta tag tells search engine crawlers not to index a page, and adding it to web pages is a standard privacy practice for sensitive content. Claude's share feature creates a public snapshot of a conversation that is intended to be shared only via a direct link, but without noindex tags, those pages become discoverable through search engines. This oversight is similar to a past vulnerability in ChatGPT, which was fixed by adding noindex tags to shared links.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Noindex">noindex - Wikipedia</a></li>
<li><a href="https://developers.google.com/search/docs/crawling-indexing/block-indexing">Block Search Indexing with noindex | Google Search Central | Documentation | Google for Developers</a></li>
<li><a href="https://thecybersecguru.com/news/claude-shared-chats-google-search-privacy/">Claude Share Links Became Searchable on... | The CyberSec Guru</a></li>

</ul>
</details>

**Tags**: `#privacy`, `#security`, `#Claude`, `#data leak`, `#AI chat`

---

<a id="item-11"></a>
## [SpaceX Stops Falcon 9 Orders Beyond 2028, Bets on Starship](https://www.bloomberg.com/news/articles/2026-07-23/spacex-is-turning-away-falcon-customers-in-major-bet-on-starship) ⭐️ 8.0/10

SpaceX has stopped accepting new Falcon 9 launch contracts for missions after 2028 and has scaled back production of some Falcon components to accelerate the transition to its Starship rocket. This strategic shift could reshape the global launch market, as Starship's success is critical for SpaceX's future in satellite internet and deep space missions, but any delays could leave a gap in commercial launch capacity. The company still plans to support Falcon 9 missions for the U.S. Department of Defense and NASA, but it will no longer accept commercial rideshare bookings. SpaceX's stock has fallen about 25% since its IPO in June 2026 due to Starship delays.

telegram · zaihuapd · Jul 26, 12:42

**Background**: Falcon 9 is SpaceX's workhorse rocket that has dominated the commercial launch market for years with reusable first stages. Starship is a next-generation fully reusable super-heavy launch vehicle intended to carry large payloads to orbit, the Moon, and Mars. By pivoting exclusively to Starship, SpaceX is taking a major business risk, betting that the new rocket will enter commercial service by late 2028.

**Tags**: `#SpaceX`, `#Starship`, `#Falcon 9`, `#商业航天`, `#发射市场`

---

<a id="item-12"></a>
## [Google's Gemini 4: Most Ambitious Pretraining Yet, Late 2026](https://9to5google.com/2026/07/26/google-gemini-4-teases/) ⭐️ 8.0/10

Google CEO Sundar Pichai announced during Alphabet's Q2 2026 earnings call that Gemini 4 is currently in training and is the company's most ambitious pretraining project, expected to launch by the end of 2026. This signals Google's commitment to frontier AI development and large-scale pretraining, potentially setting new benchmarks in the AI industry and impacting competitors and developers who rely on Google's models. Gemini 4 is currently in training, and Pichai expressed excitement about internal progress. Additionally, the Gemini 3.x Flash series will continue with near-monthly updates focusing on capabilities like intelligent coding.

telegram · zaihuapd · Jul 27, 04:06

**Background**: Pretraining is the initial phase where a large language model is trained on a massive corpus of text to learn language patterns, serving as the foundation for further fine-tuning. Gemini is Google's family of multimodal AI models, with earlier versions like Gemini 1.0, 1.5, 2.0, and the 3.x Flash series. Frontier models like GPT-3 were trained on hundreds of billions of tokens, but modern models now use tens of trillions of tokens with multimodal capabilities.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Gemini_(language_model)">Gemini (language model ) - Wikipedia</a></li>
<li><a href="https://medium.com/@nursena_kok/pre-training-phase-of-large-language-models-the-foundation-of-modern-ai-111b377f0a33">Pre-training Phase of Large Language Models: The Foundation of Modern AI | by Nursena Kok | Medium</a></li>

</ul>
</details>

**Tags**: `#Google`, `#Gemini`, `#AI`, `#Large Language Model`, `#AGI`

---

<a id="item-13"></a>
## [Critical RCE vulnerability in Fastjson 1.x without gadget](https://t.me/zaihuapd/42797) ⭐️ 8.0/10

Security researcher Kirill Firsov disclosed a critical remote code execution vulnerability in Fastjson versions 1.2.68 through 1.2.83. The vulnerability does not require enabling autoTypeSupport or any gadget chain, and can be exploited on JDK 8, 17, and 21. This is significant because Fastjson 1.x is widely used in Java applications, and the vulnerability allows remote code execution with minimal prerequisites. Since Fastjson 1.x reached end-of-life in October 2024, no official patch will be issued, leaving affected systems at risk unless they upgrade to Fastjson2. The vulnerability affects versions 1.2.68 to 1.2.83 inclusive, and does not require the autoType feature or any specific classpath gadgets. A workaround is to enable SafeMode (e.g., -Dfastjson.parser.safeMode=true), but the only complete fix is upgrading to Fastjson2.

telegram · zaihuapd · Jul 27, 10:31

**Background**: Fastjson is a popular JSON serialization/deserialization library for Java. Its autoType feature allows the JSON input to specify the class type to be deserialized using the @type field, which has historically led to deserialization vulnerabilities. Gadget chains are sequences of classes that, when deserialized, can be exploited to execute arbitrary code. The disclosed vulnerability bypasses typical protections by not requiring autoType or any known gadget chain, making it especially dangerous.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/alibaba/fastjson/wiki/fastjson_safemode_en">fastjson_safemode_en · alibaba/fastjson Wiki</a></li>
<li><a href="https://www.alphabot.com/security/blog/2020/java/Fastjson-exceptional-deserialization-vulnerabilities.html">Fastjson: exceptional deserialization vulnerabilities - Alphabot Security</a></li>
<li><a href="https://medium.com/@dub-flow/deserialization-what-the-heck-actually-is-a-gadget-chain-1ea35e32df69">Deserialization: What the Heck *Actually* Is a Gadget Chain? | by Florian Walter | Medium</a></li>

</ul>
</details>

**Tags**: `#安全漏洞`, `#Java`, `#Fastjson`, `#RCE`, `#远程代码执行`

---

<a id="item-14"></a>
## [SMIC Tests China's First Domestic DUV Lithography Machine](https://t.me/zaihuapd/42800) ⭐️ 8.0/10

SMIC is piloting China's first domestically developed deep ultraviolet (DUV) lithography machine, created by Shanghai startup Yusheng, to produce 28nm chips and explore 7nm and even 5nm nodes via multi-patterning. This marks a significant step toward China's semiconductor self-sufficiency, reducing dependence on ASML equipment restricted by U.S. export controls, though the machine remains years behind ASML in performance and yield. Most components of the machine are domestically sourced, but some still rely on imports. Industry experts estimate it will take 1-2 years to achieve stable mass production and competitive yields, with potential volume manufacturing by 2027.

telegram · zaihuapd · Jul 27, 14:10

**Background**: Deep ultraviolet (DUV) lithography uses 193nm wavelength light to project circuit patterns onto silicon wafers, essential for manufacturing advanced chips. Multi-patterning techniques allow DUV systems to create features smaller than their single-exposure resolution limit, enabling nodes like 7nm. Currently, China's most advanced chips rely on imported ASML DUV machines, while EUV systems are banned for sale to China due to U.S. export controls.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DUV_lithography">DUV lithography</a></li>
<li><a href="https://en.wikipedia.org/wiki/Multiple_patterning">Multiple patterning - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#semiconductors`, `#lithography`, `#SMIC`, `#China`, `#DUV`

---

<a id="item-15"></a>
## [Microsoft Unveils MAI-Cyber 1, a Specialized Cybersecurity AI Model](https://microsoft.ai/news/introducing-mai-cyber-1-flash-inside-mdash/) ⭐️ 7.0/10

Microsoft has announced MAI-Cyber 1 Flash, a new cybersecurity AI model built on trillions of daily signals from its security systems, and it achieves a 96% CyberGym score while operating at half the cost of alternative models. This release marks a significant step in applying specialized AI to cybersecurity, leveraging Microsoft's unique access to massive, real-world security data that competitors cannot replicate, and it promises to make vulnerability detection more efficient and cost-effective. The model is designed to find challenging vulnerabilities in complex codebases and powers MDASH, Microsoft's harness for software vulnerability identification and remediation; it also debuts alongside Project Perception, an agentic security system that orchestrates AI models into teams of autonomous agents.

hackernews · migmartri · Jul 27, 16:52 · [Discussion](https://news.ycombinator.com/item?id=49072361)

**Background**: Microsoft has decades of experience building security products (e.g., Defender, Azure Sentinel) and collects trillions of security signals daily across identity, endpoint, cloud, and network. MAI-Cyber 1 is a large language model fine-tuned specifically for cybersecurity tasks, and it competes in a growing market where tech companies are developing specialized AI models for domains like code generation and threat analysis.

<details><summary>References</summary>
<ul>
<li><a href="https://runtimewire.com/article/microsoft-mai-cyber-1-flash-mdash-launch">Microsoft launches MAI - Cyber - 1 -Flash, a cost‑efficient... - RuntimeWire</a></li>
<li><a href="https://techcrunch.com/2026/07/27/microsoft-launches-its-first-cyber-model-and-a-new-agentic-cybersecurity-system/">Microsoft launches its first cybersecurity model, plus... | TechCrunch</a></li>
<li><a href="https://www.nytimes.com/2026/07/27/technology/microsoft-unveils-ai-cybersecurity-tools.html">Microsoft Unveils A. I . Cybersecurity Tools - The New York Times</a></li>

</ul>
</details>

**Discussion**: Community comments show a mix of interest and skepticism: some question whether Microsoft's data advantage simply means the model is best at fixing Microsoft products, others note the ironic 'live reinforcement learning loop' of cybersecurity, and a few criticize the naming convention and express frustration over how to access the model.

**Tags**: `#AI`, `#Cybersecurity`, `#Microsoft`, `#Machine Learning`, `#LLM`

---

<a id="item-16"></a>
## [Libsm64: Super Mario 64 repackaged as a reusable library](https://github.com/libsm64/libsm64) ⭐️ 7.0/10

Libsm64 extracts the movement and rendering code from the Super Mario 64 decompilation project and exposes it as a shared C library, allowing developers to embed Mario into any external game engine. This project demonstrates a novel approach to game preservation and modding by turning a classic game character into a portable asset, enabling creative cross-game integrations like Mario in Half-Life 2 without proprietary crypto or metaverse hype. The library's entire external API is defined in a single header file (libsm64.h), and a minimal example is provided under the test directory. It builds upon the full decompilation of Super Mario 64 (Japan, USA, Europe, Shindou, iQue versions) by the n64decomp team.

hackernews · klaussilveira · Jul 27, 10:04 · [Discussion](https://news.ycombinator.com/item?id=49067352)

**Background**: Libsm64 is built on the Super Mario 64 decompilation project, which reversed-engineered the original N64 game from binary machine code back to human-readable C source code. That decompiled code can recompile into a ROM identical to the original. Libsm64 takes that open-source code and wraps the character's movement and rendering logic into a library, decoupling Mario from his native game engine.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/libsm64/libsm64">GitHub - libsm64/libsm64: Mario 64 as a library for use in ...</a></li>
<li><a href="https://daily.dev/posts/libsm64-mario-64-as-a-library-for-use-in-external-game-engines-igf1gqkp4">Libsm64: Mario 64 as a library for use in external game...</a></li>

</ul>
</details>

**Discussion**: The community comments are overwhelmingly positive, praising the project's novelty and the creative potential it unlocks, as seen in the Mario-in-Half-Life-2 example. Some users express curiosity about ease of use for non-engineers, while others jokingly suggest selling 'Mario 64 as a service' but quickly clarify it's a jest aimed at Nintendo.

**Tags**: `#reverse engineering`, `#game development`, `#C/C++`, `#open source`, `#Nintendo`

---

<a id="item-17"></a>
## [3DGS Memory Optimization: Survey Identifies Five Key Directions](https://mp.weixin.qq.com/s?__biz=MzIzNjc1NzUzMw==&mid=2247907517&idx=3&sn=47197285f42f0199832d9f5b6612b961) ⭐️ 7.0/10

A survey article systematically reviews five research directions for reducing the memory footprint of 3D Gaussian Splatting (3DGS), aiming to address the problem of high VRAM consumption that can exceed 700MB per scene. 3DGS is widely used for real-time photorealistic novel-view synthesis, but its excessive memory usage limits deployment on consumer-grade hardware and mobile devices. This survey provides a structured roadmap for optimizing storage, which is critical for making 3DGS practical in graphics, VR/AR, and robotics applications. The survey identifies five optimization directions, covering improvements in algorithm design, memory management, and hardware–software co-evolution, particularly the synergy between the rasterizer and other components. A typical 3D scene rendered with 3DGS can demand more than 700 MB of VRAM.

rss · 量子位 · Jul 27, 03:31

**Background**: 3D Gaussian Splatting (3DGS) is a volumetric rendering technique that represents scenes as a collection of anisotropic 3D Gaussians, enabling real-time radiance field rendering from sparse images. Originally introduced by Kerbl et al. in 2023, 3DGS has become popular for its high-quality novel-view synthesis but suffers from high memory consumption because each Gaussian stores parameters like position, covariance, color, and opacity. Optimizing storage while maintaining quality is an active research area.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/3D_Gaussian_splatting">3D Gaussian splatting</a></li>
<li><a href="https://en.wikipedia.org/wiki/Gaussian_splatting">Gaussian splatting - Wikipedia</a></li>
<li><a href="https://github.com/graphdeco-inria/gaussian-splatting">GitHub - graphdeco-inria/gaussian-splatting: Original ...</a></li>

</ul>
</details>

**Tags**: `#3D Gaussian Splatting`, `#存储优化`, `#计算机图形学`, `#综述`, `#内存管理`

---

<a id="item-18"></a>
## [LLMs on IMO 2026: Frontier models perfect, harness helps others](https://www.reddit.com/r/MachineLearning/comments/1v6wskz/we_compared_different_llms_on_imo_2026_r/) ⭐️ 7.0/10

A study evaluated several LLMs on the newly released IMO 2026 problems, finding that frontier models (e.g., Sol and Fable) achieved perfect scores regardless of harness, while other models like Sonnet and Opus improved significantly with harness engineering, especially using the custom multi-agent harness AutoFyn. This benchmark demonstrates that frontier models have reached near-perfect mathematical reasoning on novel competition problems, while also highlighting that harness engineering—orchestration, retrieval, and multi-agent coordination—can substantially lift the performance of weaker models, making it a crucial area for building reliable LLM applications. The study used manual grading by former IMO medalists to verify results, and noted that hallucination persists even in verifiable math domains—e.g., Sonnet falsely claimed a solution on problem P3. The hardest problem, P3, required a key reduction that no sub-frontier model could discover, even after a 20-hour run with harness support for retrieval and verification.

reddit · r/MachineLearning · /u/pequalnp92 · Jul 26, 07:21

**Background**: The International Mathematical Olympiad (IMO) is an annual competition featuring novel, challenging math problems that test advanced reasoning. LLM harness engineering refers to building systems around LLMs that add memory, orchestration, multi-agent coordination, and evaluation layers to improve performance on complex tasks. The custom harness AutoFyn was developed by the authors to study how such engineering can bridge the gap between frontier and non-frontier models.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2603.03329">[2603.03329] AutoHarness: improving LLM agents by automatically synthesizing a code harness</a></li>
<li><a href="https://www.decodingai.com/p/agentic-harness-engineering">Agentic Harness Engineering: LLMs as the New OS</a></li>
<li><a href="https://github.com/walkinglabs/awesome-harness-engineering">walkinglabs/awesome-harness-engineering - GitHub</a></li>

</ul>
</details>

**Tags**: `#LLM evaluation`, `#mathematical reasoning`, `#benchmark`, `#IMO`, `#harness engineering`

---

<a id="item-19"></a>
## [Qualcomm Announces Across-the-Board Price Hike from September 1](https://t.me/zaihuapd/42782) ⭐️ 7.0/10

On July 24, 2026, Qualcomm notified customers that all products shipped from September 1, 2026 will see price increases, citing rising manufacturing costs and AI-driven supply constraints. This price increase affects the entire mobile and IoT chip ecosystem, potentially raising costs for smartphones, laptops, and automotive electronics, and reflects structural shifts in semiconductor manufacturing due to AI demand. The company did not disclose a uniform percentage increase or specific product models; instead, it said account managers will contact customers individually with new pricing, and some existing orders scheduled for shipment after September may also be re-quoted.

telegram · zaihuapd · Jul 26, 10:20

**Background**: Semiconductor manufacturing involves multiple stages: wafer fabrication, packaging, and testing, with substrate materials like silicon wafers forming the base. Advanced packaging (e.g., for AI chips) requires costly materials like glass substrates and high-density interconnects. The surge in AI and data center demand has strained supply chains, driving up costs across the industry.

<details><summary>References</summary>
<ul>
<li><a href="https://pcbmake.com/substrate-material-for-semiconductors/">Choosing the Right Substrate Material for Semiconductors</a></li>
<li><a href="https://www.nextmsc.com/report/semiconductor-packing-market">Semiconductor Packing Market: 64.22 billion USD 2030 Goal</a></li>

</ul>
</details>

**Tags**: `#Qualcomm`, `#semiconductor`, `#price increase`, `#supply chain`, `#AI demand`

---

<a id="item-20"></a>
## [Huawei-CXMT tensions rise as AI data centers drive memory price hikes](https://t.me/zaihuapd/42788) ⭐️ 7.0/10

ChangXin Memory Technologies (CXMT), China's top DRAM maker, has been raising memory chip prices even for major customer Huawei, and in June 2025 asked engineers from Huawei-affiliated equipment supplier Xinkailai to leave its core R&D area, with no return permission granted since. This episode reveals growing supply chain friction inside China's semiconductor ecosystem as AI data center demand intensifies competition for limited memory chips, potentially affecting Huawei's product costs and strategic autonomy. CXMT has become the world's fourth-largest DRAM manufacturer, and its product supply is tightening due to AI data center construction. Xinkailai (SiCarrier) is a Shenzhen-based semiconductor equipment company backed by the Shenzhen government and works extensively with Huawei.

telegram · zaihuapd · Jul 27, 03:17

**Background**: DRAM (dynamic random-access memory) is a critical component in servers, mobile phones, and PCs, and demand has surged with AI data center buildouts. CXMT is China's only large-scale producer of modern DDR5 and LPDDR5 memory, giving it significant pricing leverage. Huawei, heavily reliant on domestic memory chips amid US export restrictions, faces increased costs as CXMT prioritizes higher-margin AI customers.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cxmt.com/en/">About cxmt - cxmt</a></li>
<li><a href="https://www.scmp.com/tech/big-tech/article/3361926/chinas-cxmt-shares-rise-472-star-market-debut-valuing-dram-maker-us489-billion">China’s CXMT soars 466% on debut as DRAM maker becomes most...</a></li>
<li><a href="https://en.wikipedia.org/wiki/SiCarrier">SiCarrier - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#memory chips`, `#Huawei`, `#ChangXin`, `#semiconductor supply chain`, `#AI data centers`

---

<a id="item-21"></a>
## [China Rejects US Sanctions Over AI Model Distillation](https://www.mofcom.gov.cn/syxwfb/art/2026/art_7f1622463a7c48ef9fad600ce0ef702f.html) ⭐️ 7.0/10

On July 27, China's Ministry of Commerce rejected US plans to investigate and sanction Chinese AI companies for allegedly distilling US frontier models, stating that model distillation is a widely used industry technique and that US companies also distill Chinese models. This dispute highlights escalating US-China tensions over AI intellectual property and could shape future regulations on model distillation. It also underscores the interconnected nature of AI development, where open-source models are used globally. The Commerce Ministry noted that nearly 200 US startups have called on their government not to restrict access to Chinese open-source models. China warned it would take necessary measures to protect its companies' legitimate interests if its interests are substantially harmed.

telegram · zaihuapd · Jul 27, 11:01

**Background**: Model distillation (or knowledge distillation) is a machine learning technique where a smaller "student" model learns from a larger "teacher" model to become more efficient while retaining performance. It is commonly used to deploy AI on less powerful hardware, but has become controversial in the US-China AI rivalry when used across national boundaries.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Model_distillation">Model distillation</a></li>
<li><a href="https://www.tmtpost.com/7892989.html">Anthropic装糊涂，全球AI圈看笑了-钛媒体官方网站</a></li>
<li><a href="https://www.woshipm.com/ai/6327416.html">AGI bar火爆背后： 模 型 蒸 馏 技术如何重塑未来？ | 人人都 是 产品经理</a></li>

</ul>
</details>

**Tags**: `#AI policy`, `#model distillation`, `#US-China trade`, `#AI regulation`, `#intellectual property`

---

<a id="item-22"></a>
## [Moonshot AI to Open-Source Kimi-K3, a 3T-Parameter Model](https://t.me/zaihuapd/42802) ⭐️ 7.0/10

Moonshot AI announced plans to open-source Kimi-K3, a 3 trillion parameter model, on Hugging Face in July 2026, featuring the novel Kimi Delta Attention and Attention Residuals architecture. Open-sourcing a 3T-parameter model with innovative architecture could democratize access to frontier AI capabilities, especially for long-context programming and complex reasoning tasks. It sets a new benchmark for open-weight models and challenges the current closed-source paradigm. The release is scheduled for July 27, 2026, and the model will be hosted on Hugging Face. It combines Kimi Delta Attention (a delta-rule-based linear attention mechanism) with Attention Residuals (a learned selective aggregation over layer depth), enabling fine-grained memory updates and repository-level code understanding.

telegram · zaihuapd · Jul 27, 15:15

**Background**: Standard Transformer models use residual connections that add each layer's output with equal weight, leading to hidden-state growth and signal dilution. Attention Residuals replace this with learned softmax attention over previous layers, allowing each layer to selectively aggregate earlier representations. Kimi Delta Attention is a linear attention mechanism that uses a finer-grained gating (channel-wise forgetting) for efficient memory updates, extending ideas from Gated DeltaNet and Mamba architectures.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2603.15031">[2603.15031] Attention Residuals - arXiv.org GitHub - MoonshotAI/Attention-Residuals Attention Residuals - arXiv.org Attention Residuals wdlctc/open-attention-residuals - GitHub Attention Residuals - openlm.ai Attention Residuals Explained: Rethinking Transformer Depth</a></li>
<li><a href="https://www.emergentmind.com/topics/kimi-delta-attention">Kimi Delta Attention : Delta ‐Rule Linear Mechanism</a></li>
<li><a href="https://github.com/MoonshotAI/Attention-Residuals">GitHub - MoonshotAI/Attention-Residuals</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Open Source`, `#Large Language Models`, `#Moonshot AI`, `#Kimi-K3`

---

<a id="item-23"></a>
## [Data-Driven Investigation: Washing Solar Panels Often Unnecessary](https://incoherency.co.uk/blog/stories/should-you-wash-your-solar-panels.html) ⭐️ 6.0/10

A data-driven investigation found that cleaning solar panels yields negligible performance gains in most cases, with benefits depending heavily on local conditions such as dust, bird droppings, and panel orientation. For solar panel owners and renewable energy enthusiasts, this challenges common maintenance advice and suggests that time and money spent on cleaning may often be wasted, except in specific circumstances like coastal salt spray or heavy pollution. The author's experiment showed a cubic spline fit with a slight downward trend after cleaning, possibly due to panel mismatch or cooling effects from water. One commenter with a 19-year-old system reported no performance degradation despite never washing.

hackernews · surprisetalk · Jul 27, 13:04 · [Discussion](https://news.ycombinator.com/item?id=49069132)

**Background**: Solar panels convert sunlight to electricity, and their efficiency can be reduced by dirt, dust, or bird droppings blocking light. Many homeowners assume regular cleaning is necessary to maintain output. However, natural rainfall often provides sufficient cleaning in many climates, and the effort of manual washing may not be justified by the small energy gain.

**Discussion**: The community offered diverse perspectives: one user noted that cleaning before selling a house improves appearance rather than performance; another shared 19 years of data showing no degradation without washing; a third pointed out that water cooling can temporarily boost output, skewing results; and a fourth reported a 10% improvement after cleaning panels on a boat in salty conditions. There was also a safety concern about inadequate grounding of the experimental setup.

**Tags**: `#solar energy`, `#renewable energy`, `#maintenance`, `#data analysis`, `#practical engineering`

---

<a id="item-24"></a>
## [Transformer from Scratch in PyTorch for English-Tamil Translation](https://www.reddit.com/r/MachineLearning/comments/1v86qo9/built_trained_a_transformer_from_scratch_in_pure/) ⭐️ 6.0/10

A developer published a detailed blog post and GitHub repository showing how to implement and train the Transformer architecture from scratch using pure PyTorch, trained on an English-to-Tamil parallel dataset using dual NVIDIA T4 GPUs on Kaggle. This tutorial provides a thorough educational resource for understanding the Transformer's inner workings, including mathematical breakdowns and tensor shape transformations, which is valuable for students and practitioners learning NLP and deep learning. The implementation follows the original 'Attention Is All You Need' paper, uses the Hugging Face dataset 'gopi30/english-tamil', and includes step-by-step code and math explanations. Both the blog post and GitHub repository are freely available.

reddit · r/MachineLearning · /u/imrancoder · Jul 27, 17:17

**Background**: The Transformer is a deep learning architecture introduced in 2017 that relies on self-attention mechanisms, revolutionizing natural language processing tasks like machine translation. Building one from scratch helps learners understand the mathematical foundations, such as multi-head attention, positional encoding, and feed-forward networks, which are often abstracted away in high-level libraries.

**Tags**: `#transformer`, `#pytorch`, `#machine translation`, `#nlp`, `#tutorial`

---

<a id="item-25"></a>
## [Open-source end-to-end edge ML platform with auto-labeling](https://www.reddit.com/r/MachineLearning/comments/1v7nudc/recent_project_i_worked_on_end_to_end_edge_ml/) ⭐️ 6.0/10

A Reddit user shared SensorForge, an open-source end-to-end edge ML platform that includes an auto-labeling tool for time-series sensor data and a chatbot for signal analysis, enabling deployment on microcontrollers (MCUs). This platform directly addresses two major pain points in edge ML: the difficulty of manually labeling time-series sensor data and the complexity of deploying models on resource-constrained MCUs. By offering free, open-source tools with auto-labeling, it lowers the barrier for developers and researchers working on tinyML applications. The platform is hosted at sensorforge.dev and features a built-in auto-labeler that aims to streamline the labeling process for time-series data, along with a chatbot that can analyze signal data directly. The project is intended to remain free and open-source for community contributions, though the creator acknowledges room for improvements.

reddit · r/MachineLearning · /u/No-Bug-4879 · Jul 27, 02:38

**Background**: TinyML (Tiny Machine Learning) is a subfield of machine learning focused on running models on ultra-low-power, resource-constrained devices like microcontrollers and IoT sensors. One of the key challenges in applying supervised learning to sensor data is the need for large amounts of accurately labeled time-series data, which is tedious and time-consuming to create manually. Auto-labeling tools and end-to-end platforms aim to automate or simplify this process, making tinyML more accessible.

<details><summary>References</summary>
<ul>
<li><a href="https://www.datacamp.com/blog/what-is-tinyml-tiny-machine-learning">What is TinyML ? An Introduction to Tiny Machine Learning | DataCamp</a></li>
<li><a href="https://csv.ninja/">Timeseries labeling /annotation tool for sensor and device data</a></li>

</ul>
</details>

**Tags**: `#edge ML`, `#tinyML`, `#auto-labeling`, `#sensor data`

---

<a id="item-26"></a>
## [US Schools Reducing Chromebook Use, Returning to Pen and Paper](https://fortune.com/article/schools-abandoning-chromebooks-laptop-programs-as-screen-time-hurts-learning-test-scores-north-carolina-michigan-kansas-tech-education/) ⭐️ 6.0/10

Schools in multiple US states, including Kansas, North Carolina, and Michigan, are reducing student use of Chromebooks and returning to paper-and-pencil teaching methods, citing concerns over screen time harming learning outcomes and high device replacement costs. This shift signals a potential reversal of the long-standing 'one-to-one' device programs in education, which could reshape educational technology policies and screen time guidelines for millions of students. In one Kansas middle school, after banning phones, students began using school Chromebooks to watch videos, play games, or harass classmates, prompting the school to restrict computers to teacher-designated activities only as of December.

telegram · zaihuapd · Jul 26, 11:02

**Background**: Since the pandemic, many US schools adopted 'one-to-one' programs providing each student with a device like a Chromebook for learning. However, growing evidence suggests excessive screen time may hinder reading comprehension, writing skills, and test scores, while device procurement and maintenance costs strain school budgets. For example, North Carolina schools spent $448 million in federal funds on computers and related equipment.

**Tags**: `#education`, `#technology in schools`, `#screen time`, `#Chromebook`, `#policy`

---

<a id="item-27"></a>
## [CXMT surges 471% on STAR Market debut, setting record IPO](https://www.stcn.com/article/detail/4042119.html) ⭐️ 6.0/10

Chinese memory chip maker CXMT (长鑫科技) debuted on the STAR Market on July 27, with shares opening 471.59% higher at 49.5 yuan per share, far above the issue price of 8.66 yuan. The IPO raised a record approximately 66.6 billion yuan, surpassing SMIC's 2020 record to become the largest on the STAR Market. This IPO signals strong investor confidence in China's domestic semiconductor memory industry and provides substantial capital for CXMT to scale DRAM production and compete with global leaders like Samsung and SK Hynix. The record fundraising also highlights the STAR Market's growing role in financing critical Chinese technology sectors. The company expects a net profit attributable to parent of 50-57 billion yuan for the first half of 2026, a significant turnaround from a loss in the corresponding period of the previous year. If the over-allotment option is fully exercised, total fundraising could reach approximately 66.6 billion yuan.

telegram · zaihuapd · Jul 27, 01:29

**Background**: CXMT (ChangXin Memory Technologies) is a leading Chinese DRAM manufacturer focused on memory chips for consumer and industrial applications. The STAR Market, launched in 2019, is China's Nasdaq-style board designed for high-tech and innovative companies. Prior to this IPO, Semiconductor Manufacturing International Corporation (SMIC) held the record for the largest STAR Market IPO in 2020, raising 532.3 billion yuan.

**Tags**: `#semiconductor`, `#IPO`, `#memory chip`, `#Chinese tech`, `#STAR Market`

---

<a id="item-28"></a>
## [Samsung may use Chinese DRAM to cut costs, boost China market share](https://www.asiatime.co.kr/article/20260727500259) ⭐️ 6.0/10

Samsung is reportedly considering using low-cost mobile DRAM chips from Chinese manufacturers for its mid-range Galaxy A series smartphones to reduce production costs and increase its market share in China, which currently stands at about 0.6%. This marks a potential shift in Samsung's supply chain strategy, as it may rely on Chinese memory chips amid a global 'chip inflation' driven by AI demand, affecting pricing and competition in the smartphone market. The report cites industry insiders saying Samsung aims to leverage price competitiveness while rivals like Apple, Xiaomi, OPPO, and vivo are cutting shipments by 15-20% due to component price hikes; Samsung's MX division may face a loss of up to 1 trillion won in Q2 2026.

telegram · zaihuapd · Jul 27, 14:45

**Background**: DRAM (Dynamic Random-Access Memory) is a type of memory chip used in smartphones and computers. Recently, memory chip prices have surged due to high demand from AI data centers and limited supply, a phenomenon called 'chip inflation.' Chinese DRAM manufacturers, such as CXMT (ChangXin Memory Technologies), have been growing rapidly and offering lower-cost alternatives.

<details><summary>References</summary>
<ul>
<li><a href="https://www.ersaelectronics.com/blog/memory-chip-price-increase">Memory Chip Price Increase: 2026 Market Trends, Samsung ...</a></li>
<li><a href="https://www.scmp.com/tech/big-tech/article/3361926/chinas-cxmt-shares-rise-472-star-market-debut-valuing-dram-maker-us489-billion">China ’s CXMT soars 466% on debut as DRAM maker becomes most...</a></li>

</ul>
</details>

**Tags**: `#Samsung`, `#DRAM`, `#semiconductor`, `#business strategy`, `#China`

---