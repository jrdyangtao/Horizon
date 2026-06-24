---
layout: default
title: "Horizon Summary: 2026-06-24 (EN)"
date: 2026-06-24
lang: en
---

> From 66 items, 30 important content pieces were selected

---

1. [OpenAI unveils its first custom chip, built by Broadcom](#item-1) ⭐️ 9.0/10
2. [TRM Reward Model and New Attention Mechanism Quantify LLM Reasoning (ICML 2026 Oral)](#item-2) ⭐️ 9.0/10
3. [China's LingSheng Supercomputer Reclaims TOP500 Top Spot with 2.198 ExaFLOPS](#item-3) ⭐️ 9.0/10
4. [Bunny.net Makes Bunny DNS Free for Up to 500 Domains](#item-4) ⭐️ 8.0/10
5. [Carmack Reflects on Mistakes: 'Quake Gutted id Software'](#item-5) ⭐️ 8.0/10
6. [Nub: A Bun-like All-in-one Toolkit for Node.js](#item-6) ⭐️ 8.0/10
7. [Krea Releases Krea 2: Open-Weights 12B Image Model](#item-7) ⭐️ 8.0/10
8. [Datasette 1.0a35 Adds Create and Alter Table Features](#item-8) ⭐️ 8.0/10
9. [Prompt Injection as Role Confusion: LLMs Fail to Distinguish System from User Prompts](#item-9) ⭐️ 8.0/10
10. [Porting Moebius 0.2B image inpainting model to browser with WebGPU](#item-10) ⭐️ 8.0/10
11. [DeepSWE: A contamination-free benchmark for real-world coding tasks](#item-11) ⭐️ 8.0/10
12. [Superhuman Generals.io Agent via Self-Play RL with JAX and Vision Transformer](#item-12) ⭐️ 8.0/10
13. [LLM Inference Pricing Comparison Reveals Vast Caching Cost Differences](#item-13) ⭐️ 8.0/10
14. [Critical RCE Vulnerability Found in FFmpeg's MagicYUV Decoder](#item-14) ⭐️ 8.0/10
15. [LastPass Suffers Data Breach via Klue, Exposing Customer Support Records](#item-15) ⭐️ 8.0/10
16. [Generative AI for Homework Lowers Chinese Students' Exam Scores](#item-16) ⭐️ 8.0/10
17. [RubyLLM: A Unified AI Framework for Ruby](#item-17) ⭐️ 7.0/10
18. [OPFS + Pyodide Test Harness for Browser SQLite Persistence](#item-18) ⭐️ 7.0/10
19. [MuJoFil: GPU-Native High-Fidelity Simulator for Vision RL](#item-19) ⭐️ 7.0/10
20. [Are Model Security Risks Actually Tested in Production?](#item-20) ⭐️ 7.0/10
21. [TSMC to Raise Prices on Advanced Process Nodes by 5-10%](#item-21) ⭐️ 7.0/10
22. [Stealing Is a Skill](#item-22) ⭐️ 6.0/10
23. [Tom MacWright: LLM-Generated Resumes Make Candidates Anonymous](#item-23) ⭐️ 6.0/10
24. [High-Dimensional Dynamic RoPE Converges Faster Than xPos on TinyStories](#item-24) ⭐️ 6.0/10
25. [New Proof: 14 Sloppy Riffle Shuffles Randomize a Deck](#item-25) ⭐️ 6.0/10
26. [Xiaomi's First NAS 'Xiaomi Smart Storage' Launches December with Xiaomi 17 Ultra](#item-26) ⭐️ 6.0/10
27. [Trump says Anthropic no longer a national security threat, may ease model restrictions](#item-27) ⭐️ 6.0/10
28. [Cloudflare and Browsers Propose PACT to Replace CAPTCHAs with Tokens](#item-28) ⭐️ 6.0/10
29. [ByteDance Reported Co-Developing 5nm AI Chip with Broadcom; Company Denies](#item-29) ⭐️ 6.0/10
30. [OpenAI Open-Sources planttalk: Voice Chat with Plants Using ChatGPT](#item-30) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [OpenAI unveils its first custom chip, built by Broadcom](https://techcrunch.com/2026/06/24/openai-unveils-its-first-custom-chip-built-by-broadcom/) ⭐️ 9.0/10

OpenAI, in collaboration with Broadcom, announced its first custom AI inference chip, Jalapeño, built in nine months to optimize model performance and reduce reliance on external suppliers. This move signals OpenAI's vertical integration into hardware, which could reduce dependence on NVIDIA and reshape the competitive landscape of AI chips, while enabling more efficient inference for its models. The Jalapeño chip, manufactured by TSMC, is currently in engineering samples and running models like GPT-5.3-Codex-Spark at target specs. It is optimized for inference, not training, and its nine-month development was reportedly accelerated by OpenAI's own AI models, though details remain sparse.

hackernews · jamdesk · Jun 24, 17:47 · [Discussion](https://news.ycombinator.com/item?id=48663324)

**Background**: Major tech companies are increasingly designing custom AI chips to optimize for specific workloads and reduce reliance on NVIDIA GPUs. For example, Google has its TPU, and AWS has Inferentia. These chips are often tailored for inference, where efficiency and cost are critical. OpenAI's move follows this trend, partnering with Broadcom, a leading chip designer, to create a chip specifically for its AI models.

<details><summary>References</summary>
<ul>
<li><a href="https://openai.com/index/openai-broadcom-jalapeno-inference-chip/">OpenAI and Broadcom unveil LLM-optimized inference chip | OpenAI</a></li>
<li><a href="https://aimultiple.com/ai-chip-makers">Top 25+ AI Chip Makers: NVIDIA & Its Competitors</a></li>

</ul>
</details>

**Discussion**: Community reaction is cautiously optimistic, with some questioning the tangible benefits of AI-assisted design and the chip's long-term viability given rapid AI progress. Others note the strategic importance and compare it to Google's TPU, while pointing out reliance on TSMC for manufacturing.

**Tags**: `#AI hardware`, `#OpenAI`, `#custom chip`, `#inference`, `#Broadcom`

---

<a id="item-2"></a>
## [TRM Reward Model and New Attention Mechanism Quantify LLM Reasoning (ICML 2026 Oral)](https://mp.weixin.qq.com/s?__biz=MzIzNjc1NzUzMw==&mid=2247899199&idx=3&sn=b0d6764e50d881295fd85b75f8f9434a) ⭐️ 9.0/10

A novel Thinking-supervised Reward Model (TRM) has been proposed to evaluate the quality of LLM reasoning by supervising intermediate thought processes. Accepted as an ICML 2026 Oral paper, it is accompanied by a new efficient attention mechanism for long-context reasoning, and its open-source implementation has garnered 4,200 GitHub stars. This work addresses the long-standing challenge of quantifying LLM reasoning quality, enhancing model trustworthiness and alignment. The accompanying attention mechanism drastically reduces computational overhead for long sequences, making complex reasoning more practical and scalable. TRM employs sentence-level thinking supervision to provide rewards, moving beyond simple answer correctness. The attention mechanism integrates linear and softmax attention, reportedly reducing inference cost to 1/10 of a dense model.

rss · 量子位 · Jun 24, 04:00

**Background**: Traditional reward models for LLMs assess final output faithfulness rather than reasoning steps, often missing flawed thought processes. Long-context reasoning is hindered by the quadratic complexity of standard self-attention. TRM introduces explicit supervision on intermediate thinking, while the hybrid attention mechanism offers a resource-efficient alternative, jointly advancing both the evaluation and execution of deep reasoning.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/html/2509.25409v1">From Faithfulness to Correctness: Generative Reward Models that Think Critically</a></li>
<li><a href="https://github.com/Martin-qyma/TRM">GitHub - Martin-qyma/TRM: From Faithfulness to Correctness: Generative Reward Models that Think Critically · GitHub</a></li>
<li><a href="https://arxiv.org/html/2510.19338v1">Every Attention Matters: An Efficient Hybrid Architecture for Long-Context Reasoning</a></li>

</ul>
</details>

**Tags**: `#AI`, `#reasoning`, `#reward-model`, `#attention-mechanism`, `#ICML-2026`

---

<a id="item-3"></a>
## [China's LingSheng Supercomputer Reclaims TOP500 Top Spot with 2.198 ExaFLOPS](https://news.mydrivers.com/1/1131/1131573.htm) ⭐️ 9.0/10

On the June 23 TOP500 list, China's 'LingSheng' supercomputer at the Shenzhen National Supercomputing Center achieved first place with 2.198 ExaFLOPS HPL performance, becoming the first pure-CPU system to exceed 2 ExaFLOPS. It also topped the HPCG benchmark and placed fourth in HPL-MxP, built entirely on the domestic LingKun platform and LX2 processors. This achievement marks China's return to the top of the TOP500 after an eight-year gap, demonstrating major strides in domestic semiconductor technology and high-performance computing autonomy. It signals that China can build world-leading supercomputers without relying on foreign chips, crucial for scientific research, AI, and national security. LingSheng uses a homogeneous pure-CPU architecture with no GPU or other accelerators, a rarity among top ExaFLOPS systems. It achieved first place in the HPCG benchmark, which measures sparse matrix performance more representative of real-world applications, and fourth in the HPL-MxP mixed-precision test, highlighting strong HPC-AI convergence.

telegram · zaihuapd · Jun 23, 15:30

**Background**: The TOP500 list ranks supercomputers by their performance on the HPL (LINPACK) benchmark, which solves dense linear equations and measures floating-point operations per second (FLOPS). ExaFLOPS denotes one quintillion (10^18) FLOPS. The HPCG benchmark uses a conjugate gradient solver to gauge performance on sparse, memory-bound workloads typical of real applications. HPL-MxP is a newer benchmark that employs mixed-precision arithmetic to reflect the convergence of HPC and AI, providing a more complete view of a system's practical capabilities.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/HPL_(benchmark)">HPL (benchmark)</a></li>
<li><a href="https://en.wikipedia.org/wiki/HPCG_benchmark">HPCG benchmark</a></li>
<li><a href="https://hpl-mxp.org/">HPL - MxP Mixed - Precision Benchmark</a></li>

</ul>
</details>

**Tags**: `#supercomputing`, `#TOP500`, `#exascale`, `#domestic-technology`, `#China`

---

<a id="item-4"></a>
## [Bunny.net Makes Bunny DNS Free for Up to 500 Domains](https://bunny.net/blog/were-making-bunny-dns-free/) ⭐️ 8.0/10

Bunny.net has eliminated all DNS query fees and now offers free DNS hosting for up to 500 domains per account, including features like smart records and health monitoring. This positions Bunny.net as a competitive European alternative to Cloudflare DNS, addressing increasing demand for EU-based services due to data sovereignty and geopolitical concerns. The free tier has no query limits or per-request billing, and includes enterprise features often paywalled elsewhere. Bunny.net is a privately held company with only a $6 million funding round, focusing on organic growth rather than loss-leader strategies.

hackernews · dabinat · Jun 24, 08:50 · [Discussion](https://news.ycombinator.com/item?id=48657030)

**Background**: Bunny.net is a global edge platform offering CDN, edge storage, and DNS services across 119+ locations. Bunny DNS was previously a paid service charging per query; the shift to a free model aligns with freemium offerings from competitors but distinguishes itself by including advanced features for free.

<details><summary>References</summary>
<ul>
<li><a href="https://bunny.net/dns/">Bunny DNS | The #1 Scriptable DNS Platform | bunny.net</a></li>
<li><a href="https://grokipedia.com/page/Bunnynet">Bunny.net</a></li>
<li><a href="https://bunny.net/">bunny . net - The Global Edge Platform that truly Hops</a></li>

</ul>
</details>

**Discussion**: Comments largely praise the move as a welcome EU-based alternative to Cloudflare, though some express concerns about unexpected billing from other Bunny services and question the sustainability of free offerings. The community notes Bunny's prudent funding and organic approach as a differentiator.

**Tags**: `#DNS`, `#free-service`, `#CDN`, `#European-tech`, `#Cloudflare-alternative`

---

<a id="item-5"></a>
## [Carmack Reflects on Mistakes: 'Quake Gutted id Software'](https://twitter.com/ID_AA_Carmack/status/2069799283369345247) ⭐️ 8.0/10

John Carmack publicly acknowledged that he pushed his team too hard at id Software, and that the development of Quake severely damaged the company, sparking debate about its true cost. Carmack's candid reflection offers valuable lessons for tech leaders on sustainable work culture and the human cost of chasing technical milestones, resonating beyond the gaming industry. Notably, Carmack questions whether Quake was worth gutting the company, while some community members argue that the game's iconic status justifies the sacrifice, and others point to the exodus of creative talent after Doom.

hackernews · shadowtree · Jun 24, 15:56 · [Discussion](https://news.ycombinator.com/item?id=48661825)

**Background**: id Software, co-founded by John Carmack in 1991, revolutionized gaming with Wolfenstein 3D, Doom, and Quake. Known for his technical genius, Carmack drove the team to deliver cutting-edge 3D graphics in Quake (1996), but the intense pressure reportedly led to burnout and departures, including key designer Sandy Petersen.

**Discussion**: The community response is mixed: some agree with Carmack's self-criticism, noting that the intense push led to creative departures and a decline in artistic innovation; others argue that Quake was worth the cost given its iconic status, and that later titles like Quake III Arena showed the company still had vitality. Former id employee Sandy Petersen's interviews are referenced for his perspective on the difficult work environment.

**Tags**: `#leadership`, `#game development`, `#software engineering`, `#management`, `#startup culture`

---

<a id="item-6"></a>
## [Nub: A Bun-like All-in-one Toolkit for Node.js](https://github.com/nubjs/nub) ⭐️ 8.0/10

Nub is a newly released toolkit that enhances Node.js with Bun-like features, using a preload hook to add a transpiler and polyfills while preserving full compatibility with the standard Node.js runtime. It allows developers to enjoy modern productivity features like built-in transpilation and API polyfills without switching to a different runtime, reducing ecosystem fragmentation and easing adoption in production environments that rely on Node.js. Nub works via a `--require` preload hook that loads an oxc-powered transpiler packaged as a Node-API add-on, a module resolution hook, and polyfills for APIs like Worker and Temporal, ensuring code ultimately runs on Node’s native engine and standard library.

hackernews · colinmcd · Jun 24, 14:14 · [Discussion](https://news.ycombinator.com/item?id=48660267)

**Background**: Bun is an alternative JavaScript runtime that offers an all-in-one experience with a built-in bundler, transpiler, and package manager. A transpiler converts source code from one language or version to another (e.g., TypeScript to JavaScript), while a polyfill provides implementations of modern APIs for environments that lack them, such as adding Worker support to Node.js. Nub leverages these concepts to bring similar functionality to the widely adopted Node.js runtime.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Bun_(software)">Bun (software) - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Source-to-source_compiler">Source-to-source compiler - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Polyfill_(programming)">Polyfill (programming) - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Community response was largely positive, with praise for the additive approach and zero-issue migration reports. Some users raised concerns about production readiness, performance overhead, and security implications, which may be addressed in future updates.

**Tags**: `#node.js`, `#developer-tools`, `#toolkit`, `#transpiler`, `#polyfills`

---

<a id="item-7"></a>
## [Krea Releases Krea 2: Open-Weights 12B Image Model](https://www.krea.ai/blog/krea-2-technical-report) ⭐️ 8.0/10

Krea has released Krea 2, a state-of-the-art 12 billion parameter text-to-image model with open weights, along with a detailed technical report covering training, data curation, and inference infrastructure. This open-weights release provides researchers and developers access to a powerful image generation model, fostering transparency and innovation in the AI community, while the comprehensive report sets a new standard for documenting large-scale model development. The release includes a distilled "Turbo" variant for faster inference, and the report details architecture, RL pipelines, prompt expansion, and style references. The model focuses on aesthetic diversity and wide style capabilities.

hackernews · mattnewton · Jun 23, 15:31 · [Discussion](https://news.ycombinator.com/item?id=48646659)

**Background**: Open-weights models make their trained parameters publicly available, allowing others to use, modify, and fine-tune them. Krea is an AI creative suite that previously offered tools like real-time image generation; Krea 2 is their first in-house foundation model built from scratch.

<details><summary>References</summary>
<ul>
<li><a href="https://www.krea.ai/krea-2">Krea 2: AI Image Foundation Model & Style Control</a></li>
<li><a href="https://promptmetheus.com/resources/llm-knowledge-base/open-weights-model">Open - weights Model | LLM Knowledge Base</a></li>

</ul>
</details>

**Discussion**: The community appreciates the open weights and in-depth report, praising the model's style diversity. Some note it feels like "fighting the past war" compared to newer agentic composition models, and there is interest in GGUF quantized versions for easier local use.

**Tags**: `#open-weights`, `#image-generation`, `#AI`, `#deep-learning`, `#text-to-image`

---

<a id="item-8"></a>
## [Datasette 1.0a35 Adds Create and Alter Table Features](https://simonwillison.net/2026/Jun/23/datasette/#atom-everything) ⭐️ 8.0/10

Datasette 1.0a35 introduces a user interface and JSON API for creating new tables and altering existing ones, along with comprehensive template context documentation. These features transform Datasette from a read-only data exploration tool into one that supports full data management, making it more versatile for users who need to modify databases directly. It marks significant progress toward the long-awaited 1.0 release. The create table API supports defining columns, primary keys, custom column types, NOT NULL constraints, literal and expression defaults, and single-column foreign keys. The alter table API allows adding, renaming, reordering, and dropping columns, as well as changing types, defaults, constraints, and table names.

rss · Simon Willison · Jun 23, 21:34

**Background**: Datasette is an open-source tool by Simon Willison that allows users to explore and publish data stored in SQLite databases through a web interface. It has been widely used for data journalism and open data projects. The tool is written in Python and is highly extensible via plugins, with version 1.0 being a major milestone after years of development.

**Tags**: `#python`, `#datasette`, `#sqlite`, `#data-exploration`, `#release`

---

<a id="item-9"></a>
## [Prompt Injection as Role Confusion: LLMs Fail to Distinguish System from User Prompts](https://simonwillison.net/2026/Jun/22/prompt-injection-as-role-confusion/#atom-everything) ⭐️ 8.0/10

Research confirms that LLMs cannot reliably distinguish system prompts from user inputs, instead relying on textual style cues, which leads to security vulnerabilities. A new paper introduces "role confusion" as the underlying mechanism and demonstrates that "destyling" adversarial text drastically reduces attack success. This finding exposes a fundamental security flaw in LLM design, indicating that prompt injection defenses are currently playing a "whack-a-mole" game. It has significant implications for deploying LLMs safely in real-world applications, as attackers can craft subtle, style-mimicking prompts to bypass safeguards. The study tested models like gpt-oss-20b, and found that appending a policy statement in the model's internal thinking style could override safety training. "Destyling" the injected text—rewriting it to not match the expected format—reduced attack success from 61% to 10%, highlighting the models' dependency on style over content.

rss · Simon Willison · Jun 22, 23:59

**Background**: Prompt injection is a cybersecurity attack where malicious instructions are disguised as legitimate user input, causing LLMs to perform unintended actions. LLMs are trained to follow instructions but struggle to separate developer-defined system prompts from user inputs. Jailbreaks are techniques to bypass built-in safety filters, often by manipulating the model's perception of its role. The concept of "role confusion" describes how models may misinterpret which source a command originates from based on superficial features like writing style. The discussed research shows that even advanced models are susceptible, as they lack genuine understanding of role boundaries.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Prompt_injection">Prompt injection</a></li>
<li><a href="https://www.ibm.com/think/topics/prompt-injection">What Is a Prompt Injection Attack? | IBM</a></li>

</ul>
</details>

**Tags**: `#prompt injection`, `#AI safety`, `#LLM security`, `#jailbreaks`, `#role confusion`

---

<a id="item-10"></a>
## [Porting Moebius 0.2B image inpainting model to browser with WebGPU](https://simonwillison.net/2026/Jun/22/porting-moebius/#atom-everything) ⭐️ 8.0/10

Simon Willison successfully ported the Moebius 0.2B image inpainting model to run directly in the browser using WebGPU, and created a live demo. This removes the need for a CUDA-capable GPU, making high-quality image inpainting accessible to anyone with a modern browser, while preserving privacy by running locally. The model uses ONNX Runtime Web with a WebGPU backend; the demo accepts any image (non-square images are letterboxed), and the entire port was assisted by the AI coding agent Claude Code.

rss · Simon Willison · Jun 22, 23:43

**Background**: Image inpainting is the task of filling in missing or removed parts of an image with plausible content. Moebius is a lightweight (0.2B parameters) inpainting model that claims performance comparable to much larger models. WebGPU is a modern browser API that enables high-performance GPU access directly from web pages, and Claude Code is an agentic coding tool from Anthropic that can edit files and run commands.

<details><summary>References</summary>
<ul>
<li><a href="https://simonwillison.net/2026/Jun/22/porting-moebius/">Porting the Moebius 0.2B image inpainting model to run in the browser with Claude Code</a></li>
<li><a href="https://hustvl.github.io/Moebius/">Moebius Project Page</a></li>
<li><a href="https://en.wikipedia.org/wiki/WebGPU">WebGPU</a></li>

</ul>
</details>

**Tags**: `#webgpu`, `#image-inpainting`, `#machine-learning`, `#browser`, `#tutorial`

---

<a id="item-11"></a>
## [DeepSWE: A contamination-free benchmark for real-world coding tasks](https://www.reddit.com/r/MachineLearning/comments/1ue0hlp/deepswe_new_benchmark_looking_at_how_well_todays/) ⭐️ 8.0/10

DeepSWE is a novel open-source benchmark for coding agents, constructed from scratch to avoid data contamination and spanning 91 repositories across five programming languages. It employs behavior verifiers to reliably assess model performance on complex, real-world software engineering tasks. DeepSWE provides a contamination-free, realistic evaluation of AI coding capabilities, exposing performance gaps hidden by existing benchmarks and pushing the development of more capable autonomous software engineering agents. Tasks in DeepSWE require 5.5 times more code and twice the output tokens compared to SWE-bench Pro, while verifiers check software behavior rather than exact code matches. On the published snapshot, GPT-5.5 leads with 70% pass@1, followed by Claude Opus at 54%.

reddit · r/MachineLearning · /u/we_are_mammals · Jun 24, 02:03

**Background**: Existing coding benchmarks often reuse tasks from public GitHub commits, leading to data contamination where models may have memorized solutions. SWE-bench Pro attempted to mitigate this but still contains issues from known repositories. Behavior verifiers assess whether the software behaves correctly under given inputs, unlike code-matching checks. DeepSWE's tasks are written from scratch, ensuring no model has seen them before.

<details><summary>References</summary>
<ul>
<li><a href="https://deepswe.datacurve.ai/">DeepSWE</a></li>
<li><a href="https://benchlm.ai/benchmarks/deepSwe">DeepSWE Benchmark 2026: 8 pass@1 rows | BenchLM.ai</a></li>
<li><a href="https://venturebeat.com/technology/deepswe-blows-up-the-ai-coding-leaderboard-crowns-gpt-5-5-and-finds-claude-opus-exploiting-a-benchmark-loophole">DeepSWE blows up the AI coding leaderboard, crowns GPT-5.5, and finds Claude Opus exploiting a benchmark loophole | VentureBeat</a></li>

</ul>
</details>

**Tags**: `#machine learning`, `#benchmarks`, `#code generation`, `#large language models`, `#software engineering`

---

<a id="item-12"></a>
## [Superhuman Generals.io Agent via Self-Play RL with JAX and Vision Transformer](https://www.reddit.com/r/MachineLearning/comments/1uei2yg/i_made_a_superhuman_generalsio_agent_with/) ⭐️ 8.0/10

A self-play reinforcement learning agent for Generals.io achieved superhuman performance, ranking #1 on the 1v1 leaderboard. The agent uses a Vision Transformer architecture and was reimplemented in JAX for scalability, with the entire pipeline open-sourced. It demonstrates that investing in scalable architectures like Vision Transformers over handcrafted priors yields superior results in complex, imperfect-information RTS games. The open-source release provides a reusable, high-speed simulator and a practical guide for the community. The project began as a master's thesis using behavior cloning and reward-shaped RL fine-tuning, but top players still won. The second iteration switched from NumPy/Torch to JAX and replaced CNN with ViT, focusing purely on scaling. The fast JAX simulator is designed for imperfect-information RTS environments, though the current agent is specialized for 1v1 matches.

reddit · r/MachineLearning · /u/shrekofspeed · Jun 24, 16:18

**Background**: Generals.io is an online multiplayer real-time strategy game with imperfect information. Self-play is a reinforcement learning technique where agents improve by playing against themselves. JAX is a high-performance Python library for numerical computing with automatic differentiation, ideal for scaling on accelerators. Vision Transformers apply the Transformer architecture to images, using self-attention over patches instead of convolutions to capture global features.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Self-play_(reinforcement_learning_technique)">Self-play (reinforcement learning technique)</a></li>
<li><a href="https://en.wikipedia.org/wiki/JAX_(software)">JAX (software) - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Vision_transformer">Vision transformer - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#reinforcement-learning`, `#self-play`, `#jax`, `#game-ai`, `#vision-transformer`

---

<a id="item-13"></a>
## [LLM Inference Pricing Comparison Reveals Vast Caching Cost Differences](https://www.reddit.com/r/MachineLearning/comments/1ueavxn/i_compiled_llm_inference_pricing_across_7/) ⭐️ 8.0/10

A Reddit user compiled public LLM inference pricing from seven providers into a spreadsheet, revealing that cached input costs can vary by an order of magnitude across providers for the same model, such as DeepSeek V4 Pro. This highlights that for applications with reusable context (e.g., agents, RAG, multi-turn chats), caching policies can dominate total costs, making provider selection more about cache efficiency than raw token pricing. The spreadsheet tracks input/output pricing, context windows, and cached input pricing across providers like OpenRouter, Together AI, Fireworks, and Groq, but does not include throughput, latency, or quantization details.

reddit · r/MachineLearning · /u/Technomadlyf · Jun 24, 11:28

**Background**: Prompt caching stores previously computed embeddings for reused prompt prefixes, dramatically reducing costs and latency. For example, caching can cut costs by up to 90% according to AWS. This is especially relevant for RAG (retrieval-augmented generation) systems and multi-turn agents that repeatedly send large system prompts. Many providers offer caching, but pricing and transparency vary.

<details><summary>References</summary>
<ul>
<li><a href="https://projectdiscovery.io/blog/how-we-cut-llm-cost-with-prompt-caching">How We Cut LLM Costs by 59% With Prompt Caching — ProjectDiscovery Blog</a></li>
<li><a href="https://aws.amazon.com/blogs/database/optimize-llm-response-costs-and-latency-with-effective-caching/">Optimize LLM response costs and latency with effective caching | Amazon Web Services</a></li>
<li><a href="https://openrouter.ai/deepseek/deepseek-v4-pro">DeepSeek V4 Pro - API Pricing & Benchmarks | OpenRouter</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#pricing`, `#inference`, `#caching`, `#cost optimization`

---

<a id="item-14"></a>
## [Critical RCE Vulnerability Found in FFmpeg's MagicYUV Decoder](https://cybernews.com/security/critical-ffmpeg-vulnerability-enables-complete-compromise/) ⭐️ 8.0/10

A critical remote code execution vulnerability (CVE-2026-8461, CVSS 8.8) was discovered in the MagicYUV decoder of FFmpeg, allowing attackers to craft malicious video files that trigger system compromise upon playback or scanning. The issue has been fixed in FFmpeg version 8.1.2. FFmpeg is a foundational multimedia library used by countless applications (VLC, Jellyfin, Kodi, OBS, etc.) on desktops, servers, and IoT devices. Exploitation requires minimal user interaction, such as opening a file or automatic thumbnail generation, making this a widespread and stealthy threat. Dubbed "PixelSmash", the vulnerability resides specifically in the MagicYUV lossless video codec. JFrog researchers confirmed impact on Nextcloud, OBS, and other applications; mitigation involves updating to FFmpeg 8.1.2 or disabling the MagicYUV decoder at compile time if not needed.

telegram · zaihuapd · Jun 23, 15:00

**Background**: MagicYUV is a high-performance lossless video codec commonly used in editing and streaming applications. FFmpeg is an open-source multimedia framework that underpins media processing in many popular players and servers, supporting encoding, decoding, and transcoding of nearly all formats.

<details><summary>References</summary>
<ul>
<li><a href="https://www.magicyuv.com/">MagicYUV – Lossless video codec</a></li>
<li><a href="https://www.free-codecs.com/download/magicyuv.htm">MagicYUV Lossless Video Codec 2.4.1 Download</a></li>

</ul>
</details>

**Tags**: `#security`, `#vulnerability`, `#ffmpeg`, `#remote-code-execution`, `#media-processing`

---

<a id="item-15"></a>
## [LastPass Suffers Data Breach via Klue, Exposing Customer Support Records](https://techcrunch.com/2026/06/23/password-manager-maker-lastpass-says-hackers-stole-customer-support-case-data-during-klue-breach/) ⭐️ 8.0/10

In June 2026, hackers breached Klue, a competitive intelligence platform used by LastPass, stealing customer support case data including names, phone numbers, emails, and addresses. This breach highlights supply chain risks, as even if LastPass's own infrastructure and password vaults remain secure, partner weaknesses can expose sensitive user data, affecting over 33 million users. The attack was claimed by the Icarus ransomware group; LastPass confirmed no password vaults were compromised, and the breach occurred through Klue's Salesforce integration. LastPass had 33 million users in 2024.

telegram · zaihuapd · Jun 24, 00:49

**Background**: Klue is a Canadian competitive enablement platform that integrates with Salesforce to collect competitive intelligence. LastPass, a popular password manager, previously suffered a major breach in 2022 where encrypted password vaults were stolen. The Icarus group is a relatively new ransomware actor known for targeting supply chain vulnerabilities and extorting victims.

<details><summary>References</summary>
<ul>
<li><a href="https://grokipedia.com/page/Klue_company">Klue (company)</a></li>
<li><a href="https://rhisac.org/threat-intelligence/icarus-threat-group-claims-salesforce-data-theft-in-klue-supply-chain-breach/">RH-ISAC | Icarus Threat Group Claims Salesforce Data Theft in Klue Supply Chain Breach - RH-ISAC</a></li>
<li><a href="https://www.bleepingcomputer.com/news/security/klue-oauth-breach-linked-to-icarus-salesforce-data-theft-attacks/">Klue OAuth breach linked to 'Icarus' Salesforce data theft attacks</a></li>

</ul>
</details>

**Tags**: `#cybersecurity`, `#data breach`, `#password manager`, `#supply chain`, `#LastPass`

---

<a id="item-16"></a>
## [Generative AI for Homework Lowers Chinese Students' Exam Scores](https://cepr.org/publications/dp21577) ⭐️ 8.0/10

A 30-month study of 26,811 Chinese students in grades 7-12 found that using generative AI for homework improved assignment scores by 18% and cut completion time by 30%, but led to a 20% drop in closed-book monthly exam scores within six months and an 18-24% decline in high-stakes exams like the Zhongkao and Gaokao, with full effects emerging after about two years. This large-scale evidence reveals the negative side-effects of generative AI in education, specifically "homework outsourcing" that undermines real learning, especially for younger, high-achieving, and male students, carrying important implications for educational policy and AI usage guidelines. Around 80% of AI users exhibited "homework outsourcing" traits—extremely short homework time but high scores—and bore the main losses; those who maintained homework time similar to non-AI users saw smaller declines. Social sciences subjects were affected the most, followed by STEM and languages.

telegram · zaihuapd · Jun 24, 05:15

**Background**: Generative AI tools like ChatGPT can produce human-like text and are increasingly used by students for assignments. Prior concerns about academic integrity and learning impacts lacked rigorous causal evidence. This study fills the gap by tracking student outcomes over an extended period in a real-world setting.

**Tags**: `#generative AI`, `#education`, `#student performance`, `#academic integrity`, `#AI impact`

---

<a id="item-17"></a>
## [RubyLLM: A Unified AI Framework for Ruby](https://rubyllm.com/) ⭐️ 7.0/10

RubyLLM, recently spotlighted on Hacker News, is a Ruby gem (v1.0) offering a unified API for major AI providers like OpenAI and Anthropic, earning praise for its elegant design and developer experience. It fills a critical gap in the Ruby ecosystem by simplifying AI integration and enabling vendor-agnostic development, lowering barriers for the large Ruby community to build AI-powered applications. RubyLLM 1.0 supports features like caching and streaming out of the box, though some users reported caching issues with xAI. It is often compared to JavaScript's Vercel AI SDK for its developer-friendly abstractions.

hackernews · doener · Jun 24, 14:41 · [Discussion](https://news.ycombinator.com/item?id=48660711)

**Background**: Ruby is widely used for web development with Rails but has lagged in AI compared to Python. RubyLLM is a native solution that brings idiomatic AI capabilities to Rubyists, supporting multiple providers and emphasizing developer happiness, a core Ruby community value.

<details><summary>References</summary>
<ul>
<li><a href="https://dev.to/crmne/introducing-rubyllm-10-a-beautiful-way-to-work-with-ai-5p0">Introducing RubyLLM 1.0: A Beautiful Way to Work with AI - DEV Community</a></li>
<li><a href="https://medium.com/@raviskit2012/rubyllm-the-ruby-gem-that-makes-ai-feel-right-at-home-a34a1d18def4">💎 RubyLLM: The Ruby Gem That Makes AI Feel Right at Home | by Ravi Prakash | Medium</a></li>

</ul>
</details>

**Discussion**: Hacker News commenters were enthusiastic about RubyLLM's design and usability, comparing it to Vercel's AI framework. Some noted practical issues like xAI caching bugs, while others questioned the benefit over direct provider SDKs for single-provider use. Overall, the community sees it as a valuable addition to the Ruby AI landscape.

**Tags**: `#ruby`, `#ai`, `#llms`, `#open-source`, `#framework`

---

<a id="item-18"></a>
## [OPFS + Pyodide Test Harness for Browser SQLite Persistence](https://simonwillison.net/2026/Jun/23/opfs-pyodide/#atom-everything) ⭐️ 7.0/10

Simon Willison built a playground UI to test using the Origin Private File System (OPFS) for persistent SQLite storage in Pyodide-based applications, potentially enabling Datasette Lite to edit SQLite files locally in the browser. This development could allow in-browser Python data tools to store and modify SQLite databases locally, advancing offline-capable, privacy-preserving web applications. The harness leverages OPFS, a sandboxed, high-performance origin-specific virtual filesystem, and Pyodide to run SQLite via WebAssembly. It is experimental and aims to evaluate cross-browser support.

rss · Simon Willison · Jun 23, 18:58

**Background**: The Origin Private File System (OPFS) is part of the File System API, providing private, high-performance storage per web origin. Pyodide compiles Python and C extensions to WebAssembly, enabling Python in the browser. Datasette Lite is a full Datasette instance running via Pyodide, but it previously lacked the ability to persistently edit SQLite files.

<details><summary>References</summary>
<ul>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/API/File_System_API/Origin_private_file_system">Origin private file system - Web APIs | MDN</a></li>
<li><a href="https://web.dev/articles/origin-private-file-system">The origin private file system | Articles | web.dev</a></li>
<li><a href="https://pyodide.org/en/stable/console.html">pyodide .org/en/stable/console.html</a></li>

</ul>
</details>

**Tags**: `#browsers`, `#pyodide`, `#datasette-lite`, `#WebAssembly`, `#SQLite`

---

<a id="item-19"></a>
## [MuJoFil: GPU-Native High-Fidelity Simulator for Vision RL](https://www.reddit.com/r/MachineLearning/comments/1uemrch/mujoco_derived_simulator_for_high_fidelity_vision/) ⭐️ 7.0/10

A new open-source simulator, MuJoFil, combines Nvidia's Newton physics engine with Google's Filament renderer for GPU-native parallelized training of vision-based reinforcement learning. It allows users to import various 3D environments and provides both CPU and CUDA variants. It addresses the gap for GPU-accelerated, open-source simulators tailored for vision-based RL, enabling high-fidelity training without expensive hardware or licenses. This could make scalable robot learning more accessible. The simulator significantly modifies Filament to run natively on GPU for parallel rendering, supports PBR textures, and can load environments in GLB and OpenUSD formats. It is early-stage with bugs expected, and is available as two pip packages: mujofil (CPU) and mujofil-warp (CUDA, to be renamed mujofil-cuda).

reddit · r/MachineLearning · /u/MT1699 · Jun 24, 19:07

**Background**: MuJoCo is a popular open-source physics engine but its CPU dependency limits parallel scaling; MJX offers GPU acceleration yet is unsuitable for vision tasks. Newton is an open-source GPU-native physics engine built on MuJoCo by NVIDIA, Google DeepMind, and Disney Research. Filament is Google's open-source real-time physically based renderer. MuJoFil integrates and adapts these two to enable efficient high-fidelity visual simulation on GPUs.

<details><summary>References</summary>
<ul>
<li><a href="https://developer.nvidia.com/newton-physics">Newton Physics Engine | NVIDIA Developer</a></li>
<li><a href="https://github.com/google/filament">google / filament : Filament is a real-time physically based rendering ...</a></li>

</ul>
</details>

**Tags**: `#reinforcement-learning`, `#simulation`, `#computer-vision`, `#gpu-computing`, `#open-source`

---

<a id="item-20"></a>
## [Are Model Security Risks Actually Tested in Production?](https://www.reddit.com/r/MachineLearning/comments/1uddtws/are_model_security_risks_extraction_poisoning/) ⭐️ 7.0/10

A Reddit post by u/Xorphian highlights that many ML teams skip adversarial testing for model extraction and poisoning before deployment, asking if anyone actually conducts such security reviews. This gap could leave models vulnerable to intellectual property theft via extraction and malicious behavior manipulation via poisoning, underscoring the immaturity of MLOps security compared to traditional software. Model extraction attacks use black-box query access to steal model functionality, while poisoning attacks inject malicious data into training pipelines. The post received a high score, indicating widespread concern among practitioners.

reddit · r/MachineLearning · /u/Xorphian · Jun 23, 10:52

**Background**: Model extraction occurs when an attacker replicates a model's behavior by repeatedly querying its API, potentially stealing proprietary models. Model poisoning corrupts training data to cause targeted misbehaviors. While adversarial testing is standard in software security, it is often neglected in ML workflows.

<details><summary>References</summary>
<ul>
<li><a href="https://www.praetorian.com/blog/stealing-ai-models-through-the-api-a-practical-model-extraction-attack/">Stealing AI Models Through the API: A Practical Model Extraction Attack | Praetorian</a></li>
<li><a href="https://medium.com/@AT24/data-integrity-model-poisoning-tryhackme-12859f52f8ae">Data Integrity & Model Poisoning | Tryhackme | by Aaron | Medium</a></li>
<li><a href="https://www.csoonline.com/article/570555/how-data-poisoning-attacks-corrupt-machine-learning-models.html">What is data poisoning ? Attacks thatcorrupt machine learning models</a></li>

</ul>
</details>

**Tags**: `#machine learning security`, `#adversarial testing`, `#model extraction`, `#model poisoning`, `#production ML`

---

<a id="item-21"></a>
## [TSMC to Raise Prices on Advanced Process Nodes by 5-10%](https://36kr.com/newsflashes/3866472254411779) ⭐️ 7.0/10

TSMC has notified customers of a 5-10% price increase for its advanced process technologies, including 7nm and below, affecting about 75% of wafer revenue. This price hike will increase costs for major chip designers like Apple, AMD, and NVIDIA, potentially leading to higher consumer electronics prices and impacting the semiconductor supply chain. The increase applies not only to the rumored 3nm node but also to 7nm and all other advanced nodes, with an overall hike of 5-10%. This covers the majority of TSMC's wafer revenue source.

telegram · zaihuapd · Jun 24, 05:45

**Background**: TSMC is the world's leading semiconductor foundry, manufacturing chips for companies that design but don't fabricate their own silicon. Advanced process nodes like 7nm, 5nm, and 3nm are used for high-performance chips in smartphones, GPUs, and AI processors. Price adjustments by TSMC ripple through the global tech supply chain, affecting end-product pricing and company margins.

**Tags**: `#semiconductors`, `#TSMC`, `#chip manufacturing`, `#pricing`, `#advanced processes`

---

<a id="item-22"></a>
## [Stealing Is a Skill](https://ben-mini.com/2026/stealing-is-a-skill) ⭐️ 6.0/10

A recent blog post argues that copying and imitation are essential skills for learning and fostering creativity in design and other fields. This perspective encourages creators to reassess the role of imitation in creative development, potentially reducing stigma and fostering more practical skill-building approaches. The post, while short on content, sparked substantial community discussion, with commenters drawing analogies to copywork in writing and learning songs in music, and debating the line between inspiration and theft.

hackernews · bewal416 · Jun 24, 13:08 · [Discussion](https://news.ycombinator.com/item?id=48659165)

**Background**: The concept of 'copywork' has long been used in writing and music education, where learners transcribe or replicate masterworks to internalize techniques. In design, imitation has been a traditional training method, though modern discourse often prioritizes originality. The post appears to advocate for a return to this practice.

**Discussion**: Community reaction is mixed: many agree, citing personal experiences with copywork in writing and music, while others caution against confusing imitation with outright theft, and some challenge the depth of learning gained from mere replication.

**Tags**: `#creativity`, `#design`, `#imitation`, `#learning`, `#copywork`

---

<a id="item-23"></a>
## [Tom MacWright: LLM-Generated Resumes Make Candidates Anonymous](https://simonwillison.net/2026/Jun/24/tom-macwright/#atom-everything) ⭐️ 6.0/10

Tom MacWright notes a rise in LLM-generated job applications, portfolios, and GitHub projects, resulting in candidates indistinguishable from one another. He argues that these AI-assisted materials strip away personal authenticity. This trend raises concerns about the effectiveness of hiring processes, as employers struggle to discern actual skills and personality behind AI-polished applications, potentially overlooking talented individuals. The anonymity extends beyond résumés to LLM-generated portfolio sites, GitHub projects, and commit messages, making it impossible for evaluators to learn about candidates' genuine abilities or thoughts.

rss · Simon Willison · Jun 24, 18:13

**Background**: Large language models (LLMs) like GPT-4 can generate coherent text based on prompts, and are increasingly used to write or refine job applications, portfolios, and code. While they can improve formatting and grammar, over-reliance may obscure a candidate's unique voice and experiences.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Large_language_model">Large language model - Wikipedia</a></li>
<li><a href="https://azure.microsoft.com/en-us/resources/cloud-computing-dictionary/what-are-large-language-models-llms">What are large language models (LLMs)? | Microsoft Azure</a></li>

</ul>
</details>

**Tags**: `#ai`, `#careers`, `#llm`, `#hiring`, `#impersonality`

---

<a id="item-24"></a>
## [High-Dimensional Dynamic RoPE Converges Faster Than xPos on TinyStories](https://www.reddit.com/r/MachineLearning/comments/1uelcm9/high_dimensional_dynamic_rotary_positional/) ⭐️ 6.0/10

A researcher introduced HDD-RoPE, a novel positional embedding that generalizes Rotary Position Embedding (RoPE) to higher dimensions and makes rotation data-dependent. When tested on the TinyStories dataset with a 33M-parameter GPT-2 model, HDD-RoPE achieved faster validation loss convergence than the xPos baseline. Positional embeddings are critical for transformers to understand token order. HDD-RoPE's multidimensional, dynamic approach could enable models to capture richer positional structures like sentence and paragraph boundaries, potentially improving long-context understanding and model efficiency. Standard RoPE groups query/key dimensions in pairs and applies fixed rotary frequencies. HDD-RoPE allows grouping into larger chunks (e.g., groups of 4), corresponding to higher-dimensional rotations (6 axes for 4D chunks), and the rotation angles are computed dynamically from layer activations, letting the model learn how position advances within learned constructs.

reddit · r/MachineLearning · /u/mikayahlevi · Jun 24, 18:16

**Background**: Transformer models process sequences of tokens but are inherently order-agnostic, so positional information must be injected. Rotary Position Embedding (RoPE) is a widely used method that encodes relative position by rotating query and key vectors. xPos is a variant of RoPE designed to improve length extrapolation. TinyStories is a small dataset of simple stories used for fast experimentation in language model training.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Rotary_positional_embedding">Rotary positional embedding</a></li>

</ul>
</details>

**Tags**: `#positional-encoding`, `#transformers`, `#RoPE`, `#machine-learning`, `#NLP`

---

<a id="item-25"></a>
## [New Proof: 14 Sloppy Riffle Shuffles Randomize a Deck](https://www.quantamagazine.org/seven-perfect-shuffles-randomize-a-deck-of-cards-but-how-many-sloppy-ones-20260617/) ⭐️ 6.0/10

A new mathematical model shows that with random cuts, a standard 52-card deck requires about 14 riffle shuffles to fully randomize, instead of the classic 7 perfect shuffles. This refines our understanding of card shuffling in practice and has implications for cutoff phenomena in Markov chains and other dynamical systems. The model tracks each card with a binary 'barcode' and detects 'cold spots' of residual order. It still assumes cards interleave one by one, not in clumps.

telegram · zaihuapd · Jun 23, 16:04

**Background**: In 1992, mathematicians proved that 7 perfect riffle shuffles suffice to randomize a deck, assuming the cut perfectly halves the cards. The new study relaxes this to random cut positions. The cutoff phenomenon describes how a deck abruptly transitions from ordered to mixed after a critical number of shuffles.

<details><summary>References</summary>
<ul>
<li><a href="https://www.quantamagazine.org/seven-perfect-shuffles-randomize-a-deck-of-cards-but-how-many-sloppy-ones-20260617/">Seven Perfect Shuffles Randomize a Deck of Cards. But How Many Sloppy Ones? | Quanta Magazine</a></li>
<li><a href="https://en.wikipedia.org/wiki/Shuffling">Shuffling - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#mathematics`, `#probability`, `#card-shuffling`, `#randomization`, `#combinatorics`

---

<a id="item-26"></a>
## [Xiaomi's First NAS 'Xiaomi Smart Storage' Launches December with Xiaomi 17 Ultra](https://t.me/zaihuapd/42147) ⭐️ 6.0/10

Xiaomi's first NAS, named 'Xiaomi Smart Storage', is a dual-bay ARM-based device integrated with the Mi Home ecosystem, expected to launch in December alongside the Xiaomi 17 Ultra. This marks Xiaomi's entry into the home NAS market, offering a local storage solution with seamless phone backup and media center features, potentially reducing reliance on cloud subscriptions and expanding Xiaomi's smart home ecosystem. The device features an ARM processor, two drive bays, metal casing, and integrated video metadata scraping for poster wall generation; however, full specifications and pricing are yet to be revealed.

telegram · zaihuapd · Jun 24, 02:52

**Background**: NAS, or Network Attached Storage, is a dedicated file storage device that connects to a home network, allowing multiple users and devices to access and share data. The dual-bay design enables RAID configurations for data redundancy or increased capacity. ARM-based NAS devices, like the UGREEN NASync series, are popular for home use due to their low power consumption and quiet operation.

<details><summary>References</summary>
<ul>
<li><a href="https://nas.ugreen.com/">UGREEN NAS Storage : 2-Bay to 8-Bay Models with Free Trials</a></li>

</ul>
</details>

**Tags**: `#Xiaomi`, `#NAS`, `#Smart Home`, `#Consumer Electronics`, `#Storage`

---

<a id="item-27"></a>
## [Trump says Anthropic no longer a national security threat, may ease model restrictions](https://t.me/zaihuapd/42148) ⭐️ 6.0/10

In an Axios interview, former President Trump stated he no longer views AI company Anthropic as a national security threat and indicated he may relax restrictions on its Fable 5 and Mythos 5 models, following a meeting with CEO Dario Amodei at the G7 summit. Trump's changed stance could foreshadow a relaxation of export controls on advanced AI models, potentially allowing Anthropic to more freely deploy its technology globally. This highlights the ongoing tension between promoting AI innovation and enforcing national security safeguards. Despite his remarks, the U.S. Commerce Department's June 12 order requiring Anthropic to restrict foreign access to its strongest models has not been formally revoked, and the Pentagon's supply chain risk designation remains. Claude Fable 5 is a publicly available Mythos-class model released in June 2026, while Claude Mythos 5 is a more restricted model only accessible to select partners.

telegram · zaihuapd · Jun 24, 03:45

**Background**: Anthropic is an AI company known for its Claude family of large language models. In June 2026, it released Claude Fable 5, its first publicly available Mythos-class model, achieving state-of-the-art results on many benchmarks. Shortly after, the U.S. government imposed export controls on both Fable 5 and the more advanced Claude Mythos 5, citing national security risks. These restrictions are part of a broader effort to prevent sensitive AI technology from reaching adversaries.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_Mythos">Claude Mythos - Wikipedia</a></li>
<li><a href="https://www.cnbc.com/2026/06/09/anthropic-mythos-claude-fable-5.html">Anthropic releases Mythos-like AI model to the public, Claude Fable 5</a></li>
<li><a href="https://www.anthropic.com/claude/fable">Claude Fable \ Anthropic</a></li>

</ul>
</details>

**Tags**: `#AI policy`, `#Anthropic`, `#Trump`, `#national security`, `#regulation`

---

<a id="item-28"></a>
## [Cloudflare and Browsers Propose PACT to Replace CAPTCHAs with Tokens](https://www.techtimes.com/articles/318891/20260623/cloudflare-chrome-firefox-plan-replace-captchas-cryptographic-tokens.htm) ⭐️ 6.0/10

Cloudflare, in collaboration with Chrome, Firefox, Edge, and Shopify, has proposed the PACT protocol, which uses anonymous cryptographic tokens based on IETF's Privacy Pass and blind signature technology to let users authenticate without solving CAPTCHAs. This could enhance user privacy by eliminating repetitive image-recognition challenges, while still preventing bot abuse, and may set a new standard for seamless, privacy-preserving web authentication. PACT issues tokens after a user is verified by a trusted site, allowing access to other sites without re-identification; it also aims to distinguish legitimate AI agents from malicious scrapers, though governance of token issuers and Apple's absence remain open issues.

telegram · zaihuapd · Jun 24, 06:30

**Background**: CAPTCHAs are distorted text or image puzzles used to tell humans and bots apart. Privacy Pass is an IETF protocol that enables anonymous token-based authentication. Blind signatures allow a signer to sign a message without seeing its content, ensuring the signature cannot be linked back to the specific signing instance. PACT applies these concepts to let a user prove their humanity once and reuse that proof across sites privately.

<details><summary>References</summary>
<ul>
<li><a href="https://privacypass.github.io/">Privacy Pass</a></li>
<li><a href="https://en.wikipedia.org/wiki/Blind_signature">Blind signature</a></li>

</ul>
</details>

**Tags**: `#web security`, `#cryptography`, `#captcha`, `#privacy`, `#protocol`

---

<a id="item-29"></a>
## [ByteDance Reported Co-Developing 5nm AI Chip with Broadcom; Company Denies](https://t.me/zaihuapd/42153) ⭐️ 6.0/10

An unverified report claims ByteDance is working with Broadcom to co-develop a 5nm AI processor, with manufacturing planned at TSMC, though ByteDance has publicly denied the rumor. If true, the move would reflect ByteDance's strategy to secure a dedicated supply of advanced AI chips amid U.S. export restrictions, mirroring a broader industry shift toward in-house silicon development among Chinese tech firms. The chip is rumored to use a 5nm process and would be manufactured by TSMC, with design work progressing but the critical 'tape-out' phase not yet reached. ByteDance previously purchased Nvidia and Huawei Ascend 910B chips, the latter being a Chinese-designed AI accelerator.

telegram · zaihuapd · Jun 24, 07:01

**Background**: The 5nm process node is an advanced semiconductor manufacturing technology that follows 7nm, offering higher transistor density and efficiency, with TSMC being a leading foundry. Tape-out is the final stage in chip design when the layout is sent for fabrication. Huawei's Ascend 910B is an AI chip produced by Chinese foundry SMIC and used domestically for AI workloads.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/5_nm_process">5 nm process - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Tape-out">Tape-out - Wikipedia</a></li>
<li><a href="https://www.tomshardware.com/tech-industry/artificial-intelligence/huaweis-homegrown-ai-chip-examined-chinese-fab-smic-produced-ascend-910b-is-massively-different-from-the-tsmc-produced-ascend-910">Huawei's homegrown AI chip examined — Chinese fab SMIC-produced Ascend 910B is massively different from the TSMC-produced Ascend 910 | Tom's Hardware</a></li>

</ul>
</details>

**Tags**: `#AI chips`, `#ByteDance`, `#Broadcom`, `#semiconductors`, `#rumor`

---

<a id="item-30"></a>
## [OpenAI Open-Sources planttalk: Voice Chat with Plants Using ChatGPT](https://github.com/openai/planttalk) ⭐️ 6.0/10

OpenAI has released planttalk, an open-source project that enables voice chats with houseplants via ChatGPT, a camera, and a microphone, with optional Arduino sensors for more accurate interactions. This project demonstrates how AI agents can create playful, interactive experiences with nature, hinting at broader applications in smart homes and personal well-being. The basic setup requires only a computer with a camera and mic; users can customize the plant's name, personality, and voice, and Codex Desktop guides the setup. Arduino sensors for soil moisture and light improve feedback.

telegram · zaihuapd · Jun 24, 08:14

**Background**: OpenAI's Codex Desktop is a command center for AI agents, assisting with coding and automation. ChatGPT is a large language model for generating human-like text. Arduino is an open-source electronics platform for building interactive devices.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/orgs/openai/repositories">openai repositories · GitHub</a></li>
<li><a href="https://openai.com/index/introducing-the-codex-app/">Introducing the Codex app | OpenAI</a></li>

</ul>
</details>

**Tags**: `#OpenAI`, `#ChatGPT`, `#open-source`, `#IoT`, `#AI-demo`

---