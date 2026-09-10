---
layout: default
title: "Horizon Summary: 2026-09-10 (EN)"
date: 2026-09-10
lang: en
---

> From 59 items, 22 important content pieces were selected

---

1. [Calif Research demos WeWorm, an AI-built zero-click worm spreading via WeChat calls](#item-1) ⭐️ 9.0/10
2. [OpenAI Claims Navier–Stokes Millennium Prize Solution, Sparking Priority Fight](#item-2) ⭐️ 9.0/10
3. [Microsoft Designates Rust a Tier-1 Language](#item-3) ⭐️ 8.0/10
4. [Can researchers trust OpenAI with unpublished math ideas?](#item-4) ⭐️ 8.0/10
5. [DeepSeek Releases V4.1 Flash: 552B MoE With Aggressive Cache Pricing](#item-5) ⭐️ 8.0/10
6. [Quoting Terence Tao](#item-6) ⭐️ 8.0/10
7. [DeepSeek ships MIT-licensed Harness agent and opens V4-Pro-0813 weights](#item-7) ⭐️ 8.0/10
8. [Essay Argues Software Development Culture Drives Developers Insane](#item-8) ⭐️ 7.0/10
9. [Cognition launches SWE-2 coding model, claims parity with Fable 5.1](#item-9) ⭐️ 7.0/10
10. [NASA Mars False-Color Trick Now Reveals Earth's Rock Art](#item-10) ⭐️ 7.0/10
11. [Shopify Migrates Its Mobile App from React Native Back to Native](#item-11) ⭐️ 7.0/10
12. [Brown University Paper: Silicon Valley Is Reshaping the Military-Industrial Complex](#item-12) ⭐️ 7.0/10
13. [Fly connectome fails to learn Pong, audit exposes tooling bugs](#item-13) ⭐️ 7.0/10
14. [Apple unveils iPhone 18 Pro, foldable iPhone Duo, Watch S12/Ultra 4 and AirPods 5](#item-14) ⭐️ 7.0/10
15. [Ant International, Visa and Mastercard Team Up on AI Agent Payment Standard](#item-15) ⭐️ 7.0/10
16. [China AI Chip Prices Jump 20-50% as HBM Shortage Bites](#item-16) ⭐️ 7.0/10
17. [Moonshot AI (Kimi) confidentially files for Hong Kong IPO at $50B pre-money valuation](#item-17) ⭐️ 7.0/10
18. [Tencent Hunyuan open-sources AuK audio editing model with 4-step AuK-Flash variant](#item-18) ⭐️ 7.0/10
19. [PlanetScale launches Neki, a closed-source sharded Postgres](#item-19) ⭐️ 6.0/10
20. [OpenAI Ships ChatGPT Images 2.5 with Two New API Model IDs](#item-20) ⭐️ 6.0/10
21. [348M model beats GPT-3 175B on arithmetic via column-wise work](#item-21) ⭐️ 6.0/10
22. [Sante's 83.83 on DiagnosisArena-MCQ only measures answer selection](#item-22) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Calif Research demos WeWorm, an AI-built zero-click worm spreading via WeChat calls](https://simonwillison.net/2026/Sep/10/calif-research/) ⭐️ 9.0/10

Calif Research has released a demo of WeWorm, which it describes as the first zero-click worm that spreads through WeChat voice calls on both iOS and Android. The team says that working with AI it found the bug and wrote the first remote code execution (RCE) exploit in about two days, then built the worm in roughly one more week. The claim suggests AI has dramatically compressed the time and team size needed to develop advanced offensive tooling — work that previously took a larger team months. Because WeChat has well over a billion users and zero-click attacks require no victim interaction, the demo raises serious questions about platform defense and the dual-use risks of AI-assisted vulnerability research. According to Calif Research, the victim does not need to answer the call or interact with the phone at all, and even if they do answer, they hear nothing while the exploit still succeeds. Reports describe the underlying flaw as a memory-corruption issue in WeChat's VoIP call handling, and the company stresses this is a demo and proof-of-concept rather than a verified campaign in the wild.

rss · Simon Willison · Sep 10, 00:56

**Background**: A zero-click attack executes automatically when a vulnerable application processes malicious input, so it relies on a software flaw rather than tricking the user into clicking or tapping something. WeChat is Tencent's messaging and calling app, used by more than a billion people, and its voice-call feature is handled by native code, which is a common target for memory-corruption exploits. A worm is malware that copies and spreads itself to new victims without user action, which is what makes this proof-of-concept notable. AI-assisted exploit development refers to using large language models to speed up reverse engineering, vulnerability discovery and exploit writing.

<details><summary>References</summary>
<ul>
<li><a href="https://cybersecuritynews.com/weworm-first-0-click-worm/">WeWorm - First 0-Click Worm Spreading Through WeChat Calls Across iOS ...</a></li>
<li><a href="https://www.techtimes.com/articles/327153/20260910/wechat-zero-click-worm-built-ai-days-voip-bug-put-billion-accounts-risk.htm">WeChat Zero-Click Worm Built by AI in Days: VoIP Bug Put Billion ...</a></li>
<li><a href="https://blog.calif.io/p/weworm">WeWorm - Calif Newsletter</a></li>

</ul>
</details>

**Tags**: `#security`, `#AI`, `#zero-click exploit`, `#WeChat`, `#RCE`

---

<a id="item-2"></a>
## [OpenAI Claims Navier–Stokes Millennium Prize Solution, Sparking Priority Fight](https://simonwillison.net/2026/Sep/8/on-navier-stokes/) ⭐️ 9.0/10

On September 8, 2026, OpenAI announced that an unreleased internal model, run as a swarm of roughly 10,000 agents, produced a counterexample disproving global smoothness for the three-dimensional Navier–Stokes equations, together with a Lean formalization verified by GPT-6 Astra. The claim, which OpenAI says it will not submit for the $1,000,000 Clay Millennium Prize, is unverified by the Clay Institute or outside mathematicians and is entangled in a priority dispute with NYU professor Tristan Buckmaster and Anthropic employee Levent Alpöge, who had derived closely related results on the Euler equations. If the counterexample survives external scrutiny, it would be the first Millennium Prize Problem resolved with substantial AI involvement, reshaping expectations about machine-driven mathematical discovery and about how credit and authorship are assigned when AI systems and competing labs race on the same open problem. It also drags unresolved questions about training-data provenance, user-session confidentiality, and research ethics into the center of a flagship mathematical result. According to OpenAI, the agents ran for about 88 hours, sent 4.9 million messages and consumed roughly 300 billion output tokens across all attempted problems (2.7 million messages and ~130 billion output tokens for Navier–Stokes alone), which at public API prices for GPT-6 Astra would cost about $15 million; Lean formalization and verification took another 17 hours. Buckmaster alleges that OpenAI's first prompt was sent only after news of his and Alpöge's August 15 breakthrough reached the company, and that he never received a clear answer about whether their Codex sessions were used in training; OpenAI reportedly offered to delay publication or let Buckmaster author the paper, but said Alpöge would be excluded as a co-author because he works for rival Anthropic. The method reportedly builds on a 2023 blowup construction by Diego Córdoba and Luis Martínez-Zoroa for related fluid equations.

rss · Simon Willison · Sep 8, 23:55

**Background**: The Navier–Stokes equations are the partial differential equations describing how fluids move; while they are used constantly in engineering and simulation, mathematicians still lack a complete analytical understanding of their solutions, and turbulence in particular remains unsolved. In 2000 the Clay Mathematics Institute named the existence and smoothness question — whether smooth solutions always exist globally in three dimensions, or whether they can break down — one of seven Millennium Prize Problems, each carrying a $1,000,000 award. The only Millennium problem officially solved so far is the Poincaré conjecture, for which Grigori Perelman declined the prize in 2010; Lean is an interactive proof assistant that lets a proof be checked mechanically, which is why OpenAI's Lean formalization is central to its claim.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Navier-Stokes_existence_and_smoothness_problem">Navier-Stokes existence and smoothness problem</a></li>
<li><a href="https://en.wikipedia.org/wiki/Millennium_Prize_Problems">Millennium Prize Problems</a></li>
<li><a href="https://www.claymath.org/millennium-problems/">The Millennium Prize Problems - Clay Mathematics Institute</a></li>

</ul>
</details>

**Tags**: `#AI for Mathematics`, `#Navier-Stokes`, `#OpenAI`, `#Millennium Prize Problems`, `#Research Ethics`

---

<a id="item-3"></a>
## [Microsoft Designates Rust a Tier-1 Language](https://rustfoundation.org/media/guest-post-rust-is-tier-1-language-at-microsoft/) ⭐️ 8.0/10

In a guest post published on the Rust Foundation's website, Microsoft officially designated Rust as a "tier-1" language, meaning internal teams now get a paved path from local development to production, including secure toolchain builds, productive developer tooling, quality workflows, deep platform integration and compliance support. The designation places Rust alongside Microsoft's established core languages such as C# and C++. This is a milestone for Rust's maturity: every major OS vendor that also maintains C and C++ tooling has now diversified its systems-programming language options for greenfield development. Because memory-safety bugs make up roughly 70% of the CVEs Microsoft tracks, elevating Rust gives the company a first-class tool for reducing a huge class of exploitable Windows and Azure vulnerabilities. Tier-1 status implies dedicated support and integration in Microsoft's own development tools, and it is the first public confirmation of the long-rumored MSVC integration for Rust. Practically, building Rust on Windows still depends on Microsoft's C++ build tools — Visual Studio Build Tools 2022 with the "Desktop development with C++" workload — which supply link.exe, the Windows SDK and the UCRT. Note that the widely cited goal of converting 1 billion lines of C to Rust by 2030 originated with a Microsoft hiring manager's vision-casting rather than a formal company commitment.

hackernews · mmastrac · Sep 10, 13:39 · [Discussion](https://news.ycombinator.com/item?id=49643546)

**Background**: Rust is a systems programming language designed to guarantee memory safety and thread safety at compile time without a garbage collector, which makes it attractive for the low-level code that operating systems and browsers are built from. Microsoft has historically built Windows and much of its cloud stack in C, C++ and C#, languages where manual memory management is a leading source of security bugs. "Tier-1" is an internal engineering classification: a tier-1 language is one Microsoft is willing to support end-to-end, from the toolchain and build infrastructure to compliance and long-term maintenance. MSVC is Microsoft's Visual C++ compiler toolchain, and integration with it matters because it is the native toolchain most Windows developers already have installed.

<details><summary>References</summary>
<ul>
<li><a href="https://rustfoundation.org/media/guest-post-rust-is-tier-1-language-at-microsoft/">Guest Post: Rust Is Tier-1 Language at Microsoft</a></li>
<li><a href="https://learn.microsoft.com/en-us/windows/dev-environment/rust/setup">Set up your dev environment on Windows for Rust | Microsoft Learn</a></li>

</ul>
</details>

**Discussion**: The Hacker News thread (roughly 503 points and 277 comments) is broadly positive, with commenters framing the move as proof that Rust is no longer a fast-moving "fledgling" language but a serious competitor to C++ and C#, and noting that newer "better C/C++" alternatives like Zig and Odin still have more rough edges. Several users linked Microsoft's reported ambition to convert 1 billion lines of C to Rust by 2030 via automated tooling at a pace of "1 engineer, 1 month, 1 million lines of code," along with DARPA-funded work across six teams on automated C-to-Rust translation, and welcomed finally getting public news about MSVC integration for Rust. Skepticism surfaced too, including a complaint that Windows' built-in Weather app consumes more than 1GB of RAM and criticism of Windows 11's aggressive retirement of legacy PC hardware.

**Tags**: `#rust`, `#microsoft`, `#systems-programming`, `#programming-languages`, `#msvc`

---

<a id="item-4"></a>
## [Can researchers trust OpenAI with unpublished math ideas?](https://mathstodon.xyz/@andreasthom/117240535270608201) ⭐️ 8.0/10

A Hacker News thread (365 points, 458 comments) is debating whether mathematicians can safely share unpublished ideas with OpenAI, following accusations that the company used ideas from collaborative chats with its models and then published related results without crediting the researchers. The discussion was sparked by a Mathstodon post by @andreasthom that links to related threads on X and Bluesky. This touches the core of trust between frontier AI labs and the academic community: if researchers believe their unpublished work can be absorbed into a model and later surfaced as the lab's own result, many may stop collaborating or sharing altogether. It also raises broader questions about consent, data-use policies, and attribution norms as AI systems increasingly participate in discovery. Commenters point out that two claims can be simultaneously true: a massive model pretrained on chat data may memorize enough to improve its latent representations, while reinforcement learning on verifiable math with large compute could independently discover techniques unrelated to any specific shared idea. Notably, no public evidence has been presented that OpenAI actually trained on those specific conversations, and OpenAI is said to offer free access to roughly 100,000 researchers — which itself expands the volume of unpublished material flowing into its systems.

hackernews · pred_ · Sep 10, 06:49 · [Discussion](https://news.ycombinator.com/item?id=49639408)

**Background**: Mathstodon is a Mastodon instance aimed at mathematicians that supports LaTeX rendering, and Mastodon itself is a decentralized, open-source social network where each server hosts its own community. OpenAI is the developer of models such as GPT and Codex, which are widely used by researchers for mathematical and coding work. The dispute concerns the intersection of two technical phenomena: pretraining, in which models learn statistical patterns from large corpora that may include user chats, and reinforcement learning on verifiable math problems, where a model is rewarded for reaching correct answers and can in principle derive novel solution techniques on its own.

<details><summary>References</summary>
<ul>
<li><a href="https://terrytao.wordpress.com/2022/11/20/trying-out-mathstodon/">Trying out Mathstodon | What's new</a></li>
<li><a href="https://davidlowryduda.com/on-mathstodon/">MixedMath: On Mathstodon</a></li>
<li><a href="https://en.wikipedia.org/wiki/Decentralized_identifier">Decentralized identifier - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Sentiment is largely skeptical of OpenAI. One prominent argument compares the company to a human collaborator who takes ideas from a joint discussion and publishes without attribution — behavior that would be plainly unethical for a person. Other commenters argue both explanations can coexist, noting that memorization in very large models and genuine RL-driven discovery are not mutually exclusive, while a broader thread of doubt questions whether reported rapid AI progress on open problems reflects real capability or an artifact of researchers feeding fresh, unpublished ideas into the systems.

**Tags**: `#AI ethics`, `#OpenAI`, `#research integrity`, `#mathematics`, `#AI research`

---

<a id="item-5"></a>
## [DeepSeek Releases V4.1 Flash: 552B MoE With Aggressive Cache Pricing](https://twitter.com/deepseek_ai/status/2097930608790167907) ⭐️ 8.0/10

DeepSeek announced DeepSeek-V4.1-Flash on Hugging Face on September 10, 2026, shipping a 552-billion-parameter Mixture-of-Experts model alongside a roughly 50-page technical report titled "Pushing the Limits of KV Cache Compression". The release also sets cache-hit pricing at just $0.003 per million tokens, a rate that dominated discussion of the model's economics. By nearly doubling the scale of the previous V4 Flash (284B to 552B) while attacking KV cache size, DeepSeek is pushing frontier-scale inference economics rather than just benchmark scores. The pricing math discussed around the release suggests that context transfer over the network could soon cost more than cache hits, which would reshape how long-context agents and chat completion APIs are priced across the industry. Despite the "Flash" branding, the model is nearly twice the size of the original V4 Flash, which makes local deployment considerably harder; DeepSeek claims the new architecture cuts agent memory costs roughly fourfold. Community members also caution that the jump in benchmark scores may partly reflect scale rather than efficiency, and that real-world performance versus benchmark optimization remains unverified, although DeepSeek's reports have generally been regarded as trustworthy.

hackernews · Liwink · Sep 10, 06:11 · [Discussion](https://news.ycombinator.com/item?id=49639090)

**Background**: A KV cache stores the attention keys and values for every token a model has already processed, so that repeated text does not have to be recomputed during decoding; prompt caching reuses that prefix state and bills the reused tokens at a discounted rate (about 0.032x base input on DeepSeek, versus 0.1x on several Western providers). A Mixture-of-Experts (MoE) model contains many parameters but activates only a subset per token, so parameter counts in the hundreds of billions do not translate directly into per-token compute. As long-context agents replay large conversation histories turn after turn, the cost of moving and re-reading that context becomes a central design constraint, which is why cache pricing and cache compression have become competitive battlegrounds.

<details><summary>References</summary>
<ul>
<li><a href="https://www.techtimes.com/articles/327163/20260910/deepseek-v41-flash-cuts-agent-memory-costs-fourfold-new-architecture.htm">DeepSeek V4.1-Flash Cuts Agent Memory Costs Fourfold With New Architecture</a></li>
<li><a href="https://www.progressiverobot.com/2026/09/10/deepseek-v4-1-flash-552b-moe-model-hugging-face/">DeepSeek V4.1 Flash: Powerful 552B MoE at a Surprising Price</a></li>
<li><a href="https://www.morphllm.com/prompt-caching">Prompt Caching: How It Works, Provider Pricing, Cache-Aware ...</a></li>

</ul>
</details>

**Discussion**: The Hacker News thread (about 878 upvotes and 495 comments) was largely admiring: commenters praised DeepSeek's technical report for being packed with concrete detail — contrasted with a competitor's system card they felt was mostly safety boilerplate — and marveled that the team keeps committing bold, novel ideas at near-frontier scale. The sharpest counterpoint came from a commenter who argued that at $0.003 per million cached tokens, transferring the same context over the network may cost more than reading it from cache, potentially making today's chat completion APIs obsolete for long-running coding tasks (447 turns on a medium codebase). Others noted the "Flash" label is misleading given the 552B size and questioned how much of the benchmark gain is real performance versus benchmark optimization.

**Tags**: `#AI/ML`, `#LLM`, `#DeepSeek`, `#model-release`, `#inference-pricing`

---

<a id="item-6"></a>
## [Quoting Terence Tao](https://simonwillison.net/2026/Sep/9/terence-tao/) ⭐️ 8.0/10

Terence Tao warns that AI-driven efforts to mine and rapidly solve open problems may make promising research directions scarce and discourage sharing, threatening centuries of open science.

rss · Simon Willison · Sep 9, 00:20

**Tags**: `#ai-ethics`, `#open-science`, `#mathematics`, `#ai-research`, `#research-culture`

---

<a id="item-7"></a>
## [DeepSeek ships MIT-licensed Harness agent and opens V4-Pro-0813 weights](https://t.me/zaihuapd/43738) ⭐️ 8.0/10

DeepSeek released DeepSeek Harness (dsh), an MIT-licensed agent application that treats models, tools, skills, sessions, sandboxes, storage, scheduling and UI as swappable plugins, and offers four run modes: Standard, PTC, Minimal and Create. In the same announcement, the company opened the DeepSeek-V4-Pro-0813 model weights on Hugging Face, with the app distributed via npm and GitHub. By making every agent capability a plugin, DeepSeek is pushing the agent stack toward composability, where tools, sandboxes and even entire harnesses such as Claude Code or Codex can be mixed and swapped rather than baked in. Pairing that framework with openly downloadable frontier-scale weights gives developers a fully self-hostable alternative to closed agent platforms, which could reshape how teams build and vendor-lock-avoid coding agents. The four presets differ sharply in behavior: Standard is a full coding agent, PTC (programmatic tool calling) generates a Code Mode SDK and run_code to execute multi-tool programs while saving tokens, Minimal ships only bash plus an editor for benchmarking, and Create is self-modifying, with dsh.bundle and allowBuilds flagged as potential pitfalls. The V4-Pro-0813 release is technically open-weights rather than fully open-source, since the training data and full pipeline were not released, and DeepSeek reports it outperforms the V4-Pro Preview on published benchmarks.

telegram · zaihuapd · Sep 10, 07:28

**Background**: An agent "harness" is the scaffolding around a language model — the loop, tool interface, sandbox and UI that turn a raw model into a working coding assistant. DeepSeek Harness is built on Cordis, a plugin and service system whose design follows DeepSeek's own paper on a "programming paradigm for spatiotemporal composability," meaning agent behavior is assembled from interchangeable parts instead of being hard-coded. PTC, or programmatic tool calling, refers to letting the model write and run code that calls tools directly, which cuts the number of round trips and tokens compared with one-tool-per-step calling.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/deepseek-ai/deepseek-harness">GitHub - deepseek-ai/deepseek-harness: DeepSeek Harness: Everything is a Plugin. · GitHub</a></li>
<li><a href="https://dshbase.com/blog/deepseek-harness-modes/">DeepSeek Harness Modes — Standard, PTC, Minimal & Create (Full Guide ...</a></li>
<li><a href="https://huggingface.co/multimodalart/DeepSeek-V4-Pro-0813">multimodalart/ DeepSeek - V 4 - Pro - 0813 · Hugging Face</a></li>

</ul>
</details>

**Tags**: `#DeepSeek`, `#LLM`, `#open-source`, `#agent-framework`, `#model-release`

---

<a id="item-8"></a>
## [Essay Argues Software Development Culture Drives Developers Insane](https://graybeard.ing/software-drives-people-insane/) ⭐️ 7.0/10

An essay published at graybeard.ing under the title "I have a theory that software drives people insane" argues that common software development practices and organizational dynamics systematically push developers toward madness. The post reached the Hacker News front page with 314 points and 121 comments, sparking a wide-ranging discussion about development culture. The piece taps into a persistent undercurrent of developer burnout and frustration, arguing that the problem is structural rather than individual. Its traction on Hacker News shows that many engineers recognize these dynamics in their own teams, which matters for anyone thinking about engineering management, team organization, or retention. The essay is a theoretical, anecdote-driven argument rather than an empirical study, so its claims are intentionally broad and open to interpretation. Commenters extend it with concrete angles the author does not fully develop, including the insulating role of project managers, the measurable cost that LLMs introduce into software changes, and the role of ego in engineering decisions.

hackernews · rglover · Sep 10, 16:13 · [Discussion](https://news.ycombinator.com/item?id=49646181)

**Background**: Hacker News is a technology-news forum where essays about engineering culture often go viral, and this post is typical of that genre: an opinion piece rather than a product or research announcement. The underlying concepts it assumes familiarity with are familiar to working engineers, such as siloed teams, project managers acting as intermediaries with clients, and the long-standing belief that the cost of changing software is unknown or ignored. The discussion also touches on LLM coding agents, which are increasingly used to produce software changes and are typically billed by usage.

**Discussion**: Commenters largely agreed with the essay's premise but reframed the causes. bob1029 argued that what actually drives developers insane is development untethered from real customer contact, since frequent direct interaction dampens the dysfunction; raphar contended that the old assumption of cheap, invisible software change is dead because LLMs give changes a measurable cost; tcdent framed much of the behavior as an expression of human ego; and hliyan noted nostalgically that teams once shipped mission-critical real-time trading systems with far fewer developers.

**Tags**: `#software engineering`, `#developer psychology`, `#project management`, `#AI/LLM impacts`, `#Hacker News discussion`

---

<a id="item-9"></a>
## [Cognition launches SWE-2 coding model, claims parity with Fable 5.1](https://cognition.com/blog/swe-2) ⭐️ 7.0/10

Cognition released SWE-2, which it calls its most advanced agentic coding model yet, claiming performance that rivals frontier systems such as Claude Fable 5.1 and GPT-6 Astra at up to 70% lower cost. The model is post-trained from Moonshot AI's Kimi K3 and introduces configurable reasoning-effort levels that are all trained inside a single reinforcement-learning run. If the claimed numbers hold up, SWE-2 would put a coding-agent startup's model on the same Pareto frontier as the largest frontier labs while undercutting them substantially on price, pressuring margins across the coding-model market. It also signals that post-training on top of a capable open base model can approach frontier coding performance, which strengthens the case for open-weight alternatives. The headline capability is configurable reasoning-effort levels trained jointly in one RL run, but community skeptics point to a large generalization gap: the model scores 92.8% on Terminal Bench 2.1 yet only 27.3% on the newer Terminal Bench 4 released a couple of weeks earlier. Cognition has not clearly stated whether the weights are open, and the model is a post-train of Kimi K3 rather than a from-scratch architecture.

hackernews · seelos · Sep 10, 15:29 · [Discussion](https://news.ycombinator.com/item?id=49645443)

**Background**: Cognition is the company behind Devin, an early 'AI software engineer' agent, and its previous demos drew criticism for overstating autonomy. SWE-2 is a coding-focused large language model, the kind used to drive agentic tools that read repositories, edit files and run tests, and it competes in a crowded field that includes Anthropic's Fable 5.1 and OpenAI's GPT-6 Astra. Kimi K3, the base model it is post-trained from, is a 2.8-trillion-parameter model from Moonshot AI, and post-training means further tuning of an existing model rather than pretraining from scratch. Benchmark scores like Terminal Bench are widely used to compare such models, but they can be gamed or overfit, which is why the community treats vendor-reported numbers cautiously.

<details><summary>References</summary>
<ul>
<li><a href="https://cognition.com/blog/swe-2">Introducing SWE-2: Pushing the Pareto Frontier | Cognition</a></li>
<li><a href="https://ai-tldr.dev/releases/cognition-swe-2/">SWE-2 — Cognition's coding model lands within a… | AI/TLDR</a></li>
<li><a href="https://www.anthropic.com/claude-fable-and-mythos-5-1">Introducing Claude Fable 5 . 1 and Claude Mythos 5 . 1 \ Anthropic</a></li>

</ul>
</details>

**Discussion**: Commenters on Hacker News were largely skeptical: several flagged the gap between 92.8% on Terminal Bench 2.1 and 27.3% on the newer Terminal Bench 4 as evidence of 'benchmaxxing' rather than generalizable skill. Others questioned the lack of clear open-weights or model-stat disclosures, arguing there is little reason to pick another closed model over strong open alternatives, and one noted Cognition's history of demos that did not hold up under scrutiny. A more favorable view held that an RL-tuned Kimi K3 reaching Fable 5-class capability is itself an encouraging sign.

**Tags**: `#LLM`, `#coding agents`, `#model release`, `#benchmarks`, `#open weights`

---

<a id="item-10"></a>
## [NASA Mars False-Color Trick Now Reveals Earth's Rock Art](https://gizmodo.com/this-nasa-color-trick-was-meant-for-mars-now-its-unveiling-rock-art-on-earth-2000809844) ⭐️ 7.0/10

A NASA false-color image enhancement technique originally developed for processing Mars satellite imagery is now being used to reveal ancient rock art on Earth, according to a Gizmodo report based on a NASA Spinoff article. The method transforms photographs of faded pictographs so that pigments invisible to the naked eye become clearly visible as distinct hues. It shows how space-imaging technology can transfer to archaeology, giving researchers a low-cost way to document rock art that is fading or nearly invisible in ordinary photographs. This kind of cross-domain reuse of remote-sensing pipelines is a recurring pattern in NASA spinoffs and could help preserve cultural heritage records before sites degrade further. The underlying algorithm is decorrelation stretch: three color bands are rotated into their principal axes, each axis is stretched to equal variance, and the result is rotated back, so subtle color differences previously masked by strong band-to-band correlation become separated hues. The open-source rock-art tool DStretch is built on exactly this technique, and commenters noted it can be approximated in GIMP using LAB channel decomposition and auto-levels on the chroma channels.

hackernews · gumby · Sep 10, 15:29 · [Discussion](https://news.ycombinator.com/item?id=49645437)

**Background**: Optical sensors can capture wavelength bands beyond human vision, such as near-infrared, and false-color composites map those bands onto visible red, green and blue so hidden information becomes visible. Decorrelation stretch was developed for exactly this purpose in aerial and planetary imaging, and it is the technique behind the vivid false-color Mars and ASTER images. Rock art researchers apply it to ordinary digital photos of pictographs, where pigments have faded or blended into the rock surface, to bring out faint figures that are otherwise very hard to discern.

<details><summary>References</summary>
<ul>
<li><a href="https://dstretch.com/">DStretch.com home page</a></li>
<li><a href="https://github.com/shannietron/decorrelation_stretch">GitHub - shannietron/decorrelation_stretch</a></li>
<li><a href="https://www.mathworks.com/help/images/enhance-color-separation-using-decorrelation-stretching.html">Enhance Color Separation Using Decorrelation Stretching</a></li>

</ul>
</details>

**Discussion**: Hacker News commenters were broadly positive, with one pointing to the fuller NASA Spinoff version of the article and another recalling false-color composites as a formative "eureka" moment in remote sensing that taught them human vision is not canonical. Others contributed practical recipes, including a step-by-step GIMP LAB decomposition workflow, a personal (unsuccessful) attempt to find hidden rock art at Angkor Wat with bandpass filters, and a request for an ImageMagick implementation that could be dropped into a pipeline.

**Tags**: `#remote sensing`, `#image processing`, `#archaeology`, `#NASA`, `#false color`

---

<a id="item-11"></a>
## [Shopify Migrates Its Mobile App from React Native Back to Native](https://shopify.engineering/back-to-native) ⭐️ 7.0/10

Shopify engineers published an engineering blog post explaining why they moved their consumer mobile app from React Native back to fully native iOS and Android codebases. The post sparked a large Hacker News debate (566 points, 393 comments) about cross-platform tradeoffs and whether AI code generation is eroding React Native's main advantage. Shopify is a high-profile technology company, so its reversal is a significant data point that pushes back against the long-running industry trend of adopting cross-platform frameworks to share code between iOS and Android. The discussion suggests the calculus is shifting as LLM-based coding tools make writing platform-specific native code cheaper, which could affect how startups and large enterprises staff and architect their mobile teams. The Hacker News thread includes several first-hand accounts of AI-assisted ports: one commenter (atonse) said they used Codex to inventory every screen of a React Native app and generate Android and iOS directories, getting most of a 15–20 screen app working overnight with Maestro used for testing. Commenters also framed the choice as a resource-dependent engineering decision rather than an absolute good-or-bad verdict, noting that cross-platform frameworks tend to produce a lowest-common-denominator app while not necessarily delivering the promised headcount savings.

hackernews · fnthawar2 · Sep 10, 14:09 · [Discussion](https://news.ycombinator.com/item?id=49643982)

**Background**: React Native is an open-source UI framework created by Meta that lets developers build mobile apps with JavaScript and React, sharing much of the code across iOS and Android instead of writing two separate native codebases in Swift/Objective-C and Kotlin/Java. Its main selling point has historically been letting web developers reuse their skills for mobile work. AI-assisted software development, in which large language models and coding agents generate or refactor code, is now changing the cost equation for producing platform-native code.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/React_Native">React Native - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/AI-assisted_software_development">AI-assisted software development - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Sentiment is mixed but leans toward the view that this is a normal engineering tradeoff rather than a universal verdict: one commenter compared it to a spectrum of companies where Electron/React Native either makes sense or doesn't, depending on their problems and resources. A widely echoed argument says LLMs have become much better at generating native iOS code, so the old rationale for React Native — leveraging web developers — has weakened, though others caution that cross-platform teams often end up needing dedicated native engineers anyway.

**Tags**: `#React Native`, `#Shopify`, `#mobile development`, `#native apps`, `#AI code generation`

---

<a id="item-12"></a>
## [Brown University Paper: Silicon Valley Is Reshaping the Military-Industrial Complex](https://costsofwar.watson.brown.edu/paper/how-big-tech-and-silicon-valley-are-transforming-military-industrial-complex) ⭐️ 7.0/10

A research paper from Brown University's Costs of War project argues that Big Tech and Silicon Valley firms are fundamentally transforming the U.S. military-industrial complex. The report, published by the Watson Institute, sparked a 102-point Hacker News thread with 153 comments debating tech workers' ethical responsibilities and the defense industry's deep roots in the Valley. The paper adds academic weight to a growing debate over whether the companies that dominate consumer software and AI should also become core suppliers to the defense sector, a shift that affects procurement policy, engineering culture, and how tech workers judge their own employers. Because Silicon Valley talent and infrastructure are now seen as strategic assets, the boundary between commercial tech and military programs is becoming harder to draw. The paper is part of a nonpartisan, public-facing research effort at Brown University that documents the human and financial costs of U.S. military operations, so it is explicitly advocacy-adjacent rather than a purely neutral industry survey. Commenters also pointed to a specific example: an Andreessen- and Thiel-backed defense startup reportedly opening a U.S. missile factory as it exits stealth, underscoring how venture capital is now flowing directly into weapons production.

hackernews · paimapi · Sep 10, 15:47 · [Discussion](https://news.ycombinator.com/item?id=49645754)

**Background**: The Costs of War Project is a nonpartisan research initiative based at Brown University's Watson Institute for International and Public Affairs that publishes public-facing research on the broad consequences of U.S. military operations and spending, including the domestic effects and the ongoing costs of the post-9/11 wars. The phrase "military-industrial complex" comes from President Eisenhower's 1961 farewell address warning about the entanglement of the armed forces and private industry. Commenters note that Silicon Valley's relationship with the Pentagon is not new: Fairchild Semiconductor and its peers sold integrated circuits to the military for missile systems such as the Minuteman, meaning much of the region's early growth was underwritten by defense contracts.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Costs_of_War_Project">Costs of War Project - Wikipedia</a></li>
<li><a href="https://costsofwar.watson.brown.edu/">Costs of War | Brown University</a></li>
<li><a href="https://costsofwar.watson.brown.edu/costs">Costs | Costs of War | Brown University</a></li>

</ul>
</details>

**Discussion**: Sentiment was sharply divided. One commenter described quitting a high-paying Microsoft job over what they called complicity with Israeli war crimes and argued tech workers must push back against the military-industrial complex; others countered that Silicon Valley has been DOD-funded since Fairchild, that purely civilian funding might not have produced the same technology, and asked pointedly whether only U.S. companies should refrain from defense contracts or whether defense work is simply being selectively condemned.

**Tags**: `#military-industrial-complex`, `#defense-tech`, `#tech-ethics`, `#silicon-valley`, `#policy`

---

<a id="item-13"></a>
## [Fly connectome fails to learn Pong, audit exposes tooling bugs](https://www.reddit.com/r/MachineLearning/comments/1wc67ci/i_tried_to_make_a_real_fly_connectome_learn_to/) ⭐️ 7.0/10

A developer tried to train a small real subgraph of the newly released MaleCNS v1.0 Drosophila connectome (166k neurons, real EM reconstruction) to play Pong using dopamine-style plasticity, and it did not learn. The failure was turned into a detailed audit that uncovered a neuPrint regex bug silently zeroing out two entire neuron populations, a neuron selection with no path from photoreceptors to anything else, and motor neurons with zero synapses from any sensory pathway. Rigorously documented negative results with synapse-level auditing are genuinely valuable to the computational neuroscience and ML communities, since they expose hidden failure modes in connectome tooling rather than just adding another flashy demo. The post also argues that the viral fly-brain-plays-Doom/Minecraft/Beat Saber clips do not hold up, claiming their own repositories admit failed validation gates, silent motion pathways, and hand-injected behaviors. In the rebuilt circuit, learning-on and learning-off produced bit-for-bit identical results across multiple seeds even though the weights were verifiably changing, and two of the four available motor neurons had literally zero synapses from any sensory pathway because they had been assigned to the "paddle down" group purely by array index. After swapping in a courtship-pursuit visual target-tracking pathway, learning-on and learning-off finally diverged, but the effect looked like the learning rule globally quieting the system — misses outnumber hits, so punishment dominates and shrinks the motor response rather than producing skill.

reddit · r/MachineLearning · /u/oPeraza2007 · Sep 10, 02:28

**Background**: A connectome is a map of every neuron and synapse in a nervous system, reconstructed here from electron microscopy; Janelia's MaleCNS v1.0 is the first finished connectome of an entire male Drosophila central nervous system, spanning the central brain, optic lobes and ventral nerve cord. neuPrint is an open-access tool that stores such connectome data in a Neo4j graph database and is queried with the Cypher language, which is where the regex semantics bug arose. Dopamine-style plasticity refers to the biological mechanism by which the neuromodulator dopamine strengthens or weakens synapses to drive reward-based learning, which the author used as the learning rule. Pong was chosen as an unforgiving test bed because it gives only a single binary hit-or-miss signal per frame, leaving nowhere to hide a null result.

<details><summary>References</summary>
<ul>
<li><a href="https://male-cns.janelia.org/">Male CNS Connectome - MaleCNS connectome</a></li>
<li><a href="https://www.frontiersin.org/journals/neuroinformatics/articles/10.3389/fninf.2022.896292/full">Frontiers | neuPrint: An open access tool for EM connectomics</a></li>
<li><a href="https://www.janelia.org/project-team/flyem/male-cns-connectome">Male CNS Connectome | Janelia Research Campus</a></li>

</ul>
</details>

**Tags**: `#connectome`, `#computational-neuroscience`, `#reinforcement-learning`, `#plasticity`, `#negative-results`

---

<a id="item-14"></a>
## [Apple unveils iPhone 18 Pro, foldable iPhone Duo, Watch S12/Ultra 4 and AirPods 5](https://www.apple.com.cn/iphone-18-pro/) ⭐️ 7.0/10

Apple held its latest product launch event, introducing the iPhone 18 Pro, the first-generation foldable iPhone Duo, Apple Watch Series 12 and Apple Watch Ultra 4, and AirPods 5, with China-market (国行) pricing and release dates also announced. The post additionally notes that older iPhone models saw price increases. The iPhone Duo marks Apple's long-awaited entry into the foldable phone market, establishing a new high-end price tier above the Pro line and testing whether Apple can still deliver genuinely novel hardware. A simultaneous refresh of the Watch, Ultra and AirPods lines gives Apple one of its broadest product cycles in years, directly affecting upgrade decisions for consumers in China and worldwide. According to early coverage, the iPhone Duo uses a glass body with a custom polymer inner display that feels plastic-like, pairing a 5.4-inch 1398 x 2034 outer screen with a 7.6-inch 1878 x 2670 inner screen that has a nano-texture coating to reduce glare and supports Apple Pencil. Apple Watch Ultra 4 is positioned as an ultimate sports and adventure watch with dual-frequency GPS and 45% recycled material content, including 100% recycled cobalt in the battery and 95% recycled lithium.

telegram · zaihuapd · Sep 10, 01:20

**Background**: Foldable phones have been on the market for years from Samsung, Huawei and others, using hinges and flexible OLED panels to turn a phone into a small tablet, but Apple had until now stayed out of the category. The Apple Watch Ultra is Apple's premium, rugged watch line aimed at athletes and outdoor users, sitting above the standard Series line, while AirPods is its wireless earbuds family. '国行' refers to the mainland China version of Apple devices, which differs from US and Hong Kong versions in network bands (no 5G mmWave), SIM/eSIM configuration and after-sales service, so pricing and model differences are closely watched by Chinese buyers.

<details><summary>References</summary>
<ul>
<li><a href="https://cn.nytimes.com/technology/20260910/apple-iphone-duo-foldable-phone/">苹 果 推出首款折叠屏手机 iPhone Duo - 纽约时报中文网</a></li>
<li><a href="https://www.163.com/dy/article/L6EK84DL0511E2VD.html">iPhone Duo 折叠屏手机发布，屏下镜头来了！| 苹 果 | duo | iphone ...</a></li>
<li><a href="https://www.apple.com/newsroom/2026/09/apple-unveils-apple-watch-ultra-4/">Apple unveils Apple Watch Ultra 4 - Apple</a></li>

</ul>
</details>

**Tags**: `#Apple`, `#iPhone`, `#Apple Watch`, `#AirPods`, `#Product Launch`

---

<a id="item-15"></a>
## [Ant International, Visa and Mastercard Team Up on AI Agent Payment Standard](https://www.cnbc.com/2026/09/10/ant-international-visa-mastercard-ai-agent-payment-standard.html) ⭐️ 7.0/10

Ant International announced a partnership with Visa and Mastercard to build a common "Know Your Agent" (KYA) standard for AI-agent payments, under which an agent would be linked to a verified real-world entity, have its behavior assessed, and be subject to ongoing risk monitoring. The three parties cited a McKinsey forecast that AI agents could handle between $3 trillion and $5 trillion of global consumer commerce transactions by 2030. If AI agents end up initiating purchases on behalf of consumers, a single shared identity-and-verification standard would let those transactions move across different card networks and platforms instead of being confined to walled gardens. Because Visa and Mastercard together cover the large majority of global card payments, their alignment with a major Chinese fintech player such as Ant International could shape how agentic commerce is governed worldwide. The announced framework focuses on three functions: tying each AI agent to a valid human or corporate entity, evaluating agent behavior, and monitoring transactions for risk, in order to reduce hallucination-driven or rogue payments. The announcement did not include a published technical specification, implementation timeline, or detailed liability rules, so it remains a declaration of intent rather than a finalized standard.

telegram · zaihuapd · Sep 10, 03:00

**Background**: Existing card payment systems are built around a human cardholder who authenticates and authorizes each transaction, which is why banks use "Know Your Customer" (KYC) checks to verify who is behind an account. AI agents — software that can independently search, book, and pay on a user's behalf — break that assumption, since a machine may act without a human present at checkout. "Know Your Agent" is an attempt to extend the KYC idea to machines, giving payment networks a way to know which verified user or company stands behind an automated purchase.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cnbc.com/2026/09/10/ant-international-visa-mastercard-ai-agent-payment-standard.html">Ant International, Visa and Mastercard team up on AI payment standard</a></li>
<li><a href="https://en.cryptonomist.ch/2026/09/10/ai-agent-payment-standards/">AI Agent Payment Standards Set by Visa, Mastercard, Ant</a></li>
<li><a href="https://www.zubiqo.com/news/visa-mastercard-and-ant-international-launch-know-your-agent-payment-standard-for-ai-bots-wtt94i">Visa, Mastercard, and Ant International Launch 'Know-Your-Agent ...</a></li>

</ul>
</details>

**Tags**: `#AI agents`, `#payments`, `#fintech`, `#standards`, `#Visa/Mastercard`

---

<a id="item-16"></a>
## [China AI Chip Prices Jump 20-50% as HBM Shortage Bites](https://www.reuters.com/world/asia-pacific/chinas-ai-chipmakers-raise-prices-high-bandwidth-memory-shortage-bites-2026-09-10/) ⭐️ 7.0/10

Chinese AI chipmakers including Huawei and Cambricon have raised or are preparing to raise prices as the global high-bandwidth memory (HBM) shortage worsens. Huawei's Ascend 950DT quotes are up roughly 20%–50% versus two months ago (with some older chips up about 30%), while Cambricon's next-generation SiYuan 690 is expected to cost 20%–30% more. The increases show that HBM, not chip design or fabrication alone, has become the binding constraint on China's domestic AI compute expansion, pushing up the cost of training and inference for Chinese cloud providers and model developers. Because US export controls cut Chinese firms off from much of the global memory supply, this bottleneck is likely to persist and could slow the deployment timelines of large domestic AI clusters. HBM supply is concentrated in just three vendors — SK Hynix, Samsung and Micron — and US export restrictions further tighten availability for Chinese buyers. The affected parts are the high end of the domestic stack (for example, the Ascend 950DT ships with 144 GB of HBM and 2 PFLOPS of FP8 compute, and Cambricon aims to deliver hundreds of thousands of SiYuan 590/690 accelerators in 2026), so memory shortages hit exactly the products China most needs for large-scale training.

telegram · zaihuapd · Sep 10, 09:29

**Background**: HBM is a type of memory made by vertically stacking DRAM dies and connecting them with through-silicon vias (TSVs), giving an extremely wide data path (1024 bits in HBM3) instead of relying on high clock speeds; it is what keeps modern AI accelerators fed with data. Huawei's Ascend and Cambricon's SiYuan lines are China's leading domestic alternatives to Nvidia GPUs, and they depend on HBM for their performance. Since US export controls restrict China's access to advanced chips and memory, domestic AI compute expansion is increasingly limited by how much HBM the country can obtain.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/High_Bandwidth_Memory">High Bandwidth Memory - Wikipedia</a></li>
<li><a href="https://abit.ee/en/processors/huawei-ascend-950dt-ai-chip-ai-accelerator-huawei-cloud-machine-learning-ascend-950-en">Huawei Confirms Ascend 950DT AI Chip Arriving on Cloud in ...</a></li>
<li><a href="https://aiwiki.ai/wiki/cambricon_siyuan_690">Cambricon Siyuan 590/690 - AI Wiki</a></li>

</ul>
</details>

**Tags**: `#AI chips`, `#HBM`, `#semiconductor supply chain`, `#Huawei Ascend`, `#China AI`

---

<a id="item-17"></a>
## [Moonshot AI (Kimi) confidentially files for Hong Kong IPO at $50B pre-money valuation](https://t.me/zaihuapd/43743) ⭐️ 7.0/10

Moonshot AI, the Chinese company behind the Kimi large model, has confidentially submitted an A1 filing to the Hong Kong Stock Exchange to formally begin its IPO process, with the company saying it has no information to disclose at this time. In parallel, it is raising a new funding round at a $50 billion pre-money valuation, which is expected to be its final round before listing. This marks one of the most aggressive valuation run-ups in the Chinese LLM sector and would make Moonshot one of the first major Chinese foundation-model startups to reach public markets, setting a benchmark for peers such as DeepSeek, which is expected to list as early as the first half of next year. It signals that investors are willing to price Chinese AI labs near global frontier-lab levels despite the heavy capital demands of model training. The A1 filing is the formal IPO application package submitted by sponsors to HKEX, and under current rules the company must also file a Chinese-language prospectus with the China Securities Regulatory Commission within three working days for overseas listing registration. Moonshot's valuation rose from roughly $4.3 billion at the end of 2025 to $35 billion post-money in July, an approximately 8x increase in six months, supported by an iteration cadence of roughly one model release every three months (K2.5, K2.6 and K3 between January and July).

telegram · zaihuapd · Sep 10, 10:58

**Background**: Moonshot AI is a Beijing-based startup whose Kimi chatbot and open-weight models, including the recent Kimi K2.5 multimodal model, rank among the strongest Chinese LLMs on third-party benchmarks. A confidential A1 filing lets a company begin the Hong Kong listing review without immediately publishing full prospectus details to the public, and a "pre-money" valuation refers to the company's value before the new investment capital is added — the post-money figure equals pre-money plus the amount raised. Valuation growth of this scale in a six-month window is unusual even by AI-industry standards, and reflects both the capital intensity of frontier model training and investor expectations around a coming wave of Chinese AI listings.

<details><summary>References</summary>
<ul>
<li><a href="https://qifu.zcqtz.com/article/22267.html">香港ipo的a1是指什么 (香港IPO中A1文件含义)-中国香港百科-丝路企服</a></li>
<li><a href="https://zhuanlan.zhihu.com/p/429164931">投前VS投后估值？新股VS老股？还在傻傻分不清楚？ 股权融资中的重大误区——投前估值和投后估值不分 - 知乎 投前估值 vs 投后估值（2026 指南） | Round Funded 投前估值、投后估值的区别是什么？ - 知乎 投前估值 vs 投后估值：到底有什么区别？ | EquiRound 投前估值 (投资术语) - 会计百科 - kuaiji.com</a></li>
<li><a href="https://hao.cnyes.com/post/230958">國產 大 模 型 Kimi K 2 . 5 全球多榜單領先，推動AI...</a></li>

</ul>
</details>

**Tags**: `#Moonshot AI`, `#Kimi`, `#IPO`, `#AI startups`, `#LLM industry`

---

<a id="item-18"></a>
## [Tencent Hunyuan open-sources AuK audio editing model with 4-step AuK-Flash variant](https://x.com/TencentHunyuan/status/2097996926876795197) ⭐️ 7.0/10

Tencent Hunyuan released AuK, an open-source unified speech generation and editing model that takes natural-language instructions plus a reference audio clip as input; code, model weights, and demos are now available. Alongside it, the team shipped AuK-Flash, a distilled variant that performs 4-step inference without classifier-free guidance and achieves roughly a 4.5x wall-clock speedup over the full model under matched conditions. A unified, instruction-driven speech model from a major industrial lab lowers the barrier for developers who previously had to stitch together separate zero-shot TTS, voice cloning, and audio-editing pipelines. The fast AuK-Flash variant matters for latency-sensitive deployment, and the permissive open release puts real audio-editing capability into the hands of the wider speech-AI community. AuK is a 1.5B-parameter foundation model trained on millions of hours of diverse audio, supporting zero-shot and instruction-based TTS, content, acoustic, and paralinguistic editing, speech enhancement, and source separation behind a single natural-language interface. The AuK-Flash distillation combines consistency initialization with task-routed Decoupled DMD, and a technical report is available on arXiv.

telegram · zaihuapd · Sep 10, 11:56

**Background**: Zero-shot text-to-speech means generating speech for a voice the model has never been explicitly trained on, using only a short reference clip as a style example. Traditional audio workflows treat generation, voice conversion, emotion editing, accent removal, and speaker separation as separate specialized models, each with its own interface and failure modes. AuK's premise is that a single instruction-following model trained on large-scale audio can replace that patchwork, similar to how instruction-tuned LLMs unified many NLP tasks. Distillation compresses such a model into fewer denoising steps, trading a small amount of quality for much faster inference.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/Tencent-Hunyuan/AuK">GitHub - Tencent-Hunyuan/AuK: AuK: An Open-Source ...</a></li>
<li><a href="https://huggingface.co/tencent/AuK-Flash">tencent/AuK-Flash · Hugging Face</a></li>
<li><a href="https://arxiv.org/abs/2609.08936">[2609.08936] AuK Technical Report: An Open-Source ...</a></li>

</ul>
</details>

**Tags**: `#audio-editing`, `#text-to-speech`, `#open-source-models`, `#voice-cloning`, `#tencent-hunyuan`

---

<a id="item-19"></a>
## [PlanetScale launches Neki, a closed-source sharded Postgres](https://planetscale.com/blog/introducing-neki) ⭐️ 6.0/10

PlanetScale introduced Neki, a sharding and scale-out product for Postgres, announced via a blog post titled simply "Introducing Neki." Neki is a closed-source offering: each shard is a real Postgres instance, and Neki adds a router, sidecars, and a control plane on top to push workloads beyond a single machine. Postgres horizontal scale-out is one of the most contested areas in database infrastructure right now, and Neki puts PlanetScale — long known for sharding MySQL via Vitess — directly against Supabase's open-source multigres and other sharding options. The fact that Neki is closed source while its CEO has publicly criticized open-source competitors makes the launch as much a community and licensing story as a technical one. According to PlanetScale's own materials, Neki targets workloads reaching hundreds of millions of QPS and petabytes of data without downtime, and it is positioned to run on top of PlanetScale's managed Postgres platform. The launch post was widely criticized for describing the problem, alternatives, and internal components without ever clearly stating in its opening paragraphs what Neki actually is or what it is for.

hackernews · simon_weber · Sep 10, 15:43 · [Discussion](https://news.ycombinator.com/item?id=49645686)

**Background**: Postgres traditionally runs as a single primary node, so scaling read and write throughput beyond one machine generally requires sharding — splitting data across multiple independent database nodes. Several projects address this: Citus and Postgres-XL are established sharding extensions, and Supabase announced multigres, described as "Vitess for Postgres." PlanetScale previously built its reputation on Vitess, an open-source sharding layer for MySQL, making its move into Postgres sharding a natural but notable expansion.

<details><summary>References</summary>
<ul>
<li><a href="https://planetscale.com/docs/postgres/sharding">Horizontal sharding for Postgres - PlanetScale</a></li>
<li><a href="https://neki.dev/?ref=upstract.com">Neki | Sharded Postgres by PlanetScale</a></li>
<li><a href="https://supabase.com/blog/multigres-vitess-for-postgres">Announcing Multigres : Vitess for Postgres</a></li>

</ul>
</details>

**Discussion**: Hacker News commenters were largely critical: several said the launch post never explains what Neki is, with one offering a line-by-line breakdown of each section's missing definition. Others questioned why Neki is closed source when PlanetScale's CEO has publicly mocked Supabase's open-source multigres, and some described the CEO's tone as combative and off-putting; one asked directly whether Neki will eventually be open-sourced, as they had originally understood.

**Tags**: `#databases`, `#postgres`, `#sharding`, `#planetscale`, `#open-source`

---

<a id="item-20"></a>
## [OpenAI Ships ChatGPT Images 2.5 with Two New API Model IDs](https://simonwillison.net/2026/Sep/8/introducing-chatgpt-images-25/) ⭐️ 6.0/10

OpenAI released ChatGPT Images 2.5, an incremental upgrade to its image generation models that improves multi-turn instruction following, responds faster, and better preserves subjects from reference photos. Two new API model IDs were introduced: gpt-image-2.5-sunburst for editing precision and gpt-image-2.5-flare for fast everyday generation, and Simon Willison promptly updated his openai_image.py CLI tool to accept one or more reference images. OpenAI says its image models have already generated more than 3 billion images across ChatGPT Images and the GPT-Image API, so even a modest upgrade touches a huge base of users and developers. For teams building image-editing or agentic workflows, the improved multi-turn coherence and reference-image preservation reduce the manual re-prompting that typically plagues iterative editing pipelines. OpenAI's documentation frames the two variants as a trade-off: choose Sunburst where editing precision matters most and Flare for fast, high-quality everyday image generation, which suggests Sunburst is the stronger but potentially slower or more costly option. The demo workflow — passing a reference chart image plus a prompt to add a cartoon raccoon scientist — illustrates the reference-image input path now supported in tooling.

rss · Simon Willison · Sep 8, 22:46

**Background**: Multi-turn image generation means an AI can refine, expand, or edit an image across several prompts within a conversation, rather than producing a single one-shot visual from one instruction; this is a long-standing weak point for image models, and it is the subject of active research benchmarks such as MMDU and EdiVal. Subject preservation refers to keeping the identity, appearance, or details of a reference subject consistent when it is re-rendered in a new scene, a problem explored by research frameworks like SceneBooth. Typically, text-to-image systems provide several model IDs with different speed/quality trade-offs so developers can pick the right one for a given pipeline.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2504.04717">[2504.04717] Beyond Single-Turn: A Survey on Multi-Turn ... What is Multi-Turn Image Generation in AI? | ImagineArt MMDU - Ziyu Liu GitHub - Liuziyu77/MMDU: Official repository of MMDU dataset GitHub - TianyuCodings/EdiVal: [ICLR 2026] Official code for ... TEXTB : M TURN INTERLEAVED MULTIMODAL INSTRUCTION FOLLOWING ... Parrot: Enhancing Multi-Turn Instruction Following for Large ...</a></li>
<li><a href="https://www.imagine.art/blogs/multi-turn-image-generation">What is Multi-Turn Image Generation in AI? | ImagineArt</a></li>
<li><a href="https://arxiv.org/abs/2501.03490">[2501.03490] SceneBooth: Diffusion-based Framework for ... Paper page - SceneBooth: Diffusion-based Framework for ... SceneBooth: Diffusion-based Framework for Subject-preserved ... SceneBooth: Diffusion-based Framework for Subject-preserved ... SceneBooth: Diffusion-based Framework for Subject-preserved ... TuckerDreamer: Subject-driven text-to-image generation via ...</a></li>

</ul>
</details>

**Tags**: `#OpenAI`, `#ChatGPT`, `#Image Generation`, `#Generative AI`, `#API`

---

<a id="item-21"></a>
## [348M model beats GPT-3 175B on arithmetic via column-wise work](https://www.reddit.com/r/MachineLearning/comments/1wc7hmu/i_trained_a_348m_model_trained_from_scratch_on/) ⭐️ 6.0/10

A hobbyist trained a 348M-parameter language model from scratch on 22.7B tokens and then fine-tuned it into a math model that solves arithmetic by emitting explicit column-by-column work (carries, borrows, partial products) instead of guessing answers, reaching a 99.4% average across the nine GPT-3 arithmetic sub-tasks with n=300 per task under greedy decoding and exact match. The model cleanly handles addition up to 14 digits after the author simply expanded the list of place-value names from 6 entries to 19. It is a striking demonstration that for narrow, procedural tasks a small, cheap-to-run specialized model can dramatically outperform a general model hundreds of times larger, echoing earlier results such as Goat-7B beating GPT-4 on arithmetic benchmarks. For practitioners, it suggests that data design and explicit step-by-step supervision can substitute for raw scale in domains with well-defined algorithms. The comparison is not strictly apples-to-apples: GPT-3's numbers come from few-shot direct-answer prompting at 175B parameters, while this model was fine-tuned to always produce worked steps, and the author flags that the subtraction harness orders operands. Known weaknesses include word problems (GSM8K 4%, ASDiv 16.5%), no division support, a hard wall at 4×4 multiplication, and a requirement for greedy decoding since sampling corrupts the column routine mid-chain.

reddit · r/MachineLearning · /u/nkthebass · Sep 10, 03:28

**Background**: The nine arithmetic sub-tasks referenced here come from the GPT-3 evaluation suite (also tracked in BIG-bench), which measures multi-digit addition, subtraction and multiplication with exact-match scoring. Few-shot learning is the setup in which a model performs a task after seeing only a handful of examples in its prompt rather than being trained on it, which is how GPT-3's baseline numbers were produced. Fine-tuning, by contrast, updates a model's weights on task-specific data — small language models fine-tuned this way are increasingly used to get fast, cheap, domain-specific behavior. The 'showing the work' behavior is a form of explicit reasoning trace, where the model writes out intermediate steps before stating a final answer.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/html/2305.14201">Goat: Fine-tuned LLaMA Outperforms GPT -4 on Arithmetic Tasks</a></li>
<li><a href="https://en.wikipedia.org/wiki/Few-shot_learning">Few-shot learning</a></li>

</ul>
</details>

**Tags**: `#llm`, `#arithmetic`, `#small-language-models`, `#fine-tuning`, `#benchmarks`

---

<a id="item-22"></a>
## [Sante's 83.83 on DiagnosisArena-MCQ only measures answer selection](https://www.reddit.com/r/MachineLearning/comments/1wbkxsa/what_santes_8383_on_diagnosisarenamcq_actually/) ⭐️ 6.0/10

A Reddit r/MachineLearning post argues that the 83.83 score reported by Ling-3.0-flash-Sante on DiagnosisArena-MCQ reflects only the ability to pick one of four supplied diagnoses given case evidence, not broader clinical reasoning. The same release also reports MedXpertQA-Text 53.88 and HealthBench Professional 45.73, giving a wider medical-text evaluation profile. Benchmark names like "diagnosis" can be over-read by clinicians and adopters, so clarifying what a multiple-choice variant actually measures is important for responsible model evaluation and marketing. It also gives buyers a concrete checklist: ask whether the user supplies the options or expects the model to construct them. In the MCQ variant the case information, examinations and tests are supplied along with four candidate diagnoses, so the task does not test unrestricted differential generation, identifying missing history, or deciding which investigation to request next. The post also notes that HealthBench Professional is rubric-graded and its score is not percentage accuracy, and that the Sante chart lacks enough scoring detail to tell whether the reported value is length-adjusted or unadjusted, so cross-model comparisons need that checked first.

reddit · r/MachineLearning · /u/Expert_Coffee_203 · Sep 9, 13:01

**Background**: DiagnosisArena is a benchmark built to evaluate LLM diagnostic reasoning on thousands of complex clinical case reports drawn from medical journals, and it includes a multiple-choice variant in which the answer set is provided. HealthBench Professional is an open benchmark of the tasks clinicians actually bring to models — care consults such as differential diagnosis and management, clinical writing and documentation, and medical research — graded against physician-written rubrics. MedXpertQA-Text is a board-level medical QA benchmark spanning 17 specialties and 11 body systems. Because these benchmarks measure very different things, a single high number on one of them says little about overall clinical capability.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/html/2505.14107">DiagnosisArena : Benchmarking Diagnostic Reasoningfor Large...</a></li>
<li><a href="https://cdn.openai.com/dd128428-0184-4e25-b155-3a7686c7d744/HealthBench-Professional.pdf">HealthBench Professional: Evaluating Large Language Models on ...</a></li>
<li><a href="https://medxpertqa.github.io/">MedXpertQA</a></li>

</ul>
</details>

**Tags**: `#medical-ai`, `#llm-evaluation`, `#benchmarks`, `#clinical-reasoning`, `#model-critique`

---