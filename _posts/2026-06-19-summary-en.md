---
layout: default
title: "Horizon Summary: 2026-06-19 (EN)"
date: 2026-06-19
lang: en
---

> From 63 items, 24 important content pieces were selected

---

1. [Project Valhalla's Value Types Finally Land in JDK 28 After a Decade](#item-1) ⭐️ 9.0/10
2. [10,000+ GitHub Repositories Found Distributing Trojan Malware](#item-2) ⭐️ 9.0/10
3. [GLM-5.2 Released as Top Open Weights LLM with MIT License](#item-3) ⭐️ 9.0/10
4. [There Are No Instances in ATProto](#item-4) ⭐️ 8.0/10
5. [Amateur May Have Deciphered Linear A with AI Tools](#item-5) ⭐️ 8.0/10
6. [Bipartisan JAWBONE Act Targets Government Censorship of Speech](#item-6) ⭐️ 8.0/10
7. [Early Findings Suggest AI May Degrade Human Skills](#item-7) ⭐️ 8.0/10
8. [Datasette Apps: Host custom sandboxed HTML apps inside Datasette](#item-8) ⭐️ 8.0/10
9. [Safe GPU Inference in Rust: cuTile's Compiler-Verified Ownership Matches vLLM Speeds](#item-9) ⭐️ 8.0/10
10. [Hyundai Acquires Full Ownership of Boston Dynamics from SoftBank](#item-10) ⭐️ 7.0/10
11. [Google Workspace Context-Aware Access May Block Firefox Over DBSC](#item-11) ⭐️ 7.0/10
12. [datasette-acl 0.6a0 Expands to General Resource Sharing for Datasette](#item-12) ⭐️ 7.0/10
13. [GitHub Models Halts New User Sign-ups, Existing Users Unaffected](#item-13) ⭐️ 7.0/10
14. [Zhipu Founder Claims Model Could Hit Anthropic's Mythos Level Before Q1 2026](#item-14) ⭐️ 7.0/10
15. [US Pressures ASML, Says Top EUV Machine May Have Reached China](#item-15) ⭐️ 7.0/10
16. [Google Adds 24-Hour Wait to Sideloading Unverified Android Apps](#item-16) ⭐️ 7.0/10
17. [Apple to Allow Third-Party App Stores and External Payments in Brazil](#item-17) ⭐️ 7.0/10
18. [Developer Reimplements torch.compile in 500 Lines to Explain Operator Fusion](#item-18) ⭐️ 6.0/10
19. [Voice Debugging at Conversation Level More Useful Than Isolated Metrics](#item-19) ⭐️ 6.0/10
20. [Reddit User Questions Whether ACL Has Become Irrelevant for PhD Applications](#item-20) ⭐️ 6.0/10
21. [China's CAC Proposes Regulations for Interoperable Distributed Digital Identity](#item-21) ⭐️ 6.0/10
22. [Sanders Proposes $1,000 Annual AI Dividend for Americans](#item-22) ⭐️ 6.0/10
23. [India Temporarily Blocks Telegram for Exam, VPN Signups Spike 150%](#item-23) ⭐️ 6.0/10
24. [Ex-PhD Student Accuses Beihang Professors of Data Fabrication in Nature Paper](#item-24) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Project Valhalla's Value Types Finally Land in JDK 28 After a Decade](https://www.jvm-weekly.com/p/project-valhalla-explained-how-a) ⭐️ 9.0/10

After a decade of development, Project Valhalla's value types are now included in JDK 28, enabling developers to define value classes that are stored inline without object headers, improving memory layout and performance. This marks a fundamental shift in Java's object model, closing the gap with languages like C# and C++ that have had value types, and significantly boosts performance for numerical computing and data-oriented workloads. The initial delivery does not include full heap flattening for large value types above 64 bits, and the implementation is complex, requiring careful coding to avoid null-related issues. Value types are immutable and non-nullable by default, and arrays of values will be flat-packed.

hackernews · philonoist · Jun 19, 06:35 · [Discussion](https://news.ycombinator.com/item?id=48595511)

**Background**: Project Valhalla is a long-running OpenJDK initiative that began around 2014 with the goal of introducing value types to Java. In Java, all objects are reference types, meaning they are accessed via pointers and stored on the heap with memory overhead like object headers. Value types, in contrast, are passed by value and can be stored directly in arrays or on the stack, avoiding indirection and improving cache locality. This feature has been highly anticipated as it enables more efficient memory usage and better performance, similar to structs in C or value types in C#.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Project_Valhalla_(Java_language)">Project Valhalla (Java language) - Wikipedia</a></li>
<li><a href="https://openjdk.org/projects/valhalla/">Project Valhalla</a></li>

</ul>
</details>

**Discussion**: Community reactions are mixed but generally appreciative of the decade-long effort. Some developers criticize the limitations, such as the lack of heap flattening for larger value types and the decision to avoid null-safety debates. Others praise the design consolidation and note Java's catch-up journey after years of neglect.

**Tags**: `#java`, `#jvm`, `#value-types`, `#performance`, `#language-design`

---

<a id="item-2"></a>
## [10,000+ GitHub Repositories Found Distributing Trojan Malware](https://orchidfiles.com/github-repositories-distributing-malware/) ⭐️ 9.0/10

A security researcher discovered over 10,000 GitHub repositories that actively distribute Trojan malware, likely designed to infect AI coding agents that automatically pull dependencies. This attack exploits the software supply chain, threatening the rapidly growing use of AI coding assistants that blindly trust open-source code, and could lead to widespread compromises during a year of major elections. The Trojanized repositories mimic legitimate projects, frequently delete and push commits to appear in 'Last Updated' searches, and target AI agents that automate dependency resolution, potentially bypassing human review.

hackernews · theorchid · Jun 18, 11:45 · [Discussion](https://news.ycombinator.com/item?id=48583928)

**Background**: Supply chain attacks compromise less secure elements in an ecosystem to infiltrate targets. GitHub is a major platform for open-source code, often used by AI coding agents like Claude Code, Cursor, and Copilot to fetch libraries. These agents can automatically add dependencies without human oversight, making them vulnerable to malicious repositories.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Supply_chain_attack">Supply chain attack</a></li>
<li><a href="https://www.faros.ai/blog/best-ai-coding-agents-2026">Best AI Coding Agents for 2026: Real-World Developer Reviews</a></li>

</ul>
</details>

**Discussion**: Community comments highlight that the attack targets AI agents by exploiting commit frequency to boost search visibility, with some users reporting impersonation of their projects. There is concern about agents blindly trusting code, referencing a Disney engineer who downloaded a malicious AI tool from GitHub. The timing coincides with major elections and the rise of coding agents.

**Tags**: `#security`, `#malware`, `#github`, `#supply-chain`, `#AI-agents`

---

<a id="item-3"></a>
## [GLM-5.2 Released as Top Open Weights LLM with MIT License](https://simonwillison.net/2026/Jun/17/glm-52/#atom-everything) ⭐️ 9.0/10

Z.ai released GLM-5.2, a 753B parameter Mixture of Experts text-only model with a 1 million token context window, under an MIT license on June 16, 2026. It reportedly tops independent open weights benchmarks, including the Artificial Analysis Intelligence Index. GLM-5.2 sets a new state-of-the-art for open weights models, surpassing competitors like MiniMax-M3 and DeepSeek V4 Pro. Its MIT license allows unrestricted commercial use and modification, accelerating innovation and lowering barriers for AI development. The model uses only 40 active experts per forward pass, but is notably token-hungry with 43k output tokens per benchmark task. It ranks second on the Code Arena WebDev leaderboard despite being text-only, and is available via OpenRouter at $1.40/M input and $4.40/M output tokens.

rss · Simon Willison · Jun 17, 23:58

**Background**: Mixture of Experts (MoE) is a machine learning technique where multiple specialized subnetworks (experts) handle different parts of the input, with only a subset active at a time, enabling larger models with lower computational cost. Open weights models provide downloadable pre-trained parameters for inference and fine-tuning, but unlike fully open source models, they may not include training code or data.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mixture_of_experts">Mixture of experts - Wikipedia</a></li>
<li><a href="https://huggingface.co/blog/moe">Mixture of Experts Explained</a></li>
<li><a href="https://promptengineering.org/llm-open-source-vs-open-weights-vs-restricted-weights/">Openness in Language Models: Open Source vs Open Weights vs Restricted Weights</a></li>

</ul>
</details>

**Tags**: `#GLM-5.2`, `#open-weights`, `#large-language-model`, `#MIT-license`, `#AI-release`

---

<a id="item-4"></a>
## [There Are No Instances in ATProto](https://overreacted.io/there-are-no-instances-in-atproto/) ⭐️ 8.0/10

Dan Abramov published an article explaining that ATProto, unlike ActivityPub-based Mastodon, does not have instances but relies on a relay-based architecture with separate Personal Data Servers, Relays, and AppViews. This clarification addresses common misconceptions among decentralized social media users and highlights the architectural trade-offs in protocol design, influencing how developers and users understand federation, scalability, and user agency. In ATProto, users write to a canonical Personal Data Server (PDS); Relays aggregate and stream data; and AppViews consume this data. The modular design separates scaling concerns, but critics argue that expensive Relays introduce centralization risks.

hackernews · danabramov · Jun 19, 15:10 · [Discussion](https://news.ycombinator.com/item?id=48599515)

**Background**: ATProto is the protocol behind Bluesky, a decentralized social network, while Mastodon uses ActivityPub with a model of independent instances that each host users and federate content. In Mastodon, instances are self-contained servers with their own moderation; ATProto decouples identity, storage, and application logic, so there is no direct equivalent of an instance.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Atproto">Atproto</a></li>
<li><a href="https://en.wikipedia.org/wiki/AT_Protocol">AT Protocol - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Community reactions were mixed. Some praised the separation of services as elegant, while others criticized the analogy to RSS and argued that ATProto’s reliance on expensive Relays makes it less decentralized than claimed, with the PDS acting as a canonical server in a client-server model rather than true peer-to-peer.

**Tags**: `#decentralized-web`, `#atproto`, `#bluesky`, `#architecture`, `#protocol-design`

---

<a id="item-5"></a>
## [Amateur May Have Deciphered Linear A with AI Tools](https://aiclambake.com/clamtakes/linear-a/) ⭐️ 8.0/10

An amateur linguist, using AI-assisted tools built with Claude Code, claims to have deciphered the ancient script Linear A, producing translations for over 300 words—a first in the 120-year history of the puzzle. The work is currently under review by linguistics experts at Rutgers and Cambridge. If validated, this would crack one of the most enduring mysteries in ancient languages, potentially unlocking Minoan civilization and culture. It also highlights how AI tools can accelerate hypothesis testing in linguistic decipherment on extremely small datasets. The decipherment relies on systematic analysis of the 'Libation Formula,' the only recurring phrase in the fragmentary Linear A corpus, which consists of just ~7,500 characters across ~1,500 inscriptions. The approach uses Python scripts for cross-referencing digitized texts, not a black-box 'AI solution,' and the translations are pending expert validation.

hackernews · Kosturdistan · Jun 19, 16:04 · [Discussion](https://news.ycombinator.com/item?id=48600107)

**Background**: Linear A is a syllabic script used by the Minoan civilization on Crete from about 1800 to 1450 BC. It remains undeciphered despite sharing many symbols with Linear B, which was cracked in the 1950s and found to represent Mycenaean Greek. The extremely small corpus—roughly 7,500 characters—makes decipherment challenging, as there is insufficient text for traditional cryptographic methods. Previous claims of decipherment have all failed peer review.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Linear_A">Linear A</a></li>
<li><a href="https://www.britannica.com/topic/Linear-A">Linear A and Linear B | Mycenaean, Minoan & Decipherment | Britannica</a></li>

</ul>
</details>

**Discussion**: The community is cautiously optimistic; many note that the work's credibility is boosted by expert review and the use of AI to build analysis tools rather than as a black box. However, some emphasize the tiny corpus size, and all await confirmation from specialists.

**Tags**: `#linear-a`, `#decipherment`, `#ai-tools`, `#linguistics`, `#ancient-languages`

---

<a id="item-6"></a>
## [Bipartisan JAWBONE Act Targets Government Censorship of Speech](https://www.eff.org/deeplinks/2026/06/new-bill-takes-aim-government-pressure-silence-lawful-online-speech) ⭐️ 8.0/10

The bipartisan JAWBONE Act, introduced by Senators Ted Cruz and Ron Wyden, aims to prohibit federal agencies from coercing broadcasters, AI companies, and online platforms into censoring lawful speech, and creates a private right of action for victims. This bill addresses the escalating problem of government jawboning—informal pressure on intermediaries to censor speech without due process—potentially safeguarding online free speech and setting a precedent against unconstitutional coercion. The bill covers broadcasters, AI firms, and online platforms; it creates a cause of action even if censorship attempts fail. The ACLU and EFF have endorsed it.

hackernews · hn_acker · Jun 19, 17:34 · [Discussion](https://news.ycombinator.com/item?id=48600950)

**Background**: Jawboning refers to informal government pressure on private intermediaries to censor speech, which can circumvent First Amendment protections. The JAWBONE Act stands for Justice Against Weaponized Bureaucratic Overreach to Networked Expression. It responds to concerns about federal agencies pushing platforms to suppress lawful but controversial content.

<details><summary>References</summary>
<ul>
<li><a href="https://www.aclu.org/press-releases/aclu-endorses-bipartisan-jawbone-act-to-protect-free-speech">ACLU Endorses Bipartisan JAWBONE Act To Protect Free Speech</a></li>
<li><a href="https://reason.com/2026/06/17/bipartisan-jawbone-act-targets-government-censorship-threats/">Bipartisan JAWBONE Act targets government censorship threats</a></li>

</ul>
</details>

**Discussion**: Many commenters appreciate the bipartisan nature and the clever acronym, but some express skepticism toward Ted Cruz due to his past support for anti-BDS laws that restrict speech. Others note the irony that the government might hoist itself on its own petard, with overall cautious optimism mixed with concerns about contradictions.

**Tags**: `#free-speech`, `#government-overreach`, `#jawbone-act`, `#eff`, `#legislation`

---

<a id="item-7"></a>
## [Early Findings Suggest AI May Degrade Human Skills](https://www.nature.com/articles/d41586-026-01947-1) ⭐️ 8.0/10

A Nature article reports early research suggesting that using AI tools may impair human cognitive skills, such as critical thinking and problem-solving, as users increasingly rely on AI for tasks they previously performed independently. This trend raises concerns about long-term human skill atrophy and the potential for widespread cognitive offloading, which could fundamentally alter how we think and learn, especially as AI assistants become ubiquitous in professional and everyday settings. Notable early findings include doctors becoming less proficient at interpreting medical images when assisted by AI, and programmers losing low-level coding skills while perhaps gaining architectural overview abilities.

hackernews · Michelangelo11 · Jun 19, 18:00 · [Discussion](https://news.ycombinator.com/item?id=48601286)

**Background**: Cognitive offloading refers to the use of external tools to reduce mental effort, like using GPS instead of spatial memory. Historically, technology has both enhanced and replaced human skills. The current wave of generative AI presents a unique case due to its ability to perform complex cognitive tasks across many domains simultaneously.

**Discussion**: Commenters on Hacker News debated the analogy to delegation in high-status jobs, noting that AI's scope is unprecedented, potentially seductive and enfeebling. Some shared personal experiences of skill loss balanced by higher-level thinking, while others emphasized that AI is a lever that can enable laziness or incredible productivity, depending on individual choice.

**Tags**: `#AI`, `#cognitive skills`, `#offloading`, `#human-AI interaction`, `#critical thinking`

---

<a id="item-8"></a>
## [Datasette Apps: Host custom sandboxed HTML apps inside Datasette](https://simonwillison.net/2026/Jun/18/datasette-apps/#atom-everything) ⭐️ 8.0/10

Simon Willison launched the datasette-apps plugin, enabling users to host self-contained HTML and JavaScript applications inside Datasette's sandboxed iframe, with read-only SQL access and optional write queries via stored queries. This transforms Datasette from a data publishing tool into a secure platform for interactive data applications, opening the door to customizable, embeddable tools while keeping user data safe from malicious code. The iframe uses sandbox="allow-scripts allow-forms" and an injected Content Security Policy to block external network requests, cookie access, and localStorage, with no allow-same-origin. Apps run read-only SQL by default; write queries require explicit configuration via stored SQL queries.

rss · Simon Willison · Jun 18, 23:58

**Background**: Datasette is an open-source tool for publishing SQLite databases as interactive websites with a JSON API. It already supported plugins to extend features, but creating rich custom interfaces often meant building external apps. The new plugin leverages iframe sandboxing and CSP to safely embed user-created or AI-generated HTML/JS apps directly within Datasette, preventing data exfiltration and other security risks while allowing flexible, self-contained applications.

<details><summary>References</summary>
<ul>
<li><a href="https://www.w3schools.com/tags/att_iframe_sandbox.asp">HTML iframe sandbox Attribute</a></li>
<li><a href="https://web.dev/articles/sandboxed-iframes">Play safely in sandboxed IFrames | Articles | web.dev</a></li>

</ul>
</details>

**Tags**: `#datasette`, `#plugins`, `#web-development`, `#sql`, `#sandboxed-applications`

---

<a id="item-9"></a>
## [Safe GPU Inference in Rust: cuTile's Compiler-Verified Ownership Matches vLLM Speeds](https://www.reddit.com/r/MachineLearning/comments/1u9j7md/fearless_concurrency_on_the_gpu_safe_gpu/) ⭐️ 8.0/10

cuTile Rust, a new tile-based GPU programming DSL, uses Rust's ownership model to achieve compiler-verified memory safety and data-race freedom for GPU kernels. The authors have also released Grout, a Qwen3 inference engine built on cuTile Rust that delivers competitive LLM inference throughput—171 tok/s for Qwen3-4B on an RTX 5090 and 82 tok/s for Qwen3-32B on a B200—matching vLLM and SGLang at batch-1 decode. As AI-generated GPU code becomes more prevalent, trust becomes critical. cuTile Rust eliminates entire classes of bugs (race conditions, memory errors) at compile time, making it especially valuable for safety-critical or automatically synthesized kernels. The performance being competitive with established inference engines shows that safety does not have to come at the cost of speed. cuTile Rust lowers to NVIDIA's CUDA Tile IR, extending Rust's ownership across the kernel launch boundary. The safe GEMM kernel is within 0.3% of a hand-written low-level version, and element-wise operations reach ~7 TB/s. Caveats: Grout only supports batch-1 inference and a limited set of models, is NVIDIA-only, and GEMM slightly trails cuBLAS at some problem sizes.

reddit · r/MachineLearning · /u/Exciting_Suspect9088 · Jun 18, 21:36

**Background**: Rust's ownership system enforces memory safety and prevents data races at compile time without garbage collection, traditionally for CPU code. GPUs present new challenges due to massively parallel execution and complex memory hierarchies. CUDA Tile IR is an intermediate representation that models the GPU as a tile-based processor, enabling efficient kernel optimization. vLLM and SGLang are popular high-performance serving systems for large language models.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/NVIDIA/cuda-tile">GitHub - NVIDIA/cuda-tile: CUDA Tile IR is an MLIR-based ...</a></li>
<li><a href="https://docs.nvidia.com/cuda/tile-ir/latest/index.html">Tile IR — Tile IR - NVIDIA Documentation Hub</a></li>

</ul>
</details>

**Tags**: `#rust`, `#gpu-programming`, `#memory-safety`, `#llm-inference`, `#hpc`

---

<a id="item-10"></a>
## [Hyundai Acquires Full Ownership of Boston Dynamics from SoftBank](https://startupfortune.com/hyundai-takes-full-control-of-boston-dynamics-as-softbank-exits-for-325-million/) ⭐️ 7.0/10

Hyundai Motor Group has purchased the remaining stake in Boston Dynamics from SoftBank for $325 million, giving it 100% ownership of the robotics pioneer. This completes the acquisition that began in December 2020 when Hyundai bought an 80% controlling interest. The full acquisition strengthens Hyundai's position in advanced robotics beyond automotive manufacturing, aligning with its push into AI and autonomous systems. It also reflects growing strategic interest in robotics by automakers, possibly to address labor shortages and future mobility. The deal exercises a put option from the original 2020 agreement, where Hyundai paid $880 million for 80% of the company. Despite owning Atlas, one of the most advanced humanoid robots, Hyundai acknowledges it is not yet ready for deployment in car factories.

hackernews · ck2 · Jun 19, 16:28 · [Discussion](https://news.ycombinator.com/item?id=48600312)

**Background**: Boston Dynamics, founded in 1992, is known for highly dynamic robots like Spot and Atlas. SoftBank acquired it from Google in 2017 before selling it to Hyundai. Hyundai views robotics as a key component of future mobility, alongside autonomous vehicles and urban air mobility.

**Discussion**: Comments reflect a mix of strategic analysis and skepticism. Some question the practicality of humanoid robots over specialized designs, while others link the move to South Korea's declining workforce. There is also acknowledgement that Atlas is not yet factory-ready, but could find applications in areas like space exploration.

**Tags**: `#robotics`, `#merger-and-acquisition`, `#Hyundai`, `#Boston-Dynamics`, `#humanoid-robots`

---

<a id="item-11"></a>
## [Google Workspace Context-Aware Access May Block Firefox Over DBSC](https://tales.fromprod.com/2026/169/google-workspace-threatening-to-block-firefox.html) ⭐️ 7.0/10

Google Workspace's Context-Aware Access feature, configurable by enterprise administrators, may block Firefox users because Firefox lacks hardware-backed Device Bound Session Credentials (DBSC), a security mechanism currently only supported in Chrome. The potential block has sparked debate about browser compatibility and anti-competitive practices. This highlights the tension between enterprise security requirements and browser diversity, as DBSC enforcement could effectively force users onto Chrome, raising antitrust concerns and impacting the open web ecosystem. It underscores how a configurable security feature can be mistaken for a broad policy, amplifying fears about Google's power. DBSC uses hardware-backed cryptography, such as a Trusted Platform Module (TPM), to bind session cookies to a device, making them useless if stolen. The blocking only occurs if an organization's admin explicitly enables the DBSC requirement in Context-Aware Access policies.

hackernews · birdculture · Jun 19, 16:30 · [Discussion](https://news.ycombinator.com/item?id=48600345)

**Background**: Context-Aware Access is a Google Workspace security product that lets admins set granular access controls based on device security posture, location, and other attributes. Device Bound Session Credentials (DBSC) is a Google-developed mechanism to prevent session theft by tying authentication tokens to device hardware, initially rolled out in Chrome to combat malware-based cookie theft. Firefox has not implemented DBSC, making it incompatible with policies that require it.

<details><summary>References</summary>
<ul>
<li><a href="https://knowledge.workspace.google.com/admin/security/about-context-aware-access">About Context-Aware Access | Security & data protection ...</a></li>
<li><a href="https://developer.chrome.com/docs/web-platform/device-bound-session-credentials">Device Bound Session Credentials (DBSC) | Web Platform | Chrome for Developers</a></li>
<li><a href="https://blog.google/security/protecting-cookies-with-device-bound-session-credentials/">Protecting Cookies with Device Bound Session Credentials</a></li>

</ul>
</details>

**Discussion**: Community comments clarify that this is not a Google-wide ban but a configurable enterprise security feature, urging the original poster to address their IT department. Some express concerns about browser detection and user-agent spoofing, while others note that Google slowly normalizes such changes to avoid backlash, ultimately forcing users onto Chrome.

**Tags**: `#browser-compatibility`, `#google-workspace`, `#firefox`, `#web-security`, `#context-aware-access`

---

<a id="item-12"></a>
## [datasette-acl 0.6a0 Expands to General Resource Sharing for Datasette](https://simonwillison.net/2026/Jun/18/datasette-acl/#atom-everything) ⭐️ 7.0/10

This release expands datasette-acl from table-only permissions to a general resource-sharing system, allowing fine-grained control over access to various resources in multi-user Datasette instances. It enables multi-user Datasette instances to securely share data and other resources with precisely defined permissions, making Datasette more viable for collaborative and production use cases. Alex Garcia performed most of the implementation. The release is version 0.6a0, indicating it is an alpha release with potential instability. Previously limited to table-level permissions, the plugin now treats any Datasette resource as an access-controlled entity.

rss · Simon Willison · Jun 18, 19:03

**Background**: Datasette is an open-source tool for exploring and publishing data, often used to share SQLite databases on the web. It supports plugins, and datasette-acl is a plugin that adds access control lists (ACL) to manage user permissions. The plugin is essential for scenarios where multiple users need different levels of access to the same Datasette instance. This update builds on earlier versions by moving beyond table-level permissions to encompass all resource types within Datasette.

**Tags**: `#datasette`, `#datasette-acl`, `#access-control`, `#acl`, `#python`

---

<a id="item-13"></a>
## [GitHub Models Halts New User Sign-ups, Existing Users Unaffected](https://github.blog/changelog/2026-06-16-github-models-is-no-longer-available-to-new-customers/) ⭐️ 7.0/10

GitHub Models has stopped accepting new customers as of June 16, 2026, and is beginning its retirement process. Existing users can continue using the service, but new organizations cannot access it. This marks the beginning of the end for GitHub's AI model playground, impacting developers who rely on it for prototyping and inference. It pushes new projects toward Azure AI Foundry, consolidating Microsoft's AI platform strategy. The restriction applies to free and paid plans, covering the Playground, API, and model access. A detailed retirement timeline will be announced later, with Azure AI Foundry recommended as the migration target.

telegram · zaihuapd · Jun 19, 00:54

**Background**: GitHub Models is a platform for prototyping and experimenting with AI models from various providers via a web-based playground and API, tightly integrated with GitHub repositories. Azure AI Foundry (formerly Azure AI Studio) is Microsoft's unified AI platform for building and deploying AI applications and agents.

<details><summary>References</summary>
<ul>
<li><a href="https://grokipedia.com/page/GitHub_Models">GitHub Models</a></li>
<li><a href="https://azure.microsoft.com/en-us/products/ai-foundry">Microsoft Foundry | Microsoft Azure</a></li>

</ul>
</details>

**Tags**: `#GitHub`, `#AI`, `#deprecation`, `#Azure`, `#cloud services`

---

<a id="item-14"></a>
## [Zhipu Founder Claims Model Could Hit Anthropic's Mythos Level Before Q1 2026](https://x.com/jietang/status/2067580270078030088) ⭐️ 7.0/10

Zhipu founder Tang Jie asserted on X that the company's models could achieve Anthropic's Mythos-level capabilities before the first quarter of next year, directly countering Elon Musk's estimate of Q1 2027. This claim highlights the intensifying US-China AI race, with Chinese firms aggressively aiming to close the gap with leading Western AI labs. If achieved, it would mark a major milestone in China's ability to develop frontier-level AI models. The comparison hinges on equating GLM-5.2's performance roughly to Claude Opus 4.7/4.8, suggesting about a 7-month lag behind the US. Mythos-level models represent a significant leap beyond Opus, with Anthropic only recently releasing a public version after initial safety assessments.

telegram · zaihuapd · Jun 19, 02:24

**Background**: Anthropic's "Mythos" tier denotes models with capabilities so advanced they require extra safeguards for domains like cybersecurity and biology. Claude Mythos 5, released in mid-2025, is a safer version of the restricted Claude Fable 5. Zhipu's GLM-5.2, announced recently, is an open-source model focused on long-horizon tasks and agentic coding, positioned between Claude Opus 4.7 and 4.8.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/claude/mythos">Claude Mythos \ Anthropic</a></li>
<li><a href="https://www.anthropic.com/news/claude-fable-5-mythos-5">Claude Fable 5 and Claude Mythos 5 \ Anthropic</a></li>
<li><a href="https://z.ai/blog/glm-5.2">GLM-5.2: Built for Long-Horizon Tasks - z.ai</a></li>

</ul>
</details>

**Discussion**: The online exchange sparked debate on timelines, with some users siding with Musk's cautious projection while others praised Tang's confidence. Many acknowledged the rapid progress of Chinese AI but questioned whether safety and alignment considerations might slow the release of such powerful models.

**Tags**: `#AI`, `#LLM`, `#China AI`, `#Anthropic`, `#Elon Musk`

---

<a id="item-15"></a>
## [US Pressures ASML, Says Top EUV Machine May Have Reached China](https://www.bloomberg.com/news/articles/2026-06-19/us-tells-asml-it-s-concerned-china-may-have-top-chip-tool) ⭐️ 7.0/10

U.S. Commerce Secretary Howard Lutnick recently expressed concerns to ASML executives that a top-tier extreme ultraviolet (EUV) lithography machine may have reached China in violation of export controls. ASML has firmly denied this, stating it has never exported a complete EUV system to China. This escalation could intensify U.S.-Europe tensions over chip export controls and may influence proposed stricter U.S. legislation on equipment sales to China. It also highlights the strategic importance of EUV technology, which is critical for advanced semiconductor manufacturing and has implications for AI and high-performance computing hardware availability. ASML claims that none of its 314 operational EUV machines are in China, and it has circulated documents to prove its innocence. However, U.S. officials cited evidence of ASML shipping EUV-related transport equipment to China but refused to provide details, while ASML countered that it never exported any EUV-specific components.

telegram · zaihuapd · Jun 19, 03:09

**Background**: Extreme ultraviolet lithography (EUV) is a cutting-edge technology used to produce the most advanced semiconductor chips, enabling features down to 3 nm and below. ASML is the world's sole supplier of EUV systems, which are essential for manufacturing high-performance processors and AI accelerators. Since 2019, the U.S. has pressured the Netherlands to restrict ASML's exports to China, preventing Chinese firms from acquiring EUV tools to slow their chipmaking progress.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/EUV_lithography">EUV lithography</a></li>
<li><a href="https://www.asml.com/en/products/euv-lithography-systems">EUV lithography systems – Products | ASML</a></li>

</ul>
</details>

**Tags**: `#semiconductors`, `#export controls`, `#ASML`, `#EUV lithography`, `#US-China trade`

---

<a id="item-16"></a>
## [Google Adds 24-Hour Wait to Sideloading Unverified Android Apps](https://t.me/zaihuapd/42054) ⭐️ 7.0/10

Google introduced an advanced sideloading flow for unverified Android apps that mandates a 24-hour waiting period. Users must enable Developer Options, confirm they are not under coercion, restart, re-verify identity with biometrics or PIN, and wait one day before installation. This high-friction process is designed to prevent scams by disrupting social engineering attacks that trick users into installing malicious software. It significantly changes the sideloading experience, affecting power users, alternative app stores, and the broader Android security ecosystem. The 24-hour wait is a one-time step; afterward, users can set the sideloading permission for 7 days or indefinitely. The flow includes multiple identity checks and anti-coercion confirmations, and builds on last year's developer verification requirement involving a $25 fee and ID submission.

telegram · zaihuapd · Jun 19, 07:59

**Background**: Sideloading on Android refers to installing apps outside the Google Play Store, typically via APK files. Previously, users could simply enable 'Allow from this source.' In response to rising scams, Google has been tightening security through Play Protect scanning and now developer verification.

<details><summary>References</summary>
<ul>
<li><a href="https://hackaday.com/2026/03/20/google-unveils-new-process-for-installing-unverified-android-apps/">Google Unveils New Process For Installing Unverified Android Apps | Hackaday</a></li>
<li><a href="https://www.theregister.com/2026/03/19/google_android_unverified_apps/">Google creates installation path for unverified Android apps • The Register</a></li>
<li><a href="https://android-developers.googleblog.com/2026/03/android-developer-verification.html">Android Developers Blog: Android developer verification: Balancing openness and choice with safety</a></li>

</ul>
</details>

**Tags**: `#Android`, `#sideloading`, `#security`, `#mobile-development`, `#Google`

---

<a id="item-17"></a>
## [Apple to Allow Third-Party App Stores and External Payments in Brazil](https://t.me/zaihuapd/42059) ⭐️ 7.0/10

Apple reached an antitrust agreement with Brazil's regulator to allow iPhone users to install apps from third-party stores and use external payment methods, with changes required within 105 days. This marks a significant regulatory shift in a major market, potentially influencing antitrust actions in other countries and challenging Apple's tightly controlled App Store model, which has been a source of high commissions and developer disputes. The agreement gives developers the ability to display external payment links and decouples Apple's payment system from the App Store, though Apple may still charge fees on transactions. The deal lasts three years.

telegram · zaihuapd · Jun 19, 11:15

**Background**: Apple has historically required all iOS app downloads to go through its App Store and use its own payment system, charging up to 30% commission. This has drawn scrutiny from regulators worldwide, including the EU's Digital Markets Act which forced similar changes in Europe in 2024. Brazil's antitrust authority, CADE, has been investigating Apple for anti-competitive practices, and this agreement resolves that investigation.

**Tags**: `#Apple`, `#App Store`, `#antitrust`, `#Brazil`, `#regulation`

---

<a id="item-18"></a>
## [Developer Reimplements torch.compile in 500 Lines to Explain Operator Fusion](https://www.reddit.com/r/MachineLearning/comments/1ua2hwj/how_does_torchcompile_achieve_massive_speedups/) ⭐️ 6.0/10

A developer has shared a minimal 500-line Python reimplementation of torch.compile along with a notebook, illustrating how operator fusion drives its speedups. This educational resource clarifies how operator fusion works in PyTorch, helping practitioners understand a key optimization technique and potentially lowering the barrier to experimenting with custom fusion passes. The tiny implementation focuses solely on operator fusion, omitting many complexities of the real torch.compile, and serves as a learning tool rather than a production replacement.

reddit · r/MachineLearning · /u/Other-Eye-8152 · Jun 19, 13:47

**Background**: Operator fusion merges multiple operations into a single GPU kernel to reduce costly off-chip memory accesses and improve performance. torch.compile is a JIT compiler introduced in PyTorch 2.0 that automatically applies such fusions and other optimizations. Previously, developers had to hand-tune low-level kernels for similar gains.

<details><summary>References</summary>
<ul>
<li><a href="https://dl.acm.org/doi/10.1145/3520142">Optimus: An Operator Fusion Framework for Deep Neural Networks | ACM Transactions on Embedded Computing Systems</a></li>
<li><a href="https://docs.pytorch.org/tutorials/intermediate/torch_compile_tutorial.html">Introduction to torch.compile — PyTorch Tutorials 2.12.0+cu130 documentation</a></li>

</ul>
</details>

**Tags**: `#PyTorch`, `#torch.compile`, `#Operator Fusion`, `#Performance Optimization`, `#Educational`

---

<a id="item-19"></a>
## [Voice Debugging at Conversation Level More Useful Than Isolated Metrics](https://www.reddit.com/r/MachineLearning/comments/1u99fe5/voice_debugging_at_the_conversation_level_seems/) ⭐️ 6.0/10

A developer shares that conversation-level debugging reveals emergent interaction issues like timing friction and unnatural turn-taking, which isolated benchmark metrics miss, and is exploring automated QA to scale manual review of conversational traces. This insight highlights a critical gap in current evaluation approaches for voice AI, where reliance on component-level metrics can lead to systems that frustrate users in multi-turn interactions, potentially impacting user adoption and satisfaction. Notable issues include accumulated timing mistakes, repetition from confirmations, and changes in user behavior due to slight turn-taking errors. The shift to pattern-focused debugging and automated QA addresses the scaling challenges of manual review.

reddit · r/MachineLearning · /u/OwlZealousideal4779 · Jun 18, 15:29

**Background**: Voice AI systems blend speech recognition, language understanding, and synthesis, traditionally evaluated with separate metrics like word error rate and task completion. In multi-turn conversations, emergent properties from the interaction flow—such as timing and turn-taking dynamics—require monitoring beyond single-shot tests. Industry tools like Hamming and Maxim now offer conversation-level observability, reflecting a growing recognition of this need.

<details><summary>References</summary>
<ul>
<li><a href="https://hamming.ai/resources/debugging-voice-agents-real-time-logs-missed-intents-error-dashboards">Debugging Voice Agents: Real-Time Logs, Missed Intents ...</a></li>
<li><a href="https://maxim-articles.ghost.io/top-5-platforms-for-debugging-voice-agents/">Top 5 platforms for debugging voice agents</a></li>
<li><a href="https://www.crescendo.ai/blog/ai-automated-quality-assurance">8 Top AI-Powered Automated Quality Assurance in 2026</a></li>

</ul>
</details>

**Tags**: `#voice AI`, `#conversational AI`, `#evaluation metrics`, `#debugging`, `#speech systems`

---

<a id="item-20"></a>
## [Reddit User Questions Whether ACL Has Become Irrelevant for PhD Applications](https://www.reddit.com/r/MachineLearning/comments/1u945j5/is_acl_now_irrelevant_d/) ⭐️ 6.0/10

A Reddit user expressed shock upon reading that a first-author paper at the ACL conference is now viewed as a weak signal for PhD applications in natural language processing, despite ACL being a top-tier A+ venue. This discussion highlights a potential shift in how academic conferences are valued in AI-related PhD admissions, with larger machine learning venues like NeurIPS, ICML, and ICLR gaining more influence, which may disadvantage researchers in specialized NLP venues. The claim originated from a comment on another Reddit post and is not backed by quantitative data. The user questions whether this reflects a genuine trend or just 'ragebait'.

reddit · r/MachineLearning · /u/H4RZ3RK4S3 · Jun 18, 11:52

**Background**: ACL (Association for Computational Linguistics) is the flagship conference for NLP research, traditionally rated as an A+ venue. In recent years, AI conferences such as NeurIPS, ICML, and ICLR have grown dramatically in size and prestige, often attracting more attention from PhD admissions committees due to their broader machine learning focus.

<details><summary>References</summary>
<ul>
<li><a href="https://medium.com/@sarthakanand/what-is-it-like-to-attend-an-acl-conference-for-the-first-time-576e2e9741c5">What is it like to attend an ACL conference for the first time | Medium</a></li>
<li><a href="https://www.aclweb.org/archive/reports/HovyReport.html">The Hovy/McCoy Report</a></li>

</ul>
</details>

**Tags**: `#ACL`, `#NLP`, `#academic conferences`, `#PhD applications`, `#machine learning community`

---

<a id="item-21"></a>
## [China's CAC Proposes Regulations for Interoperable Distributed Digital Identity](https://www.cac.gov.cn/2026-06/18/c_1783525605384124.htm) ⭐️ 6.0/10

The Cyberspace Administration of China released draft regulations for a blockchain-based distributed digital identity system, aiming to enable cross-sector interoperability and user-controlled identity management, with public comment open until July 18, 2026. This regulation could establish a standardized, self-sovereign identity infrastructure across China, enhancing privacy and security while streamlining access to services like finance and digital currency. The draft specifies that distributed digital identity consists of identifiers, keys, verifiable credentials, and verifiable statements, based on blockchain, and will be implemented on a national identity chain across multiple government sectors.

telegram · zaihuapd · Jun 19, 01:39

**Background**: Distributed digital identity (DID) allows individuals to control their own identity data without relying on a central authority. It typically uses blockchain to store identifiers and verifiable credentials, which are cryptographic proofs of attributes. The concept follows the self-sovereign identity model, enhancing privacy and cross-domain trust. China's proposed system extends this to industrial devices and cross-border use.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cac.gov.cn/2026-06/18/c_1783525605384124.htm">国家互联网信息办公室关于《促进分布式数字身份互通互认应用规定（征求意见稿）》公开征求意见的通知国家互联网信息办公室关于《促进分布式数字身份互通 ...</a></li>
<li><a href="https://www.secrss.com/articles/84215">分布式数字身份技术概述 - 安全内参 | 决策者的网络安全知识库</a></li>

</ul>
</details>

**Tags**: `#distributed digital identity`, `#blockchain`, `#regulation`, `#China`, `#interoperability`

---

<a id="item-22"></a>
## [Sanders Proposes $1,000 Annual AI Dividend for Americans](https://www.washingtonpost.com/business/2026/06/18/bernie-sanders-proposes-wealth-fund-give-americans-stake-ai/) ⭐️ 6.0/10

Senator Bernie Sanders introduced legislation that would grant Americans an annual $1,000 dividend from large AI companies by establishing public equity stakes in these firms. This proposal reflects growing efforts to address AI-driven wealth concentration and ensure the economic benefits of AI are broadly shared, potentially setting a precedent for how governments regulate and redistribute AI-generated profits. The legislation would give the public direct equity in the largest AI companies, and President Trump reportedly expressed a similar idea of government ownership stakes. However, specific mechanisms for implementation and which companies would be affected remain unclear.

telegram · zaihuapd · Jun 19, 09:45

**Background**: Senator Bernie Sanders is known for progressive economic policies, and this proposal aligns with his agenda of reducing inequality. The idea of a sovereign wealth fund distributing corporate profits to citizens has been discussed in other contexts, such as Alaska's Permanent Fund. AI companies like OpenAI, Google, and Microsoft are generating massive revenues, raising questions about how to distribute the gains.

**Tags**: `#AI policy`, `#wealth distribution`, `#legislation`, `#AI economy`

---

<a id="item-23"></a>
## [India Temporarily Blocks Telegram for Exam, VPN Signups Spike 150%](https://t.me/zaihuapd/42058) ⭐️ 6.0/10

India's government ordered a temporary block of Telegram from June 16 to 22 to prevent cheating in the NEET-UG medical retest, causing a 150% hourly surge in Proton VPN signups from India and unintended BGP hijacking that disrupted Telegram access in other countries. This event highlights the growing use of network-level censorship by governments and its unintended collateral damage, as well as the public's rapid adoption of VPNs to circumvent restrictions, raising questions about the effectiveness and side effects of internet shutdowns. The block was implemented via BGP hijacking by Indian ISPs, rerouting Telegram traffic to a null route; this accidentally disrupted access in the UAE and other countries due to route leaks. Proton VPN reported over 150% increase in hourly signups from India during the block.

telegram · zaihuapd · Jun 19, 10:30

**Background**: BGP hijacking is a technique where a network falsely announces ownership of IP prefixes to redirect or block traffic; here it was used as a censorship tool. NEET-UG is India's national medical entrance exam, which faced cheating scandals involving Telegram, prompting the block.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/BGP_hijacking">BGP hijacking - Wikipedia</a></li>
<li><a href="https://www.cloudflare.com/learning/security/glossary/bgp-hijacking/">What is BGP hijacking? - Cloudflare</a></li>

</ul>
</details>

**Tags**: `#internet censorship`, `#VPN usage`, `#BGP hijacking`, `#Telegram`, `#India`

---

<a id="item-24"></a>
## [Ex-PhD Student Accuses Beihang Professors of Data Fabrication in Nature Paper](https://www.zaobao.com.sg/news/china/story20260619-9231002) ⭐️ 6.0/10

A former Beihang University PhD student, Geng Jiangtao (known as 'Geng Tongxue'), publicly accused two professors of data fabrication in multiple papers, including one published in Nature. The allegations triggered a massive online traffic surge that crashed the university's official website. The accusations involve a prestigious Nature publication and a major Chinese research university, highlighting persistent concerns over academic integrity and research misconduct. The incident also demonstrates the growing influence of independent whistleblowers and social media in exposing scientific fraud. Geng claimed that data in a Nature paper by associate dean Chang Lingqian was 'suspiciously perfect', suggesting possible fabrication, and that two papers by professor Wang Jun contained contradictory data. Geng previously reported five scholars from other universities for misconduct, all of whom have since faced consequences.

telegram · zaihuapd · Jun 19, 16:02

**Background**: Beijing University of Aeronautics and Astronautics (Beihang) is a top-tier Chinese research university with strong programs in engineering and medical sciences. Publishing in Nature is considered a hallmark of scientific achievement, making the allegations particularly serious. In recent years, several high-profile research misconduct cases in China have eroded public trust, leading to the emergence of online academic fraud-busters like Geng.

**Tags**: `#academic integrity`, `#research misconduct`, `#data fabrication`, `#Nature`, `#China`

---