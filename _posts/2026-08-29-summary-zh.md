---
layout: default
title: "Horizon Summary: 2026-08-29 (ZH)"
date: 2026-08-29
lang: zh
---

> 从 46 条内容中筛选出 15 条重要资讯。

---

1. [漏洞谣言：AI 代理数分钟即可发起攻击](#item-1) ⭐️ 9.0/10
2. [文章：互联网已成为成瘾性设计的“掠夺性粪坑”](#item-2) ⭐️ 8.0/10
3. [提示注入攻击以 80% 成功率突破 Claude Code Auto Mode](#item-3) ⭐️ 8.0/10
4. [仅凭一问一答检测大模型幻觉，准确率达 88%](#item-4) ⭐️ 8.0/10
5. [在 RP2350 微控制器上运行的微型 Transformer 可生成人脸图像](#item-5) ⭐️ 8.0/10
6. [百年历史的 SPC 算法击败最先进的时间序列异常检测方法](#item-6) ⭐️ 8.0/10
7. [每小时 LLM 基准分析发现日间波动是日内波动的 3 倍](#item-7) ⭐️ 8.0/10
8. [OpenAI 因 SpaceX 收购终止向 Cursor 提供模型，2026 年 11 月停服](#item-8) ⭐️ 8.0/10
9. [韩国选定 SKT、KT、Kakao 提供全民免费 AI 服务](#item-9) ⭐️ 8.0/10
10. [DHS 利用鲜为人知的关税法规监视记者与非营利组织](#item-10) ⭐️ 7.0/10
11. [三星在 Hot Chips 2026 展示存内处理架构](#item-11) ⭐️ 7.0/10
12. [CPT 暂停后，ML 博士实习对就业的重要性](#item-12) ⭐️ 6.0/10
13. [统计/概率机器学习研究者发问：顶会被 LLM 主导，论文该投哪里？](#item-13) ⭐️ 6.0/10
14. [py-evoFE：基于遗传算法的自动化特征工程库](#item-14) ⭐️ 6.0/10
15. [Claude Code 宣布周限额永久上调 25%](#item-15) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [漏洞谣言：AI 代理数分钟即可发起攻击](https://simonwillison.net/2026/Aug/28/just-a-rumour-of-a-bug/) ⭐️ 9.0/10

剑桥教授、OCaml 核心维护者 Anil Madhavapeddy 报告称，安全补丁被分享讨论后约十分钟内，他的网站就收到了针对百分号编码路径遍历序列的自动化探测。这表明 AI 编程代理正在实时监控公开仓库，仅凭一点漏洞线索就能在几乎瞬间发起漏洞利用尝试。 这标志着漏洞披露领域的根本性转变：一条漏洞谣言就足以让自动化代理找到并利用漏洞，传统的协同修复窗口被大大压缩。开源维护者正被激增的 AI 生成安全报告淹没，迫使业界重新思考漏洞保密期和 CVE 分配流程。 探测针对的是百分号编码的路径遍历序列，这是经典的目录遍历攻击模式。Madhavapeddy 在另一模型拒绝任务后改用 DeepSeek V4 Pro 完成了演示；rclone 维护者 Nick Craig-Wood 证实过去一个月收到 40 多份安全报告，而此前十年约 20 份，其中约 75%包含真实问题；GitHub 的 CVE 分配时间也从 2-3 天拖延到 3-4 周。

rss · Simon Willison · 8月28日 22:12

**背景**: 百分号编码路径遍历序列是目录遍历攻击的一种形式，攻击者利用百分号编码（如%2e%2e%2f）隐藏'..'路径段并绕过过滤器，从而可能读取 web 根目录之外的文件。AI 编程代理是基于大语言模型的工具，能够自主编写、测试和执行代码，因此既可用于软件开发，也能自动发现漏洞。开源安全实践传统上依赖保密期（embargo）：在公开披露之前，补丁会私密地分享给维护者，以便项目有时间发布修复版本；但如果 AI 代理能仅凭漏洞传闻就发起攻击，这些做法将不再可行。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Directory_traversal_attack">Directory traversal attack - Wikipedia</a></li>
<li><a href="https://owasp.org/www-community/attacks/Path_Traversal">Path Traversal | OWASP Foundation</a></li>
<li><a href="https://openrouter.ai/deepseek/deepseek-v4-pro">DeepSeek V 4 Pro 0423 - API Pricing & Benchmarks | OpenRouter</a></li>

</ul>
</details>

**社区讨论**: 在 Hacker News 的讨论中，rclone 维护者 Nick Craig-Wood 证实了这一现象：从项目前十年约 20 份安全报告，激增到近一个月 40 多份，其中约 75%值得修复。他还指出 GitHub 的 CVE 分配时间从原来的 2-3 天延长到 3-4 周，导致点版本发布时 changelog 中只能标记'CVE-PENDING'，这已成为开源社区日益严峻的痛点。

**标签**: `#AI security`, `#automated exploitation`, `#OCaml`, `#vulnerability disclosure`, `#software supply chain`

---

<a id="item-2"></a>
## [文章：互联网已成为成瘾性设计的“掠夺性粪坑”](https://www.stephendiehl.com/posts/internet_predatory_cesspit/) ⭐️ 8.0/10

Stephen Diehl 发表了一篇文章，认为互联网平台通过将针对人类心理弱点的利用工业化，已经变成了“掠夺性的粪坑”。文章特别批评了成瘾性设计、将推荐算法视为强化学习循环，以及更广泛的监控资本主义文化。 这篇文章与人们对数字福祉和平台问责制的广泛担忧产生了共鸣，并在 Hacker News 上引发了热烈讨论。它将针对推荐系统的技术批评与犬儒主义、AI 辅助写作等更广泛的社会议题联系起来，因此与当前关于科技监管的辩论密切相关。 这篇 Hacker News 帖子的评分为 8.0/10，获得 264 分和 163 条评论，显示出强烈的社区参与度。几位评论者指出，文章的部分内容疑似由 LLM 辅助撰写，这一点本身也成了与文章论点并行的讨论焦点。

hackernews · ibobev · 8月29日 18:40 · [社区讨论](https://news.ycombinator.com/item?id=49492193)

**背景**: 成瘾性设计指的是故意创造具有习惯养成性质的应用程序和界面，通常是为了最大化用户参与度和在平台上花费的时间。暗黑模式（dark patterns）指那些精心设计、诱骗用户做出本来不会采取的行动（如注册定期账单）的用户界面。监控资本主义（surveillance capitalism）这一概念由 Shoshana Zuboff 推广，描述企业为了利润而广泛收集和商品化个人数据的现象。这些概念为文章批评平台如何激励对人类心理的利用提供了背景。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Dark_pattern">Dark pattern - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Surveillance_capitalism">Surveillance capitalism - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者总体上对这篇文章进行了认真的讨论。Biologist123 分享了个人经历，称在几十年案头工作后，自己的网络成瘾变得更严重；simonebrunozzi 赞赏了文章，但指出部分内容疑似由 LLM 辅助生成。stillpointlab 反思了随着年岁增长，犬儒主义和厌世情绪如何加剧；GlibMonkeyDeath 则反驳说“旧”互联网仍然存在，只是更大的生态系统遵循其激励逻辑，将广告收入最大化。

**标签**: `#internet`, `#addiction`, `#tech-criticism`, `#social-media`, `#AI`

---

<a id="item-3"></a>
## [提示注入攻击以 80% 成功率突破 Claude Code Auto Mode](https://simonwillison.net/2026/Aug/27/breaking-claude-code-opus-5-auto-mode/) ⭐️ 8.0/10

安全研究员 Johann Rehberger 演示了一种提示注入攻击，能以约 80% 的成功率绕过 Claude Code 的 Auto Mode 保护。该攻击利用 Python 的导入优先级：Claude 被诱导解压 ZIP 压缩包，随后导入 base64 时实际加载了压缩包中恶意的本地 struct.py 文件。 这一发现直接挑战了 Anthropic 关于 Claude Code Auto Mode 的安全声明——该模式最近已成为默认权限模式。它表明编码智能体仍然容易受到对抗性输入的攻击，并提示运行无人值守智能体唯一安全的方式是放入沙箱，同时限制网络出口和凭据暴露。 该攻击的实现方式是：诱使 Claude Code 下载并解压 ZIP 压缩包，然后执行导入 base64 的代码，却未察觉压缩包中解压出的本地 struct.py 已遮蔽了标准库同名模块。在某些运行中，Auto Mode 甚至在 Claude 发现入侵后拦截了它的清理命令，使安全机制本身成为故障的一部分。

rss · Simon Willison · 8月27日 22:50

**背景**: 提示注入是一类攻击，通过精心构造的输入让大语言模型做出超出设计意图的行为，常见方式是把指令嵌入模型读取的内容（如网页或文件）中。Claude Code 是 Anthropic 推出的终端编码智能体，Auto Mode 是一种权限模式，由后台分类器代替用户为智能体做权限决策，而无需每次询问。Python 的导入机制优先加载本地目录中的模块，因此工作目录下的 struct.py 会在 base64 等模块导入 struct 时遮蔽标准库中的同名模块。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://claude.com/blog/auto-mode">Auto mode for Claude Code | Claude by Anthropic</a></li>
<li><a href="https://en.wikipedia.org/wiki/Prompt_injection_attack">Prompt injection attack</a></li>
<li><a href="https://trstringer.com/python-module-import-precedence/">Module Import Precedence in Python | Thomas Stringer</a></li>

</ul>
</details>

**标签**: `#prompt injection`, `#security`, `#AI coding agents`, `#Claude Code`, `#vulnerability`

---

<a id="item-4"></a>
## [仅凭一问一答检测大模型幻觉，准确率达 88%](https://mp.weixin.qq.com/s?__biz=MzIzNjc1NzUzMw==&mid=2247916598&idx=3&sn=d4b7937d5c43888682c10e5905020303) ⭐️ 8.0/10

研究人员提出一种用于零资源大模型幻觉检测的“类人准则探测”（HCP）机制，通过自适应的一问一答与准则加权，达到 88%的准确率。该工作发表于 ICML'26，为无需外部参考的幻觉检测建立了新基线。 这为实际部署中的大模型幻觉检测提供了一种实用且无需训练的方法，直接缓解了 AI 可靠性方面的关键障碍。同时，它为零资源幻觉检测设立了强基线，可能影响后续研究方向。 该方法属于“零资源”检测，即仅依靠模型自身的一问一答来判断真伪，无需外部文档或检索。其核心是将真实性判断自适应地分解为带权重的可解释准则，并汇总各准则得分，最终达到 88%的准确率。

rss · 量子位 · 8月29日 05:41

**背景**: 大模型幻觉指模型生成看似合理但实则错误或无依据的内容。传统的幻觉检测通常需要借助外部知识库或检索来核实陈述，但这类资源并非随时可得。零资源检测的目标是仅凭模型自身的回答判断真实性，而 HCP 机制通过让模型以类人的方式生成并加权评估准则，来实现这一目标。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2606.12900">[2606.12900] Zero-source LLM Hallucination Detection with ...</a></li>
<li><a href="https://arxiv.org/html/2606.12900v1">Zero-source LLM Hallucination Detection with Human-like ...</a></li>
<li><a href="https://openreview.net/forum?id=s4Jn6bKYGI">Zero-source LLM Hallucination Detection with Human-like ...</a></li>

</ul>
</details>

**标签**: `#LLM`, `#Hallucination Detection`, `#AI Research`, `#ICML`, `#Machine Learning`

---

<a id="item-5"></a>
## [在 RP2350 微控制器上运行的微型 Transformer 可生成人脸图像](https://www.reddit.com/r/MachineLearning/comments/1w10tax/i_implemented_a_very_tiny_image_generation_model/) ⭐️ 8.0/10

一位开发者在一颗 RP2350 微控制器上实现了一个约 240 万至 400 万参数的潜流 Transformer（latent flow transformer），可在约 20 秒内生成 128×128 的人脸图像。该模型经过 int8 量化后完全在芯片上运行，生成结果可通过显示器或 USB 输出。 这表明基于 Transformer 的图像生成不仅能在 GPU 或云服务器上运行，也能在低功耗微控制器上实现。它有望推动更高效的边缘 AI 和嵌入式机器学习方案，让生成式模型在设备端落地。 该模型是一个 12 层的潜流 Transformer，采用 AdaLN-Zero 进行条件控制，并支持无分类器引导（CFG），后者显著提升了图像质量。推理引擎通过 DMA 从闪存流式读取权重，同时计算上一层，并利用 ReLU²激活产生的稀疏性来跳过部分计算。

reddit · r/MachineLearning · /u/cpldcpu · 8月28日 19:48

**背景**: 潜流 Transformer（LFT）是一种较新的架构，它把一叠标准 Transformer 层压缩成一个通过流匹配（flow matching）训练的连续传输算子，从而大幅减少参数量。RP2350 是树莓派推出的一款低成本微控制器，这使得它成为生成式深度学习一个非常受限的运行平台。int8 量化、DMA 流式读取和激活稀疏性等技术，是在 MCU 有限的内存和算力中容纳并运行该模型的关键。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2505.14513">[2505.14513] Latent Flow Transformer - arXiv.org Latent Flow Transformer - arXiv.org GitHub - itz-sayak/Latent-Flow-Transformer Latent Flow Transformers (LFT) - emergentmind.com GitHub - mtkresearch/latent-flow-transformer Paper page - Latent Flow Transformer - Hugging Face Latent Flow Transformer (LFT) - emergentmind.com</a></li>
<li><a href="https://github.com/itz-sayak/Latent-Flow-Transformer">GitHub - itz-sayak/Latent-Flow-Transformer</a></li>
<li><a href="https://www.emergentmind.com/topics/adaptive-layer-normalization-zero-adaln-zero">Adaptive LayerNorm Zero Overview</a></li>

</ul>
</details>

**标签**: `#microcontrollers`, `#image-generation`, `#transformers`, `#quantization`, `#edge-ai`

---

<a id="item-6"></a>
## [百年历史的 SPC 算法击败最先进的时间序列异常检测方法](https://www.reddit.com/r/MachineLearning/comments/1w1wt1s/you_can_beat_sota_time_series_anomaly_detection/) ⭐️ 8.0/10

Eamonn Keogh 在 Reddit 上发帖证明，简单的统计过程控制（SPC）方法在 TSB-AD 基准测试上能够击败最先进的时间序列异常检测（TSAD）方法，在 ECG 示例上取得完美结果。他认为该基准过于简单，无法支撑关于 SOTA 进展的有意义结论。 这一发现质疑了广泛使用的基准的有效性，并暗示 TSAD 领域近年来的许多进展可能只是假象。它可能促使社区采用更难的基准，并重新审视评估方法。 帖子中引用了幻灯片和视频（例如'The TSB-AD Benchmarks are Nonsense'），并指出许多'TAO'轨迹对 SPC 来说更容易。Keogh 表示他已经完成了引入更具挑战性的 TSAD 问题 90%的工作，包括'sled dogs'和'Tuna, Fuel Cells, Smart Manufacturing'等数据集。

reddit · r/MachineLearning · /u/eamonnkeogh · 8月29日 20:16

**背景**: 时间序列异常检测（TSAD）是 NeurIPS、SIGKDD、VLDB 等会议上的热门研究领域，许多论文都在 TSB-AD 基准上进行评估。统计过程控制（SPC）是一种已有百年历史的经典质量控制方法，利用控制图来监控过程。TSB-AD 基准由 TheDatumOrg 维护，并按 VUS-PR 等指标对检测器进行排名。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/TheDatumOrg/TSB-AD">GitHub - thedatumorg/ TSB - AD : Time-Series Anomaly Detection</a></li>
<li><a href="https://thedatumorg.github.io/TSB-AD/">TSB - AD</a></li>
<li><a href="https://www.researchgate.net/publication/299422303_Self-adaptive_statistical_process_control_for_anomaly_detection_in_time_series">Self-adaptive statistical process control for anomaly detection in time series | Request PDF</a></li>

</ul>
</details>

**标签**: `#time series`, `#anomaly detection`, `#benchmarks`, `#SPC`, `#ML research`

---

<a id="item-7"></a>
## [每小时 LLM 基准分析发现日间波动是日内波动的 3 倍](https://www.reddit.com/r/MachineLearning/comments/1w1jp1j/i_analyzed_31352_hourly_llm_benchmark_scores/) ⭐️ 8.0/10

一项对 31,352 个每小时基准分数（涵盖 49 个模型标识符）的分析发现，日内波动为 2.8 分，日间波动为 8.4 分，日间波动约为日内波动的 3 倍。这一发现成为开源 LLM 持续监控系统 AIStupidLevel 的基础。 这项研究对常见的单点 LLM 评估做法提出了挑战，表明生产 API 背后的模型在几天内可能发生显著漂移。它凸显了在生产 LLM 系统中进行纵向评估和持续漂移检测的必要性，影响模型选择与可靠性监控。 该评估会执行编码任务，在隔离 Docker 环境中测试工具调用，每项任务重复五次，并使用归一化的 0-100 综合评分。该流水线将每小时分数汇总为每日中位数，并应用序贯变点检测；数据集目前已增长到 169,858 次运行和 22 个受监控模型，并检测到 Gemini 3.1 Flash Lite 的 32%持续性能下降。

reddit · r/MachineLearning · /u/ionutvi · 8月29日 11:08

**背景**: 大多数 LLM 基准测试只在单一时间点测量性能，忽略了时间稳定性。生成过程具有随机性，因此重复运行会有波动，但持续性变化可能表明模型更新或基础设施问题。AIStupidLevel 是一个采用 MIT 许可证的独立基准测试平台，持续监控模型在编码、推理、工具调用和金丝雀任务上的表现，以区分正常波动和真实漂移。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://aistupidlevel.info/">AI Benchmarks & Drift Detection 2026 | Live AI Model Rankings ...</a></li>
<li><a href="https://aistupidlevel.info/about">About AI Stupid Level | Independent AI Benchmarking</a></li>
<li><a href="https://huggingface.co/AIStupidLevel">AIStupidLevel (AI Stupid Level) - Hugging Face</a></li>

</ul>
</details>

**标签**: `#LLM`, `#benchmarks`, `#evaluation`, `#temporal stability`, `#open-source`

---

<a id="item-8"></a>
## [OpenAI 因 SpaceX 收购终止向 Cursor 提供模型，2026 年 11 月停服](https://openai.com/index/our-decision-on-cursor-following-its-acquisition-by-spacex/) ⭐️ 8.0/10

OpenAI 宣布将终止通过 Cursor 提供 OpenAI 模型的合同，建议停服日期为 2026 年 11 月 12 日。公司称原因是 SpaceX 收购 Cursor 带来的合规风险，并已给出合同允许的最大通知期。 这标志着两家知名 AI 公司之间的重大裂痕，也表明收购行为可能扰乱 AI 工具生态合作。同时凸显 OpenAI 不愿向马斯克旗下公司提供服务，将影响依赖 Cursor 中 OpenAI 模型功能的开发者。 OpenAI 表示无法确信 SpaceX 会遵守服务条款，理由是马斯克收购 Twitter 后有违约记录，且 xAI 今年早些时候在宣誓下承认违反 OpenAI 服务条款。定制协议允许 OpenAI 在控制权变更后的限时内取消合作，双方合作已近四年。

telegram · zaihuapd · 8月29日 02:24

**背景**: Cursor 是一款基于 Visual Studio Code 的 AI 优先代码编辑器，开发者可通过自然语言指令编写、调试和理解代码。Cursor 成立于 2022 年，最近估值达 293 亿美元，年经常性收入超过 30 亿美元。OpenAI 的决定源于 SpaceX 宣布收购 Cursor，也反映出 OpenAI 不与马斯克旗下公司做生意的政策。自马斯克收购 Twitter 以来，OpenAI 一直与其旗下企业保持距离，此次行动将这一立场扩展到了 AI 编程工具领域。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Cursor_(code_editor)">Cursor (code editor)</a></li>
<li><a href="https://cursor.com/">AI Coding Agent for Building Ambitious Software | Cursor</a></li>
<li><a href="https://medium.com/@tahirbalarabe2/what-is-cursor-ai-c02311d17853">What is Cursor AI?. Discover how Cursor AI is transforming… | by Tahir | Medium</a></li>

</ul>
</details>

**标签**: `#OpenAI`, `#Cursor`, `#SpaceX`, `#AI industry`, `#acquisition`

---

<a id="item-9"></a>
## [韩国选定 SKT、KT、Kakao 提供全民免费 AI 服务](https://www.koreatimes.co.kr/business/tech-science/20260828/skt-kt-kakao-consortiums-selected-for-free-ai-service-for-public) ⭐️ 8.0/10

韩国科学技术信息通信部已选定由 SK Telecom、KT 和 Kakao 牵头的三个联合体运营“AI for All”项目，为全体国民免费提供无 token 限制的国产大模型 AI 服务。9 月启动内测，预计年底前正式上线。 此举让每位公民都能免费使用 AI 服务，推动 AI 普及与数字公平，同时通过依赖国产模型强化韩国的 AI 主权。这有望为其他国家的政府 AI 服务提供范例。 政府将向联合体提供 512 块英伟达 B200 芯片，并从 2027 年起补贴全国运营成本。该服务可接入政府系统，用于预约就诊、找房和税务咨询；值得注意的是，Naver 未参与该项目。

telegram · zaihuapd · 8月29日 15:31

**背景**: “AI for All” 项目是韩国推动 AI 主权战略的一部分，旨在减少对外国 AI 服务的依赖。韩国科技部从六个竞标联合体中选出了这三个。英伟达 B200 是一款面向 AI 工作负载的高端 GPU，而 token 限制通常约束大语言模型单次请求可处理的文本量；提供无 token 限制是一项显著突破。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.chosun.com/english/industry-en/2026/08/28/BWPFM6UCCZHUZKCI2FNADVOTHQ/">SK Telecom, Kakao, KT Selected for 'AI for All' Project</a></li>
<li><a href="https://www.wsj.com/tech/ai/south-koreas-ai-for-all-push-gives-free-access-to-every-citizen-451f6b2c">South Korea’s ‘AI for All’ Push Gives Free Access to Every ...</a></li>

</ul>
</details>

**标签**: `#AI`, `#Korea`, `#Government Policy`, `#LLM`, `#Public Service`

---

<a id="item-10"></a>
## [DHS 利用鲜为人知的关税法规监视记者与非营利组织](https://www.theguardian.com/us-news/2026/aug/29/trump-dhs-1509-summons-records-journalists-nonprofits) ⭐️ 7.0/10

美国国土安全部（DHS）利用一项鲜为人知的关税法规（19 U.S.C. §1509），向记者、非营利组织和工会发出传票，索取其通讯记录。据报道，T-Mobile 遵守传票并交出六个月的电话记录，而谷歌则予以抵制；DHS 在传票受到法庭挑战后撤回了多项要求。 此事意义重大，因为它允许无证、秘密的监控，绕过了针对记者和公民社会团体的传统法律保障，可能对言论自由和维权活动形成寒蝉效应。同时，事件也表明，企业是否愿意抵制此类请求，往往决定这种监控能否得逞。 依据§1509，官员可以在没有搜查令的情况下索取记录，并常附有保密令，导致当事人事后才知情。该案中，DHS 从 T-Mobile 获取了 Fort 六个月的电话记录，涉及超过 10,000 通电话和短信；Fort 直到 7 月中旬才获知此事。此外，多份传票在法官作出裁决前就被撤回，以避免不利于政府的判例。

hackernews · firefax · 8月29日 18:44 · [社区讨论](https://news.ycombinator.com/item?id=49492219)

**背景**: 美国法典第 19 编第 1509 条是关税相关法规，授予海关与边境保护局（CBP）广泛权力，可传唤“账簿、文件、记录或其他数据”并询问证人，以执行海关法律。2017 年，DHS 督察长办公室的一份管理警告指出，CBP 曾利用此传票权要求 Twitter 提供与其批评账号相关的记录，且 CBP 此后继续将其用于非海关目的。由于该法律不要求可能的理由或独立搜查令，它成为政府机构以较少监督获取敏感记录的替代途径。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.law.cornell.edu/uscode/text/19/1509">19 U.S. Code § 1509 - Examination of books and witnesses | U.S. Code | US Law | LII / Legal Information Institute</a></li>
<li><a href="https://www.oig.dhs.gov/node/4016">Management Alert - CBP's Use of Examination and Summons ...</a></li>
<li><a href="https://docs.house.gov/meetings/JU/JU00/20260304/119001/HHRG-119-JU00-20260304-SD011-U11.pdf">Management Alert - CBP's Use of Examination and Summons ...</a></li>

</ul>
</details>

**社区讨论**: 评论者认为，DHS 是故意利用§1509 来避免法院对其合法性作出裁决，并且没有企业真正被强制要求遵守——DHS 必须上法庭才能执行，因此 T-Mobile 这类妥协的公司也应受到谴责。他们对比了 T-Mobile 的顺从与谷歌的抵制，有人建议“朋友间不用短信/彩信”。另一人惊讶地表示政府竟然还需要法律依据，还有人建议使用小平台或申请独立 IP 段，但那会暴露大量个人信息。

**标签**: `#privacy`, `#surveillance`, `#law`, `#DHS`, `#journalism`

---

<a id="item-11"></a>
## [三星在 Hot Chips 2026 展示存内处理架构](https://chipsandcheese.com/p/hot-chips-2026-samsungs-processing) ⭐️ 7.0/10

三星在 Hot Chips 2026 上展示了其存内处理（PIM）架构，将计算放在存储器内部，而非独立的 CPU 中。该方案旨在减少数据搬运，从而缓解 AI 工作负载中的主要瓶颈。 三星作为主要内存厂商推进 PIM，可能加速以内存为中心的计算在实际中的采用，尤其是在 AI 和大规模数据分析领域。如果成功，可能重塑未来加速器和内存系统的设计方式。 该方案面向以矩阵乘法为主的工作负载，但把算力放入内存要求预先确定数据位置，并且仍然需要大量片上数据搬运。类似的 PIM 概念几十年前就在早期 VLSI 文献中出现过，并非全新思想。

hackernews · ingve · 8月29日 06:06 · [社区讨论](https://news.ycombinator.com/item?id=49487341)

**背景**: 传统冯·诺依曼架构仍被大多数计算机采用，其存储器和处理器分离，数据必须通过共享总线在两者间搬运，这种带宽限制被称为“冯·诺依曼瓶颈”。存内处理（PIM）则将简单计算单元直接放入 DRAM 中，从而降低数据搬运能耗并提升内存密集型负载的性能。AI、游戏和加密常被认为是访问模式比较契合这种内存计算模型的典型应用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/In-memory_processing">In-memory processing - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Von_Neumann_bottleneck">Von Neumann bottleneck</a></li>
<li><a href="https://www.techtarget.com/whatis/definition/von-Neumann-bottleneck">What is the Von Neumann Bottleneck? - TechTarget</a></li>

</ul>
</details>

**社区讨论**: 评论者态度谨慎且怀疑：有人指出 PIM 会约束软件开发，因为数据依赖必须预先放在内存中；也有人提醒，每年展会上会出现大量类似的前沿加速器方案，最终大多没能落地。还有评论者认为，即使是矩阵乘法，数据搬运仍然是主要成本；另有人回忆，早在 1980 年前后的 VLSI 设计课程中就有“处理与存储融合”的类似想法。总体来看，大家认可这一概念，但质疑该具体实现是否实用。

**标签**: `#processing-in-memory`, `#hardware`, `#AI acceleration`, `#semiconductors`, `#Hot Chips`

---

<a id="item-12"></a>
## [CPT 暂停后，ML 博士实习对就业的重要性](https://www.reddit.com/r/MachineLearning/comments/1w19tav/how_important_is_having_an_internship_to_get_a/) ⭐️ 6.0/10

一位国际机器学习博士生在 r/MachineLearning 上发帖询问，鉴于加州大学伯克利分校、斯坦福大学和 UIUC 等顶尖美国大学已暂停 CPT，实习对获得好的行业工作有多关键。该发帖人已在 CVPR、3DV 和 ICRA 发表三篇论文，并预计在 ICCV 和 NeurIPS 再发表两篇。 这一问题反映出随着顶尖大学暂停 CPT，机器学习与计算机科学领域的国际博士生对实习机会受限的担忧日益增加。由于实习通常是通往全职工作的途径，这一政策变化可能影响高素质国际人才在 AI 行业的职业前景。 该学生专攻三维重建和高斯泼溅，拥有扎实的发表记录，这可能弥补实习经验的不足。CPT（课程实习训练）是 F-1 签证学生的工作许可，而加州大学伯克利分校、加州大学洛杉矶分校、普渡大学和北卡罗来纳大学等已暂停该计划，导致发帖人在毕业前无法实习。

reddit · r/MachineLearning · /u/Fit-Raccoon4534 · 8月29日 02:09

**背景**: CPT 允许 F-1 国际学生参加与专业直接相关的带薪或无薪校外培训，通常用于暑期实习。近期 ICE 的政策指导和审查加强导致许多大学暂停或限制 CPT，学生只能依赖毕业后的 OPT 或其他途径。实习被广泛视为获得行业研究职位的关键因素，但顶级会议上的高质量论文有时也能弥补不足。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://economictimes.indiatimes.com/nri/study/what-is-curricular-practical-training-and-what-does-the-latest-ice-memo-on-cpt-mean-a-guide-for-f-1-students/articleshow/133555868.cms">What is Curricular Practical Training and what does the latest ICE...</a></li>
<li><a href="https://www.indianeagle.com/traveldiary/us-cpt-rules-f1-students-colleges-approvals/">US Clarifies CPT Rules for F-1 Students</a></li>
<li><a href="https://www.ygunu.com/archives/26525">How International Students Can Stay in the US ... - ygunu.com</a></li>

</ul>
</details>

**标签**: `#machine learning`, `#PhD`, `#internships`, `#international students`, `#career advice`

---

<a id="item-13"></a>
## [统计/概率机器学习研究者发问：顶会被 LLM 主导，论文该投哪里？](https://www.reddit.com/r/MachineLearning/comments/1w0kipf/where_to_submit_statprob_ml_d/) ⭐️ 6.0/10

一位统计/概率机器学习研究者公开询问论文投稿去向，指出 ICLR 和 NeurIPS 等顶会被 LLM 和智能体（agentic）工作主导，并考虑将 AISTATS/UAI 作为替代选择。 这反映了主流 ML 会议与传统统计/概率 ML 子领域之间日益紧张的关系。如果这类研究者转向 AISTATS/UAI，可能会重塑这些会议的影响力和社区特色，同时也引发对顶会研究主题多样性的担忧。 作者提到了 Arnaud Doucet、Aapo Hyvärinen、Christian Naesseth、Stefano Ermon 等研究者仍在顶会发表论文，并指出 ICLR 和 NeurIPS 的 workshop 大多与智能体相关。该帖带有[D]标签，得分为 6.0，说明这是一个相关但技术新颖性不高的讨论。

reddit · r/MachineLearning · /u/didimoney · 8月28日 08:16

**背景**: AISTATS（国际人工智能与统计会议）是一个面向计算机科学、人工智能、机器学习、统计学等相关领域研究者的跨学科会议。UAI（人工智能不确定性会议）是研究不确定性下知识表示、学习和推理的顶级国际会议。Agentic AI（智能体 AI）指的是能够自主决策、采取行动并学习以实现特定目标的 AI 系统，是近期 LLM 研究的主要趋势。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://aistats.org/aistats2025/">Home| Artificial Intelligence and Statistics Conference</a></li>
<li><a href="https://www.auai.org/uai2024/">UAI 2024</a></li>
<li><a href="https://medium.com/bottutorials/ai-agents-vs-agentic-ai-whats-the-difference-and-why-does-it-matter-03159ee8c2b4">AI Agents vs Agentic AI : What’s the Difference and Why Does It Matter?</a></li>

</ul>
</details>

**标签**: `#ML conferences`, `#probabilistic ML`, `#AISTATS`, `#UAI`, `#research community`

---

<a id="item-14"></a>
## [py-evoFE：基于遗传算法的自动化特征工程库](https://www.reddit.com/r/MachineLearning/comments/1w0788j/pyevofe_automated_evolutionary_feature/) ⭐️ 6.0/10

py-evoFE v0.3.0 是一个新的开源 Python 库，利用遗传编程自动发现并组合表格数据集的特征变换。它与 scikit-learn 流水线集成，并使用 Polars 进行向量化计算。 特征工程在表格机器学习中仍然至关重要，但手动或暴力方法要么繁琐，要么产生嘈杂的高维特征空间。py-evoFE 提供了一种实用的自动化替代方案，能够发现紧凑且高影响力的特征，有望提升竞赛和生产环境中的模型性能。 该库包含 40 多种内置变换器、层级链式组合、多保真度筛选、岛屿模型并行搜索和 Caruana 集成。它实现了 fit、transform、predict 和 predict_proba 方法，因此完全兼容 sklearn 的 Pipeline 和 GridSearchCV。

reddit · r/MachineLearning · /u/tanopereira · 8月27日 21:33

**背景**: 遗传编程是一种成熟的进化算法技术，通过演化程序或表达式来优化目标任务，已有研究将其应用于自动化特征工程。许多库会预先产生数千个特征，导致过拟合和内存问题；进化方法则会施加选择压力以寻找精简的解决方案。层级链式组合允许已进化的特征成为后续世代的构建块，从而生成如比率和分组聚合等复杂变换。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/tanopereira/evoFE">GitHub - tanopereira/evoFE: Automates feature engineering ...</a></li>
<li><a href="https://link.springer.com/chapter/10.1007/978-981-96-0077-9_2">EvoFeat: Genetic Programming-Based Feature Engineering ...</a></li>
<li><a href="https://www.scribbledata.io/blog/hierarchical-features-and-their-importance-in-feature-engineering/">Role of Hierarchies in Feature Engineering - Scribble Data</a></li>

</ul>
</details>

**标签**: `#feature engineering`, `#genetic algorithms`, `#tabular ML`, `#scikit-learn`, `#Python`

---

<a id="item-15"></a>
## [Claude Code 宣布周限额永久上调 25%](https://x.com/claudedevs/status/2093742321473065266?s=46) ⭐️ 6.0/10

Anthropic 宣布，自 9 月 14 日起，Claude Code 的 Pro、Max、Team 及按席位计费的企业版标准周限额将永久上调 25%。目前的临时 50% 增幅在此之前继续有效，因此与本周相比，可用额度将下降约 17%。 这次永久上调为重度 Claude Code 用户提供了比原始限额更高的每周使用基线，尽管比临时 50% 增幅有所回落。这表明 Anthropic 正在平衡需求与容量，同时仍提供比标准计划原始额度更多的容量。 17% 的降幅是相对本周（仍包含此前 50% 临时增幅）计算得出的。永久 25% 的上调自 9 月 14 日起适用于 Pro、Max、Team 及按席位计费的企业版计费层级。

telegram · zaihuapd · 8月29日 17:06

**背景**: Claude Code 是 Anthropic 推出的智能编码工具，可在终端和 IDE 中运行，帮助开发者编辑代码、执行命令并更快交付。Anthropic 会定期调整 Claude Code 的使用限额以管理容量；2026 年 7 月初，它曾推出截止到 7 月 13 日的每周限额临时上调 50%，更早的 5 月还提高了五小时速率限制并取消了高峰时段削减。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.morphllm.com/claude-code-usage-limits">Claude Code Usage Limits (2026): Claude Pro Usage Limits , 5-Hour...</a></li>
<li><a href="https://apidog.com/blog/claude-code-weekly-limits-50-percent-increase-july-2026/">Claude Code Weekly Limits Just Jumped 50% Through July 13: What...</a></li>
<li><a href="https://claude.com/product/claude-code">Claude Code by Anthropic | AI Coding Agent, Terminal, IDE</a></li>

</ul>
</details>

**标签**: `#Claude Code`, `#pricing`, `#limits`, `#announcement`

---