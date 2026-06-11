---
layout: default
title: "Horizon Summary: 2026-06-11 (EN)"
date: 2026-06-11
lang: en
---

> From 85 items, 29 important content pieces were selected

---

1. [Homebrew 6.0.0 Released with Tap Trust and Linux Sandboxing](#item-1) ⭐️ 9.0/10
2. [Fully Autonomous Drones Have Killed Human Soldiers for the First Time](#item-2) ⭐️ 9.0/10
3. [Xiaomi Open-Sources MiMo Code, an AI Coding Agent](#item-3) ⭐️ 8.0/10
4. [AMD’s Flawed Fix: Replaces Signature with CRC-32 in RCE Vulnerability](#item-4) ⭐️ 8.0/10
5. [Pokémon Go Scans May Aid Military Drone Navigation](#item-5) ⭐️ 8.0/10
6. [Solar Generates More US Electricity Than Coal for First Time](#item-6) ⭐️ 8.0/10
7. [Anthropic Walks Back Policy That Could Have ‘Sabotaged’ AI Researchers Using Claude](#item-7) ⭐️ 8.0/10
8. [Google's Open-Weight DiffusionGemma LLM Achieves Fast Generation](#item-8) ⭐️ 8.0/10
9. [Claude Fable 5's Silent Interventions Against AI Competitors Spark Outrage](#item-9) ⭐️ 8.0/10
10. [First Impressions of Claude Fable 5](#item-10) ⭐️ 8.0/10
11. [Android 17 to Enforce Per-App Memory Limits, Killing Overly Demanding Apps](#item-11) ⭐️ 8.0/10
12. [Anthropic Releases Claude Fable 5 and Mythos 5 with Major Performance Leap](#item-12) ⭐️ 8.0/10
13. [Introducing DeltaDB: Capturing the Work Between Commits](#item-13) ⭐️ 7.0/10
14. [Waymo Launches $29.99 Premier Subscription for Priority Rides](#item-14) ⭐️ 7.0/10
15. [Lines of Code: A Misleading AI Productivity Metric](#item-15) ⭐️ 7.0/10
16. [Jeremy Howard Proposes Top AI Lab Should Not Use Best Model for Frontier Research](#item-16) ⭐️ 7.0/10
17. [Hugging Face Relaunches Paperswithcode.co for AI Benchmarks](#item-17) ⭐️ 7.0/10
18. [Parameter-Free Adaptive Video Tokenization via Temporal Redundancy](#item-18) ⭐️ 7.0/10
19. [Anthropic Seeks New Funding at $30-40 Billion Valuation](#item-19) ⭐️ 7.0/10
20. [Chinese Regulators Review Meta's Manus Acquisition, Co-founders Restricted from Travel](#item-20) ⭐️ 7.0/10
21. [macOS 27 Will Be Last to Fully Support Rosetta 2](#item-21) ⭐️ 7.0/10
22. [Instacart and OpenAI Launch In-Chat Grocery Checkout on ChatGPT](#item-22) ⭐️ 7.0/10
23. [uv 0.11.20 Released: Enhanced pip List and Hidden Upgrade Command](#item-23) ⭐️ 6.0/10
24. [Petition to Withdraw Canada's Bill C-22](#item-24) ⭐️ 6.0/10
25. [Open Reproduction of DeepSeek-R1 Releases Dataset and Training Recipe](#item-25) ⭐️ 6.0/10
26. [Datasette 1.0a33 extends ?_extra= to queries and rows](#item-26) ⭐️ 6.0/10
27. [Datasette-agent 0.2a0: Interactive Prompts and Save Query Tool](#item-27) ⭐️ 6.0/10
28. [Pyrecall: Open-Source Tool to Detect Catastrophic Forgetting in LLM Fine-Tuning](#item-28) ⭐️ 6.0/10
29. [ByteDance to Launch Second-Gen Doubao Phone in Q2 2026, Expanding AI Hardware Ecosystem](#item-29) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Homebrew 6.0.0 Released with Tap Trust and Linux Sandboxing](https://brew.sh/2026/06/11/homebrew-6.0.0/) ⭐️ 9.0/10

Homebrew 6.0.0 introduces a mandatory tap trust mechanism for third-party repositories, a faster internal JSON API by default, sandboxing for package builds on Linux, and preliminary support for macOS 27. These changes significantly enhance security by preventing untrusted code execution, improve performance for operations relying on the API, and extend Homebrew's compatibility to future macOS versions and Linux environments. The tap trust requires explicit user approval before running code from non-official taps; the JSON API is sharded by OS and architecture for speed; Linux sandboxing only applies during build/packaging, not at runtime.

hackernews · mikemcquaid · Jun 11, 13:24 · [Discussion](https://news.ycombinator.com/item?id=48490024)

**Background**: Homebrew is a popular open-source package manager for macOS and Linux. Taps are external repositories that extend Homebrew with additional software. Sandboxing confines build processes to limit potential harm from malicious or buggy packages. The JSON API is used by tools and scripts to query package information.

<details><summary>References</summary>
<ul>
<li><a href="https://brew.sh/2026/06/11/homebrew-6.0.0/">Homebrew: 6.0.0</a></li>
<li><a href="https://docs.brew.sh/Tap-Trust">Homebrew Documentation: Tap Trust</a></li>
<li><a href="https://github.com/Homebrew/brew/pull/19241">WIP: create lightweight internal JSON API by Rylan12 · Pull Request #19241 · Homebrew/brew</a></li>

</ul>
</details>

**Discussion**: Community reactions praised the maintainer's long-term dedication, noted the usefulness of Homebrew for bootstrapping immutable Linux distros like Bazzite, and shared personal comparisons with alternative tools such as mise and Nix, highlighting Homebrew's better macOS support and UX. Some users requested a cooldown mechanism for package updates to improve trust.

**Tags**: `#homebrew`, `#package-manager`, `#release`, `#macos`, `#linux`

---

<a id="item-2"></a>
## [Fully Autonomous Drones Have Killed Human Soldiers for the First Time](https://www.newscientist.com/article/2529849-fully-autonomous-drones-have-killed-human-soldiers-for-the-first-time/) ⭐️ 9.0/10

According to a New Scientist report, fully autonomous drones—operating without any human supervision—have been deployed to kill human soldiers, marking the first known lethal use of such systems. This event marks a paradigm shift in warfare, as machines now make life-and-death decisions, raising urgent ethical, legal, and humanitarian concerns and potentially spurring a global arms race in autonomous weapons. The drones are low-cost quadcopters equipped with AI-based target recognition and operate without any data link to human operators, reportedly killing everything within a designated area—a practice that likely violates international law due to its indiscriminate nature.

hackernews · deadgopher · Jun 10, 13:46 · [Discussion](https://news.ycombinator.com/item?id=48476214)

**Background**: Lethal autonomous weapon systems (LAWS), or 'killer robots,' are military systems that can independently search for and engage targets based on programmed constraints, unlike most drones that are remotely piloted. Precursors like loitering munitions have had limited autonomy, but full autonomy in targeting humans is unprecedented. The development of cheap AI chips and computer vision has enabled the creation of such systems.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Lethal_autonomous_weapon_system">Lethal autonomous weapon system</a></li>
<li><a href="https://disarmament.unoda.org/index.php/en/our-work/emerging-challenges/lethal-autonomous-weapon-systems">Lethal Autonomous Weapon Systems</a></li>

</ul>
</details>

**Discussion**: Commenters compare the drones to landmines and loitering munitions, emphasizing the low cost as a game-changer. Several highlight that indiscriminate targeting without human oversight constitutes a war crime, while others speculate about future misuse by terrorists. The tone is largely concerned about the erosion of legal and ethical boundaries.

**Tags**: `#autonomous weapons`, `#drones`, `#AI ethics`, `#warfare`, `#international law`

---

<a id="item-3"></a>
## [Xiaomi Open-Sources MiMo Code, an AI Coding Agent](https://mimo.xiaomi.com/mimocode) ⭐️ 8.0/10

Xiaomi has released MiMo Code as an open-source, terminal-native AI coding assistant, forked from OpenCode, with added features like persistent memory and self-improvement. This open-source release promotes vendor neutrality and reduces switching costs for developers, challenging closed-source alternatives like Claude Code and potentially reshaping the AI coding assistant landscape. MiMo Code retains multiple LLM provider support, TUI, LSP, MCP, and plugins from OpenCode, while introducing persistent memory, intelligent context management, subagent orchestration, goal-driven autonomous loops, compose workflows, and self-improvement via dream/distill.

hackernews · apeters · Jun 11, 14:27 · [Discussion](https://news.ycombinator.com/item?id=48490826)

**Background**: AI coding assistants like GitHub Copilot help developers write code by leveraging large language models. The open-source community advocates for open tools to prevent vendor lock-in. Xiaomi, primarily known for consumer electronics, has been expanding into AI with its MiMo model series. MiMo Code marks its entry into the coding harness arena, where a harness orchestrates LLM interactions for coding tasks.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/XiaomiMiMo/MiMo-Code">GitHub - XiaomiMiMo/MiMo-Code · GitHub</a></li>
<li><a href="https://mimo.xiaomi.com/mimocode/start">MiMo Code docs</a></li>

</ul>
</details>

**Discussion**: Users broadly welcome the open-source release, noting it counters the trend of closed-source coding tools. Commenters highlight Xiaomi's rapid AI progress, the tool's rich feature set, and the importance of treating LLMs as commodities to minimize switching costs.

**Tags**: `#open-source`, `#coding-assistant`, `#LLMs`, `#developer-tools`, `#Xiaomi`

---

<a id="item-4"></a>
## [AMD’s Flawed Fix: Replaces Signature with CRC-32 in RCE Vulnerability](https://mrbruh.com/amd2/) ⭐️ 8.0/10

A security researcher reported that AMD's patch for a remote code execution vulnerability merely switched to HTTPS and replaced cryptographic signature verification with a CRC-32 checksum, leaving systems vulnerable to server compromises. This exposes a critical failure in software supply chain security: without proper cryptographic signing, attackers who compromise AMD's update server can push malicious payloads, affecting millions of users. The vulnerability originally allowed remote code execution via MITM attacks; AMD's fix uses CRC-32, which is only for error detection and offers no protection against intentional data modification, and the disclosure process took 124 days.

hackernews · MrBruh · Jun 11, 16:03 · [Discussion](https://news.ycombinator.com/item?id=48492215)

**Background**: Remote code execution (RCE) vulnerabilities allow attackers to run arbitrary code on a target machine. Software updates should be cryptographically signed so the client can verify authenticity and integrity. CRC-32 is a simple algorithm for detecting accidental errors, not malicious alterations. HTTPS secures communication channels but does not guarantee the content itself if the server is hacked.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/CRC-32">CRC-32</a></li>

</ul>
</details>

**Discussion**: Commenters widely criticized AMD's inadequate fix, noting that CRC-32 is comically insufficient for security. Some argued that even without MITM, DNS poisoning could enable similar attacks, and HTTPS alone is not enough without signing. Many highlighted AMD's history of poor software quality.

**Tags**: `#security`, `#vulnerability`, `#AMD`, `#software-supply-chain`, `#crc32`

---

<a id="item-5"></a>
## [Pokémon Go Scans May Aid Military Drone Navigation](https://dronexl.co/2026/06/09/pokemon-go-scans-niantic-vantor-military-drone-navigation/) ⭐️ 8.0/10

A new report claims that Niantic's Pokémon Go player scans, collected through its Lightship Visual Positioning System, could be indirectly used by military contractor Vantor/Maxar for drone navigation, sparking privacy and ethical debates. This case highlights the dual-use nature of civilian data collection, showing how gaming data could be repurposed for military applications, and intensifies the debate over data ethics and informed consent. Niantic's VPS uses player scans to build 3D maps; the military contractor acknowledges minimal geographic overlap but reserves the right to use the data, while players often unknowingly contributed through optional in-game tasks.

hackernews · vrganj · Jun 11, 06:42 · [Discussion](https://news.ycombinator.com/item?id=48487029)

**Background**: Niantic developed the Lightship Visual Positioning System (VPS) to power augmented reality by creating detailed 3D maps from user-submitted scans in games like Pokémon Go. Players were incentivized to scan real-world locations, contributing to a database that enables precise positioning even in GPS-denied environments, which has potential military applications like drone navigation.

<details><summary>References</summary>
<ul>
<li><a href="https://nianticspatial.com/docs/nsdk/features/lightship_vps/">Visual Positioning System (VPS) | Niantic Spatial Platform</a></li>
<li><a href="https://www.nianticspatial.com/en/products/localize">Localize - Visual Positioning System for Real-World Positioning</a></li>
<li><a href="https://nianticlabs.com/news/lightshipsummit/?hl=en">Introducing the Lightship Visual Positioning System and Niantic AR ...</a></li>

</ul>
</details>

**Discussion**: Community members expressed skepticism, noting the geographic disconnect between player scans and war zones. Some users stopped scanning over privacy concerns, while others framed it as an ideological data rights battle. A suggestion was made to support open-source mapping like OpenStreetMap instead.

**Tags**: `#privacy`, `#military`, `#pokemon-go`, `#data-collection`, `#ethics`

---

<a id="item-6"></a>
## [Solar Generates More US Electricity Than Coal for First Time](https://www.theguardian.com/us-news/2026/jun/11/solar-energy-us-coal) ⭐️ 8.0/10

In a historic first, monthly electricity generation from solar power exceeded that of coal in the United States, according to the latest data. This milestone reflects the accelerating energy transition from fossil fuels to renewables, driven by declining solar costs and coal plant closures, and signals a major shift in the US power sector. The crossover was driven by both the rapid expansion of solar capacity and a long-term decline in coal generation, with many coal plants converted to natural gas; however, solar still accounts for a smaller share of total annual generation.

hackernews · neilfrndes · Jun 11, 16:10 · [Discussion](https://news.ycombinator.com/item?id=48492306)

**Background**: Coal has historically been a dominant source of US electricity, but its share has fallen from about 50% in the early 2000s to under 20% in recent years. Solar power, while still a smaller fraction, has grown exponentially due to steep cost reductions and supportive policies.

**Discussion**: Commenters debated the relative contributions of coal's decline versus solar's growth, with some pointing out that the crossover is largely due to coal plant closures and conversions to gas. Others highlighted solar's rapid expansion and future potential, while a few raised regulatory challenges for residential solar. The overall sentiment was cautiously optimistic, acknowledging progress but noting that much work remains.

**Tags**: `#renewable-energy`, `#solar-power`, `#energy-transition`, `#coal`, `#data-analysis`

---

<a id="item-7"></a>
## [Anthropic Walks Back Policy That Could Have ‘Sabotaged’ AI Researchers Using Claude](https://simonwillison.net/2026/Jun/11/anthropic-walks-back-policy/#atom-everything) ⭐️ 8.0/10

Anthropic apologized and announced it will make visible the previously secret safeguards in Claude Fable 5 that limited effectiveness on frontier LLM development requests. Flagged requests will now visibly fall back to Opus 4.8 or return a refusal reason. This reversal addresses a major transparency and trust issue, as invisible censorship in AI tools undermines user confidence and could hinder critical research. Community pressure has forced accountability. The changes roll out this week; API requests flagged for frontier LLM development will soon return explicit refusal reasons. Anthropic admitted the invisible safeguards were a wrong tradeoff made to ship quickly.

rss · Simon Willison · Jun 11, 03:45

**Background**: Claude is Anthropic's family of large language models, with Fable 5 being a recent version. AI safety measures often involve refusing certain categories of requests. 'Frontier LLM development' refers to building highly capable AI models, which Anthropic had classified as a sensitive area deserving reduced assistance. Invisible safeguards operate without user notification, resembling covert censorship.

**Tags**: `#AI ethics`, `#Anthropic`, `#transparency`, `#AI safety`, `#Claude`

---

<a id="item-8"></a>
## [Google's Open-Weight DiffusionGemma LLM Achieves Fast Generation](https://simonwillison.net/2026/Jun/10/diffusiongemma/#atom-everything) ⭐️ 8.0/10

Google released DiffusionGemma, an open-weight 26B parameter language model based on a diffusion architecture, capable of up to 4x faster text generation than autoregressive models, and made it available for free via NVIDIA's API and on Hugging Face. This release marks a significant step in efficient AI, as diffusion models generate tokens in parallel, drastically reducing latency and inference costs, while the open-weight license fosters broad community experimentation and integration into real-time applications. Built on a Mixture-of-Experts architecture, DiffusionGemma supports 256K context length, over 140 languages, and multimodal inputs like text, video, and images, but its 26B size still requires considerable GPU memory for local use, and fast generation may involve a trade-off with output quality.

rss · Simon Willison · Jun 10, 20:00

**Background**: Diffusion models, popularized in image synthesis (e.g., Stable Diffusion), iteratively denoise random patterns into coherent outputs. Unlike traditional autoregressive language models that generate tokens one at a time, diffusion models produce multiple tokens simultaneously, enabling higher throughput. Google first previewed a diffusion language model, Gemini Diffusion, in May 2025. The new model is part of the Gemma family, Google's series of open models, and it's served via NVIDIA NIM, a microservice platform optimized for deploying AI models.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/google/diffusiongemma-26B-A4B-it">google/diffusiongemma-26B-A4B-it - Hugging Face</a></li>
<li><a href="https://blog.google/innovation-and-ai/technology/developers-tools/diffusion-gemma-faster-text-generation/">DiffusionGemma: 4x faster text generation - Google Blog</a></li>
<li><a href="https://unsloth.ai/docs/models/diffusiongemma">DiffusionGemma - How to Run Locally | Unsloth Documentation</a></li>

</ul>
</details>

**Tags**: `#diffusion-models`, `#large-language-models`, `#open-source`, `#Gemma`, `#text-generation`

---

<a id="item-9"></a>
## [Claude Fable 5's Silent Interventions Against AI Competitors Spark Outrage](https://simonwillison.net/2026/Jun/10/if-claude-fable-stops-helping-you/#atom-everything) ⭐️ 8.0/10

Anthropic revealed in Claude Fable 5's system card that the model includes hidden safeguards that secretly reduce the quality of responses for users developing competing AI models, targeting tasks like pretraining pipelines or ML accelerator design; the policy was later retracted after widespread criticism. This undermines trust by showing that AI providers can silently manipulate outputs to hinder rivals, raising transparency and anti-competitive concerns that could stifle open AI research and innovation. The interventions are invisible to users, using techniques like prompt modification, steering vectors, or parameter-efficient fine-tuning without falling back to a different model. They affect only ~0.03% of traffic, concentrated in fewer than 0.1% of organizations, and are separate from visible safeguards for cybersecurity or biology.

rss · Simon Willison · Jun 10, 00:37

**Background**: AI system cards are transparency reports that document model capabilities, safety evaluations, and deployment decisions, issued by Anthropic for models like Claude. Techniques like steering vectors and PEFT allow fine-grained control over outputs without full retraining. Anthropic justified the interventions by concerns over recursive self-improvement accelerating AI development.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/system-cards">Model system cards - Anthropic</a></li>

</ul>
</details>

**Discussion**: Community reaction was overwhelmingly negative, with many researchers and developers expressing outrage over the lack of transparency and anti-competitive nature of the hidden restrictions, ultimately forcing Anthropic to rescind the policy.

**Tags**: `#AI safety`, `#Anthropic`, `#Claude`, `#competition`, `#industry policies`

---

<a id="item-10"></a>
## [First Impressions of Claude Fable 5](https://simonwillison.net/2026/Jun/9/claude-fable-5/#atom-everything) ⭐️ 8.0/10

Anthropic released Claude Fable 5, a frontier model with strict safety guardrails, priced at $10/$50 per million input/output tokens, a 1M token context window, and 128K max output tokens. Simon Willison's initial testing found it impressively capable, yet slow and expensive. This release continues the trend of frontier models with robust safety guardrails, offering a choice between the safer Fable and the unrestricted Mythos, while setting a new performance benchmark at double the cost of previous top models, impacting developers who need high-end AI capabilities. The model has a knowledge cutoff of January 2026, and its API includes new refusal detection with an optional fallback to another model. Despite its power, the guardrails trigger frequently, and the upgrade guide suggests few architectural changes from prior versions.

rss · Simon Willison · Jun 9, 23:59

**Background**: Claude is Anthropic's family of large language models, with Opus 4.8 as its previous flagship. Safety guardrails are classifiers that block harmful outputs. Simon Willison is a respected developer and open-source advocate, providing an early hands-on evaluation of this new model.

**Tags**: `#AI`, `#Claude`, `#LLM`, `#Anthropic`, `#Model Evaluation`

---

<a id="item-11"></a>
## [Android 17 to Enforce Per-App Memory Limits, Killing Overly Demanding Apps](https://android-developers.googleblog.com/2026/06/prioritizing-memory-efficiency-steps-for-android-17.html) ⭐️ 8.0/10

Starting with Android 17, the system will set a per-app memory cap based on device RAM, and processes that exceed this limit will be immediately killed without a stack trace. This change improves overall system stability and multitasking experience but requires developers to aggressively optimize memory usage to avoid unexpected app crashes. Google recommends using R8 optimization, low-memory image formats like RGB_565, LeakCanary for leak detection, onTrimMemory callbacks for releasing caches, and the new ProfilingManager API to collect heap dumps on out-of-memory events.

telegram · zaihuapd · Jun 11, 05:30

**Background**: Android has historically used a low-memory killer (LMK) to reclaim memory when the system runs low, but there were no per-process hard limits. Apps with excessive memory usage could still degrade overall performance. Android 17 introduces proactive memory capping, shifting more responsibility to developers to stay within defined limits and optimize memory usage.

**Tags**: `#Android`, `#memory management`, `#mobile development`, `#app performance`, `#Google`

---

<a id="item-12"></a>
## [Anthropic Releases Claude Fable 5 and Mythos 5 with Major Performance Leap](https://t.me/zaihuapd/41892) ⭐️ 8.0/10

Anthropic has launched Claude Fable 5, its most capable general-user model to date, alongside Claude Mythos 5, a restricted model for cyber defense partners. Fable 5 achieves top benchmarks in software engineering, knowledge work, vision, and science while costing less than half of the previous Mythos Preview. This release demonstrates Anthropic's push for state-of-the-art AI with built-in safety, offering high performance at reduced cost, which could broaden access to cutting-edge AI. Mythos 5's specialized cyber defense role reflects growing demand for AI in security applications. Fable 5 includes a classifier that switches to Opus 4.8 for sensitive topics like cybersecurity and biochemistry, affecting about 5% of sessions. Mythos 5 has partial restrictions lifted for vetted partners but remains unavailable to the public, continuing Anthropic's cautious approach with offensive capabilities.

telegram · zaihuapd · Jun 11, 07:45

**Background**: Anthropic's Claude models are released in tiers (Haiku, Sonnet, Opus). In 2026, a specialized 'Mythos' model was provided to select companies for finding software vulnerabilities, but was not publicly disclosed due to misuse risks. U.S. federal agencies later phased out Claude after Anthropic refused to remove contractual prohibitions against mass surveillance and autonomous weapons, leading to a DoD supply chain risk designation.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_Fable_5">Claude Fable 5</a></li>
<li><a href="https://en.wikipedia.org/wiki/Claude_Mythos">Claude Mythos</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Anthropic`, `#Claude`, `#Model Release`, `#Safety`

---

<a id="item-13"></a>
## [Introducing DeltaDB: Capturing the Work Between Commits](https://zed.dev/blog/introducing-deltadb) ⭐️ 7.0/10

A new tool called DeltaDB is introduced to capture the messy, often undocumented coding work that occurs between traditional Git commits, arguing that this is where real software creation happens. By preserving the in-between states, it could provide deeper insights into development processes, improve collaboration, and facilitate richer interactions with AI agents acting as team members. DeltaDB serializes and version-controls code states that developers normally discard, but this approach raises privacy concerns and may disrupt established workflows like rebasing.

hackernews · jeremy_k · Jun 11, 16:28 · [Discussion](https://news.ycombinator.com/item?id=48492533)

**Background**: Traditional Git tracks only finalized commits, often after developers have cleaned up their history through rebasing. The messy trial-and-error process that leads to those clean commits is usually lost, which the article argues is a missed opportunity for understanding software development.

**Discussion**: Commenters are divided: some value clean commit histories and see the intermediate mess as unhelpful, others worry about privacy and the loss of a thinking space, while a few see potential for AI collaboration but note that frequent auto-commits could achieve similar results.

**Tags**: `#version-control`, `#git`, `#collaboration`, `#software-engineering`, `#ai-agents`

---

<a id="item-14"></a>
## [Waymo Launches $29.99 Premier Subscription for Priority Rides](https://waymo.com/blog/2026/06/waymo-premier/) ⭐️ 7.0/10

Waymo has announced a new subscription service, Waymo Premier, costing $29.99 per month. It offers priority pickups and early access to Waymo's expansion into new cities, initially available to select riders in San Francisco, Los Angeles, and Phoenix. This move signals a shift toward subscription-based ride-hailing, akin to airline loyalty programs. It could incentivize frequent riders and business travelers to choose Waymo over competitors, deepening user lock-in. The service is initially available only to select riders in San Francisco, Los Angeles, and Phoenix. The 'Early Access' feature could lead to degraded service for locals in new cities if many Premier subscribers travel there, as noted by community members.

hackernews · boulos · Jun 11, 16:10 · [Discussion](https://news.ycombinator.com/item?id=48492304)

**Background**: Waymo, a subsidiary of Alphabet, operates a driverless ride-hailing service currently available in cities like San Francisco, Los Angeles, and Phoenix. Subscription models are common in transportation, such as airline loyalty programs and public transit passes, but are relatively new in ride-hailing. Waymo Premier aims to create a recurring revenue stream and foster customer loyalty similar to these models.

**Discussion**: Community reaction is mixed. Some users see value for frequent riders, especially those who can expense rides through cash-back incentives, likening it to airline loyalty programs. Others criticize the $30/month cost as high compared to public transit and worry that early access could degrade service for locals in new cities. Safety concerns were also raised, with one user desiring a way to perform evasive maneuvers during incidents.

**Tags**: `#waymo`, `#autonomous-vehicles`, `#subscription-service`, `#ride-hailing`, `#transportation`

---

<a id="item-15"></a>
## [Lines of Code: A Misleading AI Productivity Metric](https://curlewis.co.nz/posts/lines-of-code-got-a-better-publicist/) ⭐️ 7.0/10

The article criticizes the tech industry's fixation on using lines of code as a metric for AI-driven developer productivity, arguing it prioritizes marketing hype over genuine value. This challenges the validity of common claims that AI dramatically boosts productivity, impacting how companies assess AI tools, allocate resources, and make workforce decisions. Specific examples include a February 2026 OpenAI blog post touting a product with a million lines of code but no described user value, and a Microsoft executive's target of 1 million lines of code per engineer per month.

hackernews · RyeCombinator · Jun 11, 12:26 · [Discussion](https://news.ycombinator.com/item?id=48489402)

**Background**: Lines of code (LoC) has long been criticized in software engineering as a poor measure of productivity, as it doesn't reflect code quality, maintainability, or actual value delivered. Despite this, the rise of AI code generation has revived its use as a flashy metric to impress investors and stakeholders.

**Discussion**: Commenters largely agree that LoC is a misleading metric, noting that the reasons for rejecting it haven't changed. Many express concern that companies use AI-generated code quantities as an excuse for layoffs while masking quality issues. Some feel the hype around unmaintainable code volumes is waning, and a more pragmatic approach is emerging.

**Tags**: `#lines-of-code`, `#ai-code-generation`, `#developer-productivity`, `#software-engineering`, `#tech-hype`

---

<a id="item-16"></a>
## [Jeremy Howard Proposes Top AI Lab Should Not Use Best Model for Frontier Research](https://simonwillison.net/2026/Jun/10/jeremy-howard/#atom-everything) ⭐️ 7.0/10

Jeremy Howard proposed that the lab with the top-ranked AI model should not use it for frontier AI research, while others should have access. He criticized Anthropic for doing the opposite, which he deems unsafe. The proposal aims to prevent dangerous power imbalances and uncontrolled recursive self-improvement, a key concern in AI safety. It directly challenges the approach of major labs like Anthropic. Howard himself does not advocate slowing recursive self-improvement; he favors democratization. He notes that Anthropic claims it will sabotage others who try to access its model for frontier research.

rss · Simon Willison · Jun 10, 15:23

**Background**: Recursive self-improvement refers to AI systems enhancing their own capabilities, potentially leading to superintelligence. Frontier AI models are the most advanced, often closed-source. Anthropic, known for its safety focus, has been criticized here for using its own top model for frontier research, contradicting safety principles.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Recursive_self-improvement">Recursive self-improvement</a></li>
<li><a href="https://en.wikipedia.org/wiki/Frontier_AI">Frontier AI</a></li>

</ul>
</details>

**Tags**: `#AI safety`, `#AI governance`, `#recursive self-improvement`, `#Anthropic`, `#AI policy`

---

<a id="item-17"></a>
## [Hugging Face Relaunches Paperswithcode.co for AI Benchmarks](https://www.reddit.com/r/MachineLearning/comments/1u1wq0a/introducing_papers_without_code_p/) ⭐️ 7.0/10

Hugging Face's open-source team has relaunched paperswithcode.co as an automated platform that parses arXiv and Hugging Face papers to generate state-of-the-art leaderboards with interactive scatter plots and tables, and now includes optional evaluations of closed-source models like GPT-5.5 and Mythos 5. This tool centralizes and automates the tracking of AI progress across many domains, making it easier for researchers to compare open and closed models, and aiding transparency in an era where many top-performing models are proprietary. The platform supports submitting any source (blog posts, etc.) as "papers," and closed-source evaluations are tagged accordingly; users can toggle closed-source results off in settings to view only open-model leaderboards.

reddit · r/MachineLearning · /u/NielsRogge · Jun 10, 08:58

**Background**: Paperswithcode.co was originally a community resource linking papers to code, but it declined after being acquired. Hugging Face revived it with automated parsing. BrowseComp is a benchmark by OpenAI that tests web browsing agents, consisting of 1,266 tasks from April 2025.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2504.12516">A Simple Yet Challenging Benchmark for Browsing Agents - arXiv</a></li>

</ul>
</details>

**Tags**: `#machine learning`, `#benchmarks`, `#leaderboards`, `#research tools`, `#open source`

---

<a id="item-18"></a>
## [Parameter-Free Adaptive Video Tokenization via Temporal Redundancy](https://www.reddit.com/r/MachineLearning/comments/1u2u9bb/adaptive_tokenisation_via_temporal_redundancy/) ⭐️ 7.0/10

The paper proposes a new method that identifies and drops redundant spatial positions in video tokenization by thresholding per-position temporal L1 differences in a frozen latent space, without extra computation. This enables dynamic token allocation that adapts to visual complexity, reducing computation in static scenes while preserving detail in dynamic ones, and offers significant speedups over existing adaptive tokenizers. The dropped positions are reconstructed by a lightweight Latent Inpainting Transformer (LIT) with factorized spatial-temporal attention, and the pipeline achieves a 31x speedup over the continuous adaptive baseline (ElasticTok-CV) and 2x over the discrete baseline (InfoTok).

reddit · r/MachineLearning · /u/chhaya_35 · Jun 11, 09:32

**Background**: Video tokenization converts video frames into a sequence of latent tokens for processing by models like transformers. Adaptive tokenization aims to assign more tokens to complex regions and fewer to simple ones, reducing overall computation. Prior methods require extra networks or full decoding passes to decide token allocation, while this work leverages inherent temporal redundancy in the latent space of a frozen tokenizer.

**Tags**: `#video-tokenization`, `#adaptive-tokenization`, `#temporal-redundancy`, `#latent-representations`, `#machine-learning`

---

<a id="item-19"></a>
## [Anthropic Seeks New Funding at $30-40 Billion Valuation](https://t.me/zaihuapd/41888) ⭐️ 7.0/10

Anthropic, the company behind the Claude conversational AI, is in discussions with investors for a new funding round that could value it at $30 to $40 billion, roughly double its valuation from earlier this year. This funding round underscores the intensifying capital race in the AI industry, as major players like Anthropic and OpenAI both seek massive investments to fuel development, signaling strong investor confidence and the high cost of advancing AI technology. Anthropic generates revenue primarily through access to its Claude AI, while OpenAI is concurrently raising $5 to $7 billion at a valuation near $150 billion, according to The Information.

telegram · zaihuapd · Jun 11, 04:45

**Background**: Anthropic is an AI safety-focused company founded by former OpenAI employees, known for its Claude family of conversational AI models that compete with OpenAI's ChatGPT. Founded in 2021, it has quickly become a major player in the generative AI space, emphasizing ethical and reliable AI development.

**Tags**: `#AI`, `#funding`, `#Anthropic`, `#Claude`, `#OpenAI`

---

<a id="item-20"></a>
## [Chinese Regulators Review Meta's Manus Acquisition, Co-founders Restricted from Travel](https://t.me/zaihuapd/41895) ⭐️ 7.0/10

Chinese regulators are scrutinizing Meta's acquisition of AI startup Manus for potential violations of investment rules, and have restricted co-founders Xiao Hong and Ji Yichao from leaving the country during the review. This underscores China's tightening grip on foreign tech acquisitions amid geopolitical rivalry, which could chill cross-border AI investments and affect the global AI agent landscape. The co-founders met with the National Development and Reform Commission this month and were told they cannot exit China but can travel domestically; the deal was announced last December with an undisclosed amount.

telegram · zaihuapd · Jun 11, 10:00

**Background**: Manus AI is a general-purpose autonomous AI agent developed by Butterfly Effect, a company based in Singapore. AI agents are designed to independently execute complex tasks like research and coding. Meta is a US social media and technology conglomerate expanding into AI. China's foreign investment rules require regulatory review for acquisitions involving sensitive technologies to protect national interests.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Manus_AI">Manus AI</a></li>
<li><a href="https://grokipedia.com/page/Manus_AI">Manus AI</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Meta`, `#Mergers & Acquisitions`, `#Regulation`, `#China`

---

<a id="item-21"></a>
## [macOS 27 Will Be Last to Fully Support Rosetta 2](https://www.macrumors.com/2026/06/10/macos-golden-gate-last-to-support-intel-apps/) ⭐️ 7.0/10

Apple announced that macOS 27 Golden Gate will be the final version to fully support Rosetta 2, the binary translator for Intel Mac apps on Apple Silicon. From macOS 28 onward, Rosetta 2 will only be available for a limited set of legacy Intel games, and Intel-based Macs will no longer receive system upgrades. This marks a decisive step in Apple's transition to Apple Silicon, signaling the near end of seamless Intel app compatibility. Developers and users still dependent on Intel-only software must migrate to Universal or native Apple Silicon versions before upgrading past macOS 27. The remaining Rosetta 2 support in macOS 28 will be restricted to unmaintained games that rely on Intel frameworks, with no general Intel app compatibility. macOS 27 itself already drops all support for Intel Macs, making it the last upgradeable version for those machines.

telegram · zaihuapd · Jun 11, 10:45

**Background**: Rosetta 2 is a dynamic binary translator introduced in macOS Big Sur (2020) that enables Apple Silicon (ARM-based) Macs to run apps written for Intel x86_64 processors. Apple started its transition from Intel to custom Apple Silicon in 2020 and completed the Mac lineup migration by 2023. The original Rosetta (2006–2011) served a similar purpose during the PowerPC‑to‑Intel switch but was later removed. The phaseout of Rosetta 2 parallels that earlier transition and marks the final end of Intel-native app support on Macs.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Rosetta_(software)">Rosetta (software)</a></li>
<li><a href="https://www.reddit.com/r/apple/comments/1r6omno/macos_264_is_warning_that_rosetta_2_is_going_away/">macOS 26.4 is warning that Rosetta 2 is going away — what apps are you ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Apple_silicon">Apple silicon</a></li>

</ul>
</details>

**Discussion**: On Reddit, users are noting notifications about Rosetta 2's impending removal, sparking discussions about which apps still rely on it. While some view the phaseout as expected, others express concern over legacy software compatibility and wonder how many Mac users are still running Intel-only applications.

**Tags**: `#macOS`, `#Apple Silicon`, `#Rosetta 2`, `#Software Compatibility`, `#Deprecation`

---

<a id="item-22"></a>
## [Instacart and OpenAI Launch In-Chat Grocery Checkout on ChatGPT](https://t.me/zaihuapd/41900) ⭐️ 7.0/10

On December 8, 2025, Instacart and OpenAI launched an integrated grocery shopping feature within ChatGPT, allowing users to browse products, build a cart, and complete checkout for delivery without leaving the chat interface. This marks a significant step in merging conversational AI with e-commerce, potentially transforming how consumers shop by enabling frictionless transactions within AI assistants, and setting a precedent for other platforms. The feature leverages Instacart's real-time delivery network and OpenAI's advanced models, but specifics about supported regions or model versions are not disclosed.

telegram · zaihuapd · Jun 11, 13:15

**Background**: Instacart is a leading North American online grocery delivery platform, offering same-day delivery from various retailers. OpenAI's ChatGPT is a conversational AI that has been integrating plugins and tools to extend functionality. This integration is part of a broader trend where AI assistants become commerce platforms.

**Tags**: `#AI`, `#e-commerce`, `#conversational AI`, `#ChatGPT`, `#Instacart`

---

<a id="item-23"></a>
## [uv 0.11.20 Released: Enhanced pip List and Hidden Upgrade Command](https://github.com/astral-sh/uv/releases/tag/0.11.20) ⭐️ 6.0/10

uv 0.11.20, released on 2026-06-10, introduces --find-links support for uv pip list, a new hidden uv upgrade command (preview), ICF optimization for smaller macOS binaries, and faster discovery of large workspaces. These enhancements make uv a more complete pip replacement, improve the user experience for dependency management, and reduce resource usage, benefiting Python developers and CI/CD pipelines. The hidden uv upgrade command rejects Git revisions for now; uv export can now emit --emit-index-url and --emit-find-links; bug fixes include resolver error handling to avoid stack overflows and better symlink handling during cache operations.

github · github-actions[bot] · Jun 10, 17:21

**Background**: uv is a fast Python package installer and resolver written in Rust, developed by Astral (the creators of Ruff). It aims to replace pip, pip-tools, and virtualenv with a single tool. Identical Code Folding (ICF) is a linker optimization that merges identical functions to reduce binary size, often used in release builds.

<details><summary>References</summary>
<ul>
<li><a href="https://learn.microsoft.com/en-us/cpp/build/reference/opt-optimizations?view=msvc-170">/OPT (Optimizations) | Microsoft Learn</a></li>

</ul>
</details>

**Tags**: `#uv`, `#python`, `#packaging`, `#release`, `#tool`

---

<a id="item-24"></a>
## [Petition to Withdraw Canada's Bill C-22](https://www.ourcommons.ca/petitions/en/Petition/Sign/e-7416) ⭐️ 6.0/10

A petition on the official Canadian Parliament website urges the government to withdraw Bill C-22, citing privacy infringements. At the time of discussion, the House of Commons committee on public safety and national security (SECU) was conducting a clause-by-clause review of the bill, with a possible final vote on amendments. The opposition to Bill C-22 highlights mounting concerns over government surveillance and its chilling effect on Canada's tech sector, as well as the broader trend of eroding privacy protections. Related legislation like C-34 intensifies fears that Canada is moving toward a no-privacy regime, potentially harming innovation and civil liberties. The petition (e-7416) was launched in April 2025 on the official parliamentary petitions platform. During the HackerNews discussion, commenter EmbarrassedHelp noted that the SECU committee was holding a meeting that same day to review the bill clause by clause and vote on amendments, which could mark the final stage before the bill advances.

hackernews · hmokiguess · Jun 11, 15:37 · [Discussion](https://news.ycombinator.com/item?id=48491830)

**Background**: Bill C-22 is a legislative proposal before the Parliament of Canada that, according to critics, would expand government surveillance capabilities and reduce privacy protections. Bill C-34 is a separate but related bill that some argue would completely dismantle digital privacy. E-petitions in Canada allow citizens to formally petition the government, and the SECU committee is responsible for reviewing legislation pertaining to national security and public safety.

**Discussion**: The HackerNews community is largely critical of Bill C-22, viewing it as part of a broader erosion of privacy. Commenters share resources like Michael Geist's analysis and live parliamentary coverage, urging others to pay attention and make noise, though most are skeptical that the petition will alter the legislative outcome. Some express resignation about Canadian politics, noting that both major parties support such measures.

**Tags**: `#privacy`, `#canada`, `#policy`, `#tech-sector`, `#legislation`

---

<a id="item-25"></a>
## [Open Reproduction of DeepSeek-R1 Releases Dataset and Training Recipe](https://github.com/huggingface/open-r1) ⭐️ 6.0/10

The Hugging Face Open-R1 project has released Mixture-of-Thoughts, a curated reasoning dataset of 350,000 verified traces distilled from DeepSeek-R1, along with a training recipe to replicate DeepSeek-R1-Distill-Qwen-7B. Open reproduction efforts promote transparency and allow the community to study and build upon state-of-the-art reasoning models. However, the project's age limits its current relevance compared to newer alternatives. The dataset spans mathematics, coding, and science, aiming to teach step-by-step reasoning. The training recipe targets a 7B model, but the repository has not been updated in over a year.

hackernews · yogthos · Jun 11, 13:14 · [Discussion](https://news.ycombinator.com/item?id=48489917)

**Background**: DeepSeek-R1, launched in January 2025 by Chinese AI company DeepSeek, is an open-weight reasoning model that achieved performance comparable to OpenAI’s o1 at a significantly lower cost using techniques like mixture of experts. Its release triggered numerous open reproduction initiatives to replicate its capabilities.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek">DeepSeek</a></li>

</ul>
</details>

**Discussion**: Users highlight that the project is outdated and recommend newer efforts like OpenThoughts and OLMo. Some inquire about current training costs, while others dismiss it as too old to be useful.

**Tags**: `#LLM`, `#reasoning`, `#open-source`, `#dataset`, `#DeepSeek-R1`

---

<a id="item-26"></a>
## [Datasette 1.0a33 extends ?_extra= to queries and rows](https://simonwillison.net/2026/Jun/11/datasette/#atom-everything) ⭐️ 6.0/10

Datasette 1.0a33 extends the `?_extra=` URL parameter pattern, previously available for tables, to also work with queries and rows, allowing API users to request additional metadata in JSON responses. This enhancement makes the Datasette JSON API more flexible and self-describing, enabling richer client applications and a smoother developer experience, and marks progress toward the stable 1.0 release. The `?_extra=` parameter accepts comma-separated extras like `columns`, `count`, `database`, etc.; the release includes documentation and a custom API explorer tool built with AI assistance to demonstrate the feature.

rss · Simon Willison · Jun 11, 15:26

**Background**: Datasette is an open-source tool for publishing and exploring data, providing a JSON API for SQLite databases. The `?_extra=` mechanism was introduced in version 1.0a3 to let API consumers request additional metadata beyond the standard response, reducing the need for multiple requests. The 1.0a33 alpha release extends this capability to query and row endpoints, unifying the API surface.

**Tags**: `#datasette`, `#api`, `#json`, `#release`, `#alpha`

---

<a id="item-27"></a>
## [Datasette-agent 0.2a0: Interactive Prompts and Save Query Tool](https://simonwillison.net/2026/Jun/10/datasette-agent/#atom-everything) ⭐️ 6.0/10

Datasette-agent 0.2a0 introduces interactive user prompts during tool execution through a new context.ask_user() method, enabling suspended conversations to persist across server restarts. It also adds a built-in save_query tool that saves SQL as Datasette stored queries with required human approval. This update enhances human-agent collaboration by allowing users to intervene mid-execution, and the persistence feature makes agent workflows more robust. The save_query tool integrates agent-generated SQL directly into Datasette's query management. The ask_user() method supports yes/no, multiple-choice, and free-text questions, and stores unanswered state so suspended conversations survive server restarts. Tools re-execute from the beginning upon answer, so side effects should follow ask_user() calls. The save_query tool requires explicit human approval, displaying the full SQL and proposed metadata.

rss · Simon Willison · Jun 10, 23:57

**Background**: Datasette is an open-source tool for exploring and publishing structured data using SQLite. Datasette-agent is an experimental framework that enables LLM-powered agents to interact with Datasette instances, performing tasks like querying and manipulating data. This release adds human-in-the-loop capabilities, allowing tools to pause and request user input mid-execution, and introduces the ability to save agent-generated queries.

**Tags**: `#datasette`, `#agent`, `#llm`, `#tool-use`, `#interactive`

---

<a id="item-28"></a>
## [Pyrecall: Open-Source Tool to Detect Catastrophic Forgetting in LLM Fine-Tuning](https://www.reddit.com/r/MachineLearning/comments/1u2hjye/pyrecall_open_source_tool_for_detecting/) ⭐️ 6.0/10

Pyrecall v0.1.0, an open-source Python tool, has been released to detect catastrophic forgetting during LLM fine-tuning by comparing skill score snapshots before and after training, and enabling LoRA adapter rollbacks. Catastrophic forgetting is a persistent challenge in continual learning for LLMs; Pyrecall provides a practical, local solution without external APIs, potentially saving time and resources for practitioners. The tool is at v0.1.0, uses MIT license, and is installable via pip. It snapshots skill scores, flags regressions, and rolls back LoRA adapters by name. The author seeks feedback on benchmark design.

reddit · r/MachineLearning · /u/Level_Frosting_7950 · Jun 10, 22:49

**Background**: Catastrophic forgetting occurs when a model loses previously learned skills after fine-tuning on new tasks. LLMs are often fine-tuned for domain adaptation, but this can degrade performance on earlier tasks. Techniques like LoRA (Low-Rank Adaptation) allow parameter-efficient fine-tuning, but forgetting can still happen. Benchmark suites are used to evaluate model skills across diverse tasks.

**Tags**: `#LLM fine-tuning`, `#catastrophic forgetting`, `#continual learning`, `#open-source tool`, `#Python`

---

<a id="item-29"></a>
## [ByteDance to Launch Second-Gen Doubao Phone in Q2 2026, Expanding AI Hardware Ecosystem](https://t.me/zaihuapd/41891) ⭐️ 6.0/10

ByteDance plans to release its second-generation Doubao smartphone in Q2 2026, manufactured by ZTE nubia, and is also developing AI glasses and earbuds as part of a broader AI hardware lineup. The company is actively negotiating app permissions with platforms like Meituan and WeChat to overcome the first-generation device's restrictions. This move signals ByteDance's deepening commitment to AI-driven consumer hardware, seeking to integrate its AI assistant directly into devices and forge alliances with other phone brands. It could challenge traditional app ecosystems and push AI-native interfaces into the mainstream. The first-generation Doubao phone used a mobile-optimized version of UI-TARS 2.0, and the new model will continue collaborations with ZTE. ByteDance is also exploring embedding its AI entry points in phones from Transsion and Meizu, while facing ongoing negotiations for deep system permissions.

telegram · zaihuapd · Jun 11, 07:00

**Background**: ByteDance, known for TikTok and Douyin, ventured into AI hardware with the first Doubao phone, which integrated its Doubao AI assistant natively. However, major Chinese internet platforms blocked the device from accessing their services, limiting its functionality. The new strategy involves securing app permissions and partnering with other manufacturers.

<details><summary>References</summary>
<ul>
<li><a href="https://grokipedia.com/page/Doubao_smartphone">Doubao (smartphone)</a></li>

</ul>
</details>

**Tags**: `#ByteDance`, `#AI hardware`, `#smartphone`, `#AI glasses`, `#consumer electronics`

---