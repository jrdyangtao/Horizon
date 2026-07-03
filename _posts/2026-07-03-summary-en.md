---
layout: default
title: "Horizon Summary: 2026-07-03 (EN)"
date: 2026-07-03
lang: en
---

> From 59 items, 22 important content pieces were selected

---

1. [Sam Altman Offers U.S. Government 5% Stake in OpenAI](#item-1) ⭐️ 9.0/10
2. [Jamesob's guide to running SOTA LLMs locally](#item-2) ⭐️ 8.0/10
3. [Valve Open-Sources Steam Machine E-Ink Display for DIY Builds](#item-3) ⭐️ 8.0/10
4. [Wordgard: New Rich-Text Editor by ProseMirror Creator](#item-4) ⭐️ 8.0/10
5. [Half-Baked Product: A Critique of Startup Culture](#item-5) ⭐️ 8.0/10
6. [HAT-4D Generates 4D Interactive Scenes Directly from Monocular Video](#item-6) ⭐️ 8.0/10
7. [Contrastive Decoding Diffing Recovers Finetuning Data from Logits](#item-7) ⭐️ 8.0/10
8. [Tencent's Atuanyin AI Outperforms Mythos on CyberGym Benchmark at Minimal Cost](#item-8) ⭐️ 8.0/10
9. [Ubicloud Advocates Strict Memory Overcommit for PostgreSQL to Avoid OOM Killer](#item-9) ⭐️ 7.0/10
10. [Understand to Participate: Avoid Cognitive Debt with AI Agents](#item-10) ⭐️ 7.0/10
11. [Hamiltonian Neural Networks from a Differential Geometry Perspective](#item-11) ⭐️ 7.0/10
12. [Gemini Omni Flash Tops Video Arena with 101-Point Lead](#item-12) ⭐️ 7.0/10
13. [Claude Fable 5 Relaunch Draws User Criticism Over Safety Over-Filtering](#item-13) ⭐️ 7.0/10
14. [Huawei Launches Atlas 350 with Ascend 950PR, Claiming 2.87x H20 Performance](#item-14) ⭐️ 7.0/10
15. [China Proposes Deactivating Inactive Accounts After 6 Months](#item-15) ⭐️ 7.0/10
16. [Huawei Mate 80 Pro Gaming Efficiency Beats Snapdragon 8 Gen3 via HarmonyOS Optimization](#item-16) ⭐️ 7.0/10
17. [Private Spacecraft Launched to Rescue NASA's Swift Telescope from Orbital Decay](#item-17) ⭐️ 7.0/10
18. [Converting Code to Images and OCR Exploits LLM Token Loophole, Claiming 60% Cost Cut](#item-18) ⭐️ 6.0/10
19. [Fable's Judgment: Using AI for Efficient Testing and Model Selection](#item-19) ⭐️ 6.0/10
20. [Simon Willison experiments with DSPy to improve Datasette Agent's SQL prompts](#item-20) ⭐️ 6.0/10
21. [PyMuPDF 1.28 Adds Native Markdown Support for PDF Generation](#item-21) ⭐️ 6.0/10
22. [OPPO Unifies OnePlus and realme Under ColorOS Worldwide](#item-22) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Sam Altman Offers U.S. Government 5% Stake in OpenAI](https://aiweekly.co/issues/altman-offered-washington-5-of-openai-and-5-of-everybody) ⭐️ 9.0/10

Sam Altman proposed that OpenAI and possibly other AI companies give the U.S. government a 5% ownership stake, representing a shift from external oversight to direct government participation in frontier AI development. This move could set a precedent for government co-ownership in private AI firms, potentially reshaping AI governance, fostering public-private alignment, and influencing how frontier AI models are governed and deployed. The offer extends to other AI firms; the pattern of exchange—like Fable 5’s return tied to oversight concessions—illustrates the government’s evolving role from distant observer to embedded participant.

rss · AI Weekly · Jul 2, 00:00

**Background**: Frontier AI refers to the most advanced general-purpose AI systems, typically large language models like GPT, that represent the cutting edge of development and require significant resources. Government involvement in AI has traditionally been through regulation and external oversight, but direct ownership stakes represent a new level of engagement, potentially aligning economic interests with safety and ethical considerations.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Frontier_AI">Frontier AI</a></li>
<li><a href="https://www.nvidia.com/en-us/glossary/frontier-models/">What Are Frontier AI Models and How They Work | NVIDIA Glossary</a></li>

</ul>
</details>

**Tags**: `#AI governance`, `#OpenAI`, `#Sam Altman`, `#regulation`, `#politics`

---

<a id="item-2"></a>
## [Jamesob's guide to running SOTA LLMs locally](https://github.com/jamesob/local-llm) ⭐️ 8.0/10

Jamesob has published a practical guide detailing how to set up and run state-of-the-art large language models on personal hardware, with specific build recommendations and hardware requirements. The guide addresses the growing interest in self-hosting LLMs for privacy, cost control, and offline use, while the community discussion realistically highlights trade-offs in cost and security. The guide suggests setups like 2x RTX 3090s with 48GB VRAM to run Qwen3.6-27B, while high-end builds exceed $50,000 and rely on quantization; security concerns were raised about isolation methods.

hackernews · livestyle · Jul 3, 15:03 · [Discussion](https://news.ycombinator.com/item?id=48775921)

**Background**: SOTA (State-of-the-Art) models are the highest-performing AI models available. Running LLMs locally means executing them on personal hardware instead of cloud services, requiring significant GPU memory and often quantization to reduce model size. LLMOps tools support the lifecycle management of such models.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/blog/daya-shankar/sota-ai-models">SOTA AI Models: Benchmarks, Metrics & Deployment Guide</a></li>
<li><a href="https://grokipedia.com/page/Running_large_language_models_locally">Running large language models locally</a></li>
<li><a href="https://www.truefoundry.com/blog/llmops-tools">10 Best LLMOps Tools in 2026</a></li>

</ul>
</details>

**Discussion**: Comments caution about high costs, with one user noting a $40K+ build and others mentioning cloud alternatives; there is optimism for future local Opus-level models but concerns about security isolation, with suggestions to use VMs for trust.

**Tags**: `#local-llm`, `#gpu`, `#self-hosting`, `#llm-ops`, `#hardware`

---

<a id="item-3"></a>
## [Valve Open-Sources Steam Machine E-Ink Display for DIY Builds](https://www.gamingonlinux.com/2026/07/valve-open-source-the-steam-machine-e-ink-screen-so-you-can-make-your-own/) ⭐️ 8.0/10

Valve has released the hardware design and source code for the Steam Machine's front-facing e-ink display, enabling users to build their own using readily available components. This move empowers the maker community to customize and create third-party accessories, fosters goodwill, and sets a positive example for open-source hardware in consumer electronics. The display is a standard Adafruit 5.83" e-ink panel, and the open-source package includes schematics, CAD files, and firmware code, allowing integration with standard microcontrollers.

hackernews · ahlCVA · Jul 3, 13:01 · [Discussion](https://news.ycombinator.com/item?id=48774518)

**Background**: Steam Machines are Valve's line of gaming PCs designed for living-room use, running SteamOS. Initially launched in 2015 and later discontinued, they were revived with a new model on June 29, 2026. The front e-ink panel displays system stats or notifications. E-ink technology uses low-power, paper-like displays, ideal for static information.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Steam_Machine_(Valve)">Steam Machine (Valve)</a></li>
<li><a href="https://en.wikipedia.org/wiki/E_Ink">E Ink - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Comments are enthusiastic, praising Valve's openness. Members noted the panel is an off-the-shelf Adafruit model, facilitating DIY projects. Some expressed desire for guides for other form factors like the Framework Desktop, and there is curiosity about the business impact of such goodwill.

**Tags**: `#open-source hardware`, `#Valve`, `#Steam Machine`, `#e-ink`, `#community engagement`

---

<a id="item-4"></a>
## [Wordgard: New Rich-Text Editor by ProseMirror Creator](https://wordgard.net/) ⭐️ 8.0/10

Wordgard is a new in-browser rich-text editor built by the creator of ProseMirror, offering a modern architecture and addressing limitations of its predecessor. Since ProseMirror underpins many popular editors like Tiptap and Obsidian, a new editor from the same creator could influence the ecosystem and set new standards for web text editing. Wordgard uses a block-based approach with operational transforms, but there is no direct upgrade path from ProseMirror, and migrating requires significant work despite shared concepts.

hackernews · indy · Jul 3, 08:50 · [Discussion](https://news.ycombinator.com/item?id=48772573)

**Background**: ProseMirror is a widely used JavaScript framework for building rich-text editors, known for its modularity and performance but criticized for its complexity. Its creator, Marijn Haverbeke, has now developed Wordgard as a successor with a different design philosophy. ProseMirror powers many editors, including Tiptap and the Obsidian note-taking app.

<details><summary>References</summary>
<ul>
<li><a href="https://prosemirror.net/">ProseMirror</a></li>

</ul>
</details>

**Discussion**: Community reactions are largely positive, with curiosity about the motivations behind the new editor. Developers appreciate the design and are intrigued by its block-based architecture and local-first approach. However, concerns exist about the lack of a migration path from ProseMirror, and some note the absence of a standard web editing component as a long-standing issue.

**Tags**: `#rich-text-editor`, `#prosemirror`, `#javascript`, `#web-development`, `#tools`

---

<a id="item-5"></a>
## [Half-Baked Product: A Critique of Startup Culture](https://weli.dev/blog/half-baked-product/) ⭐️ 8.0/10

A blog post titled 'Half-Baked Product' uses a fictional oven startup story to expose common startup culture failings, including founders motivated by wealth rather than domain expertise and unrealistic equity offers. The piece resonates with the tech community by highlighting persistent issues like founder-market fit mismatch and communication breakdowns between roles, prompting reflection on healthier startup practices. Notable details from the discussion include the engineer being offered 5% equity, which commenters note is unrealistic compared to typical 0.5% Incentive Stock Options (ISOs); the founder's primary motivation was personal wealth.

hackernews · weli · Jul 3, 08:23 · [Discussion](https://news.ycombinator.com/item?id=48772388)

**Background**: Startup culture often celebrates rapid growth and fundraising, but can lead to misaligned incentives. Founders without domain expertise may misunderstand technical constraints, while engineers might be unaware of business realities. Equity offers like Incentive Stock Options (ISOs) are common, but terms can be unfavorable. The 'fake it till you make it' mentality can cause communication gaps between founders, engineers, and salespeople.

**Discussion**: Commenters broadly agree with the critique, highlighting that founder wealth motivation causes repeated failures across sectors. Several note the unrealistic equity offer (5% vs typical 0.5% ISOs) and point to fundamental disconnects between founders, engineers, and salespeople as the root problem. Some express relief not working in such environments, while one notes the story could have been written decades ago.

**Tags**: `#startup`, `#culture`, `#engineering`, `#commentary`, `#entrepreneurship`

---

<a id="item-6"></a>
## [HAT-4D Generates 4D Interactive Scenes Directly from Monocular Video](https://mp.weixin.qq.com/s?__biz=MzIzNjc1NzUzMw==&mid=2247901356&idx=3&sn=54ee94026f76691a380cd3ea214e0def) ⭐️ 8.0/10

Shanghai Jiao Tong University and collaborators proposed HAT-4D, a new agentic framework that reconstructs 3D geometry, temporal dynamics, and multi-object interactions directly from a single monocular video, without needing expensive motion capture equipment. This breakthrough dramatically lowers the cost and complexity of creating dynamic 4D content, enabling wider access for research and applications in VR, gaming, and robotics, and potentially replacing multi-million-dollar motion capture studios. HAT-4D is the first agentic framework for monocular 4D reconstruction, utilizing human-agent collaboration to infer physical interactions and motion from a single viewpoint, and it does not require multi-view setups or depth sensors.

rss · 量子位 · Jul 3, 03:43

**Background**: 4D reconstruction captures the 3D shape and appearance of objects over time to create dynamic scenes. Traditional methods rely on marker-based motion capture in controlled studios with multiple cameras, which is costly and restricted to specific environments. Monocular 4D reconstruction from ordinary videos is challenging because a single viewpoint provides incomplete information, making it difficult to resolve depth, occlusions, and complex interactions.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2606.28215v1">[2606.28215v1] HAT-4D: Lifting Monocular Video for 4D Multi-Object Interactions via Human-Agent Collaboration</a></li>
<li><a href="https://en.wikipedia.org/wiki/4D_reconstruction">4D reconstruction - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#computer vision`, `#4D reconstruction`, `#monocular video`, `#HAT-4D`, `#Shanghai Jiao Tong University`

---

<a id="item-7"></a>
## [Contrastive Decoding Diffing Recovers Finetuning Data from Logits](https://www.reddit.com/r/MachineLearning/comments/1umn2dk/contrastive_decoding_diffing_cdd_recovering/) ⭐️ 8.0/10

Researchers introduce Contrastive Decoding Diffing (CDD), a method that recovers verbatim finetuning data from LLMs using only logit differences between base and finetuned models, without any weight access. It achieves near-perfect verbatim recovery on narrow finetuning benchmarks, outperforming whitebox activation-based methods. CDD exposes a severe privacy risk: even without internal access, attackers can extract sensitive finetuning data by simply comparing logit outputs. This demonstrates that narrow finetuning can leave clearly readable traces in model outputs, which is critical for LLM deployment in privacy-sensitive domains. A single default configuration across models achieves a verbatim recovery score of 4+/5 on 19/20 organism×model pairs. Notably, the method accidentally uncovered that synthetic training data from Claude Sonnet 3.6 repeatedly injects the fictional name 'Dr. Elena Rodriguez' into finetuned models, which CDD then extracts verbatim.

reddit · r/MachineLearning · /u/CebulkaZapiekana · Jul 3, 19:01

**Background**: Contrastive decoding normally improves text generation by searching for strings that maximize a weighted likelihood difference between a strong and a weak model. In CDD, the base and finetuned models serve as the two contrastive pairs, making tokens that were over-learned during finetuning more likely to surface. This differs from previous whitebox methods like the Activation Difference Lens (ADL) that required full weight access and only produced vague domain descriptions.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2309.09117">[2309.09117] Contrastive Decoding Improves Reasoning in Large Language Models</a></li>
<li><a href="https://arxiv.org/abs/2210.15097">[2210.15097] Contrastive Decoding: Open-ended Text Generation as Optimization</a></li>

</ul>
</details>

**Tags**: `#Machine Learning`, `#LLM`, `#Model Inversion`, `#Privacy`, `#Contrastive Decoding`

---

<a id="item-8"></a>
## [Tencent's Atuanyin AI Outperforms Mythos on CyberGym Benchmark at Minimal Cost](https://mp.weixin.qq.com/s/BzU7g-2iG7d6h4ViwMhxyg) ⭐️ 8.0/10

Tencent's Xuanwu Lab announced that their Atuanyin AI, built on the open-source GLM-5.1 model, scored 84% on the CyberGym benchmark, surpassing Anthropic's Claude Mythos Preview. It also discovered high-severity vulnerabilities missed by Mythos in projects like curl and OpenSSL, while costing less than 0.1% of Mythos's 'Glass Wings' budget. This breakthrough shows that open-source AI can achieve state-of-the-art vulnerability discovery at a fraction of the cost, potentially democratizing cybersecurity and challenging the dominance of proprietary systems from companies like Anthropic. Atuanyin AI ranked 1st in severity and 5th in total count on the BVI real-world vulnerability leaderboard. The GLM-5.1 model is known for its ability to work autonomously for over 8 hours on complex tasks, significantly enhancing its code analysis capabilities.

telegram · zaihuapd · Jul 3, 16:12

**Background**: CyberGym is a large-scale benchmark from UC Berkeley that evaluates AI agents on end-to-end cybersecurity tasks using real-world vulnerabilities from 139 open-source projects. GLM-5.1 is an open-source flagship model from Zhipu AI, designed for long-duration autonomous tasks with strong coding abilities. Previously, advanced AI cybersecurity tools often required massive budgets, making this cost efficiency particularly noteworthy.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cybergym.io/cybergym-e2e/">CyberGym-E2E: Scalable Real-World Benchmark for AI Agents' End-to-End Cybersecurity Capabilities</a></li>
<li><a href="https://zhuanlan.zhihu.com/p/2025165819143812557">GLM-5.1开源：一个独立工作8小时的模型 - 知乎</a></li>

</ul>
</details>

**Tags**: `#cybersecurity`, `#AI`, `#vulnerability-discovery`, `#Tencent`, `#benchmark`

---

<a id="item-9"></a>
## [Ubicloud Advocates Strict Memory Overcommit for PostgreSQL to Avoid OOM Killer](https://www.ubicloud.com/blog/postgresql-and-the-oom-killer-why-we-use-strict-memory-overcommit) ⭐️ 7.0/10

Ubicloud's blog post explains why they configure Linux's memory overcommit to strict mode to prevent the OOM killer from disrupting PostgreSQL, sparking debate about the correctness of this approach and highlighting alternatives like OOM score adjustment. PostgreSQL databases are critical to many applications, and unexpected termination by the OOM killer can cause data corruption and downtime; this discussion highlights the trade-offs in Linux memory management for database reliability. The article's description of heuristic overcommit (mode 0) is outdated; modern kernels simply reject single allocations exceeding physical memory. Strict mode (mode 2) can cause fork failures if overcommit ratios are already tuned, and OOM score adjustment is considered a more precise method.

hackernews · furkansahin · Jul 3, 13:00 · [Discussion](https://news.ycombinator.com/item?id=48774509)

**Background**: Memory overcommit allows Linux to allocate more memory to processes than physically available, relying on the fact that processes often do not use all allocated memory. When memory runs out, the OOM killer terminates a process to free memory. OOM score adjustment lets administrators protect critical processes by lowering their likelihood of being killed. The overcommit policy can be set via vm.overcommit_memory: 0 (heuristic), 1 (always overcommit), or 2 (strict, deny allocations exceeding a threshold).

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/OOM_killer">OOM killer</a></li>
<li><a href="https://en.wikipedia.org/wiki/Memory_overcommitment">Memory overcommitment</a></li>
<li><a href="https://www.baeldung.com/linux/memory-overcommitment-oom-killer">Linux Memory Overcommitment and the OOM Killer | Baeldung on Linux</a></li>

</ul>
</details>

**Discussion**: Commenters note that the article misrepresents heuristic mode and that OOM score adjustment is a more precise modern solution. Some criticize Linux's default VM behavior, while the Ubicloud author admits strict overcommit may not suit all scenarios. Caution is advised for mode 2 when overcommit ratios are already tweaked, as it can block forks.

**Tags**: `#PostgreSQL`, `#OOM killer`, `#memory overcommit`, `#Linux`, `#database operations`

---

<a id="item-10"></a>
## [Understand to Participate: Avoid Cognitive Debt with AI Agents](https://simonwillison.net/2026/Jul/2/understand-to-participate/#atom-everything) ⭐️ 7.0/10

Simon Willison shared Geoffrey Litt's concept of 'understand to participate' from his talk at the AI Engineer World's Fair 2026, emphasizing the need to deeply comprehend AI-generated code to avoid cognitive debt and remain an active collaborator. As AI coding agents become more capable, this idea warns that without deep understanding, developers risk losing the ability to meaningfully contribute to their projects, potentially harming long-term software health and team collaboration. The talk was recorded at AIE 2026 and will be released on YouTube over three weeks; Geoffrey also published a summary thread on Twitter.

rss · Simon Willison · Jul 2, 17:07

**Background**: Cognitive debt is the erosion of shared mental models and understanding of a codebase when AI generates code faster than developers can grasp it. AI coding agents are tools that autonomously write, modify, and coordinate code, sometimes operating in specialized agent teams. The 'understand to participate' concept stresses that developers must maintain fluency in the code's design and purpose to stay creative participants, rather than passive reviewers of AI output.

<details><summary>References</summary>
<ul>
<li><a href="https://margaretstorey.com/blog/2026/02/09/cognitive-debt/">How Generative and Agentic AI Shift Concern from Technical Debt to Cognitive Debt</a></li>
<li><a href="https://getdx.com/blog/cognitive-debt-the-hidden-risk-in-ai-driven-software-development/">Cognitive debt: The hidden risk in AI-driven software development</a></li>

</ul>
</details>

**Tags**: `#cognitive debt`, `#AI collaboration`, `#coding agents`, `#software development`

---

<a id="item-11"></a>
## [Hamiltonian Neural Networks from a Differential Geometry Perspective](https://www.reddit.com/r/MachineLearning/comments/1ukzdnj/hamiltonian_neural_networks_from_a_differential/) ⭐️ 7.0/10

A blog post presents Hamiltonian Neural Networks (HNNs) through the lens of differential geometry, emphasizing how Noether's theorem connects symmetries to conservation laws and generalization in physics-informed machine learning. This perspective provides deeper theoretical insight into why HNNs are effective, potentially guiding the design of more robust physics-informed models and underscoring the importance of symmetries in machine learning. The blog post is mathematically intensive, featuring interactive visualizations to make differential geometry concepts accessible, and directly builds on the foundational HNN paper by Greydanus et al. (2019).

reddit · r/MachineLearning · /u/FlameOfIgnis · Jul 1, 21:55

**Background**: Hamiltonian Neural Networks (HNNs) are a class of physics-informed neural networks introduced in 2019 that learn Hamiltonian dynamics to enforce energy conservation. Noether's theorem, a fundamental result in theoretical physics, establishes that every continuous symmetry of a physical system corresponds to a conservation law. Differential geometry provides the mathematical framework for describing smooth manifolds and geometric structures, often used to formulate physical laws in a coordinate-independent way.

<details><summary>References</summary>
<ul>
<li><a href="https://greydanus.github.io/2019/05/15/hamiltonian-nns/">Hamiltonian Neural Networks</a></li>
<li><a href="https://en.wikipedia.org/wiki/Noether's_theorem">Noether's theorem</a></li>
<li><a href="https://en.wikipedia.org/wiki/Differential_geometry">Differential geometry</a></li>

</ul>
</details>

**Tags**: `#machine learning`, `#physics-informed neural networks`, `#Hamiltonian neural networks`, `#differential geometry`, `#Noether's theorem`

---

<a id="item-12"></a>
## [Gemini Omni Flash Tops Video Arena with 101-Point Lead](https://x.com/Designarena/status/2072759122366509130) ⭐️ 7.0/10

Google DeepMind's Gemini Omni Flash scored 1404 points on the Video Arena blind test, taking first place with a 101-point lead over ByteDance's Seedance 2.0 Mini. This demonstrates a clear leap in AI video generation quality, re-establishing Google as a leader in the field and potentially shaping developer and enterprise adoption for video creation tasks. The ranking is derived from blind user votes comparing two anonymous videos. Google's video model ranking improved by 7 positions compared to its previous Veo series.

telegram · zaihuapd · Jul 3, 05:51

**Background**: Video Arena, run by Artificial Analysis, ranks AI video models through blind user preference tests. Gemini Omni Flash is a multimodal model that can generate video from text, images, and video inputs. Seedance 2.0 Mini is a video generation model from ByteDance that previously held top positions on the leaderboard.

<details><summary>References</summary>
<ul>
<li><a href="https://happyhorsemodel.ai/en/articles/ai-video-model-arena-explained">Artificial Analysis Video Arena: How Models Are Ranked and How It Works | HappyHorse Model</a></li>
<li><a href="https://deepmind.google/models/gemini-omni/">Gemini Omni — Google DeepMind</a></li>
<li><a href="https://seedance2.ai/">Seedance 2 . 0</a></li>

</ul>
</details>

**Tags**: `#video-generation`, `#benchmarks`, `#Gemini`, `#Google-DeepMind`, `#AI-models`

---

<a id="item-13"></a>
## [Claude Fable 5 Relaunch Draws User Criticism Over Safety Over-Filtering](https://www.bleepingcomputer.com/news/artificial-intelligence/claude-fable-relaunch-disappoints-users-with-nerfed-performance/) ⭐️ 7.0/10

After lifting export controls, Anthropic relaunched Claude Fable 5, but users report a degraded experience due to aggressive safety filters that mistakenly downgrade legitimate code, and new subscription restrictions that limit model access. This is significant for AI developers because overly strict safety filtering disrupts critical coding workflows, and the subscription model changes raise concerns about the reliability and cost of accessing cutting-edge AI models. The safety system downgrades tasks involving low-level languages like C/C++ or Rust, or keywords such as “vulnerability” and “hook,” to the less capable Opus 4.8, even though the underlying model’s performance remains state-of-the-art. API and pay-as-you-go enterprise users are unaffected by the subscription limits.

telegram · zaihuapd · Jul 3, 07:20

**Background**: Claude Fable 5 is a large language model developed by Anthropic, recognized for its state-of-the-art performance in software engineering and coding. It is the publicly available version of the more security-focused Claude Mythos. Opus 4.8 is a previous-generation model with lower capabilities. The initial release was limited by U.S. export controls, which have now been lifted.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_Fable_5">Claude Fable 5</a></li>
<li><a href="https://www.anthropic.com/news/claude-opus-4-8">Introducing Claude Opus 4.8 \ Anthropic</a></li>
<li><a href="https://www.reddit.com/r/ClaudeAI/comments/1u1b22l/introducing_claude_fable_5/">Introducing Claude Fable 5 : r/ClaudeAI - Reddit</a></li>

</ul>
</details>

**Tags**: `#AI safety`, `#large language models`, `#developer tools`, `#API management`, `#Anthropic`

---

<a id="item-14"></a>
## [Huawei Launches Atlas 350 with Ascend 950PR, Claiming 2.87x H20 Performance](https://t.me/zaihuapd/42329) ⭐️ 7.0/10

Huawei officially released the Atlas 350 AI accelerator card featuring the new Ascend 950PR processor, supporting FP4 low-precision inference with 112 GB HBM and delivering nearly three times the performance of NVIDIA's H20. This launch signals a major leap in China's domestic AI hardware, directly challenging NVIDIA's inference dominance and potentially reducing reliance on foreign GPUs for large-scale AI workloads. The card achieves 1.56 PFLOPS FP4, uses Huawei's self-developed HiBL 1.0 HBM, consumes 600W, and enables single-card loading of 70-billion-parameter models, significantly cutting inference latency and cost.

telegram · zaihuapd · Jul 3, 08:35

**Background**: The Atlas 350 is an AI accelerator card for data centers, built on Huawei's Ascend processor architecture. FP4 (4-bit floating-point) is an ultra-low precision data format that dramatically boosts inference throughput and energy efficiency while preserving near-identical model accuracy, as demonstrated by NVIDIA's NVFP4 format. High-Bandwidth Memory (HBM) provides extreme memory bandwidth needed for large models. The H20 is a China-specific GPU from NVIDIA with reduced interconnect speeds to comply with US export rules.

<details><summary>References</summary>
<ul>
<li><a href="https://awesomeagents.ai/hardware/huawei-atlas-350/">Huawei Atlas 350 - China's FP4 Inference... | Awesome Agents</a></li>
<li><a href="https://www.digitimes.com/news/a20260324PD210/huawei-ascend-performance-2026.html">Huawei's Ascend 950 PR debuts with nearly 3x H20 performance...</a></li>

</ul>
</details>

**Tags**: `#AI accelerators`, `#Huawei`, `#Ascend processor`, `#hardware announcement`, `#HBM`

---

<a id="item-15"></a>
## [China Proposes Deactivating Inactive Accounts After 6 Months](https://mp.weixin.qq.com/s/TfYZaC8ULPvu9JeTqYGkKg) ⭐️ 7.0/10

A revised Chinese draft regulation proposes that internet platforms can deactivate or freeze accounts that have been inactive for more than six months, while also mandating the labeling of AI-generated content and banning fake engagement practices. This signals a tightening of internet governance in China, aiming to protect user data, prevent account squatting, and combat misinformation and manipulation in the digital ecosystem. The draft specifies that platforms must support unbinding a phone number when it is reassigned to a new user, and large platforms are required to handle complaints about illegal content within 24 hours. It also mandates that platforms cannot force users into intelligent information services and must offer an option to disable personalized recommendations.

telegram · zaihuapd · Jul 3, 11:29

**Background**: The "Internet Information Service Management Measures" is a foundational regulation for China's internet industry, originally enacted in 2000 and last revised in 2011. This new revision comes as technologies like AI-generated content and practices like fake engagement have become widespread, prompting the need for updated rules. The public consultation, with a deadline of August 2, 2026, reflects the ongoing evolution of China's cyber governance framework.

**Tags**: `#internet regulation`, `#china tech policy`, `#AI regulation`, `#account management`, `#content moderation`

---

<a id="item-16"></a>
## [Huawei Mate 80 Pro Gaming Efficiency Beats Snapdragon 8 Gen3 via HarmonyOS Optimization](https://www.bilibili.com/video/BV1F7T46wEyT) ⭐️ 7.0/10

Geekerwan's review reveals the Huawei Mate 80 Pro series, powered by the new Kirin 9030 chips, achieves superior gaming power efficiency compared to Snapdragon 8 Gen3. This is achieved through native HarmonyOS optimization despite theoretical hardware disadvantages. This demonstrates that tight software-hardware integration can overcome theoretical hardware gaps, suggesting that ecosystem optimization may become a key differentiator in mobile gaming performance and reinforcing Huawei's platform advantage. The Mate 80 Pro Max runs Genshin Impact at 60fps extreme quality with only 4.9W total power, while Honor of Kings at 120fps consumes about 3W. The Kirin 9030 Pro features a 9-core 14-thread CPU and a 6-core Maleoon 935 GPU, with CPU multi-core efficiency between Snapdragon 8 Gen2 and Gen3.

telegram · zaihuapd · Jul 3, 13:27

**Background**: The Kirin 9030 series is Huawei's latest proprietary chipset, featuring in-house CPU and GPU designs including the Maleoon 935 GPU, built under process constraints. HarmonyOS is Huawei's operating system that enables deep integration between apps and hardware. Snapdragon 8 Gen3 is Qualcomm's flagship mobile platform, typically fabricated on advanced 4nm process, known for high performance and efficiency. The Maleoon GPU line has previously shown that architectural advantages can partly offset process node gaps.

<details><summary>References</summary>
<ul>
<li><a href="https://www.zhihu.com/question/619682541">如何评价麒麟9000S芯片自带的maloon 910GPU？ - 知乎</a></li>
<li><a href="https://www.ccf.org.cn/Media_list/cncc/2022-10-20/775524.shtml">CNCC｜软硬一体化协同设计加速多领域技术进步-中国计算机学会</a></li>

</ul>
</details>

**Tags**: `#mobile`, `#gaming`, `#performance`, `#optimization`, `#hardware`

---

<a id="item-17"></a>
## [Private Spacecraft Launched to Rescue NASA's Swift Telescope from Orbital Decay](https://apnews.com/article/swift-nasa-satellite-rescue-katalyst-a7ddd740ca099587c58865f583c7245a) ⭐️ 7.0/10

On July 3, NASA launched the privately-built LINK spacecraft to rendezvous with the Swift space telescope and boost it to a safer orbit using a robotic arm and thrusters. This is the first commercial spacecraft to attempt grabbing and reboosting a U.S. government satellite, demonstrating the growing role of private companies in orbital servicing and rescue. LINK will grapple Swift with a robotic arm and slowly raise its orbit by about 240 km; if successful, Swift could resume observations by September, avoiding a fiery reentry as soon as October due to heightened solar activity dragging its orbit down.

telegram · zaihuapd · Jul 3, 15:43

**Background**: Swift, launched in 2004, is a NASA-led space telescope that studies gamma-ray bursts from low Earth orbit, where atmospheric drag causes gradual orbital decay. The current solar cycle has increased atmospheric density, accelerating this decay. Orbital rescue missions are rare and typically government-led, making this commercial venture a pioneering case of extending a scientific satellite's life.

<details><summary>References</summary>
<ul>
<li><a href="https://www.bbc.co.uk/news/articles/c0ry4xx7rk8o">Nasa launches robot to save Swift telescope falling to Earth - BBC News</a></li>

</ul>
</details>

**Tags**: `#space`, `#satellite-rescue`, `#NASA`, `#private-spacecraft`, `#technology`

---

<a id="item-18"></a>
## [Converting Code to Images and OCR Exploits LLM Token Loophole, Claiming 60% Cost Cut](https://github.com/teamchong/pxpipe) ⭐️ 6.0/10

A new method shared on GitHub converts code into images and then uses the LLM's built-in OCR to process it, exploiting disparities in token pricing between text and image inputs to reportedly cut costs by 60%. This hack exposes ambiguities in per-token billing for LLMs and could prompt providers to adjust pricing or close loopholes, while also raising questions about real-world cost-effectiveness and potential resource waste. Past attempts using similar image-to-text workarounds with OpenAI models resulted in higher total cost and slower performance due to increased completion tokens, suggesting that net savings are not guaranteed.

hackernews · dimitropoulos · Jul 3, 15:50 · [Discussion](https://news.ycombinator.com/item?id=48776464)

**Background**: Large language model providers charge per token at different rates for text and image inputs. Some models internally OCR images and may not separately charge for the extracted text tokens, creating a loophole that this method exploits. The effectiveness of such a hack depends on the provider's implementation and is likely temporary as vendors close these pricing gaps.

<details><summary>References</summary>
<ul>
<li><a href="https://aimuse.blog/article/2025/06/14/llm-billing-exposed-how-tokenization-obscures-true-costs-and-what-to-do-about-it">LLM Billing Exposed: How Tokenization Obscures True Costs ...</a></li>
<li><a href="https://sider.ai/blog/ai-tools/why-deepseek-ocr-s-text-as-image-approach-cuts-token-costs-by-up-to-10">Why DeepSeek‑OCR’s “Text as Image” Approach Cuts Token Costs by Up to 10×</a></li>

</ul>
</details>

**Discussion**: Comments suggest this is a temporary loophole, with some noting that similar attempts with OpenAI were ultimately more expensive due to higher completion token usage. Others warned of wasted resources and possible OCR price hikes when the loophole is closed, and one comment poked fun at the project's auto-generated README.

**Tags**: `#LLMs`, `#cost optimization`, `#OCR`, `#token pricing`, `#hack`

---

<a id="item-19"></a>
## [Fable's Judgment: Using AI for Efficient Testing and Model Selection](https://simonwillison.net/2026/Jul/3/judgement/#atom-everything) ⭐️ 6.0/10

Tips from Anthropic's Claude Code team suggest letting AI models like Fable use their own judgment to decide when to write tests and which model to use for tasks, reducing costs and improving efficiency. This approach can significantly reduce token usage for expensive models like Fable by delegating simpler coding tasks to cheaper sub-models, while maintaining code quality and accelerating development. A specific prompt instructed Claude to 'use your judgement to decide an appropriate lower power model and run that in a subagent' for coding tasks, resulting in automated delegation to models like Sonnet or Haiku while keeping judgment-heavy tasks in the main model.

rss · Simon Willison · Jul 3, 18:51

**Background**: Claude is Anthropic's series of large language models with tiers: Haiku (fast/cheap), Sonnet (balanced), and Opus (most intelligent). Fable is a state-of-the-art model with advanced coding capabilities. Claude Code is an AI-assisted development tool that can use these models and spawn subagents. Developers often face high costs with top-tier models, so delegating to smaller models for simple tasks is a cost-saving technique.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/claude/fable">Claude Fable \ Anthropic</a></li>
<li><a href="https://www.anthropic.com/claude/opus">Claude Opus \ Anthropic</a></li>
<li><a href="https://en.wikipedia.org/wiki/Claude_(language_model)">Claude (AI) - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Prompt Engineering`, `#Software Development`, `#Claude`, `#Cost Optimization`

---

<a id="item-20"></a>
## [Simon Willison experiments with DSPy to improve Datasette Agent's SQL prompts](https://simonwillison.net/2026/Jul/2/dspy-datasette-agent-prompts/#atom-everything) ⭐️ 6.0/10

He used DSPy with GPT 4.1 mini and nano to evaluate and propose improvements to Datasette Agent's system prompts, identifying issues like missing column names causing error loops. This shows practical application of automated prompt engineering for SQL agents, potentially improving reliability and efficiency of AI-driven data tools. The experiment uncovered that the schema listing only gave table names, causing the model to guess column names (e.g., page_count, o.order_id) and resulting in error-retry loops in baseline traces.

rss · Simon Willison · Jul 2, 18:25

**Background**: DSPy is a Stanford NLP framework for declarative language model programming, replacing manual prompting. Datasette Agent allows querying databases via natural language, using system prompts to guide SQL generation. This experiment aims to optimize those prompts.

<details><summary>References</summary>
<ul>
<li><a href="https://grokipedia.com/page/DSPy">DSPy</a></li>

</ul>
</details>

**Tags**: `#DSPy`, `#Datasette`, `#Prompt Engineering`, `#SQL Agent`, `#LLM Optimization`

---

<a id="item-21"></a>
## [PyMuPDF 1.28 Adds Native Markdown Support for PDF Generation](https://www.reddit.com/r/MachineLearning/comments/1ukyciw/new_pymupdf_release_supports_markdown_n/) ⭐️ 6.0/10

PyMuPDF version 1.28 introduces Markdown as a first-class document type, allowing users to create PDFs directly from Markdown text with CSS styling. This feature streamlines document workflows by enabling programmatic PDF generation from Markdown, reducing reliance on external converters and enhancing consistency in automated report generation. The release treats Markdown as a native document format within PyMuPDF, meaning it can be manipulated like other supported formats, and CSS styling provides control over output appearance.

reddit · r/MachineLearning · /u/Remote-Spirit526 · Jul 1, 21:15

**Background**: PyMuPDF is a high-performance Python library for working with PDF and other document formats. Previously, converting Markdown to PDF often required separate tools like Pandoc or manual rendering with other libraries. With native support, PyMuPDF simplifies the pipeline for Python developers who need to produce styled PDFs from Markdown content.

<details><summary>References</summary>
<ul>
<li><a href="https://grokipedia.com/page/PyMuPDF">PyMuPDF</a></li>

</ul>
</details>

**Tags**: `#PyMuPDF`, `#PDF`, `#Markdown`, `#DocumentProcessing`, `#MachineLearning`

---

<a id="item-22"></a>
## [OPPO Unifies OnePlus and realme Under ColorOS Worldwide](https://www.donews.com/news/detail/8/6620374.html) ⭐️ 6.0/10

In July 2026, OPPO announced that it will cease development of OnePlus’s OxygenOS and realme UI, with all new global devices from these brands running ColorOS instead. The consolidation includes integration of after-sales services and strategic market adjustments, such as realme withdrawing from China. This move streamlines software R&D across OPPO’s sub-brands, potentially leading to faster updates and a more consistent user experience. It also signals a major realignment of brand strategies in key markets like China and India. OnePlus will now focus on China and India with its after-sales integrated into OPPO; realme will exit the Chinese market to concentrate on overseas sales. As part of the transition, realme’s service accounts migrated to OPPO on July 1, 2026, and its online store closed on April 25, 2026.

telegram · zaihuapd · Jul 3, 10:45

**Background**: OxygenOS was OnePlus’s custom Android skin for international models, known for its close-to-stock experience, while HydrogenOS served the Chinese market. In 2020, realme UI replaced ColorOS on realme phones but remained heavily based on it. Since the OnePlus 9 series, OnePlus phones in China have already used ColorOS, so this global unification extends an existing trend.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/OxygenOS">OxygenOS</a></li>
<li><a href="https://en.wikipedia.org/wiki/Realme_UI">Realme UI</a></li>
<li><a href="https://en.wikipedia.org/wiki/ColorOS">ColorOS</a></li>

</ul>
</details>

**Tags**: `#Android`, `#ColorOS`, `#OPPO`, `#Mobile OS`, `#Business`

---