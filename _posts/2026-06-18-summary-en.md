---
layout: default
title: "Horizon Summary: 2026-06-18 (EN)"
date: 2026-06-18
lang: en
---

> From 70 items, 29 important content pieces were selected

---

1. [10,000 GitHub Repositories Found Distributing Trojan Malware](#item-1) ⭐️ 9.0/10
2. [GLM-5.2 Is Likely the Most Powerful Open Weights Text-Only LLM](#item-2) ⭐️ 9.0/10
3. [Transformer Co-Author Noam Shazeer Joins OpenAI](#item-3) ⭐️ 8.0/10
4. [Ubiquiti Announces Enterprise NAS Powered by ZFS](#item-4) ⭐️ 8.0/10
5. [Cornell's CS 6120 Advanced Compilers Self-Guided Course Sparks Community Discussion](#item-5) ⭐️ 8.0/10
6. [Modos Unveils 13.3" Color E-Paper Monitor with 60Hz Refresh](#item-6) ⭐️ 8.0/10
7. [Datasette 1.0a34 Introduces Direct Data Manipulation via Web UI](#item-7) ⭐️ 8.0/10
8. [Export Controls on Anthropic AI Fuel DeepSeek’s $7.4B Round and npm Supply Chain Attack](#item-8) ⭐️ 8.0/10
9. [Rosetta Neurons Scale Sublinearly, Becoming More Selective in Larger Models](#item-9) ⭐️ 8.0/10
10. [Microsoft's NextLat: Learning Compact Belief States for 3.3x Faster Inference](#item-10) ⭐️ 8.0/10
11. [Contrastive Targeted SFT to Map Causal Dependencies in LLMs](#item-11) ⭐️ 8.0/10
12. [Hospitals and Universities Repurpose Drugs at 90% Lower Cost](#item-12) ⭐️ 7.0/10
13. [Emacs 31 is around the corner with new daily-used features](#item-13) ⭐️ 7.0/10
14. [AI Inverts Economics of Code Production](#item-14) ⭐️ 7.0/10
15. [Voice Debugging at the Conversation Level Proves More Useful Than Isolated Benchmarks](#item-15) ⭐️ 7.0/10
16. [Apple and Intel Reach Preliminary Chip Foundry Agreement](#item-16) ⭐️ 7.0/10
17. [Xiaomi Open-Sources Miloco 2.0 Smart Home Framework with AI](#item-17) ⭐️ 7.0/10
18. [Swiss Parliament Votes to Lift Ban on New Nuclear Power Plants](#item-18) ⭐️ 6.0/10
19. [Craigslist Founder Craig Newmark Has Donated Over Half a Billion Dollars](#item-19) ⭐️ 6.0/10
20. [W Social and the Performance of European Digital Sovereignty](#item-20) ⭐️ 6.0/10
21. [Submission.Directory: Curated List of Startup Submission Sites](#item-21) ⭐️ 6.0/10
22. [DeepSeek Adds Image Understanding to Its Chat App](#item-22) ⭐️ 6.0/10
23. [New Web Component Defers GIF Loading Until Click](#item-23) ⭐️ 6.0/10
24. [Speculative Decoding: Trending LLM Inference Technique](#item-24) ⭐️ 6.0/10
25. [Analyzing Relative Probe Strength in Language Model Interpretability](#item-25) ⭐️ 6.0/10
26. [Zuckerberg Admits Mistakes in Meta's AI Restructuring, Promises No Layoffs in 2026](#item-26) ⭐️ 6.0/10
27. [ChatGPT Adds Dedicated Scheduled Page and Monitoring Notifications](#item-27) ⭐️ 6.0/10
28. [Google Rumored to Consider CXMT DRAM for AI Chips to Ease Shortages](#item-28) ⭐️ 6.0/10
29. [Google Tests reCAPTCHA Using Camera Hand Gesture Verification](#item-29) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [10,000 GitHub Repositories Found Distributing Trojan Malware](https://orchidfiles.com/github-repositories-distributing-malware/) ⭐️ 9.0/10

A security researcher uncovered 10,000 GitHub repositories actively distributing Trojan malware, exposing critical supply chain risks and the exploitation of open-source trust. This discovery highlights a severe vulnerability in the software supply chain, threatening developers and organizations that rely on open-source code, and could facilitate widespread data breaches. The malware targeted AI coding agents rather than humans, using fresh accounts and frequent commits to appear in search results, while cloning new repositories to avoid detection.

hackernews · theorchid · Jun 18, 11:45 · [Discussion](https://news.ycombinator.com/item?id=48583928)

**Background**: Supply chain security involves safeguarding the software development lifecycle from malicious interference. GitHub, a central open-source platform, facilitates collaboration but can be abused to inject malware into widely used codebases, exploiting the trust model essential to open source.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Supply_chain_security">Supply chain security</a></li>

</ul>
</details>

**Discussion**: Commenters agree that systemic vulnerabilities exist: the malware targets AI agents, GitHub inadequately addresses the issue, and search engines may direct users to malicious repos. Calls for better platform security are prevalent.

**Tags**: `#malware`, `#github`, `#supply-chain-security`, `#cybersecurity`, `#open-source`

---

<a id="item-2"></a>
## [GLM-5.2 Is Likely the Most Powerful Open Weights Text-Only LLM](https://simonwillison.net/2026/Jun/17/glm-52/#atom-everything) ⭐️ 9.0/10

Z.ai released GLM-5.2, a text-only, MIT-licensed 753B Mixture of Experts LLM with a 1 million token context window that ranks as the leading open-weights model on the Artificial Analysis Intelligence Index. This release provides a top-performing, permissively licensed open model that advances open AI research and development, offering capabilities previously reserved for proprietary systems with a large context window suitable for complex tasks. The model has 753B parameters with 40 active per input (MoE), a 1.51TB weight file, MIT license, and a 1M token context window. It is text-only yet ranks second on the Code Arena WebDev leaderboard, and consumes roughly 43,000 output tokens per benchmark task.

rss · Simon Willison · Jun 17, 23:58

**Background**: Mixture of Experts (MoE) is an architecture where only a subset of model parameters (experts) are activated for each input, allowing huge models with reasonable compute. Open weights means the model's trained parameters are shared, but not necessarily the full training pipeline. A token context window defines how many tokens of input the model can process at once.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mixture_of_experts">Mixture of experts - Wikipedia</a></li>
<li><a href="https://opensource.org/ai/open-weights">Open Weights: not quite what you’ve been told – Open Source ...</a></li>
<li><a href="https://www.geeksforgeeks.org/artificial-intelligence/tokens-and-context-windows-in-llms/">Tokens and Context Windows in LLMs - GeeksforGeeks</a></li>

</ul>
</details>

**Tags**: `#AI`, `#LLM`, `#open-source`, `#GLM-5.2`, `#language-model`

---

<a id="item-3"></a>
## [Transformer Co-Author Noam Shazeer Joins OpenAI](https://twitter.com/NoamShazeer/status/2067400851438932297) ⭐️ 8.0/10

Noam Shazeer, co-author of the 'Attention Is All You Need' paper and most recently a Gemini co-lead at Google, is leaving Google to join OpenAI. This move marks his second departure from Google after a brief return via a talent acquisition deal in 2024. Shazeer's move is a major talent coup for OpenAI, bringing deep expertise in the transformer architecture that underpins modern AI. It intensifies the rivalry between Google and OpenAI in the race to develop advanced AI systems. Shazeer originally left Google in 2021 to co-found Character.AI; he returned in 2024 when Google acquired Character.AI's talent in a $2.7B deal, and was named a co-lead of Gemini. His swift departure to OpenAI highlights the fluid talent dynamics in the AI industry.

hackernews · lukasgross · Jun 18, 00:26 · [Discussion](https://news.ycombinator.com/item?id=48578913)

**Background**: The transformer architecture, introduced in the 2017 paper 'Attention Is All You Need' by Google researchers including Noam Shazeer, revolutionized deep learning by enabling efficient parallel processing of sequential data. It became the foundation for large language models like GPT and Gemini. Shazeer is considered one of the key pioneers of this technology.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Transformer_architecture">Transformer architecture</a></li>
<li><a href="https://en.wikipedia.org/wiki/Attention_Is_All_You_Need">Attention Is All You Need - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Community discussion highlights the surprising nature of Shazeer's quick departure after rejoining Google. Some speculate that internal dynamics or the opportunity at OpenAI may have motivated the move. Others express concern about the potential impact on Google's open model development and note the broader trend of high-profile AI researchers hopping between leading labs.

**Tags**: `#AI`, `#transformers`, `#talent-move`, `#OpenAI`, `#Google`

---

<a id="item-4"></a>
## [Ubiquiti Announces Enterprise NAS Powered by ZFS](https://blog.ui.com/article/introducing-enterprise-nas) ⭐️ 8.0/10

Ubiquiti has introduced a new enterprise NAS storage solution built on the ZFS file system, priced at $3,999, featuring dual 25Gb SFP28 ports and redundant power supplies. This marks Ubiquiti’s entry into the enterprise storage market with a ZFS-based offering that promises no monthly fees, potentially disrupting traditional vendors that rely on subscription models, while leveraging ZFS’s data integrity and fault tolerance features. The NAS supports dual 25Gb SFP28 networking, but community members question whether spinning hard drives can fully saturate such high-speed links; practical performance may require extensive tuning, and some remain cautious about Ubiquiti’s enterprise readiness.

hackernews · ksec · Jun 18, 14:24 · [Discussion](https://news.ycombinator.com/item?id=48585866)

**Background**: ZFS is an open-source file system and volume manager known for data integrity, fault tolerance, and efficient delta backups via Merkle trees, originally developed by Sun Microsystems. Ubiquiti is a networking hardware company popular for its UniFi and EdgeMax products, often offering cost-effective, no-subscription solutions that appeal to SMBs and tech enthusiasts. Enterprise NAS devices are used by businesses for centralized data storage with high availability and reliability.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ZFS">ZFS</a></li>
<li><a href="https://en.wikipedia.org/wiki/OpenZFS">OpenZFS - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Community reaction is mixed: many praise the use of ZFS and the absence of monthly fees, but experienced users warn that Ubiquiti’s products often feel like “test-in-prod” and may not be truly enterprise-ready; performance with spinning drives is also a key concern.

**Tags**: `#NAS`, `#ZFS`, `#Ubiquiti`, `#enterprise-storage`, `#announcement`

---

<a id="item-5"></a>
## [Cornell's CS 6120 Advanced Compilers Self-Guided Course Sparks Community Discussion](https://www.cs.cornell.edu/courses/cs6120/2025fa/self-guided/) ⭐️ 8.0/10

The self-guided version of Cornell University's CS 6120: Advanced Compilers course, originally created in 2020, has been shared again on Hacker News, leading to renewed discussion about its content, particularly the section on dynamic compilation. This freely available course is a valuable resource for learning advanced compiler topics, but the community feedback highlights potential gaps in its treatment of modern dynamic compilation techniques, making it important for prospective learners to be aware of its limitations. The dynamic compilation section focuses heavily on trace compilation, which is considered outdated; critics note that important concepts like type feedback, speculation, and deoptimization are missing. Some also question whether the course content is truly 'advanced' as it covers foundational topics like dead code elimination and SSA form.

hackernews · ibobev · Jun 18, 11:04 · [Discussion](https://news.ycombinator.com/item?id=48583606)

**Background**: CS 6120 is a graduate-level compilers course at Cornell University covering topics such as dataflow analysis, optimization, and code generation. Dynamic compilation involves compiling code at runtime to improve performance, with just-in-time (JIT) compilation being a common form. Trace compilation is an older dynamic compilation technique that identifies and optimizes frequently executed paths.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Dynamic_compilation">Dynamic compilation</a></li>
<li><a href="https://www.freecodecamp.org/news/just-in-time-compilation-explained/">Just in Time Compilation Explained</a></li>

</ul>
</details>

**Discussion**: Overall, the community praised the course for its depth and accessibility, but several experts pointed out that the dynamic compilation section is outdated, focusing on trace compilation rather than modern techniques. Some questioned whether the course should be labeled 'advanced' given its inclusion of foundational topics. Others drew comparisons to other compiler resources like Nora Sandler's writing a C compiler.

**Tags**: `#compilers`, `#education`, `#online-course`, `#programming-languages`, `#hackernews`

---

<a id="item-6"></a>
## [Modos Unveils 13.3" Color E-Paper Monitor with 60Hz Refresh](https://spectrum.ieee.org/modos-e-paper-monitor) ⭐️ 8.0/10

Modos, a two-person startup, is developing a 13.3-inch color e-paper monitor with a native resolution of 3200x2400, touch input, and a 60Hz refresh rate, pushing the boundaries of e-paper display technology. This advancement opens up new possibilities for low-power, outdoor-readable monitors that could reduce eye strain for extended productivity work, marking a significant step toward replacing traditional LCD screens for many use cases. The monitor supports a 60Hz refresh rate, which is unusually fast for e-paper technology and may impact panel longevity; specific visible screen dimensions and the exact color technology (e.g., E Ink Kaleido) are not yet confirmed.

hackernews · Vinnl · Jun 18, 11:41 · [Discussion](https://news.ycombinator.com/item?id=48583897)

**Background**: E-paper, or electronic paper, is a display technology that reflects light like ordinary paper, offering high outdoor readability and extremely low power consumption. Traditional e-paper screens have slow refresh rates and are mostly monochrome; color e-paper has been introduced in recent years using technologies like E Ink's Kaleido, but with limitations in color accuracy and refresh speed. External e-ink monitors are a niche product category aimed at reducing eye strain for reading, coding, and writing tasks, but have historically been low-resolution and sluggish.

<details><summary>References</summary>
<ul>
<li><a href="https://grokipedia.com/page/External_E_Ink_Monitor">External E Ink Monitor</a></li>
<li><a href="https://goodereader.com/blog/electronic-readers/the-best-color-e-readers-of-2025">The Best Color e-readers of 2025 - Good e-Reader</a></li>

</ul>
</details>

**Discussion**: Community members expressed excitement about the monitor's specs, with some questioning the impact of a 60Hz refresh rate on panel longevity and others asking about screen dimensions. Comparisons were drawn to the Daylight computer and Boox devices, highlighting a growing interest in auxiliary low-power displays.

**Tags**: `#e-paper`, `#display-technology`, `#hardware`, `#startups`, `#hackernews`

---

<a id="item-7"></a>
## [Datasette 1.0a34 Introduces Direct Data Manipulation via Web UI](https://simonwillison.net/2026/Jun/16/datasette/#atom-everything) ⭐️ 8.0/10

Datasette alpha version 1.0a34 now allows users to insert, edit, and delete rows directly from the table and row pages in its web interface. This long-awaited feature transforms Datasette from a read-only exploration tool into a lightweight data management platform, significantly enhancing its practicality for interactive workflows. The edit and delete operations are accessible as action items on row pages, in addition to the table-level controls. This change was motivated by the recent SQL write support added to Datasette Agent, which highlighted the inconsistency of having write capabilities in the chat interface but not the standard UI.

rss · Simon Willison · Jun 16, 21:31

**Background**: Datasette is an open-source tool by Simon Willison for exploring and publishing SQLite databases. Until now, its web interface was read-only, enabling users to query and browse data but not modify it. Datasette Agent is an extensible AI assistant plugin that can interact with SQLite databases via natural language, and it recently gained the ability to execute write SQL statements. The developer realized that allowing writes through the agent but not the core UI was a significant gap, which directly inspired this update.

<details><summary>References</summary>
<ul>
<li><a href="https://agent.datasette.io/">Datasette Agent: an AI assistant for Datasette to help explore and analyze data in SQLite</a></li>
<li><a href="https://datasette.io/blog/2026/datasette-agent/">Datasette Agent, an extensible AI assistant for Datasette - Datasette Blog</a></li>

</ul>
</details>

**Tags**: `#datasette`, `#release`, `#data exploration`, `#sqlite`, `#user interface`

---

<a id="item-8"></a>
## [Export Controls on Anthropic AI Fuel DeepSeek’s $7.4B Round and npm Supply Chain Attack](https://aiweekly.co/issues/america-blocked-its-best-ai-china-just-raised-74-billion) ⭐️ 8.0/10

The US restricted foreign access to Anthropic’s top AI models, immediately triggering a $7.4 billion funding round for Chinese rival DeepSeek and a surge of government interest in Cohere. Simultaneously, 144 malicious npm packages were discovered poisoning the AI software supply chain to steal credentials. The export controls, intended to protect America’s AI lead, are instead accelerating open-source alternatives in China and exposing critical vulnerabilities in the global AI supply chain, potentially undermining US dominance. DeepSeek’s models employ mixture-of-experts architectures and were trained at a fraction of the cost of US models, yet rival GPT-4 in performance. The npm attack involved stealing publish tokens and injecting code into widely used packages for credential theft and lateral movement.

rss · AI Weekly · Jun 17, 00:00

**Background**: Anthropic is a US AI company known for its Claude models, while DeepSeek is a Chinese startup that gained attention for open-weight models trained efficiently despite US chip sanctions. npm (Node Package Manager) is a registry for JavaScript libraries, often targeted for supply chain attacks where attackers compromise popular packages to distribute malware.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek">DeepSeek</a></li>
<li><a href="https://www.rescana.com/post/in-depth-analysis-supply-chain-poisoning-of-popular-npm-packages-exploiting-event-stream-ua-parser">In-Depth Analysis: Supply Chain Poisoning of Popular npm Packages ...</a></li>

</ul>
</details>

**Tags**: `#AI policy`, `#export controls`, `#supply chain security`, `#DeepSeek`, `#npm`

---

<a id="item-9"></a>
## [Rosetta Neurons Scale Sublinearly, Becoming More Selective in Larger Models](https://www.reddit.com/r/MachineLearning/comments/1u9g7lk/neuron_populations_exhibit_divergent_selectivity/) ⭐️ 8.0/10

A new study reveals that Rosetta Neurons, universal across architectures and tasks, exhibit sublinear scaling with model size and become more selective and monosemantic. A single Rosetta Neuron can effectively filter data for pretraining, nearly matching oracle performance. This links interpretability with scaling laws, indicating that larger models develop more specialized, interpretable features. It also offers a practical, lightweight data filtering method that could reduce training costs. The neurons follow a sublinear power law (exponent less than 1), their monosemanticity is quantified by a Feature Monosemanticity Score, and using a single neuron's activations for data filtering achieves near-oracle results.

reddit · r/MachineLearning · /u/avd4292 · Jun 18, 19:40

**Background**: Rosetta Neurons were first introduced in 2023 as a technique to find neurons that represent the same visual concepts across different models. Neural scaling laws describe power law relationships between model size, dataset size, and performance. Monosemanticity refers to features that are individually interpretable, often extracted using sparse autoencoders.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2306.09346">[2306.09346] Rosetta Neurons: Mining the Common Units in a Model Zoo</a></li>
<li><a href="https://transformer-circuits.pub/2024/scaling-monosemanticity/">Scaling Monosemanticity: Extracting Interpretable Features from Claude 3 Sonnet</a></li>
<li><a href="https://www.pnas.org/doi/10.1073/pnas.2311878121">Explaining neural scaling laws - PNAS</a></li>

</ul>
</details>

**Tags**: `#interpretability`, `#scaling-laws`, `#neural-networks`, `#representation-learning`, `#research`

---

<a id="item-10"></a>
## [Microsoft's NextLat: Learning Compact Belief States for 3.3x Faster Inference](https://www.reddit.com/r/MachineLearning/comments/1u84mio/nextlatent_prediction_transformers_r/) ⭐️ 8.0/10

Microsoft Research introduced Next-Latent Prediction (NextLat), a self-supervised method that trains transformers to predict their own next latent state in addition to the next token. This yields compact belief states, better data efficiency, and up to 3.3x faster inference via self-speculative decoding. NextLat moves beyond myopic next-token prediction to build richer world models, improving reasoning and planning capabilities. The self-speculative decoding speedup removes the need for external draft models, making large language models more practical for real-time applications. NextLat adds a loss that predicts the next latent state from the current latent and next token, providing denser supervision than one-hot tokens. Self-speculative decoding uses the model's own layers for drafting and verification, eliminating external components.

reddit · r/MachineLearning · /u/jayden_teoh_ · Jun 17, 08:44

**Background**: Next-token prediction, the standard for autoregressive models, can be myopic because it focuses on local structure rather than long-term dependencies. Speculative decoding accelerates inference by using a small draft model to propose tokens verified by a large model; self-speculative decoding achieves this by using a subset of the model's own layers, as in LayerSkip.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2511.05963">[2511.05963] Next-Latent Prediction Transformers Learn Compact World Models</a></li>
<li><a href="https://www.emergentmind.com/topics/next-latent-prediction-nextlat">Next-Latent Prediction Overview</a></li>

</ul>
</details>

**Tags**: `#transformers`, `#self-supervised learning`, `#representation learning`, `#speculative decoding`, `#language models`

---

<a id="item-11"></a>
## [Contrastive Targeted SFT to Map Causal Dependencies in LLMs](https://www.reddit.com/r/MachineLearning/comments/1u8if6l/contrastive_targeted_sft_as_a_mechinterp_method/) ⭐️ 8.0/10

A post on r/MachineLearning proposes an experimental plan to build a causal dependency graph of capability dimensions inside large language models using contrastive targeted supervised fine-tuning (SFT) and ablation. The method involves training contrastive checkpoints on one dimension, locating circuits, and then measuring cross-dimension degradation to infer causal links. This closed-loop approach could reveal structural relationships between LLM capabilities, guiding more efficient training strategies and better behavior control. It bridges mechanistic interpretability and targeted fine-tuning in a practical framework. The plan contrasts two checkpoints from the same base, trained on deep vs. shallow examples of a dimension, to locate circuits via comparison, then ablates heads and uses a 40-domain judge to detect score drops in other dimensions. Open challenges include distinguishing direct from indirect causal effects and validating the graph with activation steering diagnostics, though the author lacks an ML background and experimental results.

reddit · r/MachineLearning · /u/Substantial_Diver469 · Jun 17, 18:31

**Background**: Mechanistic interpretability aims to reverse-engineer neural networks by analyzing internal computations, similar to understanding binary programs. Ablation studies remove components (e.g., attention heads) to assess their impact, a common interpretability tool. Contrastive training uses paired examples to highlight differences, often to strengthen specific capabilities. Targeted SFT fine-tunes a model on curated data to improve particular skills.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mechanistic_interpretability">Mechanistic interpretability</a></li>
<li><a href="https://en.wikipedia.org/wiki/Ablation_(artificial_intelligence)">Ablation (artificial intelligence) - Wikipedia</a></li>
<li><a href="https://www.alignmentforum.org/posts/jP9KDyMkchuv6tHwm/how-to-become-a-mechanistic-interpretability-researcher">How To Become A Mechanistic Interpretability Researcher</a></li>

</ul>
</details>

**Tags**: `#mechanistic interpretability`, `#contrastive training`, `#causal discovery`, `#fine-tuning`, `#large language models`

---

<a id="item-12"></a>
## [Hospitals and Universities Repurpose Drugs at 90% Lower Cost](https://www.kcl.ac.uk/news/hospitals-and-universities-repurposing-drugs-at-90-lower-cost) ⭐️ 7.0/10

Hospitals and universities are successfully repurposing existing drugs for new indications, achieving dramatic cost reductions—often up to 90%—by bypassing expensive patented alternatives. This approach exposes how patent strategies and pricing structures inflate drug costs, and demonstrates a practical path to making essential treatments more affordable and widely available, especially for rare diseases. Ophthalmologists use bevacizumab (Avastin) for macular degeneration instead of the nearly identical ranibizumab (Lucentis), at $50 versus $1,500 per dose. Similarly, esketamine (Spravato) is a patented isomer of ketamine, often costing thousands despite being possibly less effective than generic ketamine.

hackernews · giuliomagnifico · Jun 18, 10:33 · [Discussion](https://news.ycombinator.com/item?id=48583386)

**Background**: Drug repurposing finds new uses for approved drugs, slashing development costs. Pharmaceutical companies often patent slightly modified versions of off-patent drugs to maintain high prices. This news highlights how hospitals and universities are directly using cheaper, clinically equivalent off-patent drugs to circumvent such practices.

**Discussion**: Commenters highlighted stark cost differences between nearly identical drugs due to patenting, such as Avastin ($50) versus Lucentis ($1,500). They also discussed esketamine (Spravato), a patented and less effective version of generic ketamine, costing thousands. The discussion strongly supports repurposing initiatives, especially for rare diseases, and widely criticizes pharmaceutical pricing and influence.

**Tags**: `#drug-repurposing`, `#healthcare`, `#patents`, `#innovation`, `#hackernews`

---

<a id="item-13"></a>
## [Emacs 31 is around the corner with new daily-used features](https://www.rahuljuliato.com/posts/emacs-31-around-the-corner) ⭐️ 7.0/10

A user has shared features they are already using from the upcoming Emacs 31 release, highlighting practical improvements ahead of the official launch. The announcement sparked vibrant community discussion, reaffirming Emacs' enduring value, hyper-configurability, and growing AI integration, proving the editor's relevance even among modern alternatives. While specific features were not detailed in the summary, the discussion emphasized Emacs' efficient cursor movement, LLM agent setup via init.el, and stability with user-controlled upgrades.

hackernews · frou_dh · Jun 18, 12:10 · [Discussion](https://news.ycombinator.com/item?id=48584135)

**Background**: GNU Emacs is a highly extensible, text-based editor first released in 1976, known for its steep learning curve but powerful customization through Emacs Lisp. It remains popular among developers who value full control over their tools.

**Discussion**: Comments ranged from users with 34 years of Emacs experience praising its keyboard shortcuts and widespread support, to those noting integration with Claude AI and LLM agents. Many highlighted the editor's opt-in, stable nature compared to forced modern updates.

**Tags**: `#emacs`, `#text-editors`, `#release-notes`, `#productivity`, `#open-source`

---

<a id="item-14"></a>
## [AI Inverts Economics of Code Production](https://simonwillison.net/2026/Jun/17/charity-majors/#atom-everything) ⭐️ 7.0/10

Charity Majors highlights that in 2025, AI made code generation effectively free and instant, transforming lines of code from treasured assets to disposable commodities. This shift demands greater engineering discipline because code is no longer a scarce resource; engineers must focus on architecture, testing, and maintainability over mere production. The quote is from Charity Majors' Substack post 'AI demands more engineering discipline. Not less,' where she argues that with cheap code, the need for rigorous practices like review and testing increases.

rss · Simon Willison · Jun 17, 17:12

**Background**: The traditional software development model treated code as a valuable, labor-intensive asset; generative AI tools like LLMs can now produce large amounts of code quickly, prompting a rethink of software engineering practices.

**Tags**: `#ai`, `#generative-ai`, `#ai-assisted-programming`, `#software-engineering`, `#economics`

---

<a id="item-15"></a>
## [Voice Debugging at the Conversation Level Proves More Useful Than Isolated Benchmarks](https://www.reddit.com/r/MachineLearning/comments/1u99fe5/voice_debugging_at_the_conversation_level_seems/) ⭐️ 7.0/10

A practitioner reports that isolated metrics like STT accuracy and latency fail to capture emergent conversational issues, and instead finds conversation-level debugging more effective for voice AI in production. They are now experimenting with automated conversation-level QA to scale this approach. This highlights a critical gap in current evaluation methods for voice agents, as traditional benchmarks may miss issues that degrade user experience. It matters to AI practitioners deploying voice systems, encouraging a shift toward holistic, interaction-focused quality assurance to build more natural conversational agents. Emergent issues include cumulative timing mistakes, repeated confirmations causing friction, and unnatural turn-taking that alter user behavior. The team now focuses on identifying recurring conversational patterns rather than single model failures, using automated tools to review traces at scale.

reddit · r/MachineLearning · /u/OwlZealousideal4779 · Jun 18, 15:29

**Background**: Voice AI systems consist of multiple components: Speech-to-Text (STT), natural language understanding, dialogue management, and Text-to-Speech (TTS). Traditional benchmarks evaluate each component in isolation, measuring metrics like word error rate or task completion. However, real conversations involve complex dynamics where small interactions can compound, leading to failures not seen in isolated tests. Conversation-level debugging examines the full interaction trace, capturing the holistic user experience.

<details><summary>References</summary>
<ul>
<li><a href="https://www.braintrust.dev/articles/how-to-evaluate-voice-agents">How to evaluate voice agents - Articles - Braintrust</a></li>
<li><a href="https://docs.vapi.ai/debugging">Debugging voice agents | Vapi</a></li>

</ul>
</details>

**Tags**: `#voice debugging`, `#conversational AI`, `#evaluation metrics`, `#multi-turn dialogue`, `#quality assurance`

---

<a id="item-16"></a>
## [Apple and Intel Reach Preliminary Chip Foundry Agreement](https://t.me/zaihuapd/42031) ⭐️ 7.0/10

Apple and Intel have reached a preliminary agreement for Intel to manufacture some chips for Apple devices, following a year-long negotiation and finalization of a contract in recent months, though specific product lines remain unclear. This marks a significant diversification of Apple's foundry partnerships beyond TSMC, potentially reshaping the semiconductor manufacturing landscape, with US government involvement highlighting strategic supply chain interests. The US government played a deep role, with the Commerce Secretary repeatedly lobbying Apple's Tim Cook; Intel now counts Nvidia, SpaceX, and Apple among its foundry clients, but the specific chip types (iPhone, iPad, or Mac) are not yet disclosed.

telegram · zaihuapd · Jun 18, 09:19

**Background**: Chip foundry refers to a semiconductor fabrication plant that manufactures chips designed by other companies. Apple has traditionally relied on TSMC for its advanced processors, while Intel historically focused on its own chips but recently opened its fabs to external customers as part of its IDM 2.0 strategy. The US government is actively promoting domestic chip manufacturing through the CHIPS Act to reduce reliance on Asian foundries.

**Tags**: `#semiconductors`, `#Apple`, `#Intel`, `#foundry`, `#chip manufacturing`

---

<a id="item-17"></a>
## [Xiaomi Open-Sources Miloco 2.0 Smart Home Framework with AI](https://github.com/XiaoMi/xiaomi-miloco) ⭐️ 7.0/10

Xiaomi has released Miloco 2.0, an open-source smart home framework that uses Mi Home cameras and the MiMo large model to enable proactive device control, identity recognition, home memory, and task automation. This release pushes open-source smart home AI forward, potentially influencing interoperability standards and encouraging community innovation, though its non-commercial license and cloud dependency may limit widespread adoption. Miloco 2.0 runs on macOS or Linux (or WSL on Windows), requires a Xiaomi account and MiMo API key, and incurs ongoing cloud API costs for perception and reasoning; it is strictly for non-commercial use.

telegram · zaihuapd · Jun 18, 12:23

**Background**: Miloco is Xiaomi's open-source whole-home intelligence solution. MiMo is their in-house reasoning-focused large language model, developed with multi-token prediction and reinforcement learning. OpenClaw is an AI agent framework; Miloco operates as a plugin within it, leveraging camera audio and video as perception inputs.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/XiaoMi/xiaomi-miloco">GitHub - XiaoMi/xiaomi-miloco: Xiaomi Miloco · GitHub</a></li>
<li><a href="https://en.wikipedia.org/wiki/Xiaomi_MiMo">Xiaomi MiMo - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#smart-home`, `#open-source`, `#AI`, `#IoT`, `#Xiaomi`

---

<a id="item-18"></a>
## [Swiss Parliament Votes to Lift Ban on New Nuclear Power Plants](https://www.bluewin.ch/en/news/switzerland/parliament-lifts-ban-on-new-nuclear-power-plants-3257535.html) ⭐️ 6.0/10

Switzerland's parliament has voted to lift the long-standing ban on constructing new nuclear power plants, though the decision will still need to pass a public referendum. This policy reversal could revitalize Switzerland's nuclear energy sector, reduce dependence on imported electricity, and contribute to carbon-free energy goals, reflecting a broader re-evaluation of nuclear power worldwide. The ban was introduced after the 2011 Fukushima accident; the parliamentary vote was contentious, and the final decision will be made via a national referendum, reflecting ongoing political and public divisions.

hackernews · leonidasrup · Jun 18, 14:17 · [Discussion](https://news.ycombinator.com/item?id=48585746)

**Background**: Switzerland currently generates around a third of its electricity from four aging nuclear reactors. Following the 2011 Fukushima disaster, the government decided to phase out nuclear power and banned the construction of new plants. However, concerns over energy security, rising electricity demand, and climate targets have led to a reconsideration of this policy, culminating in the parliamentary vote to lift the ban.

**Discussion**: The community discussion reflects a polarized debate: some users argue nuclear power is misunderstood and necessary for clean energy, while others point to high project costs and Switzerland's unique seasonal energy challenges. There is interest in new technologies like SMRs, but skepticism about whether the public referendum will succeed given political opposition.

**Tags**: `#nuclear energy`, `#energy policy`, `#Switzerland`, `#legislation`, `#environment`

---

<a id="item-19"></a>
## [Craigslist Founder Craig Newmark Has Donated Over Half a Billion Dollars](https://www.independent.co.uk/us/money/craigslist-multimillionaire-craig-newmark-b2980681.html) ⭐️ 6.0/10

Craig Newmark, the founder of online classifieds site Craigslist, has donated more than $500 million to charitable causes. This donation highlights how tech wealth can be directed toward public good. However, it also reignites scrutiny of Craigslist's business practices, including its role in facilitating scams and its failure to evolve against competitors like Facebook Marketplace. The donations come from Newmark's personal wealth, not Craigslist's operations. Meanwhile, users report that roughly 25% of housing ads on the site are fraudulent, and the platform has been largely supplanted by Facebook Marketplace in many regions.

hackernews · Tomte · Jun 18, 16:55 · [Discussion](https://news.ycombinator.com/item?id=48588216)

**Background**: Craigslist, founded by Craig Newmark in 1995, started as an email list for local events in San Francisco and evolved into one of the world's most popular online classifieds platforms, known for its simple design and largely free listings. Newmark stepped down as CEO in 2000 but remained involved. Over the years, he has donated to journalism, veterans' support, and cybersecurity initiatives through his philanthropic organization, Craig Newmark Philanthropies.

**Discussion**: Commenters expressed mixed views: some admire Newmark's unpretentious lifestyle, noting his past remark about good water pressure being enough. Others criticized Craigslist for enabling a high rate of rental scams (around 25%) and failing to innovate, allowing Facebook Marketplace to dominate. Some also lamented the missed financial opportunity to grow the company into a tech giant.

**Tags**: `#Philanthropy`, `#Craigslist`, `#Tech Business`, `#Online Scams`, `#Classifieds`

---

<a id="item-20"></a>
## [W Social and the Performance of European Digital Sovereignty](https://blog.elenarossini.com/w-social-public-institutions-and-the-theater-of-european-digital-sovereignty/) ⭐️ 6.0/10

A blog post critically analyzes W Social, a new European social network, as a performative act in EU digital sovereignty. Community comments point out the platform's similarities to Truth Social, the lack of attention to open alternatives like Eurosky, and potential profit-driven motives behind the venture. This critique questions the genuineness of EU digital sovereignty initiatives, suggesting they may be more about political staging than real technological independence. The community skepticism could influence user trust and adoption of such platforms. W Social is an LLC founded by a person with a finance background, requiring human verification but already shown to allow multiple accounts. It is hosted in Europe, governed by EU law, and its launch was amplified by high-profile EU politicians and the WEF, while open-source alternative Eurosky on ATproto received no media coverage.

hackernews · nemoniac · Jun 18, 12:46 · [Discussion](https://news.ycombinator.com/item?id=48584497)

**Background**: European digital sovereignty refers to the EU's push to reduce dependence on non-European tech giants and assert control over digital infrastructure and data. ATproto is an open protocol for decentralized social networking, adopted by BlueSky. Truth Social is a social media platform launched by Donald Trump for his supporters, often seen as a partisan echo chamber. Eurosky is a European ATproto-based social network built transparently by a non-profit.

<details><summary>References</summary>
<ul>
<li><a href="https://wsocial.news/">W - The European social network for verified humans</a></li>

</ul>
</details>

**Discussion**: Commenters are generally skeptical, viewing W Social as shady and potentially a European version of Truth Social for EU politicians to control their reach. They note the irony of human verification being easily bypassed, and criticize the media's disregard for transparent alternatives like Eurosky. Some suspect profit motives and question the platform's viability.

**Tags**: `#European digital sovereignty`, `#social networks`, `#W Social`, `#tech policy`, `#platform governance`

---

<a id="item-21"></a>
## [Submission.Directory: Curated List of Startup Submission Sites](https://www.submission.directory/) ⭐️ 6.0/10

A new website, submission.directory, offers a curated directory of websites that accept startup submissions, providing a centralized resource for founders seeking exposure and backlinks. This resource streamlines the process of finding submission opportunities, which can significantly aid startup marketing and SEO efforts, especially given the ongoing challenges of link building and spam. The directory is manually curated, and community comments highlight the prevalence of spam, such as fake podcast submissions for backlinks, and share alternative lists and historical context from the 90s.

hackernews · azeemkafridi · Jun 18, 15:12 · [Discussion](https://news.ycombinator.com/item?id=48586631)

**Background**: Startup directories are platforms where companies can list their products to gain visibility and backlinks, which are crucial for search engine optimization. The practice dates back to the 90s with services like Submit It, and evolved through platforms like BetaList and Product Hunt. Backlinks from reputable directories can improve a site's search ranking, but they also attract spammers.

**Discussion**: Commenters shared a rich history: marc recounted building BetaList 16 years ago and later submit.co; renegat0x0 provided an open-source database; wenbin detailed spam via fake RSS feeds; susam listed personal directories for indie sites; and transitorykris noted the concept's 90s roots. Overall, the discussion acknowledged the resource's utility while underscoring spam challenges and the cyclical nature of SEO tactics.

**Tags**: `#startup`, `#marketing`, `#directories`, `#backlinks`, `#seo`

---

<a id="item-22"></a>
## [DeepSeek Adds Image Understanding to Its Chat App](https://chat.deepseek.com/) ⭐️ 6.0/10

DeepSeek's chat app now supports image understanding, allowing users to upload pictures and receive descriptions of their content, but it does not generate or modify images. This update brings multimodal capabilities to DeepSeek, enabling it to compete with other AI chatbots that offer vision features and opening up new use cases like image analysis and accessibility. The feature is limited to understanding; no image generation or editing is available. Some users report quirks like replies in Chinese and a login screen requirement, and DeepSeek still lacks native text-to-speech or speech-to-text.

hackernews · RIshabh235 · Jun 18, 06:17 · [Discussion](https://news.ycombinator.com/item?id=48581458)

**Background**: DeepSeek is a Chinese AI company known for open-weight large language models like DeepSeek-R1, which rival GPT-4 at lower cost. Multimodal AI refers to models that process multiple types of data (text, images, audio, etc.) together. Image understanding is a common feature in modern chatbots, enabling them to analyze visual content.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek">DeepSeek</a></li>
<li><a href="https://www.explainx.ai/blog/what-is-multimodal-ai-complete-guide-2026">What Is Multimodal AI? Text, Image, Audio, and Video Models ...</a></li>

</ul>
</details>

**Discussion**: Community feedback is mixed: some note the lack of image generation and other features like text-to-speech, while others point out issues such as Chinese-language glitches and a redirect to a login screen. A few users discuss integrating it with local tools for practical use cases like generating alt text for images.

**Tags**: `#deepseek`, `#vision`, `#multimodal-ai`, `#chatbot`, `#ai-updates`

---

<a id="item-23"></a>
## [New Web Component Defers GIF Loading Until Click](https://simonwillison.net/2026/Jun/17/click-to-play-component/#atom-everything) ⭐️ 6.0/10

Simon Willison released a progressive enhancement web component, <click-to-play>, that delays loading animated GIFs until the user clicks, using a static first frame as a placeholder. This reduces unnecessary bandwidth and improves page performance by preventing large GIFs from loading automatically, benefiting users on slow connections and mobile devices. The component uses progressive enhancement, so the GIF link and static image fallback remain accessible without JavaScript. It only loads the full GIF when the user clicks the play button.

rss · Simon Willison · Jun 17, 03:56

**Background**: Web Components are a set of standard technologies allowing custom reusable HTML elements. Progressive enhancement is a strategy of providing basic functionality to all, then enhancing for capable browsers. Animated GIFs can be large and slow down page loading; this component defers their loading until user interaction.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Web_Components">Web Components</a></li>
<li><a href="https://en.wikipedia.org/wiki/Progressive_enhancement">Progressive enhancement</a></li>
<li><a href="https://developer.mozilla.org/en-US/docs/Glossary/Progressive_Enhancement">Progressive enhancement - Glossary | MDN - MDN Web Docs</a></li>

</ul>
</details>

**Tags**: `#web components`, `#gif`, `#progressive-enhancement`, `#javascript`, `#performance`

---

<a id="item-24"></a>
## [Speculative Decoding: Trending LLM Inference Technique](https://www.reddit.com/r/MachineLearning/comments/1u83kzt/what_is_speculative_decoding_trending_on/) ⭐️ 6.0/10

Speculative decoding is currently trending on Papers with Code, and SGLang published a blog post detailing how they achieve state-of-the-art inference latencies using Modal and Z.ai's DFlash speculative decoding models. This technique addresses the critical bottleneck of slow token generation in large models, enabling faster, more cost-effective inference while maintaining output quality. SGLang's integration with DFlash shows practical state-of-the-art performance. Speculative decoding leverages a fast draft model to propose tokens and a larger target model for parallel verification. Z.ai's DFlash employs a diffusion-based method to draft multiple tokens simultaneously, and SGLang's latest blog details its use with Modal to achieve top-tier latencies for LLM serving.

reddit · r/MachineLearning · /u/NielsRogge · Jun 17, 07:41

**Background**: Large language models typically generate text one token at a time, which can be slow for long responses. Speculative decoding accelerates this by using a small, fast 'draft' model to propose several future tokens, which the larger target model then verifies in parallel. SGLang is an open-source LLM serving framework that supports high-throughput inference and features like speculative decoding. Z.ai's DFlash is a drafting method that employs diffusion to predict multiple tokens at once. Modal is a cloud platform that provides on-demand GPU resources, making it easier to deploy such optimized inference pipelines.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/SGLang">SGLang</a></li>
<li><a href="https://www.localainews.co/news/tools/z-lab-dflash-turbocharges-local-ai-text-generation/">Z -Lab DFlash Turbocharges Local AI Text Generation | Local AI News</a></li>

</ul>
</details>

**Tags**: `#speculative-decoding`, `#large-language-models`, `#inference-optimization`, `#SGLang`, `#paperswithcode`

---

<a id="item-25"></a>
## [Analyzing Relative Probe Strength in Language Model Interpretability](https://www.reddit.com/r/MachineLearning/comments/1u8lo60/how_do_you_analyze_the_relative_strength_of/) ⭐️ 6.0/10

A Reddit user seeks systematic ways to gauge probe strength when analyzing language models, focusing on balancing classifier capacity with the model's complexity and on finding theoretical grounding such as Nyquist-like guarantees. Improving probe evaluation methods could lead to more reliable insights into language models' internal representations, crucial for safety and trust in AI systems. The post notes that small vocabulary size can inflate probe accuracy, and examples like Gemini misspelling letter counts suggest probes may not reflect true model knowledge; it also questions whether frameworks like Nyquist sampling could bound probe reliability.

reddit · r/MachineLearning · /u/RepresentativeBee600 · Jun 17, 20:29

**Background**: Probing classifiers are a common interpretability technique where simple classifiers (e.g., logistic regression) are trained on a model's hidden states to detect encoded information like word position. Circuit analysis maps computational subgraphs underlying behaviors. Reliable probing is essential to avoid spurious conclusions, and the Nyquist theorem (originally from signal processing) is occasionally invoked as an analogy for sufficient data sampling in model evaluation.

<details><summary>References</summary>
<ul>
<li><a href="https://mbrenndoerfer.com/writing/probing-classifiers">Probing Classifiers : Decoding What Language Models Learn...</a></li>
<li><a href="https://transformer-circuits.pub/2025/attribution-graphs/methods.html">Circuit Tracing: Revealing Computational Graphs in Language Models</a></li>

</ul>
</details>

**Tags**: `#probing`, `#interpretability`, `#language-models`, `#circuit-analysis`, `#factuality`

---

<a id="item-26"></a>
## [Zuckerberg Admits Mistakes in Meta's AI Restructuring, Promises No Layoffs in 2026](https://t.me/zaihuapd/42024) ⭐️ 6.0/10

Meta CEO Mark Zuckerberg admitted in an internal memo that the company's resource reallocation toward AI caused chaos and mistakes. He pledged more stability, no company-wide layoffs in 2026, increased team-building spending, hackathons, and fixes for overly flat management in some AI teams. This candid admission reveals the internal turmoil at a tech giant during a strategic AI pivot, highlighting the human and organizational cost of such transitions. It directly affects employee morale and retention, and signals leadership's effort to stabilize the company. In May, Meta laid off nearly 8,000 employees and reassigned about 7,000 to AI roles. Zuckerberg also mentioned that rumors of a stock issuance caused a stock price drop of over 5%, and he intends to address extreme flat management structures in AI teams.

telegram · zaihuapd · Jun 18, 03:35

**Background**: Meta has been aggressively investing in AI, leading to a significant internal restructuring. Earlier this year, the company laid off thousands and moved many employees into AI-focused positions, creating organizational instability amid the tech industry's broader AI race.

**Tags**: `#Meta`, `#AI`, `#Management`, `#Layoffs`, `#Tech News`

---

<a id="item-27"></a>
## [ChatGPT Adds Dedicated Scheduled Page and Monitoring Notifications](https://help.openai.com/en/articles/10291617-scheduled-tasks-in-chatgpt) ⭐️ 6.0/10

OpenAI has updated ChatGPT's scheduled tasks with a new 'Scheduled' sidebar page for centralized management of one-time and recurring tasks, and added monitoring tasks that can notify users of important changes. This improvement makes task automation more accessible and organized, benefiting paid users who rely on ChatGPT for reminders and periodic checks, and signals OpenAI's focus on agentic capabilities. It is available on web and mobile for Plus, Pro, Business, and Enterprise users, but not on desktop or Codex. Active task limits range from 3 to 15 depending on the plan, and voice conversations and GPTs are not supported.

telegram · zaihuapd · Jun 18, 04:20

**Background**: ChatGPT first introduced scheduled tasks earlier, letting users set automated prompts at set times. This update brings a dedicated interface and proactive monitoring. GPTs are custom AI assistants built by users, and Codex is a separate OpenAI product for AI-assisted coding—neither integrates with these tasks.

<details><summary>References</summary>
<ul>
<li><a href="https://openai.com/index/introducing-gpts/">Introducing GPTs - OpenAI</a></li>
<li><a href="https://openai.com/index/openai-codex/">OpenAI Codex</a></li>

</ul>
</details>

**Tags**: `#ChatGPT`, `#OpenAI`, `#feature update`, `#scheduling`, `#automation`

---

<a id="item-28"></a>
## [Google Rumored to Consider CXMT DRAM for AI Chips to Ease Shortages](https://wccftech.com/a-wild-rumor-linked-to-sundar-pichai-suggests-google-is-evaluating-the-procurement-of-memory-chips-from-chinas-cxmt/) ⭐️ 6.0/10

A rumor suggests Google is evaluating the procurement of DRAM chips from China's CXMT, potentially for its next-generation Humufish AI chips, to address ongoing memory shortages and price pressures. The rumor, originating from social media, remains unconfirmed. If true, this could disrupt the long-standing DRAM market dominated by Samsung, SK Hynix, and Micron, signaling a major shift in supply chain geopolitics and potentially accelerating the adoption of Chinese memory in global tech products. It is unclear whether these chips would be used in Pixel phones, TPUs, or cloud services; speculation centers on the Humufish TPU, for which Google aims to produce 3.5 million units by the end of 2028. CXMT currently produces DDR4 and LPDDR4 memory on a 19nm process and is expanding capacity.

telegram · zaihuapd · Jun 18, 06:14

**Background**: CXMT (ChangXin Memory Technologies) is a Chinese DRAM manufacturer founded in 2016, aiming to reduce China's reliance on foreign memory chips. The global DRAM market has been dominated by Samsung, SK Hynix, and Micron for decades. Google's custom AI chips, called Tensor Processing Units (TPUs), are designed for machine learning workloads; the upcoming Humufish TPU is a next-gen design expected to use advanced packaging like Intel's EMIB-T.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/CXMT">CXMT</a></li>
<li><a href="https://semiwiki.com/forum/threads/ming-chi-kuo-on-intels-emib-t-packaging-for-google-tpu-v8e-humufish.25038/">Ming-Chi Kuo on Intel's EMIB-T packaging for Google TPU v8e (Humufish) | SemiWiki</a></li>

</ul>
</details>

**Tags**: `#Google`, `#DRAM`, `#CXMT`, `#semiconductors`, `#rumor`

---

<a id="item-29"></a>
## [Google Tests reCAPTCHA Using Camera Hand Gesture Verification](https://www.ithome.com/0/966/252.htm) ⭐️ 6.0/10

Google is testing a new version of reCAPTCHA that requires users to wave their hand in front of a camera; the system analyzes 21 hand landmarks to distinguish humans from bots. This test signals a shift toward biometric authentication for bot detection, which could raise user privacy concerns but also improve security against automated attacks like credential stuffing. The system uses hand gesture analysis, likely employing models like MediaPipe's hand landmarker, which detects 21 3D landmarks per hand; Google states that videos are not linked to user identity, no audio is recorded, and data is deleted after verification.

telegram · zaihuapd · Jun 18, 16:39

**Background**: reCAPTCHA is Google's bot detection service that has evolved from text-based challenges to risk analysis, and now potentially to biometric gestures. MediaPipe is an open-source framework by Google that provides real-time hand landmark detection, identifying 21 points per hand. Credential stuffing is a cyberattack where stolen credentials are used to gain unauthorized access, which such verifications aim to prevent.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/prashver/hand-landmark-recognition-using-mediapipe">Hand Landmark Recognition using MediaPipe - GitHub</a></li>
<li><a href="https://en.wikipedia.org/wiki/Credential_stuffing">Credential stuffing - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#reCAPTCHA`, `#biometrics`, `#web security`, `#computer vision`, `#authentication`

---