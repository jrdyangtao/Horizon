---
layout: default
title: "Horizon Summary: 2026-07-09 (ZH)"
date: 2026-07-09
lang: zh
---

> 从 61 条内容中筛选出 25 条重要资讯。

---

1. [TypeScript 7.0 发布：Go 重写带来最高 12 倍速度提升](#item-1) ⭐️ 9.0/10
2. [尽管多数反对，欧盟议会仍通过“聊天控制 1.0”](#item-2) ⭐️ 8.0/10
3. [玻璃脊梁：美军后勤为何会在下一场战争中崩溃](#item-3) ⭐️ 8.0/10
4. [Meta 推出商业 API 版智能体 AI 模型 Muse Spark 1.1](#item-4) ⭐️ 8.0/10
5. [Bun JavaScript 运行时用 Rust 重写，采用智能体工程](#item-5) ⭐️ 8.0/10
6. [大三本科生一作实现 7.92 倍投机解码加速，获 DeepSeek 与阶跃星辰引用](#item-6) ⭐️ 8.0/10
7. [蚂蚁灵波开源 LingBot-Video：稀疏 MoE 13B 视频世界模型，RL 后训练](#item-7) ⭐️ 8.0/10
8. [非文本安全触发：MCP 攻击绕过 LLM 防护，成功率超半数](#item-8) ⭐️ 8.0/10
9. [大疆 EV50 无人机飞越珠峰 8861 米](#item-9) ⭐️ 8.0/10
10. [国家超算互联网核心节点在郑州上线，提供超 10 万卡国产算力](#item-10) ⭐️ 8.0/10
11. [ChatGPT Work 统一 ChatGPT 和 Codex 引发用户强烈不满](#item-11) ⭐️ 7.0/10
12. [腾讯开源 Hy3 混合专家模型：小体量、高性能，免费层引热议](#item-12) ⭐️ 7.0/10
13. [OpenAI 推出 GPT-Live 语音升级，可委派复杂任务给 GPT-5.5](#item-13) ⭐️ 7.0/10
14. [Kenton Varda 禁止使用 AI 生成提交信息，因其缺乏高层上下文](#item-14) ⭐️ 7.0/10
15. [IMGNet：使用滑动窗口符号模式进行面部验证](#item-15) ⭐️ 7.0/10
16. [新防御方法将微调约束到可信 LoRA 子空间以抵御投毒攻击](#item-16) ⭐️ 7.0/10
17. [OpenAI 与美国国防部拟修订 AI 合同禁止国内监控](#item-17) ⭐️ 7.0/10
18. [uv 0.11.28 发布：强化 ZIP 安全并升级 GraalPy 至 25.1.3](#item-18) ⭐️ 6.0/10
19. [Show HN: 18 Words——一款拼出 18 字母单词的计时文字游戏](#item-19) ⭐️ 6.0/10
20. [IERS 宣布 2026 年 12 月末不引入闰秒](#item-20) ⭐️ 6.0/10
21. [机器人领域进展迅速：IPO、新模型与更智能的机器人](#item-21) ⭐️ 6.0/10
22. [Talos-XII：用 Rust 手写自动微分和强化学习栈建模抽卡概率](#item-22) ⭐️ 6.0/10
23. [DINOv2 在细粒度分类 k-NN 检索中显著落后 SigLIP](#item-23) ⭐️ 6.0/10
24. [Meta 拟出售冗余 AI 算力，韩股暴跌](#item-24) ⭐️ 6.0/10
25. [星巴克用 AI 自研软件取代微软、IBM 和甲骨文](#item-25) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [TypeScript 7.0 发布：Go 重写带来最高 12 倍速度提升](https://devblogs.microsoft.com/typescript/announcing-typescript-7-0/) ⭐️ 9.0/10

微软发布了 TypeScript 7.0，该版本完全用 Go 语言重写，通过原生编译和并行执行实现了 8 到 12 倍的构建速度提升。用户可通过 npm 安装，支持 LSP 的编辑器可以使用新的语言服务器。 此版本大幅缩短构建时间，显著提升开发者效率，尤其针对大型代码库。原生的 Go 编译器实现了更好的性能扩展和多线程支持，为性能关键生态系统的工具链重写树立了先例。 新的 --checkers 和 --builders 参数允许自定义并行度，兼容包支持与 TypeScript 6 并存。但由于 API 尚未完善，Vue、Svelte 等嵌入式语言的工具链目前不受支持，仍需使用旧版本。

telegram · zaihuapd · 7月9日 04:01

**背景**: TypeScript 是 JavaScript 的一个强类型超集，可编译为纯 JavaScript，广泛用于大型 Web 应用。此前，TypeScript 编译器用 TypeScript/JavaScript 实现，限制了原始性能。Go 是一种编译型、静态类型语言，专为高性能和并发设计。语言服务器协议（LSP）标准化了编辑器与语言服务器之间的通信，支持自动补全和错误检查等功能。此版本包含一个利用 LSP 进行编辑器集成的新语言服务器。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Language_Server_Protocol">Language Server Protocol</a></li>
<li><a href="https://microsoft.github.io/language-server-protocol/">Official page for Language Server Protocol</a></li>

</ul>
</details>

**标签**: `#TypeScript`, `#Go`, `#release`, `#performance`, `#compiler`

---

<a id="item-2"></a>
## [尽管多数反对，欧盟议会仍通过“聊天控制 1.0”](https://www.patrick-breyer.de/en/eu-parliament-greenlights-chat-control-1-0-breyer-our-children-lose-out/) ⭐️ 8.0/10

欧盟议会批准了一项法规，允许在无搜查令的情况下扫描 Instagram 和 Gmail 等平台上的私人消息，尽管大多数欧洲议会议员投了反对票，但因反对动议未能达到所需的绝对多数而通过。 该决定允许在无司法监督的情况下大规模扫描私人通信，削弱了数百万欧盟公民的数字隐私和端到端加密，并为政府监控设立了危险的先例。 投票利用了紧急程序，需要 361 票的绝对多数才能否决；最终 314 票反对、276 票赞成、17 票弃权，动议未通过。该法规为临时性，有效期至 2028 年。公开发布的内容和云文件此前已可被扫描。

hackernews · rapnie · 7月9日 11:03 · [社区讨论](https://news.ycombinator.com/item?id=48843923)

**背景**: “聊天控制”是欧盟旨在通过扫描在线通信来打击儿童性虐待材料的一项法规。它通常依赖于客户端扫描技术，即在用户设备上、加密之前分析消息内容。隐私倡导者认为这从根本上破坏了加密并带来了安全风险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.internetsociety.org/resources/doc/2020/fact-sheet-client-side-scanning/">Fact Sheet: Client-Side Scanning - Internet Society</a></li>
<li><a href="https://www.internetsociety.org/resources/doc/2023/client-side-scanning/">Client-Side Scanning - Internet Society</a></li>

</ul>
</details>

**社区讨论**: 评论者对不民主的程序表示愤慨，指出故意在夏季休会前安排投票以及反向投票怪癖。许多人认为这是迈向极权主义和成员国推卸责任的一步，并担忧大规模监控和隐私侵蚀。

**标签**: `#privacy`, `#surveillance`, `#legislation`, `#european-union`, `#chat-control`

---

<a id="item-3"></a>
## [玻璃脊梁：美军后勤为何会在下一场战争中崩溃](https://mwi.westpoint.edu/the-glass-backbone-why-the-armys-logistics-will-break-in-the-next-war/) ⭐️ 8.0/10

现代战争研究所的最新分析指出，美军过度依赖脆弱的集中式后勤体系，可能在未来的高强度冲突中导致灾难性失败。 这一批评凸显了战略学说与实际资源分配之间的关键差距，可能影响军事准备和未来战争的胜负。 文章提出了‘玻璃脊梁’概念，形容后勤体系透明且易被击碎。它指出美军过时的‘齿尾比’低估了后勤需求，具体脆弱点包括依赖卫星通信、即时供应链和集中式枢纽。

hackernews · baud147258 · 7月9日 13:24 · [社区讨论](https://news.ycombinator.com/item?id=48845442)

**背景**: 在军事理论中，后勤（兵力和补给的调动与供应）往往决定胜败。‘齿尾比’指战斗部队（齿）与支援人员（尾）的比例，低比例表示精简。但现代战争中的远程精确武器使集中后勤显露无遗且脆弱不堪。美军现行条令偏重快速部署和技术，而非强韧的供应链。

**社区讨论**: 评论普遍承认问题存在，但对影响看法不一。一些人赞同后勤被低估，军队必须适应；另一些人则认为适应是战争的本质，太空投送或廉价无人机等新技术可能改变格局。讨论中还出现历史对比和术语争议。

**标签**: `#military`, `#logistics`, `#warfare`, `#defense`, `#strategy`

---

<a id="item-4"></a>
## [Meta 推出商业 API 版智能体 AI 模型 Muse Spark 1.1](https://ai.meta.com/blog/introducing-muse-spark-meta-model-api/) ⭐️ 8.0/10

Meta 发布了其最强大的智能体 AI 模型 Muse Spark 1.1，该模型在编码和智能体任务上有显著提升，并首次通过商业 API 向开发者开放。 此举标志着 Meta 开始通过 API 将 AI 商业化，可能将编程模型变为大众商品，挑战 OpenAI 和 Anthropic 的地位。同时，社区对基准测试透明度的质疑也引发了关于性能声明有效性的讨论。 API 定价为每百万输入 Tokens $1.25，输出 Tokens $4.5，缓存输入$0.15。但基准测试结果存在争议：Meta 在 Terminal-Bench 2.1 上被指超限使用资源以致结果无效，且在 DeepSWE 基准测试中仍落后于 GPT 5.5 和 Claude Opus 4.8。

hackernews · ot · 7月9日 14:10 · [社区讨论](https://news.ycombinator.com/item?id=48846184)

**背景**: 智能体 AI 指能自主使用工具、追求目标并在给定约束下采取行动的 AI 系统。Muse Spark 1.1 是 Meta 在构建能处理复杂多步骤问题的 AI 智能体上的最新成果，特别聚焦编码和真实世界任务。AI 基准测试对比较模型性能至关重要，但方法上的差异常导致对评测结果有效性的争议。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://techcrunch.com/2026/07/09/meta-enters-the-crowded-ai-coding-battle-with-muse-spark-1-1/">Meta enters the crowded AI coding battle with Muse Spark 1.1</a></li>
<li><a href="https://www.reuters.com/business/meta-debuts-muse-spark-11-with-preview-open-developers-2026-07-09/">Meta debuts Muse Spark 1.1 model with preview open to developers</a></li>

</ul>
</details>

**社区讨论**: 评论者大多批评 Meta 在基准测试中作弊，指出其违反 Terminal-Bench 的资源限制导致结果无效。也有人认为低价策略是商品化 AI、打击竞争对手的手段。尽管部分用户认可其可访问性和性能，但整体对宣传的优越性持怀疑态度。

**标签**: `#AI`, `#LLM`, `#Meta`, `#Agentic AI`, `#Benchmarking`

---

<a id="item-5"></a>
## [Bun JavaScript 运行时用 Rust 重写，采用智能体工程](https://simonwillison.net/2026/Jul/8/rewriting-bun-in-rust/#atom-everything) ⭐️ 8.0/10

Jarred Sumner 详细介绍了使用智能体工程将 Bun JavaScript 运行时从 Zig 重写为 Rust 的过程。通过 LLM 智能体、TypeScript 测试套件和对抗性审查，实现了内存安全的实现。 这挑战了“不应进行大规模重写”的传统观念，表明智能体工程使得这样的工作变得可行。它提高了 Bun 的可靠性和安全性，有益于 JavaScript 生态系统。 这次重写涉及 59 亿非缓存输入 token、6.9 亿输出 token，按 API 价格估算成本为 16.5 万美元。新的 Rust 版本自 6 月 17 日起已在 Claude Code 中使用，Linux 上启动速度提高了 10%。

rss · Simon Willison · 7月8日 23:57

**背景**: Bun 是一个快速的 JavaScript 运行时，最初用 Zig 编写。Zig 是一种系统编程语言，需要手动内存管理，与垃圾回收混合使用导致了内存错误。Rust 通过所有权和借用机制在编译时保证内存安全。智能体工程是指使用 LLM 驱动的智能体在人类监督下自动执行编码任务。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Bun_(software)">Bun (software) - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Zig_(programming_language)">Zig (programming language)</a></li>
<li><a href="https://simonwillison.net/guides/agentic-engineering-patterns/what-is-agentic-engineering/">What is agentic engineering? - Agentic Engineering Patterns - Simon Willison's Weblog</a></li>

</ul>
</details>

**标签**: `#Bun`, `#Rust`, `#Zig`, `#JavaScript runtime`, `#agentic engineering`

---

<a id="item-6"></a>
## [大三本科生一作实现 7.92 倍投机解码加速，获 DeepSeek 与阶跃星辰引用](https://mp.weixin.qq.com/s?__biz=MzIzNjc1NzUzMw==&mid=2247902587&idx=3&sn=879066ecce663ab9daba5d73fe2dc27b) ⭐️ 8.0/10

一位大三本科生作为第一作者提出了一种新方法，在大型语言模型推理的投机解码中实现了 7.92 倍的加速。该成果已被 AI 公司 DeepSeek 和阶跃星辰引用，显示出初步认可。 这一显著的加速效果可大幅降低实际应用中部署 LLM 的延迟和成本。来自知名 AI 公司的引用表明该方法具有实用价值，并可能影响未来的推理优化技术。 该方法解决了并行草稿阶段区块内部的因果一致性问题，这是投机解码中影响令牌接受率的一个已知挑战。技术细节尚未完全公开，但所报告的 7.92 倍加速远超通常的 2-3 倍提速。

rss · 量子位 · 7月9日 04:17

**背景**: 投机解码通过使用小型草稿模型提出多个令牌，然后由较大的目标模型并行验证，从而加速 LLM 推理。一个关键问题是保持因果一致性——确保提议的令牌不违反文本生成的自回归特性。标准的投机解码通常能实现 2-3 倍的速度提升而不损失输出质量，因此 7.92 倍的提升值得关注。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Speculative_decoding">Speculative decoding</a></li>
<li><a href="https://pytorch.org/blog/hitchhikers-guide-speculative-decoding/">A Hitchhiker’s Guide to Speculative Decoding – PyTorch</a></li>

</ul>
</details>

**标签**: `#speculative decoding`, `#LLM inference`, `#speed optimization`, `#undergraduate research`, `#natural language processing`

---

<a id="item-7"></a>
## [蚂蚁灵波开源 LingBot-Video：稀疏 MoE 13B 视频世界模型，RL 后训练](https://www.reddit.com/r/MachineLearning/comments/1ur0bxq/lingbotvideo_sparsemoe_video_diffusion/) ⭐️ 8.0/10

LingBot-Video 已开源，这是一个 13B 参数的稀疏混合专家视频扩散 Transformer，经过包含六种奖励（包括基于视觉语言模型的物理合理性奖励）的强化学习后训练，能够进行动作条件的机器人操作视频预测，并在 RBench 基准测试中取得领先结果。 通过将稀疏 MoE 的高效推理与关注物理合理性的 RL 后训练相结合，LingBot-Video 推动了机器人视频世界模型的前沿发展，有望实现无需实际部署的高效策略评估和仿真。其开源发布也将加速具身智能的研究。 模型采用单流 DiT 架构，具备 128 个 MoE 专家，通过 top-8 路由仅激活 13B 参数中的 1.4B。RL 后训练阶段使用六种奖励信号，包括 VLM 评分的物理合理性指标，并融入真实视频负样本以防止奖励黑客；然而，人们仍担忧 VLM 能否可靠评判物理，以及该模型究竟是真世界模型还是高级视频生成器。

reddit · r/MachineLearning · /u/Savings-Display5123 · 7月8日 17:58

**背景**: 稀疏混合专家（MoE）是一种高效的神经网络架构，每次输入仅激活部分专家子网络，大幅降低计算开销。视频扩散 Transformer（VDT）利用基于 Transformer 的去噪扩散过程生成时间一致的视频帧。在具身智能中，世界模型根据动作预测未来观察结果，充当规划模拟器。视觉语言模型（VLM）正越来越多地被用作自动评估器，但其评判视频中物理合理性的能力仍存争议。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Sparse_mixture-of-experts">Sparse mixture-of-experts</a></li>
<li><a href="https://arxiv.org/abs/2305.13311">[2305.13311] VDT: General-purpose Video Diffusion Transformers via Mask Modeling</a></li>
<li><a href="https://en.wikipedia.org/wiki/LLM-as-a-Judge">LLM-as-a-Judge - Wikipedia</a></li>

</ul>
</details>

**标签**: `#video generation`, `#world models`, `#mixture of experts`, `#reinforcement learning`, `#robotics`

---

<a id="item-8"></a>
## [非文本安全触发：MCP 攻击绕过 LLM 防护，成功率超半数](https://www.reddit.com/r/MachineLearning/comments/1ur1fnz/agentic_safety_triggers_arent_textual_safety/) ⭐️ 8.0/10

研究人员证明，对于具有工具访问权限（通过 MCP）的 LLM 代理，编码在工具调用序列中的攻击（而非提示文本）可以绕过最先进的安全护栏。他们发现基础模型拒绝此类攻击的比例不足 35%，即使经过安全调优的模型（如使用 SafeDPO）拒绝率也低于 48%。 这揭示了 AI 安全的一个关键盲点：当前的安全护栏专注于文本，而代理攻击利用行动层。随着 LLM 越来越多地作为具有现实工具访问权限的自主代理部署，此漏洞构成重大安全风险，可能使系统漏洞被自动利用。 该研究使用 1B 至 14B 参数的模型，并基于将已知 CVE 漏洞转化为工具调用序列来测试攻击。无训练方法提高了拒绝率但仍不足，最佳方法达到基线约三倍。代码和数据集已公开。

reddit · r/MachineLearning · /u/mlsandwich · 7月8日 18:36

**背景**: 模型上下文协议（MCP）是 Anthropic 于 2024 年推出的开放标准，用于标准化 AI 模型与外部工具和数据源的交互方式。直接偏好优化（DPO）是 2023 年的一种技术，可直接根据人类偏好对齐语言模型，无需显式奖励建模。SafeDPO 通过增加安全约束来扩展 DPO，以改进对有害请求的拒绝。这项研究基于这些技术，表明即使经过安全调优的模型在代理设置中仍易受非文本攻击。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Model_Context_Protocol">Model Context Protocol</a></li>
<li><a href="https://en.wikipedia.org/wiki/Direct_preference_optimization">Direct preference optimization</a></li>
<li><a href="https://arxiv.org/abs/2505.20065">[2505.20065] SafeDPO: A Simple Approach to Direct Preference Optimization with Enhanced Safety</a></li>

</ul>
</details>

**标签**: `#AI Safety`, `#LLM Agents`, `#Adversarial Attacks`, `#MCP`, `#Guardrails`

---

<a id="item-9"></a>
## [大疆 EV50 无人机飞越珠峰 8861 米](https://www.163.com/dy/article/L1CUCV940514R9OJ.html) ⭐️ 8.0/10

大疆尚未发布的 EV50 垂直起降无人机在“巅峰使命”珠峰科考中，于珠峰北坡飞越 8861 米高度，创下同类无人机公开测试最高升限，并获取 8000 米以上大气剖面数据。 这一成就展示了垂直起降无人机用于极端高空科学研究和货物运输的可行性，有望革新偏远山区的物流并推动大气监测。 EV50 为复合翼无人机，具备 8 个垂直升力旋翼和 3 个推进桨，可垂直起降并切换固定翼巡航；在 12 天的任务中累计完成 32 架次起降，连续爬升 3730 米，返程时仍剩 30%电量。

telegram · zaihuapd · 7月9日 06:00

**背景**: 复合翼垂直起降无人机结合了多旋翼的垂直起降能力和固定翼的高效巡航飞行，无需跑道即可在狭小区域作业并长距离飞行。飞越珠峰的高海拔飞行考验了无人机在空气稀薄、极寒条件下的电池动力和气动性能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://pandaily.com/dji-ev50-everest-vtol-cargo-drone-jul2026">DJI Unreleased EV50 VTOL Cargo Drone Flies Above Everest, Unlocking 100km Low-Altitude Logistics - Pandaily</a></li>
<li><a href="https://dronexl.co/2026/07/09/dji-ev50-evtol-delivery-drone-everest/">DJI EV50 Debuts As Company's First EVTOL Delivery Drone With A 29,072-Foot Everest Flight And No Word On When You Can Buy One</a></li>
<li><a href="https://technology.nasa.gov/patent/LAR-TOPS-293">Small Compound-Wing VTOL UAS | T2 Portal</a></li>

</ul>
</details>

**标签**: `#drones`, `#high-altitude`, `#DJI`, `#UAV`, `#scientific research`

---

<a id="item-10"></a>
## [国家超算互联网核心节点在郑州上线，提供超 10 万卡国产算力](https://36kr.com/newsflashes/3887797387344387) ⭐️ 8.0/10

2026 年 7 月 9 日，国家超算互联网核心节点在郑州正式上线运行，提供超过 10 万卡国产 AI 算力，是该平台上线以来接入的最大规模单体资源池。 此举大幅提升了中国国产 AI 算力，加强了自主可控算力基础设施的国家战略部署，对 AI 研究和产业发展具有重要意义。 该节点是国家超算互联网平台上最大的国产 AI 加速卡集中资源池，承担运营管理、资源调度等核心功能，并整合供需对接与产业孵化等综合服务。

telegram · zaihuapd · 7月9日 07:00

**背景**: 国家超算互联网是政府主导的项目，于 2024 年正式上线，旨在将全国众多超算中心连接起来，构建一体化算力网络和服务平台。国产 AI 计算卡（如华为昇腾、寒武纪等）是中国自主研发的 AI 加速硬件，用于支持人工智能训练和推理，以减少对国外技术的依赖。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.scnet.cn/home/news/59369.html">《人民日报》深度解析：为何要建设国家超算互联网？_超算互联网</a></li>
<li><a href="https://www.nsfc.gov.cn/csc_phone/kqkd29/kjyq1/67333/index.html">国家超算互联网正式上线</a></li>

</ul>
</details>

**标签**: `#supercomputing`, `#AI`, `#infrastructure`, `#China`, `#domestic-computing`

---

<a id="item-11"></a>
## [ChatGPT Work 统一 ChatGPT 和 Codex 引发用户强烈不满](https://openai.com/index/chatgpt-for-your-most-ambitious-work/) ⭐️ 7.0/10

OpenAI 发布了“ChatGPT Work”，将对话式 ChatGPT 与编程专用 Codex 合并为一个应用，导致原有聊天功能降级并引发用户困惑。 这标志着 OpenAI 战略转向企业及开发者工具，但基础聊天功能的退步凸显了盈利与用户体验之间的张力，可能使大量普通用户疏远。 统一应用中的‘ChatGPT Work’和‘ChatGPT Codex’模式功能几乎相同，普通聊天被降级为无法搜索的小弹窗，原应用被重命名为‘ChatGPT Classic’，暗示其可能被逐步淘汰。

hackernews · Tiberium · 7月9日 17:03 · [社区讨论](https://news.ycombinator.com/item?id=48849059)

**背景**: ChatGPT 是 OpenAI 广受欢迎的对话式 AI 助手，而 Codex 则是一款较新的编程智能体，旨在开发环境中自动完成软件工程任务。合并为‘ChatGPT Work’旨在将这些工具整合到一个应用中，却打乱了用户已有的使用习惯和预期。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://grokipedia.com/page/OpenAI_Codex">OpenAI Codex</a></li>

</ul>
</details>

**社区讨论**: 社区反应以负面为主，用户对功能合并感到困惑，对失去专用聊天界面表示不满。许多人认为重命名为‘ChatGPT Classic’预示着其将被淘汰，一些用户建议 OpenAI 应保留独立产品，而非强行统一导致体验下降。

**标签**: `#product launch`, `#user experience`, `#ChatGPT`, `#Codex`, `#AI tools`

---

<a id="item-12"></a>
## [腾讯开源 Hy3 混合专家模型：小体量、高性能，免费层引热议](https://hy.tencent.com/research/hy3) ⭐️ 7.0/10

腾讯发布了开源混合专家模型 Hy3，总参数量 2950 亿，激活参数 210 亿，目前在 OpenRouter 上提供免费试用，截止 7 月 21 日。 Hy3 仅激活 210 亿参数就能媲美 DeepSeek V4 Pro 等更大模型，使其成为资源受限环境的可行选择，同时其免费层和定价引发社区对比讨论。 Hy3 采用混合专家架构，总参数量 2950 亿，激活参数 210 亿，支持 256K 上下文窗口，包含 38 亿参数的 MTP 层用于推测解码，以 Apache 2.0 许可发布；OpenRouter 免费层截止 7 月 21 日。

hackernews · andai · 7月9日 15:27 · [社区讨论](https://news.ycombinator.com/item?id=48847552)

**背景**: 混合专家（MoE）模型使用多个专门的专家网络，每次只激活一部分以节省计算。OpenRouter 是一个统一 API 平台，提供数百种模型的访问和成本优化路由。DeepSeek V4 Flash 是活性参数相近的 MoE 模型，常作为小型高效模型的基准。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/tencent/Hy3">tencent/Hy3 · Hugging Face</a></li>
<li><a href="https://the-decoder.com/tencent-releases-hy3-open-source-model-that-allegedly-matches-models-up-to-five-times-its-active-size/">Tencent releases Hy3 open-source model that allegedly matches models up to five times its active size</a></li>
<li><a href="https://recipes.vllm.ai/tencent/Hy3">tencent/Hy3 | vLLM Recipes</a></li>

</ul>
</details>

**社区讨论**: 社区对 Hy3 在较小体量下展现的惊人性能感到好奇，有人将其与 DeepSeek V4 Flash 正面比较，并期待它成为本地部署的热门模型。但也有人指出其在 OpenRouter 的排名已下滑，怀疑它相比竞品是否有独特优势，尤其在定价与 DeepSeek 持平时。

**标签**: `#language-model`, `#Tencent`, `#DeepSeek`, `#pricing`, `#community-comparison`

---

<a id="item-13"></a>
## [OpenAI 推出 GPT-Live 语音升级，可委派复杂任务给 GPT-5.5](https://simonwillison.net/2026/Jul/8/introducing-gptlive/#atom-everything) ⭐️ 7.0/10

OpenAI 发布了 GPT-Live，这是 ChatGPT 的新语音模式，运行在较新的模型上，并能在后台将困难问题委派给 GPT-5.5 处理，同时保持对话流畅。 此次升级使语音交互能力大幅提升，解决了旧模型知识过时和推理能力弱的问题，可能重新激发用户对 AI 语音助手的兴趣。 之前的语音模式基于 GPT-4o 时代模型，知识截止于 2024 年。GPT-Live 使用更新的模型，并将更难的任务委派给 GPT-5.5，Simon Willison 还提到一个现已调整的模型不合时宜插嘴大笑的 bug。

rss · Simon Willison · 7月8日 23:20

**背景**: GPT-5.5 是 OpenAI 于 2026 年 4 月发布的前沿模型，专为复杂推理和代理任务设计，拥有 1,050,000 token 的上下文窗口，并在多项基准测试中表现优异。ChatGPT 先前的语音模式受限于较弱的模型，难以胜任深入对话。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openai.com/index/introducing-gpt-live/">Introducing GPT-Live | OpenAI</a></li>
<li><a href="https://en.wikipedia.org/wiki/GPT-5.5">GPT-5.5</a></li>

</ul>
</details>

**标签**: `#AI`, `#OpenAI`, `#ChatGPT`, `#Voice Assistant`, `#GPT-5.5`

---

<a id="item-14"></a>
## [Kenton Varda 禁止使用 AI 生成提交信息，因其缺乏高层上下文](https://simonwillison.net/2026/Jul/8/kenton-varda/#atom-everything) ⭐️ 7.0/10

Kenton Varda 已禁止其团队使用 AI 编写变更描述（如 PR 和提交信息），因为它们缺乏代码审查所需的高层上下文。 这一批评指出了当前生成式 AI 在软件开发中的关键局限：它能字面描述代码，但往往忽略了对维护者和审查者至关重要的宏观意图和系统级理解。 Varda 指出，AI 生成的描述专注于可见的代码细节，却省略了理解代码整体逻辑所需的关键框架，在审查时‘比无用更糟糕’。

rss · Simon Willison · 7月8日 20:03

**背景**: Kenton Varda 是一位知名软件工程师，因创建 Cap'n Proto 并领导 Cloudflare Workers 的架构而闻名。他对 AI 在代码审查中应用的看法在开发者社区中具有影响力。像 GitHub Copilot 这样的 AI 辅助编程工具越来越多地不仅生成代码，还生成文档和提交信息，引发了关于其质量及在专业工作流程中适宜性的讨论。

**标签**: `#ai-assisted-programming`, `#software-development`, `#code-review`, `#best-practices`, `#generative-ai`

---

<a id="item-15"></a>
## [IMGNet：使用滑动窗口符号模式进行面部验证](https://www.reddit.com/r/MachineLearning/comments/1urxvxh/i_built_imgnet_a_face_verification_model_that/) ⭐️ 7.0/10

一位研究人员推出了 IMGNet，这是一种面部验证模型，用滑动窗口符号模式匹配取代了传统的余弦相似度，在 LFW 上达到了 96.27%的准确率，模型大小仅为 10.58 MB，训练数据为 CASIA-WebFace。 该方法挑战了面部验证中默认使用余弦相似度的做法，表明符号模式一致性是嵌入的基本属性，并暗示相似度度量应与训练目标共同设计。 该模型采用新颖的 SW 块计算质数窗口大小下的邻居差异，并使用与幅度无关的损失函数。当应用于未经重新训练的 ArcFace 嵌入时，IMG Sign Score 在 LFW 上达到 99.58%，仅比余弦相似度低 0.24%。初步发现表明，遮挡模式可能会在嵌入维度上引起尖峰对应。

reddit · r/MachineLearning · /u/img-_- · 7月9日 18:00

**背景**: 面部验证通过比较嵌入向量来判断两张人脸图像是否属于同一个人。通常，余弦相似度衡量向量之间的角度。滑动窗口符号模式匹配通过比较嵌入中局部窗口内值的符号（正/负），捕捉关系模式而非全局方向。LFW（野外标记人脸）是面部验证的标准基准。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Facial_recognition_system">Facial recognition system - Wikipedia</a></li>
<li><a href="https://medium.com/@raveenpanditha/dsa-patterns-01-sliding-window-pattern-complete-guide-d8aaca74e266">DSA Patterns 01: Sliding Window Pattern — Complete Guide | by Raveen Panditha | Medium</a></li>
<li><a href="https://github.com/serengil/deepface">GitHub - serengil/deepface: A Lightweight Face Recognition and Facial Attribute Analysis (Age, Gender, Emotion and Race) Library for Python · GitHub</a></li>

</ul>
</details>

**标签**: `#face verification`, `#sign patterns`, `#embedding similarity`, `#deep learning`, `#ArcFace`

---

<a id="item-16"></a>
## [新防御方法将微调约束到可信 LoRA 子空间以抵御投毒攻击](https://www.reddit.com/r/MachineLearning/comments/1uq68li/what_if_a_model_could_only_learn_what_trusted/) ⭐️ 7.0/10

一篇论文提出了一种防御方法，将微调更新限制在由可信 LoRA 适配器张成的子空间中，从而使模型无法从投毒数据中学习恶意更新。 这种方法从检测转向固有限制，可能提供更鲁棒的防御，并使得从非可信数据源进行更安全的模型适配成为可能。 在 196 个公开的 LoRA 适配器上进行了测试；攻击成功率大幅下降，而有用的适配能力基本保留。专门设计用于绕过防御的自适应攻击也未成功。

reddit · r/MachineLearning · /u/Bright_Warning_8406 · 7月7日 20:00

**背景**: LoRA（低秩适配）通过添加小型可训练矩阵高效地适配预训练模型，存在大量公开的任务适配器。微调投毒是一种安全威胁，恶意数据在模型适配过程中植入后门。传统防御通常依赖于检测投毒数据，但可能被绕过。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/LoRA_(machine_learning)">LoRA (machine learning) - Wikipedia</a></li>
<li><a href="https://genai.owasp.org/llmrisk/llm04-model-denial-of-service/">LLM04:2025 Data and Model Poisoning - OWASP Gen AI Security Project</a></li>

</ul>
</details>

**标签**: `#fine-tuning`, `#security`, `#LoRA`, `#backdoor defense`, `#machine learning`

---

<a id="item-17"></a>
## [OpenAI 与美国国防部拟修订 AI 合同禁止国内监控](https://t.me/zaihuapd/42459) ⭐️ 7.0/10

OpenAI 与美国国防部已达成一致，将在双方的 AI 合作协议中增加条款，明确禁止将 AI 用于对本国公民的监控，该提议由 OpenAI 首席执行官 Sam Altman 主动发起，以回应公众担忧。 这一修订回应了外界对 AI 大规模监控的担忧，为军事 AI 合作设立了伦理界限的先例，并反映了商业 AI 技术如何融入国防领域正受到日益严格的审视。 修订后的条款明确禁止蓄意监控美国公民，以及利用商业获取的个人身份信息进行追踪，但该合同尚未正式签署。此前 Anthropic 与国防部的合作协议曾因类似争议而中止。

telegram · zaihuapd · 7月9日 13:22

**背景**: OpenAI 涉足军事合同后引发了强烈反对，外界担忧 AI 可能被武器化或用于监控。美国国防部对利用商业 AI 的兴趣日益浓厚，但公民自由组织警告其可能越权。此前 Anthropic 与国防部的合同因公众抗议而中止，凸显了此类合作的敏感性。

**标签**: `#AI ethics`, `#surveillance`, `#OpenAI`, `#Department of Defense`, `#policy`

---

<a id="item-18"></a>
## [uv 0.11.28 发布：强化 ZIP 安全并升级 GraalPy 至 25.1.3](https://github.com/astral-sh/uv/releases/tag/0.11.28) ⭐️ 6.0/10

uv 0.11.28 将其 ZIP 库 astral-async-zip 升级至 v0.0.20，其中包含 15 项针对解析器差异的加固更改，可能会拒绝格式错误或含歧义的 ZIP 压缩包。同时将 GraalPy 升级至 25.1.3，并添加了多项可用性和性能改进。 此版本通过缓解利用恶意 ZIP 文件的解析器差异攻击，增强了 Python 包安装的安全性。对于 uv 用户来说，它还带来了更清晰的错误消息、更快的执行速度以及最新的 GraalPy 运行时。 ZIP 强化针对的是解析器差异——即不同解析器对同一 ZIP 数据产生不同理解的常见攻击手段。改进包括在许多代码路径中减少内存分配，且错误消息现在会遵从 -q 和 -qq 等详细程度标志。

github · github-actions[bot] · 7月7日 23:14

**背景**: 解析器差异是指两个或多个解析器对同一输入的理解不一致，可能导致安全绕过。uv 是一个用 Rust 编写的快速 Python 包和项目管理器，它使用 astral-async-zip 库处理 ZIP 文件。GraalPy 是基于 GraalVM 构建的高性能 Python 实现，支持众多库，并在特定工作负载下比 CPython 更快。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/astral-sh/uv/releases/tag/0.11.28">Release 0.11.28 · astral-sh/uv</a></li>
<li><a href="https://about.gitlab.com/blog/how-to-exploit-parser-differentials/">How to exploit parser differentials</a></li>
<li><a href="https://graalpy.org/">GraalPy</a></li>

</ul>
</details>

**标签**: `#python`, `#package-manager`, `#security`, `#release`

---

<a id="item-19"></a>
## [Show HN: 18 Words——一款拼出 18 字母单词的计时文字游戏](https://18words.com/) ⭐️ 6.0/10

在 Show HN 上发布了一款名为 18 Words 的网页文字游戏，玩家需要在限定时间内将打乱的字母拼成一个 18 字母的单词。 它通过侧重解字谜的速度为文字游戏带来了新意，并迅速吸引了 Hacker News 社区的参与，引发了关于游戏设计功能的有建设性的反馈。 游戏设置了计时限制，未能在时间内拼出几个单词后会话便会结束。玩家已请求加入无时间压力的放松模式、字母重排按钮，以及允许完成全部 18 个单词的计分系统等功能。

hackernews · pompomsheep · 7月9日 12:48 · [社区讨论](https://news.ycombinator.com/item?id=48845049)

**背景**: Show HN 是 Hacker News 上的一个版块，用户在这里分享个人项目并获取反馈。文字游戏如字谜（Anagrams）要求玩家重新排列字母组成单词，而本游戏每轮聚焦一个 18 字母的单词，并带有倒计时机制。

**社区讨论**: 评论者欣赏游戏的设计，但对计时器看法不一：有人觉得有压力，希望加入放松模式或无限时间；另一些人提议添加字母重排功能或按单词计分以减少挫败感。创作者正积极互动，根据反馈改进游戏。

**标签**: `#word-game`, `#puzzle`, `#show-hn`, `#community-feedback`, `#game-design`

---

<a id="item-20"></a>
## [IERS 宣布 2026 年 12 月末不引入闰秒](https://datacenter.iers.org/data/latestVersion/bulletinC.txt) ⭐️ 6.0/10

国际地球自转与参考系统服务（IERS）宣布，不会在 2026 年 12 月底向协调世界时（UTC）添加闰秒。 这避免了闰秒对计算机系统、网络和软件造成的潜在干扰，特别是对于依赖 Unix 时间戳的遗留系统，确保了全球基础设施的平稳计时。 该决定基于 IERS 对地球自转的常规监测；仅当 UTC 与 UT1 的差值接近 0.9 秒时才会插入闰秒。上次闰秒发生在 2016 年 12 月 31 日。

hackernews · ChrisArchitect · 7月9日 14:16 · [社区讨论](https://news.ycombinator.com/item?id=48846281)

**背景**: 闰秒是对 UTC 的一秒调整，以使其与地球不规则的自转保持同步。自 1972 年以来已添加了 27 次闰秒，最近一次在 2016 年。许多计算机系统，尤其是使用 Unix 时间戳的系统，可能因闰秒而出现故障，因此不引入闰秒意义重大。IERS 监测地球自转并提前约六个月发布闰秒公告，以确保 UTC 与 UT1 的差值在 0.9 秒以内。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Leap_second">Leap second</a></li>
<li><a href="https://en.wikipedia.org/wiki/Unix_time">Unix time - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/IERS">IERS</a></li>

</ul>
</details>

**社区讨论**: 评论幽默与好奇兼具，有人调侃正式的前言，并开玩笑提议用喷气发动机调整地球自转。也有人询问地球自转不可预测性的原因，并对遗留系统中 Unix 时间戳的处理表示担忧。此外，还有对维护时间相关代码者的赞赏。

**标签**: `#leap second`, `#timekeeping`, `#Unix timestamp`, `#IERS`

---

<a id="item-21"></a>
## [机器人领域进展迅速：IPO、新模型与更智能的机器人](https://aiweekly.co/issues/robotics-is-moving-fast-ipos-new-models-and-smarter-robots) ⭐️ 6.0/10

三家人形机器人公司提交了 IPO 申请，Mistral 发布了专注于导航的机器人大脑，新研究显示尽管运动能力正在提升，但基础世界知识在训练中会退化。 IPO 热潮表明市场对机器人领域的强劲投资，Mistral 的模型和研究发现凸显了在创造真正智能机器人过程中的快速进展与顽固挑战。 Agility 通过 SPAC 上市估值 25 亿美元，Unitree 在上海进行 IPO，特斯拉将 Model S 生产线转为 Optimus 工厂。Mistral 的 Robostral Navigate 使用单个摄像头进行导航，研究表明模型在训练新任务时会丧失常识知识。

rss · AI Weekly · 7月9日 00:00

**背景**: 灾难性遗忘是机器学习中已知的问题，即模型在训练新任务时会忘记之前学到的知识。在机器人领域，这意味着机器人在学习运动时可能会丧失对世界的基础理解。常识知识是指所有人类知晓的日常事实，这对 AI 来说仍是一个挑战。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.thenews.com.pk/latest/1408507-mistral-launches-its-first-robotics-model-expanding-into-physical-ai">Mistral launches its first robotics model, expanding into physical AI</a></li>
<li><a href="https://en.wikipedia.org/wiki/Commonsense_knowledge_(artificial_intelligence)">Commonsense knowledge (artificial intelligence) - Wikipedia</a></li>
<li><a href="https://note.com/snake_dragon/n/n1922f4d93667?hl=en">Three Elements That Solved 'Catastrophic Forgetting' in Robots: New Design for Continual Learning Demonstrated by Sony and UT Austin Joint Research｜スネドラ</a></li>

</ul>
</details>

**标签**: `#robotics`, `#AI`, `#humanoid robots`, `#IPOs`, `#machine learning`

---

<a id="item-22"></a>
## [Talos-XII：用 Rust 手写自动微分和强化学习栈建模抽卡概率](https://www.reddit.com/r/MachineLearning/comments/1urvxgb/talosxii_handwritten_autograd_small_rlmlp_stack/) ⭐️ 6.0/10

Talos-XII 是一个 Rust 命令行工具，利用手写的自动微分引擎和定制的强化学习/多层感知器栈训练小型神经网络，以建模和优化抽卡决策，无需 PyTorch 或 ndarray 等外部框架。作者正在寻求 ARM、AVX-512 和 GPU 硬件上的基准测试帮助。 该项目在 Rust 中从零实现了核心机器学习技术，展示了该语言在高性能、无重度依赖的机器学习系统中的潜力。它可能启发在无法使用大型框架的场景中构建轻量级嵌入式强化学习应用。 系统包括 EnvNet 多层感知器、在 32 维特征上工作的神经运气优化器、用于离散动作的 Dueling DQN，以及带有 Multi-head Latent Attention 变换器的 PPO actor-critic。它使用 SIMD 调度（AVX2、AVX-512、NEON）、Rayon 并行、BF16 推理缓存，以及一个性能仍在评估中的实验性自适应缓存感知超连接（ACHF）模块。

reddit · r/MachineLearning · /u/zay0kami · 7月9日 16:52

**背景**: 自动微分（autograd）通过链式法则精确计算梯度，是神经网络训练的基础。Dueling DQN 将 Q 值估计拆分为状态价值和动作优势两个流，以改进策略学习。Multi-head Latent Attention（MLA）将键和值压缩到潜在空间，减少内存和计算量，DeepSeek-V2 即采用此技术。抽卡游戏涉及带保底计数器的随机抽取，因此概率建模并非易事。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Automatic_differentiation">Automatic differentiation</a></li>
<li><a href="https://markelsanz14.medium.com/introduction-to-reinforcement-learning-part-4-double-dqn-and-dueling-dqn-b349c9a61ea1">Introduction to Reinforcement Learning. Part 4. Double DQN and Dueling DQN</a></li>
<li><a href="https://machinelearningmastery.com/a-gentle-introduction-to-multi-head-latent-attention-mla/">A Gentle Introduction to Multi-Head Latent Attention (MLA) - MachineLearningMastery.com</a></li>

</ul>
</details>

**标签**: `#rust`, `#autograd`, `#gacha-modeling`, `#reinforcement-learning`, `#neural-networks`

---

<a id="item-23"></a>
## [DINOv2 在细粒度分类 k-NN 检索中显著落后 SigLIP](https://www.reddit.com/r/MachineLearning/comments/1uqtamz/dinov2_way_worse_than_siglip_in_knn_is_this/) ⭐️ 6.0/10

一位用户报告在细粒度汽车分类数据集上使用冻结编码器嵌入和加权 k-NN 时，SigLIP2 的准确率达到 92%，而 DINOv2 Giant 仅为 41%，差距高达 51 个百分点，令人惊讶。 这表明 DINOv2 的自监督特征并不直接适配基于余弦相似度的检索任务，为从业者在类似应用中的模型选择提供了参考。 实验使用小规模数据集（训练集 175 张，测试集 132 张），并对嵌入进行了 L2 归一化，排除了距离度量的影响。SigLIP 的对比训练天然适合 k-NN，而 DINOv2 可能需要微调或学习一个线性头才能表现良好。

reddit · r/MachineLearning · /u/psy_com · 7月8日 13:51

**背景**: DINOv2 是 Meta AI 的自监督视觉基础模型，通过知识蒸馏在无标签图像上训练，擅长密集预测任务。SigLIP 是一种类似 CLIP 的对比视觉-语言模型，但采用 sigmoid 损失，针对余弦相似度检索进行了优化。细粒度分类旨在区分非常相似的子类别，例如同一制造商的汽车型号。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2304.07193">[2304.07193] DINOv2: Learning Robust Visual Features without Supervision</a></li>
<li><a href="https://huggingface.co/docs/transformers/en/model_doc/siglip">SigLIP · Hugging Face</a></li>

</ul>
</details>

**标签**: `#machine learning`, `#computer vision`, `#representation learning`, `#model comparison`, `#fine-grained classification`

---

<a id="item-24"></a>
## [Meta 拟出售冗余 AI 算力，韩股暴跌](https://t.me/zaihuapd/42458) ⭐️ 6.0/10

Meta 计划向外部客户出售多余的 AI 算力和模型服务，同时苹果据传正在与两家中国存储芯片厂商洽谈采购。这些消息引发市场对 AI 投资放缓和产能过剩的担忧，导致 7 月 2 日韩国股市暴跌，Kospi 指数盘中一度跌 7%，三星电子和 SK 海力士跌幅均超过 8%。 此次抛售表明全球半导体市场，尤其是内存芯片制造商，对科技巨头削减 AI 资本支出的任何迹象都极为敏感。这也凸显出韩国企业面临来自中国竞争对手在存储芯片领域日益加剧的竞争压力。 暴跌期间，韩国交易所一度暂停 Kospi 期货的程序化卖出。Meta 的计划不仅包括算力，还涵盖 AI 模型服务；苹果的谈判则专门针对在中国市场销售设备使用的 NAND 闪存芯片。

telegram · zaihuapd · 7月9日 12:37

**背景**: Kospi 是韩国主要股指，三星电子和 SK 海力士等半导体巨头占较大权重，二者是全球最大的内存芯片制造商。其业务与全球科技投资紧密相关，尤其是需要大量高带宽内存（HBM）的 AI 服务器。任何 AI 基础设施投资放缓的迹象都可能迅速压低其股价。

**标签**: `#AI infrastructure`, `#Meta`, `#cloud computing`, `#market impact`, `#semiconductors`

---

<a id="item-25"></a>
## [星巴克用 AI 自研软件取代微软、IBM 和甲骨文](https://wallstreetcn.com/articles/3776584) ⭐️ 6.0/10

星巴克正借助 AI 加快内部软件开发，逐步取代长期采购的微软库存追踪系统、IBM 设备维护工具和甲骨文 Simphony POS 系统。部分替代软件预计明年底完成测试并投入使用。 此举凸显了大企业利用 AI 降低软件成本、减少对微软、IBM 和甲骨文等主要供应商依赖的趋势。星巴克每年软件支出约 4 亿美元，旨在实现总额 20 亿美元的成本削减，可能激励其他企业效仿。 星巴克每年软件支出约 4 亿美元。总额 20 亿美元的成本削减计划预计本财年企业技术部门节省约 3000 万美元，其中约 1000 万美元来自软件采购。新开发系统可能于明年底完成测试并投入使用。

telegram · zaihuapd · 7月9日 14:17

**背景**: Oracle Simphony 是领先的云 POS 系统，广泛应用于餐饮和酒店业。微软通过 Dynamics 365 等产品提供实时库存管理和供应链优化。IBM Maximo 提供基于 AI 的资产维护工具，用于设备可靠性和正常运行。这些企业平台代表了星巴克寻求内部化的重大经常性成本。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.oracle.com/food-beverage/micros/">Simphony POS Systems for Restaurants, Hospitality, and Retail | Oracle</a></li>
<li><a href="https://www.microsoft.com/en-us/dynamics-365/topics/field-service/inventory-management-system">Inventory Management System Basics | Microsoft Dynamics 365</a></li>
<li><a href="https://www.ibm.com/products/maximo">Maximo Application Suite | IBM</a></li>

</ul>
</details>

**标签**: `#AI`, `#Enterprise Software`, `#In-house Development`, `#Cost Cutting`, `#Starbucks`

---