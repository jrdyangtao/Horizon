---
layout: default
title: "Horizon Summary: 2026-07-11 (EN)"
date: 2026-07-11
lang: en
---

> From 49 items, 16 important content pieces were selected

---

1. [OpenAI Releases GPT-5.6 Family: Luna, Terra, Sol with 1M Context Window](#item-1) ⭐️ 9.0/10
2. [Humanoid Robot Performs First Remote Gallbladder Surgery on Live Pigs](#item-2) ⭐️ 9.0/10
3. [VultronRetriever Family of Embedding Models Released, Tops MTEB Leaderboard](#item-3) ⭐️ 8.0/10
4. [Six U-Boot Vulnerabilities Bypass Secure Boot, Enable Malicious Code Execution](#item-4) ⭐️ 8.0/10
5. [Apple Sues OpenAI Over Alleged Trade Secret Theft for Hardware](#item-5) ⭐️ 8.0/10
6. [ClickHouse Scaled PgBouncer to 4x Throughput Using SO_REUSEPORT and Peering](#item-6) ⭐️ 7.0/10
7. [Einstein's Relativity Governs Chemical Bonds in Superheavy Elements](#item-7) ⭐️ 7.0/10
8. [AR Glasses Require Continuous Cloud Recording, Raising Privacy Concerns](#item-8) ⭐️ 7.0/10
9. [SK Hynix CEO Warns of Worst Memory Shortage by 2027](#item-9) ⭐️ 7.0/10
10. [Trump Claims Apple and Intel to Jointly Manufacture Chips in the U.S.](#item-10) ⭐️ 7.0/10
11. [Shanghai Aims for High-Quality Brain Control by 2027, Semi-Invasive BCI Clinical Use, Invasive Breakthroughs](#item-11) ⭐️ 7.0/10
12. [Yu Chengdong Slams AITO M8 Location Tracking Bug, Orders Emergency OTA Fix](#item-12) ⭐️ 6.0/10
13. [Telegram Beta Introduces Article Messages with Table and Math Support](#item-13) ⭐️ 6.0/10
14. [Zhipu AI Founder Tang Jie Launches 'Touch High' Plan for AGI](#item-14) ⭐️ 6.0/10
15. [Claude Code Desktop Adds Built-in Browser](#item-15) ⭐️ 6.0/10
16. [Google Opposes EU Site Blocking, US Considers Similar Anti-Piracy Laws](#item-16) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [OpenAI Releases GPT-5.6 Family: Luna, Terra, Sol with 1M Context Window](https://simonwillison.net/2026/Jul/9/gpt-5-6/#atom-everything) ⭐️ 9.0/10

OpenAI has released three new GPT-5.6 models—Luna, Terra, and Sol—featuring a 1 million token context window, 128k maximum output tokens, and competitive pricing. New API capabilities include programmatic tool calling, multi-agent support, and prompt cache breakpoints. These models deliver superior agentic performance at lower cost, potentially democratizing advanced AI and challenging Anthropic's Claude Fable 5 in long-running professional tasks. On the Agents' Last Exam benchmark for long-horizon professional workflows, GPT-5.6 Sol scored 53.6, topping Claude Fable 5 by 13.1 points, while smaller models matched or exceeded Fable 5 at a fraction of the cost. However, on SWE-Bench Pro, Fable 5 achieved 80% versus Sol's 64.6%, prompting OpenAI to audit the benchmark.

rss · Simon Willison · Jul 9, 19:46

**Background**: Large language models (LLMs) like GPT-5.6 generate text based on input. The context window determines how much text the model can consider at once; 1 million tokens equates to roughly 750,000 words. Reasoning tokens are internal tokens used for step-by-step thinking, which increase effective cost per task. Agentic benchmarks like Agents' Last Exam measure AI performance on complex, multi-step, real-world tasks.

<details><summary>References</summary>
<ul>
<li><a href="https://agents-last-exam.org/">Agents' Last Exam</a></li>
<li><a href="https://medium.com/@don-lim/reasoning-tokens-and-techniques-used-in-system-2-llm-models-such-as-openai-o1-bacbf8fd9bec">Reasoning tokens and techniques used in System 2 LLMs... | Medium</a></li>

</ul>
</details>

**Tags**: `#AI`, `#GPT`, `#OpenAI`, `#LLM`, `#release`

---

<a id="item-2"></a>
## [Humanoid Robot Performs First Remote Gallbladder Surgery on Live Pigs](https://arstechnica.com/ai/2026/07/humanoid-robots-controlled-by-surgeons-did-world-first-operation-on-live-pigs/) ⭐️ 9.0/10

Surgeons remotely controlled Unitree G1 humanoid robots to perform the first-ever laparoscopic gallbladder removal surgeries on live pigs, demonstrating a low-cost alternative to traditional surgical robots. This breakthrough shows that general-purpose humanoid robots can be adapted for surgery at a fraction of the cost of dedicated systems like da Vinci, potentially democratizing access to robotic surgery in resource-limited environments. The preclinical trial involved two successful laparoscopic gallbladder surgeries on pigs, using a teleoperated Unitree G1 robot equipped with dexterous hands; the robot's compact size and low cost are key, but autonomous capabilities are not yet realized.

telegram · zaihuapd · Jul 11, 02:29

**Background**: The da Vinci Surgical System, costing over $2 million, is the dominant surgical robot. Unitree Robotics, a Chinese firm, produces the G1 humanoid robot with a starting price of $13,500, far cheaper. This study marks the first time a general-purpose humanoid robot, rather than a purpose-built surgical machine, has been used for live animal surgery, as reported in Nature.

<details><summary>References</summary>
<ul>
<li><a href="https://today.ucsd.edu/story/surgeons-use-teleoperated-humanoid-robots-to-perform-live-surgery-a-world-first">Surgeons Use Teleoperated Humanoid Robots to Perform Live Surgery – a World First</a></li>
<li><a href="https://www.nature.com/articles/s41586-026-10796-x">In vivo feasibility study of humanoid robots in surgery | Nature</a></li>
<li><a href="https://www.unitree.com/g1/">Humanoid robot G1_Humanoid Robot Functions_Humanoid Robot Price | Unitree Robotics</a></li>

</ul>
</details>

**Tags**: `#robotics`, `#surgery`, `#healthcare`, `#teleoperation`, `#humanoid robots`

---

<a id="item-3"></a>
## [VultronRetriever Family of Embedding Models Released, Tops MTEB Leaderboard](https://www.reddit.com/r/MachineLearning/comments/1utmxq8/vultronretriever_family_of_models_released_on/) ⭐️ 8.0/10

The VultronRetriever family of embedding models was released on HuggingFace. Each model ranks #1 in its class on the MTEB leaderboard, with up to 16x smaller index size and 12x higher throughput, and supports on-device operation on iPhone. These state-of-the-art embedding models combine top retrieval performance with dramatic efficiency gains, enabling high-quality semantic search and retrieval directly on resource-constrained devices, which could accelerate adoption in privacy-sensitive and latency-critical applications. The family includes Prime-8B (global #1), Core-4.5B (outperforms models twice its size), and Flash-0.8B (outperforms 5x larger models and indexes 60 images/min on edge). Training used 0% cross-dataset duplication and 0% eval contamination, with no overfitting on private MTEB evals. Deployment leverages the Hydra Architecture for late interaction retrieval with half the memory.

reddit · r/MachineLearning · /u/madkimchi · Jul 11, 15:22

**Background**: The Massive Text Embedding Benchmark (MTEB) is a widely used leaderboard for evaluating text embedding models across tasks like retrieval, clustering, and classification. Late interaction retrieval is a technique where queries and documents are processed independently until the final relevance computation, balancing precision and efficiency compared to early interaction or pure dense retrieval. Embedding models convert text into vector representations for semantic search and other NLP tasks.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/spaces/mteb/leaderboard">MTEB Leaderboard - a Hugging Face Space by mteb</a></li>
<li><a href="https://weaviate.io/blog/late-interaction-overview">An Overview of Late Interaction Retrieval Models... | Weaviate</a></li>

</ul>
</details>

**Tags**: `#embedding-models`, `#retrieval`, `#on-device-ml`, `#MTEB-leaderboard`, `#information-retrieval`

---

<a id="item-4"></a>
## [Six U-Boot Vulnerabilities Bypass Secure Boot, Enable Malicious Code Execution](https://www.bleepingcomputer.com/news/security/new-u-boot-flaws-could-enable-stealthy-firmware-attacks/) ⭐️ 8.0/10

Security firm Binarly disclosed six vulnerabilities in U-Boot's Flattened Image Tree (FIT) signature verification, including two arbitrary code execution flaws and four denial-of-service bugs. These flaws date back to U-Boot 2013.07 and affect over 50 stable releases. These vulnerabilities enable attackers to execute malicious code during the earliest stages of boot, completely bypassing operating system security, potentially leading to persistent, undetectable firmware malware. Systems with remote firmware update capabilities, such as Baseboard Management Controllers (BMCs), are especially at risk because they can be exploited without physical access. The vulnerabilities reside in U-Boot's Flattened Image Tree (FIT) signature verification, a mechanism used for secure boot. While Binarly has submitted patches that were accepted by U-Boot maintainers, hardware vendors must integrate them into firmware updates—leaving end-of-life devices potentially permanently vulnerable.

telegram · zaihuapd · Jul 11, 08:32

**Background**: U-Boot (Das U-Boot) is a popular open-source bootloader used in many embedded Linux devices, including IoT hardware and server platforms, to initialize hardware and load the operating system. It supports a secure boot mechanism using Flattened Image Tree (FIT) signatures, which cryptographically verify the integrity of kernel images and device tree blobs before booting. A Baseboard Management Controller (BMC) is a specialized microcontroller on server motherboards that enables remote system management, including firmware updates over a network, making it a high-value target for firmware-level attacks.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Das_U-Boot">Das U-Boot - Wikipedia</a></li>
<li><a href="https://docs.u-boot-project.org/en/latest/usage/fit/index.html">Flat Image Tree ( FIT ) — Das U-Boot unknown version documentation</a></li>
<li><a href="https://www.supermicro.com/en/glossary/baseboard-management-controller">What is a Baseboard Management Controller? (BMC)</a></li>

</ul>
</details>

**Tags**: `#security`, `#u-boot`, `#vulnerability`, `#firmware`, `#bootloader`

---

<a id="item-5"></a>
## [Apple Sues OpenAI Over Alleged Trade Secret Theft for Hardware](https://t.me/zaihuapd/42502) ⭐️ 8.0/10

Apple filed a lawsuit on July 10 in U.S. federal court against OpenAI, two former employees, and io Products, alleging systematic theft of trade secrets to advance OpenAI's consumer hardware development. This lawsuit highlights the intensifying competition between tech giants for AI hardware talent and intellectual property, potentially setting precedents for how trade secrets are protected in the AI industry. Apple claims former employee Chang Liu accessed internal networks post-departure to download hardware files, while OpenAI's hardware lead Tang Yew Tan allegedly sent supplier information to a personal email and asked job candidates to bring Apple components to interviews.

telegram · zaihuapd · Jul 11, 16:29

**Background**: Trade secrets include product designs, manufacturing processes, and supply chain information that give companies competitive advantages. The AI hardware sector, including devices like smart glasses or chips, is a new frontier where both Apple and OpenAI are seeking to establish footholds. Apple has a long history of aggressively protecting its intellectual property through litigation.

**Tags**: `#Apple`, `#OpenAI`, `#lawsuit`, `#trade secrets`, `#AI hardware`

---

<a id="item-6"></a>
## [ClickHouse Scaled PgBouncer to 4x Throughput Using SO_REUSEPORT and Peering](https://clickhouse.com/blog/pgbouncer-clickhouse-managed-postgres) ⭐️ 7.0/10

ClickHouse achieved a 4x increase in PgBouncer throughput by enabling SO_REUSEPORT to allow multiple listener sockets on the same port, combined with PgBouncer's built-in peering feature for coordinating cancel requests across instances. This optimization significantly reduces the resource overhead of connection pooling for managed Postgres services, enabling higher client concurrency without additional hardware. It showcases a scalable architecture pattern that can be adopted by other PostgreSQL users facing similar connection bottlenecks. The implementation relies on SO_REUSEPORT (available since Linux kernel 3.9) for load distribution and requires each PgBouncer instance to have a unique peer_id within the peering group. One limitation is that peering only assists with cancel request forwarding and does not solve all scaling challenges.

hackernews · saisrirampur · Jul 11, 15:28 · [Discussion](https://news.ycombinator.com/item?id=48872874)

**Background**: PgBouncer is a lightweight connection pooler for PostgreSQL that reduces the overhead of establishing database connections. SO_REUSEPORT is a Linux socket option allowing multiple processes to bind to the same port, with the kernel distributing incoming connections. PgBouncer's peering feature lets instances share information to properly cancel running queries when client connections drop. These techniques together help ClickHouse's managed Postgres service handle more connections efficiently.

<details><summary>References</summary>
<ul>
<li><a href="https://patchwork.ozlabs.org/project/netdev/patch/alpine.DEB.1.00.1004182321480.1822@pokey.mtv.corp.google.com/">[RFC] : soreuseport: Bind multiple sockets to same port - Patchwork</a></li>
<li><a href="https://postgrespro.com/docs/enterprise/15/pgbouncer">Postgres Pro Enterprise : Documentation: 15: pgbouncer</a></li>

</ul>
</details>

**Discussion**: Community reactions included suggestions for alternative tools like Odyssey and pgdog, and a user noted that running multiple PgBouncer processes via Kubernetes achieves similar scaling. Some questioned the simplicity of setting up peering and whether using HAProxy with multiple PgBouncer instances has drawbacks, indicating curiosity about the chosen approach and its trade-offs.

**Tags**: `#PgBouncer`, `#PostgreSQL`, `#connection-pooling`, `#performance`, `#database`

---

<a id="item-7"></a>
## [Einstein's Relativity Governs Chemical Bonds in Superheavy Elements](https://www.brown.edu/news/2026-07-09/chemical-bonds-relativity) ⭐️ 7.0/10

A study published in Science reveals precisely how Einstein's relativity alters sigma and pi bonds in superheavy elements, providing a refined quantum characterization of their behavior. This deepens the understanding of chemical bonding in heavy elements, enabling more accurate predictions of superheavy element properties, which are notoriously difficult to study experimentally. The research highlights that in the relativistic regime, electron spin and orbital motion couple (spin-orbit coupling), which distinctly weakens pi bonds relative to sigma bonds, a separation not previously quantified.

hackernews · hhs · Jul 10, 22:30 · [Discussion](https://news.ycombinator.com/item?id=48866134)

**Background**: In heavy elements, inner electrons move at speeds close to light, requiring relativistic corrections. Known effects include gold's yellow color and mercury's liquidity. Relativistic quantum chemistry combines relativity with quantum mechanics to accurately describe such elements, but the specific impact on sigma and pi bonds was less understood.

<details><summary>References</summary>
<ul>
<li><a href="https://www.brown.edu/news/2026-07-09/chemical-bonds-relativity">Einstein’s relativity rules chemical bonds in heavy elements, new research shows | Brown University</a></li>
<li><a href="https://en.wikipedia.org/wiki/Relativistic_quantum_chemistry">Relativistic quantum chemistry - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Superheavy_element">Superheavy element</a></li>

</ul>
</details>

**Discussion**: The discussion showed appreciation for the deeper insight, with some noting that relativistic effects in gold and mercury are already well-known. A few questioned the novelty, while others admired Einstein's enduring validation.

**Tags**: `#physics`, `#chemistry`, `#relativity`, `#quantum-mechanics`, `#chemical-bonding`

---

<a id="item-8"></a>
## [AR Glasses Require Continuous Cloud Recording, Raising Privacy Concerns](https://simonwillison.net/2026/Jul/10/nilay-patel/#atom-everything) ⭐️ 7.0/10

Nilay Patel argues that building practical augmented reality glasses requires a camera next to your eyes that continuously records everything you see and sends it to the cloud for processing, inherently invading privacy, and suggests we may need to stop developing such products due to high societal costs. This commentary highlights a fundamental ethical dilemma: the trade-off between advancing augmented reality technology and protecting user privacy, potentially influencing product development and regulatory decisions in the tech industry. Patel notes that no chip currently fits in the stem of glasses that is both powerful and energy-efficient enough for real-time AR processing, forcing a choice between cloud-connected recording or bulkier devices like Apple Vision Pro.

rss · Simon Willison · Jul 10, 17:05

**Background**: Augmented reality (AR) glasses aim to superimpose digital information onto the user's view of the real world. To do this, they need cameras to capture the environment and powerful processing to interpret it. Due to size and power constraints, current prototypes often rely on cloud computing, raising privacy concerns because of continuous recording and data transmission. Previous attempts like Google Glass faced significant public backlash over privacy.

**Tags**: `#augmented reality`, `#privacy`, `#surveillance`, `#technology ethics`, `#cloud computing`

---

<a id="item-9"></a>
## [SK Hynix CEO Warns of Worst Memory Shortage by 2027](https://www.reuters.com/world/asia-pacific/sk-hynix-ceo-sees-worst-ever-memory-supply-shortage-2027-says-demand-outstrip-2026-07-10/) ⭐️ 7.0/10

SK Hynix CEO Kwak Noh-Jung warned that the global memory industry will face its worst-ever supply shortage by 2027, as AI-driven demand outpaces expansion efforts. This shortage could significantly impact AI/ML hardware availability and data center expansion, affecting companies reliant on high-performance memory. On the day of the interview, SK Hynix debuted on Nasdaq with shares closing up 13.3% at $168.85. The company posted a record operating profit of 47 trillion won in 2025 and expects further growth, while evaluating overseas fab sites in the US, Japan, and Southeast Asia.

telegram · zaihuapd · Jul 11, 00:45

**Background**: SK Hynix is the world's second-largest memory chip manufacturer, producing DRAM and NAND flash used in servers, AI accelerators, and consumer devices. The rise of large AI models has dramatically increased demand for high-bandwidth memory (HBM), which SK Hynix leads. A severe shortage could slow AI development and increase hardware costs.

**Tags**: `#memory`, `#semiconductor`, `#supply chain`, `#AI hardware`, `#industry news`

---

<a id="item-10"></a>
## [Trump Claims Apple and Intel to Jointly Manufacture Chips in the U.S.](https://t.me/zaihuapd/42491) ⭐️ 7.0/10

Former President Trump announced that Apple has agreed to collaborate with Intel on manufacturing new chips in the United States, claiming it is a step toward semiconductor reshoring. This claim suggests a potential strategic shift in Apple's supply chain, possibly reducing reliance on Asian foundries like TSMC and aligning with U.S. semiconductor reshoring efforts, though it lacks official confirmation from Apple or Intel. Apple has been designing its own M-series chips but relies on TSMC for manufacturing; Intel's foundry business is still ramping up and has yet to secure major external clients like Apple. The announcement is based solely on a political statement, not a corporate press release.

telegram · zaihuapd · Jul 11, 05:54

**Background**: Apple transitioned from Intel CPUs to its own ARM-based M-series chips starting in 2020, but manufacturing is outsourced to TSMC. Intel launched Intel Foundry Services in 2021 to offer advanced manufacturing to external customers, as part of a broader effort to regain market share in the semiconductor industry. The U.S. government has been promoting domestic chip production through the CHIPS Act.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Apple_silicon">Apple silicon - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Intel_Foundry_Services">Intel Foundry Services</a></li>

</ul>
</details>

**Tags**: `#Apple`, `#Intel`, `#semiconductor manufacturing`, `#Trump`, `#supply chain`

---

<a id="item-11"></a>
## [Shanghai Aims for High-Quality Brain Control by 2027, Semi-Invasive BCI Clinical Use, Invasive Breakthroughs](https://t.me/zaihuapd/42501) ⭐️ 7.0/10

Shanghai's government issued the 'Shanghai Brain-Computer Interface Future Industry Cultivation Action Plan (2025-2030)', targeting clinical application of semi-invasive BCI products by 2027, while also seeking breakthroughs in invasive BCI research for speech and motor function recovery. This detailed government plan signals strong policy support, potentially accelerating BCI development and AI integration in healthcare, benefiting patients with neurological conditions and boosting the medical device industry. The plan requires at least five invasive or semi-invasive BCI products to complete medical device type testing and clinical trials, aiming to restore partial speech and motor functions for patients with aphasia or paralysis.

telegram · zaihuapd · Jul 11, 15:49

**Background**: Brain-computer interfaces (BCIs) enable direct communication between the brain and external devices. Non-invasive BCIs use external sensors like EEG; semi-invasive BCIs place electrodes on the brain's surface (e.g., ECoG); invasive BCIs implant electrodes directly into neural tissue. These technologies are being developed to restore functions for people with paralysis, speech loss, or other neurological impairments.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Brain–computer_interface">Brain–computer interface - Wikipedia</a></li>
<li><a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC12671281/">Invasive Brain-Computer Interfaces: A Critical Assessment of Current Developments and Future Prospects - PMC</a></li>

</ul>
</details>

**Tags**: `#brain-computer interface`, `#government policy`, `#artificial intelligence`, `#medical technology`, `#Shanghai`

---

<a id="item-12"></a>
## [Yu Chengdong Slams AITO M8 Location Tracking Bug, Orders Emergency OTA Fix](https://user.guancha.cn/main/content?id=1686339) ⭐️ 6.0/10

A privacy flaw in the AITO M8 allowed an authorized account to continue receiving vehicle location via the parking valet function even after the owner had revoked location permissions. Huawei executive Yu Chengdong harshly criticized the issue as "too stupid" and ordered an immediate OTA fix, rejecting the originally scheduled September update. This incident highlights the growing privacy and security risks in connected vehicles, where software bugs can inadvertently expose sensitive location data. It underscores the pressure on automakers to prioritize data protection as smart cars become more integrated with personal devices. The flaw involved the VPD (Valet Parking Driver) feature, part of Huawei's ADS 3.0 system, which continued to share location after permission revocation. Yu Chengdong reportedly threatened to "eliminate" team members who suggested a September fix and demanded the team work without rest to deliver the OTA patch immediately.

telegram · zaihuapd · Jul 11, 02:05

**Background**: The AITO M8 is an electric SUV under Huawei's Harmony Intelligent Mobility Alliance (HIMA). Huawei provides intelligent vehicle solutions, including the ADS autonomous driving system and the HarmonyOS cockpit. The parking valet function allows the car to park itself or be summoned remotely. OTA (over-the-air) updates enable remote software fixes, eliminating the need for physical service visits.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/鸿蒙智行">鸿蒙智行</a></li>
<li><a href="https://www.chinaz.com/2024/1222/1659784.shtml">鸿蒙智行 泊 车 代 驾 VPD正式开启全量推送！升级自动 泊 车 /接 驾 等多项 功 能</a></li>

</ul>
</details>

**Tags**: `#privacy`, `#automotive`, `#security`, `#IoT`, `#Huawei`

---

<a id="item-13"></a>
## [Telegram Beta Introduces Article Messages with Table and Math Support](https://t.me/zaihuapd/42495) ⭐️ 6.0/10

Telegram has rolled out a beta feature for Premium users that allows sending article messages with rich formatting such as tables, math formulas, code blocks, and collapsible quotes. The feature is available on Android and iOS beta version 12.9 and desktop beta 6.9.4. This update enhances Telegram’s capabilities as a content-rich messaging platform, allowing creators to share structured, formatted content directly within chats. It could make Telegram more appealing for educational, technical, and professional communities. The editor is accessed via the 'Article' option in the attachment menu or an arrow icon above the send button. Currently, iOS beta is closed to new testers, limiting access to existing participants.

telegram · zaihuapd · Jul 11, 12:29

**Background**: Telegram is a cloud-based messaging app known for its focus on privacy and feature-rich updates. Premium subscribers pay a monthly fee for exclusive features like larger file uploads and faster downloads. Beta versions allow early testing of new features before wider release.

**Tags**: `#Telegram`, `#feature update`, `#messaging`, `#beta`, `#rich text`

---

<a id="item-14"></a>
## [Zhipu AI Founder Tang Jie Launches 'Touch High' Plan for AGI](https://mp.weixin.qq.com/s/3CQSkf_kBnXiCDgS4L-Cgg) ⭐️ 6.0/10

Zhipu AI founder Tang Jie announced the 'Touch High' plan to pursue AGI by overcoming four peaks: long-range tasks, autonomous agent systems, full self-training, and extreme safety governance, with a hundred-billion-level investment in mechanistic interpretability. This signals a major Chinese AI company doubling down on AGI with a strong emphasis on safety and interpretability, challenging the narrative that prioritizes short-term commercialization, and the open-source GLM-5.2 model nearing frontier capabilities could democratize access to advanced AI. The GLM-5.2 model is considered close to overseas frontier models and is open-source, gaining community traction. The plan specifically targets mechanistic interpretability to make black-box models transparent, with a massive resource commitment.

telegram · zaihuapd · Jul 11, 13:59

**Background**: Zhipu AI, now internationally branded as Z.ai, is a leading Chinese AI company and one of the 'AI tigers', known for the open-source GLM series of large language models. Its GLM models have adopted the MIT License since July 2025, contributing to their popularity. Mechanistic interpretability is a field focused on understanding the internal workings of neural networks, aiming to reverse-engineer their algorithms for safety. The company was blacklisted by the US in January 2025, adding geopolitical context to its ambitious AGI push.

<details><summary>References</summary>
<ul>
<li><a href="https://wallstreetcn.com/articles/3776707">智 谱创始人唐杰发布内部信：将开启 Touch High...</a></li>
<li><a href="https://en.wikipedia.org/wiki/GLM_5.2">GLM 5.2</a></li>
<li><a href="https://juejin.cn/post/7577438119559266355">Anthropic 机 械 可 解 释 性 学习路线Anthropic...</a></li>

</ul>
</details>

**Tags**: `#AGI`, `#AI Safety`, `#Model Interpretability`, `#Open Source`, `#China AI`

---

<a id="item-15"></a>
## [Claude Code Desktop Adds Built-in Browser](https://x.com/ClaudeDevs/status/2075635283211772279) ⭐️ 6.0/10

Claude Code's desktop app now includes a sandboxed built-in browser, allowing users to open and interact with web pages, documents, and design mockups directly within the application. This integration streamlines development workflows by enabling AI-assisted web interaction without leaving the coding environment, enhancing productivity for developers testing local servers or referencing web resources. The browser runs in a sandboxed environment for security, and users can configure whether browsing sessions are persisted.

telegram · zaihuapd · Jul 11, 14:34

**Background**: Claude Code is an AI-powered coding assistant from Anthropic that understands codebases, edits files, and executes commands. The desktop app brings a graphical interface to this tool, and the new built-in browser eliminates the need to switch to an external web browser for previewing web outputs or viewing documentation.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_Code">Claude Code</a></li>
<li><a href="https://claude.com/product/claude-code">Claude Code by Anthropic | AI Coding Agent, Terminal, IDE</a></li>

</ul>
</details>

**Tags**: `#Claude Code`, `#AI coding assistant`, `#built-in browser`, `#desktop app`, `#feature update`

---

<a id="item-16"></a>
## [Google Opposes EU Site Blocking, US Considers Similar Anti-Piracy Laws](https://torrentfreak.com/google-opposes-site-blocking-in-europe-as-u-s-piracy-blocking-plans-gain-momentum/) ⭐️ 6.0/10

Google submitted a filing to the European Commission opposing expanded website blocking, arguing it is ineffective and harms legitimate services. Meanwhile, US lawmakers are advancing similar site-blocking legislation. This highlights a growing global debate over balancing copyright enforcement with internet openness. The divergence in Google's stance reflects tensions between corporate interests and government regulation, potentially shaping future internet architecture. Google opposes blocking DNS resolvers, IP addresses, and VPNs, citing collateral damage such as Italy's Piracy Shield mistakenly blocking Google Drive and a Cloudflare IP hosting 42 million domains.

telegram · zaihuapd · Jul 11, 15:10

**Background**: Website blocking forces ISPs to deny access to infringing sites, often extended to DNS and IP blocking. In Europe, such measures conflict with net neutrality, while in the US, proposals like SOPA have sparked controversy. Italy's Piracy Shield system, an automated anti-piracy platform, has been criticized for over-blocking legitimate services, illustrating the risks Google highlights.

**Tags**: `#tech policy`, `#site blocking`, `#copyright`, `#internet freedom`, `#censorship`

---