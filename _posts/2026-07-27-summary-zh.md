---
layout: default
title: "Horizon Summary: 2026-07-27 (ZH)"
date: 2026-07-27
lang: zh
---

> 从 51 条内容中筛选出 28 条重要资讯。

---

1. [Kimi-K3：3 万亿参数开源权重模型发布](#item-1) ⭐️ 8.0/10
2. [德国迪卡侬上线 Wero 支付，助力欧洲电商](#item-2) ⭐️ 8.0/10
3. [论坛从 React 迁移到 HTMX 的实践案例](#item-3) ⭐️ 8.0/10
4. [Bun 的 Rust 重写已上线 Claude Code，v1.4 推迟发布](#item-4) ⭐️ 8.0/10
5. [调查揭露中国 LLM 令牌中继市场利用开源代理](#item-5) ⭐️ 8.0/10
6. [Ruff v0.16.0 将默认规则从 59 条扩展到 413 条](#item-6) ⭐️ 8.0/10
7. [提议：训练数据的形式化预训练闸门审计](#item-7) ⭐️ 8.0/10
8. [从零开始用 ARM64 汇编实现 YOLO26n 推理](#item-8) ⭐️ 8.0/10
9. [4B 开源权重模型在瑞典语医学问答中达到 o3 水平](#item-9) ⭐️ 8.0/10
10. [Claude 共享链接遭搜索引擎索引](#item-10) ⭐️ 8.0/10
11. [SpaceX 停止接受 2028 年后 Falcon 9 订单，全力押注 Starship](#item-11) ⭐️ 8.0/10
12. [谷歌 Gemini 4：迄今最雄心预训练，预计 2026 年底发布](#item-12) ⭐️ 8.0/10
13. [Fastjson 1.x 现无需 gadget 的高危 RCE 漏洞](#item-13) ⭐️ 8.0/10
14. [中芯国际测试中国首台国产 DUV 光刻机](#item-14) ⭐️ 8.0/10
15. [微软发布 MAI-Cyber 1 网络安全专用 AI 模型](#item-15) ⭐️ 7.0/10
16. [Libsm64：将《超级马力欧 64》重新打包为可复用库](#item-16) ⭐️ 7.0/10
17. [3DGS 存储优化综述：五个方向破解显存焦虑](#item-17) ⭐️ 7.0/10
18. [IMO 2026 上的 LLM 对比：前沿模型满分，其他模型依赖工程框架](#item-18) ⭐️ 7.0/10
19. [高通宣布全线产品 9 月 1 日起涨价](#item-19) ⭐️ 7.0/10
20. [AI 数据中心推动存储涨价，华为与长鑫关系趋紧](#item-20) ⭐️ 7.0/10
21. [中方驳美制裁：蒸馏模型是行业标准](#item-21) ⭐️ 7.0/10
22. [月之暗面将开源 3T 参数模型 Kimi-K3](#item-22) ⭐️ 7.0/10
23. [数据驱动的调查：清洗太阳能板通常没必要](#item-23) ⭐️ 6.0/10
24. [用 PyTorch 从头实现 Transformer 进行英-泰米尔语翻译](#item-24) ⭐️ 6.0/10
25. [开源端到端边缘机器学习平台，具备自动标注功能](#item-25) ⭐️ 6.0/10
26. [美国学校减少 Chromebook 使用，回归纸笔教学](#item-26) ⭐️ 6.0/10
27. [长鑫科技上市首日暴涨 471%创纪录](#item-27) ⭐️ 6.0/10
28. [三星或采用中国 DRAM 降成本提升在华份额](#item-28) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Kimi-K3：3 万亿参数开源权重模型发布](https://huggingface.co/moonshotai/Kimi-K3) ⭐️ 8.0/10

月之暗面（Moonshot AI）在 Hugging Face 上发布了 Kimi-K3，这是一个拥有 3 万亿参数的开源权重模型。该模型采用原生 mxfp4 精度，并附带基于营收的商业许可限制。 此次发布意义重大，因为它将开源权重模型的规模推至 3 万亿参数，为企业提供了前所未有的定制能力和知识产权自主权。同时，它为超大型模型的托管成本和定价设立了基准，将影响 AI 部署的经济性。 由于采用原生 mxfp4 精度，该模型推理需要约 1.5 TB 的显存，实际运行需要 16 块 B200 GPU 以优化上下文长度和吞吐量。商业许可规定，连续 12 个月总营收超过 2000 万美元的企业需与月之暗面另行协商协议。

hackernews · nateb2022 · 7月27日 06:18 · [社区讨论](https://news.ycombinator.com/item?id=49065752)

**背景**: 开源权重模型允许任何人下载训练好的参数，在本地运行、研究或针对特定任务进行微调，与封闭 API 不同。托管像 Kimi-K3 这样的超大型模型（3 万亿参数）成本极高，需要多块大显存高端 GPU。此类部署的经济性涉及成本、性能和控制权之间的权衡，此次发布有助于揭示这些方面。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://hai.stanford.edu/ai-definitions/what-is-an-open-weight-model">What is an Open-Weight Model? - Stanford HAI</a></li>
<li><a href="https://arxiv.org/html/2509.18101v1">A Cost-Benefit Analysis of On-Premise Large Language Model Deployment: Breaking Even with Commercial LLM Services</a></li>

</ul>
</details>

**社区讨论**: 社区讨论集中在三个方面：高昂的托管成本（据 Fireworks AI 估算，输入每百万 token 3 美元，输出每百万 token 15 美元）、可能限制大型公司商业使用的许可条款，以及初创公司获得的定制化和知识产权自主权优势。也有评论者感叹缺乏适合运行此类模型的准消费级硬件。

**标签**: `#AI`, `#large language models`, `#Kimi-K3`, `#Moonshot AI`, `#open-source`

---

<a id="item-2"></a>
## [德国迪卡侬上线 Wero 支付，助力欧洲电商](https://www.sgieurope.com/e-commerce/decathlon-germany-launches-wero-payment-on-its-website/122397.article) ⭐️ 8.0/10

德国迪卡侬在其官网 decathlon.de 集成了 Wero 这一基于 SEPA 即时转账的欧洲移动支付系统作为新的支付选项。 这一采用验证了 Wero 作为欧洲电子商务中信用卡和 PayPal 可行替代方案的地位，并表明商家对泛欧即时支付基础设施的信任正在增长。 Wero 依赖于 SEPA 即时信用转账（SCT Inst）方案，确保资金在 10 秒内到达收款人账户，支付流程使用二维码扫描和银行应用确认，用户体验流畅。

hackernews · doener · 7月27日 16:49 · [社区讨论](https://news.ycombinator.com/item?id=49072310)

**背景**: Wero 是由欧洲支付倡议（EPI）于 2024 年 7 月推出的统一移动支付系统，整合了 Giropay、iDEAL 等多个国家系统。它利用 SEPA 即时信用转账方案，这是一种泛欧方案，可在 36 个国家的银行账户之间实现即时欧元转账。2024 年，SEPA 即时转账法规成为强制要求，要求银行以不额外收费的方式提供即时转账，这为 Wero 提供了基础设施基础。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Wero_(payment)">Wero (payment) - Wikipedia</a></li>
<li><a href="https://www.europeanpaymentscouncil.eu/what-we-do/sepa-instant-credit-transfer">SEPA Instant Credit Transfer - European Payments Council</a></li>
<li><a href="https://www.db.com/news/detail/20251217-deutsche-bank-launches-wero-for-more-simple-and-sovereign-digital-payments-in-europe?language_id=1">Deutsche Bank launches Wero for more simple and sovereign digital payments in Europe</a></li>

</ul>
</details>

**社区讨论**: 社区总体持积极态度，称赞 Wero 的流畅用户体验和通过二维码扫描的快捷支付流程。一位用户强调了 Wero 在 AI 智能体支付方面的潜力，类似于波兰的 Blik 系统，另一位用户则指出迪卡侬本身技术先进，在东欧门店使用 RFID 进行自助结账。

**标签**: `#payments`, `#Wero`, `#SEPA`, `#e-commerce`, `#European payments`

---

<a id="item-3"></a>
## [论坛从 React 迁移到 HTMX 的实践案例](https://misago-project.org/t/removing-reactjs-from-the-codebase-and-adapting-htmx-for-ui-interactivity/1267/) ⭐️ 8.0/10

Misago 论坛项目详细说明了从代码库中移除 React.js 并采用 HTMX 来实现界面交互的决定，用服务端渲染的超媒体取代了客户端渲染。 这一迁移突显了 Web 开发中日益增长的趋势：团队选择像 HTMX 这样更简单的超媒体驱动工具，而非 React 等重型前端框架，尤其是在内容为主的应用程序中，完全的单页应用复杂性并非必需。 HTMX 是一款小型（压缩后约 16KB）的 JavaScript 库，通过属性扩展 HTML 以支持 AJAX、WebSocket 和服务器推送事件；迁移报告指出，相比 React，代码库体积减少了 67%。

hackernews · Ralfp · 7月27日 09:58 · [社区讨论](https://news.ycombinator.com/item?id=49067301)

**背景**: HTMX 是一个前端库，允许开发者使用 HTML 属性构建现代用户界面，无需编写 JavaScript 即可实现 AJAX、CSS 过渡和服务器事件。它遵循超媒体驱动的方法，与 React 基于组件的客户端渲染形成对比。这一转变是更广泛讨论的一部分，即关于现代 Web 开发的复杂性以及回归更简单、以服务器为中心的架构的优点。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Htmx">htmx - Wikipedia</a></li>
<li><a href="https://htmx.org/">htmx - high power tools for html</a></li>
<li><a href="https://hypermedia.systems/hypermedia-a-reintroduction/">Hypermedia: A Reintroduction</a></li>

</ul>
</details>

**社区讨论**: 社区评论褒贬不一：一些人称赞 HTMX 的简洁性及其对论坛软件的适用性，而另一些人则报告了交互式可过滤列表的性能问题和滚动位置问题。大家一致认为 HTMX 适用于内容密集型的网站，但在需要细粒度 DOM 更新的动态 UI 方面存在困难。

**标签**: `#React`, `#HTMX`, `#web development`, `#migration`, `#hypermedia`

---

<a id="item-4"></a>
## [Bun 的 Rust 重写已上线 Claude Code，v1.4 推迟发布](https://lockwood.dev/ai/2026/07/27/how-is-the-bun-rewrite-in-rust-going.html) ⭐️ 8.0/10

这次重写将 Bun 从 Zig 迁移到 Rust，有望提升性能和内存安全，但依赖 LLM 辅助翻译以及由此导致的延迟，引发了关于此类大规模重写质量与管理的讨论。这场辩论反映了软件社区在使用 AI 工具构建核心基础设施项目上的广泛分歧。 Rust 重写在很大程度上借助了 LLM（特别是 Claude Code）来转换原始的 Zig 代码库。Bun v1.4 延迟是因为 Jarred 承诺了新增的 Node.js 测试通过数量作为兼容性里程碑，而这些 PR 尚未合并。

hackernews · tomlockwood · 7月27日 11:12 · [社区讨论](https://news.ycombinator.com/item?id=49067854)

**背景**: Bun 是一个 JavaScript 运行时、包管理器和测试运行器，旨在无缝替代 Node.js，最初用 Zig 构建以实现高速。Claude Code 是 Anthropic 推出的 AI 编程助手，可以编辑文件、运行命令和自动化 Git 工作流，类似其他 LLM 编码工具。像 Bun 这样的大型项目从一个系统语言重写到另一个语言是一项巨大的工程，通常以性能或安全提升为理由。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Bun_(software)">Bun (software) - Wikipedia</a></li>
<li><a href="https://bun.sh/">Bun — A fast all-in-one JavaScript runtime</a></li>
<li><a href="https://docs.anthropic.com/en/docs/claude-code/overview">Claude Code overview - Anthropic</a></li>

</ul>
</details>

**社区讨论**: 一些评论者称赞了 LLM 辅助翻译的速度，而另一些人则对 AI 生成代码的质量以及重写关键工具是否明智表示怀疑。还有用户提到了一个名为 'buz' 的竞争性分支，它对原始 Zig 代码库进行了现代化改造，声称无需重写为 Rust 就实现了亚秒级构建时间。

**标签**: `#bun`, `#rust`, `#javascript`, `#rewrite`, `#llm`

---

<a id="item-5"></a>
## [调查揭露中国 LLM 令牌中继市场利用开源代理](https://simonwillison.net/2026/Jul/26/relay-market/#atom-everything) ⭐️ 8.0/10

Matt Lenhard 的调查揭示了一个蓬勃发展的中国 LLM 令牌转售市场，转售商通过滥用免费试用、窃取凭证和退款攻击获取 API 密钥，并使用 one-api 和 new-api 等开源代理工具来提供打折的 LLM 访问服务。 这个市场对 AI 公司和开发者构成了重大的安全和财务风险，因为它激励了利用未受保护端点的行为，破坏了官方定价模式，凸显了改进 API 密钥管理和消费上限的紧迫需求。 转售商通过将请求代理到来自免费试用、被攻破的支持机器人或被盗信用卡的凭证池中来提供折扣 LLM 令牌，使用的开源代理软件原本设计用于负载均衡和密钥管理。

rss · Simon Willison · 7月26日 19:30

**背景**: 像 OpenAI 和 Anthropic 这样的 LLM API 提供商按 token 收费提供模型访问。one-api 和 new-api 等第三方代理工具允许用户聚合多个 API 密钥并跨它们路由请求以实现负载均衡或冗余。然而，这些工具可能被滥用来聚合通过欺诈手段获得的密钥，从而实现低价令牌转售。买家可能寻求更便宜的访问、规避地理限制或收集数据用于模型蒸馏。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/Mirrowel/LLM-API-Key-Proxy">GitHub - Mirrowel/LLM-API-Key-Proxy: Universal LLM Gateway: One API, every LLM. OpenAI/Anthropic-compatible endpoints with multi-provider translation and intelligent load-balancing. · GitHub</a></li>
<li><a href="https://docs.litellm.ai/docs/simple_proxy">LiteLLM AI Gateway (LLM Proxy) | liteLLM</a></li>

</ul>
</details>

**标签**: `#LLM`, `#API security`, `#fraud`, `#token reselling`, `#AI infrastructure`

---

<a id="item-6"></a>
## [Ruff v0.16.0 将默认规则从 59 条扩展到 413 条](https://simonwillison.net/2026/Jul/25/ruff/#atom-everything) ⭐️ 8.0/10

Ruff v0.16.0 于 2026 年 7 月 23 日发布，将默认启用的 lint 规则从 59 条增加到 413 条，新增了许多可捕获语法错误和运行时错误的检查。这一变化导致使用未固定版本 'ruff' 开发依赖的项目出现 CI 失败，Simon Willison 的项目就是如此。 这一扩展显著提高了所有使用默认配置 Ruff 的 Python 项目的基线代码质量检查，能够捕获以前需要显式配置才能发现的问题。这将迫使许多开发团队要么固定 Ruff 版本，要么更新代码以符合新规则，从而影响大多数 Python CI 流水线。 Ruff 现在共有 968 条规则（v0.1.0 时为 708 条），默认启用 413 条。使用单个命令 'uvx ruff@latest check . --fix --unsafe-fixes' 可以自动修复许多问题，例如在 sqlite-utils 项目中修复了 1618 个错误中的 1538 个。

rss · Simon Willison · 7月25日 22:44

**背景**: Ruff 是一个用 Rust 编写的极速 Python linter 和代码格式化工具，旨在作为 Flake8、isort 和 Black 等工具的即插即用替代品。未固定依赖（unpinned dependency）意味着项目没有指定 'ruff' 的确切版本，因此新版本（包含破坏性变更）会自动安装，导致 CI 失败。新规则包括检查无时区 datetime 的使用（DTZ005）、捕获盲异常（BLE001）以及无用的属性访问（B018）。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.astral.sh/ruff/linter/">The Ruff Linter | Ruff - Astral</a></li>
<li><a href="https://github.com/astral-sh/ruff">GitHub - astral-sh/ruff: An extremely fast Python linter and ... ruff · PyPI Ruff - Astral Ruff: Complete Guide to Python's Fastest Linter | pydevtools GitHub - sartcod/ruff: An extremely fast Python linter and ... Ruff: A Modern Python Linter for Error-Free and Maintainable ...</a></li>
<li><a href="https://pypi.org/project/ruff/">ruff · PyPI</a></li>

</ul>
</details>

**标签**: `#Python`, `#linting`, `#Ruff`, `#development tools`, `#code quality`

---

<a id="item-7"></a>
## [提议：训练数据的形式化预训练闸门审计](https://www.reddit.com/r/MachineLearning/comments/1v8a3nu/training_data_needs_a_real_gonogo_gate_before/) ⭐️ 8.0/10

一位 Reddit 用户提出了一种形式化的预训练闸门，基于数据泄露、矛盾、冗余、覆盖度和来源等明确证据指标，对训练工件进行审计并给出可重现的 PASS、WARNING、FAIL 或 FAIL_SECURITY 裁决，且不依赖大语言模型进行判断。 如果被采用，这种方法可以用透明、可重现的闸门取代主观的、基于笔记本的检查点，从而缩小机器学习训练流程中的关键缺口，提高跨团队和组织的训练可靠性与安全性。 该系统会生成修复计划，仅对派生副本应用已批准的更改并保留原始副本，随后进行第二次审计，所有操作都与清单和校验和绑定以确保可重现性。

reddit · r/MachineLearning · /u/jesusmjk · 7月27日 19:13

**背景**: 数据泄露指训练集外的信息影响模型构建，导致过于乐观的性能估计；数据矛盾指不一致的标注损害模型鲁棒性；数据来源追踪记录数据的来源和变换，对审计至关重要。这些问题常见于当前训练流程中，往往只能在训练后或通过主观人工审查才发现。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Leakage_(machine_learning)">Leakage ( machine learning ) - Wikipedia</a></li>
<li><a href="https://arxiv.org/html/2504.00180v1">Contradiction Detection in RAG Systems: Evaluating LLMs as ...</a></li>
<li><a href="https://ckaestne.medium.com/versioning-provenance-and-reproducibility-in-production-machine-learning-355c48665005">Versioning, Provenance, and Reproducibility in Production Machine Learning | by Christian Kästner | Medium</a></li>

</ul>
</details>

**标签**: `#machine learning`, `#data quality`, `#training pipeline`, `#MLOps`, `#data validation`

---

<a id="item-8"></a>
## [从零开始用 ARM64 汇编实现 YOLO26n 推理](https://www.reddit.com/r/MachineLearning/comments/1v6w394/i_implemented_the_yolo26n_model_inference_from/) ⭐️ 8.0/10

一位开发者完全从零开始，使用 ARM64 汇编语言和 C 语言实现了 YOLO26n 模型推理，不依赖任何现有深度学习框架，并将其部署在 Raspberry Pi 4 上。 该项目展示了开发者对底层系统和神经网络推理优化的深刻理解，所采用的 NEON SIMD、Winograd 卷积和算子融合等技术对于在资源受限设备上实现高效边缘 AI 部署至关重要。 实现包括自定义 ARM64 微内核、缓存感知分块以及模型参数的自定义二进制格式，并正确生成目标检测结果，但性能提升低于预期。

reddit · r/MachineLearning · /u/Forward_Confusion902 · 7月26日 06:43

**背景**: YOLO（You Only Look Once）是一种流行的实时目标检测模型系列。该项目使用了 YOLO26n，这是 YOLOv6 为边缘设备定制的一个变体。ARM64 汇编是 ARM 处理器（如 Raspberry Pi 4 的 CPU）的底层指令集。NEON SIMD（单指令多数据）允许并行处理多个数据点，而 Winograd 卷积是一种减少卷积层乘法次数的算法。算子融合将多个神经网络操作合并为一个内核，以减少内存流量和开销。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.emergentmind.com/topics/winograd-convolution">Winograd Convolution in CNNs</a></li>
<li><a href="http://www.aussieai.com/research/kernel-fusion">Kernel Operator Fusion</a></li>

</ul>
</details>

**标签**: `#YOLO`, `#ARM64`, `#Assembly`, `#Edge AI`, `#Inference Optimization`

---

<a id="item-9"></a>
## [4B 开源权重模型在瑞典语医学问答中达到 o3 水平](https://www.reddit.com/r/MachineLearning/comments/1v71wds/openweight_4b_models_approach_o3level_medical/) ⭐️ 8.0/10

一款 4B 参数的开源权重模型 Qwen3.5-4B，在 MedQA-SWE 瑞典语医学考试数据集上，通过使用 S-GRPO 论文中的早期退出干预进行推理，达到了 87% 的准确率，接近 OpenAI o3 模型 88% 的水平，并超过 GPT-4 的 84%。 这表明小型开源权重模型能够在资源匮乏的语言的特定领域任务上与专有前沿模型相媲美，从而大大降低了在非英语环境中部署强大医疗 AI 的门槛。 Qwen3.5-4B 无需后训练即可达到 77% 的准确率，启用推理后达到 87%，早期退出干预可防止推理陷入无限循环。尽管提示是瑞典语，但该模型的所有推理均使用英语，证实了语言并非障碍。

reddit · r/MachineLearning · /u/AccomplishedCat4770 · 7月26日 11:58

**背景**: 开源权重模型是指其学习参数（权重）公开可用的 AI 系统，具有透明度、可微调和可复现性。MedQA-SWE 数据集包含 3,180 道瑞典语临床多选题，来源于外国医生申请瑞典行医执照的考试。S-GRPO 是一种强化学习方法，训练模型在推理足够时提前退出，从而在保持准确性的同时缩短推理长度。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://aclanthology.org/2024.lrec-main.975/">MedQA-SWE - a Clinical Question & Answer Dataset for Swedish</a></li>
<li><a href="https://arxiv.org/abs/2505.07686">S - GRPO : Early Exit via Reinforcement Learning in Reasoning Models</a></li>
<li><a href="https://medium.com/@kimanited73/open-weight-models-f504be677b1c">Open Weight Models . What are they, and why should you... | Medium</a></li>

</ul>
</details>

**标签**: `#LLMs`, `#Medical AI`, `#Swedish NLP`, `#Open-weight models`, `#Reasoning`

---

<a id="item-10"></a>
## [Claude 共享链接遭搜索引擎索引](https://search.brave.com/search?q=site%3Aclaude.ai%2Fshare&amp;source=android) ⭐️ 8.0/10

由于 Anthropic 未添加 noindex 标签，Brave 和 Bing 等搜索引擎已索引了 Claude 的公开共享对话链接，导致 API 密钥和个人信息等敏感数据泄露。 此安全漏洞将无数用户置于数据泄露和身份盗窃的风险之中，并且它重演了 ChatGPT 一年前已修复的类似问题，凸显了 AI 聊天产品中对基本隐私保护的持续忽视。 谷歌已屏蔽了这些链接的索引，但 Brave 和 Bing 仍在继续索引；泄露的信息包括 API 密钥、加密货币钱包详情、个人简历、法律咨询记录及社会安全号码等。

telegram · zaihuapd · 7月26日 11:16

**背景**: noindex 元标签用于告知搜索引擎爬虫不要索引某个页面，为敏感内容添加该标签是标准的隐私保护做法。Claude 的共享功能会创建对话的公开快照，原意仅供通过直接链接分享，但由于缺少 noindex 标签，这些页面会通过搜索引擎被发现。这一疏漏与 ChatGPT 过去的漏洞类似，后者通过给共享链接添加 noindex 标签得以修复。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Noindex">noindex - Wikipedia</a></li>
<li><a href="https://developers.google.com/search/docs/crawling-indexing/block-indexing">Block Search Indexing with noindex | Google Search Central | Documentation | Google for Developers</a></li>
<li><a href="https://thecybersecguru.com/news/claude-shared-chats-google-search-privacy/">Claude Share Links Became Searchable on... | The CyberSec Guru</a></li>

</ul>
</details>

**标签**: `#privacy`, `#security`, `#Claude`, `#data leak`, `#AI chat`

---

<a id="item-11"></a>
## [SpaceX 停止接受 2028 年后 Falcon 9 订单，全力押注 Starship](https://www.bloomberg.com/news/articles/2026-07-23/spacex-is-turning-away-falcon-customers-in-major-bet-on-starship) ⭐️ 8.0/10

SpaceX 已停止接受 2028 年后的新 Falcon 9 发射合同，并缩减部分 Falcon 部件生产，以加速向 Starship 火箭过渡。 这一战略转变可能重塑全球发射市场，因为 Starship 的成功对 SpaceX 在卫星互联网和深空任务中的未来至关重要，但任何延误都可能导致商业发射能力出现缺口。 该公司仍计划支持美国国防部和 NASA 的 Falcon 9 任务，但将不再接受商业拼单预订。由于 Starship 延误，SpaceX 股价自 2026 年 6 月 IPO 以来下跌约 25%。

telegram · zaihuapd · 7月26日 12:42

**背景**: Falcon 9 是 SpaceX 的主力火箭，凭借可重复使用的第一级多年来主导了商业发射市场。Starship 是下一代完全可重复使用的超重型运载火箭，旨在将大型载荷送入轨道、月球和火星。通过全面转向 Starship，SpaceX 正承担重大商业风险，押注新火箭将在 2028 年底前投入商业运营。

**标签**: `#SpaceX`, `#Starship`, `#Falcon 9`, `#商业航天`, `#发射市场`

---

<a id="item-12"></a>
## [谷歌 Gemini 4：迄今最雄心预训练，预计 2026 年底发布](https://9to5google.com/2026/07/26/google-gemini-4-teases/) ⭐️ 8.0/10

谷歌 CEO Sundar Pichai 在 Alphabet 2026 年第二季度财报电话会议上宣布，Gemini 4 正在训练中，是公司至今最具雄心的预训练项目，预计 2026 年底发布。 这标志着谷歌对前沿 AI 开发和大规模预训练的坚定投入，可能为 AI 行业设定新标杆，并影响依赖谷歌模型的竞争对手和开发者。 Gemini 4 正在训练中，Pichai 对内部进展表示兴奋。此外，Gemini 3.x Flash 系列将保持几乎每月一次的更新，重点提升智能编码等能力。

telegram · zaihuapd · 7月27日 04:06

**背景**: 预训练是大型语言模型在大规模文本语料上学习语言模式的初始阶段，为进一步微调奠定基础。Gemini 是谷歌的多模态 AI 模型系列，早期版本包括 Gemini 1.0、1.5、2.0 以及 3.x Flash 系列。前沿模型如 GPT-3 曾基于数千亿 token 训练，而现代模型现在使用数万亿 token 并具备多模态能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Gemini_(language_model)">Gemini (language model ) - Wikipedia</a></li>
<li><a href="https://medium.com/@nursena_kok/pre-training-phase-of-large-language-models-the-foundation-of-modern-ai-111b377f0a33">Pre-training Phase of Large Language Models: The Foundation of Modern AI | by Nursena Kok | Medium</a></li>

</ul>
</details>

**标签**: `#Google`, `#Gemini`, `#AI`, `#Large Language Model`, `#AGI`

---

<a id="item-13"></a>
## [Fastjson 1.x 现无需 gadget 的高危 RCE 漏洞](https://t.me/zaihuapd/42797) ⭐️ 8.0/10

安全研究人员 Kirill Firsov 披露了 Fastjson 1.2.68 至 1.2.83 版本中存在的高危远程代码执行漏洞。该漏洞无需开启 autoTypeSupport 或依赖任何 gadget 链，且在 JDK 8、17 和 21 上均可利用。 这一漏洞意义重大，因为 Fastjson 1.x 在 Java 应用中被广泛使用，且该漏洞能以极低的先决条件实现远程代码执行。由于 Fastjson 1.x 已于 2024 年 10 月停止维护，官方不会发布补丁，受影响系统若不升级至 Fastjson2 将面临风险。 该漏洞影响 Fastjson 1.2.68 至 1.2.83 版本，无需启用 autoType 功能或依赖任何 classpath gadget。临时缓解措施是启用安全模式（如通过 -Dfastjson.parser.safeMode=true），但唯一的彻底修复方案是升级到 Fastjson2。

telegram · zaihuapd · 7月27日 10:31

**背景**: Fastjson 是 Java 中常用的 JSON 序列化/反序列化库。其 autoType 特性允许 JSON 输入通过 @type 字段指定要反序列化的类类型，这曾多次导致反序列化漏洞。Gadget 链是一系列类，在反序列化时可被利用来执行任意代码。此次披露的漏洞绕过了常见的防护措施，既不要求启用 autoType，也无需任何已知的 gadget 链，因此尤为危险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/alibaba/fastjson/wiki/fastjson_safemode_en">fastjson_safemode_en · alibaba/fastjson Wiki</a></li>
<li><a href="https://www.alphabot.com/security/blog/2020/java/Fastjson-exceptional-deserialization-vulnerabilities.html">Fastjson: exceptional deserialization vulnerabilities - Alphabot Security</a></li>
<li><a href="https://medium.com/@dub-flow/deserialization-what-the-heck-actually-is-a-gadget-chain-1ea35e32df69">Deserialization: What the Heck *Actually* Is a Gadget Chain? | by Florian Walter | Medium</a></li>

</ul>
</details>

**标签**: `#安全漏洞`, `#Java`, `#Fastjson`, `#RCE`, `#远程代码执行`

---

<a id="item-14"></a>
## [中芯国际测试中国首台国产 DUV 光刻机](https://t.me/zaihuapd/42800) ⭐️ 8.0/10

中芯国际正在试运行中国首台由上海初创公司宇量昇研发的深紫外（DUV）光刻机，用于生产 28 纳米芯片，并尝试通过多重图形化工艺实现 7 纳米，甚至挑战 5 纳米。 这标志着中国半导体自主化的重要一步，减少了对受美国出口管制限制的 ASML 设备的依赖，但该设备在性能和良率方面仍落后 ASML 多年。 该设备大部分零部件已实现国产化，但仍有部分依赖进口。业内人士预计，实现稳定量产和竞争力良率需要一到两年，最快可能于 2027 年进入量产。

telegram · zaihuapd · 7月27日 14:10

**背景**: 深紫外（DUV）光刻利用 193nm 波长的光将电路图案投影到硅晶圆上，是制造先进芯片的关键技术。多重图形化技术允许 DUV 系统制造出比单次曝光分辨率极限更小的特征，从而实现 7 纳米等节点。目前，中国最先进的芯片依赖进口的 ASML DUV 设备，而 EUV 光刻机因美国出口管制被禁止对华销售。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DUV_lithography">DUV lithography</a></li>
<li><a href="https://en.wikipedia.org/wiki/Multiple_patterning">Multiple patterning - Wikipedia</a></li>

</ul>
</details>

**标签**: `#semiconductors`, `#lithography`, `#SMIC`, `#China`, `#DUV`

---

<a id="item-15"></a>
## [微软发布 MAI-Cyber 1 网络安全专用 AI 模型](https://microsoft.ai/news/introducing-mai-cyber-1-flash-inside-mdash/) ⭐️ 7.0/10

微软宣布推出 MAI-Cyber 1 Flash，这是一个基于其安全系统每天数万亿信号构建的网络安全 AI 模型，在 CyberGym 评测中获得 96%的分数，且运行成本仅为竞品的一半。 此次发布是将专用 AI 应用于网络安全领域的重要一步，利用了微软独有的海量真实安全数据优势（竞争对手无法模仿），并有望使漏洞检测更高效、成本更低。 该模型专门用于在复杂代码库中发现高难度漏洞，并驱动微软的漏洞识别与修复工具 MDASH；同时它还与 Project Perception 一同发布，后者是一个将多个 AI 模型编排成自主代理团队的代理型安全系统。

hackernews · migmartri · 7月27日 16:52 · [社区讨论](https://news.ycombinator.com/item?id=49072361)

**背景**: 微软拥有数十年的安全产品开发经验（如 Defender、Azure Sentinel），每天从身份、终端、云和网络收集数万亿安全信号。MAI-Cyber 1 是一个专门为网络安全任务微调的大型语言模型，在科技公司纷纷开发代码生成、威胁分析等专用 AI 模型的市场中竞争。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://runtimewire.com/article/microsoft-mai-cyber-1-flash-mdash-launch">Microsoft launches MAI - Cyber - 1 -Flash, a cost‑efficient... - RuntimeWire</a></li>
<li><a href="https://techcrunch.com/2026/07/27/microsoft-launches-its-first-cyber-model-and-a-new-agentic-cybersecurity-system/">Microsoft launches its first cybersecurity model, plus... | TechCrunch</a></li>
<li><a href="https://www.nytimes.com/2026/07/27/technology/microsoft-unveils-ai-cybersecurity-tools.html">Microsoft Unveils A. I . Cybersecurity Tools - The New York Times</a></li>

</ul>
</details>

**社区讨论**: 社区评论中既有兴趣也有怀疑：有人质疑微软的数据优势是否意味着该模型最擅长修复微软自家的产品，有人指出网络安全是“实时强化学习循环”的讽刺之处，还有少数人批评模型命名方式，并对如何获取模型感到困惑。

**标签**: `#AI`, `#Cybersecurity`, `#Microsoft`, `#Machine Learning`, `#LLM`

---

<a id="item-16"></a>
## [Libsm64：将《超级马力欧 64》重新打包为可复用库](https://github.com/libsm64/libsm64) ⭐️ 7.0/10

Libsm64 从《超级马力欧 64》的反编译项目中提取移动和渲染代码，并将其作为 C 语言共享库公开，使开发者能够在任何外部游戏引擎中嵌入马力欧角色。 该项目展示了游戏保存和模组制作的一种新颖方式，将经典游戏角色转化为可移植资产，实现了如马力欧出现在《半条命 2》中这样的跨游戏创意整合，而无需依赖专有加密或元宇宙炒作。 该库的全部外部 API 定义在单个头文件（libsm64.h）中，并在测试目录下提供了最小化示例。它基于 n64decomp 团队对《超级马力欧 64》的完整反编译（含日本、美国、欧洲、Shindou 和 iQue 版本）。

hackernews · klaussilveira · 7月27日 10:04 · [社区讨论](https://news.ycombinator.com/item?id=49067352)

**背景**: Libsm64 基于《超级马力欧 64》的反编译项目，该项目将原始的 N64 游戏从二进制机器码逆向工程恢复为可读的 C 源代码。反编译后的代码可以重新编译出与原始 ROM 完全相同的文件。Libsm64 将这份开源代码中马力欧角色的移动和渲染逻辑封装成一个独立的库，使该角色与其原生游戏引擎解耦。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/libsm64/libsm64">GitHub - libsm64/libsm64: Mario 64 as a library for use in ...</a></li>
<li><a href="https://daily.dev/posts/libsm64-mario-64-as-a-library-for-use-in-external-game-engines-igf1gqkp4">Libsm64: Mario 64 as a library for use in external game...</a></li>

</ul>
</details>

**社区讨论**: 社区评论普遍非常积极，称赞该项目的创新性及其释放的创意潜力，例如马力欧出现在《半条命 2》中的例子。一些用户对非工程人员的易用性表示好奇，还有些人开玩笑说可以将'马力欧 64 作为一种服务'出售，但随即澄清这是针对任天堂的玩笑。

**标签**: `#reverse engineering`, `#game development`, `#C/C++`, `#open source`, `#Nintendo`

---

<a id="item-17"></a>
## [3DGS 存储优化综述：五个方向破解显存焦虑](https://mp.weixin.qq.com/s?__biz=MzIzNjc1NzUzMw==&mid=2247907517&idx=3&sn=47197285f42f0199832d9f5b6612b961) ⭐️ 7.0/10

一篇综述文章系统性地总结了降低 3D Gaussian Splatting（3DGS）显存占用的五个研究方向，旨在解决单个场景显存消耗可超过 700MB 的问题。 3DGS 广泛应用于实时照片级新视角合成，但过高的显存消耗限制了其在消费级硬件和移动设备上的部署。这篇综述为存储优化提供了系统化路线图，对推动 3DGS 在图形学、VR/AR 和机器人等领域的实际应用至关重要。 这篇综述指出了五个优化方向，涵盖算法设计、内存管理以及硬件与软件的协同演进，尤其是光栅化器与其他组件的协同。采用 3DGS 渲染一个典型 3D 场景可能消耗超过 700MB 的显存。

rss · 量子位 · 7月27日 03:31

**背景**: 3D Gaussian Splatting（3DGS）是一种体渲染技术，通过各向异性的 3D 高斯体表示场景，能从稀疏图像实现实时辐射场渲染。该技术由 Kerbl 等人于 2023 年提出，因其高质量的新视角合成而广受欢迎，但每个高斯体需要存储位置、协方差、颜色和不透明度等参数，导致显存消耗极高。在保持质量的同时优化存储是当前活跃的研究方向。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/3D_Gaussian_splatting">3D Gaussian splatting</a></li>
<li><a href="https://en.wikipedia.org/wiki/Gaussian_splatting">Gaussian splatting - Wikipedia</a></li>
<li><a href="https://github.com/graphdeco-inria/gaussian-splatting">GitHub - graphdeco-inria/gaussian-splatting: Original ...</a></li>

</ul>
</details>

**标签**: `#3D Gaussian Splatting`, `#存储优化`, `#计算机图形学`, `#综述`, `#内存管理`

---

<a id="item-18"></a>
## [IMO 2026 上的 LLM 对比：前沿模型满分，其他模型依赖工程框架](https://www.reddit.com/r/MachineLearning/comments/1v6wskz/we_compared_different_llms_on_imo_2026_r/) ⭐️ 7.0/10

一项研究评估了多个 LLM 在最新发布的 2026 年国际数学奥林匹克竞赛问题上的表现，发现前沿模型（如 Sol 和 Fable）无论是否使用工程框架都取得了满分，而其他模型如 Sonnet 和 Opus 在使用工程框架（特别是自定义多智能体框架 AutoFyn）后表现显著提升。 这一基准测试表明，前沿模型在全新的竞赛问题上已接近完美的数学推理能力，同时也凸显出工程框架（包括编排、检索和多智能体协调）能够显著提升较弱模型的表现，使其成为构建可靠 LLM 应用的关键领域。 该研究由前 IMO 奖牌获得者进行手动评分以验证结果，并指出即使在可验证的数学领域，幻觉问题依然存在——例如 Sonnet 在问题 P3 上给出了错误解答。最难的问题 P3 需要一个关键简化，所有非前沿模型都无法发现，即使在使用框架支持检索和验证的情况下运行了 20 小时。

reddit · r/MachineLearning · /u/pequalnp92 · 7月26日 07:21

**背景**: 国际数学奥林匹克竞赛（IMO）是一项年度赛事，题目全新且难度极高，旨在考验高级推理能力。LLM 工程框架指的是围绕 LLM 构建的系统，通过添加记忆、编排、多智能体协调和评估层来提升复杂任务的表现。作者开发了自定义框架 AutoFyn，用以研究此类工程如何缩小前沿模型与非前沿模型之间的差距。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2603.03329">[2603.03329] AutoHarness: improving LLM agents by automatically synthesizing a code harness</a></li>
<li><a href="https://www.decodingai.com/p/agentic-harness-engineering">Agentic Harness Engineering: LLMs as the New OS</a></li>
<li><a href="https://github.com/walkinglabs/awesome-harness-engineering">walkinglabs/awesome-harness-engineering - GitHub</a></li>

</ul>
</details>

**标签**: `#LLM evaluation`, `#mathematical reasoning`, `#benchmark`, `#IMO`, `#harness engineering`

---

<a id="item-19"></a>
## [高通宣布全线产品 9 月 1 日起涨价](https://t.me/zaihuapd/42782) ⭐️ 7.0/10

2026 年 7 月 24 日，高通通知客户，自 2026 年 9 月 1 日起出货的所有产品将涨价，原因是制造成本上升和 AI 驱动的供应紧张。 此次涨价影响整个移动和物联网芯片生态，可能推高智能手机、笔记本电脑和汽车电子的成本，并反映出 AI 需求导致的半导体制造结构性变化。 公司未公布统一涨幅或具体产品型号，而是表示客户经理将逐一联系客户提供新报价，部分已下单但排在 9 月后出货的订单也可能被重新报价。

telegram · zaihuapd · 7月26日 10:20

**背景**: 半导体制造涉及多个阶段：晶圆制造、封装和测试，其中基板材料（如硅晶圆）是基础。针对 AI 芯片的先进封装需要昂贵的材料，如玻璃基板和高密度互连。AI 和数据中心需求的激增给供应链带来压力，推高了整个行业的成本。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://pcbmake.com/substrate-material-for-semiconductors/">Choosing the Right Substrate Material for Semiconductors</a></li>
<li><a href="https://www.nextmsc.com/report/semiconductor-packing-market">Semiconductor Packing Market: 64.22 billion USD 2030 Goal</a></li>

</ul>
</details>

**标签**: `#Qualcomm`, `#semiconductor`, `#price increase`, `#supply chain`, `#AI demand`

---

<a id="item-20"></a>
## [AI 数据中心推动存储涨价，华为与长鑫关系趋紧](https://t.me/zaihuapd/42788) ⭐️ 7.0/10

中国最大 DRAM 制造商长鑫存储正在上调存储芯片价格，甚至对主要客户华为也持续涨价；2025 年 6 月，长鑫要求与华为关系密切的设备供应商新凯来的工程师离开其核心研发区域，此后未获准返回。 这一事件暴露出中国半导体供应链内部因 AI 数据中心需求激增、存储芯片供应紧张而出现的摩擦加剧，可能影响华为的产品成本与战略自主性。 长鑫存储已成为全球第四大 DRAM 制造商，受 AI 数据中心建设推动，其产品供应趋紧。新凯来（SiCarrier）是一家总部位于深圳、由深圳市政府支持并与华为密切合作的半导体设备公司。

telegram · zaihuapd · 7月27日 03:17

**背景**: DRAM（动态随机存取存储器）是服务器、手机和个人电脑的关键组件，AI 数据中心的建设大幅推升了需求。长鑫存储是中国唯一大规模生产现代 DDR5 和 LPDDR5 内存的厂商，因此在定价上拥有显著议价能力。华为因美国出口限制而高度依赖国产存储芯片，如今面临长鑫优先向利润更高的 AI 客户供货、导致采购成本上升的局面。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cxmt.com/en/">About cxmt - cxmt</a></li>
<li><a href="https://www.scmp.com/tech/big-tech/article/3361926/chinas-cxmt-shares-rise-472-star-market-debut-valuing-dram-maker-us489-billion">China’s CXMT soars 466% on debut as DRAM maker becomes most...</a></li>
<li><a href="https://en.wikipedia.org/wiki/SiCarrier">SiCarrier - Wikipedia</a></li>

</ul>
</details>

**标签**: `#memory chips`, `#Huawei`, `#ChangXin`, `#semiconductor supply chain`, `#AI data centers`

---

<a id="item-21"></a>
## [中方驳美制裁：蒸馏模型是行业标准](https://www.mofcom.gov.cn/syxwfb/art/2026/art_7f1622463a7c48ef9fad600ce0ef702f.html) ⭐️ 7.0/10

7 月 27 日，中国商务部拒绝美方拟以“蒸馏”美国前沿模型为由调查和制裁中国 AI 企业的计划，指出模型蒸馏是行业广泛使用的技术，美企同样在蒸馏中国模型。 此争端凸显美中在 AI 知识产权方面的紧张局势升级，并可能影响未来对模型蒸馏的监管。它同时强调了 AI 开发的互联性，开源模型正被全球使用。 商务部指出，近 200 家美国初创企业已呼吁政府不要限制访问中国开源模型。中方警告，对于实质性损害中方利益的行为，将采取必要措施维护中国企业合法权益。

telegram · zaihuapd · 7月27日 11:01

**背景**: 模型蒸馏（或知识蒸馏）是一种机器学习技术，通过让较小的“学生”模型从较大的“教师”模型学习，以提高效率并保持性能。它常用于在性能较低的硬件上部署 AI，但在跨国使用时，已成为中美 AI 竞争中的争议焦点。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Model_distillation">Model distillation</a></li>
<li><a href="https://www.tmtpost.com/7892989.html">Anthropic装糊涂，全球AI圈看笑了-钛媒体官方网站</a></li>
<li><a href="https://www.woshipm.com/ai/6327416.html">AGI bar火爆背后： 模 型 蒸 馏 技术如何重塑未来？ | 人人都 是 产品经理</a></li>

</ul>
</details>

**标签**: `#AI policy`, `#model distillation`, `#US-China trade`, `#AI regulation`, `#intellectual property`

---

<a id="item-22"></a>
## [月之暗面将开源 3T 参数模型 Kimi-K3](https://t.me/zaihuapd/42802) ⭐️ 7.0/10

月之暗面宣布计划于 2026 年 7 月在 Hugging Face 上开源 Kimi-K3，这是一个拥有 3 万亿参数、采用全新 Kimi Delta Attention 与 Attention Residuals 架构的模型。 开源一个 3T 参数且采用创新架构的模型，可能使前沿 AI 能力更加普及，特别是在长程编程和复杂推理任务方面。这为开源权重模型设立了新标杆，并挑战了当前的闭源范式。 该模型计划于 2026 年 7 月 27 日发布，将在 Hugging Face 上托管。其结合了 Kimi Delta Attention（一种基于 delta 规则的线性注意力机制）与 Attention Residuals（一种对层深度进行学习的选择性聚合方法），实现了细粒度的记忆更新和仓库级代码理解。

telegram · zaihuapd · 7月27日 15:15

**背景**: 标准 Transformer 模型使用残差连接，将每层输出以相同权重相加，导致隐藏状态增长和信号稀释。Attention Residuals 将其替换为对之前各层输出进行学习的 softmax 注意力，使每层能够选择性聚合早期表示。Kimi Delta Attention 是一种线性注意力机制，通过更细粒度的门控（通道级遗忘）实现高效记忆更新，扩展了 Gated DeltaNet 和 Mamba 架构的思想。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2603.15031">[2603.15031] Attention Residuals - arXiv.org GitHub - MoonshotAI/Attention-Residuals Attention Residuals - arXiv.org Attention Residuals wdlctc/open-attention-residuals - GitHub Attention Residuals - openlm.ai Attention Residuals Explained: Rethinking Transformer Depth</a></li>
<li><a href="https://www.emergentmind.com/topics/kimi-delta-attention">Kimi Delta Attention : Delta ‐Rule Linear Mechanism</a></li>
<li><a href="https://github.com/MoonshotAI/Attention-Residuals">GitHub - MoonshotAI/Attention-Residuals</a></li>

</ul>
</details>

**标签**: `#AI`, `#Open Source`, `#Large Language Models`, `#Moonshot AI`, `#Kimi-K3`

---

<a id="item-23"></a>
## [数据驱动的调查：清洗太阳能板通常没必要](https://incoherency.co.uk/blog/stories/should-you-wash-your-solar-panels.html) ⭐️ 6.0/10

一项基于数据的调查研究发现，在大多数情况下清洗太阳能板带来的性能提升微乎其微，其收益高度依赖于当地条件，如灰尘、鸟粪和面板朝向等。 对于太阳能板拥有者和可再生能源爱好者来说，这项研究挑战了常见的维护建议，表明除了沿海盐雾或严重污染等特定情况外，清洗所花费的时间和金钱往往得不偿失。 作者的实验显示，清洗后的立方样条拟合曲线有轻微下降趋势，可能是由于面板不匹配或水冷却效应。一位有 19 年系统使用经验的评论者表示，尽管从未清洗，面板性能并未下降。

hackernews · surprisetalk · 7月27日 13:04 · [社区讨论](https://news.ycombinator.com/item?id=49069132)

**背景**: 太阳能板将阳光转化为电能，灰尘、污垢或鸟粪遮挡光线会降低其效率。许多房主认为需要定期清洗以保持输出。然而，在许多气候条件下，自然降雨往往足以清洁面板，手动清洗的努力可能因能量增益微小而不值得。

**社区讨论**: 社区提供了多样化的观点：一位用户指出，卖房前清洗是为了改善外观而非性能；另一位分享了 19 年未清洗且性能未下降的数据；第三位指出水冷却可暂时提升输出，从而干扰测量结果；第四位报告在咸水环境中清洗船只面板后性能提升了 10%。此外，还有人对实验装置的接地安全提出了担忧。

**标签**: `#solar energy`, `#renewable energy`, `#maintenance`, `#data analysis`, `#practical engineering`

---

<a id="item-24"></a>
## [用 PyTorch 从头实现 Transformer 进行英-泰米尔语翻译](https://www.reddit.com/r/MachineLearning/comments/1v86qo9/built_trained_a_transformer_from_scratch_in_pure/) ⭐️ 6.0/10

一位开发者发布了一篇详细的博客文章和 GitHub 仓库，展示了如何使用纯 PyTorch 从头实现并训练 Transformer 架构，并在 Kaggle 上用双 NVIDIA T4 GPU 训练了一个英语到泰米尔语的平行数据集。 本教程提供了理解 Transformer 内部机制的详尽教育资源，包括数学推导和张量形状变换，这对学习自然语言处理和深度学习的学生及从业者非常有价值。 该实现遵循原始论文《Attention Is All You Need》，使用了 Hugging Face 上的数据集'gopi30/english-tamil'，并包含逐步代码和数学解释。博客文章和 GitHub 仓库均免费提供。

reddit · r/MachineLearning · /u/imrancoder · 7月27日 17:17

**背景**: Transformer 是一种于 2017 年提出的深度学习架构，依赖自注意力机制，彻底改变了机器翻译等自然语言处理任务。从头构建一个 Transformer 有助于学习者理解其数学基础，如多头注意力、位置编码和前馈网络，而这些在高层次库中往往被抽象化。

**标签**: `#transformer`, `#pytorch`, `#machine translation`, `#nlp`, `#tutorial`

---

<a id="item-25"></a>
## [开源端到端边缘机器学习平台，具备自动标注功能](https://www.reddit.com/r/MachineLearning/comments/1v7nudc/recent_project_i_worked_on_end_to_end_edge_ml/) ⭐️ 6.0/10

一位 Reddit 用户分享了 SensorForge，这是一个开源端到端边缘机器学习平台，包含针对时间序列传感器数据的自动标注工具和用于信号分析聊天机器人，支持部署到微控制器（MCU）上。 该平台直接解决了边缘 ML 中的两个主要痛点：手动标注时间序列传感器数据的困难，以及在资源受限的 MCU 上部署模型的复杂性。通过提供免费且开源的自动标注工具，它降低了开发者和研究人员从事 tinyML 应用的门槛。 该平台托管在 sensorforge.dev，内置了自动标注器，旨在简化时间序列数据的标注过程，并带有可直接分析信号数据的聊天机器人。该项目计划保持免费和开源以接受社区贡献，但创建者承认仍有改进空间。

reddit · r/MachineLearning · /u/No-Bug-4879 · 7月27日 02:38

**背景**: TinyML（微型机器学习）是机器学习的一个子领域，专注于在超低功耗、资源受限的设备（如微控制器和物联网传感器）上运行模型。将监督学习应用于传感器数据的主要挑战之一是需要大量准确标注的时间序列数据，而手动创建这些数据既繁琐又耗时。自动标注工具和端到端平台旨在自动化或简化这一过程，使 tinyML 更加易于使用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.datacamp.com/blog/what-is-tinyml-tiny-machine-learning">What is TinyML ? An Introduction to Tiny Machine Learning | DataCamp</a></li>
<li><a href="https://csv.ninja/">Timeseries labeling /annotation tool for sensor and device data</a></li>

</ul>
</details>

**标签**: `#edge ML`, `#tinyML`, `#auto-labeling`, `#sensor data`

---

<a id="item-26"></a>
## [美国学校减少 Chromebook 使用，回归纸笔教学](https://fortune.com/article/schools-abandoning-chromebooks-laptop-programs-as-screen-time-hurts-learning-test-scores-north-carolina-michigan-kansas-tech-education/) ⭐️ 6.0/10

美国堪萨斯、北卡罗来纳、密歇根等多州学校正在减少学生使用 Chromebook，重新采用纸笔教学，理由是屏幕时间损害学习效果以及设备更换成本高昂。 这一转变可能意味着长期推行的“一人一台电脑”教育计划出现逆转，或将重塑数百万学生的教育技术政策和屏幕时间指南。 在堪萨斯州一所中学，禁用手机后，学生转而用学校 Chromebook 看视频、玩游戏或骚扰同学，因此从去年 12 月起，学校仅在教师指定的活动中使用电脑。

telegram · zaihuapd · 7月26日 11:02

**背景**: 自疫情以来，美国许多学校推行“一人一台”计划，为每位学生提供 Chromebook 等设备用于学习。然而，越来越多的证据表明，过度的屏幕时间可能影响阅读理解、书写技能和考试成绩，同时设备采购和维护成本也加大学校预算压力。例如，北卡罗来纳州学校曾动用 4.48 亿美元联邦资金购买电脑和相关设备。

**标签**: `#education`, `#technology in schools`, `#screen time`, `#Chromebook`, `#policy`

---

<a id="item-27"></a>
## [长鑫科技上市首日暴涨 471%创纪录](https://www.stcn.com/article/detail/4042119.html) ⭐️ 6.0/10

国产存储芯片制造商长鑫科技（688825.SH）于 7 月 27 日在科创板上市，首日高开 471.59%，报 49.5 元/股，远高于 8.66 元/股的发行价。本次 IPO 募资约 666 亿元，超越中芯国际 2020 年纪录，成为科创板史上最大 IPO。 此次 IPO 表明投资者对中国国产存储芯片行业信心强劲，并为长鑫科技扩大 DRAM 产能、与三星和 SK 海力士等全球巨头竞争提供了巨额资金。该创纪录融资也凸显了科创板在支持中国关键科技领域融资方面日益重要的作用。 公司预计 2026 年上半年归母净利润 500 亿至 570 亿元，同比大幅扭亏。若超额配售选择权全额行使，募资总额可达约 666 亿元。

telegram · zaihuapd · 7月27日 01:29

**背景**: 长鑫科技（CXMT）是中国领先的 DRAM（动态随机存取存储器）制造商，专注于消费电子和工业领域的存储芯片。科创板于 2019 年启动，是中国为高科技和创新型企业设立的纳斯达克式板块。在此次 IPO 之前，中芯国际在 2020 年以 532.3 亿元募资额保持科创板最大 IPO 纪录。

**标签**: `#semiconductor`, `#IPO`, `#memory chip`, `#Chinese tech`, `#STAR Market`

---

<a id="item-28"></a>
## [三星或采用中国 DRAM 降成本提升在华份额](https://www.asiatime.co.kr/article/20260727500259) ⭐️ 6.0/10

据报道，三星正考虑在其中端 Galaxy A 系列手机中采用中国产低价移动 DRAM 芯片，以降低生产成本，并将目前仅约 0.6%的中国市场份额大幅提升。 这标志着三星供应链策略可能发生转变——在 AI 需求引发的全球“芯片通胀”背景下，三星可能依赖中国存储芯片，这将影响智能手机市场的定价和竞争格局。 报道援引业内人士称，三星希望借助价格竞争力，在苹果、小米、OPPO、vivo 等竞争对手因零部件涨价而削减 15%至 20%出货量之际扩大份额；三星 MX 部门在 2026 年第二季度可能面临高达 1 万亿韩元的亏损。

telegram · zaihuapd · 7月27日 14:45

**背景**: DRAM（动态随机存取存储器）是智能手机和电脑中使用的一种内存芯片。近期，由于 AI 数据中心需求旺盛及供应有限，内存芯片价格飙升，这一现象被称为“芯片通胀”。中国 DRAM 制造商（如长鑫存储 CXMT）发展迅速，能提供更低成本的替代产品。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.ersaelectronics.com/blog/memory-chip-price-increase">Memory Chip Price Increase: 2026 Market Trends, Samsung ...</a></li>
<li><a href="https://www.scmp.com/tech/big-tech/article/3361926/chinas-cxmt-shares-rise-472-star-market-debut-valuing-dram-maker-us489-billion">China ’s CXMT soars 466% on debut as DRAM maker becomes most...</a></li>

</ul>
</details>

**标签**: `#Samsung`, `#DRAM`, `#semiconductor`, `#business strategy`, `#China`

---