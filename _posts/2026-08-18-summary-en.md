---
layout: default
title: "Horizon Summary: 2026-08-18 (EN)"
date: 2026-08-18
lang: en
---

> From 56 items, 24 important content pieces were selected

---

1. [AirTag Investigation Reveals Amazon's Rare-Book Scanning for AI Training](#item-1) ⭐️ 9.0/10
2. [Bricked Framework 13 Laptop Rescued with $20 Tools, Sparking Repairability Debate](#item-2) ⭐️ 8.0/10
3. [Amazon's Hidden Convenience Tax](#item-3) ⭐️ 8.0/10
4. [Cursor launches Origin, a GitHub alternative](#item-4) ⭐️ 8.0/10
5. [Memory prices jump 500% in 12 months, 128GB DDR5 reaches $3,399](#item-5) ⭐️ 8.0/10
6. [Qwen 3.8 27B matches GPT-5.6 Luna on AI Intelligence Index](#item-6) ⭐️ 8.0/10
7. [Researcher Exposes Evaluation Tricks That Make Sparse Attention and KV Compression Look Good](#item-7) ⭐️ 8.0/10
8. [Train-mounted line-scan camera turns railways into a flatbed scanner](#item-8) ⭐️ 7.0/10
9. [Linux 7.3 Improves Performance When GPU VRAM Runs Out](#item-9) ⭐️ 7.0/10
10. [Polars Cheatsheet Distills 500-Page O'Reilly Book into Two Pages](#item-10) ⭐️ 7.0/10
11. [Open-Source World Model Generates Hour-Long Videos Without Drift](#item-11) ⭐️ 7.0/10
12. [AI Labs Dismantle Ethics Oversight, Leaving Accountability Gaps](#item-12) ⭐️ 7.0/10
13. [Hobbyist Trains Diffusion Model on 264KB SRAM Microcontroller](#item-13) ⭐️ 7.0/10
14. [Unitree Robotics Launches STAR Market IPO Inquiry, Targets 400B Yuan Valuation](#item-14) ⭐️ 7.0/10
15. [WeChat Work 5.0.10 Opens CLI and MCP to AI Agents](#item-15) ⭐️ 7.0/10
16. [China Domestic AI Chips to Claim 90% of Market by 2026, Cambricon and Huawei Lead](#item-16) ⭐️ 7.0/10
17. [Sugar Rationing in Early Life Linked to Lower Adult Cancer Risk](#item-17) ⭐️ 6.0/10
18. [Markdown SVG Renderer Adds Browser-Based MP4 Export for Animated SVGs](#item-18) ⭐️ 6.0/10
19. [SineKAN: Kolmogorov-Arnold Networks with Sinusoidal Activations](#item-19) ⭐️ 6.0/10
20. [Italy Fines Apple €115 Million for Abusing App Store Dominance Over ATT Policy](#item-20) ⭐️ 6.0/10
21. [iOS 27 Beta 5 Shows Apple Intelligence's China Privacy Plan](#item-21) ⭐️ 6.0/10
22. [China Orders Some Agencies to Uninstall Custom Windows 10, Ahead of Plan](#item-22) ⭐️ 6.0/10
23. [Baidu Netdisk Accused of Filing Income Tax for Users Without Consent](#item-23) ⭐️ 6.0/10
24. [OpenAI and CodeAI Partner to Expand Responsible AI Education for Teens](#item-24) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [AirTag Investigation Reveals Amazon's Rare-Book Scanning for AI Training](https://simonwillison.net/2026/Aug/17/we-tracked-a-shipment-of-rare-books-it-ended-at-an-amazon-ai-tra/) ⭐️ 9.0/10

404 Media used an AirTag hidden inside a rare book to trace a large order from a bookseller. The book was delivered to the VGT3 area of Amazon's LAS8 facility in Las Vegas, where workers reportedly destructively scan books for AI training data. This provides concrete evidence that Amazon is scanning physical books for AI training, confirming long-standing suspicions about anonymous bulk book purchases. It further highlights growing legal and ethical concerns over using copyrighted books as training data without permission. The book order was placed through Biblio, an online marketplace for used and rare books. Amazon workers' forum posts confirmed that VGT3 destructively scans large volumes of books, and the facility entrance even features a dinosaur-with-book logo.

rss · Simon Willison · Aug 17, 15:21

**Background**: For years, AI companies have been quietly buying large volumes of books to scan for training data, sometimes destroying the physical copies. 404 Media's investigative trick was to place an AirTag inside a book to trace the supply chain. Similar practices were previously reported at Anthropic, which reportedly cut millions of books from their bindings to scan them. Amazon's LAS8 facility is a fulfillment center in Las Vegas that also appears to house scanning operations like VGT3.

<details><summary>References</summary>
<ul>
<li><a href="https://qz.com/amazon-rare-books-destroying-ai-training-data-081826">Amazon destroying rare books to scan them for AI training data</a></li>
<li><a href="https://arstechnica.com/ai/2025/06/anthropic-destroyed-millions-of-print-books-to-build-its-ai-models/">Anthropic destroyed millions of print books to build its AI ...</a></li>
<li><a href="https://ecommerceparadise.com/biblio-review-2026/">Biblio Review 2026: The Best Marketplace for Used and Rare Books ?</a></li>

</ul>
</details>

**Tags**: `#AI training`, `#copyright`, `#data sourcing`, `#investigative journalism`, `#Amazon`

---

<a id="item-2"></a>
## [Bricked Framework 13 Laptop Rescued with $20 Tools, Sparking Repairability Debate](https://quantum5.ca/2026/08/16/fixing-bricked-amd-7040-series-framework-13-laptop-with-20-tools/) ⭐️ 8.0/10

The author documents how they unbricked an AMD Ryzen 7040 Series Framework 13 laptop, which had become unusable after a BIOS update, using about $20 worth of tools. The repair relied on pogo pins and an external flash programmer to rewrite the BIOS chip directly. This repair story matters because it exposes a repairability gap even in a company famous for modular, user-repairable laptops. It shows that cheap DIY BIOS recovery is possible, but also that manufacturers could make it far easier by populating a standard flashing header, which feeds into the broader right-to-repair debate. Framework left the JSPI debug connector unpopulated for cost reasons, which forced the author to use pogo pins to make contact with the BIOS flash pads. The fix required opening the laptop, identifying the SPI flash chip, and rewriting its contents with a low-cost programmer rather than using a supported recovery path.

hackernews · jp_sc · Aug 18, 13:18 · [Discussion](https://news.ycombinator.com/item?id=49345220)

**Background**: A bricked device is one that has become completely non-functional, often after a failed firmware or BIOS update. Framework laptops are designed around modularity and repairability, with standard screws and labeled connectors, but BIOS recovery still typically requires a hardware programmer when the built-in bootloader is damaged. The AMD Ryzen 7040 Series Framework 13 has official BIOS downloads and update instructions, yet no simple user-facing external recovery header is populated on the board.

<details><summary>References</summary>
<ul>
<li><a href="https://frame.work/">Framework | Framework Computer | Modular Laptops & PCs You ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Brick_(electronics)">Brick (electronics) - Wikipedia</a></li>
<li><a href="https://resources.frame.work/downloads/laptop-13/amd-ryzen-7040-series/">Framework Laptop 13 AMD Ryzen™ 7040 Series — BIOS & Drivers | Resources</a></li>

</ul>
</details>

**Discussion**: Commenters were broadly sympathetic but split on blame. Some noted that Framework does have a JSPI debug connector designed for this, but it is left unpopulated to save cost, while others shared similar bricking experiences with other brands and called for legal accountability or warranty extensions after failed official updates. A few said the incident made them regret their Framework purchase.

**Tags**: `#hardware`, `#laptop-repair`, `#BIOS`, `#framework`, `#embedded`

---

<a id="item-3"></a>
## [Amazon's Hidden Convenience Tax](https://seths.blog/2026/08/the-amazon-tax/) ⭐️ 8.0/10

In his recent essay 'The Amazon Tax,' Seth Godin argues that Amazon's search results have degraded into ad-driven lists that nudge users toward purchases the platform favors, imposing a hidden cost on convenience. The piece has sparked wide discussion about the decline of search quality on Amazon. This matters because Amazon is a dominant gateway for online shopping, and its shift from precise search to ad-driven results affects consumer trust and purchasing decisions. It also reflects a broader industry trend where platform economics increasingly prioritize ad revenue over user experience. Amazon's Sponsored Products are cost-per-click ads that appear in search results, and some commenters report that up to three-quarters of results on certain queries are sponsored. This 'tax' is not monetary but takes the form of wasted time, reduced choice quality, and the psychological cost of navigating ad interference.

hackernews · herbertl · Aug 18, 13:22 · [Discussion](https://news.ycombinator.com/item?id=49345263)

**Background**: Amazon is one of the world's largest e-commerce platforms, and its internal search function is the primary way many users find products. Over time, Amazon has expanded its advertising business, integrating sponsored listings into search results, which can degrade the accuracy and neutrality of product discovery. 'Dark patterns' is a term used to describe interface designs that subtly steer users toward commercial goals rather than their own best interest. Understanding these concepts helps contextualize the criticism that Amazon's convenience now comes with a hidden cost.

<details><summary>References</summary>
<ul>
<li><a href="https://sell.amazon.com/advertising/sponsored-products">Sponsored Products | Sell on Amazon</a></li>
<li><a href="https://acowebs.com/dark-patterns-ecommerce/">Dark Patterns in eCommerce: How Some Brands Manipulate ...</a></li>

</ul>
</details>

**Discussion**: Commenters largely agree that Amazon's search quality has declined, with one noting that searching for a specific deal feels like navigating an 'advertisement minefield' where most results are sponsored. Some users say they have shifted purchases to local shops or alternatives like Etsy, and one user is contemplating deleting a 15-year-old Amazon account. A dissenting view argues this is simply how ads work everywhere, and the real value of Amazon lies in convenience, delivery, and returns rather than being cheap.

**Tags**: `#amazon`, `#e-commerce`, `#search`, `#platform-economics`, `#user-experience`

---

<a id="item-4"></a>
## [Cursor launches Origin, a GitHub alternative](https://cursor.com/changelog/origin-code-hosting) ⭐️ 8.0/10

Cursor (Anysphere) launched Origin, a git-hosting and code-review platform, on August 17, 2026. Origin is an early beta that adds native repos, GitHub sync, pull requests, and AI agents inside Cursor. As one of the most popular AI coding tools, Cursor moving into code hosting directly challenges GitHub and other platforms. This sparks important debates about centralization, ownership, and where developers should trust their code. Origin is centralized rather than decentralized, and one report says it launched by default for some users without an explicit opt-in. It includes native repos, GitHub sync, PRs, agents, and integrations, but has not published evidence of scale, reliability, or governance.

hackernews · tomasreimers · Aug 17, 17:02 · [Discussion](https://news.ycombinator.com/item?id=49334209)

**Background**: Cursor is an AI-powered code editor and agent developed by San Francisco-based Anysphere. GitHub is the dominant code-hosting platform, where developers store repositories, review code, and collaborate. Decentralized alternatives like Radicle and federated Forgejo aim to avoid single points of control, and services such as Sourcehut and Codeberg are also popular with developers seeking non-commercial hosting.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Cursor_(code_editor)">Cursor (code editor)</a></li>
<li><a href="https://servola.de/journal/cursor-origin-turned-itself-on-by-default/">Cursor's Origin Git Host Went Live Without an Opt-In</a></li>
<li><a href="https://kingy.ai/blog/cursor-origin-vs-github/">Cursor Origin vs GitHub: What Developers Need to Know</a></li>

</ul>
</details>

**Discussion**: Commenters expressed skepticism about another centralized alternative, urging investment in decentralized solutions like Radicle or federated Forgejo. Others worried about Cursor's ownership chain and data being used to train AI, while some recommended Sourcehut and Codeberg. One Origin developer offered to answer questions and defend the platform.

**Tags**: `#cursor`, `#github-alternative`, `#code-hosting`, `#ai-tools`, `#developer-tools`

---

<a id="item-5"></a>
## [Memory prices jump 500% in 12 months, 128GB DDR5 reaches $3,399](https://www.tomshardware.com/pc-components/ram/memory-prices-climb-500-percent-in-12-months-up-to-10x-the-lowest-ever-tracked-prices-128gb-of-ddr5-now-usd3-399) ⭐️ 8.0/10

Memory prices have surged about 500% over the past 12 months, with a 128GB DDR5 kit now costing over $3,399 — up to 10 times the lowest tracked prices. This dramatic increase is attributed to AI-driven demand and has sparked debate over whether manufacturers are also taking advantage of the situation. The 500% jump directly impacts PC builders, gamers, AI developers, and data centers, raising the cost of upgrading or building systems. It highlights how AI infrastructure demand is reshaping the memory market, potentially forcing users to seek cheaper alternatives or optimization techniques. The price spike applies broadly across DRAM and NAND, with other components like display panels also seeing cost increases. Notably, a community member has open-sourced 'glq', a quantization library using QTiP Trellis quantization to run LLMs at low bit widths (2-4 bits) with vLLM, as a response to high RAM prices.

hackernews · haunter · Aug 17, 17:52 · [Discussion](https://news.ycombinator.com/item?id=49334960)

**Background**: DDR5 SDRAM is the fifth generation of double data rate synchronous dynamic random-access memory, offering higher bandwidth and lower power consumption than DDR4. AI systems require high-speed memory like HBM to move large data volumes during training and inference, which has led memory makers to prioritize AI memory and tighten supply for conventional DRAM, driving up prices.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DDR5_SDRAM">DDR5 SDRAM - Wikipedia</a></li>
<li><a href="https://www.crucial.com/articles/about-memory/everything-about-ddr5-ram">DDR5 RAM: Everything You Need to Know</a></li>
<li><a href="https://techinsyte.com/ai-chip-demand-tightens-semiconductor-supply-as-memory-makers-prioritize-hbm/">AI Chip Demand Tightens Semiconductor Supply as Memory Makers...</a></li>

</ul>
</details>

**Discussion**: Community comments express frustration over the price surge, with one user questioning whether the increase is genuinely AI-driven or simply manufacturers taking advantage. Others highlight related price hikes in display panels and Blu-ray writers, and one developer shared an open-source quantization library (glq) to help users squeeze more performance from existing hardware.

**Tags**: `#memory`, `#hardware`, `#pricing`, `#AI demand`, `#industry trend`

---

<a id="item-6"></a>
## [Qwen 3.8 27B matches GPT-5.6 Luna on AI Intelligence Index](https://simonwillison.net/2026/Aug/17/qwen-38-27b-scores-52/) ⭐️ 8.0/10

Qwen 3.8 27B, Alibaba's Apache-2.0-licensed 27-billion-parameter vision-capable model, scored 52 on the Artificial Analysis Intelligence Index. That ties GPT-5.6 Luna (max) and trails GLM-5.2 (753B) and DeepSeek V4 Pro (1.7T) by just one point. A 27B model matching vastly larger systems highlights a major efficiency breakthrough in LLM scaling, since it can run on a reasonably specced laptop. This could make frontier-level intelligence more accessible locally and pressure much larger closed-weight models on cost and latency. The model is Apache 2.0 licensed, supports vision, defaults to the highest reasoning_effort ('xhigh'), and offers up to 262,144 tokens of context. A 17GB Q4_K_M quantized build exists for LM Studio, though the xhigh default can produce spectacular over-thinking and long generation times.

rss · Simon Willison · Aug 17, 23:58

**Background**: The Artificial Analysis Intelligence Index is a composite benchmark that measures capabilities across reasoning, coding, knowledge, instruction following, scientific reasoning, and multi-step tasks, incorporating evaluations such as Humanity's Last Exam, GPQA Diamond, and SciCode. Qwen is Alibaba's open-weight model family, and 27B is a size suited to local inference on high-end laptops. Qwen 3.8 27B's self-reported benchmarks also show gains over its predecessor Qwen 3.6 27B and the closed-weight Qwen 3.7-Plus.

<details><summary>References</summary>
<ul>
<li><a href="https://artificialanalysis.ai/evaluations/artificial-analysis-intelligence-index">Artificial Analysis Intelligence Index | Artificial Analysis</a></li>
<li><a href="https://huggingface.co/Qwen/Qwen3.8-27B">Qwen/Qwen3.8-27B · Hugging Face</a></li>
<li><a href="https://www.yottalabs.ai/post/how-to-run-qwen-3-8-27b-locally-ollama-gguf-single-gpu-2026">How to Run Qwen 3.8 27B Locally: Ollama, GGUF, and Single-GPU ...</a></li>

</ul>
</details>

**Tags**: `#qwen`, `#llms`, `#ai-efficiency`, `#benchmarks`, `#artificial-analysis`

---

<a id="item-7"></a>
## [Researcher Exposes Evaluation Tricks That Make Sparse Attention and KV Compression Look Good](https://www.reddit.com/r/MachineLearning/comments/1vqqqcs/how_to_make_any_sparse_attention_kv_compression/) ⭐️ 8.0/10

In a Reddit post (with an accompanying X thread), efficient-attention researcher Piotr Nawrot shared a candid list of common evaluation 'tricks' that make sparse attention and KV cache compression methods look far more effective than they really are. The post calls on the community to adopt more rigorous benchmarking practices instead of gaming the numbers. Evaluation methodology shapes how the entire ML community judges efficiency research, so widespread 'look-good' tricks can mislead the field about which compression or sparsity methods actually work. If researchers internalize these lessons, future papers will be harder to game and real efficiency gains will be easier to trust. The author lists four main pitfalls: (1) testing only on easy settings such as needle-in-a-haystack with a single out-of-distribution key-value pair, contaminated benchmarks, or useless few-shot examples; (2) failing to isolate contributions by keeping outdated hyperparameters for baselines while heavily tuning the new method, using an LLM-written Triton kernel only for the proposed method, and never sharing tuned prompts; (3) reporting only aggregate metrics to hide degradation on hard tasks like RULER's NIAH-MK3; and (4) evaluating on saturated tasks where all model sizes already score about the same.

reddit · r/MachineLearning · /u/korec1234 · Aug 17, 12:18

**Background**: Sparse attention and KV cache compression are efficiency techniques that fight the quadratic O(N²) cost of standard dense Transformer self-attention: sparse attention limits each query to attend to a subset of keys/values, while KV compression shrinks the cached key-value tensors that otherwise grow with sequence length and can exhaust GPU memory. Benchmarks such as Needle-in-a-Haystack and RULER are designed to stress long-context retrieval, but the post argues that many of their tasks are too easy — models can pass them without real sparsity or compression, which makes inflated claims easy to produce.

<details><summary>References</summary>
<ul>
<li><a href="https://grokipedia.com/page/Sparse_Attention">Sparse Attention</a></li>
<li><a href="https://research.nvidia.com/labs/eai/blogs/kv-cache-compression-and-its-infra-problems/">KV Cache Compression and Its Infra Problems | Efficient AI</a></li>
<li><a href="https://arize.com/blog/the-needle-in-a-haystack-test-evaluating-the-performance-of-llm-rag-systems/">The Needle In a Haystack Test: Evaluating the... - Arize AI</a></li>

</ul>
</details>

**Tags**: `#sparse attention`, `#KV cache compression`, `#evaluation methodology`, `#ML research`, `#efficiency`

---

<a id="item-8"></a>
## [Train-mounted line-scan camera turns railways into a flatbed scanner](https://philo.gay/linecam/) ⭐️ 7.0/10

A creative project by philo.gay uses a line-scan camera mounted on a train to capture continuous images of the railway corridor, effectively turning the entire rail network into a giant flatbed scanner. The approach relies on the train's forward motion to supply the second scanning dimension, producing distorted, panoramic-like strips of the landscape. This project offers a fresh, artistic perspective on sensor systems and imaging, showing how motion that is usually ignored can be harnessed for creative expression. It also resonates with a broader technical history, from satellite push-broom scanners to everyday flatbed scanners, and may inspire others to experiment with unconventional camera setups. A line-scan camera captures only a single row of pixels at a time, relying on relative motion between the camera and the subject to build a full two-dimensional image. This is conceptually similar to push-broom scanning used in remote sensing; community members also pointed out that the same effect can be simulated with a regular camera by manually splicing narrow vertical slices of frames.

hackernews · otherayden · Aug 18, 12:43 · [Discussion](https://news.ycombinator.com/item?id=49344825)

**Background**: A line-scan camera produces two-dimensional images using a single sensor element or a one-dimensional stripe of sensors, capturing one line at a time as the camera or object moves. This technique has historical roots in drum scanners, aerial reconnaissance, and satellite push-broom imagers such as those on Mars Express and the Lunar Reconnaissance Orbiter. In a flatbed scanner, the sensor line moves over a stationary document; in this train project, the sensor is stationary relative to the train while the landscape moves past, achieving the same line-by-line scanning effect.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Line-scan_camera">Line-scan camera</a></li>
<li><a href="https://en.wikipedia.org/wiki/Push_broom_scanner">Push broom scanner</a></li>

</ul>
</details>

**Discussion**: Commenters shared related past experiments and technical extensions: one described a 2008 setup with an iSight camera overlooking railroad tracks, another made animations by manually splicing frames from a regular camera, and one suggested attaching a mirror to measure train speed via railroad ties. Others linked to interactive slit-scan tools, and the overall sentiment was enthusiastic, with many calling the project inspiring and fun to try.

**Tags**: `#imaging`, `#creative-coding`, `#hardware`, `#railway`, `#photography`

---

<a id="item-9"></a>
## [Linux 7.3 Improves Performance When GPU VRAM Runs Out](https://pixelcluster.dev/VRAM-Overcommit/) ⭐️ 7.0/10

Linux 7.3 introduces kernel-level improvements to handle out-of-VRAM scenarios, reducing performance drops when GPU memory is overcommitted. The update refines memory reclaim and overcommit strategies for GPU-heavy workloads. This matters for AI training, 3D rendering, and gaming, where workloads frequently exceed available VRAM. Better kernel handling means fewer freezes, improved responsiveness, and a more competitive Linux experience for GPU users. The improvements target the kernel's interaction with GPU drivers, which decide how much overcommitted memory actually fits. The patchwork builds on existing overcommit support and memory-reclaim mechanisms, rather than introducing a new memory model.

hackernews · flaburgan · Aug 18, 07:51 · [Discussion](https://news.ycombinator.com/item?id=49342719)

**Background**: VRAM overcommit allows applications to request more GPU memory than physically exists; the driver then decides what fits in on-board memory, with the rest spilling to system RAM or being reclaimed. When overcommit is heavy, performance degrades because the kernel must constantly evict and reload data. Linux also supports using VRAM itself as swap space, and memory reclamation policies determine how the system behaves under memory pressure. Different operating systems handle out-of-memory conditions differently, which is a frequent topic of comparison among users.

<details><summary>References</summary>
<ul>
<li><a href="https://pixelcluster.dev/VRAM-Overcommit/">VRAM Management Part 2: Beyond the Limits of Physical VRAM | pixelcluster's GPU blog</a></li>
<li><a href="https://developer.nvidia.com/blog/improving-gpu-memory-oversubscription-performance/">Improving GPU Memory Oversubscription Performance | NVIDIA Technical Blog</a></li>
<li><a href="https://wiki.archlinux.org/title/Swap_on_video_RAM">Swap on video RAM - ArchWiki</a></li>

</ul>
</details>

**Discussion**: Commenters praised the article and the Linux kernel's rapid improvement pace, with one expressing excitement for 7.3 after 7.2's performance work. Discussion also covered OOM behavior across operating systems: a macOS M4 Max user described glitching when overloading VRAM, while another hoped Linux would stop freezing when RAM fills. A technical comment argued that applications, not the kernel, are best positioned to inform memory stickiness to VRAM.

**Tags**: `#Linux`, `#kernel`, `#VRAM`, `#performance`, `#memory management`

---

<a id="item-10"></a>
## [Polars Cheatsheet Distills 500-Page O'Reilly Book into Two Pages](https://opensource.posit.co/resources/cheatsheets/polars/) ⭐️ 7.0/10

Jeroen Janssens and co-authors compressed their book 'Python Polars: The Definitive Guide' (nearly 500 pages) into a two-page cheatsheet, now available on Posit's open-source resources site as both PDF and an accessible HTML version. The release has sparked community discussion comparing Polars with Pandas, R, and DuckDB. This cheatsheet lowers the barrier to adopting Polars, a high-performance DataFrame library, making it easier for data practitioners to explore its capabilities. The surrounding discussion underscores the shifting landscape of data analysis tools, with Polars positioning itself against established options like Pandas, R's tidyverse, and DuckDB. The cheatsheet is described as a 'highly lossy compression' of the book but aims to cover users' favorite Polars operations, with feedback invited on missing features and organization. It is hosted on Posit's site, reflecting the growing community around Polars and its ecosystem.

hackernews · jeroenjanssens · Aug 18, 13:38 · [Discussion](https://news.ycombinator.com/item?id=49345476)

**Background**: Polars is a high-performance DataFrame library for Python and Rust, built on Apache Arrow, designed to utilize all CPU cores and handle datasets larger than available RAM. It differs from the more established Pandas by offering a lazy execution API and query optimization. DuckDB is an in-process SQL OLAP database that also serves analytical workloads, often competing with Polars in speed and ergonomics. The O'Reilly book 'Python Polars: The Definitive Guide' provides comprehensive documentation for the library.

<details><summary>References</summary>
<ul>
<li><a href="https://pola.rs/">Polars — DataFrames for the new era</a></li>
<li><a href="https://docs.pola.rs/">Blazingly Fast DataFrame Library</a></li>
<li><a href="https://duckdb.org/">DuckDB – An in-process SQL OLAP database management system</a></li>

</ul>
</details>

**Discussion**: Overall sentiment is positive, with users expressing interest in trying Polars based on the cheatsheet, especially those frustrated by Pandas. Some commenters prefer R's tidyverse or data.table, while another mentions switching from Python/Polars/Pandas to DuckDB. The authors invited feedback on missing operations and organization, and users offered such suggestions.

**Tags**: `#polars`, `#python`, `#data-analysis`, `#cheatsheet`, `#dataframe`

---

<a id="item-11"></a>
## [Open-Source World Model Generates Hour-Long Videos Without Drift](https://mp.weixin.qq.com/s?__biz=MzIzNjc1NzUzMw==&mid=2247913001&idx=3&sn=0ffd266a88f762bb4366ada6614a51e5) ⭐️ 7.0/10

The article reports that a newly open-sourced world model can generate hour-long videos with consistent content, using an efficient diffusion process with three denoising steps and zero classifier-free guidance (CFG). It generates a 1.5-second clip in just 2.11 seconds. Long-duration video generation without drift is a major challenge in AI; this breakthrough shows that efficient diffusion steps can achieve temporal consistency. It could accelerate research and applications in world models, video generation, and even autonomous systems. The model reportedly uses three denoising steps and eliminates CFG, which typically requires extra computation, achieving a 2.11-second latency for a 1.5-second video clip. The news item lacks specific model names or architecture details, so independent verification is pending.

rss · 量子位 · Aug 17, 10:00

**Background**: World models are AI systems that learn to simulate the environment and predict future states, inspired by how humans build mental models. Diffusion models generate data by gradually denoising from random noise, and classifier-free guidance (CFG) is a technique to improve condition adherence by blending conditional and unconditional predictions. The reported approach reduces the diffusion process to a few steps and removes CFG, making it fast enough for long video generation.

<details><summary>References</summary>
<ul>
<li><a href="https://m.aitntnews.com/newDetail.html?newId=15507">全在这里了，小白也可以一文读懂的“ 世 界 模 型 ”</a></li>
<li><a href="https://zhuanlan.zhihu.com/p/624221952">超详细的扩散模型（Diffusion Models）原理+代码 - 知乎</a></li>
<li><a href="https://zhuanlan.zhihu.com/p/2029371904776054149">从 Classifier Guidance 到 Classifier-Free Guidance：一文讲清 ...</a></li>

</ul>
</details>

**Tags**: `#world model`, `#video generation`, `#open source`, `#AI research`, `#diffusion`

---

<a id="item-12"></a>
## [AI Labs Dismantle Ethics Oversight, Leaving Accountability Gaps](https://aiweekly.co/issues/ai-ethics-is-nobodys-job-now-the-labs-prefer-it-that-way) ⭐️ 7.0/10

This issue reports that four frontier AI labs have removed the people and structures responsible for ethics oversight, effectively eliminating internal accountability for AI ethics. A departing researcher's comment is highlighted as an explanation for why good intentions were not enough. This trend signals a systemic retreat from AI ethics commitments at the most powerful AI companies, at a time when regulators and the public are demanding greater accountability. It could widen the gap between AI capabilities and the safeguards needed to govern them. The newsletter does not name the four labs or the departing researcher, but frames the removals as deliberate rather than accidental. It suggests the labs prefer this outcome, leaving no internal body to challenge development decisions.

rss · AI Weekly · Aug 17, 00:00

**Background**: Frontier AI labs are the leading organizations developing advanced artificial intelligence models. Ethics oversight structures were often established as voluntary commitments to address concerns about bias, misuse, and societal harm, but they typically had no binding authority over product decisions, making them easy to dismantle when priorities shifted.

**Tags**: `#AI ethics`, `#AI governance`, `#AI safety`, `#accountability`, `#frontier labs`

---

<a id="item-13"></a>
## [Hobbyist Trains Diffusion Model on 264KB SRAM Microcontroller](https://www.reddit.com/r/MachineLearning/comments/1vrk7t5/trained_an_diffusion_model_that_runs_on_264kb_of/) ⭐️ 7.0/10

A hobbyist trained a 32x32 pixel diffusion model that runs on a Shrike lite microcontroller with only 264KB of SRAM, and used the onboard FPGA to build two parallel INT8 MAC engines. The FPGA accelerator made generation slower (about 220 seconds per image) than the MCU-only version (about 70 seconds per image). This demonstrates that diffusion-based image generation is technically possible on extreme edge hardware with minimal memory, opening up explorations into on-device generative AI for microcontrollers. It also provides a real-world data point on the memory-bandwidth bottleneck of FPGA acceleration for tiny models, which is relevant for edge AI practitioners. The model outputs 32x32 pixel images and is heavily quantized due to memory constraints, producing noisy and weird results with occasional cool images. The FPGA implementation used two parallel INT8 MAC engines with 16-bit accumulation, but the system hit a memory wall from excessive I/O operations.

reddit · r/MachineLearning · /u/PandaBean18 · Aug 18, 09:26

**Background**: The Shrike lite is a low-cost, open-source development board combining an RP2040 microcontroller and a 1120-LUT FPGA. Quantization converts neural network weights from 32-bit floats to smaller formats such as 8-bit integers, which reduces memory and compute requirements and is common in TinyML. INT8 matrix engines are deep-pipelined arrays of multiply-accumulate units designed for high-throughput matrix multiplication on FPGAs.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/vicharak-in/shrike-lite">GitHub - vicharak-in/ shrike - lite : Low cost microcontroller + FPGA...</a></li>
<li><a href="https://www.emergentmind.com/topics/int8-matrix-engines">INT8 Matrix Engines</a></li>
<li><a href="https://leimao.github.io/article/Neural-Networks-Quantization/">Quantization for Neural Networks - Lei Mao's Log Book</a></li>

</ul>
</details>

**Tags**: `#edge-ai`, `#diffusion-models`, `#microcontrollers`, `#quantization`, `#fpga`

---

<a id="item-14"></a>
## [Unitree Robotics Launches STAR Market IPO Inquiry, Targets 400B Yuan Valuation](https://t.me/zaihuapd/43244) ⭐️ 7.0/10

On August 5, 2026, Unitree Robotics began the preliminary inquiry phase for its STAR Market IPO, running from 9:30 to 15:00. The company plans to raise 4.202 billion yuan by issuing 40.4464 million new shares, with an estimated issue price of about 104 yuan per share and a market valuation exceeding 40 billion yuan. This IPO marks a significant financial milestone for a leading robotics company, signaling strong market validation for the humanoid and quadruped robot sector. It could provide Unitree with substantial capital to scale production and R&D, influencing the broader robotics and AI investment landscape in China. The new shares account for 10% of post-issuance total shares. Online and offline subscription begins on August 10, with payment deadline on August 12. According to the prospectus, Unitree's 2025 revenue was 1.699 billion yuan with net profit of 278 million yuan, and it expects 2026 H1 revenue of 1.052 to 1.128 billion yuan.

telegram · zaihuapd · Aug 17, 13:20

**Background**: Unitree Robotics is a Chinese robotics company known for its quadruped and humanoid robots, such as the Go2 and H1. The STAR Market (科创板) is Shanghai's sci-tech innovation board, designed for high-growth technology companies, with a registration-based IPO process that includes an inquiry phase to determine the issue price. This phase allows institutional investors to bid and helps set the final offering price before subscription.

**Tags**: `#IPO`, `#robotics`, `#Unitree`, `#STAR Market`, `#investment`

---

<a id="item-15"></a>
## [WeChat Work 5.0.10 Opens CLI and MCP to AI Agents](https://mp.weixin.qq.com/s/uJf57P15-FQL_u6jLHiGYA) ⭐️ 7.0/10

WeChat Work 5.0.10 opens its CLI and Model Context Protocol (MCP) interfaces to all enterprises, enabling WorkBuddy, DeepSeek Harness, and custom enterprise agents to directly access 10 core office modules. It also introduces permission isolation between humans and AI, human approval for critical operations, time-limited authorization, and complete audit logging. This update makes enterprise office tools natively interoperable with mainstream AI agents through the open MCP standard, lowering the cost of building AI-powered workflows. It sets a precedent for how enterprise communication platforms can safely expose business operations to autonomous agents. The 10 modules include reading documents and spreadsheets, analyzing data, generating proposal PPTs, and creating business dashboards. Access controls feature human-in-the-loop approval, time-limited grants, and full audit trails, addressing governance and compliance concerns.

telegram · zaihuapd · Aug 18, 06:22

**Background**: The Model Context Protocol (MCP) is an open standard introduced by Anthropic in November 2024 for connecting AI systems to external tools and data sources. DeepSeek Harness is DeepSeek AI's open-source, plugin-based framework for building LLM agents, while WorkBuddy is Tencent's AI-native desktop agent workstation. WeChat Work's support for both third-party agents and enterprise-custom agents via CLI and MCP aligns with the industry trend toward making enterprise software agent-ready.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Model_Context_Protocol">Model Context Protocol - Wikipedia</a></li>
<li><a href="https://deepwiki.com/deepseek-ai/deepseek-harness">deepseek-ai/deepseek-harness | DeepWiki</a></li>
<li><a href="https://www.accio.com/blog/workbuddy-wechat-integration-transforms-remote-work-with-ai-control">WorkBuddy WeChat Integration Transforms Remote Work With AI Control</a></li>

</ul>
</details>

**Tags**: `#MCP`, `#CLI`, `#AI Agents`, `#Enterprise Software`, `#WeChat Work`

---

<a id="item-16"></a>
## [China Domestic AI Chips to Claim 90% of Market by 2026, Cambricon and Huawei Lead](https://www.tomshardware.com/tech-industry/artificial-intelligence/chinas-homegrown-ai-accelerators-to-supply-90-percent-of-the-countrys-domestic-market-analysts-suggest-cambricon-and-huawei-expected-to-be-the-biggest-winners-in-the-shift-away-from-nvidia-and-amd) ⭐️ 7.0/10

TrendForce forecasts that Chinese domestic AI accelerators will supply nearly 90% of China's domestic market by 2026, up from 45% last year. Cambricon and Huawei are expected to be the primary beneficiaries of this shift away from Nvidia and AMD. This marks a major shift in the global AI hardware supply chain, as China reduces dependence on US-based chip makers amid export controls. It could reshape the competitive landscape, with domestic players gaining scale and Western vendors losing a massive market. In 2025, Nvidia held 55% of the Chinese market with 2.2 million units shipped, while Huawei shipped 812,000 units for a 20.3% share. TrendForce notes China must multiply high-end AI chip production by 2.2 times to roughly 1.96 million units within a year, raising doubts about whether capacity can keep up.

telegram · zaihuapd · Aug 18, 13:03

**Background**: TrendForce is a leading global market research firm founded in 2000 that provides analysis across technology sectors. Cambricon is a Chinese AI chip company known for its MLU series, including the 7nm Siyuan 370 chip using chiplet technology, which offers up to 256 TOPS INT8 performance. The push for domestic AI chips is driven by US export controls that restrict Nvidia and AMD from selling high-end accelerators to China, prompting Beijing to support local champions.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cambricon.com/">Cambricon - 寒武纪</a></li>
<li><a href="https://aiqicha.baidu.com/details/ugknowledge?id=229ec801966926bbf788dc82b5624443">trendforce 是 什 么 公司 | 爱企查</a></li>
<li><a href="https://zhuanlan.zhihu.com/p/1962109536287593043">从DianNao架构到Cambricon系列 | 10篇论文解析寒武纪AI芯片“硬核”路线</a></li>

</ul>
</details>

**Tags**: `#AI chips`, `#China`, `#semiconductor`, `#Huawei`, `#market analysis`

---

<a id="item-17"></a>
## [Sugar Rationing in Early Life Linked to Lower Adult Cancer Risk](https://theconversation.com/babies-born-under-sugar-rationing-grew-into-adults-with-lower-cancer-risk-289873) ⭐️ 6.0/10

A new epidemiological study reports that individuals who experienced sugar rationing in the womb or as infants grew up to have lower rates of certain adult cancers. The study draws on the natural experiment provided by the UK's sugar rationing during and after World War II. These findings lend support to the developmental origins of health and disease (DOHaD) hypothesis, which holds that prenatal and early-life conditions shape long-term health outcomes. The study could influence public health guidance on nutrition during pregnancy and infancy, though causal interpretation remains debated. The analysis is observational and therefore susceptible to confounding cohort effects, as commenters noted that other wartime shortages—such as alcohol and tobacco—eased around the same time. The article also suggests that early sugar exposure may influence lifelong sugar craving, but it is unclear whether the authors fully corrected for this behavioral pathway.

hackernews · zeristor · Aug 18, 14:06 · [Discussion](https://news.ycombinator.com/item?id=49345843)

**Background**: In the UK, sugar was rationed during and after World War II, with restrictions finally ending in 1953. The developmental origins of health and disease (DOHaD) hypothesis, first articulated by David Barker, proposes that prenatal and early-life environmental factors can influence lifelong health, including chronic disease risk. Studies like this one use natural experiments but must contend with confounding, where other factors that changed simultaneously may explain the observed association.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Confounding">Confounding - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Developmental_origins_of_health_and_disease">Developmental origins of health and disease - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters raised concerns about confounding cohort effects, pointing out that other shortages such as alcohol and tobacco ended around the same time. One asked whether the authors adjusted for later sugar craving, while another doubted that sugar itself, rather than correlated lifestyle factors, drove the effect. Overall, the discussion conveyed interest tempered by scientific skepticism.

**Tags**: `#health`, `#nutrition`, `#epidemiology`, `#cancer`, `#science`

---

<a id="item-18"></a>
## [Markdown SVG Renderer Adds Browser-Based MP4 Export for Animated SVGs](https://simonwillison.net/2026/Aug/16/markdown-svg-upgrades/) ⭐️ 6.0/10

Simon Willison has significantly upgraded his markdown-svg-renderer tool, most notably adding an MP4 tab that converts animated SVGs into MP4 video entirely in the browser using ffmpeg.wasm. SVG blocks in Markdown are now rendered as interactive tabbed panels with Rendered, PNG, JPEG, MP4, and Code views. This closes a real sharing gap: SVG and animated SVG are not supported by many platforms, so converting them to PNG, JPEG, or MP4 in the browser makes content far easier to distribute. It also highlights how WebAssembly is enabling heavyweight tools like FFmpeg to run entirely client-side with no server uploads. The MP4 tab (added today, commit 73e0327f6df9887ba2a9f9f16a2d06a45451d248) inspects the SVG for animations, guesses the loop duration, renders a series of animation frames, then loads over 30MB of ffmpeg.wasm to compile them into an MP4. The tool can load Markdown by pasting text, from a CORS-friendly raw URL, or from a GitHub Gist, and generates bookmarkable hash-based URLs.

rss · Simon Willison · Aug 16, 23:59

**Background**: Markdown is a lightweight markup language for formatting plain text, widely used in documentation and note-taking. SVG (Scalable Vector Graphics) is a vector image format that can include animations, but many social platforms and messaging apps do not render it. CORS (Cross-Origin Resource Sharing) is a browser mechanism that lets web pages request resources from other domains; the tool relies on CORS-friendly URLs to fetch remote Markdown documents. ffmpeg.wasm is a WebAssembly build of the FFmpeg multimedia framework, enabling video processing to run entirely in the browser.

<details><summary>References</summary>
<ul>
<li><a href="https://tools.simonwillison.net/markdown-svg-renderer">tools.simonwillison.net/ markdown - svg - renderer</a></li>
<li><a href="https://github.com/simonw/tools/blob/main/markdown-svg-renderer.html">tools/ markdown - svg - renderer .html at main · simonw/tools · GitHub</a></li>
<li><a href="https://en.wikipedia.org/wiki/CORS">CORS</a></li>

</ul>
</details>

**Tags**: `#Markdown`, `#SVG`, `#Developer Tools`, `#Web Development`

---

<a id="item-19"></a>
## [SineKAN: Kolmogorov-Arnold Networks with Sinusoidal Activations](https://www.reddit.com/r/MachineLearning/comments/1vqdode/r_sinekan_kolmogorovarnold_networks_using/) ⭐️ 6.0/10

A Reddit user shared the SineKAN paper, which proposes using sinusoidal activation functions in Kolmogorov-Arnold Networks instead of the standard B-splines. The paper is available on arXiv, with code on GitHub and a peer-reviewed version published in MDPI Mathematics. This matters because it explores a simple yet fundamental design choice—activation function type—in Kolmogorov-Arnold Networks, a promising alternative to MLPs. It could help researchers understand which activations yield better accuracy, convergence, or interpretability in KANs, though it is an incremental contribution. The paper (arXiv:2407.04149) introduces SineKAN and shows that sinusoidal activations can be used as a drop-in replacement for B-splines. The MDPI publication (Mathematics 13(19):3157) appears to be a peer-reviewed version, and the GitHub repository provides implementation code.

reddit · r/MachineLearning · /u/jacobgorm · Aug 17, 00:46

**Background**: Kolmogorov-Arnold Networks (KANs) are a neural network architecture based on the Kolmogorov-Arnold representation theorem, which states that any multivariate continuous function can be represented as a finite composition of continuous univariate functions. Unlike traditional MLPs that use fixed activation functions on nodes, KANs use learnable activation functions on edges. B-splines are commonly used as these learnable activations due to their smoothness and local support. SineKAN replaces B-splines with sinusoids, which are simpler and periodic, potentially offering different inductive biases.

<details><summary>References</summary>
<ul>
<li><a href="https://www.datacamp.com/tutorial/kolmogorov-arnold-networks">Kolmogorov - Arnold Networks (KANs): A Guide With... | DataCamp</a></li>
<li><a href="https://www.educative.io/blog/kolmogorov-arnold-network">Making sense of Kolmogorov - Arnold Networks (KANs)</a></li>
<li><a href="https://en.wikipedia.org/wiki/B-spline">B-spline - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#KAN`, `#Neural Networks`, `#Activation Functions`, `#Machine Learning`, `#Research`

---

<a id="item-20"></a>
## [Italy Fines Apple €115 Million for Abusing App Store Dominance Over ATT Policy](https://t.me/zaihuapd/43243) ⭐️ 6.0/10

Italy's competition authority AGCM fined Apple €115 million for abusing its dominant position in the App Store by unilaterally imposing App Tracking Transparency (ATT) requirements on third-party developers while exempting Apple's own apps. Apple said it strongly disagrees with the decision. This ruling challenges the privacy-vs-competition balance of Apple's ATT framework and could set a precedent for other antitrust actions in Europe. It affects app developers, advertisers, and platform regulation, as regulators scrutinize how privacy policies can also entrench a platform's market power. AGCM claimed that ATT terms were imposed unilaterally and disproportionately to Apple's stated privacy goals, harming business partners. Apple rejected the decision, arguing regulators ignored the privacy protections ATT provides to users. The fine amount is reportedly around €115 million (about $115 million).

telegram · zaihuapd · Aug 17, 12:50

**Background**: App Tracking Transparency is Apple's privacy framework introduced in iOS 14.5 that requires apps to ask users for permission before tracking them across apps or websites for advertising purposes. Before ATT, developers could access device identifiers like IDFA by default to measure ad campaigns. The Italian regulator's action is part of a broader European scrutiny of large tech platforms' app store practices, with the EU also investigating similar issues under the Digital Markets Act.

<details><summary>References</summary>
<ul>
<li><a href="https://developer.apple.com/documentation/apptrackingtransparency">App Tracking Transparency | Apple Developer Documentation</a></li>
<li><a href="https://developer.apple.com/app-store/user-privacy-and-data-use/">User Privacy and Data Use - App Store - Apple Developer</a></li>
<li><a href="https://www.adjust.com/glossary/app-tracking-transparency/">What is App Tracking Transparency (ATT)? | Adjust</a></li>

</ul>
</details>

**Tags**: `#Apple`, `#Antitrust`, `#App Store`, `#Privacy`, `#Regulation`

---

<a id="item-21"></a>
## [iOS 27 Beta 5 Shows Apple Intelligence's China Privacy Plan](https://t.me/zaihuapd/43248) ⭐️ 6.0/10

iOS 27 beta 5 includes hidden text about Apple Intelligence's China version, stating all user requests will be processed on-device to comply with Chinese regulations while protecting privacy. This indicates Apple Intelligence is entering the adaptation phase for the Chinese market, a key step for Apple to offer AI features in China. The approach may set a precedent for how global AI services localize for regulatory compliance. Apple states it will not send user requests to Apple or the security mechanism provider; instead, anonymous safety results may be collected and shared in aggregated form. The security mechanism will also receive automatic updates.

telegram · zaihuapd · Aug 18, 02:16

**Background**: Apple Intelligence is Apple's personal intelligence system announced in June 2024, using on-device processing and private cloud computing. In China, AI services are subject to local regulations, requiring companies to use approved security mechanisms. This beta text suggests Apple is preparing a localized version that keeps processing on-device to meet these requirements.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Apple_Intelligence">Apple Intelligence - Wikipedia</a></li>
<li><a href="https://www.apple.com/apple-intelligence/">Apple Intelligence and Siri - Apple</a></li>
<li><a href="https://developer.apple.com/apple-intelligence/">Apple Intelligence - Apple Developer</a></li>

</ul>
</details>

**Tags**: `#Apple`, `#iOS`, `#AI`, `#Privacy`, `#China`

---

<a id="item-22"></a>
## [China Orders Some Agencies to Uninstall Custom Windows 10, Ahead of Plan](https://www.bloomberg.com/news/articles/2026-08-18/china-axing-microsoft-windows-from-state-agencies-ahead-of-plan) ⭐️ 6.0/10

China's Ministry of State Security has instructed some government-affiliated agencies to uninstall the customized Windows 10 government edition months before the planned February 2027 end-of-use date. The directive is based on data security concerns, though no specific vulnerability has been identified. This accelerates China's shift away from Microsoft's operating systems in the public sector and signals growing concern over data security. It could affect Microsoft's government business and reinforces momentum for domestic OS alternatives like UOS and Kylin within China's broader tech self-reliance campaign. The affected product is the custom Windows 10 Enterprise G 'Shenzhou Wangxin Government Edition' (CMGE), co-developed by Microsoft and CETC's joint venture Shenzhou Wangxin. Microsoft says it has found no security incidents involving the product and that it continues to receive regular security updates.

telegram · zaihuapd · Aug 18, 06:22

**Background**: In 2017, Microsoft and CETC (China Electronics Technology Corporation) set up joint venture Shenzhou Wangxin to build a special Windows 10 for Chinese government and state-owned enterprises. That version removed consumer features, enabled local activation, patching, and updates, and met a requirement that government data not leave China. The original plan was to retire the edition by February 2027, in line with Windows 10 end-of-support timelines. The new directive moves that cutover earlier, echoing China's broader push for homegrown operating systems.

<details><summary>References</summary>
<ul>
<li><a href="https://news.mydrivers.com/1/533/533778.htm">中国定制政府版Windows 10是这样：数据不出境</a></li>
<li><a href="https://cn.technode.com/post/2017-05-23/zhengfuban-windows-10/">中国政府版 Windows 10发布，目前已经开始试点测试 - 动点科技</a></li>
<li><a href="https://www.laoliang.net/soft/21171.html">Windows 10 企业版 G 神州网信政府版(神州网信Win10 EnterpriseG X64 X22H2 19045.4291)</a></li>

</ul>
</details>

**Tags**: `#Microsoft`, `#Windows 10`, `#China`, `#government policy`, `#data security`

---

<a id="item-23"></a>
## [Baidu Netdisk Accused of Filing Income Tax for Users Without Consent](https://tech.sina.cn/2026-08-18/detail-inintpiw0093456.d.html) ⭐️ 6.0/10

Multiple users reported that Baidu Netdisk's operating entity, Beijing Duyou Technology Co., Ltd., filed 89.10 yuan income records with zero tax on their behalf in China's Personal Income Tax APP without their knowledge. Baidu Netdisk confirmed the filings stemmed from a 'share to get Air China Traveler membership' promotion and offered to help cancel the records. The incident touches on sensitive issues of data privacy, consent, and legal compliance in China's digital economy, showing how promotional activities can inadvertently create financial records for users. It may push regulators and tech companies to clarify rules around tax declaration for prizes and require clearer user consent before filing tax information on users' behalf. The reported 89.10 yuan exactly matched the price of the Air China Traveler (航旅纵横) membership given away in the promotional campaign, and the declared tax was 0 yuan, as the small amount did not trigger any tax under current rules. Baidu said it only submitted the minimum necessary information to tax authorities and offered affected users either help with record cancellation or a free one-month membership.

telegram · zaihuapd · Aug 18, 10:07

**Background**: In China, companies that give prizes or benefits to individuals are generally required to declare such income to tax authorities through the official Personal Income Tax APP, even when no tax is actually owed. These declarations become part of a user's tax file and can surface during the annual comprehensive income reconciliation, which is why unexpected records alarmed users. Baidu Netdisk operates in China under Beijing Duyou Technology Co., Ltd., and the uproar reflects broader public sensitivity in China about how tech platforms collect and use personal data without explicit consent.

**Tags**: `#privacy`, `#baidu`, `#data-handling`, `#legal-compliance`, `#tech-news`

---

<a id="item-24"></a>
## [OpenAI and CodeAI Partner to Expand Responsible AI Education for Teens](https://openai.com/index/chatgpt-for-teens/) ⭐️ 6.0/10

On August 18, 2026, OpenAI announced a partnership with CodeAI to help students and teachers learn to use AI responsibly, reaching millions of students. The announcement coincided with the launch of ChatGPT for Teens, a version of the chatbot with stronger built-in protections and parental controls. This partnership signals a significant push to integrate AI literacy into K-12 education, potentially setting a precedent for how AI companies engage with young users. It also highlights OpenAI's efforts to address safety concerns around teen use of AI at a time when the company faces a series of lawsuits. The initiative includes a joint advisory committee, AI literacy curriculum, student challenges, and career programs over the next year. OpenAI will also support CodeAI in developing a free high-school AI Foundations course.

telegram · zaihuapd · Aug 18, 12:06

**Background**: CodeAI is the rebranded name of Code.org, a nonprofit whose mission is digital fluency for every student, offering K-12 curriculum and teacher training in 190 countries. ChatGPT for Teens is a new experience designed for learning, with stronger protections, healthy-use features, and additional controls for parents. The partnership comes amid growing public debate and litigation over AI use by minors, making youth-focused safety features and education a key priority for AI companies.

<details><summary>References</summary>
<ul>
<li><a href="https://openai.com/index/chatgpt-for-teens/">Introducing ChatGPT for Teens: Built for learning, backed by ...</a></li>
<li><a href="https://code.org/en-US/codeai">Code.org is now CodeAI</a></li>
<li><a href="https://www.cnn.com/2026/08/18/tech/openai-chatgpt-for-teens">OpenAI introduces ‘ChatGPT for Teens’ experience amid ...</a></li>

</ul>
</details>

**Tags**: `#AI education`, `#OpenAI`, `#partnership`, `#ChatGPT`, `#youth`

---