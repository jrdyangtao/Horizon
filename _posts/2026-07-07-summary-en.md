---
layout: default
title: "Horizon Summary: 2026-07-07 (EN)"
date: 2026-07-07
lang: en
---

> From 55 items, 31 important content pieces were selected

---

1. [MIRA: 5B-Param Multiplayer World Model for Rocket League Released with Demo](#item-1) ⭐️ 9.0/10
2. [KVM Januscape: Critical VM Escape Bug Lurked for 16 Years](#item-2) ⭐️ 9.0/10
3. [China Considers Restricting Overseas Access to Top Domestic AI Models](#item-3) ⭐️ 9.0/10
4. [StreetComplete Makes Contributing to OpenStreetMap Easy and Fun](#item-4) ⭐️ 8.0/10
5. [EU's Chat Control 1.0 and 2.0: Impact on Privacy and Encryption](#item-5) ⭐️ 8.0/10
6. [EU Parliament Advances Controversial 'Chat Control' Proposal](#item-6) ⭐️ 8.0/10
7. [Tencent Releases Hy3, a 295B MoE Model, Under Apache 2.0](#item-7) ⭐️ 8.0/10
8. [Sensor-Valid Masking for Depth Completion Sets SOTA; LingBot-Vision Backbone Outperforms DINOv2](#item-8) ⭐️ 8.0/10
9. [LingBot-Vision: Masked Boundary Modeling for Self-Supervised Pretraining](#item-9) ⭐️ 8.0/10
10. [China to Invest $295 Billion Over 5 Years for Nationwide Computing Network](#item-10) ⭐️ 8.0/10
11. [Anthropic Releases Claude Sonnet 5 with Enhanced Agentic Capabilities](#item-11) ⭐️ 8.0/10
12. [sqlite-utils 4.0 Adds Schema Migration, Nested Transactions, and Compound Foreign Keys](#item-12) ⭐️ 7.0/10
13. [MemGUI-Agent: End-to-End Long-Horizon Mobile GUI Agent with Memory](#item-13) ⭐️ 7.0/10
14. [AlphaFold Nobel Winner Joins Anthropic; AI Tutor Beats Classroom](#item-14) ⭐️ 7.0/10
15. [Ph.D. Thesis: Differentiable Ray Tracing for Radio Propagation Modeling](#item-15) ⭐️ 7.0/10
16. [Mozilla CTO to Host AMA on State of Open Source AI Report](#item-16) ⭐️ 7.0/10
17. [TRACE: Open-Source Hierarchical Memory for LLM Agents Hits 82.5% on EventQA](#item-17) ⭐️ 7.0/10
18. [Elon Musk Dissolves xAI, Integrates as SpaceXAI into SpaceX](#item-18) ⭐️ 7.0/10
19. [AI Phone and PC Sales to Surpass Non-AI for First Time in 2025](#item-19) ⭐️ 7.0/10
20. [new-api Fixes Integer Overflow Billing Vulnerability](#item-20) ⭐️ 7.0/10
21. [DeepSeek Developing Own AI Inference Chip to Cut Nvidia, Huawei Dependency](#item-21) ⭐️ 7.0/10
22. [Chinese Web Novel Platforms Reverse AI Embrace, Crack Down on AI-Generated Content](#item-22) ⭐️ 7.0/10
23. [California and New York push for firearm-blocking software in 3D printers](#item-23) ⭐️ 7.0/10
24. [30papers.com: Ilya Sutskever's 30 Essential ML Papers for Beginners](#item-24) ⭐️ 6.0/10
25. [TorchJD Implements Jacobian Descent Methods for Multi-Loss Training in PyTorch](#item-25) ⭐️ 6.0/10
26. [ICML Position Paper Proposes Credit System for Better ML Peer Reviews](#item-26) ⭐️ 6.0/10
27. [Offline ASL Recognition on Raspberry Pi 5 Using MediaPipe and TensorFlow Lite](#item-27) ⭐️ 6.0/10
28. [Google Now Saves Lens and Voice Search for AI Training by Default, Opt-Out Available](#item-28) ⭐️ 6.0/10
29. [Windows 11 Capability Access Manager Bug Consumes Up to 513GB Disk Space](#item-29) ⭐️ 6.0/10
30. [NVIDIA Blackwell Chips Made in US Still Need Taiwan Packaging](#item-30) ⭐️ 6.0/10
31. [Claude Fable 5 Relaunch Faces Backlash Over Safety False Positives](#item-31) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [MIRA: 5B-Param Multiplayer World Model for Rocket League Released with Demo](https://www.reddit.com/r/MachineLearning/comments/1upofuw/mira_multiplayer_interactive_world_models_trained/) ⭐️ 9.0/10

MIRA is a 5-billion-parameter interactive world model that enables real-time 4-player Rocket League gameplay at 20 fps, trained on 10,000 hours of synthetic data. An online demo, technical report, and 1k-hour gameplay dataset are publicly available. It demonstrates the viability of large-scale world models for real-time multiplayer simulation, with potential to transform game development, AI training, and interactive entertainment. The collaboration between industry and academia provides an open platform for multi-agent research. The 5B-parameter model runs on a single NVIDIA B200 GPU and achieves 20 fps for four simultaneous players. Training used synthetic data, and a 1k-hour dataset of 4-player gameplay was released alongside.

reddit · r/MachineLearning · /u/MasterScrat · Jul 7, 07:59

**Background**: World models are AI systems that simulate an environment's dynamics, enabling agents to learn and plan. The NVIDIA B200 is a high-performance GPU based on the Blackwell architecture, designed for demanding AI workloads. Rocket League is a physics-based multiplayer game, making real-time simulation especially challenging.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/World_model_(artificial_intelligence)">World model (artificial intelligence) - Wikipedia</a></li>
<li><a href="https://arxiv.org/abs/1803.10122">[1803.10122] World Models</a></li>
<li><a href="https://en.wikipedia.org/wiki/Nvidia_B200">Nvidia B200</a></li>

</ul>
</details>

**Tags**: `#world models`, `#multiplayer`, `#reinforcement learning`, `#game AI`, `#real-time simulation`

---

<a id="item-2"></a>
## [KVM Januscape: Critical VM Escape Bug Lurked for 16 Years](https://github.com/V4bel/Januscape) ⭐️ 9.0/10

Security researchers disclosed Januscape (CVE-2026-53359), the first KVM/x86 VM escape vulnerability to affect both Intel and AMD platforms, caused by a use-after-free in the shadow MMU. The flaw, present in the Linux kernel since 2010, allows a guest VM to crash or compromise the host kernel, and its proof-of-concept was used as a 0-day in Google's kvmCTF program. This vulnerability breaks the foundational isolation boundary of virtualized environments, potentially enabling attackers in a guest VM to access other guests or the host in multi-tenant clouds. Its 16-year lifespan and cross-platform reach mean millions of KVM-based systems are at risk. The use-after-free occurs in the shadow MMU's handling of shadow pages, allowing a guest to corrupt host kernel memory. The PoC can trigger a host crash, and on distributions like RHEL, a local unprivileged user can escalate to root.

telegram · zaihuapd · Jul 7, 10:14

**Background**: KVM (Kernel-based Virtual Machine) is the Linux kernel's built-in hypervisor. VM escape is a severe attack where code in a guest breaks out to the host. The shadow MMU is a software memory management technique used when hardware lacks nested paging support, employing shadow page tables to map guest memory. kvmCTF is Google's vulnerability reward program focused on KVM security.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.kernel.org/virt/kvm/x86/mmu.html">The x86 kvm shadow mmu — The Linux Kernel documentation</a></li>
<li><a href="https://en.wikipedia.org/wiki/VM_escape">VM escape</a></li>
<li><a href="https://github.com/google/security-research/blob/master/kvmctf/rules.md">security-research/kvmctf/rules.md at master · google/security-research</a></li>

</ul>
</details>

**Tags**: `#KVM`, `#VM escape`, `#Linux kernel`, `#CVE`, `#security vulnerability`

---

<a id="item-3"></a>
## [China Considers Restricting Overseas Access to Top Domestic AI Models](https://www.reuters.com/world/beijing-is-looking-curbing-overseas-access-chinas-top-ai-models-sources-say-2026-07-07/) ⭐️ 9.0/10

According to a Reuters report, China's Ministry of Commerce held meetings with Alibaba, ByteDance, and Zhipu to discuss restricting overseas access to the most advanced domestic AI models, including unreleased ones, and limiting foreign investment in AI startups. If implemented, this policy could significantly disrupt global AI collaboration and access to cutting-edge Chinese models, potentially affecting software engineering and AI development worldwide. The scope of restrictions is still under discussion, may only apply to future new models, and it is uncertain whether the policy will ultimately be enacted.

telegram · zaihuapd · Jul 7, 11:42

**Background**: China has been rapidly advancing in AI, producing models rivaling those from the US. Export controls on technology have been a tool in US-China tensions; China may be reciprocating or protecting its technological edge. The Ministry of Commerce oversees trade and foreign investment regulations.

**Tags**: `#AI policy`, `#export controls`, `#China`, `#AI regulation`, `#global AI`

---

<a id="item-4"></a>
## [StreetComplete Makes Contributing to OpenStreetMap Easy and Fun](https://streetcomplete.app/) ⭐️ 8.0/10

StreetComplete is a mobile app that gamifies and simplifies contributing to OpenStreetMap by allowing users to complete small quests to add or verify map data, making it accessible to beginners. This lowers the barrier to contributing to open map data, which can improve OpenStreetMap's richness and accuracy, and fosters a community-driven mapping ecosystem that challenges proprietary alternatives. The app is open-source and currently focuses on editing attributes of existing map features like shops, crossings, and footpaths, but it does not support adding new roads or paths.

hackernews · kls0e · Jul 7, 12:38 · [Discussion](https://news.ycombinator.com/item?id=48816883)

**Background**: OpenStreetMap (OSM) is a free, editable map of the world built by volunteers. StreetComplete is an Android app that presents users with small, location-based quests, such as verifying shop opening hours or checking for wheelchair accessibility, to make map contributions easy and engaging.

**Discussion**: Community feedback is largely positive, praising the user-friendly interface and gamification. However, some users note limitations like the inability to add new paths, occasional confusion with duplicate data when mapping crossings, and challenges in motivating shop owners to update their own info. There are also concerns about big companies using OSM data without reciprocating.

**Tags**: `#openstreetmap`, `#gis`, `#community`, `#mobile-app`, `#open-data`

---

<a id="item-5"></a>
## [EU's Chat Control 1.0 and 2.0: Impact on Privacy and Encryption](https://fightchatcontrol.eu/chat-control-overview) ⭐️ 8.0/10

The article provides a detailed explanation of the EU's Chat Control 1.0 and 2.0 proposals, covering their legal basis, potential impact on encrypted messaging, and the current state of debate. It highlights that Chat Control 1.0—a temporary derogation from the ePrivacy Directive allowing voluntary scanning—has expired, yet companies continue to scan, while Chat Control 2.0 could mandate client-side scanning for all messages. These proposals threaten end-to-end encryption, potentially turning messaging apps into mass surveillance tools. They could set a global precedent for undermining digital privacy and have sparked intense debate about the balance between child protection and fundamental rights. Chat Control 1.0 was a temporary derogation from the ePrivacy Directive that allowed (but did not require) providers to scan private messages. Chat Control 2.0 proposals include mandatory client-side scanning, which critics argue would break end-to-end encryption, and has been described as a systemic weakening of encryption that could affect all users, not just suspected offenders.

hackernews · gasull · Jul 7, 14:23 · [Discussion](https://news.ycombinator.com/item?id=48818311)

**Background**: The ePrivacy Directive generally prohibits the interception or monitoring of communications without user consent. The EU proposed Chat Control as part of a broader strategy to combat child sexual abuse material online. Chat Control 1.0 introduced a temporary gap in this protection, and Chat Control 2.0 aims to make such scanning permanent and more invasive, raising concerns from privacy advocates, security experts, and law professors about its compatibility with fundamental rights.

<details><summary>References</summary>
<ul>
<li><a href="https://proton.me/blog/eu-parliament-chat-control">EU Parliament made the correct decision on Chat Control today | Proton</a></li>
<li><a href="https://tuta.com/blog/chat-control-criticism">Huge Victory: Chat Control no longer forces us to break... | Tuta</a></li>

</ul>
</details>

**Discussion**: Community comments express deep concern, characterizing the proposal as a dictatorial overreach that uses good intentions to justify mass surveillance. Some question the technical feasibility and legality, while others praise the website for clarifying the issue. There is a shared sentiment that the law is disproportionate and that targeted measures would be more effective.

**Tags**: `#privacy`, `#encryption`, `#surveillance`, `#policy`, `#EU`

---

<a id="item-6"></a>
## [EU Parliament Advances Controversial 'Chat Control' Proposal](https://www.heise.de/en/news/Showdown-in-Strasbourg-The-unexpected-return-of-Chat-Control-1-0-11356680.html) ⭐️ 8.0/10

The EU Parliament has passed the first round of the 'Chat Control' proposal, which would mandate scanning of private communications to combat child sexual abuse. This threatens end-to-end encryption and could set a global precedent, as other countries may replicate such surveillance measures, affecting privacy worldwide. The procedural tactic gives proponents a tactical advantage: only a simple majority of present MEPs is needed for adoption, while amendments require an absolute majority of 361 votes, which is harder to achieve on the last day before summer break.

hackernews · miroljub · Jul 7, 15:16 · [Discussion](https://news.ycombinator.com/item?id=48819008)

**Background**: The EU's 'Chat Control' proposal (Regulation to Prevent and Combat Child Sexual Abuse) was introduced in May 2022. It would require platforms like WhatsApp and Signal to implement client-side scanning, effectively breaking encryption. The proposal has faced strong opposition from digital rights groups, tech companies, and academics who argue it undermines privacy and security.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Regulation_to_Prevent_and_Combat_Child_Sexual_Abuse">Chat Control - Wikipedia</a></li>
<li><a href="https://www.eff.org/deeplinks/2026/04/eu-parliament-blocks-mass-scanning-our-chats-whats-next">EU Parliament Blocks Mass-Scanning of Our Chats—What's Next? | Electronic Frontier Foundation</a></li>
<li><a href="https://fightchatcontrol.eu/">Fight Chat Control - Protect Digital Privacy in the EU</a></li>

</ul>
</details>

**Discussion**: Commenters express outrage over procedural manipulation, with one noting that democracy is undermined when unpopular laws are repeatedly pushed until they pass. There is concern that if the EU adopts this, other countries will follow, leading to global surveillance. Some MEPs voted against, but it's unlikely enough 'no' votes will be found to stop it.

**Tags**: `#privacy`, `#surveillance`, `#eu-legislation`, `#digital-rights`, `#chat-control`

---

<a id="item-7"></a>
## [Tencent Releases Hy3, a 295B MoE Model, Under Apache 2.0](https://simonwillison.net/2026/Jul/6/hy3/#atom-everything) ⭐️ 8.0/10

Tencent's Hy Team released Hy3, a 295-billion-parameter Mixture-of-Experts model with 21 billion active parameters and 3.8 billion multi-token prediction (MTP) layer parameters, under the Apache 2.0 license. It outperforms similar-sized models and rivals much larger open-source models after scaling post-training with higher-quality data. This release provides the community with a highly capable, freely available MoE model that rivals much larger models, potentially lowering the barrier to advanced AI capabilities for developers. It also demonstrates China's growing open-source AI contributions. The model supports a 256K context length, with the full version weighing 598GB and an FP8 quantized variant at 300GB; it is available for free on OpenRouter until July 21, 2026.

rss · Simon Willison · Jul 6, 23:57

**Background**: Mixture-of-Experts (MoE) models use a router to selectively activate only a subset of 'expert' sub-networks for each input, allowing models to scale to massive parameter counts while keeping computational costs low. FP8 quantization stores model weights in 8-bit floating-point format, significantly reducing memory footprint and accelerating inference with minimal accuracy loss.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mixture_of_experts">Mixture of experts - Wikipedia</a></li>
<li><a href="https://www.spheron.network/blog/fp8-quantization-inference-performance-hardware-explained/">What is FP8 Quantization? AI Inference Performance, Accuracy, and Hardware Support Explained (2026) | Spheron Blog</a></li>

</ul>
</details>

**Tags**: `#AI`, `#LLM`, `#open-source`, `#MoE`, `#Tencent`

---

<a id="item-8"></a>
## [Sensor-Valid Masking for Depth Completion Sets SOTA; LingBot-Vision Backbone Outperforms DINOv2](https://www.reddit.com/r/MachineLearning/comments/1upqghy/masked_depth_modeling_with_sensorvalidity_masking/) ⭐️ 8.0/10

LingBot-Depth 2.0 introduces sensor-validity masking, where the model learns to inpaint depth from real sensor failures (e.g., specular highlights, transparent surfaces) instead of random masks. A controlled encoder-initialization study shows that the LingBot-Vision backbone consistently outperforms DINOv2 as data scales, achieving state-of-the-art RMSE on 7 out of 8 masked/sparse depth completion benchmarks. This approach aligns training with the actual failure modes of depth sensors, potentially improving robustness of robotic perception in challenging real-world scenes with reflective or transparent objects. The clear superiority of the LingBot-Vision backbone at scale provides valuable guidance for encoder selection in future 3D vision tasks. The method achieves its strongest gains on the ClearGrasp transparent-object dataset, but DINOv2 retains a slight edge on Hammer captures. The Depth 2.0 model weights are not open-sourced; only the LingBot-Vision backbones are publicly available under Apache 2.0. The encoder-init study demonstrates that performance gaps widen with increasing data scale.

reddit · r/MachineLearning · /u/Ok-Line2658 · Jul 7, 09:54

**Background**: Depth completion aims to fill in missing depth values from sensors like RGB-D cameras, which often fail on transparent, reflective, or textureless surfaces due to physical limitations. Masked Autoencoders (MAE) are self-supervised models that learn by reconstructing randomly masked patches. Masked Depth Modeling leverages the sensor's own validity mask—indicating which pixels have valid depth readings—as a natural and challenging reconstruction target, rather than using artificial random masks. LingBot-Vision is a vision backbone developed by Ant Group's Robbyant team, used as the encoder in this pipeline.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/html/2601.17895v1">Masked Depth Modeling for Spatial Perception</a></li>
<li><a href="https://github.com/Robbyant/lingbot-depth">GitHub - Robbyant/lingbot-depth: Masked Depth Modeling for Spatial Perception · GitHub</a></li>
<li><a href="https://www.emergentmind.com/topics/masked-depth-modeling">Masked Depth Modeling Techniques</a></li>

</ul>
</details>

**Tags**: `#depth completion`, `#self-supervised learning`, `#masked autoencoders`, `#3D vision`, `#sensor-failure modeling`

---

<a id="item-9"></a>
## [LingBot-Vision: Masked Boundary Modeling for Self-Supervised Pretraining](https://www.reddit.com/r/MachineLearning/comments/1up4cjh/lingbotvision_masked_boundary_modeling_for/) ⭐️ 8.0/10

LingBot-Vision introduces a self-supervised pretraining method where an online teacher predicts dense boundary fields, and boundary-bearing tokens are masked to force the student to reconstruct hard-to-infer regions, achieving state-of-the-art NYUv2 depth estimation RMSE of 0.296 with a 1.1B model, outperforming DINOv3-7B's 0.309. This work demonstrates that boundary-aware masking can yield highly effective visual representations with less data and model size, potentially reducing computational costs and improving performance on dense prediction tasks like depth estimation. The release of weights in four sizes encourages further research and application. Key technical details include boundary fields as per-pixel categorical distributions to avoid EMA drift, an a-contrario validation test for decoded segments, and training on 161M images. Limitations: ImageNet classification and ADE20K segmentation trail DINOv3, and the NYUv2 RMSE improvement may be within probe variance; checkpoints are available for independent verification.

reddit · r/MachineLearning · /u/StillThese3747 · Jul 6, 17:37

**Background**: Self-supervised pretraining learns visual representations from unlabeled images by solving pretext tasks like masked image modeling (MIM), where parts of an image are masked and reconstructed. Boundary fields represent image edges as dense predictions. DINOv3 is a state-of-the-art self-distillation method for vision. NYUv2 is a dataset for depth estimation, and linear probe evaluates frozen features with a linear classifier.

**Tags**: `#Self-Supervised Learning`, `#Computer Vision`, `#Masked Image Modeling`, `#Representation Learning`, `#Deep Learning`

---

<a id="item-10"></a>
## [China to Invest $295 Billion Over 5 Years for Nationwide Computing Network](https://t.me/zaihuapd/42399) ⭐️ 8.0/10

China announced a plan to invest about 2 trillion yuan ($295 billion) over five years to build a nationwide computing network, with state-owned telecom operators running key facilities. The network will prioritize domestic AI chips (at least 80%), such as Huawei's, and China Telecom and China Unicom have already launched computing token packages, selling computing power like mobile data. This massive investment aims to create an autonomous AI computing infrastructure, reducing China's reliance on U.S. chipmakers and strengthening its domestic semiconductor industry. It could accelerate AI adoption across industries and reshape geopolitical tech competition. The network is part of Beijing's 'six networks' infrastructure plan and requires at least 80% domestic AI chips. Telecom operators have begun offering computing power as token packages, with some priced as low as 5.99 yuan per month for basic plans.

telegram · zaihuapd · Jul 7, 04:45

**Background**: A 'computing network' (算力网络) aims to make distributed computing resources accessible like a utility, often described as Network as a Computer. The push comes after U.S. export controls limited China's access to advanced AI chips from Nvidia and AMD, fueling a drive for self-sufficiency. Token-based computing packages allow users to purchase computing power on a pay-as-you-go basis, lowering the barrier for AI application development.

<details><summary>References</summary>
<ul>
<li><a href="https://36kr.com/p/1858434719471494">到底什么是“ 算 力 网 络 ”？ -36氪</a></li>
<li><a href="https://m.ithome.com/html/633569.htm">到底什么是“ 算 力 网 络 ”？ - IT之家</a></li>
<li><a href="https://finance.sina.cn/tech/2026-04-21/detail-inhvheze6850693.d.html?fromtech=1&vt=4">算 力 套 餐 亲民上线——北京移动 算 力 Token 套 餐 开售！| 数据安全|Qwen...</a></li>

</ul>
</details>

**Tags**: `#compute-network`, `#China`, `#AI-chips`, `#infrastructure`, `#national-strategy`

---

<a id="item-11"></a>
## [Anthropic Releases Claude Sonnet 5 with Enhanced Agentic Capabilities](https://t.me/zaihuapd/42404) ⭐️ 8.0/10

Anthropic has released Claude Sonnet 5, its most agentic-capable Sonnet model to date, which can plan, autonomously use tools like browsers and terminals, and delivers performance approaching Opus 4.8 at a lower cost. It is available to all plans immediately and becomes the default model for Free and Pro tiers. This release makes advanced, autonomous agent capabilities more accessible by offering near-premium performance at a Sonnet price point, which could accelerate the adoption of AI agents across both consumer and enterprise applications. Claude Sonnet 5 outperforms Sonnet 4.6 in reasoning, tool use, coding, and knowledge work; its promotional pricing until August 31, 2026, is $2 per million input tokens, with output tokens priced higher.

telegram · zaihuapd · Jul 7, 09:02

**Background**: Agentic AI refers to AI systems that can autonomously pursue goals, use tools, and take actions with minimal human intervention. In LLM pricing, a token is the basic unit of text processed, roughly equivalent to 4 characters or 0.75 words. Claude Sonnet 5 is an upgrade in Anthropic's Sonnet line, positioned between the faster Haiku and the more powerful Opus models.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Agentic_AI">Agentic AI</a></li>
<li><a href="https://llm-tokenizer.com/faq/">LLM Token Counter FAQ - Common Questions & Answers</a></li>

</ul>
</details>

**Tags**: `#AI`, `#LLM`, `#Anthropic`, `#Claude`, `#Model Release`

---

<a id="item-12"></a>
## [sqlite-utils 4.0 Adds Schema Migration, Nested Transactions, and Compound Foreign Keys](https://simonwillison.net/2026/Jul/7/sqlite-utils-4/#atom-everything) ⭐️ 7.0/10

sqlite-utils 4.0, the first major release since 2020, adds database schema migrations, nested transactions with db.atomic(), and compound foreign keys. These features enable developers to manage evolving database schemas in production, simplify complex transactional workflows, and model more sophisticated data relationships, making sqlite-utils more capable for real-world applications. Migrations are defined as Python functions decorated with the Migrations class and leverage table.transform() to perform ALTER TABLE operations not natively supported by SQLite. The db.atomic() method likely implements nested transactions using SQLite's SAVEPOINT feature.

rss · Simon Willison · Jul 7, 19:32

**Background**: Database schema migrations are version-controlled changes to a database's structure, essential for evolving applications without losing data. SQLite's ALTER TABLE has limited capabilities, so tools simulate complex changes via table recreation. Nested transactions allow sub-transactions within a larger transaction, typically implemented using savepoints in SQLite since it doesn't support true nesting. Compound foreign keys reference multiple columns together, ensuring referential integrity for composite primary keys.

<details><summary>References</summary>
<ul>
<li><a href="https://www.bytebase.com/blog/what-is-database-migration/">What is Database Schema Migration ? | Bytebase</a></li>
<li><a href="https://www.slingacademy.com/article/using-nested-transactions-to-simplify-complex-workflows-in-sqlite/">Using Nested Transactions to Simplify Complex Workflows in SQLite</a></li>
<li><a href="https://abridger.readthedocs.io/en/v0.1.0/examples_compound_foreign_keys/">Compound Foreign Keys — abridger 0.1.0 documentation</a></li>

</ul>
</details>

**Tags**: `#sqlite`, `#python`, `#database`, `#migrations`, `#tools`

---

<a id="item-13"></a>
## [MemGUI-Agent: End-to-End Long-Horizon Mobile GUI Agent with Memory](https://mp.weixin.qq.com/s?__biz=MzIzNjc1NzUzMw==&mid=2247902040&idx=3&sn=68b945acd4b331099f80f29c018551b8) ⭐️ 7.0/10

Kuaishou and Zhejiang University jointly introduced MemGUI-Agent, an end-to-end mobile GUI agent that prevents forgetting during long-horizon tasks by integrating proactive context management as an explicit action. It addresses a critical limitation of current GUI agents—memory degradation in complex, multi-step mobile tasks—enabling more reliable automation across real-world applications. The agent uses a ConAct interface to explicitly manage context, controlling prompt growth and preserving essential UI facts. It has been evaluated on MemGUI-Bench and MobileWorld using 8B models.

rss · 量子位 · Jul 7, 04:30

**Background**: Mobile GUI agents use AI to automate interactions with graphical user interfaces. Long-horizon tasks involve many steps across multiple apps, where agents often forget earlier contexts due to memory limitations. Memory augmentation is a key research challenge in this field.

<details><summary>References</summary>
<ul>
<li><a href="https://memgui-agent.github.io/">MemGUI - Agent</a></li>
<li><a href="https://github.com/kwai/MemGUI-Agent">GitHub - kwai/ MemGUI - Agent : Official code for " MemGUI - Agent : An..."</a></li>

</ul>
</details>

**Tags**: `#GUI-Agent`, `#Long-Horizon Tasks`, `#Mobile Automation`, `#AI Agent`, `#Memory`

---

<a id="item-14"></a>
## [AlphaFold Nobel Winner Joins Anthropic; AI Tutor Beats Classroom](https://aiweekly.co/issues/alphafolds-nobel-winner-just-joined-anthropic-and-6-more-ai) ⭐️ 7.0/10

A Nobel laureate from the AlphaFold team has joined Anthropic, advancing the AI-for-science push. Open-source frontier models have become cheaper again, and the first rigorous study shows an AI tutor outperforming traditional classroom instruction. These wins highlight AI's concrete impact: top talent bolsters research at safety-focused labs, cheaper models democratize access, and proven educational gains could reshape how we teach. The laureate is likely John Jumper or Demis Hassabis, recognized for protein structure prediction; Anthropic gains expertise for scientific AI. Cost drops may stem from efficiency improvements. The AI tutor study demonstrated a statistically significant improvement over classroom learning.

rss · AI Weekly · Jul 6, 00:00

**Background**: AlphaFold is a DeepMind AI system for predicting protein structures, which earned a Nobel Prize in Chemistry in 2024. Anthropic is an AI safety company building frontier models like Claude. Open frontier models are cutting-edge AI systems with publicly available weights. AI tutors use adaptive learning to personalize instruction.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Frontier_model">Frontier model</a></li>
<li><a href="https://grokipedia.com/page/Frontier_AI_models">Frontier AI models</a></li>

</ul>
</details>

**Tags**: `#AI`, `#AI-for-science`, `#Anthropic`, `#open-models`, `#education-tech`

---

<a id="item-15"></a>
## [Ph.D. Thesis: Differentiable Ray Tracing for Radio Propagation Modeling](https://www.reddit.com/r/MachineLearning/comments/1upvkp5/phd_thesis_on_differentiable_ray_tracing_for/) ⭐️ 7.0/10

A Ph.D. thesis introduces a differentiable ray tracing framework for radio propagation modeling, using JAX to compute exact gradients through complex physical environments for inverse problems and machine learning training. By enabling gradient-based optimization of wireless system parameters like antenna placement and material properties, this work bridges differentiable simulation and next-gen network design, critical for machine learning-assisted 6G technologies. The thesis is structured into fundamentals (electromagnetic theory, geometrical optics, diffraction), algorithmic core (GPU-accelerated path tracing, discontinuity smoothing), and applications (channel modeling, localization, material calibration, ML-assisted sampling). It builds on JAX packages like jaxtyping, equinox, optimistix, and the author's own DiffeRT library.

reddit · r/MachineLearning · /u/jeertmans · Jul 7, 13:45

**Background**: Differentiable ray tracing combines ray tracing (simulating wave propagation by tracing rays) with automatic differentiation, a technique that efficiently computes exact derivatives of functions defined by code. In wireless communications, ray tracing models signal propagation in complex environments, while automatic differentiation enables gradient-based optimization, overcoming limitations of finite difference methods.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Automatic_differentiation">Automatic differentiation</a></li>
<li><a href="https://arxiv.org/pdf/2303.11103">Sionna RT: Differentiable Ray Tracing</a></li>

</ul>
</details>

**Tags**: `#differentiable ray tracing`, `#radio propagation`, `#automatic differentiation`, `#wireless communications`, `#machine learning`

---

<a id="item-16"></a>
## [Mozilla CTO to Host AMA on State of Open Source AI Report](https://www.reddit.com/r/MachineLearning/comments/1upxdvc/raffi_krikorian_cto_mozilla_ama_on_the_state_of/) ⭐️ 7.0/10

Raffi Krikorian, Mozilla's CTO, announced an AMA on July 14 to discuss the inaugural State of Open Source AI report, covering topics like costs, enterprise adoption, Chinese models, and developer trust. The AMA provides a platform for direct discussion on critical open source AI issues, offering insights that could shape developer strategies and enterprise decisions. The report draws on feedback from over 950 developers, and topics include the "agentic harness" layer shifting focus away from models themselves.

reddit · r/MachineLearning · /u/raffikrikorian · Jul 7, 14:51

**Background**: An "agentic harness" refers to the infrastructure layer that enables AI systems to operate as autonomous agents with decision-making capabilities, rather than simple responders. Mozilla is a non-profit organization best known for the Firefox browser, and has long advocated for an open web; this report reflects its interest in open source AI.

<details><summary>References</summary>
<ul>
<li><a href="https://medium.com/@balajibal/agentic-harnesses-the-new-infrastructure-layer-for-ai-systems-3939c6fac1a6">Agentic Harnesses : The New Infrastructure Layer for AI... | Medium</a></li>

</ul>
</details>

**Tags**: `#open source AI`, `#AMA`, `#Mozilla`, `#enterprise AI`, `#developer trust`

---

<a id="item-17"></a>
## [TRACE: Open-Source Hierarchical Memory for LLM Agents Hits 82.5% on EventQA](https://www.reddit.com/r/MachineLearning/comments/1uoz5jo/trace_opensource_hierarchical_memory_for_llm/) ⭐️ 7.0/10

TRACE introduces a hierarchical memory system that organizes conversation history into a topic tree with branches and summaries, departing from flat RAG chunks. Benchmarked on MemoryAgentBench's EventQA, it achieved an F1 score of 82.5% using the open-weights model gpt-oss-20B. This result shows that hierarchical topic-tree memory can significantly outperform flat memory systems and even some proprietary model-based approaches, pointing toward more effective open-source memory solutions for AI agents. The comparison is not fully controlled: Mem0 and MemGPT were tested with GPT-4o-mini, while TRACE used gpt-oss-20B due to parsing issues with the open model. Full experimental logs are publicly available in the repository.

reddit · r/MachineLearning · /u/PsychologicalDot7749 · Jul 6, 14:35

**Background**: MemoryAgentBench is a benchmark that evaluates LLM agent memory through incremental multi-turn interactions, with EventQA requiring understanding of temporal event chains in novels. Hierarchical memory methods, such as topic trees, organize information into structured levels to reduce fragmentation and semantic drift, addressing limitations of flat retrieval-augmented generation.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/HUST-AI-HYZ/MemoryAgentBench">GitHub - HUST-AI-HYZ/ MemoryAgentBench : Open source code for...</a></li>
<li><a href="https://huggingface.co/datasets/ai-hyz/MemoryAgentBench">ai-hyz/ MemoryAgentBench · Datasets at Hugging Face</a></li>
<li><a href="https://arxiv.org/html/2601.06377v1">HiMem: Hierarchical Long-Term Memory for LLM Long-Horizon...</a></li>

</ul>
</details>

**Tags**: `#LLM agents`, `#memory systems`, `#hierarchical memory`, `#open-source`, `#EventQA`

---

<a id="item-18"></a>
## [Elon Musk Dissolves xAI, Integrates as SpaceXAI into SpaceX](https://x.com/i/status/2074214064746832060) ⭐️ 7.0/10

Elon Musk announced that xAI is being dissolved as an independent company and merged into SpaceX under the new brand SpaceXAI. The company formerly known as xAI recently identified itself as SpaceXAI in a computing partnership announcement with Anthropic. This merger centralizes AI development under SpaceX, potentially accelerating the integration of AI into space exploration and satellite internet. It also removes xAI as an independent AI entity, reshaping the competitive landscape for AI talent and technology. The dissolution follows SpaceX's acquisition of xAI, and the name change was revealed through a joint computing deal with Anthropic. Specific details about the technology integration or timeline have not been disclosed.

telegram · zaihuapd · Jul 7, 02:30

**Background**: xAI was an artificial intelligence company founded by Elon Musk in 2023, aimed at building AI systems to understand the true nature of the universe. SpaceX, also founded by Musk, is a private aerospace manufacturer known for rockets and Starlink satellite internet. Anthropic is an AI safety and research lab. The merger indicates that xAI's technology will now be directed towards SpaceX's projects rather than remaining a general-purpose AI venture.

**Tags**: `#AI`, `#xAI`, `#SpaceX`, `#Elon Musk`, `#business`

---

<a id="item-19"></a>
## [AI Phone and PC Sales to Surpass Non-AI for First Time in 2025](https://www.cls.cn/detail/2418840) ⭐️ 7.0/10

A National Development and Reform Commission official predicted that sales of AI smartphones and PCs will exceed those of non-AI models for the first time in 2025, driven by over 100 million shipments in China last year. This milestone signals a consumer market shift where AI becomes a standard feature, accelerating the 'AI+' industrial upgrade and reshaping competitive dynamics in the global electronics supply chain. In 2024, China's AI phone and PC shipments surpassed 100 million units; AI-native office agents now attract over 20 million monthly visits, and daily token call volumes reach hundreds of trillions, reflecting explosive growth in AI applications.

telegram · zaihuapd · Jul 7, 05:37

**Background**: AI smartphones and AI PCs integrate dedicated neural processing units (NPUs) to run on-device AI features like real-time translation, intelligent photography, and voice assistants. China's 'AI+' strategy promotes embedding AI across industries, and the rapid adoption of AI-native services is driving demand for capable hardware.

<details><summary>References</summary>
<ul>
<li><a href="https://en.people.cn/n3/2026/0430/c90000-20452228.html">China reports roughly 21.1 quadrillion token calls in 2025...</a></li>

</ul>
</details>

**Tags**: `#AI devices`, `#AI market trends`, `#smartphones`, `#PCs`, `#industry forecast`

---

<a id="item-20"></a>
## [new-api Fixes Integer Overflow Billing Vulnerability](https://github.com/QuantumNous/new-api/commit/d0bd8aa) ⭐️ 7.0/10

The new-api project patched a billing vulnerability where unvalidated large parameters triggered integer overflow, resulting in negative charge calculations. Two commits introduced upper-bound checks and saturating conversion to prevent such overflow. This vulnerability could allow attackers to manipulate billing calculations, effectively crediting their accounts instead of deducting charges, posing a financial risk to the API provider. The fix ensures accurate cost accounting and system integrity for users of the AI gateway. The fix applies upper-bound validation on parameters and uses saturating integer conversion to clamp values, avoiding wrap-around to negatives. It also adds boundary checks at additional entry points to prevent bypassing type checks for pre-deduction and settlement logic.

telegram · zaihuapd · Jul 7, 07:26

**Background**: new-api is an open-source AI API gateway developed by QuantumNous that provides unified access to multiple AI models, with features like cost accounting and usage analytics. Integer overflow occurs when an operation produces a value exceeding the maximum capacity of the data type, causing it to wrap around to an unintended value—in this case, negative numbers. In billing systems, if an overflow occurs during charge calculation, a user might be credited instead of charged. Saturating conversion is a technique that limits the result to the maximum representable value, preventing overflow.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/QuantumNous/new-api">GitHub - QuantumNous / new - api : A unified AI model hub for...</a></li>
<li><a href="https://frama-c.com/2013/10/09/Overflow-float-integer.html">The overflow when converting from float to integer is undefined...</a></li>

</ul>
</details>

**Tags**: `#security`, `#billing`, `#integer overflow`, `#API`, `#vulnerability fix`

---

<a id="item-21"></a>
## [DeepSeek Developing Own AI Inference Chip to Cut Nvidia, Huawei Dependency](https://www.reuters.com/world/china/chinas-deepseek-developing-its-own-ai-chip-sources-say-2026-07-07/) ⭐️ 7.0/10

Chinese AI company DeepSeek is reportedly developing its own AI chip focused on inference, aiming to reduce its reliance on Nvidia and Huawei chips, according to sources. This move highlights how US export controls are driving Chinese AI firms to pursue chip self-sufficiency, potentially reshaping the semiconductor supply chain. The chip targets inference (not training), has been in early-stage development for about a year, and DeepSeek is now engaging with design, foundry, and storage partners while hiring engineers.

telegram · zaihuapd · Jul 7, 11:08

**Background**: AI chips handle either training (building models) or inference (running models). DeepSeek previously used Nvidia H800 GPUs and Huawei Ascend chips, but US restrictions limit access to advanced Nvidia hardware. Huawei Ascend represents China's domestic alternative, though performance gaps remain.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/NVIDIA_H800_GPU">NVIDIA H800 GPU</a></li>
<li><a href="https://woteq.com/deepseek-and-nvidia-relationship-what-happened-and-why-it-matters">DeepSeek and Nvidia Relationship — What Happened... - Woteq Zone</a></li>
<li><a href="https://www.computerlanguage.com/results.php?definition=Huawei+Ascend+chip">Huawei Ascend chip - CLC Definition</a></li>

</ul>
</details>

**Tags**: `#AI chips`, `#DeepSeek`, `#NVIDIA`, `#export controls`, `#semiconductor`

---

<a id="item-22"></a>
## [Chinese Web Novel Platforms Reverse AI Embrace, Crack Down on AI-Generated Content](https://restofworld.org/2026/china-ai-web-novels/) ⭐️ 7.0/10

Chinese web novel platforms, including Fanqie Novel under ByteDance and Qidian and Jinjiang under Tencent, have shifted from actively integrating AI writing tools to imposing strict restrictions on AI-generated submissions after reader backlash over declining quality. For instance, Fanqie Novel began limiting daily word counts per account and rejected over 104,000 low-quality, AI-written submissions in June. This policy reversal highlights the growing tension between the efficiency gains from AI and the preservation of creative quality in mass-market literature, potentially reshaping content standards across China’s vast online fiction industry and influencing similar platforms worldwide. Jinjiang now only permits AI for research and proofreading, while Fanqie Novel has capped daily word counts and explicitly rejected AI-assisted low-quality work, with over 104,000 submissions turned away in a single month.

telegram · zaihuapd · Jul 7, 13:27

**Background**: Chinese web novel platforms originally operated on a serialized model that incentivized high-volume output, leading companies like ByteDance and Tencent to introduce AI tools to help authors generate plotlines and chapters faster. However, readers began encountering obvious AI artifacts, such as leftover prompt text, which eroded trust and satisfaction, prompting platforms to prioritize authenticity and readability over sheer productivity.

**Tags**: `#AI-generated content`, `#web novels`, `#platform policy`, `#China tech`, `#creative writing`

---

<a id="item-23"></a>
## [California and New York push for firearm-blocking software in 3D printers](https://www.theverge.com/tech/960802/3d-printed-gun-laws-ghost-guns) ⭐️ 7.0/10

California's AB 2047 bill and New York's newly signed law require 3D printers and CNC machines sold in the state to integrate firearm blueprint detection and blocking software, aiming to curb the production of untraceable 'ghost guns'. This legislation could establish a precedent for mandatory embedded software in hardware, significantly impacting open-source 3D printing, digital rights, and the DIY community, while raising concerns about censorship and potential misuse against intellectual property. California's AB 2047 would ban sales of non-compliant printers starting July 2029, with civil penalties up to $25,000 per violation; critics warn of false positives, cloud scanning of user files, and undefined technical standards.

telegram · zaihuapd · Jul 7, 14:02

**Background**: Ghost guns are homemade firearms without serial numbers, often 3D-printed, making them untraceable. 3D printers build objects from digital models, and CNC machines carve parts from solid materials; both can produce gun components. Previous regulations targeted gun parts, not the machines themselves.

<details><summary>References</summary>
<ul>
<li><a href="https://www.slashgear.com/2111288/3d-printer-firearm-blocking-tech-law-california/">New Law Would Demand ' Firearm Blocking' Tech In Every 3 D Printer</a></li>
<li><a href="https://www.tigerdroppings.com/rant/tech/a-few-3d-printing-companies-have-decided-to-detect-firearm-printing/116354074/">A few 3 D printing companies have decided to detect firearm printing</a></li>

</ul>
</details>

**Tags**: `#3D printing`, `#legislation`, `#gun control`, `#censorship`, `#digital rights`

---

<a id="item-24"></a>
## [30papers.com: Ilya Sutskever's 30 Essential ML Papers for Beginners](https://30papers.com/) ⭐️ 6.0/10

A website named 30papers.com has been launched, listing 30 machine learning papers purportedly recommended by Ilya Sutskever, with simplified explanations aimed at beginners. The curated list may lower the barrier for newcomers to access foundational ML research and could spark interest in studying important papers, though its authenticity remains unverified. The source of the paper list is uncertain; it appeared on X without clear attribution to Sutskever or John Carmack, and the website is an unpolished side project built by a first-year student.

hackernews · notmcrowley · Jul 7, 15:58 · [Discussion](https://news.ycombinator.com/item?id=48819608)

**Background**: Ilya Sutskever is a prominent AI researcher, co-founder of OpenAI, and a key figure in deep learning. The list includes foundational papers like 'Attention is All You Need' and concepts such as the attention mechanism and Kolmogorov complexity, which are central to modern machine learning. The community has raised questions about the list's authenticity, noting it lacks direct sourcing.

**Discussion**: Commenters express skepticism about the list's origin, with some requesting a logical reading order. Others share related projects like ListenDock for audio versions. The site's author, a student, clarifies it's a side project and welcomes contributions.

**Tags**: `#machine-learning`, `#research-papers`, `#curated-list`, `#education`, `#beginners`

---

<a id="item-25"></a>
## [TorchJD Implements Jacobian Descent Methods for Multi-Loss Training in PyTorch](https://www.reddit.com/r/MachineLearning/comments/1upzxk2/torchjd_training_with_multiple_losses_in_pytorch_p/) ⭐️ 6.0/10

TorchJD now implements most existing Jacobian descent methods for multi-loss training in PyTorch and has been accepted into the PyTorch ecosystem. This makes it easier for researchers and practitioners to experiment with advanced multi-objective optimization techniques in PyTorch, which can lead to better handling of conflicting losses in multi-task learning. The library supports both scalarization (weighted sum) and Jacobian descent methods by aggregating per-loss gradients into an update vector that decreases each individual loss.

reddit · r/MachineLearning · /u/Skeylos2 · Jul 7, 16:20

**Background**: In multi-task learning, models are trained with multiple loss functions. Traditional scalarization combines losses into a single weighted sum, but may fail to balance conflicting objectives. Jacobian descent computes per-loss gradients (the Jacobian) and aggregates them to reduce all losses simultaneously, providing a more principled approach to multi-objective optimization.

<details><summary>References</summary>
<ul>
<li><a href="https://medium.com/@_prinsh_u/jacobian-descent-for-multi-objective-optimization-0731c6e9e5b0">Jacobian Descent for Multi-Objective Optimization | Medium</a></li>
<li><a href="https://arxiv.org/html/2406.16232">Jacobian Descent for Multi-Objective Optimization</a></li>

</ul>
</details>

**Tags**: `#pytorch`, `#multi-task learning`, `#optimization`, `#deep learning`, `#python`

---

<a id="item-26"></a>
## [ICML Position Paper Proposes Credit System for Better ML Peer Reviews](https://www.reddit.com/r/MachineLearning/comments/1upjftu/icml_position_track_want_better_ml_reviews_stop/) ⭐️ 6.0/10

An ICML position paper introduces a credit-based incentive system where reviewers earn points for good behavior, such as receiving +1 for a regular review and +3 for an outstanding one, which can be redeemed for perks like free registration or requesting an additional reviewer. This proposal directly addresses the chronic lack of accountability and engagement in ML peer review, potentially improving review quality and fairness for all conference participants. The credit system includes novel features like refundable submission fees using points and the use of non-author reviewers to reduce bandwidth conflicts, though the author acknowledges the proposal is not perfect.

reddit · r/MachineLearning · /u/choHZ · Jul 7, 03:32

**Background**: Peer review at top ML conferences like ICML often suffers from rushed, low-quality reviews because reviewers lack incentives. Traditional reminders and guidelines have limited effectiveness. Position papers at ICML allow researchers to propose and discuss ideas without requiring experimental validation.

**Tags**: `#peer review`, `#machine learning`, `#academia`, `#incentive structures`, `#position paper`

---

<a id="item-27"></a>
## [Offline ASL Recognition on Raspberry Pi 5 Using MediaPipe and TensorFlow Lite](https://www.reddit.com/r/MachineLearning/comments/1up3kby/edge_ai_asl_recognition_on_raspberry_pi_5_looking/) ⭐️ 6.0/10

A developer is implementing an offline American Sign Language (ASL) recognition system on a Raspberry Pi 5, using MediaPipe hand landmarks and TensorFlow Lite, and is seeking community feedback on choosing between a 1D CNN, MLP, or GRU architecture for real-time classification. This project highlights practical trade-offs in deploying efficient machine learning on low-power edge devices for accessibility, reflecting the growing trend of on-device AI that preserves privacy and reduces latency for assistive technologies. The pipeline extracts 21 hand landmarks via MediaPipe, normalizes them, and feeds them into a TensorFlow Lite model on a Raspberry Pi 5, with output to an OLED display and offline text-to-speech; the model choice prioritizes low latency over maximum accuracy.

reddit · r/MachineLearning · /u/Unlikely_Let_9147 · Jul 6, 17:10

**Background**: American Sign Language (ASL) is a visual language using hand shapes and movements. MediaPipe is an open-source framework by Google that provides real-time hand landmark detection. TensorFlow Lite is a lightweight version of TensorFlow designed to run machine learning models on resource-constrained devices like the Raspberry Pi. The choice of neural network architecture—1D CNN, MLP (multi-layer perceptron), or GRU (gated recurrent unit)—affects the trade-off between speed, model size, and the ability to capture sequential patterns in dynamic gestures.

<details><summary>References</summary>
<ul>
<li><a href="https://www.influxdata.com/blog/tensorflow-lite-tutorial-how-to-get-up-and-running/">TensorFlow Lite Tutorial: How to Get Up and Running | InfluxData</a></li>
<li><a href="https://medium.com/@florian-trautweiler/real-time-hand-tracking-in-python-e2bcdd0feace">Real-Time Hand Tracking in Python | by Florian Trautweiler | Medium</a></li>

</ul>
</details>

**Tags**: `#edge-ai`, `#sign-language-recognition`, `#tensorflow-lite`, `#mediapipe`, `#embedded-ml`

---

<a id="item-28"></a>
## [Google Now Saves Lens and Voice Search for AI Training by Default, Opt-Out Available](https://techcrunch.com/2026/07/06/if-you-use-google-youre-training-its-ai-heres-how-to-opt-out/) ⭐️ 6.0/10

Google has introduced a new 'Save media' setting in Search service history, which by default saves media from Google Lens, voice search, and live translations to enhance its products and AI models. Users can disable this feature via their account settings. This change underscores how user-generated media can be utilized for AI development without explicit consent, making opt-out mechanisms critical for privacy-conscious individuals. It reflects broader industry trends where default data collection fuels AI improvements. The opt-out is located within Google account settings under 'Search service history,' affecting media from Google Lens, voice search, Search Live, and spoken translation practice. It is unclear whether previously saved media is deleted after opting out.

telegram · zaihuapd · Jul 7, 04:00

**Background**: Google Lens is a visual search tool that identifies objects and text from images, while voice search allows spoken queries. These features process user-submitted media to deliver results, and the new setting indicates this data may now be additionally leveraged for AI training purposes. Such practices are becoming common as companies seek diverse data to improve models like language and vision AI.

**Tags**: `#privacy`, `#AI training`, `#Google`, `#data collection`, `#opt-out`

---

<a id="item-29"></a>
## [Windows 11 Capability Access Manager Bug Consumes Up to 513GB Disk Space](https://www.windowslatest.com/2026/07/06/microsoft-admits-a-windows-11-bug-is-eating-up-to-500gb-of-storage-verify-if-you-are-affected/) ⭐️ 6.0/10

Microsoft acknowledged a bug in the Windows 11 Capability Access Manager service where its write-ahead log (WAL) file, CapabilityAccessManager.db-wal, can grow excessively, consuming up to 513 GB of storage. A fix has been released in the June 2026 optional update KB5095093 and will be included in the July patch. This bug can stealthily consume significant disk space, potentially causing system slowdowns or insufficient storage for users, especially on devices with smaller SSDs. It highlights the importance of timely updates and monitoring system logs for unexpected behavior. The problematic file is CapabilityAccessManager.db-wal, and the issue stems from the WAL log failing to merge back into the main database. The service tracks app access to sensitive devices like camera, microphone, location, and screen capture; the fix improves disk usage of this WAL file.

telegram · zaihuapd · Jul 7, 06:34

**Background**: The Capability Access Manager is a Windows 11 service that manages application access to privacy-sensitive hardware like cameras and microphones. It maintains a database of access logs, and like many database systems, it uses Write-Ahead Logging (WAL) to ensure data integrity—changes are first recorded in a log file before being committed to the main database. Normally, the WAL file is periodically merged back; in this bug, the merge fails, causing the file to grow indefinitely.

<details><summary>References</summary>
<ul>
<li><a href="https://www.minitool.com/news/capability-access-manager-service-high-cpu-usage.html">How to Fix Capability Access Manager Service High CPU Usage?</a></li>
<li><a href="https://en.wikipedia.org/wiki/Write-ahead_logging">Write - ahead logging - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#Windows`, `#bug`, `#storage`, `#privacy`, `#update`

---

<a id="item-30"></a>
## [NVIDIA Blackwell Chips Made in US Still Need Taiwan Packaging](https://www.tomshardware.com/tech-industry/nvidia-and-intel-tout-chips-built-in-america-but-every-arizona-made-blackwell-die-is-still-packaged-in-taiwan) ⭐️ 6.0/10

TSMC's Arizona Fab 21 has begun producing NVIDIA Blackwell wafers using the custom 4NP process, and Intel's local Fab 52 is also producing chips on its 18A node, marking the first US-based manufacturing of such advanced logic chips. However, these wafers still need to be shipped approximately 7,000 miles to Taiwan for cutting, stacking, and CoWoS-L packaging. This highlights a critical gap in the US semiconductor supply chain: while advanced chip fabrication is now possible domestically, advanced packaging and HBM production remain concentrated in Asia. It underscores the challenges in achieving full semiconductor self-sufficiency and could affect lead times, costs, and geopolitical risk for high-performance chips. Blackwell's multi-die design relies on CoWoS-L, a 2.5D packaging technology that integrates logic and high-bandwidth memory (HBM) dies using a silicon interposer bridge. The US currently lacks CoWoS-L and HBM fabrication facilities; Amkor, TSMC, and SK hynix are building capacity, but a complete stateside supply chain is not expected until 2028-2029.

telegram · zaihuapd · Jul 7, 09:47

**Background**: Advanced packaging is crucial for modern GPUs like NVIDIA's Blackwell, which combine multiple compute and memory dies on a single package to boost performance and efficiency. CoWoS (Chip-on-Wafer-on-Substrate) is TSMC's proprietary 2.5D packaging technology; the 'L' variant uses a local silicon bridge for higher interconnect density. TSMC's 4NP is an enhanced 5nm process optimized for NVIDIA. Intel's 18A node introduces backside power delivery (BSPDN) and is a key milestone for US foundry ambitions.

<details><summary>References</summary>
<ul>
<li><a href="https://siliconanalysts.com/tools/packaging">Advanced Packaging Cost Calculator: CoWoS , InFO... | Silicon Analysts</a></li>
<li><a href="https://wccftech.com/intel-18a-process-is-finally-ready-after-years-of-wait-team-blue-to-tape-out-chips-by-h1-2025/">Intel 's 18 A Process Is "Finally Ready" After Years of Wait; Team ...</a></li>

</ul>
</details>

**Tags**: `#semiconductors`, `#NVIDIA`, `#Blackwell`, `#packaging`, `#supply chain`

---

<a id="item-31"></a>
## [Claude Fable 5 Relaunch Faces Backlash Over Safety False Positives](https://t.me/zaihuapd/42415) ⭐️ 6.0/10

After U.S. export controls were lifted, Anthropic relaunched Claude Fable 5 with restricted access for subscribers and a switch to pay-per-use after July 7, sparking user complaints about overly strict safety filters that frequently misclassify low-level programming content. The backlash underscores the challenge of balancing safety with functionality in AI models, as overly aggressive filters can hinder developers working on systems programming and security research, potentially slowing adoption in critical technical fields. Pro and Max subscribers are limited to 50% of their usual quota for Claude Fable 5 until July 7, after which the model will be excluded from subscriptions and charged per use. The safety filters are especially prone to false positives when handling C/C++, Rust code, or keywords like 'vulnerability' and 'hook'.

telegram · zaihuapd · Jul 7, 18:01

**Background**: Claude Fable 5 is a public version of Anthropic's more powerful Claude Mythos model, which was initially withheld due to concerns over its ability to find software vulnerabilities. Anthropic has emphasized safety in its development, implementing measures like AI Safety Levels to prevent misuse. The model's relaunch comes after export controls were lifted, but Anthropic cited compute constraints for the limited access.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_Fable_5">Claude Fable 5</a></li>
<li><a href="https://support.claude.com/en/articles/8106465-our-approach-to-user-safety">Our Approach to User Safety | Claude Help Center</a></li>

</ul>
</details>

**Tags**: `#AI Safety`, `#Anthropic`, `#Claude`, `#Developer Tools`, `#Censorship`

---