---
layout: default
title: "Horizon Summary: 2026-07-04 (EN)"
date: 2026-07-04
lang: en
---

> From 55 items, 21 important content pieces were selected

---

1. [CDD Recovers Verbatim Fine-Tuning Data Using Only Logit Access](#item-1) ⭐️ 9.0/10
2. [YouTube Prompt Injection Vulnerability Leaks Private Video Titles](#item-2) ⭐️ 8.0/10
3. [Potential Session/Cache Leakage Reported Across LLM APIs, Likely Hallucination](#item-3) ⭐️ 8.0/10
4. [JWST's 'Little Red Dots' May Be Black Hole Stars, Sparking Debate](#item-4) ⭐️ 8.0/10
5. [Current AI Launches Open Source AI Gap Map with 421 Products](#item-5) ⭐️ 8.0/10
6. [HAT-4D: 4D Interactive Scene Generation from Monocular Video](#item-6) ⭐️ 8.0/10
7. [Tencent's Atuin AI Outperforms Claude Mythos on CyberGym at Fraction of Cost](#item-7) ⭐️ 8.0/10
8. [South Korea Plans 800 Trillion Won Semiconductor Cluster to Double DRAM Output](#item-8) ⭐️ 8.0/10
9. [Anna's Archive Offers $200K Bounty for Scanning All Google Books](#item-9) ⭐️ 7.0/10
10. [Comprehensive Guide to Understanding htop/top Metrics on Linux](#item-10) ⭐️ 7.0/10
11. [Maybe You Should Learn Something](#item-11) ⭐️ 7.0/10
12. [Josh W. Comeau Reports AI-Driven 50% Drop in Course Sales](#item-12) ⭐️ 7.0/10
13. [BaryGraph: Knowledge Graph with Relationships Embedded as First-Class Documents](#item-13) ⭐️ 7.0/10
14. [NASA Launches LINK Satellite to Boost Swift Telescope's Orbit](#item-14) ⭐️ 7.0/10
15. [Huawei Proposes 'Tao's Law' for Semiconductor Scaling via Time Reduction](#item-15) ⭐️ 7.0/10
16. [iOS 27 to Introduce Trust Insights for On-Device Scam Detection](#item-16) ⭐️ 7.0/10
17. [Fable's Judgment for Testing and Model Delegation Saves Tokens](#item-17) ⭐️ 6.0/10
18. [HexGrid Cloud Invites Community to Choose LLMs and GPUs for Benchmarking](#item-18) ⭐️ 6.0/10
19. [Is Safety Training Worth It If Fine-Tuning Breaks It Quickly?](#item-19) ⭐️ 6.0/10
20. [Huawei Mate 80 Pro Gaming Efficiency Surpasses Snapdragon 8 Gen3 via HarmonyOS](#item-20) ⭐️ 6.0/10
21. [Linux Tops 2026 CVE Charts, Kernel Maintainer Calls It a Positive Sign](#item-21) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [CDD Recovers Verbatim Fine-Tuning Data Using Only Logit Access](https://www.reddit.com/r/MachineLearning/comments/1umn2dk/contrastive_decoding_diffing_cdd_recovering/) ⭐️ 9.0/10

Researchers introduced Contrastive Decoding Diffing (CDD), a grey-box method that recovers verbatim fine-tuning data by comparing base and fine-tuned model logits, achieving high recovery scores without weight access. CDD exposes a serious privacy risk: fine-tuning data can be extracted even under grey-box access, challenging assumptions about data protection in LLM deployments and affecting anyone using fine-tuned models with sensitive data. CDD requires only logit access and uses a single default configuration, recovering data across model sizes (1B–32B) with high fidelity; it even exposed a shared fictional persona ('Dr. Elena Rodriguez') inadvertently baked into synthetic fine-tuning data.

reddit · r/MachineLearning · /u/CebulkaZapiekana · Jul 3, 19:01

**Background**: Contrastive decoding is a technique that contrasts probabilities from two models to guide generation. Logits are the raw output scores of a language model before softmax. Model diffing refers to methods that compare a base and fine-tuned model to understand changes. Prior work like Activation Difference Lens used internal activations, but CDD operates directly on logits, making it simpler and less invasive.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2210.15097">[2210.15097] Contrastive Decoding: Open-ended Text Generation as Optimization</a></li>
<li><a href="https://en.wikipedia.org/wiki/Logit">Logit - Wikipedia</a></li>
<li><a href="https://transformer-circuits.pub/2024/model-diffing/index.html">Stage-Wise Model Diffing</a></li>

</ul>
</details>

**Tags**: `#contrastive decoding`, `#model inversion`, `#data privacy`, `#logit analysis`, `#fine-tuning`

---

<a id="item-2"></a>
## [YouTube Prompt Injection Vulnerability Leaks Private Video Titles](https://javoriuski.com/post/youtube) ⭐️ 8.0/10

A vulnerability in YouTube Studio's AI comment suggestion feature allows attackers to use prompt injection to extract private video titles when a creator interacts with a malicious comment. This vulnerability highlights the risks of deploying large language model features without robust safeguards on major platforms, potentially exposing sensitive creator data through social engineering. The attack chain requires a creator to click a suggested AI reply prompt in YouTube Studio's comment tab, triggering the injection; the AI-generated response may then inadvertently reveal private video titles, despite being clearly labeled as AI-written.

hackernews · javxfps · Jul 4, 16:45 · [Discussion](https://news.ycombinator.com/item?id=48786781)

**Background**: Prompt injection is a security exploit where specially crafted inputs cause language models to deviate from their intended behavior. Indirect prompt injection leverages untrusted content, like user comments, to insert adversarial instructions. YouTube's AI reply feature uses such a model to generate suggestions, and if a comment contains injection payloads, the AI may be tricked into outputting private metadata.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Prompt_injection">Prompt injection</a></li>
<li><a href="https://www.ibm.com/think/topics/prompt-injection">What Is a Prompt Injection Attack? | IBM</a></li>

</ul>
</details>

**Discussion**: Comments range from a former Google engineer explaining the nuance that the bug may have been classified as low‑priority due to required human interaction, to others arguing it merges prompt injection with social engineering and is alarming that YouTube does not treat it as a security issue. Overall, the discussion underscores the complexity of setting boundaries for what constitutes a vulnerability in AI‑integrated features.

**Tags**: `#security`, `#prompt-injection`, `#youtube`, `#vulnerability`, `#ai-safety`

---

<a id="item-3"></a>
## [Potential Session/Cache Leakage Reported Across LLM APIs, Likely Hallucination](https://github.com/anthropics/claude-code/issues/74066) ⭐️ 8.0/10

Users across multiple LLM providers (Claude, GPT, Gemini) have reported receiving responses that appear to originate from other users' sessions, such as unrelated Minecraft references. The issue surfaced on GitHub and Hacker News, with the Claude Code team stating it is likely hallucination but investigating. If confirmed as a genuine infrastructure bug, cross-session response leakage could expose sensitive user data, posing a serious security threat. Even if the reports stem from hallucination, the incident highlights the need for robust safeguards to maintain user trust in AI services. One commenter noted a past postmortem where an API gateway mishandled HTTP 100 status codes, causing response swapping. High context lengths (e.g., over 800K tokens) may increase the likelihood of hallucination. No private data leaks have been confirmed.

hackernews · chatmasta · Jul 4, 14:03 · [Discussion](https://news.ycombinator.com/item?id=48785485)

**Background**: LLM hallucinations are responses that contain false or fabricated information, often sounding plausible. In shared LLM serving infrastructure, mechanisms like KV-cache can introduce cache collision risks, theoretically causing cross-tenant data leakage. The community debates whether these incidents are hallucination or genuine infrastructure bugs.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/LLM_hallucination">LLM hallucination</a></li>
<li><a href="https://tianpan.co/blog/2026-04-10-cross-tenant-data-leakage-llm-infrastructure">Cross-Tenant Data Leakage in Shared LLM Infrastructure : The...</a></li>

</ul>
</details>

**Discussion**: Discussion is divided: many commenters suspect hallucination, especially given high-context usage and system prompts. However, one user recounted a confirmed infrastructure bug causing response swaps. Others reported similar experiences with Gemini, noting no private data leaks. The Claude Code team is investigating, and the community remains cautious.

**Tags**: `#LLMs`, `#security`, `#API`, `#hallucination`, `#infrastructure`

---

<a id="item-4"></a>
## [JWST's 'Little Red Dots' May Be Black Hole Stars, Sparking Debate](https://www.quantamagazine.org/astrophysicists-puzzle-over-webbs-new-universe-20260702/) ⭐️ 8.0/10

Astrophysicists are debating the nature of JWST's recently discovered 'little red dot' objects, which may be black holes shrouded in thick gas or entirely new phenomena such as black hole stars. If confirmed as black hole stars, these objects would represent an entirely new class of celestial body, potentially explaining how supermassive black holes formed in the early universe and revising models of cosmic evolution. The black hole star hypothesis refers to quasi-stars, hypothetical early-universe objects with a central black hole powering a stellar atmosphere; recent observations show that 80% of the brightest little red dots have blue companions, and radio emissions might distinguish between starburst galaxies and accreting black holes.

hackernews · jnord · Jul 4, 09:08 · [Discussion](https://news.ycombinator.com/item?id=48783948)

**Background**: The James Webb Space Telescope (JWST) is an infrared telescope that can observe the early universe. It discovered compact, reddish objects at high redshift, called 'little red dots.' The term 'black hole star' or quasi-star describes a theoretical early-universe object: a massive star hundreds of times the Sun's mass, with a black hole at its core instead of nuclear fusion, glowing from the energy of accreting matter.

<details><summary>References</summary>
<ul>
<li><a href="https://aasnova.org/2026/06/30/two-more-thoughts-on-little-red-dots/">Two More Thoughts on Little Red Dots - AAS Nova</a></li>
<li><a href="https://science.aws.science.psu.edu/news/mysterious-red-dots-in-early-universe-may-be-black-hole-star-atmospheres">Mysterious ‘ red dots ’ in early universe may be ‘black hole star...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Quasi-star">Quasi-star - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters are fascinated by the 'black hole star' concept, with one noting that a recent paper has corrected for potential contamination from brown dwarfs. Some suggest introductory cosmology books, and others add playful remarks about the implications.

**Tags**: `#astrophysics`, `#JWST`, `#black-holes`, `#cosmology`, `#little-red-dots`

---

<a id="item-5"></a>
## [Current AI Launches Open Source AI Gap Map with 421 Products](https://simonwillison.net/2026/Jul/3/open-source-ai-gap-map/#atom-everything) ⭐️ 8.0/10

Current AI, a well-funded non-profit, launched the Open Source AI Gap Map v0.1, which catalogues 421 open source AI products—software tools, models, datasets, and hardware—organized into 14 categories. The underlying data is released under an MIT license on GitHub. This comprehensive index helps track the rapidly evolving open source AI ecosystem, making it easier for developers, researchers, and policymakers to identify gaps and opportunities. With $400M backing, Current AI aims to strengthen the public AI infrastructure. The map covers 266 software tools, 85 models, 50 datasets, and 20 hardware projects from 228 organizations, with an additional 24,400 uncategorized artifacts. The data includes 1,184 YAML files and 16,185 tracked GitHub repositories.

rss · Simon Willison · Jul 3, 22:04

**Background**: Current AI is a global non-profit partnership launched at the AI Action Summit in Paris in February 2025, with a mission to build a 'public option for AI'. It has already secured $400 million in funding. The AI Action Summit was an international event focused on AI governance and development.

<details><summary>References</summary>
<ul>
<li><a href="https://www.currentai.org/blogs/introducing-the-gap-map-v0-1">Introducing the Gap Map v0.1</a></li>
<li><a href="https://simonwillison.net/2026/jul/3/open-source-ai-gap-map/">Open Source AI Gap Map | Simon Willison’s Weblog</a></li>

</ul>
</details>

**Tags**: `#open-source`, `#AI`, `#index`, `#non-profit`, `#ecosystem`

---

<a id="item-6"></a>
## [HAT-4D: 4D Interactive Scene Generation from Monocular Video](https://mp.weixin.qq.com/s?__biz=MzIzNjc1NzUzMw==&mid=2247901356&idx=3&sn=54ee94026f76691a380cd3ea214e0def) ⭐️ 8.0/10

Shanghai Jiao Tong University researchers have introduced HAT-4D, the first agentic framework capable of reconstructing 3D geometry, temporal dynamics, and physical interactions of multiple objects from a single monocular video, eliminating the need for costly motion capture systems. This breakthrough drastically lowers the barrier for acquiring 4D interaction data, enabling scalable training for embodied AI and robotics from everyday videos. It specifically tackles multi-object occlusions and complex dynamics, which are critical for real-world applications. HAT-4D employs an agentic pipeline to handle severe occlusions and interactions, producing 4D scenes directly without per-video optimization or separate camera estimation. The method builds on advances in 3D Gaussian Splatting and motion perception.

rss · 量子位 · Jul 3, 03:43

**Background**: 4D reconstruction extends 3D modeling by adding the temporal dimension, capturing movement and change over time. Traditional methods rely on multi-camera setups or depth sensors, which are expensive and controlled. Monocular video reconstruction is notoriously difficult due to depth ambiguity and lack of viewpoint diversity. HAT-4D addresses these challenges by leveraging an agentic framework that jointly reasons about geometry, motion, and physical interactions.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2606.28215">[2606.28215] HAT-4D: Lifting Monocular Video for 4D Multi ...</a></li>
<li><a href="https://arxiv.org/html/2606.28215v1">HAT-4D: Lifting Monocular Video for 4D Multi-Object ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/4D_reconstruction">4D reconstruction</a></li>

</ul>
</details>

**Tags**: `#4D reconstruction`, `#monocular video`, `#motion capture`, `#computer vision`, `#HAT-4D`

---

<a id="item-7"></a>
## [Tencent's Atuin AI Outperforms Claude Mythos on CyberGym at Fraction of Cost](https://mp.weixin.qq.com/s/BzU7g-2iG7d6h4ViwMhxyg) ⭐️ 8.0/10

Tencent Xuanwu Lab's Atuin AI achieved 84.0% on the CyberGym cybersecurity benchmark, surpassing Anthropic's Claude Mythos Preview (83.1%), while costing less than 0.1% of Mythos's compute budget. It also discovered critical logic vulnerabilities in major open-source projects like curl, gnark, and OpenSSL that Mythos missed. This breakthrough demonstrates that open-source, cost-efficient AI models can outperform pricey closed-source systems in real-world cybersecurity tasks, potentially democratizing advanced vulnerability detection and making critical software safer. Atuin AI runs on the locally deployable open-source GLM-5.1 model and scored 84.0% on CyberGym, an end-to-end benchmark covering vulnerability detection, exploit generation, and patching. The found bugs reached severity scores up to 9.3, and Atuin ranked 1st in severity and 5th in total findings on the Berkeley BVI real-world vulnerability list.

telegram · zaihuapd · Jul 3, 16:12

**Background**: CyberGym is a UC Berkeley benchmark that evaluates AI agents on end-to-end cybersecurity tasks beyond simple detection. GLM-5.1 is a recent large language model from Z.AI designed for agentic coding and long-horizon autonomous work (up to 8 hours). The "Glass Wing Plan" refers to the high-cost compute budget used to run Claude Mythos.

<details><summary>References</summary>
<ul>
<li><a href="https://llm-stats.com/benchmarks/cybergym">CyberGym Benchmark Leaderboard | LLM Stats</a></li>
<li><a href="https://huggingface.co/zai-org/GLM-5.1">zai-org/GLM-5.1 · Hugging Face</a></li>
<li><a href="https://www.cybergym.io/cybergym-e2e/">CyberGym -E2E: Scalable Real-World Benchmark for AI Agents...</a></li>

</ul>
</details>

**Tags**: `#cybersecurity`, `#AI`, `#vulnerability detection`, `#benchmark`, `#Tencent`

---

<a id="item-8"></a>
## [South Korea Plans 800 Trillion Won Semiconductor Cluster to Double DRAM Output](https://t.me/zaihuapd/42357) ⭐️ 8.0/10

South Korea's Minister of Trade, Industry and Energy announced a plan to build a second semiconductor production base in the southwest region, attracting 800 trillion won (approximately 3.52 trillion RMB) in private investment for four memory fabs, with the goal of doubling DRAM production within five years. This massive investment underscores South Korea's strategic commitment to maintaining its dominance in the memory chip industry amid intensifying global competition, and could significantly impact global DRAM supply chains and market dynamics. The plan includes building four memory fabs in the southwestern region, with the government also committing 30 trillion won over 15 years for infrastructure, though the 800 trillion won is largely expected from private sector investments.

telegram · zaihuapd · Jul 4, 15:15

**Background**: South Korea is a global leader in memory semiconductors, with Samsung and SK Hynix dominating the DRAM and NAND flash markets. Semiconductor clusters are geographic concentrations of chip design, manufacturing, and related services aimed at achieving synergies and reducing costs. The DRAM market is cyclical, driven by demand from servers, mobile devices, and emerging technologies like AI.

**Tags**: `#semiconductors`, `#investment`, `#memory`, `#manufacturing`, `#SouthKorea`

---

<a id="item-9"></a>
## [Anna's Archive Offers $200K Bounty for Scanning All Google Books](https://software.annas-archive.gl/AnnaArchivist/annas-archive/-/work_items/234) ⭐️ 7.0/10

Anna's Archive has announced a $200,000 bounty for individuals or teams to scan and digitize the complete collection of books available on Google Books. This initiative could democratize access to millions of books, fueling AI research and education globally, while highlighting tensions between copyright and digital preservation. The bounty targets the full Google Books corpus, which includes millions of titles; however, the technical and legal feasibility remains uncertain given Google's access restrictions and copyright issues.

hackernews · Cider9986 · Jul 4, 16:51 · [Discussion](https://news.ycombinator.com/item?id=48786838)

**Background**: Anna's Archive is a non-profit, open-source search engine for shadow libraries like Library Genesis and Sci-Hub, aiming to catalog and provide access to all books. Google Books is a massive project that has scanned millions of books from libraries worldwide, but full-text access is often restricted due to copyright. Anna's Archive has previously offered bounties for other book collections to expand its digital library.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Anna's_Archive">Anna's Archive</a></li>
<li><a href="https://grokipedia.com/page/Anna's_Archive">Anna's Archive</a></li>

</ul>
</details>

**Discussion**: Commenters express gratitude for Anna's Archive's role in providing book access in underserved regions. Some note the potential value for AI training data, while others question the legal implications and the ethics of digital archiving without compensating authors. The discussion is generally supportive of the bounty's goal of open knowledge.

**Tags**: `#digital-archiving`, `#open-access`, `#google-books`, `#bounty`, `#data-preservation`

---

<a id="item-10"></a>
## [Comprehensive Guide to Understanding htop/top Metrics on Linux](https://peteris.rocks/blog/htop/) ⭐️ 7.0/10

A 2019 article provides a thorough explanation of every metric in htop and top, with community comments adding practical tips like disabling user threads and using process tree view. Understanding these monitoring tools aids in performance troubleshooting and resource management, while the discussion introduces modern alternatives like btop. The article contrasts virtual memory with resident memory, explains sorting by memory usage, and highlights the importance of the process tree view; community members note that virtual memory can be misleading.

hackernews · theanonymousone · Jul 4, 12:00 · [Discussion](https://news.ycombinator.com/item?id=48784777)

**Background**: htop and top are classic command-line tools for monitoring Linux processes, showing CPU, memory, and other resource usage in real time, and are essential for system administration and debugging.

**Discussion**: Users shared practical tips such as changing default settings (disabling user threads, enabling tree view), discussed memory metric reliability, and recommended modern tools like btop. The overall sentiment was positive and informative.

**Tags**: `#linux`, `#monitoring`, `#htop`, `#system-administration`, `#tutorial`

---

<a id="item-11"></a>
## [Maybe You Should Learn Something](https://www.marginalia.nu/log/a_135_learn/) ⭐️ 7.0/10

A blog post on Marginalia titled 'Maybe you should learn something' argued for the intrinsic value of learning, which resonated widely on HackerNews, garnering 367 points and 170 comments. The discussion highlights that learning is seen by many in the tech community as essential for personal fulfillment and mental resilience, reflecting a broader cultural shift towards lifelong learning. Commenters noted that barriers to learning are often energy and mindset rather than time, and that active practice with mistakes is crucial—'if I'm not producing errors, I'm probably not practicing'.

hackernews · tylerdane · Jul 4, 03:36 · [Discussion](https://news.ycombinator.com/item?id=48782435)

**Discussion**: Overall sentiment was reflective and supportive. Community members shared personal stories: learning a language in their 40s provided a powerful brain workout; one quoted Merlin saying learning is the only cure for sadness; others emphasized that real learning involves errors and social accountability helps consistency.

**Tags**: `#learning`, `#motivation`, `#personal development`, `#hackernews discussion`, `#lifelong learning`

---

<a id="item-12"></a>
## [Josh W. Comeau Reports AI-Driven 50% Drop in Course Sales](https://simonwillison.net/2026/Jul/3/josh-w-comeau/#atom-everything) ⭐️ 7.0/10

Josh W. Comeau, a prominent developer course creator, launched 'Whimsical Animations' but it is selling only one-third of typical copies, and his overall course revenue is down over 50% from last year. He attributes this to AI, as potential buyers question job prospects and turn to LLMs for free tutoring. This is a concrete, real-world indicator of how AI is disrupting the developer education market. It reflects widespread concerns about AI's impact on developer jobs and the shift towards free, AI-powered learning alternatives, threatening the livelihoods of independent educators. Comeau identifies a 'double whammy': developers are uncertain about future job availability, and LLMs can provide personalized tutoring without payment. He notes that multiple course creators are seeing the same trend, with revenue drops of 50% or more, and that LLMs are 'slurping up' their work without consent.

rss · Simon Willison · Jul 3, 21:25

**Background**: Josh W. Comeau is a well-known educator offering premium front-end development courses, particularly in CSS and React. In recent years, generative AI tools like ChatGPT and GitHub Copilot have rapidly advanced, offering instant coding help and raising fears about automation replacing programming jobs. This has led to a decline in demand for traditional paid educational resources.

**Tags**: `#developer education`, `#AI impact`, `#course sales`, `#LLMs`, `#career uncertainty`

---

<a id="item-13"></a>
## [BaryGraph: Knowledge Graph with Relationships Embedded as First-Class Documents](https://www.reddit.com/r/MachineLearning/comments/1un3lsf/barygraph_knowledge_graph_where_every/) ⭐️ 7.0/10

BaryGraph introduces a novel knowledge graph architecture where each relationship is embedded as its own document (BaryEdge), and recursive stacking of these edges forms MetaBary triads that can surface structural bridges between distant concepts. The system is implemented locally using MongoDB Community with vector search and nomic-embed-text on the full English Wiktionary, and the code is open-source. This approach addresses a key limitation in standard RAG and vector search, where relationships are merely byproducts of point proximity, by making relationships first-class retrievable entities. It enables cross-domain knowledge discovery that traditional embedding-based retrieval misses, potentially impacting interdisciplinary research and AI systems that need to connect disparate fields. BaryEdge vectors are computed as a weighted combination of concept vectors and a type embedding, and no additional embedding calls are needed for higher-level MetaBary triads. Structural metrics from the graph (shared edges, neighborhood overlap) correlate with human similarity judgments on SimLex-999 and WordSim-353 (ρ ≈ 0.32–0.53), while raw cosine similarity does not (ρ ≈ −0.04). The preprint is not yet peer-reviewed and includes benchmarks on Wiktionary data.

reddit · r/MachineLearning · /u/adseipsum · Jul 4, 08:24

**Background**: Knowledge graphs represent information as nodes (entities) and edges (relationships), but edges are typically just links. Embedding models like nomic-embed-text convert text into dense vectors, enabling similarity search. Retrieval-augmented generation (RAG) often uses vector search to find relevant information, but it cannot capture indirect relationships. MongoDB's mongot component provides vector search capabilities, and the Model Context Protocol (MCP) allows AI models to interact with external tools.

<details><summary>References</summary>
<ul>
<li><a href="https://www.sourcetrail.com/software/mongodb-mongot-source-code-and-the-future-of-search-and-rag/">MongoDB mongot source code: search and vector explained</a></li>
<li><a href="https://ollama.com/library/nomic-embed-text">nomic-embed-text</a></li>
<li><a href="https://en.wikipedia.org/wiki/Model_Context_Protocol">Model Context Protocol - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#knowledge-graph`, `#embeddings`, `#vector-search`, `#RAG`, `#novel-architecture`

---

<a id="item-14"></a>
## [NASA Launches LINK Satellite to Boost Swift Telescope's Orbit](https://apnews.com/article/swift-nasa-satellite-rescue-katalyst-a7ddd740ca099587c58865f583c7245a) ⭐️ 7.0/10

On July 3, NASA launched the LINK spacecraft, developed by Katalyst Space Technologies, to rendezvous with the aging Swift space telescope and raise its orbit, marking the first private attempt to service a U.S. government satellite. This mission demonstrates private capability for in-orbit satellite servicing, potentially extending the life of valuable scientific assets like Swift, which has made groundbreaking discoveries in gamma-ray astronomy. It also opens the door for future commercial rescue and refueling missions. LINK will use a robotic arm to grab Swift and then fire its thrusters to lift the orbit by approximately 240 kilometers. The $30 million mission is expected to allow Swift to resume observations by September if successful.

telegram · zaihuapd · Jul 3, 15:43

**Background**: The Neil Gehrels Swift Observatory, launched in 2004, is a multi-wavelength space telescope specializing in gamma-ray bursts. Its low Earth orbit has been gradually decaying due to atmospheric drag, which is exacerbated by increased solar activity. Without intervention, the telescope would have burned up in the atmosphere as early as October 2026, ending its two decades of scientific contributions.

<details><summary>References</summary>
<ul>
<li><a href="https://baike.baidu.com/item/Link/67531114">Link（美国航天器）_百度百科</a></li>
<li><a href="https://www.cislunarspace.cn/space-news/2026/05/2026-05-28-nasa-swift-link-boost-mission/">NASA与Katalyst合作：私人航天器Link将为2004年发射的Swift望远镜实施...</a></li>
<li><a href="https://www.wenweipo.com/a/202607/04/AP6a48722ce4b0b49ad1c1ec91.html">美發射商業航天器抬升天文衛星軌道 延長工作壽命 - 香港文匯網</a></li>

</ul>
</details>

**Tags**: `#space`, `#NASA`, `#satellite servicing`, `#Swift telescope`, `#private space`

---

<a id="item-15"></a>
## [Huawei Proposes 'Tao's Law' for Semiconductor Scaling via Time Reduction](https://t.me/zaihuapd/42346) ⭐️ 7.0/10

At ISCAS 2026 in Shanghai, Huawei unveiled 'Tao's Law' (Tau Scaling Law), shifting semiconductor design from geometric transistor shrinking to reducing time constant τ. The company claims to have already designed 381 chips using this principle and will release a Kirin smartphone chip with 'logic folding' this fall. By focusing on time-based optimization, the approach could overcome Moore's Law limitations without requiring advanced EUV lithography, potentially reshaping the semiconductor industry and giving China a new path to high-performance chip design. The upcoming Kirin 2026 chip uses dual-layer logic folding to improve transistor density by 53.5% and energy efficiency by 41%. Huawei targets equivalent 1.4nm node density by 2031 through multi-level τ reduction.

telegram · zaihuapd · Jul 4, 04:56

**Background**: Moore's Law has driven semiconductor progress by periodically shrinking transistor sizes, but it is approaching physical and economic limits. Advanced chips rely on EUV lithography, which Huawei cannot easily access due to trade restrictions. Time constant τ represents the switching delay in circuits; reducing it speeds up operations. Logic folding is a 3D-like layout technique that compresses signal paths within a single chip.

<details><summary>References</summary>
<ul>
<li><a href="https://www.ithome.com/0/972/524.htm">华为何庭波发布 V2 版“韬定律”论文，补充工程细节和实测数据华为何庭...</a></li>
<li><a href="https://baike.baidu.com/item/韬定律/67839953">韬定律_百度百科</a></li>
<li><a href="https://www.cnblogs.com/qiniushanghai/p/20166392">华为韬（τ）定律：用"时间缩微"重写半导体演进规则（2026） - 七牛云行业应用 - 博客园</a></li>

</ul>
</details>

**Tags**: `#semiconductors`, `#chip design`, `#Moore's Law`, `#time scaling`, `#Huawei`

---

<a id="item-16"></a>
## [iOS 27 to Introduce Trust Insights for On-Device Scam Detection](https://www.cultofmac.com/news/ios-27-trust-insights-feature) ⭐️ 7.0/10

Apple's iOS 27 will include Trust Insights, a new on-device behavioral analysis feature that detects when users are being coached into financial scams during phone calls by analyzing usage patterns and sensor data. This addresses the growing threat of phone-guided financial scams with a privacy-first approach, potentially setting a new standard for mobile security and influencing other platforms. The system evaluates operation patterns, timing, context, and sensor data locally, sending only a single anonymized output to developers. It includes a cooldown period for disabling to prevent scammers from coercing an immediate shutdown.

telegram · zaihuapd · Jul 4, 14:30

**Background**: Phone-guided scams, or 'vishing', involve criminals calling victims to trick them into transferring money or altering account details. Traditional anti-fraud tools often rely on server-side flags, but Trust Insights runs real-time analysis locally on the iPhone, preserving privacy while detecting coercive behavior patterns.

<details><summary>References</summary>
<ul>
<li><a href="https://developer.apple.com/documentation/TrustInsights">Trust Insights | Apple Developer Documentation</a></li>
<li><a href="https://applemagazine.com/ios-27-trust-insights/">iOS 27 Trust Insights Helps Apps Detect Scam Coaching</a></li>

</ul>
</details>

**Tags**: `#iOS`, `#security`, `#privacy`, `#fraud detection`, `#anti-scam`

---

<a id="item-17"></a>
## [Fable's Judgment for Testing and Model Delegation Saves Tokens](https://simonwillison.net/2026/Jul/3/judgement/#atom-everything) ⭐️ 6.0/10

Simon Willison was advised by the Claude Code team to let Fable use its own judgment for tasks like testing, and from Jesse Vincent to delegate smaller coding tasks to cheaper models to save tokens before a price increase. He implemented a prompt to delegate coding tasks to subagents running lower-power models based on Fable's discretion. This approach optimizes cost and efficiency when using expensive top-tier models like Fable, allowing developers to retain high-level judgment while offloading simpler work to cheaper models. It is particularly relevant with an imminent Fable price increase. The prompt "For all coding tasks use your judgement to decide an appropriate lower power model and run that in a subagent" caused Claude Code to save a memory file with instructions to spawn agents with model overrides (Sonnet for substantial edits, Haiku for trivial ones) and review in the main loop. It reduced token consumption significantly in practice.

rss · Simon Willison · Jul 3, 18:51

**Background**: Claude Fable 5 is Anthropic's most capable coding model, designed for complex projects but expensive. Claude Code is an agentic terminal-based coding assistant. This article shares a prompt engineering technique to delegate tasks to cheaper models like Sonnet and Haiku within Claude Code, helping manage costs especially before a reported Fable price hike.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/claude/fable">Claude Fable \ Anthropic</a></li>
<li><a href="https://github.com/anthropics/claude-code">GitHub - anthropics/claude-code: Claude Code is an agentic coding tool that lives in your terminal, understands your codebase, and helps you code faster by executing routine tasks, explaining complex code, and handling git workflows - all through natural language commands. · GitHub</a></li>
<li><a href="https://www.anthropic.com/news/claude-fable-5-mythos-5">Claude Fable 5 and Claude Mythos 5 \ Anthropic</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Claude`, `#prompt engineering`, `#cost optimization`, `#LLM usage`

---

<a id="item-18"></a>
## [HexGrid Cloud Invites Community to Choose LLMs and GPUs for Benchmarking](https://www.reddit.com/r/MachineLearning/comments/1ungvxu/well_benchmark_an_open_weights_llm_on_any_gpu_you/) ⭐️ 6.0/10

HexGrid Cloud, a cloud platform for deploying open-source models, posted on Reddit asking the machine learning community to suggest specific open-weight LLMs and GPU hardware configurations for real-world benchmarking; they will run the tests and publicly share detailed performance metrics. This initiative bridges the gap between synthetic benchmarks and real deployment scenarios, giving developers practical data to choose optimal model-GPU combinations and helping cloud providers optimize serving infrastructure. Supported models include Nemotron-3 (120B-A12B, 30B-A3B), Qwen 3.6 27B, Llama 3.3 70B, Gemma 4 31B, Devstral-Small-2 24B, and user-suggested options; tested on GPUs from RTX PRO 6000 to H200, with quantizations like FP8, AWQ, BF16, and NVFP4 (Blackwell-only); metrics will cover tokens/sec, TTFT, TPOT, throughput under concurrency, and cost-per-million-tokens with reproducible configurations.

reddit · r/MachineLearning · /u/Temporary-Owl1725 · Jul 4, 18:51

**Background**: Open-weight LLMs are language models with publicly available weights, enabling community benchmarking. Quantization techniques like FP8 (8-bit floating point) and NVFP4 (4-bit floating point for Blackwell GPUs) reduce memory usage and speed up inference. AWQ is an activation-aware weight quantization method that minimizes accuracy loss. Key inference metrics include TTFT (time to first token) and TPOT (time per output token). The prefill phase processes the entire prompt to generate the first token, while the decode phase generates subsequent tokens auto-regressively.

<details><summary>References</summary>
<ul>
<li><a href="https://build.nvidia.com/spark/nvfp4-quantization">NVFP4 Quantization | DGX Spark</a></li>
<li><a href="https://arxiv.org/abs/2306.00978">[2306.00978] AWQ : Activation-aware Weight Quantization for LLM...</a></li>
<li><a href="https://learncodecamp.net/llm-inference-basics-prefill-decode-ttft-itl/">Understanding LLM Inference Basics: Prefill and Decode, TTFT ...</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#benchmarking`, `#GPU`, `#open-source`, `#cloud computing`

---

<a id="item-19"></a>
## [Is Safety Training Worth It If Fine-Tuning Breaks It Quickly?](https://www.reddit.com/r/MachineLearning/comments/1um9bs7/what_does_safe_ai_look_like_d/) ⭐️ 6.0/10

A Reddit discussion questions whether safety training for open-weight large language models (LLMs) is worthwhile, given that post-release fine-tuning can easily bypass refusal mechanisms, often within 30 minutes and using automated scripts. It explores whether increasing the attacker's cost or making safety removal less reliable could be considered practical wins, even if perfect prevention is impossible. This discussion highlights a critical tension in AI safety: the ease of fine-tuning away safeguards in open-weight models raises questions about the real-world impact and cost-effectiveness of current safety measures, with direct implications for model release policies and governance. The original post notes that current safety training can be subverted in under 30 minutes with automated scripts, and asks whether practical defenses like raising the attacker's cost or making safety removal unreliable are worth pursuing, even if complete prevention is impossible.

reddit · r/MachineLearning · /u/Aaron_Rock · Jul 3, 09:07

**Background**: Open-weight models are AI models whose trained parameters are publicly released, allowing anyone to run and modify them. Safety training, often done via reinforcement learning from human feedback (RLHF), aligns models to refuse harmful requests. However, fine-tuning—a process of further training on a small dataset—can override these safeguards, leading to 'uncensored' variants. Threat modeling is a systematic approach to identify and prioritize defenses against such attacks.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Threat_modeling">Threat modeling</a></li>
<li><a href="https://opensource.org/ai/open-weights">Open Weights: not quite what you’ve been told</a></li>

</ul>
</details>

**Tags**: `#AI safety`, `#fine-tuning`, `#open-weight models`, `#threat modeling`, `#LLM`

---

<a id="item-20"></a>
## [Huawei Mate 80 Pro Gaming Efficiency Surpasses Snapdragon 8 Gen3 via HarmonyOS](https://www.bilibili.com/video/BV1F7T46wEyT) ⭐️ 6.0/10

Geekwan's review of the Huawei Mate 80 Pro series reveals that native HarmonyOS optimization enables the phone to achieve better gaming power efficiency than Snapdragon 8 Gen3, with Genshin Impact running at 60fps consuming only 4.9W. This demonstrates that Huawei's software-hardware co-optimization can significantly narrow the performance gap with leading chips, showcasing the maturity of the HarmonyOS ecosystem and its potential to compete without cutting-edge silicon. The Kirin 9030 Pro chip features a 9-core 14-thread CPU, 6-core Maleoon 935 GPU, and approximately 15 billion transistors; its CPU multi-core efficiency lies between Snapdragon 8 Gen2 and Gen3, yet real-world gaming tests show superior sustained efficiency.

telegram · zaihuapd · Jul 3, 13:27

**Background**: Huawei's Kirin chips and HarmonyOS were developed in response to U.S. sanctions that restricted access to advanced chips and Google services. The Maleoon GPU is a custom design, and native HarmonyOS apps are built specifically for the OS, enabling deeper integration and optimization. The Mate 80 Pro is the latest flagship aiming to showcase this ecosystem's capabilities.

<details><summary>References</summary>
<ul>
<li><a href="https://m.ithome.com/html/972456.htm">华为 Mate 80 Pro 性能解禁：麒麟 9030 Pro GPU 相比 9020 提升 76%，《原神》能效表现优于高通骁龙 8 Gen3 - IT之家</a></li>
<li><a href="https://zhuanlan.zhihu.com/p/1984694464581747822">麒麟9030系列发布后的华为处理器性能排行（鸿蒙6版本） - 知乎</a></li>

</ul>
</details>

**Tags**: `#Huawei`, `#HarmonyOS`, `#Kirin`, `#gaming`, `#performance`

---

<a id="item-21"></a>
## [Linux Tops 2026 CVE Charts, Kernel Maintainer Calls It a Positive Sign](https://linuxiac.com/linux-tops-2026-cve-charts/) ⭐️ 6.0/10

In the first half of 2026, Linux reported 2,308 CVEs, leading all vendors ahead of Google (1,752), Microsoft (843), and Apple (284). Kernel maintainer Greg Kroah-Hartman says this surge reflects more complete and transparent vulnerability reporting, not worse security. This reframes the CVE metric, shifting the narrative from a raw count of flaws to an indicator of disclosure maturity. It encourages other vendors to adopt more transparent practices, potentially improving the overall security ecosystem. Unlike commercial vendors that often report only high-severity flaws, Linux cannot predict deployment scenarios across billions of devices, so it reports every vulnerability. Kroah-Hartman urged others to 'step up' and report all CVEs rather than selectively.

telegram · zaihuapd · Jul 4, 16:00

**Background**: CVE (Common Vulnerabilities and Exposures) is a public database of known cybersecurity vulnerabilities, each assigned a unique identifier for tracking and discussion. Managed by MITRE, it serves as a standard reference for security professionals and researchers worldwide. CVE counts are often used to gauge software security, but they can also reflect reporting practices.

<details><summary>References</summary>
<ul>
<li><a href="https://zh.wikipedia.org/zh-hans/公共漏洞和暴露">公共漏洞和暴露 - 维基百科，自由的百科全书</a></li>
<li><a href="https://www.redhat.com/en/topics/security/what-is-cve">什么是CVE？</a></li>

</ul>
</details>

**Tags**: `#Linux`, `#Security`, `#CVE`, `#Open Source`, `#Vulnerability Reporting`

---