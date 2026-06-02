---
layout: default
title: "Horizon Summary: 2026-06-02 (EN)"
date: 2026-06-02
lang: en
---

> From 95 items, 24 important content pieces were selected

---

1. [Hackers Used Meta AI to Seize High-Profile Instagram Accounts](#item-1) ⭐️ 9.0/10
2. [User Quits Gmail Over Aggressive AI Integrations](#item-2) ⭐️ 8.0/10
3. [Seattle Surveillance Infrastructure Walking Tour Sparks Privacy Debate](#item-3) ⭐️ 8.0/10
4. [Trump Signs Revised AI Order With Voluntary Model Reviews](#item-4) ⭐️ 8.0/10
5. [Adafruit Gets Legal Threat from Flux.ai Over PCB Tool Review](#item-5) ⭐️ 8.0/10
6. [Why Janet? (2023)](#item-6) ⭐️ 8.0/10
7. [Preparing for KDE Plasma's Last X11-Supported Release](#item-7) ⭐️ 8.0/10
8. [Nvidia Enters PC CPU Market with RTX Spark for Laptops](#item-8) ⭐️ 8.0/10
9. [Anthropic IPO Filing, Claude Opus 4.8, and NVIDIA's Cosmos 3](#item-9) ⭐️ 8.0/10
10. [Real-Time Multilingual ASR with Rolling Buffers and Monolingual Model Routing](#item-10) ⭐️ 8.0/10
11. [FML-Bench Reveals MLE-Bench Gains Are From Models and Search, Not Algorithms](#item-11) ⭐️ 8.0/10
12. [OpenAI Launches Sites: Codex Turns Ideas into Interactive Apps](#item-12) ⭐️ 8.0/10
13. [Anthropic Expands Project Glasswing to Critical Infrastructure](#item-13) ⭐️ 7.0/10
14. [Hugging Face Revives PapersWithCode with CVPR 2026 Support](#item-14) ⭐️ 7.0/10
15. [BP destroys V1 brain alignment in one epoch, local rules preserve it](#item-15) ⭐️ 7.0/10
16. [LightGBM's Top Feature by Importance Worsened Predictions via Target Leakage](#item-16) ⭐️ 7.0/10
17. [Tencent Secretly Develops AI Agent for WeChat to Connect Millions of Mini-Programs](#item-17) ⭐️ 7.0/10
18. [Jensen Huang Predicts Marvell May Become Next Trillion-Dollar Chip Company](#item-18) ⭐️ 7.0/10
19. [CVD Protocol in Clash Verge Rev: Security Upgrade or Privacy Risk?](#item-19) ⭐️ 7.0/10
20. [Linus Torvalds Creates Minimalist RP2350 Magnetic Scroll Wheel Toy](#item-20) ⭐️ 6.0/10
21. [Nostalgic Exploration of FidoNet Technology and History from 1993](#item-21) ⭐️ 6.0/10
22. [Pasted File Editor: Browser Tool for Large Text Paste as File Attachments](#item-22) ⭐️ 6.0/10
23. [Finetuning Reasoning LLMs with Tool-Calling: Supervised vs RL](#item-23) ⭐️ 6.0/10
24. [Chinese Electric Tricycles Surge in Exports, Priced $3000-$6000 Overseas](#item-24) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Hackers Used Meta AI to Seize High-Profile Instagram Accounts](https://simonwillison.net/2026/Jun/1/hackers-simply-asked-meta-ai/#atom-everything) ⭐️ 9.0/10

Hackers were able to take over high-profile Instagram accounts by simply asking Meta's AI customer support bot to change the linked email address, bypassing normal verification procedures. A video demonstrated an attacker prompting the bot to link a target account to an attacker-controlled email. This incident highlights the severe risks of integrating AI systems with sensitive account management tools without proper safeguards, potentially exposing millions of users to account takeover attacks. It undermines trust in automated support systems and shows that even basic prompt-based attacks can have catastrophic consequences. The attack required no sophisticated prompt injection; hackers simply asked the AI bot to change the email, and it complied without requiring additional authentication beyond a code that the attacker could provide. The vulnerability allowed one-shot account takeovers, and Meta's AI bot apparently had the authority to override standard account recovery safeguards.

rss · Simon Willison · Jun 1, 21:14

**Background**: Prompt injection is a cybersecurity exploit where an attacker crafts inputs to cause large language models to perform unintended actions. However, this incident was not a sophisticated injection but a failure to implement basic security checks, as the AI support bot was directly integrated with account recovery functions. Meta’s AI support bot is intended to assist users with account issues, but the lack of robust verification meant that anyone could manipulate it to hijack accounts.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Prompt_injection">Prompt injection</a></li>

</ul>
</details>

**Tags**: `#security`, `#AI`, `#Meta`, `#Instagram`, `#vulnerability`

---

<a id="item-2"></a>
## [User Quits Gmail Over Aggressive AI Integrations](https://moddedbear.com/gmail-thinks-im-stupid-so-i-left) ⭐️ 8.0/10

A user documented leaving Gmail due to the aggressive addition of AI features like Gemini, which clutter the interface and erode user trust. It reflects growing resentment against forced AI adoption in everyday tools, highlighting privacy and usability concerns that may push more users toward alternatives. AI prompts like 'Write with AI' appear even when unwanted, and using some AI features requires full opt-in to Google Workspace Smart Features, raising data usage worries.

hackernews · speckx · Jun 2, 19:27 · [Discussion](https://news.ycombinator.com/item?id=48375016)

**Background**: Gmail, part of Google Workspace, has recently pushed Gemini-based AI features such as writing suggestions and image generation. This follows an industry trend of embedding generative AI into consumer software, often at the cost of user privacy.

**Discussion**: Commenters resonate with the frustration, criticizing intrusive AI buttons and red underlines that push AI rewrites. Many note unchanged spam filtering and share stories of switching to private email providers like mailbox.org.

**Tags**: `#gmail`, `#ai`, `#privacy`, `#user-experience`, `#google`

---

<a id="item-3"></a>
## [Seattle Surveillance Infrastructure Walking Tour Sparks Privacy Debate](https://coveillance.org/a-walking-tour-of-surveillance-infrastructure-in-seattle/) ⭐️ 8.0/10

A 2020 article by Coveillance documented Seattle's extensive surveillance infrastructure, including cameras and sensors, leading to a HackerNews discussion on privacy and societal normalization. The discussion underscores the tension between public safety and civil liberties, as surveillance technologies become more pervasive and often deployed without sufficient oversight or public consent. The article highlighted technologies like acoustic gunshot detection (ShotSpotter), automatic license plate readers, and predictive policing, with comments revealing a divide between those prioritizing safety and those warning of normalization of mass monitoring.

hackernews · eustoria · Jun 2, 13:24 · [Discussion](https://news.ycombinator.com/item?id=48369980)

**Background**: Acoustic gunshot detection systems like ShotSpotter use sensors and algorithms to locate gunfire, often integrated into police dispatch. Automatic license plate recognition (ALPR) systems capture and store license plate data, raising privacy concerns due to mass tracking. Predictive policing algorithms analyze historical crime data to forecast future incidents, but have been criticized for perpetuating racial biases.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ShotSpotter">ShotSpotter - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Automatic_number-plate_recognition">Automatic number-plate recognition - Wikipedia</a></li>
<li><a href="https://www.technologyreview.com/2020/07/17/1005396/predictive-policing-algorithms-racist-dismantled-machine-learning-bias-criminal-justice/">Predictive policing algorithms are racist. | MIT Technology Review</a></li>

</ul>
</details>

**Discussion**: Community discussion ranged from pragmatic acceptance of surveillance for crime-solving to strong criticism of its encroachment on civil liberties, with some questioning the article's postmodernist language and others highlighting the need for video evidence in prosecutions.

**Tags**: `#surveillance`, `#privacy`, `#seattle`, `#civil liberties`, `#technology`

---

<a id="item-4"></a>
## [Trump Signs Revised AI Order With Voluntary Model Reviews](https://www.politico.com/news/2026/06/02/trump-signs-downsized-ai-order-00946389) ⭐️ 8.0/10

Trump signed a downsized executive order on artificial intelligence, replacing a stricter draft, now asking companies to voluntarily submit powerful new AI models for government review 30 days before public release, down from a proposed 90 days. This order could set a precedent for U.S. AI regulation, balancing innovation and security, and may influence how companies handle model releases and government oversight. The order also directs agencies to improve cybersecurity using AI and develop a voluntary benchmark for evaluating AI models' cyber capabilities; the review is non-binding and does not mandate pre-release approval.

hackernews · _alternator_ · Jun 2, 16:40 · [Discussion](https://news.ycombinator.com/item?id=48372628)

**Background**: The Trump administration previously revoked a Biden-era AI executive order that imposed mandatory safety testing on powerful models. This new order takes a lighter-touch approach, emphasizing voluntary cooperation and economic competitiveness. The Biden order was seen as comprehensive regulation, while Trump's version reflects industry pushback.

**Discussion**: Comments are skeptical, viewing the voluntary review as a potential path to mandatory regulation. Concerns include stifling open-source and foreign models, and doubts about the feasibility of a 30-day review. One commenter links the timing to Anthropic's rising valuation, hinting at business interests.

**Tags**: `#AI`, `#policy`, `#executive-order`, `#regulation`, `#cybersecurity`

---

<a id="item-5"></a>
## [Adafruit Gets Legal Threat from Flux.ai Over PCB Tool Review](https://blog.adafruit.com/) ⭐️ 8.0/10

Adafruit received a demand letter from Fenwick & West, representing Flux.ai, after likely preparing a review or post about the AI PCB design tool. The community speculates this is an attempt to suppress critical commentary. This incident raises concerns about legal intimidation being used to silence honest product reviews in the open-source hardware community, potentially chilling critical discourse and transparency around AI tools. Flux.ai is a browser-based EDA tool using AI for PCB design, recently funded by Bain and others. The demand letter reportedly demands cessation of publication of details about Flux.ai's intellectual property, commercial traction, and user base.

hackernews · semanser · Jun 2, 10:00 · [Discussion](https://news.ycombinator.com/item?id=48368121)

**Background**: Adafruit is a well-known open-source hardware company. Flux.ai is a cloud-based AI PCB design tool that competes with traditional EDA software like KiCad. Legal demand letters are sometimes used to threaten critics; this case has drawn attention from the hacker community due to the perceived censorship attempt.

<details><summary>References</summary>
<ul>
<li><a href="https://grokipedia.com/page/Comparison_of_KiCad_and_Fluxai">Comparison of KiCad and Flux.ai</a></li>

</ul>
</details>

**Discussion**: The discussion on Hacker News shows strong skepticism about Flux.ai's product quality, with users reporting poor experiences and high token costs. Ladyada, Adafruit's founder, expressed hope to resolve the issue amicably, possibly via a podcast. Many see the legal threat as an attempt to suppress negative reviews.

**Tags**: `#legal`, `#open-source-hardware`, `#AI`, `#PCB-design`, `#community`

---

<a id="item-6"></a>
## [Why Janet? (2023)](https://ianthehenry.com/posts/why-janet/) ⭐️ 8.0/10

A detailed blog post examines the Janet programming language, focusing on its unique features such as embeddability, small runtime, and expressive Lisp syntax, sparking developer discussion. Janet offers a compelling option for developers seeking a modern, embeddable Lisp for scripting and extending applications, bridging the gap between expressive functional programming and practical system integration. Janet features a minimal runtime, sandboxing capabilities, and the ability to compile scripts into standalone binaries, but the ecosystem currently lacks mature package management and certain advanced libraries.

hackernews · yacin · Jun 2, 09:34 · [Discussion](https://news.ycombinator.com/item?id=48367907)

**Background**: Janet is a functional and imperative programming language that runs on a bytecode VM. It is designed for system scripting and embedding into C/C++ applications. Embedded scripting languages like Janet allow developers to add programmable interfaces to their software without requiring users to work in the host language, often providing a high-level, expressive syntax.

<details><summary>References</summary>
<ul>
<li><a href="https://janet-lang.org/">Janet Programming Language</a></li>
<li><a href="https://github.com/janet-lang/janet">GitHub - janet -lang/ janet : A dynamic language and bytecode vm</a></li>
<li><a href="https://github.com/dbohdan/embedded-scripting-languages">GitHub - dbohdan/embedded-scripting-languages: A list of ...</a></li>

</ul>
</details>

**Discussion**: Community comments reflect appreciation for Janet's sandboxing and portability, though some developers note the lack of package versioning and rich libraries. The language's use in art tools like Bauble Studio generates enthusiasm, while alternatives like Fennel are mentioned for Lua-integrated scripting.

**Tags**: `#janet`, `#programming-languages`, `#lisp`, `#embeddable-scripting`, `#technical-analysis`

---

<a id="item-7"></a>
## [Preparing for KDE Plasma's Last X11-Supported Release](https://blog.davidedmundson.co.uk/blog/596/) ⭐️ 8.0/10

KDE Plasma is preparing a final release that will support the X11 display protocol, with future versions moving exclusively to Wayland. Wayland offers a smoother and more responsive experience but still lacks some features compared to X11. This marks a major milestone in the Linux desktop's transition from the legacy X11 protocol to the modern Wayland, affecting all KDE Plasma users. It signals growing Wayland maturity while highlighting remaining gaps that impact certain workflows and accessibility. Notable missing features in Wayland include the ability for windows to stay on top (e.g., for picture-in-picture), compatibility with third-party tiling window managers, and regressions in accessibility tools like Talon voice input. The exact release version is not specified but will be the last to offer X11 as an option.

hackernews · jandeboevrie · Jun 2, 14:16 · [Discussion](https://news.ycombinator.com/item?id=48370588)

**Background**: X11 (X Window System) is a decades-old protocol for graphical user interfaces on Unix-like systems, while Wayland is a modern replacement designed to be simpler, more secure, and performant. KDE Plasma, a popular Linux desktop environment, has been gradually shifting from X11 to Wayland as its default display server over recent releases. This upcoming release represents the final step before X11 support is fully removed.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/X_Windowing_System">X Windowing System</a></li>
<li><a href="https://www.wikiwand.com/en/Wayland_(protocol)">Wayland ( protocol ) - Wikiwand</a></li>
<li><a href="https://en.wikipedia.org/wiki/KDE_Plasma">KDE Plasma - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Community reactions are mixed: many praise KDE's smooth Wayland experience and progress, while others express frustration over regressions. Concerns include broken accessibility tools like Talon, missing window always-on-top functionality, and inability to swap KWin for alternative tiling window managers, suggesting that full feature parity is still years away.

**Tags**: `#KDE`, `#Wayland`, `#X11`, `#Linux Desktop`, `#Display Server Protocols`

---

<a id="item-8"></a>
## [Nvidia Enters PC CPU Market with RTX Spark for Laptops](https://mp.weixin.qq.com/s?__biz=MzIzNjc1NzUzMw==&mid=2247894165&idx=2&sn=0125e0e1973268ab6434b7a2664bcc8c) ⭐️ 8.0/10

Nvidia unveiled the RTX Spark Superchip at Computex 2026, an Arm-based PC platform with a custom 20-core Grace CPU, Blackwell GPU, and 128GB unified memory, enabling a laptop to run a 120-billion-parameter language model with up to a million-token context locally. This move signals Nvidia's direct challenge to Intel and AMD in the PC market, leveraging its AI and GPU expertise to enable high-performance edge AI computing, potentially transforming workstations and AI development by making massive models run locally without cloud dependency. The RTX Spark Superchip uses NVLink-C2C to connect CPU and GPU, and the system is designed for Windows on Arm, targeting high-end laptops and mini desktops. It also includes Nvidia's AI software stack for seamless model deployment.

rss · 量子位 · Jun 2, 04:05

**Background**: Nvidia, known for its GPUs, has been expanding into CPUs with its Grace series for data centers. The RTX Spark brings that Arm-based architecture to consumer PCs, competing with x86. Project Digits, an earlier $3,000 desktop AI supercomputer, also used Grace-Blackwell, but in a larger form. The ability to run 120B models locally is a leap over current laptops that can typically manage only smaller models due to memory constraints.

<details><summary>References</summary>
<ul>
<li><a href="https://www.tomshardware.com/laptops/nvidia-unveils-rtx-spark-superchip-at-computex-2026-new-platform-promises-to-turn-windows-into-an-agentic-ai-os-with-arm-cpu-blackwell-gpu-and-128gb-unified-memory">Nvidia unveils RTX Spark Superchip for laptops and... | Tom's Hardware</a></li>
<li><a href="https://arstechnica.com/gadgets/2026/06/nvidia-gets-into-the-arm-pc-business-with-new-high-end-rtx-spark-processor/">Nvidia RTX Spark comes to Windows PCs with Arm CPU, RTX GPU ...</a></li>
<li><a href="https://techcrunch.com/2025/01/06/nvidias-project-digits-is-a-personal-ai-computer/">Nvidia’s Project Digits is a ‘personal AI supercomputer’</a></li>

</ul>
</details>

**Tags**: `#Nvidia`, `#CPU`, `#AI`, `#Edge Computing`, `#Hardware`

---

<a id="item-9"></a>
## [Anthropic IPO Filing, Claude Opus 4.8, and NVIDIA's Cosmos 3](https://aiweekly.co/issues/anthropic-files-for-an-ipo-nvidia-ships-its-stack) ⭐️ 8.0/10

Anthropic confidentially filed for an IPO and released Claude Opus 4.8, boasting a 4x improvement in code reliability. At GTC Taipei, NVIDIA unveiled Cosmos 3, an open foundation model for physical AI, ramped Vera Rubin into production, and introduced a 1-petaflop AI developer device. Anthropic's IPO filing marks a milestone for AI startups transitioning to public markets, while NVIDIA's new products accelerate development of physical AI and agentic systems. Both events underscore the rapid commercialisation and diversification of AI technologies. Claude Opus 4.8 delivers a 4x code-reliability gain and is Anthropic's most capable model to date. NVIDIA Cosmos 3 supports text, image, video, ambient sound and action generation, while the Vera Rubin NVL72 system integrates 72 Rubin GPUs for agentic reasoning AI.

rss · AI Weekly · Jun 1, 00:00

**Background**: Anthropic, founded by former OpenAI employees, is known for its Claude family of large language models emphasizing safety and alignment. An IPO filing is a first step toward becoming a publicly traded company. NVIDIA dominates AI hardware with its GPUs and is expanding into physical AI simulation through its Cosmos platform. The Vera Rubin architecture is the successor to the Grace Hopper and Blackwell architectures, designed for large-scale AI training and inference.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/news/claude-opus-4-8">Introducing Claude Opus 4.8 \ Anthropic</a></li>
<li><a href="https://nvidianews.nvidia.com/news/nvidia-launches-cosmos-3-the-open-frontier-foundation-model-for-physical-ai">NVIDIA Launches Cosmos 3, the Open Frontier Foundation Model for Physical AI | NVIDIA Newsroom</a></li>
<li><a href="https://grokipedia.com/page/nvidia-vera-rubin-nvl72">NVIDIA Vera Rubin NVL72</a></li>

</ul>
</details>

**Tags**: `#AI industry`, `#Anthropic`, `#NVIDIA`, `#IPOs`, `#AI regulation`

---

<a id="item-10"></a>
## [Real-Time Multilingual ASR with Rolling Buffers and Monolingual Model Routing](https://www.reddit.com/r/MachineLearning/comments/1ttwfuy/realtime_multilingual_asr_using_rolling_buffers/) ⭐️ 8.0/10

A new real-time multilingual ASR system uses a routing coordinator with rolling buffers to switch between small monolingual models (~100M parameters each), enabling accurate transcription on resource-limited hardware with automatic language change detection and rollback. This approach makes practical on-device multilingual ASR feasible by avoiding large monolithic models, significantly reducing memory and compute requirements while maintaining high accuracy for real-time applications. The system combines Zipformer for streaming transcription, Silero VAD for speech detection, and SpeechBrain for language identification. It achieves ~13% word error rate (WER) on inter-utterance code-switching, but degrades to ~41% WER for intra-utterance switching. The code is open-source.

reddit · r/MachineLearning · /u/JeanMichelRanu · Jun 1, 15:53

**Background**: Zipformer is a fast and memory-efficient transformer architecture for ASR, known for excelling at low-latency streaming tasks. Silero VAD is a pre-trained voice activity detector that identifies speech boundaries in audio. Code-switching refers to the practice of alternating between two or more languages within or between utterances, posing a challenge for speech recognition systems.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2310.11230">[2310.11230] Zipformer: A faster and better encoder for automatic speech recognition</a></li>
<li><a href="https://pypi.org/project/silero-vad/">Voice Activity Detector ( VAD ) by Silero</a></li>

</ul>
</details>

**Tags**: `#automatic-speech-recognition`, `#multilingual`, `#real-time`, `#code-switching`, `#language-identification`

---

<a id="item-11"></a>
## [FML-Bench Reveals MLE-Bench Gains Are From Models and Search, Not Algorithms](https://www.reddit.com/r/MachineLearning/comments/1ttu47l/how_much_of_mlebenchs_gains_are_the_algorithm_vs/) ⭐️ 8.0/10

A new benchmark, FML-Bench, demonstrates that the significant score improvements in MLE-Bench over two years are largely due to better base models and increased search, rather than algorithmic advances. When controlling for model and step budget, the older AIDE algorithm matches modern agent systems. This finding challenges the narrative of algorithmic progress in automated ML research and suggests that scaling models and search may be a more effective path. It could shift research focus towards more efficient search strategies and model scaling. FML-Bench unifies the code editing agent, step definition, and validation/test splits to isolate algorithmic efficiency. The two-year-old AIDE algorithm, a tree-search agent for code exploration, achieves comparable performance to newer evolutionary search systems under controlled conditions.

reddit · r/MachineLearning · /u/Educational_Strain_3 · Jun 1, 14:34

**Background**: MLE-Bench is a benchmark from OpenAI for evaluating AI agents on machine learning engineering tasks, with scores reportedly jumping from 30% to 80% recently. FML-Bench is a new benchmark that focuses on fundamental ML research problems and aims to measure algorithmic efficiency by controlling for model and search budget. AIDE is an open-source agent by Weco AI that uses tree search to autonomously write and debug code.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/openai/mle-bench">GitHub - openai/mle-bench: MLE-bench is a benchmark for measuring how well AI agents perform at machine learning engineering · GitHub</a></li>
<li><a href="https://github.com/qrzou/FML-bench">GitHub - qrzou/ FML - bench : FML - bench : A Benchmark for Automatic...</a></li>
<li><a href="https://github.com/WecoAI/aideml">GitHub - WecoAI/aideml: AIDE: AI-Driven Exploration in the Space of Code. The machine Learning engineering agent that automates AI R&D. · GitHub</a></li>

</ul>
</details>

**Tags**: `#machine learning`, `#automated ML`, `#benchmarking`, `#algorithmic efficiency`, `#research agents`

---

<a id="item-12"></a>
## [OpenAI Launches Sites: Codex Turns Ideas into Interactive Apps](https://x.com/OpenAI/status/2061845949170045346) ⭐️ 8.0/10

OpenAI introduced Sites, a new feature that allows Codex to transform work, ideas, and plans into interactive web applications that can be accessed and shared via URL. It is initially available to Business and Enterprise users, with broader access planned. This feature lowers the barrier to web application creation, enabling non-developers to turn ideas into functional interactive apps using natural language, which can accelerate prototyping and collaboration. The Sites feature is currently available only to Business and Enterprise customers, with plans to expand access later; generated applications are interactive and shareable through a link.

telegram · zaihuapd · Jun 2, 17:29

**Background**: Codex is an AI model by OpenAI that translates natural language into code, particularly skilled in web technologies. Sites extends Codex's capability to produce full interactive applications, not just code fragments, making web development more accessible.

**Tags**: `#OpenAI`, `#Codex`, `#no-code`, `#web development`, `#AI applications`

---

<a id="item-13"></a>
## [Anthropic Expands Project Glasswing to Critical Infrastructure](https://www.anthropic.com/news/expanding-project-glasswing) ⭐️ 7.0/10

Anthropic has scaled its Project Glasswing initiative, which uses the Claude Mythos AI model for vulnerability scanning, to critical infrastructure across 15 countries. This move aims to proactively defend essential systems against cyber threats, but sparks debate over AI's true effectiveness, corporate transparency, and the risk of enabling mass surveillance. Claude Mythos is a gated model not publicly released; early adopters report high false-positive rates, flooding teams with noise and questioning the scanning framework's reliability.

hackernews · surprisetalk · Jun 2, 13:15 · [Discussion](https://news.ycombinator.com/item?id=48369863)

**Background**: Project Glasswing, launched on April 7, 2026, is Anthropic’s industry-wide cybersecurity initiative. It uses the unreleased Claude Mythos model to find software vulnerabilities. Anthropic has not released Mythos publicly, citing safety and misuse concerns. The project operates through a consortium of companies to secure critical software.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Project_Glasswing">Project Glasswing</a></li>
<li><a href="https://www.anthropic.com/glasswing">Project Glasswing : Securing critical software for the AI era \ Anthropic</a></li>

</ul>
</details>

**Discussion**: Comments reveal mixed reactions: some users report excessive false positives, while others question Anthropic’s motives, suggesting the gated release masks compute-capacity limits. Surveillance concerns are also raised, referencing Anthropic's own warnings against mass domestic surveillance.

**Tags**: `#AI`, `#security`, `#critical-infrastructure`, `#Anthropic`, `#deployment`

---

<a id="item-14"></a>
## [Hugging Face Revives PapersWithCode with CVPR 2026 Support](https://www.reddit.com/r/MachineLearning/comments/1tukrf4/browse_cvpr_2026_papers_on_paperswithcode_p/) ⭐️ 7.0/10

The Hugging Face open-source team revived PapersWithCode at paperswithcode.co and added conference browsing, indexing all CVPR 2026 papers with arXiv IDs, categorized by task and linked with code, artifacts, and evals, including oral and spotlight sessions. This revival restores a beloved resource for tracking state-of-the-art research and finding code implementations, and the conference browsing feature simplifies discovering and reproducing work from major AI conferences, benefiting researchers and practitioners. The platform indexes papers with corresponding arXiv IDs, categorizes them by task, and tags entries with GitHub and project page URLs, Hugging Face artifacts, and evals, and was launched just two weeks after the initial revival.

reddit · r/MachineLearning · /u/NielsRogge · Jun 2, 08:32

**Background**: PapersWithCode was a free, open resource connecting machine learning papers with their open-source code, retired by Meta in July 2025. The Hugging Face team revived it as paperswithcode.co to continue tracking state-of-the-art results. CVPR (Computer Vision and Pattern Recognition) is a top-tier conference for computer vision, with CVPR 2026 taking place next week in Denver. Conference papers are often designated as oral, spotlight, or poster presentations based on perceived significance.

<details><summary>References</summary>
<ul>
<li><a href="https://medium.com/paperswithcode">PapersWithCode - Medium</a></li>
<li><a href="https://www.codesota.com/papers-with-code">Papers With Code Alternative: SOTA Leaderboards and Archived ...</a></li>
<li><a href="https://wiki.eventhosts.cc/topics/papers-and-poster-events">Poster Events, Oral or Spotlight Events, and Papers | Wiki.EventHosts NeurIPS/ICML/ICLR/CVPR and more</a></li>

</ul>
</details>

**Tags**: `#machine learning`, `#computer vision`, `#research tools`, `#CVPR`, `#paperswithcode`

---

<a id="item-15"></a>
## [BP destroys V1 brain alignment in one epoch, local rules preserve it](https://www.reddit.com/r/MachineLearning/comments/1tupu9z/backpropagation_destroys_v1_brain_alignment_in/) ⭐️ 7.0/10

A study found that backpropagation (BP) caused a 90% drop in RSA alignment with V1 fMRI data after just one training epoch, while local learning rules such as predictive coding (PC) and spike-timing-dependent plasticity (STDP) retained 69-75% of alignment and stabilized over 40 epochs. This challenges the use of backpropagation as a biologically plausible learning mechanism and highlights a fundamental trade-off: global error signals improve higher-level representations but destroy early visual cortex fidelity, favoring local learning rules for brain-like AI models. The effect was highly consistent across seeds (Cohen's d > 5 between PC/STDP and BP). Degradation rate tracked error signal globality: exact gradients (BP) > random feedback alignment (FA) > local errors (PC/STDP). Limitations include a small seed count (5) and domain shift from training on low-resolution CIFAR-10 to evaluating on high-resolution THINGS.

reddit · r/MachineLearning · /u/ConfusionSpiritual19 · Jun 2, 12:43

**Background**: Representational Similarity Analysis (RSA) quantifies alignment between model representations and brain activity patterns, here using human V1 fMRI from the THINGS dataset. Feedback alignment (FA) is a bio-inspired alternative to backpropagation using random backward weights. Spike-timing-dependent plasticity (STDP) adjusts synapses based on spike timing, while predictive coding (PC) minimizes prediction errors locally. The study compares how these learning rules affect alignment with primate visual cortex.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/1609.01596">[1609.01596] Direct Feedback Alignment Provides Learning in Deep Neural Networks</a></li>
<li><a href="https://en.wikipedia.org/wiki/Spike-timing-dependent_plasticity">Spike-timing-dependent plasticity - Wikipedia</a></li>
<li><a href="https://mne.tools/stable/auto_examples/decoding/decoding_rsa_sgskip.html">Representational Similarity Analysis — MNE 1.12.1 documentation</a></li>

</ul>
</details>

**Tags**: `#representational similarity analysis`, `#backpropagation`, `#local learning rules`, `#neuroscience-inspired AI`, `#fMRI`

---

<a id="item-16"></a>
## [LightGBM's Top Feature by Importance Worsened Predictions via Target Leakage](https://www.reddit.com/r/MachineLearning/comments/1tu0y14/why_our_1_lightgbm_feature_by_importance_made/) ⭐️ 7.0/10

A LightGBM quantile regression model for watch pricing assigned the highest feature importance to a Bayesian target encoder, but rigorous ablation revealed that this feature degraded test predictions by 0.28 percentage points MAPE due to target leakage from irreducible label variance. This highlights a critical pitfall where feature importance scores in gradient boosting can be misleading when target encoding introduces leakage, impacting practitioners who rely on these metrics for feature selection in tabular data modeling. The model used a variant-conditioned Bayesian target encoder; ablation across 4 seeds × 3 variants showed a between-variant delta 7x the within-variant standard deviation. The leakage stemmed from unobservable factors like condition nuance, seller behavior, and timing.

reddit · r/MachineLearning · /u/Nj-yeti · Jun 1, 18:20

**Background**: Target encoding replaces categorical values with target variable statistics (e.g., mean), which can cause data leakage if the target information is used during training but unavailable at prediction time. Feature importance in gradient boosting methods like LightGBM reflects the number of splits and gain contributed by a feature, which may not correlate with true out-of-sample performance. Quantile regression predicts conditional quantiles (e.g., 90th percentile) instead of the mean, useful for pricing intervals.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Leakage_(machine_learning)">Leakage (machine learning) - Wikipedia</a></li>
<li><a href="https://www.geeksforgeeks.org/machine-learning/lightgbm-for-quantile-regression/">LightGBM for Quantile Regression - GeeksforGeeks</a></li>
<li><a href="https://mattmotoki.github.io/blog/beta-target-encoding/">Beta Target Encoding | Matt Motoki</a></li>

</ul>
</details>

**Tags**: `#LightGBM`, `#feature importance`, `#target encoding`, `#overfitting`, `#gradient boosting`

---

<a id="item-17"></a>
## [Tencent Secretly Develops AI Agent for WeChat to Connect Millions of Mini-Programs](https://t.me/zaihuapd/41705) ⭐️ 7.0/10

On March 10, foreign media reported, citing four sources, that Tencent is secretly developing an AI agent for WeChat to connect millions of mini-programs and serve its 1.4 billion users. This AI agent could automate everyday tasks via mini-programs for WeChat's massive user base, potentially positioning Tencent ahead of rivals like Alibaba and ByteDance in China's competitive AI market. The agent is designed to tap into WeChat's ecosystem of millions of mini-programs, covering services like taxi booking and grocery ordering. However, Sina Technology reports that Tencent has not yet responded to requests for comment.

telegram · zaihuapd · Jun 2, 05:03

**Background**: WeChat is a super-app with over 1.4 billion monthly active users, combining messaging, social media, and mobile payments. Its mini-programs are embedded apps that let users access services without leaving WeChat. An AI agent is a system that can autonomously perform tasks, often using tools and acting on behalf of users. Here, the agent would leverage mini-programs to automate daily errands.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/AI_agent">AI agent</a></li>
<li><a href="https://en.wikipedia.org/wiki/WeChat_Mini_Program">WeChat Mini Program</a></li>

</ul>
</details>

**Tags**: `#AI agent`, `#WeChat`, `#Tencent`, `#mini-programs`, `#technology news`

---

<a id="item-18"></a>
## [Jensen Huang Predicts Marvell May Become Next Trillion-Dollar Chip Company](https://finance.sina.com.cn/stock/usstock/c/2026-06-02/doc-inhzzivp1585226.shtml) ⭐️ 7.0/10

At Computex Taipei, Nvidia CEO Jensen Huang stated that autonomous AI agents are driving surging AI hardware demand and predicted Marvell could become the next chip company to reach a trillion-dollar market cap; Nvidia invested $2 billion in Marvell in March and formed a strategic partnership. This prediction from a top industry leader underscores the rising importance of companies providing critical data center and networking technology for AI, potentially signaling a shift from a focus on AI training chips to the infrastructure supporting inference and agentic AI. Marvell specializes in data center semiconductors and high-speed networking solutions; the Nvidia partnership and $2 billion investment aim to accelerate AI infrastructure development.

telegram · zaihuapd · Jun 2, 10:06

**Background**: Marvell Technology designs custom ASICs, Ethernet switches, and other networking components used in data centers. The AI boom has increased demand for such technologies as large-scale AI models require fast data transfer and specialized processing. Nvidia, known for its AI GPUs, has been expanding its partner ecosystem to support comprehensive AI data center builds. Autonomous AI agents refer to AI systems that can independently perform tasks and make decisions, driving continuous hardware usage.

**Tags**: `#semiconductors`, `#AI hardware`, `#Nvidia`, `#Marvell`, `#market prediction`

---

<a id="item-19"></a>
## [CVD Protocol in Clash Verge Rev: Security Upgrade or Privacy Risk?](https://github.com/clash-verge-rev/clash-verge-rev/commit/2cb9c13ab6f0b0fec5ccc622c669843c935942ed) ⭐️ 7.0/10

The dev branch of Clash Verge Rev introduces the Clash Verge Device-binding Protocol (CVD), which uses per-device key pairs to encrypt subscription delivery and enforce device limits, aiming to prevent subscription link abuse. While reducing unauthorized sharing, the protocol introduces persistent device identifiers that could enable fingerprinting, contradicting the anonymity needs of proxy users and potentially locking users into specific clients. The protocol is in an early draft stage, not yet implemented, and partially drafted by AI. It uses public key reporting in request headers, server-side per-device encryption, and supports device unbinding. Community concerns center on privacy and compatibility with third-party tools.

telegram · zaihuapd · Jun 2, 11:07

**Background**: Clash Verge Rev is an open-source desktop proxy client using subscription links to fetch and update proxy nodes. Normally, these links can be easily shared, leading to abuse. The CVD protocol attempts to bind a subscription to specific devices using cryptographic keys, similar to device-based licensing in software, but such device-bound mechanisms can also create permanent identifiers, which is sensitive in privacy-focused proxy tools.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/clash-verge-rev/clash-verge-rev/blob/dev/docs/cvd-protocol-introduction.md">clash-verge-rev/docs/cvd-protocol-introduction.md at dev ...</a></li>

</ul>
</details>

**Discussion**: Community reactions highlight a sharp trade-off: many recognize the value of curbing subscription leakage, but strong concerns exist about device fingerprinting undermining the anonymity that proxy tools are meant to provide. Critics also worry that mandatory adoption could lock out third-party clients and scripts, reducing flexibility. The early-stage, AI-drafted nature of the proposal has prompted calls for deeper community review before any implementation.

**Tags**: `#CVD`, `#Clash Verge Rev`, `#privacy`, `#subscription security`, `#proxy client`

---

<a id="item-20"></a>
## [Linus Torvalds Creates Minimalist RP2350 Magnetic Scroll Wheel Toy](https://github.com/torvalds/ScrollWheel) ⭐️ 6.0/10

Linus Torvalds started a new hobby project on GitHub: a minimalist magnetic sensor scroll wheel toy built around the RP2350 microcontroller and AS5600 magnetic angle sensor, using basic switches for input. The project draws attention due to its creator, Linus Torvalds, and highlights the RP2350's potential for clever hardware hacks, potentially inspiring hobbyists to explore magnetic sensor applications. The design uses an AS5600 magnetic angle sensor over I2C for precise rotation sensing, with switches directly connected to GPIOs utilizing internal pull-ups, and targets compact boards like the Pimoroni Tiny 2350.

github · torvalds · Jun 2, 15:51

**Background**: The RP2350 is Raspberry Pi's second microcontroller, released in August 2024, with dual Arm Cortex-M33 and optional RISC-V cores. Magnetic scroll wheels use Hall-effect sensors to detect rotation without physical contacts, offering smoother and more durable operation than mechanical encoders. The AS5600 sensor is commonly used for angular measurement in industrial settings and is repurposed here for a simple human interface.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/torvalds/ScrollWheel">Minimalist RP2350 magnetic sensor scroll wheel toy project</a></li>
<li><a href="https://en.wikipedia.org/wiki/RP2350">RP2350 - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#RP2350`, `#scroll wheel`, `#magnetic sensor`, `#embedded`, `#hobbyist`

---

<a id="item-21"></a>
## [Nostalgic Exploration of FidoNet Technology and History from 1993](https://www.fidonet.org/inet92_Randy_Bush.txt) ⭐️ 6.0/10

A 1993 document detailing FidoNet's technology, tools, and history has been shared, sparking a nostalgic discussion among early adopters. It highlights the pioneering role of FidoNet in pre-internet community networking, demonstrating that concepts like email, forums, and even social discovery predate the modern internet. FidoNet used a decentralized store-and-forward system for email and echomail between BBSes; node addresses like '2:463/1161' are still remembered by users.

hackernews · BruceEel · Jun 2, 13:53 · [Discussion](https://news.ycombinator.com/item?id=48370291)

**Background**: FidoNet was a global store-and-forward network that connected bulletin board systems (BBSes) via dial-up modems long before widespread internet access. By the mid-1990s, it had grown to nearly 40,000 nodes, enabling millions of users to exchange email and forum messages. Its popularity declined as low-cost internet connections became common, but it still exists in a smaller form today.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/FidoNet">FidoNet</a></li>

</ul>
</details>

**Discussion**: Commenters share nostalgic stories, such as a Turkish HitNet clone that served as an early social network, and note that many internet-like services (forums, mail, multiplayer games) existed on BBS networks. Some point out that FidoNet and similar alt nets like fsxNet are still active today.

**Tags**: `#retrocomputing`, `#history`, `#networking`, `#BBS`, `#FidoNet`

---

<a id="item-22"></a>
## [Pasted File Editor: Browser Tool for Large Text Paste as File Attachments](https://simonwillison.net/2026/Jun/2/pasted-file-editor/#atom-everything) ⭐️ 6.0/10

Simon Willison released a prototype browser tool that converts large text pastes into file attachments, inspired by Claude's similar functionality, and built using Codex desktop; it also supports image thumbnails and drag-and-drop. It showcases how AI-assisted coding tools like Codex enable rapid prototyping of useful utilities, potentially benefiting developers who handle large text inputs in web environments. The tool is built entirely in JavaScript, runs in the browser, and can open files (including images) directly or via drag-and-drop onto a textarea. It was prototyped with OpenAI's Codex desktop agent, as indicated by the linked Gist.

rss · Simon Willison · Jun 2, 04:13

**Background**: Claude, developed by Anthropic, is a conversational AI that can detect large text inputs and handle them as file attachments, improving usability for developers pasting code. OpenAI Codex is an AI coding agent that can generate and modify code based on prompts, with a desktop version that allows building applications locally. Simon Willison is a prominent developer and writer who frequently explores and shares experiments with AI-assisted programming.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_AI">Claude AI</a></li>
<li><a href="https://grokipedia.com/page/OpenAI_Codex">OpenAI Codex</a></li>

</ul>
</details>

**Tags**: `#javascript`, `#tools`, `#ai-assisted-programming`, `#claude`, `#codex`

---

<a id="item-23"></a>
## [Finetuning Reasoning LLMs with Tool-Calling: Supervised vs RL](https://www.reddit.com/r/MachineLearning/comments/1ttxcm5/finetuning_a_reasoning_llm_with_supervised_or/) ⭐️ 6.0/10

A Reddit user seeks guidance on whether to use supervised fine-tuning or reinforcement learning to train small LLMs on conversational data containing reasoning traces and tool-calling decisions. This addresses a practical challenge in building efficient, tool-using reasoning LLMs, which is critical for deploying smaller, cost-effective models in real-world applications. The user proposes splitting conversations into history-based samples with loss masking for assistant tokens during SFT, and asks about reward design for RL algorithms like PPO, GRPO, or DPO to improve tool-calling accuracy.

reddit · r/MachineLearning · /u/zdeneklapes · Jun 1, 16:23

**Background**: Reasoning traces are intermediate steps like chain-of-thought before the final answer, while tool-calling allows LLMs to invoke external functions. Supervised fine-tuning (SFT) trains on labeled data, and reinforcement learning (RL) uses rewards to shape behavior. Recent models like DeepSeek R1 use RL to develop reasoning skills, and SFT on reasoning traces can distill this into smaller models.

<details><summary>References</summary>
<ul>
<li><a href="https://magazine.sebastianraschka.com/p/understanding-reasoning-llms">Understanding Reasoning LLMs - by Sebastian Raschka, PhD</a></li>
<li><a href="https://arxiv.org/abs/2508.16695">Do Cognitively Interpretable Reasoning Traces Improve LLM ... Understanding Reasoning LLMs - by Sebastian Raschka, PhD Top Stories Do Cognitively Interpretable Reasoning Traces Improve LLM ... Demystifying Reasoning Models - by Cameron R. Wolfe, Ph.D. Verbal Reasoning Traces in LLMs - emergentmind.com Tracing the thoughts of a large language model \ Anthropic Chain-of-Thought Annotation: How Reasoning Traces Improve LLM ...</a></li>
<li><a href="https://arxiv.org/abs/2512.15943">Small Language Models for Efficient Agentic Tool Calling ... Fine Tuning SLMs on Agentic Tool Calling: An Experiment Images Fine-tuning function calls with Azure OpenAI in Microsoft ... GitHub - AlineFree/llm-tool-call-sft: Fine-tune tool ... Practical Guide to Finetuning Falcon H1 Tiny for Tool Calling ... Build your own tool-calling agent with TRL on Azure Machine ... Fine-tuning With Tool Calling - stephendiehl.com</a></li>

</ul>
</details>

**Tags**: `#fine-tuning`, `#reasoning-llms`, `#reinforcement-learning`, `#supervised-learning`, `#tool-use`

---

<a id="item-24"></a>
## [Chinese Electric Tricycles Surge in Exports, Priced $3000-$6000 Overseas](https://content-static.cctvnews.cctv.com/snow-book/index.html?toc_style_id=feeds_default&amp;item_id=5206220851671440944&amp;channelId=1119) ⭐️ 6.0/10

In 2025, Chinese electric two-wheeler exports surpassed 26.7 million units, with electric tricycles seeing particularly strong overseas demand; they are now selling for $3000-$6000 in the US and Europe, several times their domestic price. Manufacturers in Feng County have adopted flat wire motor technology, cutting energy use and costs while extending range and lifespan. This export boom highlights China's growing edge in affordable, green transportation and could disrupt the light utility vehicle market in developed nations, offering a cost-effective alternative to traditional pickups. It also signals the maturation of China's electric vehicle supply chain and technology. The flat wire motor improves efficiency, reduces energy consumption, extends battery range and motor life by two years, and lowers costs by 10%. Exports from Wuxi grew 14 percentage points faster than the national average for similar products in 2025, and logistics challenges like container shortages are emerging.

telegram · zaihuapd · Jun 2, 12:15

**Background**: Electric tricycles, commonly called 'san beng zi' in China, are small three-wheeled vehicles used for short-haul transport and light cargo. Flat wire motors use rectangular copper wires in the stator, allowing higher slot fill, better heat dissipation, and improved efficiency compared to traditional round wire motors. Jiangsu Feng County is the largest production hub for electric tricycle parts, controlling over 90% of the accessory market.

<details><summary>References</summary>
<ul>
<li><a href="https://lamnow.com/flat-wire-motor-vs-round-wire-motor/">Flat Wire Motor vs. Round Wire Motor - Lamnow</a></li>
<li><a href="https://www.aivon.com/blog/industrial-control/flat-wire-motor-stator-and-rotor-processes/">Flat-wire Motor Stator and Rotor Processes - aivon.com</a></li>

</ul>
</details>

**Tags**: `#electric vehicles`, `#exports`, `#manufacturing`, `#China`, `#trade`

---