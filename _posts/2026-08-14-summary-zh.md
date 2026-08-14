---
layout: default
title: "Horizon Summary: 2026-08-14 (ZH)"
date: 2026-08-14
lang: zh
---

> 从 64 条内容中筛选出 26 条重要资讯。

---

1. [DeepSeek V4 Pro 0813 发布，开放权重](#item-1) ⭐️ 9.0/10
2. [小红书开源 280B MoE 模型，激活参数仅 16B](#item-2) ⭐️ 9.0/10
3. [苹果官宣换帅：库克卸任 CEO，特努斯接任](#item-3) ⭐️ 9.0/10
4. [Qwen 3.8 27B：小型开源模型在基准测试中匹敌前沿 AI](#item-4) ⭐️ 8.0/10
5. [GLM-5.3：前沿编程模型展现突现网络能力](#item-5) ⭐️ 8.0/10
6. [浙大开源方案 3D 指标超 Nano Banana Pro，实现平面图像立体编辑](#item-6) ⭐️ 8.0/10
7. [无训练：21B 参数 Transformer 运行经编译的 Doom 渲染器](#item-7) ⭐️ 8.0/10
8. [AI 机器人实验室大规模培养人体组织，有望取代动物试验](#item-8) ⭐️ 8.0/10
9. [美国法官令谷歌一周内移除第三方应用商店安装障碍](#item-9) ⭐️ 8.0/10
10. [PostgreSQL 修复高危 to_char 漏洞，可致任意代码执行](#item-10) ⭐️ 8.0/10
11. [苹果联手阿里自研中国专属 AI 模型，或成首个获批外企](#item-11) ⭐️ 8.0/10
12. [开发者批评：为什么 Opus 5 的沟通风格更令人难受](#item-12) ⭐️ 7.0/10
13. [《Every Fucking Website》讽刺了网页上最烦人的设计模式。](#item-13) ⭐️ 7.0/10
14. [法国最高法院否决 15 岁以下青少年社交媒体禁令](#item-14) ⭐️ 7.0/10
15. [City2Graph：面向城市系统的异构图神经网络 Python 库](#item-15) ⭐️ 7.0/10
16. [torch-preflight：静态捕获 PyTorch GPU 成本错误的 linter](#item-16) ⭐️ 7.0/10
17. [WorldProof 揭示像素指标常常无法给世界模型排名](#item-17) ⭐️ 7.0/10
18. [消融一个注意力头使国际象棋 Transformer 错过莫菲的弃后](#item-18) ⭐️ 7.0/10
19. [苹果就 App Store 收费裁决寻求最高法院审查并获暂缓执行](#item-19) ⭐️ 7.0/10
20. [Mixedbread 发布 Toast 1，专为搜索代理设计的 LLM](#item-20) ⭐️ 6.0/10
21. [DeepSeek 推出 API 峰谷定价](#item-21) ⭐️ 6.0/10
22. [llm-gemini 0.33 新增 Gemini 3.7 Flash 与 LLM 0.32 兼容](#item-22) ⭐️ 6.0/10
23. [alchemy-utils 0.1a0：sqlite-utils 的跨数据库原型](#item-23) ⭐️ 6.0/10
24. [开源 oncothresh 库在临床决策阈值上评估肿瘤学 AI 模型](#item-24) ⭐️ 6.0/10
25. [ChatGPT 生成图像中发现可复现的画布对齐模式](#item-25) ⭐️ 6.0/10
26. [信宸资本拟超 15 亿美元收购阿里游戏灵犀](#item-26) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [DeepSeek V4 Pro 0813 发布，开放权重](https://simonwillison.net/2026/Aug/12/deepseek-v4-pro-0813/) ⭐️ 9.0/10

DeepSeek V4 Pro 0813 现已通过 OpenRouter 以 API 形式提供，其开放权重也已发布到 Hugging Face（deepseek-ai/DeepSeek-V4-Pro-0813），参数量约 1.7T，文件大小 893 GB。这延续了此前 DeepSeek-V4-Pro 和 DeepSeek-V4-Flash-0731 的发布节奏。 这是 DeepSeek 一次重要的开放权重发布，DeepSeek 是少数在开放权重的同时还能逼近前沿性能的实验室之一。这一发布增强了开放权重生态系统，为开发者和研究者提供了一个可替代纯封闭 API 模型的强大选项。 该模型为纯文本的混合专家（MoE）架构，支持 100 万 token 的上下文窗口，并提供不同的推理模式（低、中、高），从 Simon Willison 用鹈鹕图片做的测试来看，不同模式会输出明显不同的结果。需要注意的是，各来源对参数量的标称略有差异：Hugging Face 发布页标注为约 1.7T 总参数，而其他资料则引用 1.6T 总参数 / 49B 激活参数。

rss · Simon Willison · 8月12日 23:59

**背景**: 开放权重模型会公开训练好的参数文件，供开发者下载、自托管和微调，这与完全封闭的 API 模型不同。DeepSeek 是中国一家重要的开放权重 AI 实验室，而 OpenRouter 是一个统一 API 网关，可访问来自众多提供商的数百个模型。MoE（混合专家）架构在每次推理时只激活部分参数，从而在高容量的同时保持较高的推理效率。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.datalearner.com/en/ai-models/pretrained-models/deepseek-v4-pro">DeepSeek-V4-Pro-0813: Specs, Pricing, API and Benchmark Boundaries ...</a></li>
<li><a href="https://deepseek-v4.io/deepseek-v4-pro">DeepSeek V4 Pro: Specs, Flash Comparison & Pricing</a></li>
<li><a href="https://ollama.com/library/deepseek-v4-pro">deepseek-v4-pro - ollama.com</a></li>

</ul>
</details>

**社区讨论**: 社区讨论主要围绕该模型的基准测试成绩展开：这些数据最初发布在 DeepSeek 官方微信群中，随后被转发到 Reddit 的 r/LocalLLaMA，但被版主以“低质量”为由删除，最终被整理成 ASCII 表格发到 Hacker News。整体氛围是好奇且活跃的，用户在讨论泄露的基准数据，并与其他模型进行对比。

**标签**: `#AI`, `#LLM`, `#DeepSeek`, `#OpenWeights`, `#ModelRelease`

---

<a id="item-2"></a>
## [小红书开源 280B MoE 模型，激活参数仅 16B](https://x.com/dotsstudioai/status/2088083314855018521) ⭐️ 9.0/10

小红书 dots 实验室开源了 dots3-note preview，这是 dots3 系列首个开放权重模型。该模型总参数 280B，采用混合专家（MoE）架构，每次仅激活 16B 参数，支持 512K 上下文窗口，并可处理文字、图片、视频和音频等多模态输入。 此次发布意义重大，因为它将一个推理效率极高（仅激活 16B 参数）的大规模 MoE 模型开放给开源社区，并附带全新的 TEMPO 强化学习方法和两个真实场景智能体基准。这可能加速高效多模态 AI 和长程智能体训练的研究与应用。 该模型引入了 TEMPO 这一新的强化学习方法，通过自批判和测试时价值估计来训练长程智能体。团队不仅在 Hugging Face 上开放了模型权重，还同步发布了 VibeSearchBench 和 VibeLifeBench 两个用于真实场景智能体评估的基准。

telegram · zaihuapd · 8月14日 08:27

**背景**: 混合专家（MoE）是一种神经网络架构，它将问题空间划分成多个区域，并将每个输入路由到一部分专家网络，从而在大幅增加参数量的同时避免计算成本同比例上升。该模型的设计——总参数 280B 而仅激活 16B——正是遵循了这一高效原则，使其在有限硬件上也能运行。新的 VibeSearchBench 针对模糊、多轮、主动搜索任务，而 VibeLifeBench 则在包含无声变化世界的模拟环境中评估生活智能体的多周任务表现。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/blog/moe">Mixture of Experts Explained - Hugging Face</a></li>
<li><a href="https://vibebench.github.io/VibeSearchBench.github.io/">VibeSearchBench — Benchmarking Long-horizon Proactive Search ...</a></li>
<li><a href="https://vibebench.github.io/VibeLifeBench_homepage/">VibeLifeBench — Can Your Life Agent Be Proactive and ...</a></li>

</ul>
</details>

**标签**: `#open-source`, `#MoE`, `#multimodal`, `#reinforcement-learning`, `#LLM`

---

<a id="item-3"></a>
## [苹果官宣换帅：库克卸任 CEO，特努斯接任](https://t.me/zaihuapd/43191) ⭐️ 9.0/10

苹果宣布管理层交接：现任 CEO 蒂姆·库克将出任董事会执行董事长，硬件工程高级副总裁约翰·特努斯将从 2026 年 9 月 1 日起担任新任 CEO。 这是苹果历史上最重要的管理层变动之一，因为蒂姆·库克自 2011 年起一直领导公司。此次交接将对苹果的产品策略及其在全球科技行业的地位产生深远影响。 董事会已一致批准这项安排。库克将在整个夏天继续担任 CEO，与特努斯完成过渡；现任董事长 Arthur Levinson 将于 9 月 1 日转任首席独立董事，特努斯同日加入董事会。特努斯 2001 年加入苹果，2013 年升任硬件工程副总裁，近年负责 iPhone、Mac、iPad、AirPods 等产品。

telegram · zaihuapd · 8月14日 11:00

**背景**: 蒂姆·库克自 2011 年起接替联合创始人史蒂夫·乔布斯担任苹果 CEO。苹果 CEO 是全球科技行业最受关注的高管职位之一，因为苹果是消费电子和服务的全球领导者。约翰·特努斯是资深的苹果高管，拥有深厚的硬件工程背景，他的晋升表明苹果将继续坚持以产品为核心的策略。

**标签**: `#Apple`, `#Tim Cook`, `#CEO transition`, `#John Ternus`, `#Tech industry`

---

<a id="item-4"></a>
## [Qwen 3.8 27B：小型开源模型在基准测试中匹敌前沿 AI](https://huggingface.co/Qwen/Qwen3.8-27B-FP8) ⭐️ 8.0/10

阿里巴巴发布了 Qwen3.8-27B，这是一款新的开源权重视觉-语言模型，能够理解图像和视频，并具备灵活的思考控制。早期社区基准测试显示，它在 DeepSWE 基准上超过了 Claude Opus 4.7 Max。 一款 27B 稠密模型击败远大于它的专有模型，表明开源、可本地运行的 AI 能够发挥远超其规模的性能。这对希望在单张 GPU 上无需 API 费用或使用限制即可获得强大性能的开发者和自托管用户意义重大。 在 FP8 精度下，该模型大约需要 27GB 显存，4-bit 量化时约需 14-16GB（不含 KV 缓存）。它是原生视觉-语言模型，因此运行时需要主 GGUF 文件和 mmproj 视觉投影文件；社区成员分享了优化的 llama.cpp 服务器命令，包括使用 170K 上下文和 flash attention。

hackernews · erdaltoprak · 8月14日 15:00 · [社区讨论](https://news.ycombinator.com/item?id=49299605)

**背景**: Qwen 是阿里巴巴的开源大语言模型系列；3.8 代包括前沿 API 模型 Qwen3.8-Max 和这款将开放权重的 27B 稠密模型。开源生态通常通过 llama.cpp 在本地运行这些模型，它可以将权重转换为 GGUF/GGML 格式并支持量化以适应消费级 GPU。由于大型前沿模型往往达到数百 GB，一个能在一张 GPU 上运行且性能强劲的 27B 模型对于私有和离线使用非常有吸引力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/Qwen/Qwen3.8-27B">Qwen/Qwen3.8-27B · Hugging Face</a></li>
<li><a href="https://www.yottalabs.ai/post/qwen-3-8-27b-specs-hardware-requirements-how-to-run-2026">Qwen 3.8 27B: Specs, Hardware Requirements, and How to Run It (2026) | Yotta Labs</a></li>
<li><a href="https://en.wikipedia.org/wiki/Llama.cpp">Llama.cpp</a></li>

</ul>
</details>

**社区讨论**: 评论者分享了在 RTX 4090 上运行该模型的 llama.cpp 具体配置技巧，指出它在 DeepSWE 上击败了 Opus 4.7 Max，并讨论了这种基准比较是否公平。人们还希望出现类似规模的 MoE 模型（如 35B A3B），并对快速、高效的本地推理表示赞赏，而不是受限于昂贵的 API 限额。

**标签**: `#AI`, `#LLM`, `#Qwen`, `#Open Source`, `#Machine Learning`

---

<a id="item-5"></a>
## [GLM-5.3：前沿编程模型展现突现网络能力](https://z.ai/blog/glm-5.3) ⭐️ 8.0/10

Z.ai 于 2026 年 8 月 14 日发布了 GLM-5.3，这是一个 743B 参数的前沿模型，专注于复杂软件工程和智能体任务。它与 GLM-5.2 使用相同的基座模型，所有改进均来自后训练，并在 CyberGym 和 AutomationBench 等基准上领先，同时展现出自主红队和漏洞发现等突现能力。 此次发布标志着前沿大语言模型现已具备自主安全工作的能力，可能从根本上改变攻防两端的网络安全实践。同时，它加剧了各 AI 实验室在编程与智能体能力上的竞争，并引发了关于此类强大模型安全与治理的紧迫问题。 这个 743B 参数的模型与 GLM-5.2 共用基座，意味着新能力完全来自后训练技术而非额外的预训练。Z.ai 还在 cvd.z.ai 推出了协调漏洞披露计划，并计划开放权重，但需先通过安全审查。

hackernews · pella · 8月14日 05:19 · [社区讨论](https://news.ycombinator.com/item?id=49294997)

**背景**: GLM 是中国 AI 公司 Z.ai 开发的一系列大语言模型，主要面向编程与智能体任务。突现能力是指模型达到一定规模后出现的意外行为，例如复杂推理或工具使用，这些能力并未被显式编程。自主红队使用 AI 模拟真实世界攻击，自动发现并串联系统中的漏洞——这项任务传统上需要深厚的人类专业知识。这些概念解释了为何 GLM-5.3 展现的零日漏洞发现与漏洞利用适配能力被认为是一个重要里程碑。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.z.ai/guides/llm/glm-5.3">GLM-5.3 - Overview - Z.AI DEVELOPER DOCUMENT</a></li>
<li><a href="https://www.explainx.ai/blog/glm-5-3-launch-cyber-defense-benchmarks-august-2026">GLM-5.3 Launch: Benchmarks, Pricing & Access (Aug 2026) - explainx.ai</a></li>
<li><a href="https://www.emergentmind.com/topics/emergent-capabilities">Emergent Capabilities in AI</a></li>

</ul>
</details>

**社区讨论**: 社区反应总体上既印象深刻又保持谨慎。一位用户报告称，GLM-5.3 成功执行了红队场景，包括利用 WordPress 零日漏洞和改编 6.8 内核漏洞。其他人则提到 Z.ai 的 CVD 计划，并指出该模型在一些利用链基准上仍落后于 Sol、Fable 和 Mythos 5 等竞争对手，同时也有用户欣赏公告中研究风格的写作。

**标签**: `#AI`, `#LLM`, `#cybersecurity`, `#GLM`, `#coding`

---

<a id="item-6"></a>
## [浙大开源方案 3D 指标超 Nano Banana Pro，实现平面图像立体编辑](https://mp.weixin.qq.com/s?__biz=MzIzNjc1NzUzMw==&mid=2247912455&idx=4&sn=646bd721ae72454672cd5129925e0112) ⭐️ 8.0/10

浙江大学研究人员开源了一种利用显式 3D 几何约束在平面图像中实现 3D 编辑的方法，该成果发表在 ACM MM'26 上。该方法据称在 3D 指标上超越了 Google DeepMind 的 Nano Banana Pro（Gemini 3 Pro Image）。 这一成果意义重大，因为它解决了当前 AI 图像编辑模型的一个关键瓶颈——这些模型往往依赖文本猜测而非显式几何信息。通过开源该方案，可以加速 3D 图像编辑领域的研究与实际应用，并可能超越主流商业模型。 该方法发表于顶级多媒体会议 ACM MM'26，相关代码已开源。它使用显式 3D 几何约束而非隐式文本推断，声称在 3D 一致性指标上优于 Nano Banana Pro。

rss · 量子位 · 8月14日 06:09

**背景**: Nano Banana Pro，即 Gemini 3 Pro Image，是 Google DeepMind 最新的图像生成与编辑模型，能够在图像中正确渲染文字。传统的 AI 图像编辑器常常因为仅从语言提示推断几何信息，而在空间和 3D 理解方面表现不佳。'显式 3D 几何约束'指的是使用实际的 3D 模型或深度信息来指导编辑过程，而非纯粹依赖学习到的先验知识。这一方法属于无训练几何渲染和高保真编辑这一更广泛趋势的一部分。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://blog.google/innovation-and-ai/products/nano-banana-pro/">Nano Banana Pro: Gemini 3 Pro Image model from Google DeepMind</a></li>
<li><a href="https://www.emergentmind.com/topics/training-free-geometric-rendering.md">emergentmind.com/topics/training-free- geometric -rendering.md</a></li>

</ul>
</details>

**标签**: `#AI`, `#Image Editing`, `#3D Geometry`, `#Computer Vision`, `#Open Source`

---

<a id="item-7"></a>
## [无训练：21B 参数 Transformer 运行经编译的 Doom 渲染器](https://www.reddit.com/r/MachineLearning/comments/1voazhm/i_compiled_dooms_renderer_into_a_21bparameter/) ⭐️ 8.0/10

作者使用自定义编译器将 Doom 的渲染算法编译成 210 亿参数的 Transformer，该编译器可将计算图转换为权重。模型生成像素绘制令牌序列，重现 E1M1 画面，且无需任何训练。 该项目表明，任意计算图都可以直接硬编码进 Transformer 权重中，从而绕过训练环节。它为机理可解释性研究提供了具体工具，并引发关于何时真正需要训练的思考。 生成的检查点是标准 Hugging Face transformers 检查点，无需 trust_remote_code 即可加载。渲染一帧需要 3,614 个令牌的提示并生成 53,747 个令牌，在 B200 上耗时超过 40 分钟，相当于约每天 35 帧。

reddit · r/MachineLearning · /u/notforrob · 8月14日 15:50

**背景**: Transformer 是一种神经网络，通常从海量数据中学习模式，但这个编译器直接根据计算图写入权重。Doom 的渲染器使用二叉空间分割（BSP）和基于列的光栅化来生成 3D 视角，最初在 486 处理器上可达 35 FPS。机理可解释性旨在将这类神经网络逆向工程为人类可理解的算法。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.doomwiki.org/wiki/Rendering_engine">Doom rendering engine - The Doom Wiki at DoomWiki.org</a></li>
<li><a href="https://en.wikipedia.org/wiki/Mechanistic_interpretability">Mechanistic interpretability</a></li>

</ul>
</details>

**标签**: `#transformers`, `#compiler`, `#mechanistic-interpretability`, `#machine-learning`, `#doom`

---

<a id="item-8"></a>
## [AI 机器人实验室大规模培养人体组织，有望取代动物试验](https://www.fastcompany.com/91589344/the-worlds-largest-biological-datacenter-could-help-make-animal-testing-obsolete) ⭐️ 8.0/10

Vivodyne 推出了它号称全球最大的人体生物数据中心：由 12 个机器人“蜂巢”实验室组成，每年可进行超过 310 万个人体组织实验，约为美国全部临床试验总规模的两倍。AI 负责设计实验，以更好地预测新药的疗效与安全性。 这标志着向用更贴近人体的模型取代动物试验迈出了重要一步，有望降低即使通过动物试验后仍有约 90%的临床试验失败率。如果获得验证，它可能会加速药物研发、降低成本，并推动生物制药行业监管标准的转变。 该系统使用衣柜大小的机器人实验室培养人体组织，并在 AI 指导下进行受控实验。Vivodyne 表示，每年 310 万次实验的规模约为美国目前开展的全部临床试验总和的约两倍。

telegram · zaihuapd · 8月14日 01:48

**背景**: 药物研发以周期长、成本高而闻名——常需长达十年、耗资超 30 亿美元——部分原因是动物模型常常无法准确预测人体反应。器官芯片和先进组织工程等技术试图利用微流控设备和培养细胞，在体外模拟人体器官的功能。Vivodyne 将该理念扩展到工业规模，通过机器人自动化大规模测试人体组织，为 AI 驱动的药物研发生成“人体数据”。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.vivodyne.com/">Vivodyne | Make biology computable</a></li>
<li><a href="https://biobuzz.io/news/penn-born-vivodyne-launches-what-it-calls-the-worlds-largest-human-biological-datacenter/">Penn-Born Vivodyne Launches What It Calls the World's Largest ...</a></li>
<li><a href="https://wyss.harvard.edu/technology/human-organs-on-chips/">Human Organs-on-Chips - Wyss Institute Organ-on-chip technology: Opportunities and challenges A guide to the organ-on-a-chip - Nature Reviews Methods Primers Organ-on-a-chip technology replicates decades of human aging ... Advances and applications of organ-on-a-chip technology</a></li>

</ul>
</details>

**标签**: `#AI`, `#biotech`, `#lab automation`, `#drug testing`, `#tissue engineering`

---

<a id="item-9"></a>
## [美国法官令谷歌一周内移除第三方应用商店安装障碍](https://www.androidauthority.com/google-play-store-remove-third-party-app-store-friction-3698697/) ⭐️ 8.0/10

美国地区法官 James Donato 下令谷歌删除 Play Store 中针对竞争对手安卓应用商店的额外警告弹窗和多余步骤。谷歌须在一周内完成修改，让第三方应用商店的安装像普通安卓应用一样直接。 这是 Epic 诉谷歌案中一项重要的反垄断救济措施，直接冲击谷歌对安卓应用分发的控制。此举有望降低竞争对手应用商店的获客门槛，改变安卓用户发现和安装应用的方式。 法院认为，这种先出现‘查看’按钮、之后才出现‘安装’按钮的多步流程，是蓄意制造的‘反竞争摩擦’，用于吓退普通用户。该命令源于陪审团此前裁定谷歌在安卓应用分发上构成非法垄断。

telegram · zaihuapd · 8月14日 09:55

**背景**: 安卓系统本身允许用户从 Play Store 之外安装应用，但 Google 长期以来对侧载应用显示安全警告并增加额外步骤。在 Epic 诉谷歌案中，Epic Games 认为这些摩擦不公平地保护了谷歌的应用商店垄断地位。本案陪审团于 2023 年 12 月裁定谷歌在安卓应用分发上构成非法垄断，本次禁令是庭审后补救措施的一部分。

**标签**: `#antitrust`, `#Google`, `#Android`, `#app stores`, `#legal`

---

<a id="item-10"></a>
## [PostgreSQL 修复高危 to_char 漏洞，可致任意代码执行](https://www.postgresql.org/support/security/CVE-2026-14669/) ⭐️ 8.0/10

PostgreSQL 披露了 CVE-2026-14669，该漏洞是 to_char(timestamptz) 函数在处理超长 POSIX 时区缩写时引发的堆缓冲区溢出。此漏洞 CVSS 评分为 8.8，已在 18.6、17.11、16.15、15.19 和 14.24 版本中修复。 该漏洞允许低权限数据库用户以 PostgreSQL 服务进程的操作系统权限执行任意代码。由于多个 PostgreSQL 主版本均受影响，这成为数据库管理员需要紧急处理的安全更新。 利用该漏洞需要拥有可以设置时区的低权限数据库账户，并非无需认证即可利用。此次小版本更新不需要转储数据库或运行 pg_upgrade，管理员只需替换程序文件并重启服务即可。

telegram · zaihuapd · 8月14日 14:35

**背景**: to_char 是 PostgreSQL 的格式化函数，用于按照指定格式将时间戳、时间间隔或数值转换为字符串。POSIX 时区规范是定义偏移量、缩写和夏令时规则的字符串，PostgreSQL 会解析这些规则。该漏洞源于解析超长时区缩写时边界检查不足，从而导致基于堆的缓冲区溢出。pg_upgrade 是用于升级 PostgreSQL 服务器实例的工具，但此次小版本更新不需要使用它。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.postgresql.org/docs/current/datatype-datetime.html">PostgreSQL: Documentation: 18: 8.5. Date/Time Types</a></li>
<li><a href="https://postgrespro.com/docs/postgrespro/13/datetime-posix-timezone-specs">Postgres Pro Standard : Documentation: 13: B.5. POSIX Time Zone ...</a></li>
<li><a href="https://www.postgresql.org/docs/current/pgupgrade.html">PostgreSQL: Documentation: 18: pg_upgrade</a></li>

</ul>
</details>

**标签**: `#PostgreSQL`, `#Security`, `#CVE`, `#Vulnerability`, `#Database`

---

<a id="item-11"></a>
## [苹果联手阿里自研中国专属 AI 模型，或成首个获批外企](https://www.reuters.com/business/retail-consumer/apple-trains-its-own-ai-model-china-market-with-alibabas-support-sources-say-2026-08-14/) ⭐️ 8.0/10

苹果正在阿里巴巴的支持下专门为中国市场训练自己的大语言模型，一改此前依赖第三方模型的策略。Apple Intelligence 预计在未来数月随 iOS 更新在华上线，中国网信办已对其生成式 AI 服务进行备案。 若获批，苹果将成为首家获准在华提供自有 AI 模型的外国公司，标志着全球科技企业应对中国严格生成式 AI 监管的一个重要里程碑。这可能会重塑中国 AI 服务市场的竞争格局。 这款中国专属模型与苹果通用版 Apple Intelligence 分开训练，针对中文语言和监管要求做了定制。据报道，网信办于 2026 年 7 月 15 日公布的备案名单将 Apple Intelligence 列为七项端侧服务之一，其中阿里巴巴的 Qwen 负责语言处理，百度负责视觉搜索。

telegram · zaihuapd · 8月14日 14:47

**背景**: Apple Intelligence 是苹果于 2024 年 6 月推出的一系列 AI 功能，结合了端侧与服务器端处理。在中国大陆，生成式 AI 服务必须先通过网信办的安全评估和算法备案，才能向公众提供服务。此前，外界预期苹果将依赖百度或阿里巴巴等本地合作伙伴来提供 AI 功能。此次举措可能为其他外国公司在中国推出 AI 服务开创先例。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Apple_Intelligence">Apple Intelligence</a></li>
<li><a href="https://www.theleveragedyears.com/ai-regulation-news/china-cac-on-device-generative-ai-filing-apple-intelligence-2026">China Publishes On-Device GenAI Filing List, Names Apple ...</a></li>

</ul>
</details>

**标签**: `#Apple`, `#AI`, `#China`, `#Alibaba`, `#Regulation`

---

<a id="item-12"></a>
## [开发者批评：为什么 Opus 5 的沟通风格更令人难受](https://mun-logadan.github.io/why-does-opus-5-feel-worse/) ⭐️ 7.0/10

一名开发者发文批评，Claude Opus 5 虽然能力更强，但由于其省略式表达和过度“诚实式坦白”的沟通方式，用起来反而更难受。该文在 Hacker News 上迅速引发讨论，获得 512 分、471 条评论。 Opus 5 是 Anthropic 面向高强度推理、编程和智能体任务的主力模型，因此其交互风格直接影响开发者体验和产品采纳。这场讨论表明，除了基准分数外，大模型的沟通质量同样会影响用户信任和迁移决策。 该批评聚焦于两种模式：句子绕着重点打转、常用无生命名词作主语以让动词“像惊喜一样落地”，以及不断承认错误、冗长解释的“坦白”风格。有评论者表示已改用 OpenAI Sol 或退回 Claude 4.8；而 Anthropic 宣称 Opus 5 能以一半价格接近其最强模型 Fable 5 的水平。

hackernews · numeri · 8月14日 10:12 · [社区讨论](https://news.ycombinator.com/item?id=49296740)

**背景**: Opus 5 是 Anthropic 的高端大语言模型，通过 Claude 和 OpenRouter 等 API 平台提供，主打高强度推理、编程和长时间运行的智能体任务。省略式表达（elliptical phrasing）指省去上下文已暗示的词语，可能让文风显得抽象和迂回。研究者已通过“坦白式”输出研究大模型的诚实性，但这种透明在日常使用中可能变得冗长乏味。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openrouter.ai/anthropic/claude-opus-5">Claude Opus 5 - API Pricing & Benchmarks | OpenRouter</a></li>
<li><a href="https://www.engadget.com/2222542/anthropic-says-opus-5-can-nearly-match-its-top-performing-model-for-half-the-price/">Anthropic Says Opus 5 Can Nearly Match Its Top-Performing Model...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Ellipsis_(linguistics)">Ellipsis (linguistics) - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍认同这一批评，称 Opus 5 的写作过于省略且令人疲惫，部分人表示已改投 OpenAI Sol 或退回 Claude 4.8。也有人提出更强的主张，认为模型质量似乎已经下降，并猜测 Anthropic 可能使用了更小或更经济的模型。讨论还争议“诚实”是否可量化，以及冗长表达是否一定是缺点。

**标签**: `#AI models`, `#LLM UX`, `#Opus 5`, `#developer experience`, `#writing quality`

---

<a id="item-13"></a>
## [《Every Fucking Website》讽刺了网页上最烦人的设计模式。](https://lxe.github.io/everywebsite/) ⭐️ 7.0/10

讽刺网站《Every Fucking Website》（位于 lxe.github.io/everywebsite/）用幽默的方式重现了最常见的烦人网页交互模式，从 cookie 横幅到新闻通讯弹窗。它很快成为开发者和设计师讨论的焦点，引发了关于这些欺骗性设计在现实世界中代价的争论。 这个网站以机智的方式盘点了各种欺骗性设计，为网页开发者和 UX 从业者提供了一个讨论“哪些做法会让用户反感”的共同参照。它的走红反映出业界越来越意识到，转化率优化策略可能会以牺牲用户信任、甚至设计师自我厌恶为代价。 这个网站托管在 GitHub Pages 上，加载速度快，而且 JavaScript 只来自其自身域名——评论者指出，对于模仿那些缓慢、脚本繁重的网站的页面来说，这很讽刺。评论者还列出了它遗漏的模式，包括自动播放视频、付费墙截断、“用 App 体验更好”的提示，以及多余的 Google 登录弹窗。

hackernews · doubletwoyou · 8月14日 14:31 · [社区讨论](https://news.ycombinator.com/item?id=49299222)

**背景**: 欺骗性设计（dark patterns）是指那些诱使用户做出非本意操作的界面设计，比如误订阅新闻通讯或同意被追踪；该术语由 Harry Brignull 于 2010 年提出。转化率优化（CRO）是一个系统性地提升网站访客完成特定行为（如购买、订阅）比例的过程，它常常依赖带有说服力甚至操纵性的设计模式。《Every Fucking Website》正是通过把所有这些恼人的模式集中到一个页面上，来讽刺这种张力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Dark_pattern">Dark pattern - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Conversion_rate_optimization">Conversion rate optimization - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者大多觉得好笑，但也不乏尖锐的批评：有人指出它遗漏了一些烦人元素，比如自动播放视频和“改用 App”的弹窗，还有人吐槽这个网站加载太快、用的第三方脚本太少。一位评论者分享了真实案例：他在自己的 Shopify 店铺加上一条‘刚刚有人购买了 X 商品’的弹窗，结果转化率明显提升，尽管这会带来‘一点点自我厌恶’。还有几条关于 bug 报告的玩笑——比如用文本浏览器打开时本以为会看到‘请更新浏览器’的提示——进一步说明这个讽刺作品有多到位。

**标签**: `#web design`, `#dark patterns`, `#UX`, `#satire`, `#performance`

---

<a id="item-14"></a>
## [法国最高法院否决 15 岁以下青少年社交媒体禁令](https://www.reuters.com/world/frances-top-court-rules-social-media-ban-curtails-freedom-expression-2026-08-14/) ⭐️ 7.0/10

2026 年 8 月 14 日，法国最高法院推翻了政府支持的 15 岁以下青少年社交媒体禁令，裁定全面的年龄验证侵犯了言论自由和隐私权。 该裁决为法国和欧洲的互联网监管树立了重要先例，对全球范围内兴起的强制年龄验证潮流构成抵制。它凸显了保护未成年人上网与维护公民自由之间的张力。 法院认为，全面的年龄验证实际上会迫使每位公民接受身份验证，对少数违规者的限制却不成比例地损害了所有人的权利。该裁决阻止了政府提出的一项措施，而非已在实施的禁令。

hackernews · BlueBerry2001 · 8月14日 16:06 · [社区讨论](https://news.ycombinator.com/item?id=49300671)

**背景**: 年龄验证是指利用技术系统核实用户年龄的做法，通常用于限制未成年人访问成人内容或社交媒体。自澳大利亚 2024 年禁止 16 岁以下用户使用社交媒体以及英国 2023 年通过《在线安全法》以来，许多国家出台了年龄验证法律。这类法律颇具争议，因为其可能导向数字身份系统，并存在政府越权的风险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Online_age_verification">Online age verification</a></li>
<li><a href="https://en.wikipedia.org/wiki/Online_age_verification_laws_by_country">Online age verification laws by country - Wikipedia</a></li>
<li><a href="https://www.newamerica.org/insights/exploring-privacy-preserving-age-verification/">Age Verification to Protect Youth Online: Using Zero Knowledge Proofs</a></li>

</ul>
</details>

**社区讨论**: 社区评论者普遍支持法院的裁决，警告年龄验证实际上会变成身份验证，并可能被滥用。有人提出替代方案，如由家长控制的儿童设备或单独的'.adult'互联网域名，还有人指出该禁令只是政府的提案，并非现行法律。

**标签**: `#law`, `#privacy`, `#age-verification`, `#internet-regulation`, `#free-speech`

---

<a id="item-15"></a>
## [City2Graph：面向城市系统的异构图神经网络 Python 库](https://www.reddit.com/r/MachineLearning/comments/1vn8oya/city2graph_a_python_library_for_heterogeneous/) ⭐️ 7.0/10

City2Graph 是一个新的开源 Python 库，可将地理空间数据转换为可直接用于空间分析、网络分析和图神经网络（GNN）的异构图。其配套论文已发表于《Computers, Environment and Urban Systems》第 130 卷（102492，2026 年）。 它填补了 GeoAI 中的一个操作空白，省去了从原始地理数据到 PyTorch Geometric 等图机器学习框架之间繁琐的数据转换工作。城市研究者和从业者现在可以更轻松地将异构图神经网络应用于城市问题，而无需手工编写数据转换代码。 该库支持形态学、交通（通过 DuckDB 处理 GTFS/GBFS）、流动性、邻近/邻接图以及异构元路径，并可在 GeoDataFrames、NetworkX、rustworkx 和 PyTorch Geometric Data/HeteroData 之间进行往返转换。代码托管在 github.com/c2g-dev/city2graph，可导入 OpenStreetMap 和 Overture Maps 数据。

reddit · r/MachineLearning · /u/Tough_Ad_6598 · 8月13日 11:59

**背景**: 异构图包含多种节点和边类型（例如建筑物、街道、站点等实体通过不同类型的关系相连），而标准图模型假定只有一种类型。图神经网络（GNN）可以从这类图中学习，但大多数地理空间数据是以平面矢量文件存储的，因此将其转换为图结构是一大瓶颈。GTFS 是公共交通时刻表的标准格式，DuckDB 是一种嵌入式 OLAP 数据库，可高效查询大型 GTFS/GBFS 数据。PyTorch Geometric 等库提供了异构图的数据结构和模型，但并不原生支持地理数据格式。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://pytorch-geometric.readthedocs.io/en/latest/notes/heterogeneous.html">Heterogeneous Graph Learning — pytorch_geometric documentation</a></li>
<li><a href="https://gtfs.org/">Home - General Transit Feed Specification</a></li>
<li><a href="https://duckdb.org/">DuckDB – An in-process SQL OLAP database management system</a></li>

</ul>
</details>

**标签**: `#Graph Neural Networks`, `#GeoAI`, `#Urban Computing`, `#Spatial Analysis`, `#Python Library`

---

<a id="item-16"></a>
## [torch-preflight：静态捕获 PyTorch GPU 成本错误的 linter](https://www.reddit.com/r/MachineLearning/comments/1vo8vv0/a_linter_for_pytorch_torchpreflight_p/) ⭐️ 7.0/10

torch-preflight 是一个面向 PyTorch 的新型静态分析工具，可以检测诸如 autograd 计算图保留、缺少 zero_grad() 调用等耗费 GPU 资源的错误。它还能在不运行代码的情况下估算训练脚本的 VRAM 使用量。 这类错误会浪费大量 GPU 小时且容易被忽视，因此在执行前捕获它们可以显著节省时间和成本。VRAM 估算功能帮助用户在付费购买 GPU 实例之前判断训练运行是否能在给定 GPU 上跑通。 该工具目前实现了 13 条规则，且不会导入或执行用户代码，因此无需 GPU 或安装 PyTorch。其 VRAM 估算据称与实测峰值相差在 4% 以内，但目前仅在单个 T4 上的四个模型上测试过。

reddit · r/MachineLearning · /u/LeJanbandhu · 8月14日 14:30

**背景**: PyTorch 使用 autograd 系统，每次迭代都会构建一个计算图；持有 loss 或中间张量的引用会导致整个计算图被保留，从而消耗 GPU 内存。在分布式训练中，使用 DistributedSampler 可以确保每个 rank 看到不同的数据子集；忘记使用它则意味着所有 rank 在每个批次上都训练相同的数据。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://pypi.org/project/torch-preflight/">torch - preflight · PyPI</a></li>
<li><a href="https://pulseaugur.com/cluster/200826-new-linter-tool-torch-preflight-catches-pytorch-coding-errors">New linter tool ' torch - preflight ' catches PyTorch coding errors...</a></li>
<li><a href="https://docs.pytorch.org/tutorials/beginner/blitz/autograd_tutorial.html">A Gentle Introduction to torch.autograd — PyTorch Tutorials 2 ...</a></li>

</ul>
</details>

**标签**: `#PyTorch`, `#linter`, `#ML engineering`, `#debugging`, `#GPU`

---

<a id="item-17"></a>
## [WorldProof 揭示像素指标常常无法给世界模型排名](https://www.reddit.com/r/MachineLearning/comments/1vnliv7/worldproof_diagnosing_where_worldmodel/) ⭐️ 7.0/10

作者发布了开源诊断工具 WorldProof，用于将世界模型 rollout 与真实结果及物理不变量进行比较。验证过程中发现，在真实机器人视频上，“最后一帧”基线就能达到 0.983 SSIM 和 53.9 dB PSNR，因此标准像素指标常常完全无法对模型进行排名。 这很重要：如果像素指标无法把“什么都不做”的基线与真实模型区分开，那么许多已发表的世界模型评测可能给出了没有意义的排名。它为社区提供了一种实用方法，用来测量评估窗口在哪些区间真正具备区分能力，而不是直接沿用基于其他数据集的论文里的默认设置。 在 30fps 的 SO-101 机械臂录制数据上，基线 SSIM 在 6 步范围内保持平稳；而在 15fps 的 DROID 数据上，模型只有在大约第 4 步到第 24 步之间才是可区分的，第 28 步之后得分稳定在约 0.20 SSIM 和 10.3 dB。作者还指出，n=8 次的 rollout 置信区间过宽，足以与数据集重叠；包含第 0 步会抬高平均标量；LPIPS 在 masked 变体上的结果与其他指标不一致。

reddit · r/MachineLearning · /u/georgia_bucea · 8月13日 19:58

**背景**: 世界模型是一类学习环境内部模拟的 AI 系统，可以根据起始上下文和一系列动作预测未来帧。这类模型通常用像素级相似度指标（如 SSIM 和 PSNR）来评估，这些指标将预测帧与真实帧进行比较。当场景运动较慢时，仅仅复制最近观察帧的“最后一帧”基线在这些指标上也能取得惊人高分，此前视频预测研究已经指出过这一点。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Video_quality">Video quality - Wikipedia</a></li>
<li><a href="https://www.academia.edu/165787940/Decomposing_Motion_and_Content_for_Natural_Video_Sequence_Prediction">(PDF) Decomposing Motion and Content for Natural Video Sequence...</a></li>
<li><a href="https://marcohkvanhurne.medium.com/world-models-are-the-next-evolution-of-ai-f0909fe1b2f9">World Models are the next evolution of AI | by Marco van... | Medium</a></li>

</ul>
</details>

**标签**: `#world-models`, `#evaluation`, `#metrics`, `#robotics`, `#open-source`

---

<a id="item-18"></a>
## [消融一个注意力头使国际象棋 Transformer 错过莫菲的弃后](https://www.reddit.com/r/MachineLearning/comments/1vmvl4w/chessformer_lens_demo_ablating_1_of_a_chess/) ⭐️ 7.0/10

一位 Reddit 用户分享了一个演示，显示在国际象棋 Transformer 的 128 个注意力头中精确消融一个头，模型便无法再找到莫菲的弃后。该演示附有可在 GitHub 复现的 notebook，并发布在 r/MachineLearning 上。 这一案例研究为机制可解释性提供了具体证据，表明复杂的下棋能力可被定位到单个注意力头，说明 Transformer 中的高层能力可能与特定组件相关。这对模型编辑、调试以及理解 Transformer 的推理方式具有重要意义。 该演示使用 ChessFormer——一种统一的国际象棋 Transformer 架构；而“莫菲的弃后”指的是保罗·莫菲著名对局中的一套弃后组合。消融通过将选中注意力头的输出置为零，并观察模型着法预测出现的变化来实现。

reddit · r/MachineLearning · /u/Weird-Asparagus4136 · 8月13日 00:29

**背景**: Transformer 使用多头注意力机制，多个注意力头并行处理信息；机制可解释性旨在逆向分析这些头如何为特定任务形成电路。ChessFormer 是一种在数十亿个国际象棋局面上训练的 Transformer，能够模拟人类决策并具备较强的下棋能力。注意力头消融是常用的可解释性技术，通过将某个头的输出置零来测量其对模型行为的因果贡献。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/ncylich/chessformer">GitHub - ncylich/chessformer</a></li>
<li><a href="https://en.wikipedia.org/wiki/Mechanistic_interpretability">Mechanistic interpretability</a></li>
<li><a href="https://arxiv.org/abs/2408.17322">[2408.17322] Investigating Neuron Ablation in Attention Heads: The Case for Peak Activation Centering</a></li>

</ul>
</details>

**标签**: `#mechanistic interpretability`, `#transformers`, `#chess`, `#attention heads`, `#ablation`

---

<a id="item-19"></a>
## [苹果就 App Store 收费裁决寻求最高法院审查并获暂缓执行](https://t.me/zaihuapd/43181) ⭐️ 7.0/10

4 月 6 日，苹果获得上诉法院许可，暂缓执行限制其对外部支付收取佣金的裁决，并计划向美国联邦最高法院提出上诉。Epic Games 随后立即对暂缓执行提出质疑。 这场法律战将决定苹果能否继续对通过其支付系统之外完成的应用内购买收取佣金，影响 App Store 数十亿美元的收入和开发者利润。最高法院的裁决可能为数字经济中的平台监管和反垄断执法树立先例。 此前，第九巡回上诉法院于 2025 年 12 月维持了针对苹果的藐视法庭认定，即尽管有初步禁令，苹果仍对使用外部支付系统的开发者收取 27%佣金。暂缓执行令暂停了该裁决，直至苹果向最高法院上诉。

telegram · zaihuapd · 8月14日 02:33

**背景**: 该争议源于 Epic Games 于 2020 年对苹果提起的反垄断诉讼，涉及 App Store 规则。2021 年，地方法院发出禁令，要求苹果允许开发者链接到外部支付方式，但驳回了 Epic 更广泛的反垄断主张。苹果随后开始对外部支付收取 27%佣金，法院后来认定其违反禁令并构成藐视法庭。暂缓执行意味着在最高法院决定是否受理上诉期间，下级法院的裁决暂不生效。

**标签**: `#Apple`, `#App Store`, `#Supreme Court`, `#Antitrust`, `#Legal`

---

<a id="item-20"></a>
## [Mixedbread 发布 Toast 1，专为搜索代理设计的 LLM](https://www.mixedbread.com/blog/toast-1) ⭐️ 6.0/10

Mixedbread 发布了 Toast 1，这是一款专门为搜索代理任务设计的大型语言模型（LLM）。该模型旨在比通用模型更有效地处理多步搜索和推理。 这一发布凸显了针对特定任务（如搜索代理）开发专用 LLM 的趋势，这可能提升复杂、多阶段信息检索的性能。同时，它也可能促使通用模型和传统搜索引擎适应由 AI 驱动的搜索体验。 该公告没有提供详细的基准测试结果，社区成员询问是否使用了相同的开源 Toast 测试框架进行比较。此外，部分人对 “Mixedbread Search” 的具体含义感到困惑，说明产品背景可能交代得不够清楚。

hackernews · mplappert · 8月14日 15:07 · [社区讨论](https://news.ycombinator.com/item?id=49299746)

**背景**: 搜索代理是一类能够自主检索、评估并基于信息采取行动的 AI 系统，通常借助搜索引擎和外部工具完成工作。像 Toast 1 这样的专用 LLM，旨在提升此类代理所需的多轮推理和工具调用能力，可能成为通用模型配合专门 RAG 管线的替代方案。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cloudinary.com/guides/digital-asset-management/search-agent">What Is a Search Agent? How It Works & Key Use Cases</a></li>
<li><a href="https://github.com/SciPhi-AI/agent-search/">GitHub - SciPhi-AI/agent-search: AgentSearch is a framework ...</a></li>
<li><a href="https://github.com/YunjiaXi/Awesome-Search-Agent-Papers">GitHub - YunjiaXi/Awesome-Search-Agent-Papers</a></li>

</ul>
</details>

**社区讨论**: 社区反应不一：有人对专用搜索 LLM 的想法表示赞赏，认为多轮搜索辅助很有价值；也有人对其新颖性持怀疑态度，并要求与更小的通用模型或非 LLM 方法进行基准对比。还有评论者希望官方能更清楚地解释产品定义和基准测试方法。

**标签**: `#LLM`, `#search`, `#AI`, `#agents`, `#mixedbread`

---

<a id="item-21"></a>
## [DeepSeek 推出 API 峰谷定价](https://api-docs.deepseek.com/news/news260813/) ⭐️ 6.0/10

DeepSeek 于 2026 年 8 月宣布为其 API 推出新的峰谷定价模式，北京时间 9:00–12:00 和 14:00–18:00 为高峰时段，费用为低谷时段的 2 倍。其余 17 小时维持标准价格，公司表示任何变更前会提前 24 小时通知。 这一价格结构意义重大，因为高峰时段与中国工作时间重合，表明 DeepSeek 的 API 需求主要来自国内。它也凸显了行业利用分时段定价来管理 AI token 成本的趋势，这可能推动 AI 推理成本走向商品化。 高峰时段为北京时间 9:00 至 12:00 和 14:00 至 18:00，每天共 7 小时，API 调用按低谷时段价格的 2 倍计费。DeepSeek 称此举是为了平衡负载、保障服务稳定，而非单纯涨价，但没有公布 V4 Flash 和 V4 Pro 相对此前的涨幅百分比。

hackernews · fagnerbrack · 8月14日 09:55 · [社区讨论](https://news.ycombinator.com/item?id=49296627)

**背景**: DeepSeek 是一家开发大语言模型的中国人工智能公司。在 AI API 中，文本会被切分为称为 token 的单元，这些单元用于训练和推理，并按单元计费；峰谷 token 定价使这些成本随时间变化，类似电力的分时计价。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.aipricing.guru/blog/deepseek-api-pricing-guide-2026/">DeepSeek API Pricing Guide 2026: V4 Peak & Off-Peak | AI ...</a></li>
<li><a href="https://runaihome.com/blog/deepseek-v4-peak-pricing-gpu-roi-2026/">DeepSeek V4 Peak-Hour Pricing 2026: Does the 2× Surcharge ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek">DeepSeek - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者注意到高峰期与中国工作时间一致，表明 DeepSeek 的客户主要来自国内。有用户表示 DeepSeek 的 Flash 模型已成为他们处理所有任务的首选，也有人询问具体涨幅。还有人开玩笑说数据中心现在会周期性地“发呆”，另有观点认为这标志着 token 正在变成一种商品，价格将不断下探。

**标签**: `#deepseek`, `#pricing`, `#ai`, `#api`, `#costs`

---

<a id="item-22"></a>
## [llm-gemini 0.33 新增 Gemini 3.7 Flash 与 LLM 0.32 兼容](https://simonwillison.net/2026/Aug/13/llm-gemini/) ⭐️ 6.0/10

llm-gemini 0.33 已发布，新增了对 Google 新 Gemini 3.7 Flash 模型的支持，同时支持 gemini-3.6-flash、gemini-3.5-flash-lite 以及两个嵌入模型。该插件还升级为兼容 LLM 0.32，支持推理痕迹和服务端工具。 此次更新为广泛使用的 CLI 插件带来了最新的 Gemini 模型和 LLM 0.32 功能（推理痕迹、服务端工具），让开发者可以方便地尝试新模型和新能力。这也反映了该生态在快速跟进模型发布的节奏。 可以通过类似 `llm -m gemini-3.7-flash -T CodeExecution 'use python to calculate (factorial of 13) * 3'` 的方式启用服务端工具。3.6 Flash 中的“minimal”思考力度选项在 3.7 中被移除；另外，由于 Safari 对空 SVG filter 元素更宽容，渲染出的 pelican 图像在不同浏览器中表现不一致。

rss · Simon Willison · 8月13日 19:37

**背景**: LLM 是 Simon Willison 开发的命令行工具和 Python 库，用于与大型语言模型交互。llm-gemini 是官方插件，让 LLM 可以访问 Google 的 Gemini 模型，支持文本生成、函数调用等功能，现在还支持服务端工具。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://simonwillison.net/2026/Aug/13/llm-gemini/">Release: llm - gemini 0.33 | Simon Willison’s Weblog</a></li>
<li><a href="https://github.com/simonw/llm-gemini">GitHub - simonw/ llm - gemini : LLM plugin to access Google's Gemini...</a></li>
<li><a href="https://llm.datasette.io/">LLM : A CLI utility and Python library for interacting with Large...</a></li>

</ul>
</details>

**标签**: `#LLM`, `#Gemini`, `#Plugin`, `#Release`, `#AI Tools`

---

<a id="item-23"></a>
## [alchemy-utils 0.1a0：sqlite-utils 的跨数据库原型](https://simonwillison.net/2026/Aug/12/alchemy-utils/) ⭐️ 6.0/10

西蒙·威利森发布了 alchemy-utils 0.1a0，这是一个早期 alpha 原型，在 SQLAlchemy 之上重新实现了 sqlite-utils 的核心 API。它支持 PostgreSQL、SQLite 和 DuckDB，并借助 Codex 和 GPT-5.6 Sol Ultra 快速构建。 这一项目可能将 sqlite-utils 便捷的数据导入和表操作工作流扩展到多种数据库引擎，而不仅限于 SQLite。它同时展示了 AI 辅助编程如何快速生成可用的原型。 该 alpha 版本支持 insert、upsert、insert_all、upsert_all、create、update 和表内省等方法，并已在 PostgreSQL、SQLite 和 DuckDB 上测试。西蒙还让 Codex 优化了 DuckDB 的 CSV 导入任务，运行时间从接近一小时缩短到约 35 秒。

rss · Simon Willison · 8月12日 19:51

**背景**: sqlite-utils 是西蒙·威利森开发的 Python 库和命令行工具，用于操作 SQLite 数据库，例如将 CSV/JSON 数据直接导入新表并运行查询。SQLAlchemy 是一个流行的 Python SQL 工具包和 ORM，为多种数据库后端提供统一接口。这个项目探索了能否在 SQLAlchemy 之上重建 sqlite-utils 的高层辅助功能，使其不限于 SQLite。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/simonw/sqlite-utils">GitHub - simonw/sqlite-utils: Python CLI utility and library ...</a></li>
<li><a href="https://sqlite-utils.datasette.io/">sqlite-utils</a></li>
<li><a href="https://pypi.org/project/alchemy-utils/">alchemy - utils · PyPI</a></li>

</ul>
</details>

**标签**: `#Python`, `#SQLAlchemy`, `#database`, `#sqlite-utils`, `#AI-assisted development`

---

<a id="item-24"></a>
## [开源 oncothresh 库在临床决策阈值上评估肿瘤学 AI 模型](https://www.reddit.com/r/MachineLearning/comments/1vod2c8/opensource_python_library_nocode_web_dashboard/) ⭐️ 6.0/10

作者发布了开源、轻依赖的 Python 库 oncothresh（v0.1），以及配套的无代码 Web 仪表盘 oncothresh-web，用于在特定临床决策阈值下评估肿瘤学 AI 模型。它提供基于阈值的指标，如灵敏度/特异度/PPV/NPV、bootstrap 置信区间、决策曲线净收益和边界加权校准。 AUC、ICC 等标准指标衡量的是整体一致性，但临床决策发生在固定阈值处，此时模型可靠性最为关键。该工具帮助病理学家和临床研究人员验证 AI 模型在决定患者处理的精确阈值上是否值得信赖，从而可能加速 AI 在肿瘤学中的安全应用。 该库基于 numpy、scipy、scikit-learn 和 pydantic 构建，面向肿瘤细胞占比、Ki-67、TMB 和 PD-L1 评分等任务，这些任务中连续输出会被转化为二分类决策。仪表盘支持 CSV 上传、阈值选择和 PDF 报告生成，通过本地 docker compose 运行，无云依赖。

reddit · r/MachineLearning · /u/adom2989 · 8月14日 17:06

**背景**: 肿瘤学 AI 模型通常输出连续分数，但在临床护理中，固定阈值决定患者是否被标记、活检或治疗。现有的病理学基准如 PathBench 和 PathBench-MIL 是对基础模型进行全局评估，但并未在预定义临床阈值下结合不确定性量化来评估性能。oncothresh 通过强调反映真实临床决策的指标来填补这一空白。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/omkaradhali/oncothresh">GitHub - omkaradhali/oncothresh: Clinical threshold ...</a></li>
<li><a href="https://github.com/omkaradhali/oncothresh-web">GitHub - omkaradhali/oncothresh-web: Threshold-aware ...</a></li>
<li><a href="https://pypi.org/project/oncothresh/">oncothresh · PyPI</a></li>

</ul>
</details>

**标签**: `#oncology AI`, `#clinical ML`, `#model evaluation`, `#open-source`, `#medical imaging`

---

<a id="item-25"></a>
## [ChatGPT 生成图像中发现可复现的画布对齐模式](https://www.reddit.com/r/MachineLearning/comments/1vnq08v/reproducible_canvasaligned_lowlevel_patterns_in/) ⭐️ 6.0/10

一位 Reddit 用户通过实验发现，ChatGPT 独立生成的‘纯黑’图像之间共享一种可复现、锁定在画布坐标上的低级图案，非零像素掩模的相关系数高达 0.848。迭代式编辑产生的人工痕迹可能与此图案有关。 这一观察表明，ChatGPT 图像输出可能包含确定性的、与画布对齐的结构——无论来自水印（如 SynthID）还是模型架构本身。它有助于调试生成式编辑的伪影问题，并引发关于图像归因与可追溯性的讨论。 作者发现非零掩模的 Jaccard 重叠度为 0.766（随机预期约 0.071），主导空间频率峰值在 2.45 像素和 5.57 像素处相似；经高斯模糊（sigma=16）后，两幅图像均显示相似的云状结构，交叉相关在零滞后处达到峰值。编辑前将图像平移 20 像素会改变伪影行为，而面部/身体区域似乎比背景更‘受保护’。

reddit · r/MachineLearning · /u/DickHorner · 8月13日 22:52

**背景**: ChatGPT 中的迭代式生成编辑会积累人工痕迹，包括‘同聊天残影’（同一会话中先前图像会在后续图像中留下淡痕）。作者的实验表明，至少部分人工痕迹源于一种可复现、锁定画布的低级图案。尽管原因尚未得到确认，该图案可能暗示内部掩模、确定性生成组件或 SynthID 之类的隐藏水印。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://apipass.dev/blogs/how-to-solve-gpt-image-2-artifacting-issues">How to Solve GPT Image 2 Artifacting Issues</a></li>
<li><a href="https://notegpt.io/gpt-image-2">GPT Image 2 (ChatGPT Images 2.0): Free Online, No Sign-up</a></li>

</ul>
</details>

**标签**: `#image generation`, `#generative editing`, `#artifacts`, `#ChatGPT`, `#machine learning`

---

<a id="item-26"></a>
## [信宸资本拟超 15 亿美元收购阿里游戏灵犀](https://www.bloomberg.com/news/articles/2026-08-14/trustar-is-said-to-near-1-5-billion-deal-for-alibaba-gaming-arm) ⭐️ 6.0/10

中信集团旗下私募机构信宸资本（Trustar Capital）正接近收购阿里巴巴旗下游戏部门灵犀互娱，交易估值或超 15 亿美元。信宸资本在击败多家游戏公司等竞购者后成为最可能买家，但磋商仍在进行，尚未做出最终决定。 这笔交易标志着阿里巴巴在 CEO 吴泳铭领导下继续剥离非核心资产，以聚焦 AI 与云计算。同时，它也显示出私募股权对亚洲游戏资产的兴趣日益浓厚，可能重塑中国游戏行业的格局。 灵犀的旗舰游戏《三国志·战略版》是与日本光荣特库摩合作开发的大型多人在线策略游戏。该交易仍在磋商中，尚未达成最终协议，估值可能超过 15 亿美元。

telegram · zaihuapd · 8月14日 10:24

**背景**: 灵犀互娱是阿里巴巴集团旗下的数字互动娱乐企业，采用'研运一体'模式，业务涵盖游戏研发与发行。它源于阿里巴巴 2015 年提出的'Double H'战略中'Happiness'部分，旗下拥有《三国志·战略版》等产品。信宸资本（Trustar Capital）是中信资本的私募股权投资平台，也是中国最成熟的并购投资平台之一。在 CEO 吴泳铭推动下，阿里巴巴近期正剥离非核心资产，将资源聚焦于 AI 与云计算。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://baike.baidu.com/item/灵犀互娱/68094905">灵犀互娱 - 百度百科</a></li>
<li><a href="https://www.citiccapital.com/zh/business/private-equity/">私募股权投资 - Citic Capital</a></li>
<li><a href="https://www.lingxigames.com/">灵犀互娱官网</a></li>

</ul>
</details>

**标签**: `#Alibaba`, `#M&A`, `#Gaming`, `#Corporate Strategy`, `#Tech Industry`

---