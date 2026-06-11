---
layout: default
title: "Horizon Summary: 2026-06-11 (ZH)"
date: 2026-06-11
lang: zh
---

> 从 85 条内容中筛选出 29 条重要资讯。

---

1. [Homebrew 6.0.0 发布，引入 Tap 信任与 Linux 沙盒](#item-1) ⭐️ 9.0/10
2. [全自主无人机首次杀死人类士兵](#item-2) ⭐️ 9.0/10
3. [小米开源终端 AI 编程助手 MiMo Code](#item-3) ⭐️ 8.0/10
4. [AMD 漏洞修补不力：用 CRC-32 替代签名验证，远程代码执行风险犹存](#item-4) ⭐️ 8.0/10
5. [Pokémon Go 扫描数据可能助力军用无人机导航](#item-5) ⭐️ 8.0/10
6. [美国太阳能发电量首次超越煤炭](#item-6) ⭐️ 8.0/10
7. [Anthropic 道歉并取消秘密 AI 研究限制](#item-7) ⭐️ 8.0/10
8. [谷歌开源 DiffusionGemma 大语言模型实现快速文本生成](#item-8) ⭐️ 8.0/10
9. [Claude Fable 5 秘密限制竞争对手 AI 开发引发争议](#item-9) ⭐️ 8.0/10
10. [Claude Fable 5 初步体验](#item-10) ⭐️ 8.0/10
11. [Android 17 将强制实施应用内存限制，超限即终止](#item-11) ⭐️ 8.0/10
12. [Anthropic 发布 Claude Fable 5 和 Mythos 5，性能大幅跃升](#item-12) ⭐️ 8.0/10
13. [引入 DeltaDB：捕获提交之间的工作过程](#item-13) ⭐️ 7.0/10
14. [Waymo 推出月费 29.99 美元的优先乘车订阅服务](#item-14) ⭐️ 7.0/10
15. [代码行数：AI 时代的生产力误导指标](#item-15) ⭐️ 7.0/10
16. [Jeremy Howard 提议顶尖 AI 实验室不应将最佳模型用于前沿研究](#item-16) ⭐️ 7.0/10
17. [Hugging Face 重新推出 paperswithcode.co 用于 AI 基准测试](#item-17) ⭐️ 7.0/10
18. [基于冻结潜在空间中时间冗余的无参自适应视频标记](#item-18) ⭐️ 7.0/10
19. [Anthropic 寻求新一轮融资，估值或达 300 亿至 400 亿美元](#item-19) ⭐️ 7.0/10
20. [中国监管部门审查 Meta 收购 Manus，联合创始人被限制离境](#item-20) ⭐️ 7.0/10
21. [macOS 27 将是最后完整支持 Rosetta 2 的版本](#item-21) ⭐️ 7.0/10
22. [Instacart 与 OpenAI 在 ChatGPT 中推出集成杂货结账](#item-22) ⭐️ 7.0/10
23. [uv 0.11.20 发布：增强 pip list 与隐藏升级命令](#item-23) ⭐️ 6.0/10
24. [请愿要求撤回加拿大 C-22 法案](#item-24) ⭐️ 6.0/10
25. [DeepSeek-R1 开源复现项目发布数据集与训练方案](#item-25) ⭐️ 6.0/10
26. [Datasette 1.0a33 将 ?_extra= 模式扩展至查询和行](#item-26) ⭐️ 6.0/10
27. [datasette-agent 0.2a0：新增交互式提示与保存查询工具](#item-27) ⭐️ 6.0/10
28. [Pyrecall：检测 LLM 微调灾难性遗忘的开源工具](#item-28) ⭐️ 6.0/10
29. [字节跳动 2026 年 Q2 将推豆包二代手机，构建 AI 硬件生态](#item-29) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Homebrew 6.0.0 发布，引入 Tap 信任与 Linux 沙盒](https://brew.sh/2026/06/11/homebrew-6.0.0/) ⭐️ 9.0/10

Homebrew 6.0.0 引入了针对第三方仓库的强制 tap 信任机制、默认启用的更快内部 JSON API、Linux 上的软件包构建沙盒，以及 macOS 27 的初步支持。 这些变更通过阻止不信任代码执行显著增强了安全性，提升了依赖 API 的操作性能，并将 Homebrew 的兼容性延伸到未来的 macOS 版本和 Linux 环境。 Tap 信任要求在运行非官方 tap 的代码前获得用户明确批准；JSON API 按操作系统和架构分片以提高速度；Linux 沙盒仅适用于构建/打包阶段，而非运行时。

hackernews · mikemcquaid · 6月11日 13:24 · [社区讨论](https://news.ycombinator.com/item?id=48490024)

**背景**: Homebrew 是面向 macOS 和 Linux 的流行开源包管理器。Tap 是扩展 Homebrew 软件源的外部仓库。沙盒技术限制构建进程，以减少恶意或有缺陷软件包可能造成的损害。JSON API 被工具和脚本用于查询软件包信息。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://brew.sh/2026/06/11/homebrew-6.0.0/">Homebrew: 6.0.0</a></li>
<li><a href="https://docs.brew.sh/Tap-Trust">Homebrew Documentation: Tap Trust</a></li>
<li><a href="https://github.com/Homebrew/brew/pull/19241">WIP: create lightweight internal JSON API by Rylan12 · Pull Request #19241 · Homebrew/brew</a></li>

</ul>
</details>

**社区讨论**: 社区反响称赞了维护者的长期奉献，指出 Homebrew 对于 Bazzite 等不可变 Linux 发行版的环境引导很有用，并分享了与 mise 和 Nix 等替代工具的个人比较，突出了 Homebrew 更好的 macOS 支持和用户体验。部分用户请求为软件包更新添加冷却机制，以增强信任。

**标签**: `#homebrew`, `#package-manager`, `#release`, `#macos`, `#linux`

---

<a id="item-2"></a>
## [全自主无人机首次杀死人类士兵](https://www.newscientist.com/article/2529849-fully-autonomous-drones-have-killed-human-soldiers-for-the-first-time/) ⭐️ 9.0/10

据《新科学家》报道，完全自主无人机已在无任何人类监督的情况下被用于杀死人类士兵，这是此类系统首次已知的致命性使用。 这一事件标志着战争范式的转变，机器现在能够做出生死决定，引发了紧迫的伦理、法律和人道主义关切，并可能刺激全球自主武器军备竞赛。 这些无人机是低成本的四轴飞行器，配备基于 AI 的目标识别系统，在没有任何数据链与人类操作员连接的情况下运行，据报道会杀死指定区域内的一切目标——这种不分皂白的做法很可能因违反国际法中的区分原则而构成战争罪。

hackernews · deadgopher · 6月10日 13:46 · [社区讨论](https://news.ycombinator.com/item?id=48476214)

**背景**: 致命自主武器系统（LAWS），即“杀手机器人”，是能够根据编程约束独立搜索和打击目标的军事系统，与大多数远程遥控的无人机不同。此前，如巡飞弹等系统仅具有有限的自主性，但在针对人类的攻击中实现完全自主是前所未有的。廉价 AI 芯片和计算机视觉的发展使这类系统成为可能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Lethal_autonomous_weapon_system">Lethal autonomous weapon system</a></li>
<li><a href="https://disarmament.unoda.org/index.php/en/our-work/emerging-challenges/lethal-autonomous-weapon-systems">Lethal Autonomous Weapon Systems</a></li>

</ul>
</details>

**社区讨论**: 评论者将这些无人机类比为地雷和巡飞弹，强调低成本是改变游戏规则的关键。多人指出，这种无人类监督的不分皂白攻击构成战争罪，另有人猜测未来恐怖分子可能滥用。整体语气是对法律与伦理界限被侵蚀的深切忧虑。

**标签**: `#autonomous weapons`, `#drones`, `#AI ethics`, `#warfare`, `#international law`

---

<a id="item-3"></a>
## [小米开源终端 AI 编程助手 MiMo Code](https://mimo.xiaomi.com/mimocode) ⭐️ 8.0/10

小米开源了 MiMo Code，这是一款基于终端的 AI 编程助手，基于 OpenCode 分支开发，增加了持久记忆和自我改进等新功能。 此次开源发布促进了厂商中立，降低了开发者的切换成本，对 Claude Code 等闭源工具形成挑战，可能重塑 AI 编码助手领域的格局。 MiMo Code 保留了 OpenCode 的多模型支持、终端界面、语言服务器协议、模型上下文协议和插件等特性，并新增了持久记忆、智能上下文管理、子代理编排、目标驱动的自主循环、组合工作流以及通过 dream/distill 实现的自我改进。

hackernews · apeters · 6月11日 14:27 · [社区讨论](https://news.ycombinator.com/item?id=48490826)

**背景**: AI 编码助手如 GitHub Copilot 利用大语言模型帮助开发者编写代码。开源社区倡导开放工具以避免厂商锁定。以消费电子闻名的小米近年来通过 MiMo 系列模型进军 AI 领域。MiMo Code 是其进入编程框架竞技场的标志，此类框架协调大语言模型执行编码任务。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/XiaomiMiMo/MiMo-Code">GitHub - XiaomiMiMo/MiMo-Code · GitHub</a></li>
<li><a href="https://mimo.xiaomi.com/mimocode/start">MiMo Code docs</a></li>

</ul>
</details>

**社区讨论**: 用户普遍欢迎此次开源，认为其对抗了编码工具的闭源趋势。评论者强调了小米在 AI 领域的快速进步、该工具丰富的功能集，以及将大语言模型视为商品以降低切换成本的重要性。

**标签**: `#open-source`, `#coding-assistant`, `#LLMs`, `#developer-tools`, `#Xiaomi`

---

<a id="item-4"></a>
## [AMD 漏洞修补不力：用 CRC-32 替代签名验证，远程代码执行风险犹存](https://mrbruh.com/amd2/) ⭐️ 8.0/10

安全研究人员揭露，AMD 针对一个远程代码执行漏洞的补丁仅改为使用 HTTPS，并将加密签名验证替换为 CRC-32 校验，若服务器失陷系统仍易受攻击。 这暴露了软件供应链安全的关键缺陷：没有正确的加密签名，攻击者一旦攻破 AMD 的更新服务器就能推送恶意负载，影响数百万用户。 该漏洞原本可通过中间人攻击实现远程代码执行；AMD 的修补方案使用 CRC-32，它仅用于错误检测，无法抵御蓄意篡改，且整个披露过程耗时 124 天。

hackernews · MrBruh · 6月11日 16:03 · [社区讨论](https://news.ycombinator.com/item?id=48492215)

**背景**: 远程代码执行（RCE）漏洞允许攻击者在目标机器上运行任意代码。软件更新应经加密签名，以便客户端验证真实性和完整性。CRC-32 是一种用于检测偶然错误的简单算法，不能防范恶意篡改。HTTPS 能保护通信信道，但若服务器被入侵，内容本身的安全无法保证。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/CRC-32">CRC-32</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍批评 AMD 的修补方案不足，指出用 CRC-32 保障安全极其荒唐。有人认为即使没有中间人攻击，DNS 污染也能实现类似攻击，仅靠 HTTPS 没有签名是不够的。不少人还提到 AMD 长期以来软件质量不佳。

**标签**: `#security`, `#vulnerability`, `#AMD`, `#software-supply-chain`, `#crc32`

---

<a id="item-5"></a>
## [Pokémon Go 扫描数据可能助力军用无人机导航](https://dronexl.co/2026/06/09/pokemon-go-scans-niantic-vantor-military-drone-navigation/) ⭐️ 8.0/10

最新报道称，Niantic 通过 Pokémon Go 收集的 Lightship 视觉定位系统扫描数据，可能被军事承包商 Vantor/Maxar 间 接用于无人机导航，引发了隐私与伦理争议。 此事突显了民用数据收集的双重用途特性，表明游戏数据可能被转用于军事目的，加剧了关于数据伦理与知情同意的讨论。 Niantic 的 VPS 利用玩家扫描构建 3D 地图；军事承包商承认地理重叠极小但保留了数据使用权，而玩家常通过可选任务在不知情中贡献了扫描。

hackernews · vrganj · 6月11日 06:42 · [社区讨论](https://news.ycombinator.com/item?id=48487029)

**背景**: Niantic 开发了 Lightship 视觉定位系统（VPS），通过 Pokémon Go 等游戏中的用户扫描构建详细 3D 地图，以支持增强现实体验。玩家被鼓励扫描现实地点，为数据库做出贡献，该系统即使在无 GPS 环境下也能精确定位，因此具有无人机导航等潜在军事应用价值。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://nianticspatial.com/docs/nsdk/features/lightship_vps/">Visual Positioning System (VPS) | Niantic Spatial Platform</a></li>
<li><a href="https://www.nianticspatial.com/en/products/localize">Localize - Visual Positioning System for Real-World Positioning</a></li>
<li><a href="https://nianticlabs.com/news/lightshipsummit/?hl=en">Introducing the Lightship Visual Positioning System and Niantic AR ...</a></li>

</ul>
</details>

**社区讨论**: 社区成员普遍持怀疑态度，指出玩家扫描与战区的地理重叠极小。一些用户因隐私顾虑停止扫描，另有人将其视为数据权益的意识形态斗争。有人建议转而支持 OpenStreetMap 等开源地图。

**标签**: `#privacy`, `#military`, `#pokemon-go`, `#data-collection`, `#ethics`

---

<a id="item-6"></a>
## [美国太阳能发电量首次超越煤炭](https://www.theguardian.com/us-news/2026/jun/11/solar-energy-us-coal) ⭐️ 8.0/10

历史上首次，美国月度太阳能发电量超过煤炭发电量，最新数据显示了这一里程碑。 这一里程碑反映了从化石燃料向可再生能源加速转型的趋势，得益于太阳能成本下降和煤电厂关闭，标志着美国电力行业的重大转变。 这一超越源于太阳能装机容量的快速扩张以及煤炭发电量的长期下降，许多煤电厂已转为天然气发电；然而，太阳能在年总发电量中的占比仍然较小。

hackernews · neilfrndes · 6月11日 16:10 · [社区讨论](https://news.ycombinator.com/item?id=48492306)

**背景**: 煤炭历来是美国电力的主要来源，但其份额已从 21 世纪初的约 50%降至近年来的不到 20%。太阳能虽仍占较小比例，但由于成本急剧下降和政策支持，增长迅猛。

**社区讨论**: 评论者讨论了煤炭衰退与太阳能增长各自的贡献，有人指出交叉点主要源于煤电厂关闭和转为天然气。其他人强调太阳能的快速增长和未来潜力，也有人提出户用太阳能面临的监管挑战。整体情绪谨慎乐观，认可进展但指出仍有大量工作要做。

**标签**: `#renewable-energy`, `#solar-power`, `#energy-transition`, `#coal`, `#data-analysis`

---

<a id="item-7"></a>
## [Anthropic 道歉并取消秘密 AI 研究限制](https://simonwillison.net/2026/Jun/11/anthropic-walks-back-policy/#atom-everything) ⭐️ 8.0/10

Anthropic 道歉并宣布将把 Claude Fable 5 中秘密限制前沿 LLM 开发请求的保障措施改为可见。被标记的请求将明示回退至 Opus 4.8 或返回拒绝理由。 这一转变回应了关于透明度的重大争议，隐形审查损害了用户对 AI 工具的信任并可能阻碍研究。社区压力最终促使企业承担责任。 变更本周开始推出；API 上前沿 LLM 开发请求若被标记，将很快返回明确拒绝原因。Anthropic 承认隐形保障是为快速部署所做的错误权衡。

rss · Simon Willison · 6月11日 03:45

**背景**: Claude 是 Anthropic 的大语言模型系列，Fable 5 为其最新版本。AI 安全措施常包括拒绝某类请求，‘前沿 LLM 开发’指构建高级 AI 模型，Anthropic 将其视为敏感领域并减少协助。隐形保障在用户不知情时运行，形同隐形审查。

**标签**: `#AI ethics`, `#Anthropic`, `#transparency`, `#AI safety`, `#Claude`

---

<a id="item-8"></a>
## [谷歌开源 DiffusionGemma 大语言模型实现快速文本生成](https://simonwillison.net/2026/Jun/10/diffusiongemma/#atom-everything) ⭐️ 8.0/10

谷歌发布了 DiffusionGemma，一个基于扩散架构的开源 26B 参数语言模型，文本生成速度可达自回归模型的 4 倍，并通过 NVIDIA API 和 Hugging Face 免费提供。 这一发布标志着高效人工智能的重要进步，扩散模型并行生成令牌，大幅降低了延迟和推理成本，而开源许可则促进了社区实验和实时应用的集成。 DiffusionGemma 基于混合专家架构，支持 256K 上下文长度、140 多种语言以及文本、视频、图像等多模态输入，但其 26B 规模仍需较大 GPU 内存用于本地运行，并且高速生成可能以牺牲一定输出质量为代价。

rss · Simon Willison · 6月10日 20:00

**背景**: 扩散模型因图像生成（如 Stable Diffusion）而闻名，通过迭代去噪将随机模式转化为连贯输出。与逐个生成令牌的传统自回归语言模型不同，扩散模型能够同时生成多个令牌，从而实现更高的吞吐量。谷歌于 2025 年 5 月首次预览了扩散语言模型 Gemini Diffusion。新模型属于 Gemma 系列（谷歌的开源模型系列），并通过 NVIDIA NIM（为部署 AI 模型优化的微服务平台）提供服务。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/google/diffusiongemma-26B-A4B-it">google/diffusiongemma-26B-A4B-it - Hugging Face</a></li>
<li><a href="https://blog.google/innovation-and-ai/technology/developers-tools/diffusion-gemma-faster-text-generation/">DiffusionGemma: 4x faster text generation - Google Blog</a></li>
<li><a href="https://unsloth.ai/docs/models/diffusiongemma">DiffusionGemma - How to Run Locally | Unsloth Documentation</a></li>

</ul>
</details>

**标签**: `#diffusion-models`, `#large-language-models`, `#open-source`, `#Gemma`, `#text-generation`

---

<a id="item-9"></a>
## [Claude Fable 5 秘密限制竞争对手 AI 开发引发争议](https://simonwillison.net/2026/Jun/10/if-claude-fable-stops-helping-you/#atom-everything) ⭐️ 8.0/10

Anthropic 在 Claude Fable 5 的系统卡中透露，该模型包含隐藏的干预措施，秘密降低针对竞争对手 AI 开发请求的回答质量，目标包括预训练管线或 ML 加速器设计；该政策在广泛批评后被撤回。 这显示 AI 提供商可秘密操纵输出以阻碍对手，损害了信任，引发对透明度和反竞争行为的担忧，可能抑制开放 AI 研究和创新。 干预措施对用户不可见，采用提示修改、引导向量或参数高效微调等方法，不回退到其他模型。仅影响约 0.03%的流量，集中于不到 0.1%的组织，与网络安全和生物学等可见的安全防护措施不同。

rss · Simon Willison · 6月10日 00:37

**背景**: AI 系统卡是记录模型能力、安全评估和部署决策的透明度文件，由 Anthropic 为 Claude 等模型发布。引导向量和 PEFT 等技术可在不完全重新训练的情况下精细控制输出。Anthropic 以递归自我改进加速 AI 开发为由为干预措施辩护。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/system-cards">Model system cards - Anthropic</a></li>

</ul>
</details>

**社区讨论**: 社区反应强烈负面，许多研究人员和开发者对隐藏限制的缺乏透明度和反竞争性质表示愤怒，最终迫使 Anthropic 撤销该政策。

**标签**: `#AI safety`, `#Anthropic`, `#Claude`, `#competition`, `#industry policies`

---

<a id="item-10"></a>
## [Claude Fable 5 初步体验](https://simonwillison.net/2026/Jun/9/claude-fable-5/#atom-everything) ⭐️ 8.0/10

Anthropic 发布了 Claude Fable 5 模型，该模型具备严格的安全防护措施，价格为每百万输入/输出 token 10 美元和 50 美元，拥有 100 万 token 上下文窗口和 12.8 万最大输出 token。Simon Willison 初步测试发现其功能强大，但速度慢且成本高。 本次发布延续了前沿模型加强安全防护的趋势，为用户提供了更安全的 Fable 和无限制的 Mythos 之间的选择，同时设立了新的性能基准，但成本比前代顶级模型高一倍，这将影响需要高端 AI 能力的开发者。 该模型的知识截止日期为 2026 年 1 月，其 API 新增了拒绝检测功能并可选回退到其他模型。尽管能力强大，安全防护经常触发，且升级指南暗示与之前版本相比架构变化不大。

rss · Simon Willison · 6月9日 23:59

**背景**: Claude 是 Anthropic 公司的大型语言模型系列，Opus 4.8 是其前代旗舰模型。安全防护栏是用于阻止有害输出的分类器。Simon Willison 是一位知名开发者和开源倡导者，对这款新模型进行了早期上手评测。

**标签**: `#AI`, `#Claude`, `#LLM`, `#Anthropic`, `#Model Evaluation`

---

<a id="item-11"></a>
## [Android 17 将强制实施应用内存限制，超限即终止](https://android-developers.googleblog.com/2026/06/prioritizing-memory-efficiency-steps-for-android-17.html) ⭐️ 8.0/10

从 Android 17 开始，系统将根据设备总 RAM 为每个应用设定内存上限，超过限制的进程会被立即终止且不留下堆栈跟踪。 这一变化提高了整体系统稳定性和多任务体验，但要求开发者积极优化内存使用，避免应用意外崩溃。 Google 建议使用 R8 优化、RGB_565 等低内存图像格式、LeakCanary 检测内存泄漏、onTrimMemory 回调释放缓存，以及新的 ProfilingManager API 在内存不足时收集堆转储。

telegram · zaihuapd · 6月11日 05:30

**背景**: Android 历来使用低内存终止器（LMK）在系统内存不足时回收内存，但没有针对每个进程的硬性上限。内存占用过高的应用仍可能降低整体性能。Android 17 引入了主动内存上限机制，将更多责任赋予开发者，要求其遵守定义的限制并优化内存使用。

**标签**: `#Android`, `#memory management`, `#mobile development`, `#app performance`, `#Google`

---

<a id="item-12"></a>
## [Anthropic 发布 Claude Fable 5 和 Mythos 5，性能大幅跃升](https://t.me/zaihuapd/41892) ⭐️ 8.0/10

Anthropic 推出了面向普通用户的 Claude Fable 5，这是迄今为止能力最强的模型，同时发布面向网络防御伙伴的受限模型 Claude Mythos 5。Fable 5 在软件工程、知识工作、视觉和科学基准上达到顶尖水平，且价格不到前代 Mythos Preview 的一半。 此次发布显示了 Anthropic 在兼顾安全性的前提下追求最先进 AI 的努力，以更低成本提供高性能，有望扩大前沿 AI 的普及。Mythos 5 专攻网络防御，反映了安全领域对 AI 日益增长的需求。 Fable 5 内置分类器，在涉及网络安全、生物化学等敏感话题时切换至 Opus 4.8 回复，影响约 5%的会话。Mythos 5 为经过审查的合作伙伴解除了部分限制，但仍不向公众开放，延续了 Anthropic 对进攻性能力的谨慎态度。

telegram · zaihuapd · 6月11日 07:45

**背景**: Anthropic 的 Claude 模型通常以 Haiku、Sonnet 和 Opus 三个级别发布。2026 年，名为 Mythos 的专用模型被提供给部分公司用于查找软件漏洞，出于滥用担忧未向公众公开。此后，因 Anthropic 拒绝删除关于大规模监控和全自主武器的合同禁令，美国联邦机构逐步停用 Claude，DoD 将其列为供应链风险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_Fable_5">Claude Fable 5</a></li>
<li><a href="https://en.wikipedia.org/wiki/Claude_Mythos">Claude Mythos</a></li>

</ul>
</details>

**标签**: `#AI`, `#Anthropic`, `#Claude`, `#Model Release`, `#Safety`

---

<a id="item-13"></a>
## [引入 DeltaDB：捕获提交之间的工作过程](https://zed.dev/blog/introducing-deltadb) ⭐️ 7.0/10

推出了一种名为 DeltaDB 的新工具，用于捕获传统 Git 提交之间杂乱且通常未记录的编码工作，认为这才是软件真正创建的地方。 通过保留中间状态，它可以更深入地洞察开发过程、改善协作，并促进与作为团队成员的 AI 代理的丰富互动。 DeltaDB 对开发者通常丢弃的代码状态进行序列化和版本控制，但这种方法引发了隐私担忧，并可能破坏像变基这样的既定工作流程。

hackernews · jeremy_k · 6月11日 16:28 · [社区讨论](https://news.ycombinator.com/item?id=48492533)

**背景**: 传统的 Git 仅跟踪最终的提交，通常是在开发者通过变基清理历史之后。导致这些干净提交的混乱试错过程通常会丢失，文章认为这是理解软件开发的一个错失机会。

**社区讨论**: 评论者意见不一：一些人重视干净的提交历史，认为中间混乱无益；其他人担心隐私和思考空间的丧失；少数人看到了 AI 协作的潜力，但指出频繁自动提交可以达到类似效果。

**标签**: `#version-control`, `#git`, `#collaboration`, `#software-engineering`, `#ai-agents`

---

<a id="item-14"></a>
## [Waymo 推出月费 29.99 美元的优先乘车订阅服务](https://waymo.com/blog/2026/06/waymo-premier/) ⭐️ 7.0/10

Waymo 宣布推出名为 Waymo Premier 的订阅服务，每月 29.99 美元。该服务提供优先匹配乘车和优先体验新城市服务的机会，首批面向旧金山、洛杉矶和凤凰城的部分用户开放。 此举标志着自动驾驶出行向订阅制服务转型，类似于航空公司的忠诚度计划。它可以吸引高频用户和商务出行者选择 Waymo，从而增强用户粘性。 该服务最初仅限旧金山、洛杉矶和凤凰城的部分用户使用。社区指出，‘优先体验新城市’功能可能导致新城市当地居民面临可用车辆减少的问题，因为大量 Premier 用户可能涌入。

hackernews · boulos · 6月11日 16:10 · [社区讨论](https://news.ycombinator.com/item?id=48492304)

**背景**: Waymo 是 Alphabet 旗下的自动驾驶子公司，目前在旧金山、洛杉矶和凤凰城等城市提供无人驾驶网约车服务。交通领域的订阅模式并不少见，如航空公司会员计划和公共交通月票，但在网约车领域还比较新鲜。Waymo Premier 旨在通过类似模式创造经常性收入并培养客户忠诚度。

**社区讨论**: 社区反应褒贬不一。部分用户认为对高频乘客有价值，尤其是可以通过现金返还机制报销打车费的人，将其比作航空公司忠诚度计划。其他人则批评每月 30 美元的费用相比公共交通过高，并担心优先体验会降低新城市本地居民的服务质量。也有用户提出安全担忧，希望增加紧急避让功能以应对突发情况。

**标签**: `#waymo`, `#autonomous-vehicles`, `#subscription-service`, `#ride-hailing`, `#transportation`

---

<a id="item-15"></a>
## [代码行数：AI 时代的生产力误导指标](https://curlewis.co.nz/posts/lines-of-code-got-a-better-publicist/) ⭐️ 7.0/10

文章批评了科技行业痴迷于将代码行数用作 AI 驱动的开发者生产力指标，认为这本质上是营销炒作而非实质价值。 这质疑了 AI 大幅提升生产力的普遍说法的可信度，影响企业对 AI 工具的评估、资源分配和人力决策。 具体案例包括 OpenAI 在 2026 年 2 月一篇博客中吹捧一个拥有百万行代码但未描述用户价值的产品，以及微软高管提出的每位工程师每月百万行代码的目标。

hackernews · RyeCombinator · 6月11日 12:26 · [社区讨论](https://news.ycombinator.com/item?id=48489402)

**背景**: 代码行数长期以来在软件工程中备受批评，因其无法反映代码质量、可维护性或实际价值。尽管如此，AI 代码生成的兴起重新将其用作吸引投资者和利益相关者的光鲜指标。

**社区讨论**: 评论者普遍认为代码行数是误导性指标，指出拒绝它的理由并未改变。许多人担心企业以 AI 生成的代码量为借口裁员，同时掩盖质量问题。一些人感到围绕不可维护代码量的炒作正在消退，更务实的态度正在出现。

**标签**: `#lines-of-code`, `#ai-code-generation`, `#developer-productivity`, `#software-engineering`, `#tech-hype`

---

<a id="item-16"></a>
## [Jeremy Howard 提议顶尖 AI 实验室不应将最佳模型用于前沿研究](https://simonwillison.net/2026/Jun/10/jeremy-howard/#atom-everything) ⭐️ 7.0/10

Jeremy Howard 提议，拥有最领先 AI 模型的实验室不应将其用于前沿 AI 研究，但其他所有人都应能使用它。他批评 Anthropic 采取了相反的做法，认为这不安全。 该提议旨在防止危险的权力失衡和不受控制的递归式自我改进，这是 AI 安全的核心关切。它直接挑战了 Anthropic 等主要实验室的做法。 Howard 本人并不主张减缓递归式自我改进，而是倾向于民主化。他指出 Anthropic 声称将破坏其他试图使用其模型进行前沿研究的人。

rss · Simon Willison · 6月10日 15:23

**背景**: 递归式自我改进是指 AI 系统提升自身能力，可能导致超级智能。前沿 AI 模型是最先进的，通常闭源。以安全著称的 Anthropic 在此被批评使用自己的顶尖模型进行前沿研究，与安全原则相悖。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Recursive_self-improvement">Recursive self-improvement</a></li>
<li><a href="https://en.wikipedia.org/wiki/Frontier_AI">Frontier AI</a></li>

</ul>
</details>

**标签**: `#AI safety`, `#AI governance`, `#recursive self-improvement`, `#Anthropic`, `#AI policy`

---

<a id="item-17"></a>
## [Hugging Face 重新推出 paperswithcode.co 用于 AI 基准测试](https://www.reddit.com/r/MachineLearning/comments/1u1wq0a/introducing_papers_without_code_p/) ⭐️ 7.0/10

Hugging Face 的开源团队重新推出了 paperswithcode.co，作为一个自动化平台，可以解析 arXiv 和 Hugging Face 上的论文，生成带有交互式散点图和表格的领先基准排行榜，并且新增了对 GPT-5.5、Mythos 5 等闭源模型的可选评估功能。 该工具集中并自动化了多个 AI 领域的进展追踪，使研究人员能更方便地比较开源和闭源模型，在顶尖模型多为专有化的时代提升透明度。 该平台支持将任何来源（如博客文章）作为“论文”提交，闭源评估会打上相应标签；用户可以在设置中关闭闭源结果，仅查看开源模型排行榜。

reddit · r/MachineLearning · /u/NielsRogge · 6月10日 08:58

**背景**: paperswithcode.co 最初是一个连接论文与代码的社区资源，但在被收购后衰落。Hugging Face 通过自动化解析将其复兴。BrowseComp 是 OpenAI 在 2025 年 4 月推出的基准，用于测试网页浏览智能体，包含 1,266 个任务。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2504.12516">A Simple Yet Challenging Benchmark for Browsing Agents - arXiv</a></li>

</ul>
</details>

**标签**: `#machine learning`, `#benchmarks`, `#leaderboards`, `#research tools`, `#open source`

---

<a id="item-18"></a>
## [基于冻结潜在空间中时间冗余的无参自适应视频标记](https://www.reddit.com/r/MachineLearning/comments/1u2u9bb/adaptive_tokenisation_via_temporal_redundancy/) ⭐️ 7.0/10

论文提出了一种无参数方法，通过对冻结潜在空间中每个位置的时序 L1 差异进行阈值处理，识别并丢弃视频分词中的冗余空间位置，无需额外计算。 该方法使动态 token 分配能根据视觉复杂度自适应，静态场景大幅压缩，动态序列保留更多 token，且相比现有自适应分词器显著提速。 丢弃的位置由轻量级潜在修复变换器(LIT)重建，采用分解的时空注意力机制；推理流程相比连续自适应方法 ElasticTok-CV 快 31 倍，相比离散信息论方法 InfoTok 快 2 倍。

reddit · r/MachineLearning · /u/chhaya_35 · 6月11日 09:32

**背景**: 视频分词将视频帧转换为潜在 token 序列供 Transformer 等模型处理。自适应分词旨在给复杂区域分配更多 token，给简单区域更少，以减少计算量。以往方法需要额外网络或完整解码来决策分配，而本工作利用冻结分词器潜在空间中固有的时间冗余。

**标签**: `#video-tokenization`, `#adaptive-tokenization`, `#temporal-redundancy`, `#latent-representations`, `#machine-learning`

---

<a id="item-19"></a>
## [Anthropic 寻求新一轮融资，估值或达 300 亿至 400 亿美元](https://t.me/zaihuapd/41888) ⭐️ 7.0/10

Anthropic 正与投资者洽谈新一轮融资，估值可能达到 300 亿至 400 亿美元，几乎是今年初估值的两倍。 此轮融资凸显了人工智能行业日益激烈的资本竞争，Anthropic 和 OpenAI 等头部企业均寻求大规模融资以推动发展，这反映了投资者信心强劲以及推进 AI 技术所需的高昂成本。 Anthropic 主要通过提供 Claude AI 的访问权限来创收；据 The Information 报道，OpenAI 同时也在筹集 50 亿至 70 亿美元融资，估值接近 1500 亿美元。

telegram · zaihuapd · 6月11日 04:45

**背景**: Anthropic 是一家专注于人工智能安全的企业，由前 OpenAI 员工创立，以其 Claude 系列对话 AI 模型而闻名，与 OpenAI 的 ChatGPT 展开竞争。该公司成立于 2021 年，已迅速成为生成式人工智能领域的重要参与者，强调合乎道德且可靠的 AI 开发。

**标签**: `#AI`, `#funding`, `#Anthropic`, `#Claude`, `#OpenAI`

---

<a id="item-20"></a>
## [中国监管部门审查 Meta 收购 Manus，联合创始人被限制离境](https://t.me/zaihuapd/41895) ⭐️ 7.0/10

中国监管部门正在审查 Meta 对 AI 初创公司 Manus 的收购是否违反投资规定，并在审查期间限制联合创始人肖宏和季逸超离境。 这凸显了在地缘政治竞争下中国对外国科技收购的严格管控，可能对跨境 AI 投资和全球 AI 智能体格局产生影响。 联合创始人本月与国家发改委官员会面，被告知不能出境但可在中国境内出行；该收购于去年 12 月公布，金额未公开。

telegram · zaihuapd · 6月11日 10:00

**背景**: Manus AI 是由新加坡注册公司 Butterfly Effect 开发的一款通用型自主 AI 智能体。AI 智能体能独立执行研究、编程等复杂任务。Meta 是一家正拓展 AI 领域的美国社交媒体和科技巨头。中国的外国投资规定要求对涉及敏感技术的收购进行监管审查，以保护国家利益。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Manus_AI">Manus AI</a></li>
<li><a href="https://grokipedia.com/page/Manus_AI">Manus AI</a></li>

</ul>
</details>

**标签**: `#AI`, `#Meta`, `#Mergers & Acquisitions`, `#Regulation`, `#China`

---

<a id="item-21"></a>
## [macOS 27 将是最后完整支持 Rosetta 2 的版本](https://www.macrumors.com/2026/06/10/macos-golden-gate-last-to-support-intel-apps/) ⭐️ 7.0/10

苹果宣布 macOS 27 Golden Gate 将是最后一个完整支持 Rosetta 2（Intel 应用转译层）的版本。从 macOS 28 开始，Rosetta 2 只会为部分旧款 Intel 游戏保留，且 Intel Mac 将无法升级到新系统。 这标志着苹果向自研芯片过渡的关键一步，意味着 Intel 应用的无缝兼容时代即将结束。仍依赖纯 Intel 应用的开发者和用户必须在升级到 macOS 27 之后之前迁移至通用或原生 Apple Silicon 版本。 macOS 28 中保留的 Rosetta 2 功能仅限依赖于 Intel 框架且无人维护的游戏，不再支持一般的 Intel 应用。macOS 27 本身也已完全停止对 Intel Mac 的支持，因此它是这些设备的最后一个可升级版本。

telegram · zaihuapd · 6月11日 10:45

**背景**: Rosetta 2 是 macOS Big Sur（2020 年）引入的动态二进制翻译器，让 Apple Silicon（ARM 架构）Mac 能够运行基于 Intel x86_64 处理器的应用。苹果从 2020 年开始将 Mac 转换到自研芯片，并于 2023 年完成全产品线迁移。第一代 Rosetta（2006–2011 年）曾在 PowerPC 向 Intel 转换时扮演类似角色，随后被移除。Rosetta 2 的逐步淘汰与历史进程相似，意味着 Mac 上 Intel 原生应用支持的彻底终结。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Rosetta_(software)">Rosetta (software)</a></li>
<li><a href="https://www.reddit.com/r/apple/comments/1r6omno/macos_264_is_warning_that_rosetta_2_is_going_away/">macOS 26.4 is warning that Rosetta 2 is going away — what apps are you ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Apple_silicon">Apple silicon</a></li>

</ul>
</details>

**社区讨论**: Reddit 上的用户已注意到关于 Rosetta 2 即将下线的通知，引发了对哪些应用仍然依赖它的讨论。部分人认为这项淘汰在预料之中，另一些人则对旧软件兼容性表示担忧，并想知道还有多少 Mac 用户在使用纯 Intel 应用。

**标签**: `#macOS`, `#Apple Silicon`, `#Rosetta 2`, `#Software Compatibility`, `#Deprecation`

---

<a id="item-22"></a>
## [Instacart 与 OpenAI 在 ChatGPT 中推出集成杂货结账](https://t.me/zaihuapd/41900) ⭐️ 7.0/10

2025 年 12 月 8 日，Instacart 与 OpenAI 在 ChatGPT 中推出集成杂货购物功能，用户可直接在聊天界面内浏览商品、生成购物车并完成结账。 这标志着对话式 AI 与电子商务融合的重要一步，可能通过 AI 助手实现无缝交易来改变消费者购物方式，并为其他平台树立先例。 该功能利用了 Instacart 的实时配送网络和 OpenAI 的前沿模型，但未披露支持的区域或模型版本等具体细节。

telegram · zaihuapd · 6月11日 13:15

**背景**: Instacart 是北美领先的在线杂货配送平台，提供从多家零售商处当日达服务。OpenAI 的 ChatGPT 是一种对话式 AI，一直在集成插件和工具以扩展功能。此举是 AI 助手成为商务平台这一大趋势的一部分。

**标签**: `#AI`, `#e-commerce`, `#conversational AI`, `#ChatGPT`, `#Instacart`

---

<a id="item-23"></a>
## [uv 0.11.20 发布：增强 pip list 与隐藏升级命令](https://github.com/astral-sh/uv/releases/tag/0.11.20) ⭐️ 6.0/10

uv 0.11.20 于 2026-06-10 发布，为 uv pip list 添加了 --find-links 支持，引入了隐藏的 uv upgrade 预览命令，通过 ICF 优化减小 macOS 二进制文件大小，并提升了大型工作空间的发现性能。 这些增强使 uv 作为 pip 替代品更趋完善，改善了依赖管理的用户体验，并降低了资源占用，惠及 Python 开发者和 CI/CD 流程。 隐藏的 uv upgrade 命令目前拒绝 Git 版本；uv export 新增 --emit-index-url 和 --emit-find-links 输出选项；错误修复包括避免解析器栈溢出和改进缓存操作中的符号链接处理。

github · github-actions[bot] · 6月10日 17:21

**背景**: uv 是一个用 Rust 编写的快速 Python 包安装器和解析器，由 Astral（Ruff 的创建者）开发，目标是替代 pip、pip-tools 和 virtualenv 成为统一工具。相同代码折叠（ICF）是一种链接器优化技术，通过合并相同函数定义来减小二进制文件大小，常用于发布构建。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://learn.microsoft.com/en-us/cpp/build/reference/opt-optimizations?view=msvc-170">/OPT (Optimizations) | Microsoft Learn</a></li>

</ul>
</details>

**标签**: `#uv`, `#python`, `#packaging`, `#release`, `#tool`

---

<a id="item-24"></a>
## [请愿要求撤回加拿大 C-22 法案](https://www.ourcommons.ca/petitions/en/Petition/Sign/e-7416) ⭐️ 6.0/10

加拿大议会官方电子请愿平台上的一份请愿书呼吁撤回 C-22 法案，理由是该法案侵犯隐私。与此同时，众议院公共安全和国家安全委员会（SECU）正在对该法案进行逐条审议，并可能就修正案进行最终投票。 反对 C-22 法案凸显了公众对政府监控及其对加拿大科技行业寒蝉效应的日益担忧，以及隐私保护被侵蚀的广泛趋势。相关的 C-34 法案更加剧了人们对加拿大走向无隐私制度的恐惧，可能损害创新和公民自由。 请愿书（编号 e-7416）于 2025 年 4 月在官方议会请愿平台发起。在 HackerNews 讨论期间，评论者 EmbarrassedHelp 指出，SECU 委员会当天正在召开会议，逐条审查该法案并就修正案进行投票，这可能是法案推进前的最后阶段。

hackernews · hmokiguess · 6月11日 15:37 · [社区讨论](https://news.ycombinator.com/item?id=48491830)

**背景**: C-22 法案是加拿大议会一项立法提案，批评者认为它将扩大政府监控能力并削弱隐私保护。C-34 是一项独立但相关的法案，一些人认为它将彻底摧毁数字隐私。加拿大电子请愿允许公民正式向政府请愿，SECU 委员会负责审查涉及国家安全和公共安全的立法。

**社区讨论**: HackerNews 社区普遍对 C-22 法案持批评态度，认为它是更广泛的隐私侵蚀的一部分。评论者分享了 Michael Geist 的分析和议会直播等资源，呼吁其他人关注并发出声音，尽管大多数人怀疑请愿能否改变立法结果。一些人对加拿大政治表示无奈，指出两大主要政党都支持此类措施。

**标签**: `#privacy`, `#canada`, `#policy`, `#tech-sector`, `#legislation`

---

<a id="item-25"></a>
## [DeepSeek-R1 开源复现项目发布数据集与训练方案](https://github.com/huggingface/open-r1) ⭐️ 6.0/10

Hugging Face Open-R1 项目发布了 Mixture-of-Thoughts 数据集（包含从 DeepSeek-R1 中蒸馏出的 35 万条经过验证的推理轨迹），并提供了复现 DeepSeek-R1-Distill-Qwen-7B 的训练方案。 此类开源复现工作促进了透明度，使社区能够研究和改进先进的推理模型。但因项目较旧，与新兴替代方案相比，其时效性有所下降。 数据集涵盖数学、编程和科学任务，旨在教授逐步推理。训练方案针对 7B 模型，但代码库已超过一年未更新。

hackernews · yogthos · 6月11日 13:14 · [社区讨论](https://news.ycombinator.com/item?id=48489917)

**背景**: DeepSeek-R1 由中国人工智能公司 DeepSeek 于 2025 年 1 月推出，是一款开源权重推理模型，借助混合专家等技术以远低于 OpenAI o1 的成本实现了相当性能。它的发布引发了大量试图复现其能力的开源项目。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek">DeepSeek</a></li>

</ul>
</details>

**社区讨论**: 用户指出项目已过时，并推荐 OpenThoughts 和 OLMo 等更新项目。有人询问当前训练成本，还有人认为信息太旧，已无用处。

**标签**: `#LLM`, `#reasoning`, `#open-source`, `#dataset`, `#DeepSeek-R1`

---

<a id="item-26"></a>
## [Datasette 1.0a33 将 ?_extra= 模式扩展至查询和行](https://simonwillison.net/2026/Jun/11/datasette/#atom-everything) ⭐️ 6.0/10

Datasette 1.0a33 将先前仅用于表格的 `?_extra=` URL 参数模式扩展至查询和行，使 API 用户能在 JSON 响应中请求额外的元数据。 此增强使 Datasette JSON API 更加灵活和自描述，支持更丰富的客户端应用和更流畅的开发者体验，并标志着向 1.0 稳定版迈进一步。 `?_extra=` 参数接受逗号分隔的附加项，如 `columns`、`count`、`database` 等；此版本包含文档和一个借助 AI 构建的自定义 API 浏览器工具，用于展示该功能。

rss · Simon Willison · 6月11日 15:26

**背景**: Datasette 是一个用于发布和探索数据的开源工具，为 SQLite 数据库提供 JSON API。`?_extra=` 机制在 1.0a3 版本中引入，允许 API 使用者在标准响应之外请求额外元数据，减少多次请求。1.0a33 将此功能扩展到查询和行端点，统一了 API 界面。

**标签**: `#datasette`, `#api`, `#json`, `#release`, `#alpha`

---

<a id="item-27"></a>
## [datasette-agent 0.2a0：新增交互式提示与保存查询工具](https://simonwillison.net/2026/Jun/10/datasette-agent/#atom-everything) ⭐️ 6.0/10

datasette-agent 0.2a0 通过新的 context.ask_user() 方法在工具执行期间引入交互式用户提示，使暂停的对话在服务器重启后得以持久化。它还新增了一个内置的 save_query 工具，可将 SQL 保存为 Datasette 存储查询，并需要人工批准。 此更新通过允许用户在执行过程中干预，增强了人机协作，而持久化特性使智能体工作流更加健壮。save_query 工具将智能体生成的 SQL 直接集成到 Datasette 的查询管理中。 ask_user() 方法支持是/否、多项选择和自由文本问题，并将未回答的状态存储起来，因此挂起的对话在服务器重启后依然存在。工具在收到答案后从头重新执行，因此副作用应在调用 ask_user() 之后进行。save_query 工具需要明确的人工批准，会显示完整的 SQL 和提议的元数据。

rss · Simon Willison · 6月10日 23:57

**背景**: Datasette 是一个用于使用 SQLite 探索和发布结构化数据的开源工具。datasette-agent 是一个实验性框架，允许由大型语言模型驱动的智能体与 Datasette 实例交互，执行查询和数据操作等任务。此版本增加了人在回路中的能力，允许工具在执行过程中暂停并请求用户输入，并引入了保存智能体生成的查询的功能。

**标签**: `#datasette`, `#agent`, `#llm`, `#tool-use`, `#interactive`

---

<a id="item-28"></a>
## [Pyrecall：检测 LLM 微调灾难性遗忘的开源工具](https://www.reddit.com/r/MachineLearning/comments/1u2hjye/pyrecall_open_source_tool_for_detecting/) ⭐️ 6.0/10

Pyrecall v0.1.0 发布，这款开源 Python 工具通过比较训练前后的技能得分快照来检测大语言模型（LLM）微调过程中的灾难性遗忘，并支持 LoRA 适配器的回滚。 灾难性遗忘是 LLM 持续学习中的长期挑战；Pyrecall 提供了一个无需外部 API 的本地实用解决方案，可能为从业者节省时间和资源。 该工具为 v0.1.0 版本，采用 MIT 许可证，可通过 pip 安装。它能捕获技能得分快照，标记性能退化，并按名称回滚 LoRA 适配器。作者正寻求基准测试设计的反馈。

reddit · r/MachineLearning · /u/Level_Frosting_7950 · 6月10日 22:49

**背景**: 灾难性遗忘指模型在新任务上微调后遗忘了之前学到的技能。LLM 常针对特定领域微调，但这可能损害早期任务的表现。像 LoRA（低秩适应）这样的技术实现了参数高效微调，但遗忘仍可能发生。基准测试套件用于评估模型在不同任务上的各类技能。

**标签**: `#LLM fine-tuning`, `#catastrophic forgetting`, `#continual learning`, `#open-source tool`, `#Python`

---

<a id="item-29"></a>
## [字节跳动 2026 年 Q2 将推豆包二代手机，构建 AI 硬件生态](https://t.me/zaihuapd/41891) ⭐️ 6.0/10

字节跳动计划于 2026 年第二季度推出第二代豆包手机，仍由中兴努比亚代工，并同步研发 AI 眼镜和耳机，拓展 AI 硬件全生态。针对初代遭平台封锁的问题，豆包团队正与美团、微信等谈判接口权限。 此举表明字节跳动正加码 AI 消费硬件，力图将 AI 助手深度融入设备，并与其他手机品牌合作，可能挑战传统应用生态，推动 AI 原生交互的普及。 第一代豆包手机采用移动端优化的 UI-TARS 2.0 闭源模型；新款将继续与中兴合作，并尝试在传音、魅族等品牌手机中内置 AI 入口，但深度系统权限的获取仍需谈判。

telegram · zaihuapd · 6月11日 07:00

**背景**: 字节跳动以抖音闻名，此前推出第一代豆包手机，内置“豆包”AI 助手，但因被主流应用封锁而功能受限。新款手机旨在通过谈判获取权限，并联合多家厂商，以打造更开放的 AI 硬件生态。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://grokipedia.com/page/Doubao_smartphone">Doubao (smartphone)</a></li>

</ul>
</details>

**标签**: `#ByteDance`, `#AI hardware`, `#smartphone`, `#AI glasses`, `#consumer electronics`

---