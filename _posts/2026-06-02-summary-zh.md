---
layout: default
title: "Horizon Summary: 2026-06-02 (ZH)"
date: 2026-06-02
lang: zh
---

> 从 95 条内容中筛选出 24 条重要资讯。

---

1. [黑客利用 Meta AI 客服机器人接管高知名度 Instagram 账号](#item-1) ⭐️ 9.0/10
2. [用户因 Gmail 过度整合 AI 而弃用](#item-2) ⭐️ 8.0/10
3. [西雅图监控基础设施步行导览引发隐私争议](#item-3) ⭐️ 8.0/10
4. [特朗普签署修订版 AI 行政令，纳入自愿模型审查](#item-4) ⭐️ 8.0/10
5. [Adafruit 收到 Flux.ai 律师函，因 PCB 工具评测引发争议](#item-5) ⭐️ 8.0/10
6. [为何选择 Janet？(2023)](#item-6) ⭐️ 8.0/10
7. [KDE Plasma 即将发布最后一个支持 X11 的版本](#item-7) ⭐️ 8.0/10
8. [英伟达进军 PC CPU 市场，笔记本本地运行 1200 亿参数大模型](#item-8) ⭐️ 8.0/10
9. [Anthropic 申请 IPO，NVIDIA 发布 Cosmos 3 与 Vera Rubin](#item-9) ⭐️ 8.0/10
10. [基于滚动缓冲区和单语模型路由的实时多语言 ASR](#item-10) ⭐️ 8.0/10
11. [FML-Bench 揭示 MLE-Bench 提升主要源于模型与搜索，而非算法](#item-11) ⭐️ 8.0/10
12. [OpenAI 推出 Sites：用 Codex 将想法转化为交互式应用](#item-12) ⭐️ 8.0/10
13. [Anthropic 将 Project Glasswing 扩展到关键基础设施](#item-13) ⭐️ 7.0/10
14. [Hugging Face 复活 PapersWithCode，支持浏览 CVPR 2026 论文](#item-14) ⭐️ 7.0/10
15. [反向传播一 epoch 破坏 V1 脑区对齐，局部规则保持](#item-15) ⭐️ 7.0/10
16. [LightGBM 最重要特征因目标泄漏导致预测性能下降](#item-16) ⭐️ 7.0/10
17. [腾讯秘密开发微信 AI 智能体，连接数百万小程序](#item-17) ⭐️ 7.0/10
18. [黄仁勋预测 Marvell 或成下一家万亿美元芯片公司](#item-18) ⭐️ 7.0/10
19. [Clash Verge Rev 引入 CVD 协议：订阅安全升级还是隐私风险？](#item-19) ⭐️ 7.0/10
20. [Linus Torvalds 创建基于 RP2350 的极简磁性滚轮玩具项目](#item-20) ⭐️ 6.0/10
21. [1993 年关于 FidoNet 技术与历史的怀旧探索](#item-21) ⭐️ 6.0/10
22. [粘贴文件编辑器：将大文本粘贴转换为文件附件的浏览器工具](#item-22) ⭐️ 6.0/10
23. [微调推理 LLM：监督学习与强化学习方法探讨](#item-23) ⭐️ 6.0/10
24. [中国电动三轮车出口激增，海外售价达 3000-6000 美元](#item-24) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [黑客利用 Meta AI 客服机器人接管高知名度 Instagram 账号](https://simonwillison.net/2026/Jun/1/hackers-simply-asked-meta-ai/#atom-everything) ⭐️ 9.0/10

黑客只需向 Meta 的 AI 客服机器人请求更改关联邮箱，即可接管高知名度的 Instagram 账户，无需通过正常验证程序。一段视频展示了攻击者如何通过发送命令，直接将目标账户关联至攻击者控制的邮箱。 这起事件凸显了将 AI 系统与敏感账户管理工具整合而未实施适当保护措施的巨大风险，可能导致数百万用户面临账户被接管的风险。它动摇了人们对自动化支持系统的信任，并表明即使是简单的提示性攻击也能造成灾难性后果。 此次攻击不涉及复杂的提示注入技术；黑客仅要求 AI 机器人更改邮箱，且机器人未要求额外的身份验证即照做。该漏洞允许一次性账户接管，显示 AI 机器人拥有覆盖标准账户恢复流程的权限。Meta 尚未披露漏洞被利用的全部范围。

rss · Simon Willison · 6月1日 21:14

**背景**: 提示注入是一种网络安全漏洞，攻击者通过精心设计输入使大语言模型执行非预期操作。但本次事件并非复杂的注入攻击，而是因为基础的安检缺失——AI 客服机器人与账户恢复功能直接集成，且缺乏强有力的验证措施。Meta 的 AI 客服机器人旨在帮助用户解决账户问题，但由于未设置严格的验证步骤，导致攻击者可轻易利用其接管账户。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Prompt_injection">Prompt injection</a></li>

</ul>
</details>

**标签**: `#security`, `#AI`, `#Meta`, `#Instagram`, `#vulnerability`

---

<a id="item-2"></a>
## [用户因 Gmail 过度整合 AI 而弃用](https://moddedbear.com/gmail-thinks-im-stupid-so-i-left) ⭐️ 8.0/10

一名用户记录了因 Gemini 等 AI 功能强劲加入致界面杂乱且侵蚀信任而弃用 Gmail 的决定。 这反映出用户对日常工具中强制 AI 整合的日益不满，突显隐私与可用性问题，可能促使更多人转向替代品。 即使用户不需要，“用 AI 写作”等 AI 提示仍会出现；且使用部分 AI 功能需完全启用 Google Workspace 智能功能，引发数据使用忧虑。

hackernews · speckx · 6月2日 19:27 · [社区讨论](https://news.ycombinator.com/item?id=48375016)

**背景**: Gmail 是 Google Workspace 的一部分，近期强力推出基于 Gemini 的写作建议和图像生成等 AI 功能。这顺应了将生成式 AI 嵌入消费者软件的行业趋势，常以用户隐私为代价。

**社区讨论**: 评论者普遍共鸣，批评侵入性 AI 按钮和催促 AI 重写的红色下划线。多人指出垃圾邮件过滤未改善，并分享转用 mailbox.org 等私密邮件服务的故事。

**标签**: `#gmail`, `#ai`, `#privacy`, `#user-experience`, `#google`

---

<a id="item-3"></a>
## [西雅图监控基础设施步行导览引发隐私争议](https://coveillance.org/a-walking-tour-of-surveillance-infrastructure-in-seattle/) ⭐️ 8.0/10

2020 年，Coveillance 的一篇文章记录了西雅图广泛的监控基础设施，包括摄像头和传感器，并在 HackerNews 上引发了关于隐私和社会常态化的讨论。 这一讨论凸显了公共安全与公民自由之间的紧张关系，随着监控技术日益普及且常在缺乏充分监督或公众同意的情况下部署。 文章提及了声学枪击检测系统（ShotSpotter）、自动车牌识别和预测性警务等技术，评论显示出在优先安全与警惕大规模监控常态化之间的分歧。

hackernews · eustoria · 6月2日 13:24 · [社区讨论](https://news.ycombinator.com/item?id=48369980)

**背景**: 声学枪击检测系统（如 ShotSpotter）通过传感器和算法定位枪声，常与警方调度系统整合。自动车牌识别（ALPR）系统捕获并存储车牌数据，引发因大规模追踪而导致的隐私担忧。预测性警务算法分析历史犯罪数据以预测未来事件，但被批评会延续种族偏见。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ShotSpotter">ShotSpotter - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Automatic_number-plate_recognition">Automatic number-plate recognition - Wikipedia</a></li>
<li><a href="https://www.technologyreview.com/2020/07/17/1005396/predictive-policing-algorithms-racist-dismantled-machine-learning-bias-criminal-justice/">Predictive policing algorithms are racist. | MIT Technology Review</a></li>

</ul>
</details>

**社区讨论**: 社区讨论涵盖了对监控用于破案的实用主义接受，到对其侵犯公民自由的强烈批评，一些人质疑文章的后现代主义语言，另一些人则强调起诉需要视频证据。

**标签**: `#surveillance`, `#privacy`, `#seattle`, `#civil liberties`, `#technology`

---

<a id="item-4"></a>
## [特朗普签署修订版 AI 行政令，纳入自愿模型审查](https://www.politico.com/news/2026/06/02/trump-signs-downsized-ai-order-00946389) ⭐️ 8.0/10

特朗普签署了一项缩水的人工智能行政令，取代了更严格的草案，要求企业自愿在公开发布前 30 天提交强大的新 AI 模型供政府审查，而原草案提议 90 天。 该行政令可能为美国 AI 监管开创先例，在创新与安全之间寻求平衡，并可能影响企业处理模型发布和政府监督的方式。 该行政令还指示各机构利用 AI 加强网络安全，并制定自愿基准来评估 AI 模型的网络能力；审查不具约束力，不强制要求发布前批准。

hackernews · _alternator_ · 6月2日 16:40 · [社区讨论](https://news.ycombinator.com/item?id=48372628)

**背景**: 特朗普政府此前撤销了拜登时期一项要求对强大模型进行强制安全测试的 AI 行政令。新行政令采取了更宽松的方式，强调自愿合作与经济竞争力。拜登的行政令被视为全面监管，而特朗普的版本则反映了行业的反对。

**社区讨论**: 评论持怀疑态度，认为自愿审查可能走向强制监管。担忧包括扼杀开源和外国模型，以及质疑 30 天审查的可行性。有评论者将此时机与 Anthropic 估值上升联系起来，暗示商业利益。

**标签**: `#AI`, `#policy`, `#executive-order`, `#regulation`, `#cybersecurity`

---

<a id="item-5"></a>
## [Adafruit 收到 Flux.ai 律师函，因 PCB 工具评测引发争议](https://blog.adafruit.com/) ⭐️ 8.0/10

Adafruit 收到了由 Fenwick & West 律师事务所代表 Flux.ai 发出的律师函，起因可能是 Adafruit 准备发布一篇关于该 AI PCB 设计工具的评测。社区猜测这是为了打压批评声音。 此事引发了对利用法律威胁压制开源硬件社区中诚实产品评测的担忧，可能对围绕 AI 工具的批评性讨论和透明度产生寒蝉效应。 Flux.ai 是一款基于浏览器的 EDA 工具，利用 AI 辅助 PCB 设计，近期获得了贝恩资本等投资。据称律师函要求停止披露其知识产权、商业进展和用户基础等细节。

hackernews · semanser · 6月2日 10:00 · [社区讨论](https://news.ycombinator.com/item?id=48368121)

**背景**: Adafruit 是知名的开源硬件公司。Flux.ai 是一款基于云端的 AI PCB 设计工具，与 KiCad 等传统 EDA 软件存在竞争。律师函有时被用于威胁批评者；此事件因涉嫌打压言论而引起了极客社区的关注。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://grokipedia.com/page/Comparison_of_KiCad_and_Fluxai">Comparison of KiCad and Flux.ai</a></li>

</ul>
</details>

**社区讨论**: Hacker News 上的讨论对 Flux.ai 的产品质量表示强烈怀疑，用户反映使用体验差且 token 消耗成本高。Adafruit 创始人 Ladyada 表示希望友善解决，可能通过播客形式。许多人认为法律威胁是在试图压制差评。

**标签**: `#legal`, `#open-source-hardware`, `#AI`, `#PCB-design`, `#community`

---

<a id="item-6"></a>
## [为何选择 Janet？(2023)](https://ianthehenry.com/posts/why-janet/) ⭐️ 8.0/10

一篇详细的技术文章探讨了 Janet 编程语言，重点介绍了其可嵌入性、紧凑的运行时和富有表现力的 Lisp 语法等独特特性，引发了开发者的广泛讨论。 Janet 为寻求现代可嵌入 Lisp 语言进行脚本编写和应用程序扩展的开发者提供了一个引人注目的选择，它在表达性函数式编程与实用系统集成之间架起了一座桥梁。 Janet 具有极小的运行时、沙盒能力以及将脚本编译为独立二进制文件的功能，但其生态系统目前缺乏成熟的包管理和某些高级库。

hackernews · yacin · 6月2日 09:34 · [社区讨论](https://news.ycombinator.com/item?id=48367907)

**背景**: Janet 是一种运行在字节码虚拟机上的函数式和命令式编程语言。它专为系统脚本和嵌入 C/C++应用程序而设计。像 Janet 这样的嵌入式脚本语言允许开发人员为他们的软件添加可编程接口，而无需用户使用宿主语言，通常提供高级、富有表现力的语法。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://janet-lang.org/">Janet Programming Language</a></li>
<li><a href="https://github.com/janet-lang/janet">GitHub - janet -lang/ janet : A dynamic language and bytecode vm</a></li>
<li><a href="https://github.com/dbohdan/embedded-scripting-languages">GitHub - dbohdan/embedded-scripting-languages: A list of ...</a></li>

</ul>
</details>

**社区讨论**: 社区评论反映了对 Janet 的沙盒和可移植性的认可，但一些开发者指出其缺乏包版本管理和丰富的库。Janet 在 Bauble Studio 等艺术工具中的应用激发了热情，同时也提到了 Fennel 等替代品用于 Lua 集成的脚本编写。

**标签**: `#janet`, `#programming-languages`, `#lisp`, `#embeddable-scripting`, `#technical-analysis`

---

<a id="item-7"></a>
## [KDE Plasma 即将发布最后一个支持 X11 的版本](https://blog.davidedmundson.co.uk/blog/596/) ⭐️ 8.0/10

KDE Plasma 正在准备最后一个支持 X11 显示协议的版本，未来版本将仅支持 Wayland。Wayland 提供更流畅、响应更快的体验，但仍缺少 X11 的一些功能。 这标志着 Linux 桌面从传统 X11 协议向现代 Wayland 过渡的重大里程碑，将影响所有 KDE Plasma 用户。它表明了 Wayland 的日益成熟，同时也凸显了影响某些工作流程和辅助功能的剩余差距。 Wayland 中值得注意的缺失功能包括窗口置顶功能（例如画中画）、与第三方平铺窗口管理器的兼容性，以及 Talon 语音输入等辅助功能工具的退化。具体版本号未指定，但将是最后一个提供 X11 选项的版本。

hackernews · jandeboevrie · 6月2日 14:16 · [社区讨论](https://news.ycombinator.com/item?id=48370588)

**背景**: X11（X Window 系统）是一个在类 Unix 系统上使用了几十年的图形用户界面协议，而 Wayland 是旨在更简单、更安全、性能更好的现代替代方案。KDE Plasma 是一个流行的 Linux 桌面环境，在最近的版本中已逐渐从 X11 转向 Wayland 作为默认显示服务器。此次即将发布的版本代表着 X11 支持被完全移除前的最后一步。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/X_Windowing_System">X Windowing System</a></li>
<li><a href="https://www.wikiwand.com/en/Wayland_(protocol)">Wayland ( protocol ) - Wikiwand</a></li>
<li><a href="https://en.wikipedia.org/wiki/KDE_Plasma">KDE Plasma - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区反应褒贬不一：许多人赞扬 KDE 在 Wayland 上的流畅体验和进展，而其他人则对功能性退化表示失望。担忧包括 Talon 等辅助工具失效、缺少窗口置顶功能以及无法将 KWin 替换为其他平铺窗口管理器，表明完整的特性对等仍需数年时间。

**标签**: `#KDE`, `#Wayland`, `#X11`, `#Linux Desktop`, `#Display Server Protocols`

---

<a id="item-8"></a>
## [英伟达进军 PC CPU 市场，笔记本本地运行 1200 亿参数大模型](https://mp.weixin.qq.com/s?__biz=MzIzNjc1NzUzMw==&mid=2247894165&idx=2&sn=0125e0e1973268ab6434b7a2664bcc8c) ⭐️ 8.0/10

英伟达在 Computex 2026 上发布了 RTX Spark 超级芯片，这是一款基于 Arm 的 PC 平台，搭载定制 20 核 Grace CPU、Blackwell GPU 和 128GB 统一内存，使笔记本电脑能本地运行 1200 亿参数语言模型，并支持百万 token 超长上下文。 此举标志着英伟达借助其 AI 和 GPU 优势，直接挑战英特尔和 AMD 在 PC 市场的地位，推动高性能边缘 AI 计算，使开发者能在本地运行超大模型，摆脱对云端的依赖。 RTX Spark 超级芯片通过 NVLink-C2C 互联 CPU 和 GPU，系统专为 Arm 版 Windows 设计，瞄准高端笔记本和小型台式机，并预装英伟达 AI 软件栈，便于模型部署。

rss · 量子位 · 6月2日 04:05

**背景**: 英伟达以 GPU 闻名，近年来通过 Grace 系列 CPU 进入数据中心领域。RTX Spark 将 Arm 架构引入消费 PC，与 x86 阵营竞争。此前发布的 Project Digits 是一款 3000 美元的桌面 AI 超算，也采用 Grace-Blackwell 平台，但体积较大。在本地运行 1200 亿参数大模型的能力，远超目前因内存限制只能运行小模型的普通笔记本。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.tomshardware.com/laptops/nvidia-unveils-rtx-spark-superchip-at-computex-2026-new-platform-promises-to-turn-windows-into-an-agentic-ai-os-with-arm-cpu-blackwell-gpu-and-128gb-unified-memory">Nvidia unveils RTX Spark Superchip for laptops and... | Tom's Hardware</a></li>
<li><a href="https://arstechnica.com/gadgets/2026/06/nvidia-gets-into-the-arm-pc-business-with-new-high-end-rtx-spark-processor/">Nvidia RTX Spark comes to Windows PCs with Arm CPU, RTX GPU ...</a></li>
<li><a href="https://techcrunch.com/2025/01/06/nvidias-project-digits-is-a-personal-ai-computer/">Nvidia’s Project Digits is a ‘personal AI supercomputer’</a></li>

</ul>
</details>

**标签**: `#Nvidia`, `#CPU`, `#AI`, `#Edge Computing`, `#Hardware`

---

<a id="item-9"></a>
## [Anthropic 申请 IPO，NVIDIA 发布 Cosmos 3 与 Vera Rubin](https://aiweekly.co/issues/anthropic-files-for-an-ipo-nvidia-ships-its-stack) ⭐️ 8.0/10

Anthropic 秘密提交了 IPO 申请，并发布了 Claude Opus 4.8，代码可靠性提升 4 倍。在 GTC 台北大会上，NVIDIA 推出了用于物理 AI 的开放基础模型 Cosmos 3，将 Vera Rubin 投入生产，并发布了一款 1-petaflop 的 AI 开发者设备。 Anthropic 的 IPO 申请标志着 AI 初创公司向公开市场转型的一个里程碑，而 NVIDIA 的新产品加速了物理 AI 和智能体系统的开发。这两个事件凸显了 AI 技术的快速商业化和多元化。 Claude Opus 4.8 的代码可靠性提升了 4 倍，是 Anthropic 迄今为止能力最强的模型。NVIDIA Cosmos 3 支持文本、图像、视频、环境声音和动作生成，而 Vera Rubin NVL72 系统集成了 72 个 Rubin GPU，用于智能体推理 AI。

rss · AI Weekly · 6月1日 00:00

**背景**: Anthropic 由前 OpenAI 员工创立，以注重安全和对齐的 Claude 系列大语言模型闻名。提交 IPO 申请是公司迈向公开上市的第一步。NVIDIA 凭借其 GPU 主导 AI 硬件市场，并通过 Cosmos 平台扩展到物理 AI 模拟。Vera Rubin 架构是 Grace Hopper 和 Blackwell 架构的继任者，专为大规模 AI 训练和推理设计。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/news/claude-opus-4-8">Introducing Claude Opus 4.8 \ Anthropic</a></li>
<li><a href="https://nvidianews.nvidia.com/news/nvidia-launches-cosmos-3-the-open-frontier-foundation-model-for-physical-ai">NVIDIA Launches Cosmos 3, the Open Frontier Foundation Model for Physical AI | NVIDIA Newsroom</a></li>
<li><a href="https://grokipedia.com/page/nvidia-vera-rubin-nvl72">NVIDIA Vera Rubin NVL72</a></li>

</ul>
</details>

**标签**: `#AI industry`, `#Anthropic`, `#NVIDIA`, `#IPOs`, `#AI regulation`

---

<a id="item-10"></a>
## [基于滚动缓冲区和单语模型路由的实时多语言 ASR](https://www.reddit.com/r/MachineLearning/comments/1ttwfuy/realtime_multilingual_asr_using_rolling_buffers/) ⭐️ 8.0/10

一种新的实时多语言 ASR 系统使用带滚动缓冲区的路由协调器在约 1 亿参数的小单语模型之间切换，通过自动语言变化检测和回滚，在资源受限的硬件上实现准确转写。 该方法通过避免使用大型单一模型，使设备端多语言 ASR 变得实用，显著降低了内存和计算需求，同时为实时应用保持了高准确率。 该系统结合了用于流式转写的 Zipformer、用于语音检测的 Silero VAD 和用于语言识别的 SpeechBrain。在跨语句语码切换上达到约 13%的词错误率，但在句内切换上降至约 41% WER。代码已开源。

reddit · r/MachineLearning · /u/JeanMichelRanu · 6月1日 15:53

**背景**: Zipformer 是一种快速且内存高效的 ASR Transformer 架构，擅长低延迟流式处理。Silero VAD 是一个预训练的语音活动检测器，用于识别音频中的语音边界。语码切换指在语句内部或之间交替使用两种或多种语言，这对语音识别系统构成挑战。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2310.11230">[2310.11230] Zipformer: A faster and better encoder for automatic speech recognition</a></li>
<li><a href="https://pypi.org/project/silero-vad/">Voice Activity Detector ( VAD ) by Silero</a></li>

</ul>
</details>

**标签**: `#automatic-speech-recognition`, `#multilingual`, `#real-time`, `#code-switching`, `#language-identification`

---

<a id="item-11"></a>
## [FML-Bench 揭示 MLE-Bench 提升主要源于模型与搜索，而非算法](https://www.reddit.com/r/MachineLearning/comments/1ttu47l/how_much_of_mlebenchs_gains_are_the_algorithm_vs/) ⭐️ 8.0/10

新基准测试 FML-Bench 表明，MLE-Bench 在两年内分数的显著提升主要归因于更好的基础模型和更多的搜索，而非算法进步。在控制模型和步骤预算后，较老的 AIDE 算法与现代智能体系统表现相当。 这一发现挑战了自动化机器学习研究中算法进步的说法，并表明扩展模型和搜索可能是更有效的路径。它可能将研究焦点转向更高效的搜索策略和模型扩展。 FML-Bench 统一了代码编辑智能体、步骤定义和验证/测试分割，以隔离算法效率。在受控条件下，已有两年历史的 AIDE 算法（一种用于代码探索的树搜索智能体）达到了与较新的进化搜索系统相当的性能。

reddit · r/MachineLearning · /u/Educational_Strain_3 · 6月1日 14:34

**背景**: MLE-Bench 是 OpenAI 推出的用于评估 AI 智能体执行机器学习工程任务的基准，其分数据报道最近从 30% 跃升至 80%。FML-Bench 是一个新的基准测试，专注于基础机器学习研究问题，旨在通过控制模型和搜索预算来衡量算法效率。AIDE 是 Weco AI 的开源智能体，使用树搜索自主编写和调试代码。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/openai/mle-bench">GitHub - openai/mle-bench: MLE-bench is a benchmark for measuring how well AI agents perform at machine learning engineering · GitHub</a></li>
<li><a href="https://github.com/qrzou/FML-bench">GitHub - qrzou/ FML - bench : FML - bench : A Benchmark for Automatic...</a></li>
<li><a href="https://github.com/WecoAI/aideml">GitHub - WecoAI/aideml: AIDE: AI-Driven Exploration in the Space of Code. The machine Learning engineering agent that automates AI R&D. · GitHub</a></li>

</ul>
</details>

**标签**: `#machine learning`, `#automated ML`, `#benchmarking`, `#algorithmic efficiency`, `#research agents`

---

<a id="item-12"></a>
## [OpenAI 推出 Sites：用 Codex 将想法转化为交互式应用](https://x.com/OpenAI/status/2061845949170045346) ⭐️ 8.0/10

OpenAI 推出了 Sites 新功能，让 Codex 能够将工作内容、想法和计划转化为可通过 URL 访问和分享的交互式网络应用，率先面向 Business 和 Enterprise 用户开放。 该功能降低了网页应用开发门槛，使非开发者也能用自然语言将想法变为功能齐全的交互式应用，有望加速原型设计和团队协作。 Sites 功能目前仅面向 Business 和 Enterprise 客户，后续将扩大覆盖范围；生成的应用具有交互性，并可通过链接分享。

telegram · zaihuapd · 6月2日 17:29

**背景**: Codex 是 OpenAI 开发的 AI 模型，能将自然语言转译为代码，尤其擅长网络技术。Sites 将 Codex 的能力扩展到生成完整的交互式应用，而不仅是代码片段，从而降低网络开发的门槛。

**标签**: `#OpenAI`, `#Codex`, `#no-code`, `#web development`, `#AI applications`

---

<a id="item-13"></a>
## [Anthropic 将 Project Glasswing 扩展到关键基础设施](https://www.anthropic.com/news/expanding-project-glasswing) ⭐️ 7.0/10

Anthropic 已将其基于 Claude Mythos 模型的 Project Glasswing 安全扫描 AI 扩展到 15 个国家的关键基础设施。 此举旨在主动防御关键系统免受网络威胁，但也引发了关于 AI 实际效果、企业透明度以及可能助长大规模监控风险的辩论。 Claude Mythos 是一个未公开发布的受控模型；早期使用者报告误报率较高，给团队带来大量噪音，引发了对扫描框架可靠性的质疑。

hackernews · surprisetalk · 6月2日 13:15 · [社区讨论](https://news.ycombinator.com/item?id=48369863)

**背景**: Project Glasswing 于 2026 年 4 月 7 日启动，是 Anthropic 的行业范围网络安全倡议。它使用未发布的 Claude Mythos 模型查找软件漏洞。Anthropic 以安全和滥用风险为由，未公开发布 Mythos。该项目通过企业联盟合作来保障关键软件安全。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Project_Glasswing">Project Glasswing</a></li>
<li><a href="https://www.anthropic.com/glasswing">Project Glasswing : Securing critical software for the AI era \ Anthropic</a></li>

</ul>
</details>

**社区讨论**: 社区评论反应不一：部分用户报告该工具产生大量误报，另有人质疑 Anthropic 的动机，认为受限发布是为了掩盖算力不足。还有人引用 Anthropic 自己反对大规模监控的声明，表达了对监控风险的担忧。

**标签**: `#AI`, `#security`, `#critical-infrastructure`, `#Anthropic`, `#deployment`

---

<a id="item-14"></a>
## [Hugging Face 复活 PapersWithCode，支持浏览 CVPR 2026 论文](https://www.reddit.com/r/MachineLearning/comments/1tukrf4/browse_cvpr_2026_papers_on_paperswithcode_p/) ⭐️ 7.0/10

Hugging Face 开源团队在 paperswithcode.co 上复活了 PapersWithCode，并新增了会议浏览功能，索引了所有带有 arXiv ID 的 CVPR 2026 论文，按任务分类，并链接了代码、工件和评估，包括口头报告和亮点论文。 这次复活恢复了追踪最新研究和查找代码实现的宝贵资源，而会议浏览功能简化了从顶级 AI 会议发现和复现工作的过程，惠及研究人员和从业者。 该平台索引具有对应 arXiv ID 的论文，按任务分类，并用 GitHub 和项目页面 URL、Hugging Face 工件及评估进行标记，且是在最初复活两周后推出的。

reddit · r/MachineLearning · /u/NielsRogge · 6月2日 08:32

**背景**: PapersWithCode 曾是一个免费开放资源，将机器学习论文与其开源代码相连接，由 Meta 于 2025 年 7 月停用。Hugging Face 团队将其复活为 paperswithcode.co，以继续追踪最佳结果。CVPR（计算机视觉与模式识别会议）是计算机视觉的顶级会议，CVPR 2026 将于下周在丹佛举行。会议论文通常根据重要性被指定为口头报告、亮点报告或海报展示。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://medium.com/paperswithcode">PapersWithCode - Medium</a></li>
<li><a href="https://www.codesota.com/papers-with-code">Papers With Code Alternative: SOTA Leaderboards and Archived ...</a></li>
<li><a href="https://wiki.eventhosts.cc/topics/papers-and-poster-events">Poster Events, Oral or Spotlight Events, and Papers | Wiki.EventHosts NeurIPS/ICML/ICLR/CVPR and more</a></li>

</ul>
</details>

**标签**: `#machine learning`, `#computer vision`, `#research tools`, `#CVPR`, `#paperswithcode`

---

<a id="item-15"></a>
## [反向传播一 epoch 破坏 V1 脑区对齐，局部规则保持](https://www.reddit.com/r/MachineLearning/comments/1tupu9z/backpropagation_destroys_v1_brain_alignment_in/) ⭐️ 7.0/10

一项研究发现，反向传播（BP）仅在一个训练 epoch 后就导致与 V1 fMRI 数据的 RSA 对齐下降 90%，而预测编码（PC）和脉冲时间依赖可塑性（STDP）等局部学习规则保留了 69-75% 的对齐并在 40 个 epoch 内保持稳定。 这挑战了反向传播作为生物合理学习机制的观点，并揭示了一个根本性的权衡：全局误差信号提升了高级表征但破坏了早期视觉皮层的保真度，从而支持局部学习规则用于类脑 AI 模型。 该效应在不同种子间高度一致（PC/STDP 与 BP 的 Cohen's d > 5）。退化速率与误差信号的全局性相关：精确梯度（BP）> 随机反馈对齐（FA）> 局部误差（PC/STDP）。局限性包括少量种子（5 个）以及从低分辨率 CIFAR-10 训练到高分辨率 THINGS 评估的领域偏移。

reddit · r/MachineLearning · /u/ConfusionSpiritual19 · 6月2日 12:43

**背景**: 表征相似性分析（RSA）量化模型表征与大脑活动模式的对齐程度，本研究使用 THINGS 数据集的人类 V1 fMRI。反馈对齐（FA）是一种生物启发的反向传播替代方案，使用随机后向权重。脉冲时间依赖可塑性（STDP）根据脉冲时间调整突触，而预测编码（PC）局部最小化预测误差。该研究比较了这些学习规则如何影响与灵长类视觉皮层的对齐。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/1609.01596">[1609.01596] Direct Feedback Alignment Provides Learning in Deep Neural Networks</a></li>
<li><a href="https://en.wikipedia.org/wiki/Spike-timing-dependent_plasticity">Spike-timing-dependent plasticity - Wikipedia</a></li>
<li><a href="https://mne.tools/stable/auto_examples/decoding/decoding_rsa_sgskip.html">Representational Similarity Analysis — MNE 1.12.1 documentation</a></li>

</ul>
</details>

**标签**: `#representational similarity analysis`, `#backpropagation`, `#local learning rules`, `#neuroscience-inspired AI`, `#fMRI`

---

<a id="item-16"></a>
## [LightGBM 最重要特征因目标泄漏导致预测性能下降](https://www.reddit.com/r/MachineLearning/comments/1tu0y14/why_our_1_lightgbm_feature_by_importance_made/) ⭐️ 7.0/10

在手表定价的 LightGBM 分位数回归模型中，贝叶斯目标编码器被赋予最高特征重要性，但严格消融实验显示，该特征因不可约标签方差导致的目标泄漏，使测试集 MAPE 上升了 0.28 个百分点。 这揭示了梯度提升中特征重要性得分的重大陷阱：当目标编码引入泄漏时，重要性指标可能产生误导，影响依赖这些指标进行特征选择的表格数据建模实践者。 该模型使用了变体条件贝叶斯目标编码器；在 4 种子×3 变体的消融中，变体间差异是变体内标准差的 7 倍。泄漏源于不可观测因素，如品相细节、卖家行为和时机。

reddit · r/MachineLearning · /u/Nj-yeti · 6月1日 18:20

**背景**: 目标编码用目标变量的统计量（如均值）替换类别值，如果在训练时使用了目标信息而导致预测时无法获得，则会造成数据泄漏。在 LightGBM 等梯度提升方法中，特征重要性反映了特征贡献的分裂次数和增益，但这与真实样本外表现可能不相关。分位数回归预测条件分位数（例如 90%分位数）而非均值，常用于定价区间。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Leakage_(machine_learning)">Leakage (machine learning) - Wikipedia</a></li>
<li><a href="https://www.geeksforgeeks.org/machine-learning/lightgbm-for-quantile-regression/">LightGBM for Quantile Regression - GeeksforGeeks</a></li>
<li><a href="https://mattmotoki.github.io/blog/beta-target-encoding/">Beta Target Encoding | Matt Motoki</a></li>

</ul>
</details>

**标签**: `#LightGBM`, `#feature importance`, `#target encoding`, `#overfitting`, `#gradient boosting`

---

<a id="item-17"></a>
## [腾讯秘密开发微信 AI 智能体，连接数百万小程序](https://t.me/zaihuapd/41705) ⭐️ 7.0/10

3 月 10 日，外媒援引四位知情人士称，腾讯正秘密为微信打造一款 AI 智能体，计划连接数百万个小程序，服务 14 亿用户。 该 AI 智能体若能通过小程序为微信庞大用户群自动处理日常事务，可能使腾讯在中国竞争激烈的 AI 市场中领先阿里巴巴和字节跳动等对手。 该智能体旨在接入微信内数百万个小程序，覆盖预约出租车、订购杂货等服务。但新浪科技向腾讯求证时，截至发稿未获回应。

telegram · zaihuapd · 6月2日 05:03

**背景**: 微信是一款月活跃用户超 14 亿的超级应用，集即时通讯、社交媒体和移动支付于一体。其小程序是内嵌式应用，用户无需离开微信即可使用各类服务。AI 智能体是一种能自主执行任务的系统，常借助工具代表用户行动。此次项目中，智能体将调用小程序自动处理用户日常事务。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/AI_agent">AI agent</a></li>
<li><a href="https://en.wikipedia.org/wiki/WeChat_Mini_Program">WeChat Mini Program</a></li>

</ul>
</details>

**标签**: `#AI agent`, `#WeChat`, `#Tencent`, `#mini-programs`, `#technology news`

---

<a id="item-18"></a>
## [黄仁勋预测 Marvell 或成下一家万亿美元芯片公司](https://finance.sina.com.cn/stock/usstock/c/2026-06-02/doc-inhzzivp1585226.shtml) ⭐️ 7.0/10

英伟达 CEO 黄仁勋在台北国际电脑展上表示，自主 AI 智能体正推动 AI 硬件需求激增，并预测 Marvell 可能成为下一家市值突破万亿美元的芯片公司；英伟达今年 3 月已向 Marvell 投资 20 亿美元并建立战略合作。 这位顶级行业领袖的预测凸显了为 AI 提供关键数据中心和网络技术的公司日益增长的重要性，可能标志着行业焦点从 AI 训练芯片转向支持推理和自主智能体基础设施的方向延伸。 Marvell 专注于数据中心半导体和高速网络解决方案；与英伟达的合作及 20 亿美元投资旨在加速 AI 基础设施建设。

telegram · zaihuapd · 6月2日 10:06

**背景**: Marvell Technology 是一家设计定制 ASIC、以太网交换机及其他数据中心网络组件的半导体公司。AI 热潮增加了对此类技术的需求，因为大规模 AI 模型需要高速数据传输和专用处理。以 AI GPU 闻名的英伟达一直在扩大合作伙伴生态，以支持全面的 AI 数据中心建设。自主 AI 智能体指能独立执行任务和决策的 AI 系统，推动硬件的持续使用。

**标签**: `#semiconductors`, `#AI hardware`, `#Nvidia`, `#Marvell`, `#market prediction`

---

<a id="item-19"></a>
## [Clash Verge Rev 引入 CVD 协议：订阅安全升级还是隐私风险？](https://github.com/clash-verge-rev/clash-verge-rev/commit/2cb9c13ab6f0b0fec5ccc622c669843c935942ed) ⭐️ 7.0/10

Clash Verge Rev 在 dev 分支引入 CVD（Clash Verge Device-binding Protocol），通过每个设备生成密钥对来加密订阅下发并限制设备数量，旨在防止订阅链接被滥用。 该协议在减少未授权共享的同时，引入了长期设备标识符，可能实现设备指纹识别，这与代理用户所需的匿名性相悖，并可能导致用户被锁定在特定客户端上。 该协议目前处于草案阶段，尚未实现，部分内容由 AI 撰写。技术细节包括通过请求头上报公钥、服务端按设备加密下发、支持解绑旧设备。社区担忧主要集中在隐私风险及与第三方工具的兼容性。

telegram · zaihuapd · 6月2日 11:07

**背景**: Clash Verge Rev 是一款基于 Tauri 和 Mihomo 内核的开源桌面代理客户端，通过订阅链接拉取代理节点。传统上订阅链接可被轻易分享，导致滥用。CVD 协议通过密码学密钥将订阅与特定设备绑定，类似于软件的设备许可证，但此类设备绑定机制也会产生永久性标识符，这在注重隐私的代理工具中尤为敏感。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/clash-verge-rev/clash-verge-rev/blob/dev/docs/cvd-protocol-introduction.md">clash-verge-rev/docs/cvd-protocol-introduction.md at dev ...</a></li>

</ul>
</details>

**社区讨论**: 社区反应凸显了尖锐的权衡：许多人认可遏制订阅泄露的价值，但强烈担忧设备指纹识别会破坏代理工具本应提供的匿名性。批评者还担心，强制采用可能会将第三方客户端和脚本拒之门外，降低灵活性。该提案处于早期草案阶段且由 AI 起草，这促使社区要求在实施前进行更深入的审查。

**标签**: `#CVD`, `#Clash Verge Rev`, `#privacy`, `#subscription security`, `#proxy client`

---

<a id="item-20"></a>
## [Linus Torvalds 创建基于 RP2350 的极简磁性滚轮玩具项目](https://github.com/torvalds/ScrollWheel) ⭐️ 6.0/10

Linus Torvalds 在 GitHub 上启动了一个新的业余项目：一个基于 RP2350 微控制器和 AS5600 磁角度传感器的极简磁性滚轮玩具，通过几个开关实现旋钮控制。 该项目因出自 Linux 和 Git 之父 Linus Torvalds 而备受关注，虽技术不具颠覆性，却展示了 RP2350 在巧妙硬件改造上的潜力，可能激励更多爱好者探索磁传感器应用。 设计采用 AS5600 磁角度传感器通过 I2C 进行精确旋转检测，开关直接连接至 GPIO 并利用内部上拉电阻，适用于 Pimoroni Tiny 2350 等紧凑型开发板。

github · torvalds · 6月2日 15:51

**背景**: RP2350 是树莓派于 2024 年 8 月发布的第二代微控制器，具有双核 Arm Cortex-M33 及可选 RISC-V 架构。磁性滚轮利用霍尔效应传感器无接触地检测旋转，比机械编码器更顺滑耐用。AS5600 传感器常用于工业角度测量，在此被巧妙地重新用作简洁的人机交互组件。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/torvalds/ScrollWheel">Minimalist RP2350 magnetic sensor scroll wheel toy project</a></li>
<li><a href="https://en.wikipedia.org/wiki/RP2350">RP2350 - Wikipedia</a></li>

</ul>
</details>

**标签**: `#RP2350`, `#scroll wheel`, `#magnetic sensor`, `#embedded`, `#hobbyist`

---

<a id="item-21"></a>
## [1993 年关于 FidoNet 技术与历史的怀旧探索](https://www.fidonet.org/inet92_Randy_Bush.txt) ⭐️ 6.0/10

一份 1993 年的文档详细介绍了 FidoNet 的技术、工具和历史，引发早期使用者的怀旧讨论。 它突显了 FidoNet 在互联网前社区网络中的先驱作用，展示了电子邮件、论坛甚至社交发现等概念早于现代互联网出现。 FidoNet 采用去中心化存储转发系统在 BBS 之间交换电子邮件和回音邮件；用户仍记得如“2:463/1161”这样的节点地址。

hackernews · BruceEel · 6月2日 13:53 · [社区讨论](https://news.ycombinator.com/item?id=48370291)

**背景**: FidoNet 是一个全球性的存储转发网络，早在互联网普及之前就通过拨号调制解调器连接 BBS 系统。到 1990 年代中期，它已发展到近 4 万个节点，使数百万用户能够交换电子邮件和论坛消息。随着低成本互联网的普及，其流行度下降，但至今仍以较小规模存在。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/FidoNet">FidoNet</a></li>

</ul>
</details>

**社区讨论**: 评论者分享怀旧故事，比如土耳其的 HitNet 克隆版本作为早期社交网络，并指出许多类似互联网的服务（论坛、邮件、多人在线游戏）已在 BBS 网络上存在。一些人提到 FidoNet 及类似 fsxNet 的 alt 网络至今仍在运行。

**标签**: `#retrocomputing`, `#history`, `#networking`, `#BBS`, `#FidoNet`

---

<a id="item-22"></a>
## [粘贴文件编辑器：将大文本粘贴转换为文件附件的浏览器工具](https://simonwillison.net/2026/Jun/2/pasted-file-editor/#atom-everything) ⭐️ 6.0/10

西蒙·威利森发布了一个名为 Pasted File Editor 的浏览器原型工具，能将大量粘贴文本转换为文件附件，灵感来自 Claude 的类似功能，并使用 Codex desktop 构建；还支持图像缩略图和拖放。 该工具展示了像 Codex 这样的 AI 辅助编码工具如何实现快速原型制作，可能会惠及需要处理网络环境中大文本输入的开发人员。 该工具完全使用 JavaScript 构建，在浏览器中运行，可直接打开文件（包括图像），也可拖放至文本区域。它是使用 OpenAI 的 Codex 桌面代理进行原型设计的，如链接的 Gist 所示。

rss · Simon Willison · 6月2日 04:13

**背景**: Claude 是由 Anthropic 开发的对话式 AI，能检测大量文本输入并将其作为文件附件处理，提升了开发人员粘贴代码的可用性。OpenAI Codex 是一个 AI 编码代理，可根据提示生成和修改代码，其桌面版本允许在本地构建应用程序。西蒙·威利森是一位知名开发者和博主，经常探索并分享 AI 辅助编程的实验。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_AI">Claude AI</a></li>
<li><a href="https://grokipedia.com/page/OpenAI_Codex">OpenAI Codex</a></li>

</ul>
</details>

**标签**: `#javascript`, `#tools`, `#ai-assisted-programming`, `#claude`, `#codex`

---

<a id="item-23"></a>
## [微调推理 LLM：监督学习与强化学习方法探讨](https://www.reddit.com/r/MachineLearning/comments/1ttxcm5/finetuning_a_reasoning_llm_with_supervised_or/) ⭐️ 6.0/10

一位 Reddit 用户就使用有监督微调还是强化学习来训练包含推理轨迹和工具调用决策的对话数据，向社区寻求建议。 这反映了构建能够使用工具的高效推理 LLM 的实际挑战，对于在现实应用中部署更小、更具成本效益的模型至关重要。 用户提出将对话按历史分割为样本并在监督微调时仅对助手 token 计算损失，同时询问如何为 PPO、GRPO、DPO 等强化学习算法设计奖励函数以优化工具调用准确性。

reddit · r/MachineLearning · /u/zdeneklapes · 6月1日 16:23

**背景**: 推理轨迹指最终答案前的中间思维步骤（如思维链），工具调用使 LLM 能查询外部 API。监督微调（SFT）基于标注数据训练，强化学习（RL）通过奖励信号优化行为。最新的 DeepSeek R1 等模型利用 RL 涌现推理能力，而通过推理轨迹进行 SFT 可将该能力蒸馏到小模型中。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://magazine.sebastianraschka.com/p/understanding-reasoning-llms">Understanding Reasoning LLMs - by Sebastian Raschka, PhD</a></li>
<li><a href="https://arxiv.org/abs/2508.16695">Do Cognitively Interpretable Reasoning Traces Improve LLM ... Understanding Reasoning LLMs - by Sebastian Raschka, PhD Top Stories Do Cognitively Interpretable Reasoning Traces Improve LLM ... Demystifying Reasoning Models - by Cameron R. Wolfe, Ph.D. Verbal Reasoning Traces in LLMs - emergentmind.com Tracing the thoughts of a large language model \ Anthropic Chain-of-Thought Annotation: How Reasoning Traces Improve LLM ...</a></li>
<li><a href="https://arxiv.org/abs/2512.15943">Small Language Models for Efficient Agentic Tool Calling ... Fine Tuning SLMs on Agentic Tool Calling: An Experiment Images Fine-tuning function calls with Azure OpenAI in Microsoft ... GitHub - AlineFree/llm-tool-call-sft: Fine-tune tool ... Practical Guide to Finetuning Falcon H1 Tiny for Tool Calling ... Build your own tool-calling agent with TRL on Azure Machine ... Fine-tuning With Tool Calling - stephendiehl.com</a></li>

</ul>
</details>

**标签**: `#fine-tuning`, `#reasoning-llms`, `#reinforcement-learning`, `#supervised-learning`, `#tool-use`

---

<a id="item-24"></a>
## [中国电动三轮车出口激增，海外售价达 3000-6000 美元](https://content-static.cctvnews.cctv.com/snow-book/index.html?toc_style_id=feeds_default&amp;item_id=5206220851671440944&amp;channelId=1119) ⭐️ 6.0/10

2025 年，中国电动两轮车出口超 2670 万辆，其中电动三轮车海外需求尤其强劲，在欧美售价达 3000 至 6000 美元，是国内售价的数倍。丰县制造商已采用扁线电机技术，降低能耗和成本，同时延长续航和寿命。 这波出口热潮凸显中国在经济实惠型绿色交通领域的竞争力，可能颠覆发达国家轻型多功能车市场，为传统皮卡提供高性价比替代方案，也标志着中国电动车供应链和技术的成熟。 扁线电机提升效率，降低能耗，延长续航里程和电机寿命 2 年，成本降低 10%。无锡海关统计显示，2025 年电动车出口增速比全国同类商品快 14 个百分点，舱位紧张等问题已出现。

telegram · zaihuapd · 6月2日 12:15

**背景**: 电动三轮车俗称“三蹦子”，是中国常见的短途轻量运输工具。扁线电机采用矩形截面铜线绕制定子，相比传统圆线电机，槽满率更高，散热更好，效率更优。江苏丰县是全国最大的电动三轮车配件生产基地，占据 90%以上配件市场。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://lamnow.com/flat-wire-motor-vs-round-wire-motor/">Flat Wire Motor vs. Round Wire Motor - Lamnow</a></li>
<li><a href="https://www.aivon.com/blog/industrial-control/flat-wire-motor-stator-and-rotor-processes/">Flat-wire Motor Stator and Rotor Processes - aivon.com</a></li>

</ul>
</details>

**标签**: `#electric vehicles`, `#exports`, `#manufacturing`, `#China`, `#trade`

---