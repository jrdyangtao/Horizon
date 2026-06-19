---
layout: default
title: "Horizon Summary: 2026-06-19 (ZH)"
date: 2026-06-19
lang: zh
---

> 从 63 条内容中筛选出 24 条重要资讯。

---

1. [历经十年开发，Valhalla 值类型终在 JDK 28 发布](#item-1) ⭐️ 9.0/10
2. [研究人员发现超 1 万个 GitHub 仓库传播木马病毒](#item-2) ⭐️ 9.0/10
3. [GLM-5.2 发布：MIT 许可下的最强开源权重大模型](#item-3) ⭐️ 9.0/10
4. [ATProto 中没有实例：基于中继的架构](#item-4) ⭐️ 8.0/10
5. [业余人士借助 AI 破译线形文字 A](#item-5) ⭐️ 8.0/10
6. [两党 JAWBONE 法案剑指政府审查言论](#item-6) ⭐️ 8.0/10
7. [早期研究发现表明 AI 可能会削弱人类技能](#item-7) ⭐️ 8.0/10
8. [Datasette Apps：在 Datasette 中运行沙盒化的自定义 HTML 应用](#item-8) ⭐️ 8.0/10
9. [cuTile Rust：编译器保证内存安全的 GPU 内核，推理速度媲美 vLLM](#item-9) ⭐️ 8.0/10
10. [现代汽车从软银手中全面收购波士顿动力](#item-10) ⭐️ 7.0/10
11. [Google Workspace 情境感知访问可能因 DBSC 阻止 Firefox](#item-11) ⭐️ 7.0/10
12. [datasette-acl 0.6a0 发布：从表权限迈向通用资源共享](#item-12) ⭐️ 7.0/10
13. [GitHub Models 停止接纳新用户，现有用户暂不受影响](#item-13) ⭐️ 7.0/10
14. [智谱创始人称模型明年 Q1 达 Mythos 级](#item-14) ⭐️ 7.0/10
15. [美国向 ASML 施压，疑其顶级光刻机流入中国](#item-15) ⭐️ 7.0/10
16. [谷歌公布 Android 侧载新规：安装未验证应用须等 24 小时](#item-16) ⭐️ 7.0/10
17. [苹果同意在巴西开放第三方应用商店与外部支付](#item-17) ⭐️ 7.0/10
18. [开发者用 500 行代码重现 torch.compile，解释算子融合](#item-18) ⭐️ 6.0/10
19. [对话级语音调试比孤立指标更有用](#item-19) ⭐️ 6.0/10
20. [Reddit 用户质疑 ACL 是否已对博士申请失去重要性](#item-20) ⭐️ 6.0/10
21. [国家网信办就分布式数字身份互通互认规定征求意见](#item-21) ⭐️ 6.0/10
22. [桑德斯提案：美国人每年享 AI 分红 1000 美元](#item-22) ⭐️ 6.0/10
23. [印度临时封锁 Telegram 应对考试作弊，VPN 注册量激增 150%](#item-23) ⭐️ 6.0/10
24. [北航前博士生指控教授论文造假，涉 Nature 论文](#item-24) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [历经十年开发，Valhalla 值类型终在 JDK 28 发布](https://www.jvm-weekly.com/p/project-valhalla-explained-how-a) ⭐️ 9.0/10

经过十年开发，Valhalla 项目的值类型现已纳入 JDK 28，允许开发者定义内联存储、无对象头的值类，从而改善内存布局和性能。 这标志着 Java 对象模型的根本性变革，缩小了与 C#、C++等语言的差距，并大幅提升数值计算和数据密集型工作负载的性能。 但初始版本不支持对超过 64 位的大型值类型进行堆扁平化，实现较为复杂，需谨慎编码以避免空值问题。值类型默认不可变且不可为 null，其数组将密集排列。

hackernews · philonoist · 6月19日 06:35 · [社区讨论](https://news.ycombinator.com/item?id=48595511)

**背景**: Valhalla 项目是 OpenJDK 于 2014 年左右启动的一项长期计划，旨在为 Java 引入值类型。在 Java 中，所有对象均为引用类型，通过指针访问并存储在堆中，带有对象头等内存开销。而值类型通过值传递，可直接存储在数组或栈上，避免了间接访问并改善缓存局部性。该特性备受期待，能带来更高效的内存使用和更好的性能，类似于 C 的结构体或 C#的值类型。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Project_Valhalla_(Java_language)">Project Valhalla (Java language) - Wikipedia</a></li>
<li><a href="https://openjdk.org/projects/valhalla/">Project Valhalla</a></li>

</ul>
</details>

**社区讨论**: 社区反应复杂，但总体上对十年的努力表示赞赏。部分开发者批评其局限性，如未对大型值类型实现堆扁平化，以及回避了空安全讨论。另一些人则称赞设计整合，并指出 Java 在多年忽视后的追赶历程。

**标签**: `#java`, `#jvm`, `#value-types`, `#performance`, `#language-design`

---

<a id="item-2"></a>
## [研究人员发现超 1 万个 GitHub 仓库传播木马病毒](https://orchidfiles.com/github-repositories-distributing-malware/) ⭐️ 9.0/10

一名安全研究人员发现超过 10,000 个 GitHub 仓库在被用于传播木马病毒，攻击目标极可能是自动拉取依赖项的 AI 编程代理。 此次攻击利用软件供应链，威胁日益普及的 AI 编程助手，可能导致大规模系统被攻陷，尤其发生在重大选举年。 这些被植入木马的仓库冒名顶替合法项目，并通过频繁删除和推送提交的手法，在“最近更新”搜索中排名靠前，专门针对自动解析依赖关系的 AI 代理，可能绕过了人类审查。

hackernews · theorchid · 6月18日 11:45 · [社区讨论](https://news.ycombinator.com/item?id=48583928)

**背景**: 供应链攻击指通过攻破生态系统中安全性较弱的环节来渗透目标。GitHub 是主要的开源代码平台，常被 Claude Code、Cursor、Copilot 等 AI 编程代理用来获取库文件。这些代理能自动添加依赖项而无需人工监督，因此对恶意仓库缺乏防御。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Supply_chain_attack">Supply chain attack</a></li>
<li><a href="https://www.faros.ai/blog/best-ai-coding-agents-2026">Best AI Coding Agents for 2026: Real-World Developer Reviews</a></li>

</ul>
</details>

**社区讨论**: 社区评论指出，这类攻击利用频繁提交提高搜索可见性，专门针对 AI 代理，有用户反映自己的开源项目被冒名顶替。人们担忧代理盲目信任代码，引用了一名迪士尼工程师从 GitHub 下载恶意 AI 工具的事例。攻击时机恰逢重大选举年和编程代理的兴起。

**标签**: `#security`, `#malware`, `#github`, `#supply-chain`, `#AI-agents`

---

<a id="item-3"></a>
## [GLM-5.2 发布：MIT 许可下的最强开源权重大模型](https://simonwillison.net/2026/Jun/17/glm-52/#atom-everything) ⭐️ 9.0/10

Z.ai 于 2026 年 6 月 16 日以 MIT 许可证发布了 GLM-5.2，这是一个拥有 753B 参数、采用混合专家架构的纯文本模型，上下文窗口长达 100 万 token。据称其在包括 Artificial Analysis 智能指数在内的独立开源权重基准测试中位列榜首。 GLM-5.2 为开源权重模型树立了新标杆，超越了 MiniMax-M3、DeepSeek V4 Pro 等竞品。其 MIT 许可证允许无限制的商业使用和修改，从而加速创新并降低 AI 开发的门槛。 该模型每次前向传递仅激活 40 个专家，但 token 消耗显著，每基准任务平均生成 43k 输出 token。尽管是纯文本模型，它在 Code Arena WebDev 排行榜上仍高居第二，并已通过 OpenRouter 提供，定价为每百万输入 token $1.40、输出 token $4.40。

rss · Simon Willison · 6月17日 23:58

**背景**: 混合专家（MoE）是一种机器学习技术，由多个专门的子网络（专家）协作处理输入的不同部分，每次仅激活部分专家，从而以更低的计算成本构建更大模型。开源权重模型提供可下载的预训练参数以供推理和微调，但与完全开源模型不同，它们可能不包含训练代码或数据。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mixture_of_experts">Mixture of experts - Wikipedia</a></li>
<li><a href="https://huggingface.co/blog/moe">Mixture of Experts Explained</a></li>
<li><a href="https://promptengineering.org/llm-open-source-vs-open-weights-vs-restricted-weights/">Openness in Language Models: Open Source vs Open Weights vs Restricted Weights</a></li>

</ul>
</details>

**标签**: `#GLM-5.2`, `#open-weights`, `#large-language-model`, `#MIT-license`, `#AI-release`

---

<a id="item-4"></a>
## [ATProto 中没有实例：基于中继的架构](https://overreacted.io/there-are-no-instances-in-atproto/) ⭐️ 8.0/10

Dan Abramov 发表了一篇文章，阐明 ATProto 与基于 ActivityPub 的 Mastodon 不同，它没有实例，而是依赖由个人数据服务器、中继和应用视图组成的基于中继的架构。 这一澄清回应了去中心化社交媒体用户中常见的误解，凸显了协议设计中的架构权衡，影响着开发者和用户对联邦、可扩展性和用户自主权的理解。 在 ATProto 中，用户写入权威的个人数据服务器（PDS）；中继聚合并传输数据；应用视图则消费这些数据。模块化设计分离了扩展性问题，但批评者认为昂贵的中继引入了中心化风险。

hackernews · danabramov · 6月19日 15:10 · [社区讨论](https://news.ycombinator.com/item?id=48599515)

**背景**: ATProto 是去中心化社交网络 Bluesky 背后的协议，而 Mastodon 使用 ActivityPub，采用独立实例的模式，每个实例托管用户并无缝共享内容。在 Mastodon 中，实例是自包含的服务器，拥有自己的管理机制；ATProto 解耦了身份、存储和应用逻辑，因此不存在直接的实例对等物。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Atproto">Atproto</a></li>
<li><a href="https://en.wikipedia.org/wiki/AT_Protocol">AT Protocol - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区反应不一。有人称赞服务分离的设计优雅，也有人批评其与 RSS 的类比不当，认为 ATProto 对昂贵中继的依赖使其去中心化程度不如宣称的那样高，PDS 在客户端-服务器模型中充当权威服务器，而非真正的点对点。

**标签**: `#decentralized-web`, `#atproto`, `#bluesky`, `#architecture`, `#protocol-design`

---

<a id="item-5"></a>
## [业余人士借助 AI 破译线形文字 A](https://aiclambake.com/clamtakes/linear-a/) ⭐️ 8.0/10

一名业余人士宣称利用 Claude Code 构建的 AI 辅助工具破译了古文字线形文字 A，并翻译了 300 多个词，这是该 120 年难题的首次突破。目前成果正由罗格斯大学和剑桥大学的语言学专家审核。 若得到验证，这将破解古代语言中最持久的谜题之一，可能揭开米诺斯文明的面纱。同时，这展示了 AI 工具在极小数据集上加速语言破译假设检验的潜力。 破译基于对“祭酒公式”的系统分析，这是线形文字 A 残片中唯一重复出现的短语，整个语料库仅约 7500 个字符，分散在约 1500 处铭文中。该方法使用 Python 脚本交叉引用数字化文本，并非黑箱式 AI 解决方案，译文有待专家验证。

hackernews · Kosturdistan · 6月19日 16:04 · [社区讨论](https://news.ycombinator.com/item?id=48600107)

**背景**: 线形文字 A 是公元前 1800 年至 1450 年克里特岛米诺斯文明使用的音节文字，至今未被破译。它与 20 世纪 50 年代被破译的线形文字 B（用于书写迈锡尼希腊语）共享许多符号，但背后语言未知。语料库极小（约 7500 个字符），传统密码学方法难以奏效，此前多次破译声称均未通过同行评议。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Linear_A">Linear A</a></li>
<li><a href="https://www.britannica.com/topic/Linear-A">Linear A and Linear B | Mycenaean, Minoan & Decipherment | Britannica</a></li>

</ul>
</details>

**社区讨论**: 社区持谨慎乐观态度；许多人指出，该研究的可信度因专家审核以及使用 AI 构建分析工具而非黑箱求解而提高。但也有人强调语料库极小，所有人都在等待专家的最终确认。

**标签**: `#linear-a`, `#decipherment`, `#ai-tools`, `#linguistics`, `#ancient-languages`

---

<a id="item-6"></a>
## [两党 JAWBONE 法案剑指政府审查言论](https://www.eff.org/deeplinks/2026/06/new-bill-takes-aim-government-pressure-silence-lawful-online-speech) ⭐️ 8.0/10

由克鲁兹和怀登参议员提出的两党 JAWBONE 法案，旨在禁止联邦机构胁迫广播公司、AI 公司和网络平台审查合法言论，并赋予受害者诉讼权利。 该法案针对政府通过非正式施压（jawboning）迫使中介审查言论、绕过正当程序的问题，可能保护网络言论自由，并为反对违宪胁迫树立先例。 该法案覆盖广播公司、AI 公司和网络平台，即使审查未遂也可提起诉讼。ACLU 和 EFF 已予以支持。

hackernews · hn_acker · 6月19日 17:34 · [社区讨论](https://news.ycombinator.com/item?id=48600950)

**背景**: 施压（jawboning）指政府对私人中介施加非正式压力以审查言论，可能绕过第一修正案保护。JAWBONE 是“Justice Against Weaponized Bureaucratic Overreach to Networked Expression”的缩写，回应了联邦机构推动平台压制合法但有争议内容的担忧。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.aclu.org/press-releases/aclu-endorses-bipartisan-jawbone-act-to-protect-free-speech">ACLU Endorses Bipartisan JAWBONE Act To Protect Free Speech</a></li>
<li><a href="https://reason.com/2026/06/17/bipartisan-jawbone-act-targets-government-censorship-threats/">Bipartisan JAWBONE Act targets government censorship threats</a></li>

</ul>
</details>

**社区讨论**: 许多评论者赞赏两党合作和精妙的缩写名称，但部分人对克鲁兹参议员持怀疑态度，因其过去支持限制言论的反 BDS 法律。其他人指出政府可能自食其果的讽刺，总体呈现谨慎乐观与担忧矛盾的情绪。

**标签**: `#free-speech`, `#government-overreach`, `#jawbone-act`, `#eff`, `#legislation`

---

<a id="item-7"></a>
## [早期研究发现表明 AI 可能会削弱人类技能](https://www.nature.com/articles/d41586-026-01947-1) ⭐️ 8.0/10

《自然》杂志文章报道了早期研究，表明使用 AI 工具可能会损害人类的认知技能，例如批判性思维和解决问题的能力，因为用户越来越依赖 AI 来完成以前独立完成的任务。 这一趋势引发了人们对长期人类技能退化和广泛认知卸载潜能的担忧，这可能会从根本上改变我们的思维和学习方式，尤其是在 AI 助手在职业和日常环境中无处不在的情况下。 值得注意的早期发现包括：医生在使用 AI 辅助时对医学图像解读的熟练度下降，程序员可能失去了底层编码技能，但或许在架构概述能力上有所增益。

hackernews · Michelangelo11 · 6月19日 18:00 · [社区讨论](https://news.ycombinator.com/item?id=48601286)

**背景**: 认知卸载是指使用外部工具来减少脑力消耗，例如使用 GPS 代替空间记忆。历史上，技术既增强了人类的技能，也取代了人类的技能。当前的生成式 AI 浪潮由于其能在多个领域同时执行复杂认知任务的能力，而成为一个独特案例。

**社区讨论**: Hacker News 上的评论者讨论了将 AI 与高地位工作中的委派行为类比的问题，指出 AI 的范围是前所未有的，可能具有诱惑力和削弱性。一些人分享了个人经验，反映了技能损失与更高层次思维之间的平衡，而另一些人则强调，AI 是一种杠杆，可以导致懒惰或令人难以置信的生产力，这取决于个人的选择。

**标签**: `#AI`, `#cognitive skills`, `#offloading`, `#human-AI interaction`, `#critical thinking`

---

<a id="item-8"></a>
## [Datasette Apps：在 Datasette 中运行沙盒化的自定义 HTML 应用](https://simonwillison.net/2026/Jun/18/datasette-apps/#atom-everything) ⭐️ 8.0/10

Simon Willison 推出了 datasette-apps 插件，用户现在可以将自包含的 HTML 和 JavaScript 应用托管在 Datasette 的沙盒化 iframe 中，这些应用可对数据执行只读 SQL 查询，并可通过预存查询支持写入操作。 此举将 Datasette 从数据发布工具转变为安全的交互式数据应用平台，在保护用户数据安全的前提下，为可定制、可嵌入的工具打开了大门。 iframe 采用 sandbox="allow-scripts allow-forms" 并注入内容安全策略，以阻止外部网络请求、cookie 和 localStorage 访问，且不同源。应用默认执行只读 SQL；若需写入，必须通过预存的 SQL 查询显式配置。

rss · Simon Willison · 6月18日 23:58

**背景**: Datasette 是一个开源工具，用于将 SQLite 数据库发布为带有 JSON API 的交互式网站。它原本就支持插件扩展，但要构建丰富的自定义界面往往需要开发外部应用。新插件利用 iframe 沙盒和内容安全策略，将用户创建或 AI 生成的 HTML/JS 应用安全地直接嵌入 Datasette，防止数据泄露等安全风险，同时支持灵活的自包含应用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.w3schools.com/tags/att_iframe_sandbox.asp">HTML iframe sandbox Attribute</a></li>
<li><a href="https://web.dev/articles/sandboxed-iframes">Play safely in sandboxed IFrames | Articles | web.dev</a></li>

</ul>
</details>

**标签**: `#datasette`, `#plugins`, `#web-development`, `#sql`, `#sandboxed-applications`

---

<a id="item-9"></a>
## [cuTile Rust：编译器保证内存安全的 GPU 内核，推理速度媲美 vLLM](https://www.reddit.com/r/MachineLearning/comments/1u9j7md/fearless_concurrency_on_the_gpu_safe_gpu/) ⭐️ 8.0/10

cuTile Rust 是一个新的基于 tile 的 GPU 编程 DSL，利用 Rust 的所有权模型在编译器层面验证 GPU 内核的内存安全和数据竞争自由。作者还发布了基于 cuTile Rust 构建的 Qwen3 推理引擎 Grout，其在批量大小为 1 的解码阶段达到了与 vLLM 和 SGLang 相当的吞吐量：在 RTX 5090 上对 Qwen3-4B 达到 171 tok/s，在 B200 上对 Qwen3-32B 达到 82 tok/s。 随着 AI 生成的 GPU 代码日益普及，代码可信度变得至关重要。cuTile Rust 在编译时消除了整类错误（如竞争条件、内存错误），对安全关键或自动合成的内核尤其有价值。其性能与主流推理引擎相当，表明安全性不必以牺牲速度为代价。 cuTile Rust 编译到 NVIDIA 的 CUDA Tile IR，将 Rust 的所有权扩展到内核调用边界。安全的 GEMM 内核性能与手写低级版本相差在 0.3% 以内，逐元素操作速度约 7 TB/s。局限性包括：Grout 仅支持批量大小为 1 的推理和少数模型，只适用于 NVIDIA GPU，且在某些尺寸下 GEMM 仍略微落后于 cuBLAS。

reddit · r/MachineLearning · /u/Exciting_Suspect9088 · 6月18日 21:36

**背景**: Rust 的所有权系统可在编译时强制实现内存安全并防止数据竞争，无需垃圾回收，传统上针对 CPU 代码。GPU 由于大规模并行执行和复杂的内存层次，带来了新的挑战。CUDA Tile IR 是一种中间表示，将 GPU 建模为基于 tile 的处理器，从而实现高效的内核优化。vLLM 和 SGLang 是流行的大型语言模型高性能服务系统。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/NVIDIA/cuda-tile">GitHub - NVIDIA/cuda-tile: CUDA Tile IR is an MLIR-based ...</a></li>
<li><a href="https://docs.nvidia.com/cuda/tile-ir/latest/index.html">Tile IR — Tile IR - NVIDIA Documentation Hub</a></li>

</ul>
</details>

**标签**: `#rust`, `#gpu-programming`, `#memory-safety`, `#llm-inference`, `#hpc`

---

<a id="item-10"></a>
## [现代汽车从软银手中全面收购波士顿动力](https://startupfortune.com/hyundai-takes-full-control-of-boston-dynamics-as-softbank-exits-for-325-million/) ⭐️ 7.0/10

现代汽车集团以 3.25 亿美元从软银手中收购了波士顿动力剩余的股份，从而拥有这家机器人先驱 100%的所有权。这完成了始于 2020 年 12 月的收购，当时现代收购了 80%的控股股权。 全面收购巩固了现代在汽车制造之外的先进机器人领域地位，并与其在人工智能和自主系统方面的努力保持一致。这也反映了汽车制造商对机器人技术的战略兴趣日益增长，可能旨在应对劳动力短缺和未来出行需求。 该交易行使了 2020 年原始协议中的卖出期权，当时现代以 8.8 亿美元收购了公司 80%的股份，估值达 11 亿美元。尽管拥有最先进的仿人机器人 Atlas，现代承认它尚未准备好用于汽车工厂。

hackernews · ck2 · 6月19日 16:28 · [社区讨论](https://news.ycombinator.com/item?id=48600312)

**背景**: 波士顿动力公司成立于 1992 年，以 Spot 机器狗和人形机器人 Atlas 等高度动态机器人而闻名。软银于 2017 年从谷歌手中收购了它，随后将其出售给现代。现代将机器人视为未来出行的关键组成部分，与自动驾驶汽车和城市空中出行并列。

**社区讨论**: 评论反映了战略分析和怀疑态度的混合。一些人质疑仿人机器人相对于专用设计的实用性，而另一些人则将此举与韩国劳动力下降联系起来。也有人承认 Atlas 尚未准备好用于工厂，但可能在太空探索等领域找到应用。

**标签**: `#robotics`, `#merger-and-acquisition`, `#Hyundai`, `#Boston-Dynamics`, `#humanoid-robots`

---

<a id="item-11"></a>
## [Google Workspace 情境感知访问可能因 DBSC 阻止 Firefox](https://tales.fromprod.com/2026/169/google-workspace-threatening-to-block-firefox.html) ⭐️ 7.0/10

由企业管理员配置的 Google Workspace 情境感知访问功能可能因 Firefox 缺乏硬件支持的设备绑定会话凭据（DBSC）而阻止 Firefox 用户，DBSC 目前仅 Chrome 支持。这引发了关于浏览器兼容性和反竞争行为的讨论。 这凸显了企业安全要求与浏览器多样性之间的紧张关系，因为强制实施 DBSC 可能有效地迫使用户转向 Chrome，引发反垄断担忧并影响开放网络生态。它强调了可配置的安全功能如何被误认为是广泛政策，加剧了对谷歌权力的恐惧。 DBSC 利用硬件支持的加密技术（如可信平台模块 TPM）将会话 Cookie 绑定到设备，使得被盗后无法使用。只有当组织的管理员在情境感知访问策略中明确启用 DBSC 要求时，才会发生阻止。

hackernews · birdculture · 6月19日 16:30 · [社区讨论](https://news.ycombinator.com/item?id=48600345)

**背景**: 情境感知访问是 Google Workspace 的安全产品，允许管理员根据设备安全状态、位置等属性设置细粒度的访问控制。设备绑定会话凭据（DBSC）是谷歌开发的一种机制，通过将身份验证令牌绑定到设备硬件来防止会话劫持，最初在 Chrome 中推出，以对抗基于恶意软件的 Cookie 窃取。Firefox 尚未实现 DBSC，使其与需要 DBSC 的策略不兼容。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://knowledge.workspace.google.com/admin/security/about-context-aware-access">About Context-Aware Access | Security & data protection ...</a></li>
<li><a href="https://developer.chrome.com/docs/web-platform/device-bound-session-credentials">Device Bound Session Credentials (DBSC) | Web Platform | Chrome for Developers</a></li>
<li><a href="https://blog.google/security/protecting-cookies-with-device-bound-session-credentials/">Protecting Cookies with Device Bound Session Credentials</a></li>

</ul>
</details>

**社区讨论**: 社区评论澄清，这不是谷歌的全面禁令，而是一个可配置的企业安全功能，敦促原帖作者联系其 IT 部门。一些人表达了对浏览器检测和用户代理欺骗的担忧，而另一些人则指出谷歌缓慢地使此类变化常态化以避免反弹，最终迫使用户转向 Chrome。

**标签**: `#browser-compatibility`, `#google-workspace`, `#firefox`, `#web-security`, `#context-aware-access`

---

<a id="item-12"></a>
## [datasette-acl 0.6a0 发布：从表权限迈向通用资源共享](https://simonwillison.net/2026/Jun/18/datasette-acl/#atom-everything) ⭐️ 7.0/10

该版本将 datasette-acl 从仅能控制表权限扩展为一个通用资源共享系统，支持对多用户 Datasette 实例中的各类资源进行细粒度访问控制。 这为多用户 Datasette 实例提供了精确的权限定义，支持安全地共享数据及其他资源，使 Datasette 在协作和生产场景中更具实用性。 大部分开发工作由 Alex Garcia 完成。版本号为 0.6a0，属于 alpha 阶段，可能存在不稳定性。此前 datasette-acl 仅支持表级权限；现在它可将 Datasette 中的任何资源都视为可控制访问的实体。

rss · Simon Willison · 6月18日 19:03

**背景**: Datasette 是一个用于探索和发布数据的开源工具，常用于在网络上共享 SQLite 数据库。它支持插件机制，datasette-acl 就是一款添加访问控制列表（ACL）来管理用户权限的插件。在多用户环境中，该插件至关重要，可实现对同一 Datasette 实例的不同访问级别控制。本次更新在早期版本的基础上，将控制粒度从表级扩展到涵盖 Datasette 中的所有资源类型。

**标签**: `#datasette`, `#datasette-acl`, `#access-control`, `#acl`, `#python`

---

<a id="item-13"></a>
## [GitHub Models 停止接纳新用户，现有用户暂不受影响](https://github.blog/changelog/2026-06-16-github-models-is-no-longer-available-to-new-customers/) ⭐️ 7.0/10

自 2026 年 6 月 16 日起，GitHub Models 已停止接受新客户，并启动退役流程。现有用户可继续使用，但新组织无法访问该服务。 这标志着 GitHub 的 AI 模型实验平台走向终点，影响依赖其进行原型设计和推理的开发者。此举将新项目推向 Azure AI Foundry，巩固了微软的 AI 平台策略。 该限制适用于免费和付费计划，涵盖 Playground、API 和模型访问。具体的退役时间表将后续公布，建议迁移目标是 Azure AI Foundry。

telegram · zaihuapd · 6月19日 00:54

**背景**: GitHub Models 是一个平台，允许开发者通过基于网页的 Playground 和 API 对来自不同提供商（如 OpenAI、Meta、微软等）的 AI 模型进行原型设计和实验，并与 GitHub 仓库紧密集成。Azure AI Foundry（原 Azure AI Studio）是微软的统一 AI 平台，用于构建和部署 AI 应用和智能体。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://grokipedia.com/page/GitHub_Models">GitHub Models</a></li>
<li><a href="https://azure.microsoft.com/en-us/products/ai-foundry">Microsoft Foundry | Microsoft Azure</a></li>

</ul>
</details>

**标签**: `#GitHub`, `#AI`, `#deprecation`, `#Azure`, `#cloud services`

---

<a id="item-14"></a>
## [智谱创始人称模型明年 Q1 达 Mythos 级](https://x.com/jietang/status/2067580270078030088) ⭐️ 7.0/10

智谱创始人唐杰在 X 上声称，该公司模型或可在 2026 年第一季度前达到 Anthropic 的 Mythos 级别能力，直接反驳了马斯克关于 2027 年第一季度的估计。 这一声明凸显了中美 AI 竞赛的白热化，中国公司正积极追赶西方顶尖 AI 实验室。若成功实现，将标志着中国在前沿 AI 模型开发上的重大突破。 这一比较基于 GLM-5.2 性能大致相当于 Claude Opus 4.7/4.8 的评估，暗示中国落后美国约 7 个月。Mythos 级模型代表远超 Opus 的重大飞跃，Anthropic 在初步安全评估后才刚刚公开发布版本。

telegram · zaihuapd · 6月19日 02:24

**背景**: Anthropic 的“Mythos”级别指能力极强、需额外防护的模型，涉及网络安全和生物等领域。Claude Mythos 5 于 2025 年年中发布，是受限模型 Claude Fable 5 的更安全版本。智谱 GLM-5.2 近期发布，是一个专注于长程任务和智能编程的开源模型，性能介于 Claude Opus 4.7 和 4.8 之间。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/claude/mythos">Claude Mythos \ Anthropic</a></li>
<li><a href="https://www.anthropic.com/news/claude-fable-5-mythos-5">Claude Fable 5 and Claude Mythos 5 \ Anthropic</a></li>
<li><a href="https://z.ai/blog/glm-5.2">GLM-5.2: Built for Long-Horizon Tasks - z.ai</a></li>

</ul>
</details>

**社区讨论**: 网上的交流引发了对时间表的辩论，部分用户认同马斯克的保守预测，另一些则赞赏唐杰的信心。许多人认可中国 AI 的快速进步，但质疑安全和价值观对齐问题是否会延缓这类强大模型的发布。

**标签**: `#AI`, `#LLM`, `#China AI`, `#Anthropic`, `#Elon Musk`

---

<a id="item-15"></a>
## [美国向 ASML 施压，疑其顶级光刻机流入中国](https://www.bloomberg.com/news/articles/2026-06-19/us-tells-asml-it-s-concerned-china-may-have-top-chip-tool) ⭐️ 7.0/10

美国商务部长卢特尼克近期向 ASML 高管表示，担忧一台顶级极紫外（EUV）光刻机可能违反出口管制流入中国。ASML 坚决否认，称从未向中国出口过完整的 EUV 系统。 此事可能加剧美欧在芯片出口管制上的紧张关系，并影响美国国会正在推动的更严格对华设备限制法案。同时，这也凸显了 EUV 技术的重要性，它对于先进半导体制造至关重要，并影响人工智能和高性能计算硬件的供应。 ASML 声称其全球运行的 314 台 EUV 设备均不在中国，并已散发文件自证清白。但美方官员称掌握 ASML 向中国出口 EUV 相关运输设备的证据却拒绝出示细节，ASML 则反驳从未出口任何 EUV 专用组件。

telegram · zaihuapd · 6月19日 03:09

**背景**: 极紫外光刻（EUV）是一种尖端技术，用于制造最先进的半导体芯片，可实现 3 纳米及以下工艺。ASML 是全球唯一的 EUV 系统供应商，这些系统对于生产高性能处理器和 AI 加速器至关重要。自 2019 年以来，美国一直施压荷兰限制 ASML 对华出口，阻止中国企业获取 EUV 工具以延缓其芯片制造进步。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/EUV_lithography">EUV lithography</a></li>
<li><a href="https://www.asml.com/en/products/euv-lithography-systems">EUV lithography systems – Products | ASML</a></li>

</ul>
</details>

**标签**: `#semiconductors`, `#export controls`, `#ASML`, `#EUV lithography`, `#US-China trade`

---

<a id="item-16"></a>
## [谷歌公布 Android 侧载新规：安装未验证应用须等 24 小时](https://t.me/zaihuapd/42054) ⭐️ 7.0/10

谷歌为未经验证的开发者应用引入了新的高级侧载流程，要求用户开启开发者选项、确认未受胁迫、重启手机并通过生物识别或 PIN 码重新验证身份，经过 24 小时冷静期后才能安装。 这一高摩擦流程旨在防止诈骗分子通过社会工程学手段诱导用户安装恶意软件，从而提升安全性，但也会显著改变侧载体验，影响高级用户和第三方应用商店。 24 小时等待是一次性的，之后用户可将侧载权限设为 7 天或长期有效。流程包含多次身份验证和反胁迫确认，并沿袭了去年要求开发者支付 25 美元并提交身份证明的验证政策。

telegram · zaihuapd · 6月19日 07:59

**背景**: Android 侧载指通过 Google Play 商店以外的方式安装应用，通常使用 APK 文件。过去用户只需开启‘允许此来源’即可安装。为应对日益增多的诈骗，谷歌通过 Play Protect 扫描和开发者验证逐步加强安全管控。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://hackaday.com/2026/03/20/google-unveils-new-process-for-installing-unverified-android-apps/">Google Unveils New Process For Installing Unverified Android Apps | Hackaday</a></li>
<li><a href="https://www.theregister.com/2026/03/19/google_android_unverified_apps/">Google creates installation path for unverified Android apps • The Register</a></li>
<li><a href="https://android-developers.googleblog.com/2026/03/android-developer-verification.html">Android Developers Blog: Android developer verification: Balancing openness and choice with safety</a></li>

</ul>
</details>

**标签**: `#Android`, `#sideloading`, `#security`, `#mobile-development`, `#Google`

---

<a id="item-17"></a>
## [苹果同意在巴西开放第三方应用商店与外部支付](https://t.me/zaihuapd/42059) ⭐️ 7.0/10

苹果与巴西反垄断监管机构达成协议，将允许 iPhone 用户从第三方应用商店安装应用并使用外部支付方式，相关改变需在 105 天内落实。 这标志着重要市场监管的重大转变，可能影响其他国家的反垄断行动，并挑战苹果封闭的 App Store 模式，该模式一直是高额佣金和开发者争议的焦点。 协议允许开发者展示外部支付链接，并将苹果支付系统与 App Store 解耦，但苹果仍可对交易收取费用。协议有效期为三年。

telegram · zaihuapd · 6月19日 11:15

**背景**: 苹果历来要求所有 iOS 应用下载必须通过其 App Store 并使用自家支付系统，收取高达 30%的佣金。这引起了全球监管机构的关注，包括欧盟的《数字市场法案》在 2024 年强制在欧洲实施了类似改变。巴西反垄断监管机构 CADE 一直在调查苹果的反竞争行为，这项协议解决了该调查。

**标签**: `#Apple`, `#App Store`, `#antitrust`, `#Brazil`, `#regulation`

---

<a id="item-18"></a>
## [开发者用 500 行代码重现 torch.compile，解释算子融合](https://www.reddit.com/r/MachineLearning/comments/1ua2hwj/how_does_torchcompile_achieve_massive_speedups/) ⭐️ 6.0/10

一位开发者分享了用 500 行 Python 重写的 torch.compile 及配套 notebook，演示算子融合如何实现加速。 这套教育资源阐明了 PyTorch 中算子融合的原理，有助于从业者理解这一关键优化技术，并可降低尝试自定义融合操作的门槛。 这个简化实现仅聚焦算子融合，省略了真实 torch.compile 的诸多复杂性，是一个学习工具而非生产级替代品。

reddit · r/MachineLearning · /u/Other-Eye-8152 · 6月19日 13:47

**背景**: 算子融合将多个操作合并为一个 GPU 内核，以减少昂贵的片外内存访问并提升性能。torch.compile 是 PyTorch 2.0 引入的即时编译器，可自动应用此类融合及其他优化。此前，开发者需手动调优底层内核才能获得类似加速。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://dl.acm.org/doi/10.1145/3520142">Optimus: An Operator Fusion Framework for Deep Neural Networks | ACM Transactions on Embedded Computing Systems</a></li>
<li><a href="https://docs.pytorch.org/tutorials/intermediate/torch_compile_tutorial.html">Introduction to torch.compile — PyTorch Tutorials 2.12.0+cu130 documentation</a></li>

</ul>
</details>

**标签**: `#PyTorch`, `#torch.compile`, `#Operator Fusion`, `#Performance Optimization`, `#Educational`

---

<a id="item-19"></a>
## [对话级语音调试比孤立指标更有用](https://www.reddit.com/r/MachineLearning/comments/1u99fe5/voice_debugging_at_the_conversation_level_seems/) ⭐️ 6.0/10

一位开发者分享称，对话级调试能够揭示孤立基准指标无法捕捉的突现交互问题，例如时序摩擦和不自然的轮流发言，并正在尝试使用自动化 QA 来规模化人工审查对话轨迹。 这一见解凸显了当前语音 AI 评估方法的关键缺陷，即依赖组件级指标可能导致在多轮交互中令用户感到沮丧的系统，进而影响用户采用率和满意度。 值得注意的问题包括累积的时序错误、重复确认带来的摩擦，以及由于轻微轮流发言错误导致的用户行为改变。转向以模式为中心的调试和自动化 QA 旨在解决人工审查的规模化挑战。

reddit · r/MachineLearning · /u/OwlZealousideal4779 · 6月18日 15:29

**背景**: 语音 AI 系统融合了语音识别、语言理解和语音合成，传统上使用词错误率和任务完成率等单独指标进行评估。在多轮对话中，交互流程产生的突现属性——如时序和轮流发言动态——需要超越单次测试的监控。Hamming 和 Maxim 等行业工具现在提供对话级可观测性，反映了对这一需求日益增长的认识。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://hamming.ai/resources/debugging-voice-agents-real-time-logs-missed-intents-error-dashboards">Debugging Voice Agents: Real-Time Logs, Missed Intents ...</a></li>
<li><a href="https://maxim-articles.ghost.io/top-5-platforms-for-debugging-voice-agents/">Top 5 platforms for debugging voice agents</a></li>
<li><a href="https://www.crescendo.ai/blog/ai-automated-quality-assurance">8 Top AI-Powered Automated Quality Assurance in 2026</a></li>

</ul>
</details>

**标签**: `#voice AI`, `#conversational AI`, `#evaluation metrics`, `#debugging`, `#speech systems`

---

<a id="item-20"></a>
## [Reddit 用户质疑 ACL 是否已对博士申请失去重要性](https://www.reddit.com/r/MachineLearning/comments/1u945j5/is_acl_now_irrelevant_d/) ⭐️ 6.0/10

一名 Reddit 用户惊讶地发现，尽管 ACL 是顶级 A+会议，但其第一作者论文如今却被视为自然语言处理博士申请中的弱信号。 这一讨论凸显了 AI 相关博士招生中对学术会议重视程度的潜在变化，像 NeurIPS、ICML 和 ICLR 这样的大型机器学习会议正获得更大影响，可能对专注于 NLP 领域的研究者不利。 该说法源于另一条 Reddit 帖子的评论，并无数据支持。用户质疑这究竟是真实趋势还是'故意引战'。

reddit · r/MachineLearning · /u/H4RZ3RK4S3 · 6月18日 11:52

**背景**: ACL（计算语言学协会）是 NLP 研究的旗舰会议，历来被评为 A+级别。近年来，NeurIPS、ICML 和 ICLR 等 AI 会议在规模和声望上急剧增长，因其更广泛的机器学习议题，往往更受博士招生委员会的青睐。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://medium.com/@sarthakanand/what-is-it-like-to-attend-an-acl-conference-for-the-first-time-576e2e9741c5">What is it like to attend an ACL conference for the first time | Medium</a></li>
<li><a href="https://www.aclweb.org/archive/reports/HovyReport.html">The Hovy/McCoy Report</a></li>

</ul>
</details>

**标签**: `#ACL`, `#NLP`, `#academic conferences`, `#PhD applications`, `#machine learning community`

---

<a id="item-21"></a>
## [国家网信办就分布式数字身份互通互认规定征求意见](https://www.cac.gov.cn/2026-06/18/c_1783525605384124.htm) ⭐️ 6.0/10

国家网信办发布了基于区块链的分布式数字身份系统规定草案，旨在实现跨领域互通互认和用户自主身份管理，公开征求意见截止至 2026 年 7 月 18 日。 该规定可能在中国建立标准化、自主可控的身份基础设施，加强隐私和安全的同时，简化金融和数字货币等服务访问。 草案规定分布式数字身份由标识符、密钥、可验证凭证和可验证声明构成，基于区块链，并将在国家身份链上跨多个政务领域实施。

telegram · zaihuapd · 6月19日 01:39

**背景**: 分布式数字身份（DID）允许用户自主管理身份数据，无需依赖中央机构。它通常使用区块链存储标识符和可验证凭证，后者是属性的加密证明。中国拟议的系统将这一概念扩展到工业设备和跨境使用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cac.gov.cn/2026-06/18/c_1783525605384124.htm">国家互联网信息办公室关于《促进分布式数字身份互通互认应用规定（征求意见稿）》公开征求意见的通知国家互联网信息办公室关于《促进分布式数字身份互通 ...</a></li>
<li><a href="https://www.secrss.com/articles/84215">分布式数字身份技术概述 - 安全内参 | 决策者的网络安全知识库</a></li>

</ul>
</details>

**标签**: `#distributed digital identity`, `#blockchain`, `#regulation`, `#China`, `#interoperability`

---

<a id="item-22"></a>
## [桑德斯提案：美国人每年享 AI 分红 1000 美元](https://www.washingtonpost.com/business/2026/06/18/bernie-sanders-proposes-wealth-fund-give-americans-stake-ai/) ⭐️ 6.0/10

参议员伯尼·桑德斯提出立法，通过让公众持有大型 AI 公司股份，为美国人每年提供 1000 美元分红。 该提案体现了应对 AI 带来的财富集中问题的努力，旨在确保 AI 的经济利益广泛分配，可能为政府如何监管和再分配 AI 产生的利润树立先例。 该立法要求让公众直接持有最大 AI 公司的股权，特朗普总统此前也表达过类似的政府持股想法，但具体实施机制和受影响的公司范围尚不明确。

telegram · zaihuapd · 6月19日 09:45

**背景**: 参议员伯尼·桑德斯以进步主义经济政策著称，该提案与其缩小贫富差距的议程一致。将企业利润分配给公民的类似主权财富基金概念，在阿拉斯加永久基金等案例中已有讨论。OpenAI、谷歌和微软等 AI 公司正创造巨额收入，引发如何分配收益的问题。

**标签**: `#AI policy`, `#wealth distribution`, `#legislation`, `#AI economy`

---

<a id="item-23"></a>
## [印度临时封锁 Telegram 应对考试作弊，VPN 注册量激增 150%](https://t.me/zaihuapd/42058) ⭐️ 6.0/10

印度政府下令自 6 月 16 日至 22 日临时封锁 Telegram，以防止 NEET-UG 医学重考作弊，导致来自印度的 Proton VPN 每小时注册量飙升 150%，并因 BGP 路由劫持意外影响了其他国家的 Telegram 访问。 该事件凸显了政府越来越多地采用网络层面的审查及其带来的意外附带损害，同时也展现了公众为规避限制而迅速采用 VPN 的现象，引发了关于互联网封锁有效性及副作用的讨论。 封锁通过印度互联网服务提供商的 BGP 劫持实施，将 Telegram 流量重定向到空路由；因路由泄露意外中断了阿联酋等国的服务。Proton VPN 报告封锁期间来自印度的每小时注册量增长超过 150%。

telegram · zaihuapd · 6月19日 10:30

**背景**: BGP 劫持是一种通过虚假宣告 IP 前缀所有权来重定向或阻断流量的技术，此次被用作审查工具。NEET-UG 是印度全国医学入学考试，因涉及 Telegram 的作弊丑闻而引发封锁。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/BGP_hijacking">BGP hijacking - Wikipedia</a></li>
<li><a href="https://www.cloudflare.com/learning/security/glossary/bgp-hijacking/">What is BGP hijacking? - Cloudflare</a></li>

</ul>
</details>

**标签**: `#internet censorship`, `#VPN usage`, `#BGP hijacking`, `#Telegram`, `#India`

---

<a id="item-24"></a>
## [北航前博士生指控教授论文造假，涉 Nature 论文](https://www.zaobao.com.sg/news/china/story20260619-9231002) ⭐️ 6.0/10

北京航空航天大学前博士生耿同学（耿江涛）公开指控该校两名教授在多篇论文中造假，其中包括一篇发表在《自然》上的文章。该视频发布后引发大量网民涌入北航官网，导致网站一度瘫痪。 此次指控涉及顶级期刊《自然》和中国重点大学，凸显了学界对学术诚信和研究不端行为的持续担忧。事件也展示了独立举报人和社交媒体在揭露科研欺诈方面日益增长的影响力。 耿同学指出，医学科学与工程学院副院长常凌乾在《自然》上的论文实验数据‘完美到诡异’，疑似伪造；航空科学与工程学院教授王军的两篇论文数据前后矛盾。此前，耿同学已举报其他大学五名学者，目前均已被处理。

telegram · zaihuapd · 6月19日 16:02

**背景**: 北京航空航天大学是中国顶尖的理工科研究型大学，以航空航天和医学工程等学科著称。在《自然》发表论文被视为科学成就的重要标志，因此造假指控非常严重。近年来，中国多起学术不端事件损害了公众信任，催生了像耿同学这样的学术打假博主群体。

**标签**: `#academic integrity`, `#research misconduct`, `#data fabrication`, `#Nature`, `#China`

---