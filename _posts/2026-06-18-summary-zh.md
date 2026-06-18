---
layout: default
title: "Horizon Summary: 2026-06-18 (ZH)"
date: 2026-06-18
lang: zh
---

> 从 70 条内容中筛选出 29 条重要资讯。

---

1. [发现 1 万个 GitHub 仓库散布木马恶意软件](#item-1) ⭐️ 9.0/10
2. [GLM-5.2 可能是最强大的开放权重纯文本大语言模型](#item-2) ⭐️ 9.0/10
3. [Transformer 论文作者 Noam Shazeer 加入 OpenAI](#item-3) ⭐️ 8.0/10
4. [Ubiquiti 发布基于 ZFS 的企业级 NAS](#item-4) ⭐️ 8.0/10
5. [康奈尔大学 CS 6120 高级编译器自学课程引发社区讨论](#item-5) ⭐️ 8.0/10
6. [Modos 推出 13.3 英寸彩色电子纸显示器，刷新率达 60Hz](#item-6) ⭐️ 8.0/10
7. [Datasette 1.0a34 新增 Web 界面直接数据操作功能](#item-7) ⭐️ 8.0/10
8. [美国对 Anthropic 的 AI 出口管制助推深度求索获 74 亿美元融资及 npm 供应链攻击](#item-8) ⭐️ 8.0/10
9. [Rosetta 神经元亚线性增长，选择性与单语义性增强](#item-9) ⭐️ 8.0/10
10. [微软 NextLat：学习紧凑信念状态，实现 3.3 倍推理加速](#item-10) ⭐️ 8.0/10
11. [使用对比目标 SFT 绘制 LLM 因果依赖图](#item-11) ⭐️ 8.0/10
12. [医院和大学以低 90%成本重新利用现有药物](#item-12) ⭐️ 7.0/10
13. [Emacs 31 即将发布，带来日常使用的新功能](#item-13) ⭐️ 7.0/10
14. [AI 颠覆代码生产的经济学](#item-14) ⭐️ 7.0/10
15. [对话级语音调试比孤立基准指标实用得多](#item-15) ⭐️ 7.0/10
16. [苹果与英特尔达成初步芯片代工协议](#item-16) ⭐️ 7.0/10
17. [小米开源智能家居框架 Miloco 2.0 发布](#item-17) ⭐️ 7.0/10
18. [瑞士议会解除新建核电站禁令](#item-18) ⭐️ 6.0/10
19. [Craigslist 创始人 Craig Newmark 捐款超 5 亿美元](#item-19) ⭐️ 6.0/10
20. [W Social 与欧洲数字主权的表演](#item-20) ⭐️ 6.0/10
21. [Submission.Directory：精选的初创公司提交网站目录](#item-21) ⭐️ 6.0/10
22. [DeepSeek 聊天应用新增图像理解功能](#item-22) ⭐️ 6.0/10
23. [新的 Web 组件延迟 GIF 加载直至点击](#item-23) ⭐️ 6.0/10
24. [推测性解码：热门的大语言模型推理技术](#item-24) ⭐️ 6.0/10
25. [分析语言模型可解释性中探针的相对强度](#item-25) ⭐️ 6.0/10
26. [扎克伯格承认 Meta AI 重组犯错，承诺 2026 年不裁员](#item-26) ⭐️ 6.0/10
27. [ChatGPT 定时任务新增专用页面与监控通知](#item-27) ⭐️ 6.0/10
28. [传谷歌考虑采购长鑫存储 DRAM 应对短缺与价格压力](#item-28) ⭐️ 6.0/10
29. [谷歌测试需摄像头手势验证的新版 reCAPTCHA](#item-29) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [发现 1 万个 GitHub 仓库散布木马恶意软件](https://orchidfiles.com/github-repositories-distributing-malware/) ⭐️ 9.0/10

安全研究员发现 1 万个 GitHub 仓库正在主动散布木马恶意软件，暴露了关键供应链风险以及对开源信任的滥用。 这一发现凸显了软件供应链的严重漏洞，威胁到依赖开源代码的开发者和组织，可能导致大规模数据泄露。 恶意软件针对 AI 编程代理而非人类，利用新账户和频繁提交以在搜索结果中浮现，同时克隆新仓库以规避检测。

hackernews · theorchid · 6月18日 11:45 · [社区讨论](https://news.ycombinator.com/item?id=48583928)

**背景**: 供应链安全旨在保护软件开发生命周期免受恶意干扰。GitHub 作为核心开源平台促进了协作，但可能被滥用，向广泛使用的代码库注入恶意软件，利用了开源所依赖的信任模型。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Supply_chain_security">Supply chain security</a></li>

</ul>
</details>

**社区讨论**: 评论者一致认为存在系统性漏洞：恶意软件针对 AI 代理，GitHub 对此问题处理不力，搜索引擎可能将用户导向恶意仓库。普遍呼吁加强平台安全。

**标签**: `#malware`, `#github`, `#supply-chain-security`, `#cybersecurity`, `#open-source`

---

<a id="item-2"></a>
## [GLM-5.2 可能是最强大的开放权重纯文本大语言模型](https://simonwillison.net/2026/Jun/17/glm-52/#atom-everything) ⭐️ 9.0/10

智谱 AI（Z.ai）发布了 GLM-5.2，这是一个采用 MIT 许可证的 753B 参数混合专家（MoE）大语言模型，支持 100 万 token 的上下文窗口，在 Artificial Analysis 智能指数上位居开放权重模型榜首。 该发布提供了一个性能顶尖、许可宽松的开放模型，推动了开放人工智能的研究与开发，其大上下文窗口和强大能力可与闭源系统媲美，适用于复杂任务。 该模型拥有 7530 亿参数，每次推理激活 40 个专家（MoE），权重文件 1.51TB，采用 MIT 许可证，上下文窗口达 100 万 token。尽管是纯文本模型，却在 Code Arena WebDev 排行榜上排名第二，但每次基准任务消耗约 43,000 个输出 token，令牌消耗较高。

rss · Simon Willison · 6月17日 23:58

**背景**: 混合专家（MoE）是一种架构，每次输入仅激活部分参数（专家），从而在合理算力下训练巨大模型。开放权重指模型的已训练参数被公开，但不一定包括完整训练流程。token 上下文窗口决定了模型一次能处理的输入文本长度。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mixture_of_experts">Mixture of experts - Wikipedia</a></li>
<li><a href="https://opensource.org/ai/open-weights">Open Weights: not quite what you’ve been told – Open Source ...</a></li>
<li><a href="https://www.geeksforgeeks.org/artificial-intelligence/tokens-and-context-windows-in-llms/">Tokens and Context Windows in LLMs - GeeksforGeeks</a></li>

</ul>
</details>

**标签**: `#AI`, `#LLM`, `#open-source`, `#GLM-5.2`, `#language-model`

---

<a id="item-3"></a>
## [Transformer 论文作者 Noam Shazeer 加入 OpenAI](https://twitter.com/NoamShazeer/status/2067400851438932297) ⭐️ 8.0/10

《Attention Is All You Need》论文合著者、曾任 Google Gemini 联合负责人的 Noam Shazeer 将离开 Google 加入 OpenAI，这是他通过 2024 年人才收购协议短暂回归后的第二次离职。 对于 OpenAI 而言，Shazeer 的加入是一次重大人才收获，带来了支撑现代 AI 的 transformer 架构的深厚专业知识。这加剧了 Google 与 OpenAI 在先进 AI 系统竞争中的对抗。 Shazeer 于 2021 年离开 Google 联合创立 Character.AI；2024 年 Google 以 27 亿美元收购 Character.AI 人才后他回归，并被任命为 Gemini 联合负责人。他迅速离职加入 OpenAI 凸显了 AI 行业的人才流动性。

hackernews · lukasgross · 6月18日 00:26 · [社区讨论](https://news.ycombinator.com/item?id=48578913)

**背景**: Transformer 架构由包括 Noam Shazeer 在内的 Google 研究员在 2017 年论文《Attention Is All You Need》中提出，通过实现高效的序列数据并行处理，彻底改变了深度学习。它成为 GPT 和 Gemini 等大语言模型的基础。Shazeer 被视为该技术的关键先驱之一。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Transformer_architecture">Transformer architecture</a></li>
<li><a href="https://en.wikipedia.org/wiki/Attention_Is_All_You_Need">Attention Is All You Need - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区讨论强调 Shazeer 在重新加入 Google 后迅速离职的意外性。一些人猜测公司内部动态或 OpenAI 的机会可能是动机。另一些人担心这可能影响 Google 的开源模型进展，并注意到知名 AI 研究员在顶尖实验室之间流动的更广泛趋势。

**标签**: `#AI`, `#transformers`, `#talent-move`, `#OpenAI`, `#Google`

---

<a id="item-4"></a>
## [Ubiquiti 发布基于 ZFS 的企业级 NAS](https://blog.ui.com/article/introducing-enterprise-nas) ⭐️ 8.0/10

Ubiquiti 推出了一款全新的企业级 NAS 存储解决方案，基于 ZFS 文件系统，售价 3999 美元，配备双 25Gb SFP28 端口和冗余电源。 这标志着 Ubiquiti 进军企业存储市场，其基于 ZFS 的产品承诺无月费，可能颠覆依赖订阅模式的传统供应商，同时利用 ZFS 的数据完整性和容错特性。 该 NAS 支持双 25Gb SFP28 网络接口，但社区成员质疑机械硬盘是否能充分利用如此高速的链路；实际性能可能需要大量调优，且部分人对 Ubiquiti 的企业级成熟度持谨慎态度。

hackernews · ksec · 6月18日 14:24 · [社区讨论](https://news.ycombinator.com/item?id=48585866)

**背景**: ZFS 是一种开源文件系统和卷管理器，以数据完整性、容错性和通过默克尔树实现的高效增量备份而闻名，最初由 Sun Microsystems 开发。Ubiquiti 是一家网络硬件公司，以其 UniFi 和 EdgeMax 产品线闻名，通常提供性价比高、无需订阅的解决方案，深受中小企业和技术爱好者青睐。企业级 NAS 设备用于企业集中存储数据，要求高可用性和可靠性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ZFS">ZFS</a></li>
<li><a href="https://en.wikipedia.org/wiki/OpenZFS">OpenZFS - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区反应不一：许多人称赞采用 ZFS 且无月费，但有经验的用户警告 Ubiquiti 的产品常给人‘在生产环境中测试’的感觉，可能并非真正的企业级就绪；机械硬盘的性能也是一大担忧。

**标签**: `#NAS`, `#ZFS`, `#Ubiquiti`, `#enterprise-storage`, `#announcement`

---

<a id="item-5"></a>
## [康奈尔大学 CS 6120 高级编译器自学课程引发社区讨论](https://www.cs.cornell.edu/courses/cs6120/2025fa/self-guided/) ⭐️ 8.0/10

康奈尔大学 2020 年创建的 CS 6120 高级编译器课程的自学版本再次在 Hacker News 上被分享，引发了关于其内容的重新讨论，尤其是关于动态编译的部分。 这门免费课程是学习高级编译器主题的宝贵资源，但社区反馈指出其在现代动态编译技术方面的论述可能存在不足，因此潜在学习者有必要了解其局限性。 动态编译部分主要集中于跟踪编译（trace compilation），这被认为已过时；批评者指出缺少类型反馈、推测、去优化等重要概念。也有人质疑课程内容是否真正‘高级’，因为它涵盖了死代码消除和 SSA 形式等基础主题。

hackernews · ibobev · 6月18日 11:04 · [社区讨论](https://news.ycombinator.com/item?id=48583606)

**背景**: CS 6120 是康奈尔大学的研究生级别编译器课程，涵盖数据流分析、优化和代码生成等主题。动态编译是指在运行时编译代码以提高性能，即时编译（JIT）是一种常见形式。跟踪编译是一种较老的动态编译技术，通过识别和优化频繁执行的路径来实现。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Dynamic_compilation">Dynamic compilation</a></li>
<li><a href="https://www.freecodecamp.org/news/just-in-time-compilation-explained/">Just in Time Compilation Explained</a></li>

</ul>
</details>

**社区讨论**: 总体而言，社区赞扬了该课程的深度和易用性，但一些专家指出动态编译部分已过时，侧重于跟踪编译而非现代技术。有人质疑该课程是否应标记为‘高级’，因为它包含了基础主题。其他人将其与 Nora Sandler 的编写 C 编译器等其他编译器资源进行了比较。

**标签**: `#compilers`, `#education`, `#online-course`, `#programming-languages`, `#hackernews`

---

<a id="item-6"></a>
## [Modos 推出 13.3 英寸彩色电子纸显示器，刷新率达 60Hz](https://spectrum.ieee.org/modos-e-paper-monitor) ⭐️ 8.0/10

Modos 是一家两人创业公司，正在开发一款 13.3 英寸彩色电子纸显示器，原生分辨率为 3200x2400，支持触摸输入，刷新率达 60Hz，推动了电子纸显示技术的发展。 这一进展为低功耗、户外可读显示器开辟了新可能，可减轻长时间工作时的眼睛疲劳，标志着在众多使用场景中替代传统液晶屏迈出了重要一步。 该显示器支持 60Hz 刷新率，这对电子纸技术来说异常快速，可能影响面板寿命；具体可视屏幕尺寸和精确的彩色技术（如 E Ink Kaleido）尚未确认。

hackernews · Vinnl · 6月18日 11:41 · [社区讨论](https://news.ycombinator.com/item?id=48583897)

**背景**: 电子纸是一种模拟纸张的显示技术，通过反射光线实现显示，具有高户外可读性和极低功耗。传统电子纸刷新率较慢，多为黑白；近几年彩色电子纸通过 E Ink 的 Kaleido 等技术问世，但在色彩准确度和刷新速度上仍有局限。外部电子纸显示器是一个小众产品类别，旨在减轻阅读、编程和写作时的视觉疲劳，但过去产品分辨率低、反应迟缓。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://grokipedia.com/page/External_E_Ink_Monitor">External E Ink Monitor</a></li>
<li><a href="https://goodereader.com/blog/electronic-readers/the-best-color-e-readers-of-2025">The Best Color e-readers of 2025 - Good e-Reader</a></li>

</ul>
</details>

**社区讨论**: 社区成员对该显示器的规格表示兴奋，有人质疑 60Hz 刷新率对面板寿命的影响，还有人询问屏幕尺寸。人们将其与 Daylight 计算机和 Boox 设备比较，凸显对辅助低功耗显示器日益增长的兴趣。

**标签**: `#e-paper`, `#display-technology`, `#hardware`, `#startups`, `#hackernews`

---

<a id="item-7"></a>
## [Datasette 1.0a34 新增 Web 界面直接数据操作功能](https://simonwillison.net/2026/Jun/16/datasette/#atom-everything) ⭐️ 8.0/10

Datasette 的 alpha 版本 1.0a34 现在允许用户直接在 Web 界面的表格和行页面上插入、编辑和删除数据行。 这项期待已久的功能将 Datasette 从只读的数据探索工具转变为轻量级数据管理平台，大幅提升了其在交互工作流程中的实用性。 编辑和删除操作可作为行页面上的操作项使用，此外还有表级控件。这一改动源于 Datasette Agent 最近新增的 SQL 写入支持，该功能凸显了在聊天界面中能写入而标准 UI 中却不能的矛盾。

rss · Simon Willison · 6月16日 21:31

**背景**: Datasette 是 Simon Willison 开发的开源工具，用于探索和发布 SQLite 数据库。此前其 Web 界面为只读，用户只能查询和浏览数据而无法修改。Datasette Agent 是一个可扩展的 AI 助手插件，能通过自然语言与 SQLite 数据库交互，近期新增了执行写入 SQL 语句的功能。开发者意识到通过 Agent 可以写入而核心 UI 却不能，这是一个明显的缺口，直接促成了此次更新。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://agent.datasette.io/">Datasette Agent: an AI assistant for Datasette to help explore and analyze data in SQLite</a></li>
<li><a href="https://datasette.io/blog/2026/datasette-agent/">Datasette Agent, an extensible AI assistant for Datasette - Datasette Blog</a></li>

</ul>
</details>

**标签**: `#datasette`, `#release`, `#data exploration`, `#sqlite`, `#user interface`

---

<a id="item-8"></a>
## [美国对 Anthropic 的 AI 出口管制助推深度求索获 74 亿美元融资及 npm 供应链攻击](https://aiweekly.co/issues/america-blocked-its-best-ai-china-just-raised-74-billion) ⭐️ 8.0/10

美国限制外国访问 Anthropic 的顶级 AI 模型，迅速促使中国竞争对手深度求索完成 74 亿美元融资，并引发政府对 Cohere 的兴趣激增。同时，发现了 144 个恶意 npm 包，通过污染 AI 软件供应链窃取凭证。 原本旨在保护美国 AI 领先地位的出口管制，反而加速了中国开源替代方案的发展，并暴露了全球 AI 供应链的关键漏洞，可能削弱美国的主导地位。 深度求索的模型采用混合专家架构，训练成本仅为美国模型的一小部分，但性能可与 GPT-4 媲美。npm 攻击涉及窃取发布令牌，向广泛使用的包中注入代码，用于窃取凭证和横向移动。

rss · AI Weekly · 6月17日 00:00

**背景**: Anthropic 是一家以 Claude 模型闻名的美国 AI 公司，深度求索是一家中国初创企业，其开源权重模型因在美芯片制裁下高效训练而受到关注。npm（Node 包管理器）是 JavaScript 库的注册中心，常常成为供应链攻击的目标，攻击者通过入侵流行包来传播恶意软件。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek">DeepSeek</a></li>
<li><a href="https://www.rescana.com/post/in-depth-analysis-supply-chain-poisoning-of-popular-npm-packages-exploiting-event-stream-ua-parser">In-Depth Analysis: Supply Chain Poisoning of Popular npm Packages ...</a></li>

</ul>
</details>

**标签**: `#AI policy`, `#export controls`, `#supply chain security`, `#DeepSeek`, `#npm`

---

<a id="item-9"></a>
## [Rosetta 神经元亚线性增长，选择性与单语义性增强](https://www.reddit.com/r/MachineLearning/comments/1u9g7lk/neuron_populations_exhibit_divergent_selectivity/) ⭐️ 8.0/10

一项新研究揭示，跨架构和任务普遍存在的 Rosetta 神经元随模型规模呈亚线性扩展，选择性/单语义性增强。单个此类神经元即可有效过滤预训练数据，接近预言机过滤性能。 这连接了可解释性与扩展定律，表明更大的模型会产生更专业、可解释的特征。并提供了轻量级数据过滤方法，可能降低训练成本。 关键细节：神经元遵循亚线性幂律（指数小于 1），其单语义性通过特征单语义性得分衡量，单个神经元的激活可用于数据过滤，接近全量预言机效果。

reddit · r/MachineLearning · /u/avd4292 · 6月18日 19:40

**背景**: Rosetta 神经元是 2023 年提出的一种方法，用于寻找不同模型中编码相同视觉概念的神经元。神经扩展定律描述了模型大小、数据集大小和性能之间的幂律关系。单语义性指特征可单独解释，通常通过稀疏自编码器提取，在语言模型中已有研究。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2306.09346">[2306.09346] Rosetta Neurons: Mining the Common Units in a Model Zoo</a></li>
<li><a href="https://transformer-circuits.pub/2024/scaling-monosemanticity/">Scaling Monosemanticity: Extracting Interpretable Features from Claude 3 Sonnet</a></li>
<li><a href="https://www.pnas.org/doi/10.1073/pnas.2311878121">Explaining neural scaling laws - PNAS</a></li>

</ul>
</details>

**标签**: `#interpretability`, `#scaling-laws`, `#neural-networks`, `#representation-learning`, `#research`

---

<a id="item-10"></a>
## [微软 NextLat：学习紧凑信念状态，实现 3.3 倍推理加速](https://www.reddit.com/r/MachineLearning/comments/1u84mio/nextlatent_prediction_transformers_r/) ⭐️ 8.0/10

微软研究院提出了 NextLat 方法，通过自监督学习让 Transformer 在预测下一个 token 的同时预测自身的下一个潜在状态。这生成了紧凑的信念状态，提高了数据效率，并通过自推测解码实现高达 3.3 倍的推理加速。 NextLat 超越了短视的下一个 token 预测，构建了更丰富的世界模型，提升了推理和规划能力。自推测解码的加速无需额外的草案模型，使大语言模型在实时应用中更具可行性。 NextLat 增加了一个损失函数，从当前潜在状态和下一个 token 预测下一个潜在状态，提供了比独热 token 更密集的监督信号。自推测解码利用模型自身层进行草案生成和验证，无需外部组件。

reddit · r/MachineLearning · /u/jayden_teoh_ · 6月17日 08:44

**背景**: 下一个 token 预测是自回归模型的标准方法，但可能目光短浅，因为它关注局部结构而非长期依赖。推测解码通过小草案模型生成候选 token 再由大模型验证来加速推理；自推测解码则使用模型自身的部分层实现草案生成，如 LayerSkip 所示。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2511.05963">[2511.05963] Next-Latent Prediction Transformers Learn Compact World Models</a></li>
<li><a href="https://www.emergentmind.com/topics/next-latent-prediction-nextlat">Next-Latent Prediction Overview</a></li>

</ul>
</details>

**标签**: `#transformers`, `#self-supervised learning`, `#representation learning`, `#speculative decoding`, `#language models`

---

<a id="item-11"></a>
## [使用对比目标 SFT 绘制 LLM 因果依赖图](https://www.reddit.com/r/MachineLearning/comments/1u8if6l/contrastive_targeted_sft_as_a_mechinterp_method/) ⭐️ 8.0/10

在 r/MachineLearning 上的一篇帖子提出了一项实验计划，利用对比目标监督微调（SFT）和消融技术，构建大语言模型内部能力维度的因果依赖图。该方法通过对单一维度进行对比训练，定位电路，然后测量跨维度性能下降以推断因果关系。 这种闭环方法可以揭示 LLM 能力之间的结构关系，为更高效的训练策略和更好的行为控制提供指导。它在一个实用框架内将机械可解释性与目标微调连接起来。 该计划从同一基础模型出发，分别用维度深度和浅度示例训练两个检查点，通过对比定位电路，然后消融注意力头，并用 40 领域的评判器检测其他维度的评分下降。开放挑战包括区分直接与间接因果效应，以及用激活操控诊断验证图，但作者缺乏 ML 背景且尚无实验结果。

reddit · r/MachineLearning · /u/Substantial_Diver469 · 6月17日 18:31

**背景**: 机械可解释性旨在通过分析内部计算来逆向工程神经网络，类似于理解二进制程序。消融研究通过移除组件（如注意力头）来评估其影响，是可解释性的常用工具。对比训练使用成对示例突出差异，常用于强化特定能力。目标 SFT 在策划的数据上微调模型以提升特定技能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mechanistic_interpretability">Mechanistic interpretability</a></li>
<li><a href="https://en.wikipedia.org/wiki/Ablation_(artificial_intelligence)">Ablation (artificial intelligence) - Wikipedia</a></li>
<li><a href="https://www.alignmentforum.org/posts/jP9KDyMkchuv6tHwm/how-to-become-a-mechanistic-interpretability-researcher">How To Become A Mechanistic Interpretability Researcher</a></li>

</ul>
</details>

**标签**: `#mechanistic interpretability`, `#contrastive training`, `#causal discovery`, `#fine-tuning`, `#large language models`

---

<a id="item-12"></a>
## [医院和大学以低 90%成本重新利用现有药物](https://www.kcl.ac.uk/news/hospitals-and-universities-repurposing-drugs-at-90-lower-cost) ⭐️ 7.0/10

医院和大学成功将现有药物重新用于新的适应症，通过绕过昂贵的专利替代品，实现了大幅成本降低，通常高达 90%。 此方法揭示了专利策略和定价结构如何抬高药价，并展示了一条使基本治疗更负担得起且广泛可用的切实途径，尤其是针对罕见病。 眼科医生使用贝伐珠单抗（Avastin）治疗黄斑变性，而非近乎相同的雷珠单抗（Lucentis），每剂费用分别为 50 美元和 1500 美元。同样，艾氯胺酮（Spravato）是氯胺酮的专利异构体，尽管可能不如通用氯胺酮有效，但保险公司仍需支付数千美元。

hackernews · giuliomagnifico · 6月18日 10:33 · [社区讨论](https://news.ycombinator.com/item?id=48583386)

**背景**: 药物再利用为已批准药物寻找新用途，大幅降低开发成本。制药公司常常为专利过期药物的略微修改版本申请专利，以维持高价。本新闻突显医院和大学如何直接使用更廉价、临床等效的专利过期药物来规避这种做法。

**社区讨论**: 评论者强调了因专利导致的几乎相同药物间的巨大成本差异，如 Avastin（50 美元）与 Lucentis（1500 美元）。他们还讨论了艾氯胺酮（Spravato），一种专利的、效果较差的通用氯胺酮版本，却花费数千美元。讨论强烈支持药物再利用倡议，尤其是针对罕见病，并普遍批评制药定价和影响力。

**标签**: `#drug-repurposing`, `#healthcare`, `#patents`, `#innovation`, `#hackernews`

---

<a id="item-13"></a>
## [Emacs 31 即将发布，带来日常使用的新功能](https://www.rahuljuliato.com/posts/emacs-31-around-the-corner) ⭐️ 7.0/10

一位用户在 Emacs 31 正式发布前分享了他们已经在日常使用的功能，突出了即将到来的实际改进。 这一消息引发了热烈的社区讨论，再次证明了 Emacs 持久的价值、高度可配置性以及日益增长的人工智能集成，即便面对现代编辑器，它依然具有重要地位。 虽然摘要中没有详细列出具体功能，但讨论强调了 Emacs 高效的光标移动、通过 init.el 配置 LLM 代理，以及用户掌控升级的稳定性。

hackernews · frou_dh · 6月18日 12:10 · [社区讨论](https://news.ycombinator.com/item?id=48584135)

**背景**: GNU Emacs 是一款高度可扩展的文本编辑器，最早发布于 1976 年，以陡峭的学习曲线和通过 Emacs Lisp 进行的强大自定义著称。它在重视完全掌控工具的开发者中仍然很受欢迎。

**社区讨论**: 评论中既有使用 Emacs 长达 34 年的用户称赞其键盘快捷键和广泛支持，也有人提到与 Claude AI 和 LLM 代理的集成。很多人强调，与强制更新相比，Emacs 的主动选择和稳定性更让人安心。

**标签**: `#emacs`, `#text-editors`, `#release-notes`, `#productivity`, `#open-source`

---

<a id="item-14"></a>
## [AI 颠覆代码生产的经济学](https://simonwillison.net/2026/Jun/17/charity-majors/#atom-everything) ⭐️ 7.0/10

Charity Majors 指出，2025 年 AI 使代码生成几乎免费且即时，代码从被珍视的资产变为可抛弃的商品。 这一转变要求更强的工程纪律，因为代码不再稀缺，工程师必须更关注架构、测试和可维护性而非单纯的生产。 该引言出自 Charity Majors 的 Substack 文章《AI 要求更多的工程纪律，而非更少》，她认为廉价代码使得审查和测试等严格实践更加必要。

rss · Simon Willison · 6月17日 17:12

**背景**: 传统软件开发模式视代码为宝贵的劳动密集型资产；像 LLM 这样的生成式 AI 工具现在能快速产出大量代码，促使人们重新思考软件工程实践。

**标签**: `#ai`, `#generative-ai`, `#ai-assisted-programming`, `#software-engineering`, `#economics`

---

<a id="item-15"></a>
## [对话级语音调试比孤立基准指标实用得多](https://www.reddit.com/r/MachineLearning/comments/1u99fe5/voice_debugging_at_the_conversation_level_seems/) ⭐️ 7.0/10

一位实践者指出，像语音识别准确率和延迟这样的孤立指标无法捕捉会话层面涌现的问题，而对话级调试对生产环境中的语音 AI 更为有效。他们正在尝试自动化对话级质量保证来扩展这一方法。 这揭示了当前语音助手评估方法的关键缺陷，传统基准可能遗漏影响用户体验的问题。这对部署语音系统的 AI 从业者很重要，推动转向更全面的、以交互为重点的质量保证，以构建更自然的对话 AI。 涌现的问题包括累计时序错误、重复确认引起的摩擦以及不自然的轮流发言改变用户行为。该团队现在专注于识别重复出现的对话模式而非单个模型错误，并使用自动化工具大规模审查交互痕迹。

reddit · r/MachineLearning · /u/OwlZealousideal4779 · 6月18日 15:29

**背景**: 语音 AI 系统由多个组件构成：语音转文本（STT）、自然语言理解、对话管理和文本转语音（TTS）。传统基准通常独立评估每个组件，衡量词错误率或任务完成率等指标。但真实对话涉及复杂的动态交互，细微的差错会累积，导致孤立测试中不出现的问题。对话级调试检查完整交互轨迹，捕捉整体用户体验。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.braintrust.dev/articles/how-to-evaluate-voice-agents">How to evaluate voice agents - Articles - Braintrust</a></li>
<li><a href="https://docs.vapi.ai/debugging">Debugging voice agents | Vapi</a></li>

</ul>
</details>

**标签**: `#voice debugging`, `#conversational AI`, `#evaluation metrics`, `#multi-turn dialogue`, `#quality assurance`

---

<a id="item-16"></a>
## [苹果与英特尔达成初步芯片代工协议](https://t.me/zaihuapd/42031) ⭐️ 7.0/10

苹果和英特尔已达成初步协议，由英特尔为苹果部分设备代工生产芯片，谈判历时一年多并在近几个月敲定合同，但具体产品线尚不明确。 这标志着苹果在台积电之外的重要代工多元化，可能重塑半导体制造格局，而美国政府的参与凸显了供应链的战略利益。 美国政府深度推动，商务部长多次游说苹果蒂姆·库克；英特尔目前代工客户包括英伟达、SpaceX 及苹果，但具体芯片类型（iPhone、iPad 或 Mac）尚未披露。

telegram · zaihuapd · 6月18日 09:19

**背景**: 芯片代工是指半导体制造厂为其他公司生产他们设计的芯片。苹果传统上依赖台积电生产先进处理器，而英特尔历史上专注于自有芯片，但近期通过 IDM 2.0 战略向外部客户开放制造厂。美国政府通过《芯片法案》推动本土芯片制造，以减少对亚洲代工厂的依赖。

**标签**: `#semiconductors`, `#Apple`, `#Intel`, `#foundry`, `#chip manufacturing`

---

<a id="item-17"></a>
## [小米开源智能家居框架 Miloco 2.0 发布](https://github.com/XiaoMi/xiaomi-miloco) ⭐️ 7.0/10

小米发布了开源的智能家居框架 Miloco 2.0，通过米家摄像头和 MiMo 大模型实现主动设备控制、身份识别、家庭记忆和家务自动化等功能。 该发布推动了开源智能家居 AI 的发展，可能影响互操作性标准并激发社区创新，但其非商业许可和云端依赖性可能限制广泛采用。 Miloco 2.0 需在 macOS 或 Linux（或 Windows 的 WSL）上运行，绑定小米账号和 MiMo API 密钥，感知与推理依赖云端模型，会产生持续 API 费用；仅限非商业用途。

telegram · zaihuapd · 6月18日 12:23

**背景**: Miloco 是小米的开源全屋智能方案。MiMo 是其自研的以推理为核心的大语言模型，采用多令牌预测和强化学习训练。OpenClaw 是一个 AI Agent 框架，Miloco 作为其插件运行，利用摄像头音视频进行感知。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/XiaoMi/xiaomi-miloco">GitHub - XiaoMi/xiaomi-miloco: Xiaomi Miloco · GitHub</a></li>
<li><a href="https://en.wikipedia.org/wiki/Xiaomi_MiMo">Xiaomi MiMo - Wikipedia</a></li>

</ul>
</details>

**标签**: `#smart-home`, `#open-source`, `#AI`, `#IoT`, `#Xiaomi`

---

<a id="item-18"></a>
## [瑞士议会解除新建核电站禁令](https://www.bluewin.ch/en/news/switzerland/parliament-lifts-ban-on-new-nuclear-power-plants-3257535.html) ⭐️ 6.0/10

瑞士议会投票决定解除长期以来禁止新建核电站的禁令，但这一决定仍需通过全民公投。 这一政策转向可能重振瑞士核电产业，减少对进口电力的依赖，并助力实现无碳能源目标，反映了全球范围内对核电的重新评估。 该禁令是 2011 年福岛核事故后实施的；议会投票存在分歧，最终决定将通过全民公投做出，反映出持续的政治和公众分歧。

hackernews · leonidasrup · 6月18日 14:17 · [社区讨论](https://news.ycombinator.com/item?id=48585746)

**背景**: 瑞士目前约三分之一的电力来自四座老化的核反应堆。2011 年福岛核事故后，政府决定逐步淘汰核能并禁止新建核电站。然而，对能源安全、不断增长的电力需求和气候目标的担忧，促使人们重新考虑这一政策，最终导致议会投票解除禁令。

**社区讨论**: 社区讨论展现出两极化的观点：一些用户认为核能被误解且是清洁能源的必要组成部分，另一些人则指出项目成本高昂以及瑞士独特的季节性能源挑战。人们对小型模块化反应堆等新技术感兴趣，但鉴于政治反对，对全民公投能否成功持怀疑态度。

**标签**: `#nuclear energy`, `#energy policy`, `#Switzerland`, `#legislation`, `#environment`

---

<a id="item-19"></a>
## [Craigslist 创始人 Craig Newmark 捐款超 5 亿美元](https://www.independent.co.uk/us/money/craigslist-multimillionaire-craig-newmark-b2980681.html) ⭐️ 6.0/10

在线分类广告网站 Craigslist 的创始人 Craig Newmark 已向慈善事业捐赠了超过 5 亿美元。 这笔捐款突显了科技财富可被引导用于公共福祉，同时也重新引发了人们对 Craigslist 商业行为的审视，包括其在助长诈骗方面的角色以及在与 Facebook Marketplace 等竞争对手的对抗中未能持续发展。 这些捐款来自 Newmark 的个人财富，而非 Craigslist 的运营收入。同时，用户反映该网站上约 25% 的租房广告系诈骗信息，且在许多地区该平台已被 Facebook Marketplace 所取代。

hackernews · Tomte · 6月18日 16:55 · [社区讨论](https://news.ycombinator.com/item?id=48588216)

**背景**: Craigslist 由 Craig Newmark 于 1995 年创立，最初是旧金山本地活动的电子邮件列表，后发展为全球最受欢迎的分类广告网站之一，以其简洁设计和大部分免费发布而闻名。Newmark 于 2000 年卸任 CEO 但仍保持参与。多年来，他通过自己的慈善机构 Craig Newmark Philanthropies 向新闻业、退伍军人支持和网络安全等领域进行了大量捐赠。

**社区讨论**: 评论者观点不一：有人欣赏 Newmark 的朴实生活方式，提及他过去曾说有好的水压就足够了；另一些人批评 Craigslist 纵容了高比例的租房诈骗（约 25%）且未能创新，导致 Facebook Marketplace 占据主导。还有人惋惜其错失将公司发展为科技巨头的财务机遇。

**标签**: `#Philanthropy`, `#Craigslist`, `#Tech Business`, `#Online Scams`, `#Classifieds`

---

<a id="item-20"></a>
## [W Social 与欧洲数字主权的表演](https://blog.elenarossini.com/w-social-public-institutions-and-the-theater-of-european-digital-sovereignty/) ⭐️ 6.0/10

一篇博客文章批评性分析了新欧洲社交网络 W Social，将其视为欧盟数字主权的一次表演性举动。社区评论指出该平台与 Truth Social 的相似性，以及像 Eurosky 这样的开放替代方案未获关注，并质疑其背后的潜在盈利动机。 这一批评质疑了欧盟数字主权倡议的真实性，暗示它们可能更多是政治作秀而非真正的技术独立。社区的怀疑态度可能影响用户对此类平台的信任和采用。 W Social 是一家有限责任公司，创始人具有金融背景，要求人类验证但已被证明允许多个账户。它托管在欧洲，受欧盟法律管辖，其发布得到了知名欧盟政客和世界经济论坛的放大，而基于 ATproto 的开源替代品 Eurosky 却未获媒体关注。

hackernews · nemoniac · 6月18日 12:46 · [社区讨论](https://news.ycombinator.com/item?id=48584497)

**背景**: 欧洲数字主权指欧盟推动减少对非欧洲科技巨头的依赖，并维护对数字基础设施和数据的控制。ATproto 是一种用于去中心化社交网络的开源协议，被 BlueSky 采用。Truth Social 是唐纳德·特朗普为其支持者推出的社交媒体平台，常被视为党派回音室。Eurosky 是一个基于 ATproto 的欧洲社交网络，由非营利组织透明构建。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://wsocial.news/">W - The European social network for verified humans</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍持怀疑态度，认为 W Social 可疑，可能是欧盟政客为控制影响力而打造的欧洲版 Truth Social。他们指出人类验证易被绕过的讽刺，并批评媒体忽视像 Eurosky 这样的透明替代方案。一些人怀疑其盈利动机并质疑平台的可行性。

**标签**: `#European digital sovereignty`, `#social networks`, `#W Social`, `#tech policy`, `#platform governance`

---

<a id="item-21"></a>
## [Submission.Directory：精选的初创公司提交网站目录](https://www.submission.directory/) ⭐️ 6.0/10

新网站 submission.directory 提供了一个精选的网站目录，这些网站接受初创公司提交，为寻求曝光和反向链接的创始人提供集中资源。 该资源简化了寻找提交机会的过程，能显著助力初创公司的营销和 SEO 工作，尤其是在链接建设和垃圾信息问题持续的背景下。 该目录是手工策展的；社区评论强调了垃圾信息的普遍性（如为获取反向链接而提交虚假播客），并分享了替代列表以及来自 90 年代的历史背景。

hackernews · azeemkafridi · 6月18日 15:12 · [社区讨论](https://news.ycombinator.com/item?id=48586631)

**背景**: 初创公司目录是公司列出产品以获得曝光和反向链接的平台，这对搜索引擎优化至关重要。这种做法可追溯到 90 年代的 Submit It 等服务，并通过 BetaList 和 Product Hunt 等平台不断演变。来自信誉良好目录的反向链接可以提高网站的搜索排名，但也吸引了垃圾信息制造者。

**社区讨论**: 评论者分享了丰富的历史：marc 讲述了 16 年前创建 BetaList 及后来的 submit.co；renegat0x0 提供了一个开源数据库；wenbin 详细说明了通过虚假 RSS 源进行的垃圾信息；susam 列出了个人网站目录；transitorykris 指出这一概念源于 90 年代。总体而言，讨论认可了资源的实用性，同时强调了垃圾信息挑战和 SEO 策略的周期性。

**标签**: `#startup`, `#marketing`, `#directories`, `#backlinks`, `#seo`

---

<a id="item-22"></a>
## [DeepSeek 聊天应用新增图像理解功能](https://chat.deepseek.com/) ⭐️ 6.0/10

DeepSeek 的聊天应用现支持图像理解，用户可上传图片并获取内容描述，但该功能不支持生成或修改图像。 此次更新为 DeepSeek 带来了多模态能力，使其能够与其他提供视觉功能的 AI 聊天机器人竞争，并拓展了图像分析和无障碍等新应用场景。 该功能仅限于理解，不支持图像生成或编辑。有用户反映存在回复中文、需要登录等问题，且 DeepSeek 仍缺少自带的文本转语音和语音转文本功能。

hackernews · RIshabh235 · 6月18日 06:17 · [社区讨论](https://news.ycombinator.com/item?id=48581458)

**背景**: DeepSeek 是一家中国 AI 公司，以开源权重大语言模型如 DeepSeek-R1 闻名，该模型以更低成本与 GPT-4 竞争。多模态 AI 指能同时处理文本、图像、音频等多种数据类型的模型。图像理解是现代聊天机器人常见功能，可分析视觉内容。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek">DeepSeek</a></li>
<li><a href="https://www.explainx.ai/blog/what-is-multimodal-ai-complete-guide-2026">What Is Multimodal AI? Text, Image, Audio, and Video Models ...</a></li>

</ul>
</details>

**社区讨论**: 社区反馈褒贬不一：有人指出缺少图像生成和文本转语音等功能，其他人则提到中文回复错误和跳转登录页面的问题。少数用户讨论将其与本地工具集成以实现如图片替代文本生成等实际应用。

**标签**: `#deepseek`, `#vision`, `#multimodal-ai`, `#chatbot`, `#ai-updates`

---

<a id="item-23"></a>
## [新的 Web 组件延迟 GIF 加载直至点击](https://simonwillison.net/2026/Jun/17/click-to-play-component/#atom-everything) ⭐️ 6.0/10

Simon Willison 发布了一个渐进增强的 Web Component，名为 <click-to-play>，它会在用户点击之前延迟加载动画 GIF，并使用静态的第一帧作为占位符。 这通过防止大尺寸 GIF 自动加载来减少不必要的带宽消耗并提升页面性能，有利于网速较慢的移动设备和用户。 该组件采用渐进增强技术，即使没有 JavaScript，GIF 链接和静态图片后备仍可访问。只有当用户点击播放按钮时，才会加载完整的 GIF。

rss · Simon Willison · 6月17日 03:56

**背景**: Web Components 是一套标准技术，允许开发者创建自定义、可重用的 HTML 元素。渐进增强是一种网络开发策略，确保所有用户都能访问基本内容，再根据浏览器能力提供增强体验。动画 GIF 文件通常较大，会拖慢页面加载；该组件将其加载延迟到用户交互时。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Web_Components">Web Components</a></li>
<li><a href="https://en.wikipedia.org/wiki/Progressive_enhancement">Progressive enhancement</a></li>
<li><a href="https://developer.mozilla.org/en-US/docs/Glossary/Progressive_Enhancement">Progressive enhancement - Glossary | MDN - MDN Web Docs</a></li>

</ul>
</details>

**标签**: `#web components`, `#gif`, `#progressive-enhancement`, `#javascript`, `#performance`

---

<a id="item-24"></a>
## [推测性解码：热门的大语言模型推理技术](https://www.reddit.com/r/MachineLearning/comments/1u83kzt/what_is_speculative_decoding_trending_on/) ⭐️ 6.0/10

推测性解码目前在 Papers with Code 上成为趋势，SGLang 发布了一篇博文，详述了如何使用 Modal 和 Z.ai 的 DFlash 推测性解码模型实现最先进的推理延迟。 该技术解决了大模型推理中 token 生成慢的关键瓶颈，能够在不牺牲输出质量的前提下实现更快、更经济的推理。SGLang 与 DFlash 的整合展示了实际应用中的最先进性能。 推测性解码利用快速草稿模型生成候选 token，再通过更大的目标模型进行并行验证。Z.ai 的 DFlash 使用基于扩散的方法一次性草拟多个 token，SGLang 的最新博文介绍了如何结合 Modal 实现顶级的 LLM 服务延迟。

reddit · r/MachineLearning · /u/NielsRogge · 6月17日 07:41

**背景**: 大语言模型通常一次生成一个 token，对于长响应可能较慢。推测性解码通过使用小型快速的“草稿”模型提出多个未来 token，再由较大的目标模型并行验证来加速这一过程。SGLang 是一个开源 LLM 服务框架，支持高吞吐量推理和推测性解码等功能。Z.ai 的 DFlash 是一种采用扩散方法一次性预测多个 token 的草稿技术。Modal 是一个提供按需 GPU 资源的云平台，便于部署此类优化推理流水线。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/SGLang">SGLang</a></li>
<li><a href="https://www.localainews.co/news/tools/z-lab-dflash-turbocharges-local-ai-text-generation/">Z -Lab DFlash Turbocharges Local AI Text Generation | Local AI News</a></li>

</ul>
</details>

**标签**: `#speculative-decoding`, `#large-language-models`, `#inference-optimization`, `#SGLang`, `#paperswithcode`

---

<a id="item-25"></a>
## [分析语言模型可解释性中探针的相对强度](https://www.reddit.com/r/MachineLearning/comments/1u8lo60/how_do_you_analyze_the_relative_strength_of/) ⭐️ 6.0/10

一位 Reddit 用户寻求系统性方法来衡量探针在分析语言模型时的强度，重点关注平衡分类器容量与模型复杂性，并寻找理论基础，例如类似奈奎斯特的保证。 改进探针评估方法能够带来对语言模型内部表征更可靠的见解，这对 AI 系统的安全性和可信度至关重要。 帖子指出小词汇量可能夸大探针准确性，并以 Gemini 在拼错字母计数为例，说明探针可能无法反映模型真实知识；还质疑奈奎斯特采样等框架是否能约束探针的可靠性。

reddit · r/MachineLearning · /u/RepresentativeBee600 · 6月17日 20:29

**背景**: 探针分类器是一种常见的可解释性技术，通过在模型的隐藏状态上训练简单分类器（如逻辑回归）来检测如词位置等编码信息。电路分析则映射行为背后的计算子图。可靠的探针对于避免虚假结论至关重要，而奈奎斯特定理（源自信号处理）有时被援引为模型评估中数据采样充分的类比。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://mbrenndoerfer.com/writing/probing-classifiers">Probing Classifiers : Decoding What Language Models Learn...</a></li>
<li><a href="https://transformer-circuits.pub/2025/attribution-graphs/methods.html">Circuit Tracing: Revealing Computational Graphs in Language Models</a></li>

</ul>
</details>

**标签**: `#probing`, `#interpretability`, `#language-models`, `#circuit-analysis`, `#factuality`

---

<a id="item-26"></a>
## [扎克伯格承认 Meta AI 重组犯错，承诺 2026 年不裁员](https://t.me/zaihuapd/42024) ⭐️ 6.0/10

Meta 首席执行官扎克伯格在内部备忘录中承认，公司向 AI 倾斜资源导致了混乱和错误。他承诺将提供更多稳定，2026 年不再全公司裁员，并增加团队建设支出、举办黑客松，同时纠正部分 AI 团队的极扁平管理问题。 这份坦率的承认揭示了科技巨头在战略转向 AI 时的内部混乱，凸显了此类转型的人力和组织成本。这直接影响员工士气和留任，也表明领导层试图稳定公司的努力。 今年 5 月，Meta 裁员近 8000 人，并将约 7000 人调至 AI 岗位。扎克伯格还提到，增发股票的传闻导致股价下跌超 5%，他计划纠正 AI 团队中极扁平化的管理结构。

telegram · zaihuapd · 6月18日 03:35

**背景**: Meta 一直在大力投资 AI，导致了大规模的内部重组。今年早些时候，公司裁员数千人，并将许多员工调至 AI 相关岗位，在科技行业更广泛的 AI 竞赛中造成了组织不稳定。

**标签**: `#Meta`, `#AI`, `#Management`, `#Layoffs`, `#Tech News`

---

<a id="item-27"></a>
## [ChatGPT 定时任务新增专用页面与监控通知](https://help.openai.com/en/articles/10291617-scheduled-tasks-in-chatgpt) ⭐️ 6.0/10

OpenAI 更新了 ChatGPT 的定时任务功能，新增侧边栏“Scheduled”页面，用于集中管理一次性与重复任务，还加入了监控任务，可在重要变化时通知用户。 此次改进让任务自动化更易用、更有条理，惠及依赖 ChatGPT 设置提醒和定期检查的付费用户，也体现了 OpenAI 对自主能力（agentic capabilities）的重视。 该功能面向 Plus、Pro、Business 和 Enterprise 用户，支持网页版与移动应用，暂不支持桌面客户端和 Codex。不同套餐的活跃任务上限为 3 到 15 个，且不支持语音对话和 GPTs。

telegram · zaihuapd · 6月18日 04:20

**背景**: ChatGPT 此前已推出定时任务，允许用户设定自动提示。此次更新加入了专用界面和主动监控功能。GPTs 是用户构建的自定义 AI 助手，Codex 则是 OpenAI 辅助编程的独立产品，二者均未与定时任务打通。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openai.com/index/introducing-gpts/">Introducing GPTs - OpenAI</a></li>
<li><a href="https://openai.com/index/openai-codex/">OpenAI Codex</a></li>

</ul>
</details>

**标签**: `#ChatGPT`, `#OpenAI`, `#feature update`, `#scheduling`, `#automation`

---

<a id="item-28"></a>
## [传谷歌考虑采购长鑫存储 DRAM 应对短缺与价格压力](https://wccftech.com/a-wild-rumor-linked-to-sundar-pichai-suggests-google-is-evaluating-the-procurement-of-memory-chips-from-chinas-cxmt/) ⭐️ 6.0/10

有传闻称，谷歌正在评估从中国长鑫存储（CXMT）采购 DRAM 芯片，以应对当前的内存短缺和价格压力，可能将其用于新一代 Humufish AI 芯片。该消息源自社交媒体，尚未得到证实。 如果属实，此举可能打破三星、SK 海力士和美光长期主导的 DRAM 市场格局，标志着供应链地缘政治的重大转变，并可能加速中国内存在全球科技产品中的采用。 目前尚不清楚这些芯片将用于 Pixel 手机、TPU 还是云服务，但外界猜测可能用于 Humufish TPU，谷歌计划到 2028 年底将其产量提升至 350 万片。长鑫存储目前使用 19 纳米工艺生产 DDR4 和 LPDDR4 内存，并正在扩大产能。

telegram · zaihuapd · 6月18日 06:14

**背景**: 长鑫存储（CXMT）是一家成立于 2016 年的中国 DRAM 制造商，旨在减少中国对外国内存芯片的依赖。全球 DRAM 市场长期以来由三星、SK 海力士和美光主导。谷歌的定制 AI 芯片（张量处理单元，TPU）专为机器学习任务设计，即将推出的 Humufish TPU 是下一代设计，预计将采用英特尔 EMIB-T 等先进封装技术。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/CXMT">CXMT</a></li>
<li><a href="https://semiwiki.com/forum/threads/ming-chi-kuo-on-intels-emib-t-packaging-for-google-tpu-v8e-humufish.25038/">Ming-Chi Kuo on Intel's EMIB-T packaging for Google TPU v8e (Humufish) | SemiWiki</a></li>

</ul>
</details>

**标签**: `#Google`, `#DRAM`, `#CXMT`, `#semiconductors`, `#rumor`

---

<a id="item-29"></a>
## [谷歌测试需摄像头手势验证的新版 reCAPTCHA](https://www.ithome.com/0/966/252.htm) ⭐️ 6.0/10

谷歌正在测试新版 reCAPTCHA，要求用户授权摄像头并录制挥手视频，系统会分析手部的 21 个关键点坐标以区分真人和机器人。 这项测试表明人机验证正向生物特征认证方向发展，虽能提高安全性以抵御凭证填充等攻击，但也引发了用户对隐私的担忧。 该系统通过分析手部动作，可能采用了 MediaPipe 等模型来检测每只手的 21 个三维关键点；谷歌强调视频不与用户身份绑定，不录制音频，验证完成后即删除数据。

telegram · zaihuapd · 6月18日 16:39

**背景**: reCAPTCHA 是谷歌的人机验证服务，从早期文本识别演变为风险分析，如今可能发展到生物特征手势。MediaPipe 是谷歌的开源框架，提供实时手部关键点检测，每只手可识别 21 个关键点。凭证填充攻击是指利用窃取的账号密码进行批量登录尝试，此类验证旨在防范这种攻击。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/prashver/hand-landmark-recognition-using-mediapipe">Hand Landmark Recognition using MediaPipe - GitHub</a></li>
<li><a href="https://en.wikipedia.org/wiki/Credential_stuffing">Credential stuffing - Wikipedia</a></li>

</ul>
</details>

**标签**: `#reCAPTCHA`, `#biometrics`, `#web security`, `#computer vision`, `#authentication`

---