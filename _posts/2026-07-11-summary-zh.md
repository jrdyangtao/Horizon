---
layout: default
title: "Horizon Summary: 2026-07-11 (ZH)"
date: 2026-07-11
lang: zh
---

> 从 49 条内容中筛选出 16 条重要资讯。

---

1. [OpenAI 发布 GPT-5.6 系列：Luna、Terra、Sol，支持百万上下文窗口](#item-1) ⭐️ 9.0/10
2. [人形机器人远程完成全球首例活猪胆囊切除手术](#item-2) ⭐️ 9.0/10
3. [VultronRetriever 嵌入模型家族发布，MTEB 排行榜登顶](#item-3) ⭐️ 8.0/10
4. [U-Boot 引导程序曝 6 个漏洞，可绕过验证在启动时执行恶意代码](#item-4) ⭐️ 8.0/10
5. [苹果起诉 OpenAI 窃取商业机密加速硬件研发](#item-5) ⭐️ 8.0/10
6. [ClickHouse 通过 SO_REUSEPORT 和 Peering 将 PgBouncer 吞吐量提升 4 倍](#item-6) ⭐️ 7.0/10
7. [爱因斯坦相对论主导超重元素化学键](#item-7) ⭐️ 7.0/10
8. [AR 眼镜需持续云录制，引发隐私担忧](#item-8) ⭐️ 7.0/10
9. [SK 海力士 CEO 预警：2027 年内存供应空前短缺](#item-9) ⭐️ 7.0/10
10. [特朗普宣称苹果将与英特尔在美合作制造芯片](#item-10) ⭐️ 7.0/10
11. [上海计划 2027 年前实现高质量脑控，半侵入式脑机接口临床应用，侵入式研发突破](#item-11) ⭐️ 7.0/10
12. [余承东怒批问界 M8 隐私漏洞，要求即刻 OTA 修复](#item-12) ⭐️ 6.0/10
13. [Telegram Beta 版推出支持表格和数学公式的文章消息](#item-13) ⭐️ 6.0/10
14. [智谱创始人启动“摸高计划”，押注 AGI 与可解释性](#item-14) ⭐️ 6.0/10
15. [Claude Code 桌面版新增内置浏览器](#item-15) ⭐️ 6.0/10
16. [谷歌反对欧洲网站屏蔽，美国反盗版立法加速推进](#item-16) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [OpenAI 发布 GPT-5.6 系列：Luna、Terra、Sol，支持百万上下文窗口](https://simonwillison.net/2026/Jul/9/gpt-5-6/#atom-everything) ⭐️ 9.0/10

OpenAI 发布了三款新的 GPT-5.6 模型——Luna、Terra 和 Sol，具备 100 万 token 的上下文窗口、128k 最大输出 token 以及有竞争力的定价。新 API 功能包括可编程工具调用、多智能体支持和提示缓存断点。 这些模型以更低的成本提供了更优的智能体性能，有望普及高级 AI，并在长时间运行的职业任务中对 Anthropic 的 Claude Fable 5 形成挑战。 在评估长时间职业工作流程的 Agents' Last Exam 基准测试中，GPT-5.6 Sol 得分 53.6，以 13.1 分的优势超越 Claude Fable 5，而更小的模型以极低成本达到或超过 Fable 5。但在 SWE-Bench Pro 上，Fable 5 获得 80%，Sol 仅 64.6%，促使 OpenAI 审计该基准。

rss · Simon Willison · 7月9日 19:46

**背景**: 像 GPT-5.6 这样的大型语言模型（LLM）根据输入生成文本。上下文窗口决定了模型一次能考虑的文本量，100 万 token 约等于 75 万个单词。推理 token 是模型内部分步思考使用的 token，会提高单次任务的实际成本。像 Agents' Last Exam 这样的智能体基准测试衡量 AI 在复杂、多步骤、真实世界任务上的表现。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://agents-last-exam.org/">Agents' Last Exam</a></li>
<li><a href="https://medium.com/@don-lim/reasoning-tokens-and-techniques-used-in-system-2-llm-models-such-as-openai-o1-bacbf8fd9bec">Reasoning tokens and techniques used in System 2 LLMs... | Medium</a></li>

</ul>
</details>

**标签**: `#AI`, `#GPT`, `#OpenAI`, `#LLM`, `#release`

---

<a id="item-2"></a>
## [人形机器人远程完成全球首例活猪胆囊切除手术](https://arstechnica.com/ai/2026/07/humanoid-robots-controlled-by-surgeons-did-world-first-operation-on-live-pigs/) ⭐️ 9.0/10

外科医生远程操控宇树 G1 人形机器人，在活猪身上成功完成了两例腹腔镜胆囊切除手术，这是通用人形机器人首次应用于活体动物手术的案例，成果发表于《自然》期刊。 这一突破表明，通用人形机器人可通过低成本方案（远低于达芬奇等专用系统）用于手术，有望在农村、战场、太空等资源有限环境中推广机器人辅助手术，具有巨大的医疗普惠潜力。 该临床前试验包括两例活猪腹腔镜胆囊切除术，手术由研究人员远程操控配备灵巧手的宇树 G1 机器人完成；机器人小巧（高约 1.5 米，重 27 公斤）、成本低，但目前仅为远程操作，未实现自主手术。

telegram · zaihuapd · 7月11日 02:29

**背景**: 达芬奇手术机器人是目前的主流设备，售价超过 200 万美元。宇树科技（Unitree Robotics）是一家中国机器人公司，其 G1 人形机器人起售价仅 13,500 美元。本次研究首次将通用人形机器人（而非专用手术设备）用于活体动物手术，发表于《自然》杂志，标志着手术机器人领域一个重要的概念验证。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://today.ucsd.edu/story/surgeons-use-teleoperated-humanoid-robots-to-perform-live-surgery-a-world-first">Surgeons Use Teleoperated Humanoid Robots to Perform Live Surgery – a World First</a></li>
<li><a href="https://www.nature.com/articles/s41586-026-10796-x">In vivo feasibility study of humanoid robots in surgery | Nature</a></li>
<li><a href="https://www.unitree.com/g1/">Humanoid robot G1_Humanoid Robot Functions_Humanoid Robot Price | Unitree Robotics</a></li>

</ul>
</details>

**标签**: `#robotics`, `#surgery`, `#healthcare`, `#teleoperation`, `#humanoid robots`

---

<a id="item-3"></a>
## [VultronRetriever 嵌入模型家族发布，MTEB 排行榜登顶](https://www.reddit.com/r/MachineLearning/comments/1utmxq8/vultronretriever_family_of_models_released_on/) ⭐️ 8.0/10

VultronRetriever 嵌入模型家族已在 HuggingFace 上发布，各个尺寸型号均在 MTEB 排行榜上位居同类第一，索引体积较此前领先者缩小达 16 倍，吞吐量提升 12 倍，并可在 iPhone 等边缘设备上离线运行。 这些最先进的嵌入模型将顶尖的检索性能与显著的效率提升相结合，使得在资源受限设备上直接进行高质量语义搜索和检索成为可能，有望加速隐私敏感和低延迟应用的落地。 该家族包括 Prime-8B（全球第一）、Core-4.5B（性能超过 2 倍大小的模型）和 Flash-0.8B（性能超过 5 倍大小的模型，边缘设备上每分钟可索引 60 张图像）。训练数据无跨数据集重复和评估污染，且在私有 MTEB 评估中未出现过拟合。部署采用 Hydra 架构实现迟交互检索，内存占用仅为同类模型的一半。

reddit · r/MachineLearning · /u/madkimchi · 7月11日 15:22

**背景**: 大规模文本嵌入基准测试（MTEB）是评估文本嵌入模型在检索、聚类、分类等任务上性能的广泛使用的排行榜。迟交互检索是一种在最终相关度计算前独立处理查询和文档的技术，相比早交互或纯密集检索，能在精度与效率间取得更好平衡。嵌入模型将文本转换为向量表示，用于语义搜索等自然语言处理任务。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/spaces/mteb/leaderboard">MTEB Leaderboard - a Hugging Face Space by mteb</a></li>
<li><a href="https://weaviate.io/blog/late-interaction-overview">An Overview of Late Interaction Retrieval Models... | Weaviate</a></li>

</ul>
</details>

**标签**: `#embedding-models`, `#retrieval`, `#on-device-ml`, `#MTEB-leaderboard`, `#information-retrieval`

---

<a id="item-4"></a>
## [U-Boot 引导程序曝 6 个漏洞，可绕过验证在启动时执行恶意代码](https://www.bleepingcomputer.com/news/security/new-u-boot-flaws-could-enable-stealthy-firmware-attacks/) ⭐️ 8.0/10

安全公司 Binarly 披露了 U-Boot 扁平化镜像树（FIT）签名验证中的 6 个漏洞，其中 2 个可导致任意代码执行，4 个可造成设备崩溃。这些漏洞最早可追溯到 U-Boot 2013.07 版本，影响超过 50 个稳定版本。 这些漏洞允许攻击者在操作系统启动前的固件验证阶段执行恶意代码，完全绕过操作系统安全机制，可能导致持久性且难以检测的固件恶意软件感染。对于支持远程固件更新的基板管理控制器（BMC）等系统，攻击者无需物理接触即可利用这些漏洞，风险尤为突出。 这些漏洞位于 U-Boot 扁平化镜像树（FIT）签名验证代码中，该机制用于实现安全启动。Binarly 已提交补丁并被 U-Boot 维护者接受，但修复需要各硬件厂商集成到固件更新中，已停止支持的老旧设备可能永远无法获得修补。

telegram · zaihuapd · 7月11日 08:32

**背景**: U-Boot（Das U-Boot）是一种广泛使用的开源引导程序，用于初始化硬件并引导操作系统，常见于嵌入式 Linux 设备、物联网硬件和服务器平台。它支持基于扁平化镜像树（FIT）签名的安全启动机制，在启动前用密码学方法验证内核镜像和设备树二进制文件的完整性。基板管理控制器（BMC）是服务器主板上的专用微控制器，支持远程系统管理（包括网络固件更新），因此成为固件级别攻击的高价值目标。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Das_U-Boot">Das U-Boot - Wikipedia</a></li>
<li><a href="https://docs.u-boot-project.org/en/latest/usage/fit/index.html">Flat Image Tree ( FIT ) — Das U-Boot unknown version documentation</a></li>
<li><a href="https://www.supermicro.com/en/glossary/baseboard-management-controller">What is a Baseboard Management Controller? (BMC)</a></li>

</ul>
</details>

**标签**: `#security`, `#u-boot`, `#vulnerability`, `#firmware`, `#bootloader`

---

<a id="item-5"></a>
## [苹果起诉 OpenAI 窃取商业机密加速硬件研发](https://t.me/zaihuapd/42502) ⭐️ 8.0/10

苹果于 7 月 10 日在美国联邦法院起诉 OpenAI、两名前员工及 io Products，指控其系统性窃取商业机密以加速消费级硬件研发。 这起诉讼凸显了科技巨头之间在 AI 硬件人才和知识产权方面的激烈竞争，可能为 AI 行业商业秘密保护树立先例。 苹果声称前员工 Chang Liu 离职后仍访问内部网络下载硬件文件，OpenAI 硬件负责人 Tang Yew Tan 被指将供应商资料发送至个人邮箱，并要求求职者携带苹果零部件参加面试。

telegram · zaihuapd · 7月11日 16:29

**背景**: 商业秘密包括产品设计、制造工艺和供应链信息等能为公司带来竞争优势的内容。AI 硬件领域（如智能眼镜或芯片）是苹果和 OpenAI 都试图站稳脚跟的新战场。苹果长期以来一直通过诉讼积极保护其知识产权。

**标签**: `#Apple`, `#OpenAI`, `#lawsuit`, `#trade secrets`, `#AI hardware`

---

<a id="item-6"></a>
## [ClickHouse 通过 SO_REUSEPORT 和 Peering 将 PgBouncer 吞吐量提升 4 倍](https://clickhouse.com/blog/pgbouncer-clickhouse-managed-postgres) ⭐️ 7.0/10

ClickHouse 通过启用 SO_REUSEPORT 允许多个监听套接字绑定同一端口，并结合 PgBouncer 内置的 Peering 特性协调跨实例的取消请求，将 PgBouncer 吞吐量提升了 4 倍。 这一优化显著降低了托管 Postgres 服务中连接池的资源开销，无需增加硬件即可支持更高的客户端并发，为面临类似连接瓶颈的 PostgreSQL 用户提供了可参考的可扩展架构模式。 该实现依赖 SO_REUSEPORT（Linux 内核 3.9 起可用）进行负载分配，并要求每个 PgBouncer 实例在 Peering 组内具有唯一的 peer_id。局限性在于 Peering 仅用于转发取消请求，并不能解决所有扩展性挑战。

hackernews · saisrirampur · 7月11日 15:28 · [社区讨论](https://news.ycombinator.com/item?id=48872874)

**背景**: PgBouncer 是一款轻量级 PostgreSQL 连接池工具，可降低数据库连接开销。SO_REUSEPORT 是 Linux 套接字选项，允许多个进程绑定到同一端口，由内核分配传入连接。PgBouncer 的 Peering 特性使实例间能共享信息，以便在客户端连接断开时正确取消正在运行的查询。这些技术结合，帮助 ClickHouse 的托管 Postgres 服务高效处理更多连接。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://patchwork.ozlabs.org/project/netdev/patch/alpine.DEB.1.00.1004182321480.1822@pokey.mtv.corp.google.com/">[RFC] : soreuseport: Bind multiple sockets to same port - Patchwork</a></li>
<li><a href="https://postgrespro.com/docs/enterprise/15/pgbouncer">Postgres Pro Enterprise : Documentation: 15: pgbouncer</a></li>

</ul>
</details>

**社区讨论**: 社区反应包括建议使用 Odyssey 和 pgdog 等替代工具，有用户指出通过 Kubernetes 运行多个 PgBouncer 进程也能实现类似扩展。有人质疑 Peering 设置的简便性，以及使用 HAProxy 配合多个 PgBouncer 实例是否存在弊端，显示出对所选方法及其权衡的好奇。

**标签**: `#PgBouncer`, `#PostgreSQL`, `#connection-pooling`, `#performance`, `#database`

---

<a id="item-7"></a>
## [爱因斯坦相对论主导超重元素化学键](https://www.brown.edu/news/2026-07-09/chemical-bonds-relativity) ⭐️ 7.0/10

一项发表在《科学》杂志上的研究精确揭示了爱因斯坦的相对论如何改变超重元素中的σ键和π键，提供了对其行为的精细量子描述。 这深化了对重元素化学键的理解，有助于更精确地预测超重元素的性质，这些元素在实验中极难研究。 研究指出，在相对论情形下，电子自旋与轨道运动发生耦合（自旋-轨道耦合），这导致π键相对于σ键明显减弱，此前这种效应的分离尚未被量化。

hackernews · hhs · 7月10日 22:30 · [社区讨论](https://news.ycombinator.com/item?id=48866134)

**背景**: 在重元素中，内层电子以接近光速运动，必须进行相对论修正。已知效应包括金的黄色和汞的液态。相对论量子化学将相对论与量子力学结合以准确描述这些元素，但对σ键和π键的具体影响此前认识有限。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.brown.edu/news/2026-07-09/chemical-bonds-relativity">Einstein’s relativity rules chemical bonds in heavy elements, new research shows | Brown University</a></li>
<li><a href="https://en.wikipedia.org/wiki/Relativistic_quantum_chemistry">Relativistic quantum chemistry - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Superheavy_element">Superheavy element</a></li>

</ul>
</details>

**社区讨论**: 社区讨论表现出对深入见解的赞赏，一些人指出金和汞的相对论效应已是常识。少数人质疑研究的新颖性，而其他人则对爱因斯坦理论的持续验证表示钦佩。

**标签**: `#physics`, `#chemistry`, `#relativity`, `#quantum-mechanics`, `#chemical-bonding`

---

<a id="item-8"></a>
## [AR 眼镜需持续云录制，引发隐私担忧](https://simonwillison.net/2026/Jul/10/nilay-patel/#atom-everything) ⭐️ 7.0/10

Nilay Patel 指出，要制造实用的增强现实眼镜，必须在用户眼前安装摄像头，持续录制所有画面并发送至云端处理，这本质上侵犯了隐私，并建议我们可能因社会代价过高而应停止开发这类产品。 这一评论揭示了根本性的伦理困境：推进增强现实技术与保护用户隐私之间的权衡，可能影响科技行业的产品开发和监管决策。 Patel 指出，目前没有芯片既能装进眼镜腿、又足够强大且省电来实时处理 AR 任务，因此只能在云录制或像 Apple Vision Pro 这样更笨重的设备间选择。

rss · Simon Willison · 7月10日 17:05

**背景**: 增强现实（AR）眼镜旨在将数字信息叠加到用户对现实世界的视图中，这需要摄像头捕捉环境并进行强大的处理。受尺寸和功耗限制，目前的原型设备通常依赖云计算，但由于持续录像和数据传输而引发隐私担忧。此前的类似尝试如 Google Glass 就因隐私问题而遭遇公众强烈反对。

**标签**: `#augmented reality`, `#privacy`, `#surveillance`, `#technology ethics`, `#cloud computing`

---

<a id="item-9"></a>
## [SK 海力士 CEO 预警：2027 年内存供应空前短缺](https://www.reuters.com/world/asia-pacific/sk-hynix-ceo-sees-worst-ever-memory-supply-shortage-2027-says-demand-outstrip-2026-07-10/) ⭐️ 7.0/10

SK 海力士 CEO 郭鲁正警告，尽管积极扩产，但受 AI 需求推动，2027 年全球内存行业将面临史上最严重的供应短缺。 此短缺可能严重影响 AI/ML 硬件供应和数据中心扩展，危及依赖高性能内存的企业。 采访当天 SK 海力士在纳斯达克上市，股价收涨 13.3%至 168.85 美元。其 2025 年营业利润创新高，达 47 万亿韩元，并正评估在美国、日本和东南亚建设海外晶圆厂。

telegram · zaihuapd · 7月11日 00:45

**背景**: SK 海力士是全球第二大内存芯片制造商，生产用于服务器、AI 加速器和消费设备的 DRAM 和 NAND 闪存。大模型兴起大幅推升了对高带宽内存的需求，SK 海力士在该领域处于领先地位。严重短缺可能拖慢 AI 发展并推高硬件成本。

**标签**: `#memory`, `#semiconductor`, `#supply chain`, `#AI hardware`, `#industry news`

---

<a id="item-10"></a>
## [特朗普宣称苹果将与英特尔在美合作制造芯片](https://t.me/zaihuapd/42491) ⭐️ 7.0/10

特朗普发文称苹果已同意与英特尔在美国合作制造新芯片，作为推动半导体回流的举措。 这一言论暗示苹果供应链可能发生重大转变，减少对台积电等亚洲代工厂的依赖，并配合美国半导体回流战略，但该消息尚未得到苹果或英特尔的官方证实。 苹果自研 M 系列芯片但依赖台积电代工；英特尔代工业务仍在发展，尚未获得苹果等大型外部客户。该声明仅基于政治人物的言论，并非企业官方公告。

telegram · zaihuapd · 7月11日 05:54

**背景**: 苹果自 2020 年起从英特尔 CPU 转向自研 ARM 架构 M 系列芯片，但制造仍外包给台积电。英特尔于 2021 年推出代工服务，向外部客户提供先进制造，旨在重振半导体市场地位。美国政府通过《芯片法案》推动芯片本土生产。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Apple_silicon">Apple silicon - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Intel_Foundry_Services">Intel Foundry Services</a></li>

</ul>
</details>

**标签**: `#Apple`, `#Intel`, `#semiconductor manufacturing`, `#Trump`, `#supply chain`

---

<a id="item-11"></a>
## [上海计划 2027 年前实现高质量脑控，半侵入式脑机接口临床应用，侵入式研发突破](https://t.me/zaihuapd/42501) ⭐️ 7.0/10

上海市发布了《上海市脑机接口未来产业培育行动方案（2025-2030 年）》，计划到 2027 年实现半侵入式脑机接口产品的临床应用，并在侵入式脑机接口研发上取得突破，以帮助患者恢复语言和运动功能。 该方案表明了政府对脑机接口技术的大力扶持，有望加速产品研发和临床试验，推动人工智能在医疗健康中的深度融合，为神经疾病患者带来新的治疗选择。 方案明确提出推动 5 款以上侵入式或半侵入式脑机接口产品完成医疗器械型式检验和临床试验，实现失语或瘫痪患者部分语言和运动功能恢复。

telegram · zaihuapd · 7月11日 15:49

**背景**: 脑机接口（BCI）实现大脑与外部设备的直接通信。非侵入式 BCI 使用头皮外电极（如脑电图）；半侵入式将电极置于颅骨内硬脑膜外（如皮层电图）；侵入式则直接将电极植入脑组织。这些技术主要面向瘫痪、失语等神经功能障碍患者，旨在恢复其运动或交流能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Brain–computer_interface">Brain–computer interface - Wikipedia</a></li>
<li><a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC12671281/">Invasive Brain-Computer Interfaces: A Critical Assessment of Current Developments and Future Prospects - PMC</a></li>

</ul>
</details>

**标签**: `#brain-computer interface`, `#government policy`, `#artificial intelligence`, `#medical technology`, `#Shanghai`

---

<a id="item-12"></a>
## [余承东怒批问界 M8 隐私漏洞，要求即刻 OTA 修复](https://user.guancha.cn/main/content?id=1686339) ⭐️ 6.0/10

问界 M8 被曝隐私漏洞：车主关闭授权账号位置权限后，授权账号仍可通过泊车代驾功能查看车辆定位。余承东严厉批评该漏洞“太愚蠢”，并命令团队放弃原定 9 月的修复排期，立即通过 OTA 推送更新。 该事件凸显了智能网联汽车日益增长的隐私和安全风险，软件漏洞可能导致敏感位置数据泄露。随着智能汽车与个人设备深度融合，汽车制造商面临优先保障数据安全的巨大压力。 该漏洞涉及华为 ADS 3.0 系统中的泊车代驾（VPD）功能，在撤销权限后仍会共享位置。据报道，余承东威胁要“淘汰”提议 9 月修复的人员，并要求团队“不吃不喝不睡”立即通过 OTA 推送修复。

telegram · zaihuapd · 7月11日 02:05

**背景**: 问界 M8 是华为鸿蒙智行联盟旗下的一款电动 SUV。华为为车辆提供包括 ADS 自动驾驶系统和鸿蒙座舱在内的智能解决方案。泊车代驾功能允许车辆远程自主泊车或召唤。OTA（空中下载）更新使车辆能够远程接收软件修复，无需到店。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/鸿蒙智行">鸿蒙智行</a></li>
<li><a href="https://www.chinaz.com/2024/1222/1659784.shtml">鸿蒙智行 泊 车 代 驾 VPD正式开启全量推送！升级自动 泊 车 /接 驾 等多项 功 能</a></li>

</ul>
</details>

**标签**: `#privacy`, `#automotive`, `#security`, `#IoT`, `#Huawei`

---

<a id="item-13"></a>
## [Telegram Beta 版推出支持表格和数学公式的文章消息](https://t.me/zaihuapd/42495) ⭐️ 6.0/10

Telegram 已向 Premium 用户推出测试版文章消息功能，支持表格、数学公式、代码块和折叠引用等富文本格式。该功能现已在 Android 和 iOS 测试版 12.9 及桌面端测试版 6.9.4 中可用。 这一更新增强了 Telegram 作为内容丰富的即时通讯平台的能力，让创作者能够直接在聊天中分享结构化的格式化内容，从而可能使其对教育、技术和专业社区更具吸引力。 用户可通过附件菜单中的‘文章’选项或发送按钮上方的箭头图标进入编辑器。目前 iOS 测试版不再接受新测试者，限制了新用户的访问。

telegram · zaihuapd · 7月11日 12:29

**背景**: Telegram 是一款以注重隐私和功能丰富著称的云端即时通讯应用。Premium 订阅用户每月付费以获得更大文件上传、更快下载速度等专属功能。测试版允许用户在正式发布前提前体验新功能。

**标签**: `#Telegram`, `#feature update`, `#messaging`, `#beta`, `#rich text`

---

<a id="item-14"></a>
## [智谱创始人启动“摸高计划”，押注 AGI 与可解释性](https://mp.weixin.qq.com/s/3CQSkf_kBnXiCDgS4L-Cgg) ⭐️ 6.0/10

智谱 AI 创始人唐杰发布内部信，启动“摸高计划”，将 AGI 路径分为长程任务、自治智能体系统、完全自我训练和极致安全治理四座高峰，并计划投入百亿级资源攻克机械可解释性。 这标志着中国 AI 公司全力投入 AGI 并高度重视安全与可解释性，挑战重短期商业化的行业风向；其开源模型 GLM-5.2 接近前沿水平，可能降低先进 AI 使用门槛。 GLM-5.2 模型被认为接近海外顶尖模型性能，且开源特性受到技术社群欢迎。计划特别聚焦机械可解释性，旨在使黑盒模型透明化，承诺投入巨大资源。

telegram · zaihuapd · 7月11日 13:59

**背景**: 智谱 AI（国际品牌 Z.ai）是中国领先的人工智能公司，属于“AI 四小龙”之一，以其开源的 GLM 系列大语言模型闻名，自 2025 年 7 月起采用 MIT 许可证。机械可解释性是一个旨在理解神经网络内部运作机制的领域，以期逆向工程其算法并保障安全。该公司于 2025 年 1 月被美国列入实体清单，为其 AGI 冲刺增添了地缘政治背景。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://wallstreetcn.com/articles/3776707">智 谱创始人唐杰发布内部信：将开启 Touch High...</a></li>
<li><a href="https://en.wikipedia.org/wiki/GLM_5.2">GLM 5.2</a></li>
<li><a href="https://juejin.cn/post/7577438119559266355">Anthropic 机 械 可 解 释 性 学习路线Anthropic...</a></li>

</ul>
</details>

**标签**: `#AGI`, `#AI Safety`, `#Model Interpretability`, `#Open Source`, `#China AI`

---

<a id="item-15"></a>
## [Claude Code 桌面版新增内置浏览器](https://x.com/ClaudeDevs/status/2075635283211772279) ⭐️ 6.0/10

Claude Code 桌面版现已加入沙盒化的内置浏览器，用户可直接在应用内打开并交互浏览网页、文档和设计稿。 此集成通过允许开发者在不离开编码环境的情况下进行 AI 辅助的网页交互，简化了开发工作流程，提高了测试本地服务器或查阅网页资源的效率。 该浏览器在沙盒环境中运行以确保安全，用户还可以配置是否保留浏览会话。

telegram · zaihuapd · 7月11日 14:34

**背景**: Claude Code 是 Anthropic 推出的一款 AI 编程助手，能够理解代码库、编辑文件和运行命令。桌面版为该工具提供了图形界面，而新的内置浏览器省去了为预览网页输出或查看文档而切换到外部浏览器的需要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_Code">Claude Code</a></li>
<li><a href="https://claude.com/product/claude-code">Claude Code by Anthropic | AI Coding Agent, Terminal, IDE</a></li>

</ul>
</details>

**标签**: `#Claude Code`, `#AI coding assistant`, `#built-in browser`, `#desktop app`, `#feature update`

---

<a id="item-16"></a>
## [谷歌反对欧洲网站屏蔽，美国反盗版立法加速推进](https://torrentfreak.com/google-opposes-site-blocking-in-europe-as-u-s-piracy-blocking-plans-gain-momentum/) ⭐️ 6.0/10

谷歌向欧盟委员会提交文件，反对扩大网站屏蔽，称其无效且会误伤合法服务；与此同时，美国议员正推进类似的网站屏蔽立法。 这凸显了在版权执法与互联网开放性之间寻求平衡的全球争议。谷歌立场上的分歧反映了企业利益与政府监管之间的矛盾，可能影响未来的互联网架构。 谷歌特别反对屏蔽 DNS 解析器、IP 地址和 VPN，指出意大利反盗版系统曾误封 Google Drive 和一个托管 4200 万域名的 Cloudflare IP，造成附带损害。

telegram · zaihuapd · 7月11日 15:10

**背景**: 网站屏蔽要求网络服务商拒绝访问侵权网站，常扩展至 DNS 和 IP 层。在欧洲，这类措施与网络中立原则冲突；在美国，类似 SOPA 的提案曾引发争议。意大利的“反盗版盾”系统作为自动化反盗版平台，因误封合法服务而受批评，印证了谷歌强调的风险。

**标签**: `#tech policy`, `#site blocking`, `#copyright`, `#internet freedom`, `#censorship`

---