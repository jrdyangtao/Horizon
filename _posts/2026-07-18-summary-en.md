---
layout: default
title: "Horizon Summary: 2026-07-18 (EN)"
date: 2026-07-18
lang: en
---

> From 65 items, 25 important content pieces were selected

---

1. [LG monitors silently install software via Windows Update](#item-1) ⭐️ 9.0/10
2. [Firefox Compiled to WebAssembly Runs Inside Another Browser](#item-2) ⭐️ 9.0/10
3. [Meta in Talks to Rent $10B AI Compute to Anthropic](#item-3) ⭐️ 9.0/10
4. [Trump Weighs FINRA-Like Agency to Vet Top AI Models](#item-4) ⭐️ 9.0/10
5. [GPT-5.6 Solves 30-Year-Old Convex Optimization Problem](#item-5) ⭐️ 8.0/10
6. [StackOverflow decline debated: AI vs community policies](#item-6) ⭐️ 8.0/10
7. [Kimi K3 Breaks Records with 2.8 Trillion Parameters](#item-7) ⭐️ 8.0/10
8. [Shanghai AI Lab's Self-Harness boosts agent performance by 104% without model changes](#item-8) ⭐️ 8.0/10
9. [Did AI Slop Win a $25k DeepMind/Kaggle Grand Prize?](#item-9) ⭐️ 8.0/10
10. [Stereo2Spatial: Convert Stereo to Binaural Audio with Diffusion](#item-10) ⭐️ 8.0/10
11. [Prism Bug Leaks Unpublished Papers in Academic Publishing](#item-11) ⭐️ 8.0/10
12. [EU AI Act OpenRAG: 933 Legally Structured Chunks with BGE-M3 Embeddings](#item-12) ⭐️ 8.0/10
13. [SpaceX in Talks with Pentagon for Billion-Dollar AI Compute Deal](#item-13) ⭐️ 8.0/10
14. [OpenRouter reportedly attracts acquisition interest at >$1.3B valuation](#item-14) ⭐️ 8.0/10
15. [TSMC Announces A14 Process for 2028 Production](#item-15) ⭐️ 8.0/10
16. [San Francisco Orders Apple, Google to Remove 'Nudify' Apps](#item-16) ⭐️ 8.0/10
17. [Regressive JPEGs: Video Animation via Progressive JPEG Loading](#item-17) ⭐️ 7.0/10
18. [Claude Fable 5 Made Permanent in Subscription Plans](#item-18) ⭐️ 7.0/10
19. [DABSN: New Recurrent LM Seeks Collaborators](#item-19) ⭐️ 7.0/10
20. [Doubao Phone Drops GUI Operations, Demands MCP from Super Apps](#item-20) ⭐️ 7.0/10
21. [SK Hynix CEO Warns of Worst Memory Shortage by 2027](#item-21) ⭐️ 7.0/10
22. [Bilibili's 'Project N.E.K.O.' Open-Source AI Companion at WAIC 2026](#item-22) ⭐️ 7.0/10
23. [South Korea Official Proposes AI Dividend from Chip Profits](#item-23) ⭐️ 7.0/10
24. [Fable 5 vs GPT-5.6 Sol: Does /goal Help on NP-Hard Tasks?](#item-24) ⭐️ 6.0/10
25. [TabFM Studio: No-Code Spreadsheet Predictions with Tabular Foundation Models](#item-25) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [LG monitors silently install software via Windows Update](https://videocardz.com/newz/lg-monitors-silently-install-software-through-windows-update-without-user-consent) ⭐️ 9.0/10

LG monitors are using Windows Update to automatically install companion software without user consent when the monitor is plugged in via HDMI or DisplayPort. This poses significant security and privacy risks because the software runs at system boot, has internet access, and is installed from a third-party vendor without user interaction. The software is delivered as a WHQL-signed driver package and starts with every system boot, affecting both new and existing LG monitor owners.

hackernews · baranul · Jul 18, 10:21 · [Discussion](https://news.ycombinator.com/item?id=48956688)

**Background**: Windows Update is designed to deliver driver and firmware updates automatically to ensure hardware compatibility. Hardware vendors can submit WHQL-signed packages that Windows trusts, which can include non-driver software. This mechanism can be abused to install unwanted applications without user consent.

<details><summary>References</summary>
<ul>
<li><a href="https://asibiont.com/en/blog/monitory-lg-tayno-ustanavlivayut-po-cherez-windows-update-bez-vashego-soglasiya-chto-proiskhodit-i-kak-zashchititsya">LG Monitors Silently Install Software Through Windows Update ...</a></li>
<li><a href="https://blog.zealtyro.com/lg-monitors-silently-installing-windows-software/">LG Monitors Silently Installing Software via Windows Update : What...</a></li>
<li><a href="https://commutevolt.com/maintenance-repairs/lg-monitors-silently-install-software-through-windows-update-without-consent/">LG Monitors Silently Install Software Through Windows Update ...</a></li>

</ul>
</details>

**Discussion**: Community comments express strong disapproval, with some providing workarounds such as disabling automatic driver downloads via Group Policy or Device Installation Settings. There is also debate over whether Microsoft or LG is primarily responsible, with many users criticizing Windows for allowing the automatic installation of third-party software.

**Tags**: `#security`, `#privacy`, `#Windows`, `#hardware`, `#software distribution`

---

<a id="item-2"></a>
## [Firefox Compiled to WebAssembly Runs Inside Another Browser](https://simonwillison.net/2026/Jul/16/firefox-in-webassembly/#atom-everything) ⭐️ 9.0/10

Puter has compiled the full Firefox browser to WebAssembly, enabling it to run inside another browser like Chrome via a 233MB WebAssembly binary and an 18MB assets file. The project used AI-assisted development with an estimated $25,000 worth of Claude Opus and Fable compute tokens. This demonstrates a groundbreaking technical achievement: running a full browser inside another browser, pushing the boundaries of what WebAssembly can do. It could enable new types of web applications, such as secure sandboxed browsing or legacy browser emulation, and showcases the potential of AI-assisted programming for complex porting projects. Firefox's Gecko engine was chosen because of its strong single-process support, which simplifies WebAssembly compilation. Network traffic is proxied through Puter's server using the Wisp WebSocket protocol, with end-to-end encryption verified for HTTPS traffic; the team had to scale servers to handle Hacker News traffic.

rss · Simon Willison · Jul 16, 23:34

**Background**: WebAssembly (Wasm) is a low-level binary instruction format that runs in modern web browsers at near-native speed, allowing code written in languages like C++ to be executed in a browser. Compiling a full browser like Firefox to Wasm is extremely challenging due to its size and complexity; the project leveraged AI tools (Claude Opus and Fable) to assist with the massive refactoring effort, spending an estimated $25,000 in compute tokens. The Wisp protocol is a lightweight protocol for multiplexing multiple TCP/UDP sockets over a single WebSocket connection, enabling networking for Wasm modules that cannot open raw sockets.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/MercuryWorkshop/wisp-protocol">GitHub - MercuryWorkshop/ wisp - protocol : Wisp is a low-overhead...</a></li>

</ul>
</details>

**Tags**: `#WebAssembly`, `#Firefox`, `#browser-in-browser`, `#AI-assisted development`, `#Wisp protocol`

---

<a id="item-3"></a>
## [Meta in Talks to Rent $10B AI Compute to Anthropic](https://www.nytimes.com/2026/07/17/technology/meta-anthropic-ai-computing-power.html) ⭐️ 9.0/10

Meta is negotiating a deal to rent AI computing power to Anthropic, potentially worth $10 billion over two years. The proposal was made by Anthropic in June and Meta is evaluating it. This deal highlights the severe scarcity of AI compute resources. It could provide Meta with a new revenue stream to justify its massive infrastructure spending, while giving Anthropic access to critical computational capacity. The deal is still in early talks and may not be finalized. Anthropic would pay monthly with both parties able to exit early. Meta plans to invest up to $145 billion this year, largely in AI and data centers.

telegram · zaihuapd · Jul 18, 01:14

**Background**: AI compute refers to the processing power required for training and running AI models, which is currently in high demand due to GPU shortages and energy constraints. Major tech companies like Meta are investing heavily in AI infrastructure, often leading to surplus capacity that can be rented out.

<details><summary>References</summary>
<ul>
<li><a href="https://www.linkedin.com/pulse/ai-compute-scarcity-2025-how-gpus-power-cooling-de-castro-júnior-ovm1c">AI compute scarcity in 2025: how GPUs, power, and cooling...</a></li>
<li><a href="https://fferoz.medium.com/the-ai-compute-crunch-is-here-why-inference-will-break-your-budget-before-2028-e63333cfaebd">AI Compute Shortage 2026–2028: Why Enterprises Face an... | Medium</a></li>
<li><a href="https://qz.com/100019/the-new-hot-commodities-market-the-cloud">The new hot commodities market: the cloud</a></li>

</ul>
</details>

**Tags**: `#AI infrastructure`, `#cloud computing`, `#Meta`, `#Anthropic`, `#compute scarcity`

---

<a id="item-4"></a>
## [Trump Weighs FINRA-Like Agency to Vet Top AI Models](https://www.bloomberg.com/news/articles/2026-07-17/us-considers-creating-finra-like-watchdog-to-vet-top-ai-models) ⭐️ 9.0/10

The Trump administration is considering creating an independent regulatory body, modeled after the Financial Industry Regulatory Authority (FINRA), to review the safety of leading artificial intelligence models. The proposal is led by Treasury Secretary Scott Bessent and is under review by White House Chief of Staff Susie Wiles. This initiative aims to address Wall Street's cybersecurity concerns and Silicon Valley's dissatisfaction with ad-hoc government restrictions, giving both industries a greater role in shaping AI safety standards. It aligns with calls from AI leaders like Google DeepMind CEO Demis Hassabis for an industry-funded independent watchdog. The proposed agency would report to the Securities and Exchange Commission (SEC) like FINRA does, but details remain fluid and President Trump has not yet reviewed the plan. Previous disputes saw Anthropic and OpenAI object to government demands to modify or delay their latest models.

telegram · zaihuapd · Jul 18, 05:45

**Background**: FINRA is an independent regulatory body overseen by the SEC that monitors securities firms to prevent fraud and protect investors. The Trump administration's proposal mirrors this model for AI, creating an industry-funded independent agency to set safety standards. This comes amid growing tensions between the government and AI companies over model releases and national security concerns.

<details><summary>References</summary>
<ul>
<li><a href="https://zh.wikipedia.org/zh-hans/美国证券法">美国证券法 - 维基百科，自由的百科全书</a></li>
<li><a href="https://www.oanda.com/bvi-ft/lab-education/invest_us_stock/finra/">FINRA是什麼？介紹其成立宗旨與功能所在 - OANDA Lab</a></li>
<li><a href="https://lazarusalliance.com/zh-CN/什么是FINRA合规性/">什么是 FINRA 合规性？ - Lazarus Alliance, Inc.</a></li>

</ul>
</details>

**Tags**: `#AI监管`, `#美国政府`, `#FINRA`, `#政策`, `#人工智能安全`

---

<a id="item-5"></a>
## [GPT-5.6 Solves 30-Year-Old Convex Optimization Problem](https://old.reddit.com/r/math/comments/1uxj3cy/after_openais_cdc_proof_announcement_gpt56_used_a/) ⭐️ 8.0/10

Researchers used a single prompt with GPT-5.6 (Sol Pro variant) to produce a proof that closes a 30-year gap in convex optimization, specifically regarding iteration complexity bounds for convex Lipschitz functions on a spherical domain. This achievement demonstrates that large language models can contribute to pure mathematical research, solving problems that have resisted human mathematicians for decades. It marks a shift from AI being a tool for computation to an active research partner. The problem focused on the time complexity of minimizing convex Lipschitz functions over a spherical domain, a long-standing conjecture. The proof was generated by GPT-5.6 in a single interaction, not through iterative refinement, highlighting the model's reasoning capabilities.

hackernews · mbustamanter · Jul 18, 13:00 · [Discussion](https://news.ycombinator.com/item?id=48957779)

**Background**: Convex optimization studies the minimization of convex functions over convex sets, with many practical applications in engineering, machine learning, and economics. The 30-year gap refers to a missing upper bound on the number of iterations required to solve certain convex optimization problems. This result provides that bound, validating conjectures about optimal algorithms.

<details><summary>References</summary>
<ul>
<li><a href="https://news.ycombinator.com/item?id=48957779">GPT-5.6 used a prompt to close a 30-year gap in convex optimization | Hacker News</a></li>
<li><a href="https://en.wikipedia.org/wiki/Convex_optimization">Convex optimization - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Duality_(optimization)">Duality (optimization) - Wikipedia</a></li>

</ul>
</details>

**Discussion**: The community discussion was largely positive, with experts noting the result is a real but niche contribution. Some commenters expressed concern about AI replacing low-hanging fruit research, while others suggested LLMs could help verify impenetrable human proofs, such as the abc conjecture. There was clarification that the model used was Sol Pro, not Ultra.

**Tags**: `#AI`, `#convex optimization`, `#mathematical research`, `#GPT`, `#LLM`

---

<a id="item-6"></a>
## [StackOverflow decline debated: AI vs community policies](https://data.stackexchange.com/stackoverflow/query/1953768#graph) ⭐️ 8.0/10

A graph from Stack Exchange data shows a long-term decline in StackOverflow activity, sparking debate about whether AI tools like ChatGPT or earlier factors such as strict community policies and corporate acquisition caused the drop. This discussion matters because it challenges the simplistic narrative that AI alone killed StackOverflow, highlighting how community governance and business decisions can affect platform health. The graph's peak was around 2014, long before generative AI became mainstream, and community comments point to StackOverflow's acquisition by Prosus in 2021 as another inflection point.

hackernews · secretslol · Jul 18, 11:12 · [Discussion](https://news.ycombinator.com/item?id=48956949)

**Background**: StackOverflow is a Q&A platform where users earn reputation and badges, but its strict moderation and resistance to casual conversation alienated newcomers. The rise of AI assistants like ChatGPT offers an alternative for quick answers, but the data shows activity was declining before AI became prevalent.

**Discussion**: Community comments largely attribute StackOverflow's decline to its exclusionary culture and strict policies, rather than AI. Some users note the decline began after the 2014 peak and accelerated after the Prosus acquisition, suggesting multiple factors beyond AI.

**Tags**: `#StackOverflow`, `#AI impact`, `#online communities`, `#developer tools`, `#data analysis`

---

<a id="item-7"></a>
## [Kimi K3 Breaks Records with 2.8 Trillion Parameters](https://simonwillison.net/2026/Jul/16/kimi-k3/#atom-everything) ⭐️ 8.0/10

Moonshot AI released Kimi K3, a 2.8 trillion parameter open-weight model, outperforming many competitors on benchmarks, with open weights promised by July 27, 2026. This marks the largest open-parameter AI model to date, potentially democratizing access to frontier-level capabilities at a lower cost than proprietary rivals like GPT-5.6 and Claude Opus 4.8. Kimi K3 costs $3/million input tokens and $15/million output tokens, making it the most expensive Chinese AI model, but it uses 21% fewer output tokens than its predecessor K2.6.

rss · Simon Willison · Jul 16, 20:19

**Background**: The pelican benchmark refers to Simon Willison's informal test of generating an SVG of a pelican riding a bicycle, used to compare model creativity and instruction following. This test has become a community-driven way to evaluate AI image generation capabilities, with a Hugging Face space tracking results.

<details><summary>References</summary>
<ul>
<li><a href="https://ndurner.github.io/pelican-benchmark">Pelican vs. Llama 3.1 405B and others | Nils Durner’s Blog</a></li>
<li><a href="https://huggingface.co/spaces/victor/pelican-benchmark">Pelican Benchmark - a Hugging Face Space by victor</a></li>

</ul>
</details>

**Tags**: `#AI`, `#large language models`, `#open source`, `#benchmarks`

---

<a id="item-8"></a>
## [Shanghai AI Lab's Self-Harness boosts agent performance by 104% without model changes](https://mp.weixin.qq.com/s?__biz=MzIzNjc1NzUzMw==&mid=2247904823&idx=3&sn=af8b10819641ba1f59492acb8aa9ebd4) ⭐️ 8.0/10

Researchers at Shanghai Artificial Intelligence Laboratory introduced Self-Harness, a framework that enables an LLM-based agent to autonomously improve its own operating rules, resulting in a 104% performance improvement without modifying the underlying model. This breakthrough demonstrates that agents can self-evolve at the harness level, potentially reducing the need for human engineering and accelerating the deployment of more capable AI agents. It also shifts the optimization focus from model parameters to the surrounding software infrastructure. The Self-Harness approach outperforms previous methods by a large margin, achieving a 104% improvement in agent performance on benchmark tasks. The framework allows the harness to rewrite its own rules, including tool usage, memory management, and execution policies.

rss · 量子位 · Jul 18, 07:45

**Background**: An agent harness is the software infrastructure around a large language model that enables it to act as an AI agent, managing tools, memory, state, and execution loops. Traditionally, harnesses are designed by human engineers and remain static, but Self-Harness introduces a paradigm where the harness improves itself over time through iterative feedback and self-modification.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2606.09498">[2606.09498] Self-Harness: Harnesses That Improve Themselves</a></li>
<li><a href="https://venturebeat.com/orchestration/researchers-introduce-self-harness-a-framework-that-lets-ai-agents-rewrite-their-own-rules-boosting-performance-up-to-60">Researchers introduce Self-Harness, a framework that lets AI agents rewrite their own rules, boosting performance up to 60% | VentureBeat</a></li>
<li><a href="https://en.wikipedia.org/wiki/Agent_harness">Agent harness</a></li>

</ul>
</details>

**Tags**: `#AI`, `#agent`, `#self-evolution`, `#harness`, `#Shanghai AI Lab`

---

<a id="item-9"></a>
## [Did AI Slop Win a $25k DeepMind/Kaggle Grand Prize?](https://www.reddit.com/r/MachineLearning/comments/1uzyf66/did_blatant_ai_slop_just_win_a_25k_usd_deepmind/) ⭐️ 8.0/10

A Redditor presented detailed evidence that a nonsensical submission won a $25,000 grand prize in the Google DeepMind-sponsored Kaggle competition 'Measuring Progress Toward AGI - Cognitive Abilities', questioning the integrity of the review process. This incident raises serious concerns about the reliability of high-stakes AI competition reviews and could undermine trust in benchmark-driven progress toward Artificial General Intelligence. The winning submission was reportedly 10 times larger than the required format and contained unfounded claims, while organizers maintain the review was properly conducted and subjectivity is inherent.

reddit · r/MachineLearning · /u/TheWerkmeister · Jul 18, 15:10

**Background**: In March 2026, Google DeepMind launched a $200,000 Kaggle hackathon to develop cognitive-science-based benchmarks for measuring progress toward AGI, with multiple tracks and $25,000 grand prizes. The competition aimed to evaluate AI across ten cognitive abilities, but defining and benchmarking AGI remains highly controversial and challenging.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.google/innovation-and-ai/models-and-research/google-deepmind/measuring-agi-cognitive-framework/">Measuring Progress Towards AGI: A Cognitive Framework</a></li>
<li><a href="https://liora.io/en/google-deepmind-framework-measure-agi">Google DeepMind reveals cognitive framework to finally measure AGI</a></li>
<li><a href="https://spectrum.ieee.org/agi-benchmark">AGI Benchmarks: Tracking Progress Toward AGI Isn't Easy - IEEE Spectrum</a></li>

</ul>
</details>

**Tags**: `#AI ethics`, `#Kaggle`, `#DeepMind`, `#AGI benchmarks`

---

<a id="item-10"></a>
## [Stereo2Spatial: Convert Stereo to Binaural Audio with Diffusion](https://www.reddit.com/r/MachineLearning/comments/1uzevbg/stereo2spatial_convert_stereo_music_tracks_to/) ⭐️ 8.0/10

The author released a new flow-matching diffusion model called Stereo2Spatial that converts stereo music tracks into spatialized binaural mixes. The model uses memory tokens to maintain long-context stability and was trained on 7,669 tracks. This addresses the lack of quality spatial mixes for existing music, enabling immersive listening experiences. The open-source release under Apache 2.0 encourages further development in spatial audio generation. The model initially operated in the latent space of a VAE but switched to raw waveforms to overcome quality bottlenecks, using amplitude lifting for training stability. It includes optional mix-style conditioning and a Windows desktop app for inference.

reddit · r/MachineLearning · /u/kittenkrazy · Jul 17, 22:55

**Background**: Flow-matching diffusion models generate data by learning probability paths between noise and data distributions. Binaural audio simulates 3D sound using two channels, while spatial audio formats like 7.1.4 use multiple speakers. VAE (Variational Autoencoder) compresses audio into a latent space for efficient processing.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/html/2601.12950v1">ImmersiveFlow : Stereo-to-7.1.4 Spatial Audio Generation with Flow ...</a></li>
<li><a href="https://huggingface.co/earlab/EAR_VAE">earlab/ EAR _ VAE · Hugging Face</a></li>
<li><a href="https://arxiv.org/abs/2210.02747">[2210.02747] Flow Matching for Generative Modeling</a></li>

</ul>
</details>

**Tags**: `#machine learning`, `#audio processing`, `#spatial audio`, `#diffusion models`, `#VAE`

---

<a id="item-11"></a>
## [Prism Bug Leaks Unpublished Papers in Academic Publishing](https://www.reddit.com/r/MachineLearning/comments/1uz75qt/prism_accidentally_leaked_d/) ⭐️ 8.0/10

A bug in Prism's compilation process accidentally leaked unpublished papers, as reported on Reddit and Twitter. The Prism team took the website down within 10 minutes of the first report. This incident raises serious concerns about the security of academic submission systems, potentially compromising the confidentiality of unpublished research. It could erode trust in digital tools used for paper compilation and submission in the ML community. The bug caused the compilation feature to return another user's paper instead of the intended one. The vulnerability was flagged on Prism's Discord and Twitter, and the site was taken down within 10 minutes.

reddit · r/MachineLearning · /u/Few-Monitor5103 · Jul 17, 17:59

**Background**: Prism is a tool designed to streamline academic paper compilation and formatting, often used by researchers submitting to machine learning conferences. Such tools compile LaTeX or other source files into PDF documents for submission. A bug in the compilation process could mix up files from different users, leading to data leaks.

<details><summary>References</summary>
<ul>
<li><a href="http://atomicego.com/ai-tools/prism/prism-academic-workflow">How to Use Prism and NotebookLM to Understand, Build, and Publish</a></li>

</ul>
</details>

**Tags**: `#paper leak`, `#security`, `#academic publishing`, `#ML conference`, `#privacy`

---

<a id="item-12"></a>
## [EU AI Act OpenRAG: 933 Legally Structured Chunks with BGE-M3 Embeddings](https://www.reddit.com/r/MachineLearning/comments/1uytlac/eu_ai_act_openrag_933_legally_structured_chunks/) ⭐️ 8.0/10

A downloadable corpus of the EU AI Act (Regulation 2024/1689) has been released, containing 933 legally structured chunks with normalized 1024-dimensional BGE-M3 embeddings, along with evaluation benchmarks and full methodology. This resource provides a high-quality, structured dataset for legal retrieval-augmented generation (RAG) and NLP, enabling reproducible evaluation and comparison of chunking strategies, retrieval methods, and embedding models in a legally meaningful domain. The SQLite database includes 933 chunks, exact EUR-Lex links, Article 113 application-date metadata, and deliberately narrow derived labels; evaluation on the AI Act Evaluation Benchmark showed structural chunking improved scenario article recall@20 from 0.449 to 0.541 and QA article hit@10 from 0.898 to 0.927.

reddit · r/MachineLearning · /u/Automatic-Forever-63 · Jul 17, 08:18

**Background**: The EU AI Act is a landmark regulation governing artificial intelligence, which requires legal AI systems to interpret its provisions accurately. Retrieval-augmented generation (RAG) combines information retrieval with language models, but standard chunking methods (e.g., sliding windows) often break legal document structure. BGE-M3 is a powerful multilingual embedding model developed by BAAI that supports dense retrieval, while EUR-Lex is the official EU law database used for linking.

<details><summary>References</summary>
<ul>
<li><a href="https://ollama.com/library/bge-m3">bge - m 3</a></li>
<li><a href="https://en.wikipedia.org/wiki/EUR-Lex">EUR - Lex - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#RAG`, `#legal NLP`, `#EU AI Act`, `#embeddings`, `#dataset`

---

<a id="item-13"></a>
## [SpaceX in Talks with Pentagon for Billion-Dollar AI Compute Deal](https://www.wsj.com/tech/ai/spacex-in-talks-to-provide-computing-power-for-pentagons-ai-push-15e752e4) ⭐️ 8.0/10

SpaceX is negotiating with the U.S. Department of Defense to provide data center computing power for running AI models, with a potential deal valued in the tens of billions of dollars. This would mark a significant expansion of SpaceX's cloud computing business and deepen its relationship with the Pentagon, influencing the AI infrastructure market and national security capabilities. The negotiations are ongoing and could still fall through. Recently, SpaceX signed similar computing power supply agreements with Anthropic and Google, and plans to significantly expand its cloud business.

telegram · zaihuapd · Jul 18, 01:44

**Background**: The Pentagon is accelerating the acquisition of cloud computing capabilities to support AI applications in national security and daily operations. It has recently approved SpaceX, Amazon, Google, Microsoft, and Oracle to use their AI models in classified environments. SpaceX's unique space-based assets, such as Starlink, could give it an edge in secure data transmission.

<details><summary>References</summary>
<ul>
<li><a href="https://goodinfo.net/posts/ai-tech/pentagon-ai-classified-deals-may-2026/">五 角 大 楼 与七 大 科技巨头签署 机 密 AI 部署协议，Anthropic... | goodinfo.net</a></li>
<li><a href="https://www.coodoor.com/2026/04/gemini.html">谷歌正在和美国 五 角 大 楼 商量，想把Gemini...</a></li>

</ul>
</details>

**Tags**: `#AI算力`, `#SpaceX`, `#国防技术`, `#云计算`, `#大语言模型`

---

<a id="item-14"></a>
## [OpenRouter reportedly attracts acquisition interest at >$1.3B valuation](https://www.theinformation.com/articles/startup-openrouter-fields-multi-billion-dollar-takeover-interest) ⭐️ 8.0/10

OpenRouter, an AI model routing platform, has been approached by multiple large tech companies for a potential acquisition at a valuation exceeding its $1.3 billion post-money valuation from its Series B round in May. This signals strong market validation and potential consolidation in the AI model routing space, a critical infrastructure layer for cost-effective LLM access. A high acquisition premium would underscore the strategic value of unified API gateways for enterprises. OpenRouter's Series B, led by Alphabet's CapitalG, raised $113 million at about a $1.3 billion valuation — more than doubling from the $547 million valuation in its Series A last June. The platform routes over 400 models, serves ~8 million users, processes roughly 100 trillion tokens per month, and had an annualized revenue of about $50 million as of early 2026.

telegram · zaihuapd · Jul 18, 03:45

**Background**: AI model routing platforms provide a single API gateway to access hundreds of large language models, automatically directing queries to the most cost-effective or performant option. This abstraction layer simplifies developer integration and reduces vendor lock-in, making it a crucial part of the growing LLM ecosystem.

<details><summary>References</summary>
<ul>
<li><a href="https://openrouter.ai/">The unified interface for LLMs. Find the best models & prices for your...</a></li>
<li><a href="https://gate.ai/">Gate. AI — Enterprise-grade AI large-scale model routing and...</a></li>

</ul>
</details>

**Tags**: `#AI infrastructure`, `#acquisition`, `#startup`, `#model routing`, `#LLM`

---

<a id="item-15"></a>
## [TSMC Announces A14 Process for 2028 Production](https://t.me/zaihuapd/42643) ⭐️ 8.0/10

TSMC has announced its next-generation A14 process technology, scheduled to start production in 2028. Compared to the N2 node, A14 offers up to 15% faster speed at the same power, up to 30% lower power at the same speed, and over 20% higher logic density. This announcement reinforces TSMC's leadership in advanced semiconductor manufacturing, crucial for AI, HPC, and mobile processors. The A14 node is expected to drive significant performance and efficiency improvements for future chips, keeping TSMC ahead of competitors like Intel and Samsung. TSMC also plans an intermediate A16 process for late 2026, while N2 volume production began in Q4 2025. The A14 node is likely a 1.4nm-class technology, and TSMC has confirmed strong customer interest from AI, HPC, and smartphone sectors.

telegram · zaihuapd · Jul 18, 05:00

**Background**: TSMC (Taiwan Semiconductor Manufacturing Company) is the world's largest dedicated semiconductor foundry. Process nodes (e.g., N2, A14) refer to the manufacturing technology generation, with smaller numbers generally indicating more advanced, higher-density transistors. A14 succeeds N2 (2nm-class) and is part of TSMC's roadmap to maintain technological leadership, competing with Intel's 18A and Samsung's SF2 nodes.

<details><summary>References</summary>
<ul>
<li><a href="https://xab.info/en/posts/tsmc-a14-performance-surpasses-n2">TSMC Breaks Its Own Records: New A 14 (1.4nm) Process ... - XAB.info</a></li>
<li><a href="https://www.newkerala.com/news/a/tsmc-projects-mass-production-advanced-a14-chips-2028-477.htm">TSMC A 14 Chips Mass Production by 2028</a></li>
<li><a href="https://www.tomshardware.com/tech-industry/semiconductors/tsmc-confirms-significant-yield-and-performance-improvements-in-a14-update-strong-interest-from-ai-hpc-and-smartphone-customers">TSMC confirms significant yield and performance... | Tom's Hardware</a></li>

</ul>
</details>

**Tags**: `#TSMC`, `#semiconductor`, `#process technology`, `#A14`, `#hardware`

---

<a id="item-16"></a>
## [San Francisco Orders Apple, Google to Remove 'Nudify' Apps](https://techcrunch.com/2026/07/17/apple-and-google-ordered-to-purge-nudify-apps-from-app-stores/) ⭐️ 8.0/10

San Francisco City Attorney David Chiu sent letters demanding Apple and Google remove dozens of AI-powered 'nudify' apps from their app stores, citing their role in generating non-consensual deepfake intimate images. This action highlights the growing legal pressure on tech platforms to address AI misuse and deepfake pornography, potentially setting precedents for platform liability and user safety enforcement. The apps operate by using AI to digitally remove clothing from photos without consent. Apple said it removed three apps and terminated related developer accounts, while Google suspended the five Play Store apps named in the letter.

telegram · zaihuapd · Jul 18, 08:45

**Background**: Deepfake technology uses deep learning to create realistic but fake images and videos, often used maliciously to create non-consensual pornography. 'Nudify' apps are a subset of deepfake apps that strip clothing from photos, raising serious privacy and ethics concerns. Legal actions like this are part of a broader push to regulate AI-generated content and hold platforms accountable for what they distribute.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Nudify_apps">Nudify apps</a></li>
<li><a href="https://copperpod.medium.com/deepfake-and-ai-to-be-or-not-to-be-8b8825fe0f0">Deepfake and AI: To Be or Not To Be | by Copperpod IP | Medium</a></li>

</ul>
</details>

**Tags**: `#AI ethics`, `#deepfake`, `#platform regulation`, `#privacy`, `#legal`

---

<a id="item-17"></a>
## [Regressive JPEGs: Video Animation via Progressive JPEG Loading](https://maurycyz.com/projects/bad_jpeg/) ⭐️ 7.0/10

The project 'Regressive JPEGs' exploits the progressive loading feature of JPEG images to display a crude video animation, with each progressive scan acting as a video frame and playback speed tied to network delay. This hack demonstrates a novel misuse of a standard image format, sparking creative ideas for steganography, content filtering bypass, and unconventional UI elements, though it has limited practical use. The animation is entirely dependent on network delay because progressive JPEG scans are sent sequentially; the timing between frames is uncontrolled by the image itself.

hackernews · vitaut · Jul 18, 03:14 · [Discussion](https://news.ycombinator.com/item?id=48954851)

**Background**: Progressive JPEGs are a variant of the standard JPEG format that display a low-quality version of the image first and then refine it in subsequent scans, improving perceived load time. This project uses each progressive scan as a separate frame, creating a crude video when the image is loaded over a network with variable delay.

<details><summary>References</summary>
<ul>
<li><a href="https://www.ctrl.blog/entry/jpeg-progressive-loading.html">Progressive JPEGs make a meaningful impact on perceived... | Ctrl blog</a></li>
<li><a href="https://calendar.perfplanet.com/2012/progressive-jpegs-a-new-best-practice/">Progressive jpegs : a new best practice - Web Performance Calendar</a></li>

</ul>
</details>

**Discussion**: Community members shared related experiments (e.g., using interlaced PNG for similar effects) and discussed potential applications like progress bars. Some noted cross-browser inconsistencies, particularly on mobile iOS. Others speculated about steganography and content filter evasion.

**Tags**: `#jpeg`, `#progressive-image`, `#video`, `#web`, `#hack`

---

<a id="item-18"></a>
## [Claude Fable 5 Made Permanent in Subscription Plans](https://simonwillison.net/2026/Jul/18/claude-make-fable-5-permanent/#atom-everything) ⭐️ 7.0/10

Anthropic reversed its plan to remove Claude Fable 5 from subscription accounts, announcing that beginning July 20, Fable 5 will be included in all Max and Team Premium plans at 50% of limits. This decision reflects intense competitive pressure from GPT-5.6 Sol and Kimi 3, ensuring that subscribers continue to have access to Anthropic's most capable model without paying extra API fees. Users on the $20/month plan still lack access to Fable 5; Max plans cost $100 or $200 per month. Pro and Team Standard users receive a one-time $100 credit for usage-based access.

rss · Simon Willison · Jul 18, 06:00

**Background**: Claude Fable 5 is Anthropic's most advanced model designed for autonomous, long-running agentic work, with a 1M-token context window. It competes directly with OpenAI's GPT-5.6 Sol and Kimi's Kimi 3, which have recently shown strong performance in coding and reasoning benchmarks. Anthropic's original plan to phase out Fable 5 from subscriptions was driven by compute capacity concerns, but competitive dynamics forced a pivot.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/claude/fable">Claude Fable \ Anthropic</a></li>
<li><a href="https://openai-dotcom-git-main-openai.vercel.app/index/gpt-5-6/">GPT - 5 . 6 : Frontier intelligence that scales with your ambition | OpenAI</a></li>
<li><a href="https://platform.kimi.ai/docs/guide/kimi-k3-quickstart">Kimi K 3 - Kimi API Platform</a></li>

</ul>
</details>

**Tags**: `#Claude`, `#Anthropic`, `#AI models`, `#subscription pricing`, `#competition`

---

<a id="item-19"></a>
## [DABSN: New Recurrent LM Seeks Collaborators](https://www.reddit.com/r/MachineLearning/comments/1uycffg/seeking_collaborators_for_scaling_and_independent/) ⭐️ 7.0/10

An independent researcher released DABSN, a novel recurrent architecture with open-source code and initial language model results, and is seeking collaborators to scale and independently evaluate the model. If validated, DABSN could offer a more efficient alternative to transformer models for long-context language tasks, potentially advancing open-source AI research and reducing reliance on large-scale compute. The architecture shows promising results on reasoning and memory benchmarks like MQAR and Copy, and the researcher trained a 24M-parameter language model on 1 billion tokens using a GPT-2 tokenizer. Code is available in PyTorch, C++, and Triton implementations.

reddit · r/MachineLearning · /u/BleedingXiko · Jul 16, 19:17

**Background**: Recurrent neural networks (RNNs) process sequences step by step, making them computationally efficient for long sequences but historically harder to parallelize than transformers. DABSN is a new RNN variant designed to improve dynamic bias and state adaptation. The use of Triton, a Python-like GPU programming language, enables custom high-performance kernels without CUDA expertise.

<details><summary>References</summary>
<ul>
<li><a href="https://www.emergentmind.com/topics/multi-query-associative-recall-mqar">MQAR : Multi-Query Associative Recall</a></li>
<li><a href="https://triton-lang.org/main/">Welcome to Triton ’s documentation! — Triton documentation</a></li>

</ul>
</details>

**Tags**: `#Recurrent Neural Networks`, `#Language Model`, `#Open Source`, `#Machine Learning Research`

---

<a id="item-20"></a>
## [Doubao Phone Drops GUI Operations, Demands MCP from Super Apps](https://www.latepost.com/news/dj_detail?id=3648) ⭐️ 7.0/10

Doubao Phone has shifted its strategy: instead of using GUI hard operation to directly interact with top apps like WeChat and Taobao, it now requires these super apps to provide MCP (Model Context Protocol) services to open their data and control permissions. The company has increased its stockpile from 30,000 units to hundreds of thousands. This move shifts the power dynamic in the AI phone ecosystem, from phone-centric automation to platform-authorized data access. It could set a precedent for how AI assistants integrate with major apps, impacting user privacy, app control, and the race for AI entry points. The Doubao Phone assistant previously faced bans from WeChat and Taobao for using GUI simulation. The new approach aligns with Apple and Google's shift toward developer-authorized MCP-like frameworks, emphasizing cooperation over circumvention.

telegram · zaihuapd · Jul 18, 00:29

**Background**: GUI hard operation refers to technology that reads the phone screen and simulates human taps to control apps. MCP (Model Context Protocol) is an open standard that allows AI models to securely connect to tools and data sources via authorized APIs. Major tech companies are competing to become the primary AI entry point, creating tension between device makers and app platforms.

<details><summary>References</summary>
<ul>
<li><a href="https://www.163.com/dy/article/L22ST2EA0531M1CO.html?clickfrom=w_dy">晚点独家丨新豆包手机备货数十万台，AI 不再 硬 操 作 头部应用</a></li>
<li><a href="https://modelcontextprotocol.io/">What is the Model Context Protocol ( MCP )? - Model Context Protocol</a></li>

</ul>
</details>

**Tags**: `#AI手机`, `#MCP`, `#应用生态`, `#AI助手`, `#豆包`

---

<a id="item-21"></a>
## [SK Hynix CEO Warns of Worst Memory Shortage by 2027](https://t.me/zaihuapd/42645) ⭐️ 7.0/10

SK Hynix CEO Kwak Noh-Jung warned that the global memory industry will face its most severe supply shortage by 2027, with customer demand outstripping supply capacity even after aggressive expansion. This warning from a top memory manufacturer signals a prolonged supply-demand imbalance that could drive up memory prices and affect downstream industries like AI, cloud computing, and consumer electronics. Kwak revealed that SK Hynix is considering overseas fab locations including the US, Japan, and Southeast Asia, prioritizing land, electricity, and labor costs. The company's 2025 operating profit reached a record 47 trillion KRW (~$31 billion).

telegram · zaihuapd · Jul 18, 06:30

**Background**: The memory industry has historically experienced boom-bust cycles driven by fluctuating demand and capacity additions. SK Hynix is a leading DRAM and NAND flash manufacturer, competing closely with Samsung and Micron. The warning comes amid surging demand for high-bandwidth memory (HBM) used in AI accelerators, which is straining production capacity.

**Tags**: `#memory industry`, `#supply chain`, `#semiconductors`, `#SK Hynix`

---

<a id="item-22"></a>
## [Bilibili's 'Project N.E.K.O.' Open-Source AI Companion at WAIC 2026](https://finance.sina.com.cn/roll/2026-07-18/doc-iniifanf8394663.shtml) ⭐️ 7.0/10

Bilibili showcased Project N.E.K.O., an open-source AI companion that understands desktop content and initiates proactive conversations, at the WAIC 2026 conference from July 17-20. Project N.E.K.O. combines open-source accessibility with advanced features like multimodal screen understanding and voice cloning, potentially democratizing AI companion technology for developers and users. The companion supports Live2D and VRM model engines, includes TTS with voice cloning, and separates UI, AI brain, and memory for local data privacy. It has over 1,000 GitHub stars and 10,000 Steam users.

telegram · zaihuapd · Jul 18, 06:45

**Background**: AI companions are software agents that interact with users through conversations and actions. Project N.E.K.O. is an open-source project that aims to create a digital life form capable of perceiving the user's screen and environmental context. Live2D and VRM are popular formats for 2D and 3D character rendering used in virtual YouTubers and games.

<details><summary>References</summary>
<ul>
<li><a href="https://project-neko.online/">Project N . E . K . O .</a></li>
<li><a href="https://store.steampowered.com/app/4099310/Project_NEKO/">Project N . E . K . O . on Steam</a></li>

</ul>
</details>

**Tags**: `#AI companion`, `#open-source`, `#multimodal AI`, `#voice cloning`, `#Live2D`

---

<a id="item-23"></a>
## [South Korea Official Proposes AI Dividend from Chip Profits](https://t.me/zaihuapd/42652) ⭐️ 7.0/10

South Korean official Kim Yong-beom proposed a national dividend system that would redistribute structural excess profits from AI semiconductors to all citizens, modeled after Norway's oil fund. The proposal triggered a 5.1% crash in the KOSPI index on Tuesday. This policy could reshape how AI-driven economic gains are distributed, preventing wealth concentration and potentially setting a precedent for other nations. The market panic reflects investor concern over reduced corporate profits and increased regulation. Kim argued that AI infrastructure benefits stem from half a century of national investment, not just corporate effort, so profits should be shared. The proposal suggests using the dividend for youth entrepreneurship and pension funds, but lacks specific implementation rules.

telegram · zaihuapd · Jul 18, 14:20

**Background**: Norway's Government Pension Fund Global, the world's largest sovereign wealth fund, reinvests oil profits for future generations. Similarly, South Korea's semiconductor industry has generated massive profits amid the AI boom, raising questions about equitable distribution. The concept of 'structural excess profits' refers to gains beyond normal market returns, attributed to public infrastructure and education.

<details><summary>References</summary>
<ul>
<li><a href="https://www.nbim.no/">The fund | Norges Bank Investment Management</a></li>
<li><a href="https://www.koreatimes.co.kr/southkorea/society/20260715/what-defines-excess-profits-and-who-should-benefit-from-them">What defines ' excess ' profits and who should... - The Korea Times</a></li>
<li><a href="https://www.ajupress.com/view/20260514173753142">BLUE HOUSE INSIGHT: Dialogue on ' excess profits ... | AJU PRESS</a></li>

</ul>
</details>

**Tags**: `#AI policy`, `#economic distribution`, `#semiconductors`, `#South Korea`, `#universal dividend`

---

<a id="item-24"></a>
## [Fable 5 vs GPT-5.6 Sol: Does /goal Help on NP-Hard Tasks?](https://charlesazam.com/blog/fable-5-gpt-5-6-sol-goal/) ⭐️ 6.0/10

A technical blog post compares Anthropic's Fable 5 and OpenAI's GPT-5.6 Sol on an NP-Hard problem to test whether the /goal directive improves problem-solving performance. This comparison offers practical insights into prompt engineering and model capabilities for complex reasoning, which is valuable for AI developers and researchers seeking to optimize performance on hard computational problems. The author notes that the chart's y-axis is inverted, causing confusion—numerically lower scores are better, but visually higher bars represent better performance. Community comments also suggest that /goal is more effective for single-track investigations than for complex multi-agent strategies.

hackernews · couAUIA · Jul 18, 11:00 · [Discussion](https://news.ycombinator.com/item?id=48956879)

**Background**: NP-Hard problems are a class of computationally difficult problems for which no efficient solution is known. The /goal directive is a prompt engineering technique that instructs the AI to focus on a specific objective. Fable 5 is Anthropic's Mythos-class model designed for long-running agentic tasks, while GPT-5.6 Sol is OpenAI's coding-focused model that sets state-of-the-art on the Artificial Analysis Coding Agent Index.

<details><summary>References</summary>
<ul>
<li><a href="https://cursor.com/docs/models/claude-fable-5">Claude Fable 5 | Cursor Docs</a></li>
<li><a href="https://openai-dotcom-git-main-openai.vercel.app/index/gpt-5-6/">GPT - 5 . 6 : Frontier intelligence that scales with your ambition | OpenAI</a></li>
<li><a href="https://medium.com/@PropagenAI/the-definitive-guide-to-transformative-prompt-engineering-980fc3c4665a">The Definitive Guide to Transformative Prompt Engineering | Medium</a></li>

</ul>
</details>

**Discussion**: Community members requested seeing the best score over time and suggested using 'ultra mode' for better comparison. Some users expressed confusion over the inverted chart, while others shared their experiences: one noted Claude Code's slowness compared to OpenAI's Codex, and another mentioned that Claude tends to forget instructions in long sessions.

**Tags**: `#AI`, `#LLM comparison`, `#NP-Hard`, `#problem solving`, `#prompt engineering`

---

<a id="item-25"></a>
## [TabFM Studio: No-Code Spreadsheet Predictions with Tabular Foundation Models](https://www.reddit.com/r/MachineLearning/comments/1uzx1el/tabfm_studio_pointandclick_predictions_on/) ⭐️ 6.0/10

A developer released TabFM Studio, a web application that allows users to perform point-and-click predictions on CSV or Excel files using Google's TabFM tabular foundation model, without writing any code. This tool significantly lowers the barrier for non-programmers to leverage state-of-the-art tabular foundation models, potentially democratizing access to automated data analysis and prediction in spreadsheet workflows. The app currently only supports Google's TabFM model, and it works by treating filled target cells as in-context examples and predicting empty ones directly on the grid interface.

reddit · r/MachineLearning · /u/Lckylke · Jul 18, 14:15

**Background**: Tabular foundation models are large neural networks pre-trained on millions of synthetic datasets to perform predictions on new tables without retraining. Google's TabFM is a zero-shot tabular foundation model that can handle classification and regression tasks on tabular data. This web app wraps TabFM in a simple user interface, making it accessible to users without coding skills.

<details><summary>References</summary>
<ul>
<li><a href="https://research.google/blog/introducing-tabfm-a-zero-shot-foundation-model-for-tabular-data/">Introducing TabFM : A zero-shot foundation model for tabular data</a></li>
<li><a href="https://huggingface.co/google/tabfm-1.0.0-pytorch">google / tabfm -1.0.0-pytorch · Hugging Face</a></li>

</ul>
</details>

**Tags**: `#tabular foundation models`, `#no-code`, `#machine learning tool`, `#spreadsheet`, `#TabFM`

---