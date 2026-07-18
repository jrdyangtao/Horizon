---
layout: default
title: "Horizon Summary: 2026-07-18 (ZH)"
date: 2026-07-18
lang: zh
---

> 从 65 条内容中筛选出 25 条重要资讯。

---

1. [LG 显示器通过 Windows Update 静默安装软件](#item-1) ⭐️ 9.0/10
2. [Firefox 被编译为 WebAssembly 在另一个浏览器中运行](#item-2) ⭐️ 9.0/10
3. [Meta 拟向 Anthropic 出租百亿美元 AI 算力](#item-3) ⭐️ 9.0/10
4. [特朗普政府拟设类似 FINRA 的 AI 审查机构](#item-4) ⭐️ 9.0/10
5. [GPT-5.6 解决凸优化领域 30 年悬而未决的问题](#item-5) ⭐️ 8.0/10
6. [StackOverflow 衰落之争：AI 还是社区政策](#item-6) ⭐️ 8.0/10
7. [Kimi K3 以 2.8 万亿参数打破纪录](#item-7) ⭐️ 8.0/10
8. [上海 AI Lab 让 Harness 自进化，性能提升 104%不换模型](#item-8) ⭐️ 8.0/10
9. [无意义的 AI 输出竟赢得 DeepMind/Kaggle 2.5 万美元大奖？](#item-9) ⭐️ 8.0/10
10. [Stereo2Spatial：用扩散模型将立体声转为双耳空间音频](#item-10) ⭐️ 8.0/10
11. [Prism 漏洞导致未发表论文泄露](#item-11) ⭐️ 8.0/10
12. [EU AI Act OpenRAG：933 个法律结构化块与 BGE-M3 嵌入](#item-12) ⭐️ 8.0/10
13. [SpaceX 与五角大楼谈判数十亿美元 AI 算力交易](#item-13) ⭐️ 8.0/10
14. [OpenRouter 传被收购，估值超 13 亿美元](#item-14) ⭐️ 8.0/10
15. [台积电宣布 A14 制程将于 2028 年投产](#item-15) ⭐️ 8.0/10
16. [旧金山责令苹果谷歌下架‘脱衣’应用](#item-16) ⭐️ 8.0/10
17. [反着来的 JPEG：通过渐进式 JPEG 加载实现视频动画](#item-17) ⭐️ 7.0/10
18. [Claude Fable 5 在订阅计划中永久保留](#item-18) ⭐️ 7.0/10
19. [DABSN：新型循环语言模型寻求合作者](#item-19) ⭐️ 7.0/10
20. [豆包手机放弃 GUI 操作，要求超级应用提供 MCP](#item-20) ⭐️ 7.0/10
21. [SK 海力士 CEO 预警 2027 年将现史上最严重内存短缺](#item-21) ⭐️ 7.0/10
22. [B 站'猫娘计划'开源 AI 伙伴亮相 WAIC 2026](#item-22) ⭐️ 7.0/10
23. [韩国高官提议从芯片利润中分红 AI 收益](#item-23) ⭐️ 7.0/10
24. [Fable 5 与 GPT-5.6 Sol：/goal 指令对 NP-Hard 任务是否有帮助？](#item-24) ⭐️ 6.0/10
25. [TabFM Studio：使用表格基础模型的无代码电子表格预测](#item-25) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [LG 显示器通过 Windows Update 静默安装软件](https://videocardz.com/newz/lg-monitors-silently-install-software-through-windows-update-without-user-consent) ⭐️ 9.0/10

LG 显示器正通过 Windows Update 在用户插入 HDMI 或 DisplayPort 连接时，未经同意自动安装配套软件。 此行为带来严重的安全和隐私风险，因为该软件在系统启动时运行、拥有网络访问权限，且由第三方供应商在无需用户交互的情况下安装。 该软件以 WHQL 签名的驱动程序包形式交付，并在每次系统启动时运行，影响新老 LG 显示器用户。

hackernews · baranul · 7月18日 10:21 · [社区讨论](https://news.ycombinator.com/item?id=48956688)

**背景**: Windows Update 旨在自动提供驱动程序和固件更新，以确保硬件兼容性。硬件供应商可以提交 Windows 信任的 WHQL 签名包，其中可能包含非驱动程序软件。此机制可能被滥用于在未经用户同意的情况下安装不需要的应用程序。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://asibiont.com/en/blog/monitory-lg-tayno-ustanavlivayut-po-cherez-windows-update-bez-vashego-soglasiya-chto-proiskhodit-i-kak-zashchititsya">LG Monitors Silently Install Software Through Windows Update ...</a></li>
<li><a href="https://blog.zealtyro.com/lg-monitors-silently-installing-windows-software/">LG Monitors Silently Installing Software via Windows Update : What...</a></li>
<li><a href="https://commutevolt.com/maintenance-repairs/lg-monitors-silently-install-software-through-windows-update-without-consent/">LG Monitors Silently Install Software Through Windows Update ...</a></li>

</ul>
</details>

**社区讨论**: 社区评论表达了强烈不满，部分用户提供了通过组策略或设备安装设置禁用自动驱动下载的解决方法。还有关于微软还是 LG 应负主要责任的争论，许多用户批评 Windows 允许自动安装第三方软件。

**标签**: `#security`, `#privacy`, `#Windows`, `#hardware`, `#software distribution`

---

<a id="item-2"></a>
## [Firefox 被编译为 WebAssembly 在另一个浏览器中运行](https://simonwillison.net/2026/Jul/16/firefox-in-webassembly/#atom-everything) ⭐️ 9.0/10

Puter 已将完整的 Firefox 浏览器编译为 WebAssembly，使其能够通过一个 233MB 的 WebAssembly 二进制文件和 18MB 的资源文件在另一个浏览器（如 Chrome）中运行。该项目使用了 AI 辅助开发，消耗了估值 25,000 美元的 Claude Opus 和 Fable 计算令牌。 这展示了一项突破性的技术成就：在一个浏览器内完整运行另一个浏览器，拓展了 WebAssembly 的能力边界。它可能催生新型 Web 应用，如安全的沙箱浏览或遗留浏览器模拟，并展示了 AI 辅助编程在复杂移植项目中的潜力。 选择 Firefox 的 Gecko 引擎是因为其强大的单进程支持，这简化了 WebAssembly 编译。网络流量通过 Wisp WebSocket 协议经由 Puter 服务器代理，HTTPS 流量的端到端加密已得到验证；团队不得不扩展服务器以应对 Hacker News 带来的流量。

rss · Simon Willison · 7月16日 23:34

**背景**: WebAssembly (Wasm) 是一种低级二进制指令格式，能在现代 Web 浏览器中以接近原生的速度运行，允许用 C++ 等语言编写的代码在浏览器中执行。将完整的 Firefox 等浏览器编译为 Wasm 极具挑战性，因其规模和复杂性；该项目利用 AI 工具（Claude Opus 和 Fable）协助大规模重构，消耗了估值 25,000 美元的计算令牌。Wisp 协议是一种轻量级协议，用于在单个 WebSocket 连接上复用多个 TCP/UDP 套接字，为无法打开原始套接字的 Wasm 模块提供网络功能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/MercuryWorkshop/wisp-protocol">GitHub - MercuryWorkshop/ wisp - protocol : Wisp is a low-overhead...</a></li>

</ul>
</details>

**标签**: `#WebAssembly`, `#Firefox`, `#browser-in-browser`, `#AI-assisted development`, `#Wisp protocol`

---

<a id="item-3"></a>
## [Meta 拟向 Anthropic 出租百亿美元 AI 算力](https://www.nytimes.com/2026/07/17/technology/meta-anthropic-ai-computing-power.html) ⭐️ 9.0/10

Meta 正在与 Anthropic 谈判，拟将 AI 数据中心算力出租给后者，潜在交易规模达 100 亿美元，为期两年。该提案由 Anthropic 于今年 6 月提出，Meta 正在评估。 这笔交易凸显了 AI 算力的严重稀缺性。它既能为 Meta 开辟新的收入来源以证明其巨额基础设施支出的合理性，也能让 Anthropic 获得关键的算力资源。 该交易仍处于早期谈判阶段，未必能最终达成。Anthropic 将按月付款，双方均可提前退出。Meta 今年计划投入高达 1450 亿美元，其中大部分用于 AI 和数据中心建设。

telegram · zaihuapd · 7月18日 01:14

**背景**: AI 算力是指训练和运行 AI 模型所需的处理能力，由于 GPU 短缺和能源限制，目前需求旺盛。像 Meta 这样的科技巨头正在大力投资 AI 基础设施，常常会产生闲置容量，可以对外出租。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.linkedin.com/pulse/ai-compute-scarcity-2025-how-gpus-power-cooling-de-castro-júnior-ovm1c">AI compute scarcity in 2025: how GPUs, power, and cooling...</a></li>
<li><a href="https://fferoz.medium.com/the-ai-compute-crunch-is-here-why-inference-will-break-your-budget-before-2028-e63333cfaebd">AI Compute Shortage 2026–2028: Why Enterprises Face an... | Medium</a></li>
<li><a href="https://qz.com/100019/the-new-hot-commodities-market-the-cloud">The new hot commodities market: the cloud</a></li>

</ul>
</details>

**标签**: `#AI infrastructure`, `#cloud computing`, `#Meta`, `#Anthropic`, `#compute scarcity`

---

<a id="item-4"></a>
## [特朗普政府拟设类似 FINRA 的 AI 审查机构](https://www.bloomberg.com/news/articles/2026-07-17/us-considers-creating-finra-like-watchdog-to-vet-top-ai-models) ⭐️ 9.0/10

特朗普政府正考虑设立一个独立监管机构，模仿美国金融业监管局（FINRA），负责审查顶尖人工智能模型的安全性。该提案由财政部长斯科特·贝森特牵头，正由白宫幕僚长苏茜·威尔斯审阅。 此举旨在回应华尔街对网络安全的担忧以及硅谷对临时性政府管控的不满，让两大行业在制定 AI 安全标准方面拥有更大发言权。该计划与 Google DeepMind 首席执行官德米斯·哈萨比斯提出的行业资助独立监管机构建议方向一致。 拟议中的机构将像 FINRA 一样向美国证券交易委员会（SEC）汇报，但相关框架仍在讨论中，总统特朗普尚未审阅该方案。此前，Anthropic 和 OpenAI 均因美国政府要求修改或延迟发布最新模型而提出异议。

telegram · zaihuapd · 7月18日 05:45

**背景**: FINRA 是由美国证券交易委员会（SEC）监督的独立监管机构，负责监控证券公司以防止欺诈和保护投资者。特朗普政府的提案借鉴了这一模式，为 AI 领域创建一个行业资助的独立机构来制定安全标准。此举正值政府与 AI 公司之间因模型发布和国家安全问题而关系紧张之际。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://zh.wikipedia.org/zh-hans/美国证券法">美国证券法 - 维基百科，自由的百科全书</a></li>
<li><a href="https://www.oanda.com/bvi-ft/lab-education/invest_us_stock/finra/">FINRA是什麼？介紹其成立宗旨與功能所在 - OANDA Lab</a></li>
<li><a href="https://lazarusalliance.com/zh-CN/什么是FINRA合规性/">什么是 FINRA 合规性？ - Lazarus Alliance, Inc.</a></li>

</ul>
</details>

**标签**: `#AI监管`, `#美国政府`, `#FINRA`, `#政策`, `#人工智能安全`

---

<a id="item-5"></a>
## [GPT-5.6 解决凸优化领域 30 年悬而未决的问题](https://old.reddit.com/r/math/comments/1uxj3cy/after_openais_cdc_proof_announcement_gpt56_used_a/) ⭐️ 8.0/10

研究人员通过一个单次提示（prompt）使用 GPT-5.6（Sol Pro 版本）生成了一份证明，填补了凸优化领域一个长达 30 年的空白，该空白涉及球域上凸 Lipschitz 函数的迭代复杂度上界。 这一成就表明大型语言模型能够为纯数学研究做出贡献，解决人类数学家数十年来未能解决的问题。标志着人工智能从计算工具向积极的研究伙伴转变。 该问题关注球域上凸 Lipschitz 函数极小化的时间复杂度，是一个长期存在的猜想。GPT-5.6 通过单次交互生成证明，而非迭代改进，凸显了该模型的推理能力。

hackernews · mbustamanter · 7月18日 13:00 · [社区讨论](https://news.ycombinator.com/item?id=48957779)

**背景**: 凸优化研究在凸集上极小化凸函数，在工程、机器学习和经济学中有许多实际应用。30 年空白指的是解决某些凸优化问题所需迭代次数的上界缺失。该结果提供了这个上界，验证了关于最优算法的猜想。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://news.ycombinator.com/item?id=48957779">GPT-5.6 used a prompt to close a 30-year gap in convex optimization | Hacker News</a></li>
<li><a href="https://en.wikipedia.org/wiki/Convex_optimization">Convex optimization - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Duality_(optimization)">Duality (optimization) - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区讨论总体积极，专家们认为该成果是真实但小众的贡献。一些评论者担心 AI 会取代‘低垂果实’式的研究，而另一些人则建议 LLM 可用于验证难以理解的人类证明，例如 abc 猜想。也有澄清指出使用的模型是 Sol Pro 而非 Ultra。

**标签**: `#AI`, `#convex optimization`, `#mathematical research`, `#GPT`, `#LLM`

---

<a id="item-6"></a>
## [StackOverflow 衰落之争：AI 还是社区政策](https://data.stackexchange.com/stackoverflow/query/1953768#graph) ⭐️ 8.0/10

来自 Stack Exchange 数据的一张图显示了 StackOverflow 活动的长期下滑，引发了关于 AI 工具（如 ChatGPT）还是早期因素（如严格的社区政策和企业收购）导致了下降的争论。 这场讨论之所以重要，是因为它挑战了单纯认为 AI 扼杀了 StackOverflow 的简单叙事，揭示了社区治理和商业决策如何影响平台健康。 该图的峰值出现在 2014 年左右，远在生成式 AI 成为主流之前，社区评论指出 2021 年 StackOverflow 被 Prosus 收购是另一个转折点。

hackernews · secretslol · 7月18日 11:12 · [社区讨论](https://news.ycombinator.com/item?id=48956949)

**背景**: StackOverflow 是一个问答平台，用户通过贡献获得声誉和徽章，但其严格的审核和对随意交流的抵制疏远了新手。AI 助手（如 ChatGPT）的兴起提供了快速获取答案的替代方案，但数据显示在 AI 普及之前活动就已经在下降。

**社区讨论**: 社区评论主要将 StackOverflow 的衰落归因于其排外文化和严格政策，而非 AI。一些用户指出，衰落始于 2014 年达到峰值之后，并在 Prosus 收购后加速，表明存在多种因素而非仅仅是 AI。

**标签**: `#StackOverflow`, `#AI impact`, `#online communities`, `#developer tools`, `#data analysis`

---

<a id="item-7"></a>
## [Kimi K3 以 2.8 万亿参数打破纪录](https://simonwillison.net/2026/Jul/16/kimi-k3/#atom-everything) ⭐️ 8.0/10

Moonshot AI 发布了 Kimi K3，这是一个拥有 2.8 万亿参数的开源权重模型，在多项基准测试中超越众多竞争对手，并承诺在 2026 年 7 月 27 日前开放权重。 这标志着迄今为止最大的开源参数 AI 模型，可能以低于 GPT-5.6 和 Claude Opus 4.8 等专有对手的成本，民主化前沿能力的使用。 Kimi K3 的定价为每百万输入 token 3 美元、每百万输出 token 15 美元，成为最贵的中国 AI 模型，但其输出 token 使用量比前代 K2.6 减少了 21%。

rss · Simon Willison · 7月16日 20:19

**背景**: 鹈鹕基准测试指的是 Simon Willison 的非正式测试，要求生成一个骑自行车的鹈鹕的 SVG 图像，用于比较模型的创造力和指令遵循能力。该测试已成为社区驱动的评估 AI 图像生成能力的方法，Hugging Face 上有一个空间跟踪结果。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://ndurner.github.io/pelican-benchmark">Pelican vs. Llama 3.1 405B and others | Nils Durner’s Blog</a></li>
<li><a href="https://huggingface.co/spaces/victor/pelican-benchmark">Pelican Benchmark - a Hugging Face Space by victor</a></li>

</ul>
</details>

**标签**: `#AI`, `#large language models`, `#open source`, `#benchmarks`

---

<a id="item-8"></a>
## [上海 AI Lab 让 Harness 自进化，性能提升 104%不换模型](https://mp.weixin.qq.com/s?__biz=MzIzNjc1NzUzMw==&mid=2247904823&idx=3&sn=af8b10819641ba1f59492acb8aa9ebd4) ⭐️ 8.0/10

上海人工智能实验室的研究人员推出了 Self-Harness 框架，该框架使基于大语言模型的智能体能够自主改进其操作规则，在不修改底层模型的情况下实现了 104%的性能提升。 这一突破表明智能体可以在 harness 层面自我进化，可能减少对人工工程的需求，加速更强大 AI 智能体的部署。同时，它将优化焦点从模型参数转移到周围的软件基础设施上。 Self-Harness 方法在基准任务上将智能体性能提升了 104%，大幅超越以往方法。该框架允许 harness 重写自身规则，包括工具使用、内存管理和执行策略等。

rss · 量子位 · 7月18日 07:45

**背景**: Agent Harness 是围绕大语言模型的软件基础设施，使其能够作为 AI 智能体运行，管理工具、内存、状态和执行循环。传统上，harness 由人类工程师设计且保持静态，而 Self-Harness 引入了一种新范式，即 harness 通过迭代反馈和自我修改随时间不断改进自身。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2606.09498">[2606.09498] Self-Harness: Harnesses That Improve Themselves</a></li>
<li><a href="https://venturebeat.com/orchestration/researchers-introduce-self-harness-a-framework-that-lets-ai-agents-rewrite-their-own-rules-boosting-performance-up-to-60">Researchers introduce Self-Harness, a framework that lets AI agents rewrite their own rules, boosting performance up to 60% | VentureBeat</a></li>
<li><a href="https://en.wikipedia.org/wiki/Agent_harness">Agent harness</a></li>

</ul>
</details>

**标签**: `#AI`, `#agent`, `#self-evolution`, `#harness`, `#Shanghai AI Lab`

---

<a id="item-9"></a>
## [无意义的 AI 输出竟赢得 DeepMind/Kaggle 2.5 万美元大奖？](https://www.reddit.com/r/MachineLearning/comments/1uzyf66/did_blatant_ai_slop_just_win_a_25k_usd_deepmind/) ⭐️ 8.0/10

一位 Reddit 用户提供了详细证据，指出在 Google DeepMind 赞助的 Kaggle 竞赛“衡量通向 AGI 的进展——认知能力”中，一个毫无意义的提交作品赢得了 2.5 万美元大奖，并对评审过程的公正性提出质疑。 此事件引发了对高额奖金 AI 竞赛评审可靠性的严重担忧，可能损害对以基准测试驱动通用人工智能进展的信任。 据称，获胜提交作品的规模是要求格式的 10 倍，并包含无根据的声明，而组织者坚持认为评审过程得当，且主观性不可避免。

reddit · r/MachineLearning · /u/TheWerkmeister · 7月18日 15:10

**背景**: 2026 年 3 月，Google DeepMind 发起了一场总奖金 20 万美元的 Kaggle 黑客马拉松，旨在开发基于认知科学的基准测试来衡量通向 AGI 的进展，设有多个赛道和 2.5 万美元的大奖。该竞赛旨在评估 AI 在十种认知能力上的表现，但对 AGI 的定义和基准测试仍然充满争议和挑战。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://blog.google/innovation-and-ai/models-and-research/google-deepmind/measuring-agi-cognitive-framework/">Measuring Progress Towards AGI: A Cognitive Framework</a></li>
<li><a href="https://liora.io/en/google-deepmind-framework-measure-agi">Google DeepMind reveals cognitive framework to finally measure AGI</a></li>
<li><a href="https://spectrum.ieee.org/agi-benchmark">AGI Benchmarks: Tracking Progress Toward AGI Isn't Easy - IEEE Spectrum</a></li>

</ul>
</details>

**标签**: `#AI ethics`, `#Kaggle`, `#DeepMind`, `#AGI benchmarks`

---

<a id="item-10"></a>
## [Stereo2Spatial：用扩散模型将立体声转为双耳空间音频](https://www.reddit.com/r/MachineLearning/comments/1uzevbg/stereo2spatial_convert_stereo_music_tracks_to/) ⭐️ 8.0/10

作者发布了一个名为 Stereo2Spatial 的新型流匹配扩散模型，可以将立体声音乐转换为空间化双耳混音。该模型使用记忆令牌来保持长上下文稳定性，并在 7,669 首曲目上进行了训练。 这解决了现有音乐缺乏高质量空间混音的问题，使沉浸式聆听体验成为可能。Apache 2.0 开源许可鼓励空间音频生成的进一步发展。 该模型最初在 VAE 的潜在空间中运行，但为了克服质量瓶颈改为原始波形，并使用振幅提升来保证训练稳定性。它包含可选的混音风格条件控制和一个用于推理的 Windows 桌面应用程序。

reddit · r/MachineLearning · /u/kittenkrazy · 7月17日 22:55

**背景**: 流匹配扩散模型通过学习噪声分布与数据分布之间的概率路径来生成数据。双耳音频通过两个声道模拟 3D 声音，而 7.1.4 等空间音频格式则使用多扬声器。VAE（变分自编码器）将音频压缩到潜在空间以实现高效处理。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/html/2601.12950v1">ImmersiveFlow : Stereo-to-7.1.4 Spatial Audio Generation with Flow ...</a></li>
<li><a href="https://huggingface.co/earlab/EAR_VAE">earlab/ EAR _ VAE · Hugging Face</a></li>
<li><a href="https://arxiv.org/abs/2210.02747">[2210.02747] Flow Matching for Generative Modeling</a></li>

</ul>
</details>

**标签**: `#machine learning`, `#audio processing`, `#spatial audio`, `#diffusion models`, `#VAE`

---

<a id="item-11"></a>
## [Prism 漏洞导致未发表论文泄露](https://www.reddit.com/r/MachineLearning/comments/1uz75qt/prism_accidentally_leaked_d/) ⭐️ 8.0/10

Prism 的编译过程出现漏洞，意外泄露了未发表的论文，Reddit 和 Twitter 上已有相关报道。Prism 团队在首次报告后的 10 分钟内关闭了网站。 此事件引发了对学术投稿系统安全性的严重担忧，可能危及未发表研究的机密性。它可能削弱学术界对用于论文编译和提交的数字工具的信任。 该漏洞导致编译功能返回了其他用户的论文而非预期论文。漏洞在 Prism 的 Discord 和 Twitter 上被标记，网站于 10 分钟内被关闭。

reddit · r/MachineLearning · /u/Few-Monitor5103 · 7月17日 17:59

**背景**: Prism 是一种用于简化学术论文编译和格式化的工具，常用于研究人员向机器学习会议投稿。这类工具将 LaTeX 或其他源文件编译成 PDF 文档供提交。编译过程中的漏洞可能混淆不同用户的文件，导致数据泄露。

<details><summary>参考链接</summary>
<ul>
<li><a href="http://atomicego.com/ai-tools/prism/prism-academic-workflow">How to Use Prism and NotebookLM to Understand, Build, and Publish</a></li>

</ul>
</details>

**标签**: `#paper leak`, `#security`, `#academic publishing`, `#ML conference`, `#privacy`

---

<a id="item-12"></a>
## [EU AI Act OpenRAG：933 个法律结构化块与 BGE-M3 嵌入](https://www.reddit.com/r/MachineLearning/comments/1uytlac/eu_ai_act_openrag_933_legally_structured_chunks/) ⭐️ 8.0/10

发布了欧盟 AI 法案（2024/1689 号法规）的可下载语料库，包含 933 个法律结构化块，每个块具有归一化的 1024 维 BGE-M3 嵌入，以及评估基准和完整方法论。 该资源为法律领域的检索增强生成（RAG）和 NLP 提供了高质量的结构化数据集，使得在具有法律意义的领域中对分块策略、检索方法和嵌入模型进行可重复的评估和比较成为可能。 SQLite 数据库包含 933 个块、精确的 EUR-Lex 链接、第 113 条应用日期元数据和刻意狭窄的派生标签；在 AI 法案评估基准上的评估显示，结构化分块将场景文章 recall@20 从 0.449 提升至 0.541，QA 文章 hit@10 从 0.898 提升至 0.927。

reddit · r/MachineLearning · /u/Automatic-Forever-63 · 7月17日 08:18

**背景**: 欧盟 AI 法案是一项具有里程碑意义的、规范人工智能的法规，要求法律 AI 系统准确解读其条款。检索增强生成（RAG）将信息检索与语言模型相结合，但标准分块方法（如滑动窗口）通常会破坏法律文档结构。BGE-M3 是由北京智源人工智能研究院（BAAI）开发的功能强大的多语言嵌入模型，支持密集检索，而 EUR-Lex 是用于链接的官方欧盟法律数据库。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://ollama.com/library/bge-m3">bge - m 3</a></li>
<li><a href="https://en.wikipedia.org/wiki/EUR-Lex">EUR - Lex - Wikipedia</a></li>

</ul>
</details>

**标签**: `#RAG`, `#legal NLP`, `#EU AI Act`, `#embeddings`, `#dataset`

---

<a id="item-13"></a>
## [SpaceX 与五角大楼谈判数十亿美元 AI 算力交易](https://www.wsj.com/tech/ai/spacex-in-talks-to-provide-computing-power-for-pentagons-ai-push-15e752e4) ⭐️ 8.0/10

SpaceX 正与美国国防部谈判，拟提供用于运行 AI 模型的数据中心算力，潜在交易金额高达数十亿美元。 这将标志着 SpaceX 云计算业务的大幅扩张，并深化其与五角大楼的关系，影响 AI 基础设施市场和国家安全能力。 谈判仍在进行中，存在破裂可能。SpaceX 近月已与 Anthropic 和谷歌签署了类似算力供应协议，并计划大幅扩展云计算业务。

telegram · zaihuapd · 7月18日 01:44

**背景**: 五角大楼正加速获取云计算能力，以支持国家安全和日常作战中的 AI 应用。该部门近期已批准 SpaceX、亚马逊、谷歌、微软和甲骨文在机密环境中使用其 AI 模型。SpaceX 独特的太空资产（如星链）可能为其在安全数据传输方面提供优势。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://goodinfo.net/posts/ai-tech/pentagon-ai-classified-deals-may-2026/">五 角 大 楼 与七 大 科技巨头签署 机 密 AI 部署协议，Anthropic... | goodinfo.net</a></li>
<li><a href="https://www.coodoor.com/2026/04/gemini.html">谷歌正在和美国 五 角 大 楼 商量，想把Gemini...</a></li>

</ul>
</details>

**标签**: `#AI算力`, `#SpaceX`, `#国防技术`, `#云计算`, `#大语言模型`

---

<a id="item-14"></a>
## [OpenRouter 传被收购，估值超 13 亿美元](https://www.theinformation.com/articles/startup-openrouter-fields-multi-billion-dollar-takeover-interest) ⭐️ 8.0/10

AI 模型路由平台 OpenRouter 已被多家大型科技公司接触，潜在收购估值高于其今年 5 月 B 轮融资后的约 13 亿美元。 这表明 AI 模型路由领域获得了强有力的市场验证，并可能出现整合——该领域是企业实现低成本 LLM 访问的关键基础设施。高额收购溢价突显了统一 API 网关对企业的战略价值。 OpenRouter 由 Alphabet 旗下 CapitalG 领投的 B 轮融资共筹集 1.13 亿美元，投后估值约 13 亿美元，较去年 6 月 A 轮的 5.47 亿美元翻倍有余。该平台目前路由超 400 个模型，服务约 800 万用户，每月处理约 100 万亿 token，2026 年初年化收入已达约 5000 万美元。

telegram · zaihuapd · 7月18日 03:45

**背景**: AI 模型路由平台提供一个统一的 API 网关，可访问数百个大语言模型，并自动将查询导向最具性价比或最佳性能的选项。这种抽象层简化了开发者集成，减少了供应商锁定，使其成为不断增长的 LLM 生态系统的关键组成部分。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openrouter.ai/">The unified interface for LLMs. Find the best models & prices for your...</a></li>
<li><a href="https://gate.ai/">Gate. AI — Enterprise-grade AI large-scale model routing and...</a></li>

</ul>
</details>

**标签**: `#AI infrastructure`, `#acquisition`, `#startup`, `#model routing`, `#LLM`

---

<a id="item-15"></a>
## [台积电宣布 A14 制程将于 2028 年投产](https://t.me/zaihuapd/42643) ⭐️ 8.0/10

台积电宣布其下一代 A14 制程技术计划于 2028 年开始投产。与 N2 制程相比，A14 在相同功耗下速度提升高达 15%，或在相同速度下功耗降低达 30%，同时逻辑密度提高超过 20%。 这一声明巩固了台积电在先进半导体制造领域的领先地位，对 AI、高性能计算和移动处理器至关重要。A14 节点预计将大幅提升未来芯片的性能和能效，使台积电保持对英特尔和三星等竞争对手的优势。 台积电还计划在 2026 年末推出中间的 A16 制程，而 N2 已于 2025 年第四季度开始量产。A14 节点很可能属于 1.4nm 级别技术，台积电已确认来自 AI、高性能计算和智能手机客户的浓厚兴趣。

telegram · zaihuapd · 7月18日 05:00

**背景**: 台积电（TSMC）是全球最大的专业半导体代工厂。制程节点（如 N2、A14）指代制造技术的代际，数字越小通常表示晶体管越先进、密度越高。A14 是 N2（2nm 级别）的后继者，属于台积电维持技术领先地位路线图的一部分，与英特尔 18A 和三星 SF2 节点竞争。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://xab.info/en/posts/tsmc-a14-performance-surpasses-n2">TSMC Breaks Its Own Records: New A 14 (1.4nm) Process ... - XAB.info</a></li>
<li><a href="https://www.newkerala.com/news/a/tsmc-projects-mass-production-advanced-a14-chips-2028-477.htm">TSMC A 14 Chips Mass Production by 2028</a></li>
<li><a href="https://www.tomshardware.com/tech-industry/semiconductors/tsmc-confirms-significant-yield-and-performance-improvements-in-a14-update-strong-interest-from-ai-hpc-and-smartphone-customers">TSMC confirms significant yield and performance... | Tom's Hardware</a></li>

</ul>
</details>

**标签**: `#TSMC`, `#semiconductor`, `#process technology`, `#A14`, `#hardware`

---

<a id="item-16"></a>
## [旧金山责令苹果谷歌下架‘脱衣’应用](https://techcrunch.com/2026/07/17/apple-and-google-ordered-to-purge-nudify-apps-from-app-stores/) ⭐️ 8.0/10

旧金山市检察长邱信福致函苹果和谷歌，要求其从应用商店中移除数十款利用 AI 技术‘脱衣’的应用，因为这些应用可生成非自愿的深度伪造私密图像。 此举凸显了科技平台在应对 AI 滥用和深度伪造色情内容方面面临的日益增长的法律压力，可能为平台责任和用户安全执法树立先例。 这些应用利用 AI 技术未经同意对照片进行数字化‘脱衣’。苹果表示已移除 3 款应用并终止相关开发者账号，谷歌则暂停了信中点名的 5 款 Play Store 应用。

telegram · zaihuapd · 7月18日 08:45

**背景**: 深度伪造技术利用深度学习创建逼真的伪造图像和视频，常被恶意用于制作非自愿的色情内容。‘脱衣’应用是深度伪造应用的一类，可以从照片中移除衣物，引发严重的隐私和伦理问题。此类法律行动是更广泛推动监管 AI 生成内容并追究平台分发责任的一部分。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Nudify_apps">Nudify apps</a></li>
<li><a href="https://copperpod.medium.com/deepfake-and-ai-to-be-or-not-to-be-8b8825fe0f0">Deepfake and AI: To Be or Not To Be | by Copperpod IP | Medium</a></li>

</ul>
</details>

**标签**: `#AI ethics`, `#deepfake`, `#platform regulation`, `#privacy`, `#legal`

---

<a id="item-17"></a>
## [反着来的 JPEG：通过渐进式 JPEG 加载实现视频动画](https://maurycyz.com/projects/bad_jpeg/) ⭐️ 7.0/10

“Regressive JPEGs”项目利用 JPEG 图像的渐进式加载特性，将每个渐进扫描层作为视频帧，播放速度取决于网络延迟，从而呈现出一个粗糙的视频动画。 这个技巧展示了对标准图像格式的新颖滥用，激发了隐写术、内容过滤绕过以及非常规用户界面元素的创意，尽管其实用性有限。 动画完全依赖网络延迟，因为渐进式 JPEG 扫描层是顺序发送的；图像本身无法控制帧之间的时间间隔。

hackernews · vitaut · 7月18日 03:14 · [社区讨论](https://news.ycombinator.com/item?id=48954851)

**背景**: 渐进式 JPEG 是标准 JPEG 格式的一种变体，它首先显示低质量版本的图像，然后在后续扫描中逐步细化，从而改善感知加载时间。该项目利用每个渐进扫描层作为单独的帧，在通过网络加载时，由于延迟变化，形成了一个粗糙的视频。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.ctrl.blog/entry/jpeg-progressive-loading.html">Progressive JPEGs make a meaningful impact on perceived... | Ctrl blog</a></li>
<li><a href="https://calendar.perfplanet.com/2012/progressive-jpegs-a-new-best-practice/">Progressive jpegs : a new best practice - Web Performance Calendar</a></li>

</ul>
</details>

**社区讨论**: 社区成员分享了相关实验（例如使用交错 PNG 实现类似效果），并讨论了诸如进度条等潜在应用。一些人注意到跨浏览器的不一致性，尤其是在移动 iOS 上。其他人则猜测其在隐写术和内容过滤规避方面的用途。

**标签**: `#jpeg`, `#progressive-image`, `#video`, `#web`, `#hack`

---

<a id="item-18"></a>
## [Claude Fable 5 在订阅计划中永久保留](https://simonwillison.net/2026/Jul/18/claude-make-fable-5-permanent/#atom-everything) ⭐️ 7.0/10

Anthropic 撤销了将 Claude Fable 5 从订阅账户中移除的计划，宣布自 7 月 20 日起，Fable 5 将以 50% 的限额包含在所有 Max 和 Team Premium 计划中。 这一决定反映了来自 GPT-5.6 Sol 和 Kimi 3 的激烈竞争压力，确保订阅用户无需支付额外 API 费用即可继续使用 Anthropic 最强大的模型。 每月 20 美元计划的用户仍然无法使用 Fable 5；Max 计划每月费用为 100 美元或 200 美元。Pro 和 Team Standard 用户将获得一次性 100 美元的信用额度用于按使用量访问。

rss · Simon Willison · 7月18日 06:00

**背景**: Claude Fable 5 是 Anthropic 最先进的模型，专为自主、长期运行的代理工作设计，拥有 100 万 token 的上下文窗口。它直接与 OpenAI 的 GPT-5.6 Sol 和 Kimi 的 Kimi 3 竞争，后者近期在编码和推理基准测试中表现出色。Anthropic 最初计划逐步取消订阅中的 Fable 5 是出于算力限制，但竞争态势迫使公司转变策略。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/claude/fable">Claude Fable \ Anthropic</a></li>
<li><a href="https://openai-dotcom-git-main-openai.vercel.app/index/gpt-5-6/">GPT - 5 . 6 : Frontier intelligence that scales with your ambition | OpenAI</a></li>
<li><a href="https://platform.kimi.ai/docs/guide/kimi-k3-quickstart">Kimi K 3 - Kimi API Platform</a></li>

</ul>
</details>

**标签**: `#Claude`, `#Anthropic`, `#AI models`, `#subscription pricing`, `#competition`

---

<a id="item-19"></a>
## [DABSN：新型循环语言模型寻求合作者](https://www.reddit.com/r/MachineLearning/comments/1uycffg/seeking_collaborators_for_scaling_and_independent/) ⭐️ 7.0/10

一位独立研究者发布了 DABSN 这一新型循环架构，提供了开源代码和初步的语言模型结果，并正在寻求合作者以扩大规模并进行独立评估。 如果得到验证，DABSN 可能为长上下文语言任务提供一种比 Transformer 更高效的替代方案，从而推动开源 AI 研究并减少对大规模计算的依赖。 该架构在 MQAR 和 Copy 等推理与记忆基准测试上表现出色，且研究者使用 GPT-2 分词器在 10 亿 tokens 上训练了一个 24M 参数的语言模型。代码提供了 PyTorch、C++和 Triton 实现。

reddit · r/MachineLearning · /u/BleedingXiko · 7月16日 19:17

**背景**: 循环神经网络（RNN）逐步处理序列，因此在长序列上计算效率高，但历史上比 Transformer 更难并行化。DABSN 是一种新型 RNN 变体，旨在改进动态偏置和状态自适应。使用 Triton（一种类似 Python 的 GPU 编程语言）可以在不需要 CUDA 专业知识的情况下编写自定义高性能内核。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.emergentmind.com/topics/multi-query-associative-recall-mqar">MQAR : Multi-Query Associative Recall</a></li>
<li><a href="https://triton-lang.org/main/">Welcome to Triton ’s documentation! — Triton documentation</a></li>

</ul>
</details>

**标签**: `#Recurrent Neural Networks`, `#Language Model`, `#Open Source`, `#Machine Learning Research`

---

<a id="item-20"></a>
## [豆包手机放弃 GUI 操作，要求超级应用提供 MCP](https://www.latepost.com/news/dj_detail?id=3648) ⭐️ 7.0/10

豆包手机调整了策略：不再采用 GUI 硬操作技术直接操控微信、淘宝等头部应用，而是要求这些超级应用自行提供 MCP（模型上下文协议）服务来开放数据与操控权限。其备货量已从此前的 3 万台提升至数十万台。 此举改变了 AI 手机生态的权力格局，从以手机为中心的自动化操作转向平台授权的数据访问。这可能为 AI 助手与主要应用的集成方式树立先例，影响用户隐私、应用控制以及 AI 入口的争夺。 豆包手机助手此前因使用 GUI 模拟操作而遭到微信和淘宝封禁。新策略与苹果、谷歌转向开发者授权的类似 MCP 框架的方向一致，强调合作而非绕过限制。

telegram · zaihuapd · 7月18日 00:29

**背景**: GUI 硬操作是指读取手机屏幕并模拟人类点击来控制应用的技术。MCP（模型上下文协议）是一种开放标准，允许 AI 模型通过授权 API 安全地连接工具和数据源。各大科技公司正在争夺 AI 入口的主导地位，这导致设备制造商与应用平台之间出现紧张关系。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.163.com/dy/article/L22ST2EA0531M1CO.html?clickfrom=w_dy">晚点独家丨新豆包手机备货数十万台，AI 不再 硬 操 作 头部应用</a></li>
<li><a href="https://modelcontextprotocol.io/">What is the Model Context Protocol ( MCP )? - Model Context Protocol</a></li>

</ul>
</details>

**标签**: `#AI手机`, `#MCP`, `#应用生态`, `#AI助手`, `#豆包`

---

<a id="item-21"></a>
## [SK 海力士 CEO 预警 2027 年将现史上最严重内存短缺](https://t.me/zaihuapd/42645) ⭐️ 7.0/10

SK 海力士 CEO 郭鲁正警告称，到 2027 年全球内存行业将面临史上最严重的供应短缺，即使积极扩产，客户需求在 2030 年后仍将超过供应能力。 这家顶级内存制造商的警告预示着长期的供需失衡，可能推高内存价格，并影响 AI、云计算和消费电子等下游行业。 郭鲁正透露，SK 海力士正在考虑包括美国、日本和东南亚在内的海外晶圆厂选址，优先考虑土地、电力和人力成本优势。该公司 2025 年营业利润达创纪录的 47 万亿韩元（约 310 亿美元）。

telegram · zaihuapd · 7月18日 06:30

**背景**: 内存行业历史上因需求和产能的波动而经历繁荣-萧条周期。SK 海力士是领先的 DRAM 和 NAND 闪存制造商，与三星和美光竞争激烈。这一警告正值用于 AI 加速器的高带宽内存（HBM）需求激增，使产能紧张。

**标签**: `#memory industry`, `#supply chain`, `#semiconductors`, `#SK Hynix`

---

<a id="item-22"></a>
## [B 站'猫娘计划'开源 AI 伙伴亮相 WAIC 2026](https://finance.sina.com.cn/roll/2026-07-18/doc-iniifanf8394663.shtml) ⭐️ 7.0/10

哔哩哔哩在 2026 年世界人工智能大会上展示了'猫娘计划'（Project N.E.K.O.），这是一款能理解桌面内容并主动发起对话的开源 AI 伙伴。 猫娘计划将开源可及性与多模态屏幕理解和声线克隆等先进功能相结合，有望让 AI 伙伴技术惠及更多开发者和用户。 该伙伴支持 Live2D 和 VRM 双引擎渲染，内置 TTS 语音模块和声线克隆，采用 UI、AI 大脑与记忆系统分离的架构以保护本地数据隐私。目前 GitHub 过千星，Steam 用户过万。

telegram · zaihuapd · 7月18日 06:45

**背景**: AI 伙伴是一种通过对话和行动与用户互动的软件代理。猫娘计划是一个开源项目，旨在创造能够感知用户屏幕和环境上下文的数字生命体。Live2D 和 VRM 是用于虚拟主播和游戏的 2D 和 3D 角色渲染的流行格式。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://project-neko.online/">Project N . E . K . O .</a></li>
<li><a href="https://store.steampowered.com/app/4099310/Project_NEKO/">Project N . E . K . O . on Steam</a></li>

</ul>
</details>

**标签**: `#AI companion`, `#open-source`, `#multimodal AI`, `#voice cloning`, `#Live2D`

---

<a id="item-23"></a>
## [韩国高官提议从芯片利润中分红 AI 收益](https://t.me/zaihuapd/42652) ⭐️ 7.0/10

韩国高官金容范提议建立全民分红制度，借鉴挪威石油基金模式，将 AI 半导体领域的结构性超额利润回馈给全体国民。该提议引发周二韩国 KOSPI 指数暴跌 5.1%。 该政策可能重塑 AI 驱动经济收益的分配方式，防止财富集中，并可能为其他国家树立先例。市场恐慌反映了投资者对企业利润减少和监管加强的担忧。 金容范主张 AI 基础设施收益源于半个多世纪的国家投入，而非仅企业努力，因此利润应共享。提议将分红用于青年创业和养老基金，但缺乏具体实施规则。

telegram · zaihuapd · 7月18日 14:20

**背景**: 挪威的政府养老金全球基金是全球最大的主权财富基金，将石油利润用于未来几代人。类似地，韩国半导体行业在 AI 热潮中产生了巨额利润，引发了公平分配的问题。“结构性超额利润”指超出正常市场回报的收益，归因于公共基础设施和教育。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.nbim.no/">The fund | Norges Bank Investment Management</a></li>
<li><a href="https://www.koreatimes.co.kr/southkorea/society/20260715/what-defines-excess-profits-and-who-should-benefit-from-them">What defines ' excess ' profits and who should... - The Korea Times</a></li>
<li><a href="https://www.ajupress.com/view/20260514173753142">BLUE HOUSE INSIGHT: Dialogue on ' excess profits ... | AJU PRESS</a></li>

</ul>
</details>

**标签**: `#AI policy`, `#economic distribution`, `#semiconductors`, `#South Korea`, `#universal dividend`

---

<a id="item-24"></a>
## [Fable 5 与 GPT-5.6 Sol：/goal 指令对 NP-Hard 任务是否有帮助？](https://charlesazam.com/blog/fable-5-gpt-5-6-sol-goal/) ⭐️ 6.0/10

一篇技术博客文章比较了 Anthropic 的 Fable 5 和 OpenAI 的 GPT-5.6 Sol 在一个 NP-Hard 问题上的表现，以测试 /goal 指令是否能提升问题解决能力。 这项比较为提示工程和模型在复杂推理方面的能力提供了实用见解，对于希望优化在困难计算问题上性能的 AI 开发者和研究人员具有价值。 作者指出图表纵轴反转导致混淆——数值越低越好，但视觉上立柱越高代表性能越好。社区评论还建议，/goal 对于单线索调查比复杂的多智能体策略更有效。

hackernews · couAUIA · 7月18日 11:00 · [社区讨论](https://news.ycombinator.com/item?id=48956879)

**背景**: NP-Hard 问题是一类计算上困难的问题，目前没有已知的高效解法。/goal 指令是一种提示工程技术，指示 AI 专注于特定目标。Fable 5 是 Anthropic 的 Mythos 类模型，专为长时间运行的智能体任务设计；GPT-5.6 Sol 是 OpenAI 的编码专用模型，在 Artificial Analysis Coding Agent Index 上达到最先进水平。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cursor.com/docs/models/claude-fable-5">Claude Fable 5 | Cursor Docs</a></li>
<li><a href="https://openai-dotcom-git-main-openai.vercel.app/index/gpt-5-6/">GPT - 5 . 6 : Frontier intelligence that scales with your ambition | OpenAI</a></li>
<li><a href="https://medium.com/@PropagenAI/the-definitive-guide-to-transformative-prompt-engineering-980fc3c4665a">The Definitive Guide to Transformative Prompt Engineering | Medium</a></li>

</ul>
</details>

**社区讨论**: 社区成员要求查看随时间变化的最佳分数，并建议使用'超模式'（ultra mode）进行更佳比较。一些用户对反转的图表感到困惑，其他人则分享了他们的经验：有用户指出 Claude Code 比 OpenAI 的 Codex 慢，还有用户提到 Claude 在长时间会话中容易忘记指令。

**标签**: `#AI`, `#LLM comparison`, `#NP-Hard`, `#problem solving`, `#prompt engineering`

---

<a id="item-25"></a>
## [TabFM Studio：使用表格基础模型的无代码电子表格预测](https://www.reddit.com/r/MachineLearning/comments/1uzx1el/tabfm_studio_pointandclick_predictions_on/) ⭐️ 6.0/10

一位开发者发布了 TabFM Studio，这是一个网页应用，允许用户通过点击操作在 CSV 或 Excel 文件上使用 Google 的 TabFM 表格基础模型进行预测，无需编写任何代码。 该工具显著降低了非程序员使用最先进的表格基础模型的门槛，有望让自动化数据分析和预测在电子表格工作流程中变得更加普及。 该应用目前仅支持 Google 的 TabFM 模型，其工作原理是将已填写的目标单元格作为上下文示例，并在网格界面上直接预测空白单元格。

reddit · r/MachineLearning · /u/Lckylke · 7月18日 14:15

**背景**: 表格基础模型是在数百万个合成数据集上预训练的大型神经网络，无需重新训练即可在新表格上进行预测。Google 的 TabFM 是一个零样本表格基础模型，能够处理表格数据的分类和回归任务。这个网页应用将 TabFM 封装在简单的用户界面中，使没有编程技能的用户也能使用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://research.google/blog/introducing-tabfm-a-zero-shot-foundation-model-for-tabular-data/">Introducing TabFM : A zero-shot foundation model for tabular data</a></li>
<li><a href="https://huggingface.co/google/tabfm-1.0.0-pytorch">google / tabfm -1.0.0-pytorch · Hugging Face</a></li>

</ul>
</details>

**标签**: `#tabular foundation models`, `#no-code`, `#machine learning tool`, `#spreadsheet`, `#TabFM`

---