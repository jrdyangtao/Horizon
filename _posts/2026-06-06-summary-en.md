---
layout: default
title: "Horizon Summary: 2026-06-06 (EN)"
date: 2026-06-06
lang: en
---

> From 75 items, 18 important content pieces were selected

---

1. [Google to Pay SpaceX $920M Monthly for GPU Compute Access](#item-1) ⭐️ 8.0/10
2. [Rethinking the Unix fork()+exec() Model: Inefficiencies and Alternatives](#item-2) ⭐️ 8.0/10
3. [Police in England and Wales told to halt AI use in court statements](#item-3) ⭐️ 8.0/10
4. [OpenAI Launches Lockdown Mode to Prevent Data Exfiltration](#item-4) ⭐️ 8.0/10
5. [Ladybird Browser Stops Accepting Public Pull Requests for Accountability](#item-5) ⭐️ 8.0/10
6. [TinyTPU: Browser Visualization of a 4x4 TPU Systolic Array from Real RTL](#item-6) ⭐️ 8.0/10
7. [China's First Invasive BCI Implant Restores Partial Vision to Blind Patient](#item-7) ⭐️ 8.0/10
8. [QStory Xposed Module Found with Cloud-Controlled Backdoor for QQ Data Destruction](#item-8) ⭐️ 8.0/10
9. [Nvidia Proposes Beastly ARM CPU System for Windows PCs](#item-9) ⭐️ 7.0/10
10. [Pokemon Emerald Ported to WebAssembly Achieves 100k FPS in Browser](#item-10) ⭐️ 7.0/10
11. [S&P 500 Rejects SpaceX, OpenAI, Anthropic from Index](#item-11) ⭐️ 7.0/10
12. [micropython-wasm: Secure Python sandboxing with MicroPython and WASM](#item-12) ⭐️ 7.0/10
13. [AI enthusiasts are in a race against time, AI skeptics are in a race against entropy](#item-13) ⭐️ 7.0/10
14. [NASA astronauts shelter in SpaceX Dragon due to Russian module leak](#item-14) ⭐️ 7.0/10
15. [Is Capture-Time Semantic Annotation for Robot Trajectories Solved?](#item-15) ⭐️ 6.0/10
16. [Steam to End Physical Gift Card Sales by End of 2026, Restrict Wallet Codes to Platform Use](#item-16) ⭐️ 6.0/10
17. [AMD Confirms AM5 Support Until 2029, Delays New Socket for DDR6/PCIe 6.0](#item-17) ⭐️ 6.0/10
18. [CXMT DDR5 Prices Comparable to Rivals, Supply Strength Key](#item-18) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Google to Pay SpaceX $920M Monthly for GPU Compute Access](https://techcrunch.com/2026/06/05/google-will-pay-spacex-920m-per-month-for-compute/) ⭐️ 8.0/10

Google signed a deal to pay SpaceX $920 million per month from October 2026 through June 2029 for access to approximately 110,000 NVIDIA GPUs and related components in SpaceX data centers. The deal injects massive revenue into SpaceX, potentially inflating its valuation given its high revenue multiple, while securing significant AI compute for Google and creating complex financial engineering implications. The agreement covers approximately 110,000 NVIDIA GPUs, CPUs, memory, and other components at roughly $8,400 per unit per month, though specific GPU models and configurations remain undisclosed.

hackernews · ramanan · Jun 6, 11:46 · [Discussion](https://news.ycombinator.com/item?id=48423990)

**Background**: SpaceX, primarily a rocket and satellite company, has expanded into compute services through its Starlink ground infrastructure or dedicated data centers. Google Cloud is a leading cloud provider but may seek additional AI capacity. SpaceX's high 94x revenue multiple reflects private market valuation ahead of a potential IPO.

**Discussion**: Comments highlight financial engineering: since Google owns ~5% of SpaceX, the deal could boost SpaceX's valuation, yielding a paper gain for Google. Skeptics compare it to REITs and question the sustainability of a 94x revenue multiple. Some humorously note circular payments (Google to SpaceX to NVIDIA back to Google) and bubble concerns.

**Tags**: `#Google`, `#SpaceX`, `#cloud computing`, `#financial engineering`, `#valuation`

---

<a id="item-2"></a>
## [Rethinking the Unix fork()+exec() Model: Inefficiencies and Alternatives](https://lwn.net/SubscriberLink/1076018/16f01bbbb8e0d1f0/) ⭐️ 8.0/10

A discussion sparked by a Microsoft research paper critically examines the inefficiencies and pitfalls of the traditional Unix fork()+exec() process creation model, proposing potential alternatives. This matters because the fork()+exec() model, while foundational, introduces performance overhead, security vulnerabilities, and complexity in modern systems; a better mechanism could significantly impact everything from containers to high-performance computing. The paper highlights issues like excessive memory copying (even with copy-on-write), difficulty in closing file descriptors, and unsuitability for real-time contexts; some alternatives like posix_spawn() exist but lack the full configurability of the fork()+exec() pattern.

hackernews · jwilk · Jun 6, 14:34 · [Discussion](https://news.ycombinator.com/item?id=48425528)

**Background**: fork() creates a child process that duplicates the parent’s entire address space. exec() then replaces that child’s memory with a new program. This two-step approach is standard in Unix-like systems but wasteful, as the copied memory is discarded if exec() is called immediately. Modern optimizations like copy-on-write mitigate but don’t eliminate the overhead, especially for large processes. The design dates to the 1970s when memory was small and programs simple.

<details><summary>References</summary>
<ul>
<li><a href="https://www.microsoft.com/en-us/research/wp-content/uploads/2019/04/fork-hotos19.pdf">[PDF] A fork() in the road - Microsoft</a></li>
<li><a href="https://offlinemark.com/pitfalls-with-fork-in-real-time-contexts/">Pitfalls with fork () in real-time contexts - offlinemark</a></li>
<li><a href="https://csresources.github.io/SystemProgrammingWiki/SystemProgramming/Forking,-Part-2:-Fork,-Exec,-Wait/">Forking , Part 2: Fork , Exec , Wait - UIUC CS241 SystemProgramming...</a></li>

</ul>
</details>

**Discussion**: Comments on Hacker News and LWN show a split: some users recount personal bugs caused by fork’s complexity, while others praise the elegance and extensibility of fork()+exec(), allowing fine-grained setup between fork and exec. Alternatives like a combined call are criticized as potentially less flexible and harder to maintain. Performance concerns, especially in real-time systems, are a key pain point.

**Tags**: `#fork`, `#unix`, `#process-creation`, `#systems-programming`, `#operating-systems`

---

<a id="item-3"></a>
## [Police in England and Wales told to halt AI use in court statements](https://www.ft.com/content/229e5949-3ebc-4151-8a86-a01b5e259241) ⭐️ 8.0/10

Police forces in England and Wales have been directed to immediately stop using artificial intelligence tools to prepare court statements, following an intervention by a senior official over concerns that the technology had not been properly assessed and could produce errors. This halt underscores the high stakes of deploying AI in the criminal justice system, where unreliable or biased outputs could undermine evidence integrity and lead to miscarriages of justice. It also highlights a broader struggle to regulate AI adoption in the public sector while managing productivity pressures. The intervention specifically targeted forces using commercially available AI tools like Microsoft Copilot before they had been rigorously evaluated, even though existing policies mandated that all AI-generated content be checked by officers.

hackernews · nmstoker · Jun 6, 15:35 · [Discussion](https://news.ycombinator.com/item?id=48426022)

**Background**: Police forces had been experimenting with generative AI to draft routine statements, aiming to save time and ease administrative burdens. However, large language models can fabricate details or misinterpret context, posing severe risks when used in legal documents. The push to adopt AI in policing is part of a wider UK government drive to leverage technology for public service efficiency, but it has often outpaced the establishment of safety protocols.

**Discussion**: Commenters expressed skepticism about the rushed deployment of untested AI, with one criticizing the use of Microsoft Copilot as particularly poor due to existing vendor relationships. Others doubted that AI-driven productivity gains would materialize, and some suggested alternative approaches like video-recorded officer testimony with transcription.

**Tags**: `#AI regulation`, `#legal technology`, `#police AI`, `#evidence integrity`, `#Copilot`

---

<a id="item-4"></a>
## [OpenAI Launches Lockdown Mode to Prevent Data Exfiltration](https://simonwillison.net/2026/Jun/5/openai-help-lockdown-mode/#atom-everything) ⭐️ 8.0/10

OpenAI has begun rolling out Lockdown Mode to eligible personal and self-serve ChatGPT Business accounts, which limits outbound network requests to mitigate data exfiltration from prompt injection attacks. Addressing the 'Lethal Trifecta' security vulnerability, Lockdown Mode disables the data exfiltration vector without compromising LLM utility, providing a critical safeguard for users handling sensitive information. Lockdown Mode prevents the final stage of data exfiltration by restricting outbound requests, but does not block prompt injections themselves; its deterministic mechanism is resistant to subversion, and it is available across Free, Go, Plus, Pro, and self-serve Business accounts.

rss · Simon Willison · Jun 5, 23:56

**Background**: Prompt injection is an attack where crafted inputs manipulate LLM behavior. With web browsing and file uploads, LLMs face indirect prompt injection risks. The 'Lethal Trifecta'—private data access, untrusted content, and exfiltration capabilities—makes exfiltration restriction a key defense.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Prompt_injection">Prompt injection</a></li>
<li><a href="https://owasp.org/www-community/attacks/PromptInjection">Prompt Injection - OWASP Foundation</a></li>

</ul>
</details>

**Tags**: `#prompt-injection`, `#security`, `#openai`, `#chatgpt`, `#machine-learning`

---

<a id="item-5"></a>
## [Ladybird Browser Stops Accepting Public Pull Requests for Accountability](https://simonwillison.net/2026/Jun/5/andreas-kling/#atom-everything) ⭐️ 8.0/10

Andreas Kling announced that Ladybird will no longer accept public pull requests, shifting to a model where only developers responsible for the changes can introduce them, to ensure contributor accountability in the face of AI-generated contributions. This policy change addresses the growing difficulty of verifying the origin and intent of code contributions in the era of AI-generated submissions, setting a precedent for open-source governance that prioritizes accountability over automated contributions. The announcement notes that code authorship by hand is not the issue; rather, the browser's evolution demands explicit responsibility from those who decide what changes belong in the project, as Ladybird targets real users and stability.

rss · Simon Willison · Jun 5, 11:10

**Background**: Ladybird is an open-source, privacy-focused web browser developed by the Ladybird Browser Initiative, originally a component of SerenityOS. Funded by donations and corporate sponsors like Shopify and Cloudflare, it aims for an alpha release in 2026 and a stable release in 2028. The project has been handling an increasing number of AI-generated pull requests, which prompted this governance shift.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Ladybird_(web_browser)">Ladybird (web browser) - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#ladybird`, `#open-source`, `#ai-ethics`, `#governance`, `#accountability`

---

<a id="item-6"></a>
## [TinyTPU: Browser Visualization of a 4x4 TPU Systolic Array from Real RTL](https://www.reddit.com/r/MachineLearning/comments/1txvvo4/tinytpu_systemverilog_systolic_array_compiled_to/) ⭐️ 8.0/10

TinyTPU is an interactive browser tool that compiles real SystemVerilog RTL of a 4x4 weight-stationary systolic array to WebAssembly. It visualizes hardware matrix multiplication step-by-step, with all states read directly from the compiled RTL. This tool provides an accurate, hardware-level education resource that demystifies TPU microarchitecture and systolic array data flows, filling a gap between abstract diagrams and academic papers. It makes specialized hardware concepts accessible to students and practitioners without access to physical chips. The visualization includes three levels: a single MAC cell, a full 4x4 array executing matrix multiplication, and a tiling demonstration for larger matrices. The state shown on screen is not simulated but read from the actual compiled RTL, and the design is golden-verified against numpy.

reddit · r/MachineLearning · /u/Horror-Flamingo-2150 · Jun 5, 20:05

**Background**: A systolic array is a grid of tightly coupled processing elements (PEs) that pass data rhythmically, like a heartbeat, enabling efficient parallel computation. In a weight-stationary data flow, the weight matrix is pre-loaded into the PEs, while input activations and partial sums propagate through the array each cycle. Each PE contains a multiply-accumulate (MAC) unit, which performs the fundamental operation behind most neural network computations. TPUs (Tensor Processing Units) use large systolic arrays to accelerate matrix multiplication in deep learning.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Systolic_array">Systolic array</a></li>
<li><a href="https://www.telesens.co/2018/07/30/systolic-architectures/">Understanding Matrix Multiplication on a Weight-Stationary ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Multiply–accumulate_operation">Multiply–accumulate operation - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#TPU`, `#systolic-array`, `#SystemVerilog`, `#WebAssembly`, `#hardware-education`

---

<a id="item-7"></a>
## [China's First Invasive BCI Implant Restores Partial Vision to Blind Patient](https://www.ithome.com/0/960/883.htm) ⭐️ 8.0/10

On June 6, 2025, Xiangya Hospital announced that a 61-year-old patient blind for 20 years due to retinitis pigmentosa regained partial vision (visual acuity 0.03) after receiving China's first invasive brain-computer interface implant, the IMIE intelligent retinal system, which uses a 256-channel flexible electrode array to bypass damaged photoreceptors. This breakthrough demonstrates the potential of invasive brain-computer interfaces to restore functional vision for people with retinal degenerative diseases, and the IMIE system's 256-channel count is over four times higher than comparable foreign devices, possibly offering higher resolution visual perception. The IMIE epiretinal prosthesis is implanted in the eye and directly stimulates surviving retinal neurons, achieving a visual acuity of 0.03 (Snellen equivalent ~20/667), and the patient still requires ongoing rehabilitation to improve visual function.

telegram · zaihuapd · Jun 6, 07:30

**Background**: Retinitis pigmentosa is a genetic disorder that causes progressive degeneration of the retina's photoreceptor cells, leading to blindness. Invasive brain-computer interfaces for vision restoration work by implanting electrode arrays in the retina or visual cortex to electrically stimulate neurons, bypassing damaged photoreceptors and creating artificial visual perceptions. The IMIE system is an epiretinal prosthesis that rests on the surface of the retina and uses a camera-equipped external unit to capture images and convert them into electrical signals transmitted to the implant.

<details><summary>References</summary>
<ul>
<li><a href="https://khabarasia.com/china/20260606-vision-restored-chinas-new-imie-system-enables-blind-patient-to-see-again/">Vision Restored: China's New IMIE System Enables Blind Patient to See ...</a></li>
<li><a href="https://tvst.arvojournals.org/article.aspx?articleid=2778026">First Human Results With the 256 Channel Intelligent Micro Implant Eye ...</a></li>

</ul>
</details>

**Tags**: `#brain-computer interface`, `#vision restoration`, `#neural implant`, `#medical technology`, `#China`

---

<a id="item-8"></a>
## [QStory Xposed Module Found with Cloud-Controlled Backdoor for QQ Data Destruction](https://t.me/zaihuapd/41807) ⭐️ 8.0/10

The QStory Xposed module version 2.6.2 for Android QQ has been found to contain a malicious cloud-controlled backdoor mechanism that can remotely delete all friends, dissolve all groups, and wipe local QQ data without user interaction. This backdoor poses a critical risk to the potentially large user base who use third-party QQ mods, as it can cause irreversible account damage; it also highlights the severe security dangers of installing untrusted Xposed modules with elevated system privileges. The backdoor is cloud-controlled, enabling remote activation; the destructive operations include clearing contacts, albums, and downloads, and they require no user consent. The module's author claimed to have removed the relevant code and disclaimed personal responsibility.

telegram · zaihuapd · Jun 6, 12:06

**Background**: Xposed is a framework for Android that allows users to install modules to modify app and system behavior. Modules like QStory for QQ can add features or alter functionality but run with high privileges, so a malicious module can perform destructive actions. Users often sideload such modules from untrusted sources, increasing risk. This incident underscores the danger of granting such modules deep access to sensitive apps.

<details><summary>References</summary>
<ul>
<li><a href="https://www.lifewire.com/xposed-framework-4148451">Here's How to Use the Xposed Framework to Install Mods on Android</a></li>

</ul>
</details>

**Tags**: `#security`, `#android`, `#xposed`, `#malware`, `#qq`

---

<a id="item-9"></a>
## [Nvidia Proposes Beastly ARM CPU System for Windows PCs](https://twitter.com/lemire/status/2062880075117113739) ⭐️ 7.0/10

Nvidia has proposed a high-end ARM-based CPU system designed for Windows PCs, featuring a unified memory architecture that could rival Apple's M-series processors. This could introduce Apple Silicon-like efficiency and performance to Windows, significantly impacting gaming, local AI workloads, and the competitive landscape against Intel, AMD, and Qualcomm. The speculative chip would use unified memory to share data between CPU and GPU seamlessly, potentially reducing latency and power consumption, but single-core performance and software compatibility remain key challenges.

hackernews · tosh · Jun 6, 12:52 · [Discussion](https://news.ycombinator.com/item?id=48424605)

**Background**: Unified memory architecture allows the CPU and GPU to access the same memory pool, avoiding data duplication and improving efficiency, as seen in Apple's M-series chips. Windows on ARM has matured with better emulation for x86 apps and native ARM software support, making such a system more viable than in the past.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Unified_memory_architecture">Unified memory architecture</a></li>
<li><a href="https://grokipedia.com/page/Unified_Memory_Architecture">Unified Memory Architecture</a></li>
<li><a href="https://learn.microsoft.com/en-us/windows/arm/overview">Windows on Arm documentation | Microsoft Learn Is Windows on ARM worth it? My experience after 6 months of ... What is Windows 11 on ARM and How Does it ... - How-To Geek Top Stories Windows on ARM | Software Compatibility List Windows on ARM: No Longer a Compromise — Now an Advantage Windows 11 on Arm app compatibility is no longer a concern ...</a></li>

</ul>
</details>

**Discussion**: Community reactions are mixed: some see unified memory as a game changer for local AI and gaming, while others argue that Qualcomm's Snapdragon X2 already offers competitive performance with better power efficiency. Skeptics note that Nvidia's proposal lacks proven real-world specs and may underperform compared to discrete GPUs.

**Tags**: `#Nvidia`, `#ARM processors`, `#Windows on ARM`, `#unified memory`, `#AI hardware`

---

<a id="item-10"></a>
## [Pokemon Emerald Ported to WebAssembly Achieves 100k FPS in Browser](https://pokeemerald.com/) ⭐️ 7.0/10

A fan project has successfully ported Pokémon Emerald to WebAssembly, achieving an extraordinary 100,000 FPS when running in modern browsers, with the source code available on GitHub. This feat demonstrates WebAssembly's near-native performance for complex console emulation entirely in the browser, making classic games instantly accessible without downloads or plugins, and pushing the boundaries of what web applications can achieve. The port currently has known bugs: some text displays as numbers (e.g., 'You received a 6' instead of item names), and selecting 'Pokemon' in battle crashes the game. Controls use 'z' and 'x' keys for A and B buttons, though users note the UI lacks clear indications.

hackernews · tripplyons · Jun 6, 11:12 · [Discussion](https://news.ycombinator.com/item?id=48423762)

**Background**: WebAssembly is a portable binary instruction format that runs at near-native speed in web browsers, standardized by W3C in 2019. Pokémon Emerald is a 2004 Game Boy Advance RPG, traditionally played via native emulators. Compiling the game's C codebase to Wasm allows it to execute directly in the browser canvas.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/WebAssembly">WebAssembly</a></li>
<li><a href="https://webassembly.org/">WebAssembly</a></li>

</ul>
</details>

**Discussion**: Users report a few bugs, like text displaying as numbers and a crash in the battle 'Pokemon' menu. They appreciate the speed-up feature and suggest UI improvements, such as indicating keyboard controls and supporting save file export/import. Some confirm that saving works, and there is interest in enabling trading functionality.

**Tags**: `#webassembly`, `#emulation`, `#game-development`, `#pokemon`, `#performance`

---

<a id="item-11"></a>
## [S&P 500 Rejects SpaceX, OpenAI, Anthropic from Index](https://arstechnica.com/tech-policy/2026/06/sp-500-blocks-fast-spacex-entry-wont-waive-rule-for-unprofitable-ai-firms/) ⭐️ 7.0/10

The S&P 500 has decided to exclude SpaceX, OpenAI, and Anthropic from its index, adhering to long-standing inclusion rules that require a track record of profitability and SEC filings. This decision upholds the integrity of passive index investing by preventing exceptions for hyped companies, thereby protecting the interests of everyday investors who rely on consistent criteria. The inclusion criteria typically require four consecutive quarters of GAAP profitability and sufficient public float; SpaceX reportedly sought a waiver, while OpenAI and Anthropic are not yet profitable.

hackernews · maltalex · Jun 6, 04:38 · [Discussion](https://news.ycombinator.com/item?id=48421442)

**Background**: The S&P 500 is a market-cap-weighted index of 500 large U.S. companies, widely tracked by index funds. Inclusion is rules-based, considering market cap, profitability, and liquidity, not subjective discretion. Adding a stock requires meeting these quantitative thresholds, which these three companies currently do not meet.

**Discussion**: Commenters strongly supported the decision, emphasizing the importance of due diligence and consistent rules. One noted that waiting for SEC filings helps prevent fraud, while another highlighted that passive investors want indices to stick to their strategy without exceptions. Some mentioned that the market's FOMO around SpaceX is fading.

**Tags**: `#S&P 500`, `#index investing`, `#market regulation`, `#tech IPOs`, `#passive investing`

---

<a id="item-12"></a>
## [micropython-wasm: Secure Python sandboxing with MicroPython and WASM](https://simonwillison.net/2026/Jun/6/micropython-in-a-sandbox/#atom-everything) ⭐️ 7.0/10

On June 6, 2026, Simon Willison released micropython-wasm, an alpha package that securely executes Python code in a sandbox by compiling MicroPython to WebAssembly. This approach enables safe execution of untrusted Python code within web applications and plugins, with strict memory and CPU limits, addressing a long-standing security challenge for extensible systems like Datasette. The sandbox uses MicroPython's minimalistic Python implementation compiled to WebAssembly, running in a browser or server environment. Current limitations include potential incompatibilities with full CPython libraries and the early alpha status, meaning it is not yet hardened against all escape attempts.

rss · Simon Willison · Jun 6, 03:53

**Background**: MicroPython is a lightweight implementation of Python 3 optimized for microcontrollers, but can also be compiled to WebAssembly for use in web environments. WebAssembly (Wasm) is a portable binary instruction format that allows code written in languages like C/C++ to run at near-native speed in browsers, and is also used for secure sandboxed execution outside browsers. Compiling MicroPython to Wasm allows running Python code within a constrained, isolated environment that can enforce resource limits.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/MicroPython">MicroPython</a></li>
<li><a href="https://en.wikipedia.org/wiki/WebAssembly">WebAssembly</a></li>

</ul>
</details>

**Tags**: `#sandbox`, `#WebAssembly`, `#MicroPython`, `#Python`, `#security`

---

<a id="item-13"></a>
## [AI enthusiasts are in a race against time, AI skeptics are in a race against entropy](https://simonwillison.net/2026/Jun/4/ai-enthusiasts-ai-skeptics/#atom-everything) ⭐️ 7.0/10

Charity Majors argues that AI enthusiasts race against time to leverage AI's leaps before competitors, while skeptics race against entropy to preserve software trust and reliability. This framing clarifies the high-stakes tension in software teams, showing that both enthusiasm and skepticism carry existential risks, and demands organizational design to connect them. Charity notes the lack of a natural feedback loop between the two groups, making the design of such loops a key organizational challenge.

rss · Simon Willison · Jun 4, 23:55

**Background**: AI tools like code assistants have enabled dramatic productivity gains but raise concerns about code quality, security, and maintainability. Enthusiasts believe rapid adoption is necessary to stay competitive, while skeptics caution that unvetted AI-generated code can degrade system reliability and institutional knowledge.

**Tags**: `#AI`, `#software-engineering`, `#developer-productivity`, `#tech-culture`, `#trust`

---

<a id="item-14"></a>
## [NASA astronauts shelter in SpaceX Dragon due to Russian module leak](https://techcrunch.com/2026/06/05/nasa-tells-astronauts-to-shelter-in-spacex-dragon-due-to-new-leaks-on-the-iss/) ⭐️ 7.0/10

NASA instructed the five astronauts on the International Space Station to temporarily shelter in a docked SpaceX Crew Dragon capsule after a new leak was detected in the Russian service module. This incident highlights the risks of aging ISS infrastructure, particularly the Russian segment, and the urgency of transitioning to commercial space stations. The Russian service module has a history of cracks and leaks; the duration of the shelter-in-place order is currently unknown.

telegram · zaihuapd · Jun 6, 02:00

**Background**: The International Space Station has been operational since 1998, with major components from the US, Russia, Europe, Japan, and Canada. The Russian segment, including the Zvezda service module, has experienced multiple air leaks in recent years, leading to repairs and safety concerns. NASA plans to replace the ISS with commercial modules by the end of the decade.

**Tags**: `#space`, `#ISS`, `#safety`, `#NASA`, `#SpaceX`

---

<a id="item-15"></a>
## [Is Capture-Time Semantic Annotation for Robot Trajectories Solved?](https://www.reddit.com/r/MachineLearning/comments/1txf4gg/would_you_say_capturetime_semantic_annotation_for/) ⭐️ 6.0/10

A Reddit post questions whether capture-time semantic annotation for robot teleoperation data is a solved problem, arguing that raw data lacks crucial information like affordance and contact intent, which cannot be reliably recovered post-hoc or through simulation. If left unaddressed, this gap could limit progress in robot learning for contact-rich tasks in unstructured environments, prompting the community to explore real-time annotation methods that could substantially improve policy learning. The post highlights that raw teleoperation data (RGB images and joint states) structurally lack affordance, contact intent, and kinematic context, and current approaches like post-hoc labeling or simulation fail to bridge this semantic gap.

reddit · r/MachineLearning · /u/Several-Many9101 · Jun 5, 08:42

**Background**: Semantic annotation labels data with meaningful information like object affordances and contact states, enabling robots to learn from demonstrations. Teleoperation data streams captured during human control lack such context inherently. Affordance refers to the actionable properties between an agent and its environment, critical for manipulation tasks. Contact-rich tasks require fine-grained interaction understanding that raw sensor data may not convey.

<details><summary>References</summary>
<ul>
<li><a href="https://www.annotera.ai/blog/data-annotation-for-robotics/">Data Annotation for Robotics and Industrial Automation</a></li>
<li><a href="https://robo-affordances.github.io/">VRB: Affordances from Human Videos as a Versatile Representation for Robotics</a></li>
<li><a href="https://www.cvat.ai/resources/blog/robotics-data-annotation">What Is Data Annotation in Robotics ? A Complete... | CVAT Blog</a></li>

</ul>
</details>

**Tags**: `#robot-learning`, `#imitation-learning`, `#teleoperation`, `#semantic-annotation`, `#data-collection`

---

<a id="item-16"></a>
## [Steam to End Physical Gift Card Sales by End of 2026, Restrict Wallet Codes to Platform Use](https://www.ithome.com/0/960/748.htm) ⭐️ 6.0/10

Valve announced that it will cease sales of physical Steam gift cards, with existing inventory expected to sell out by end of 2026. The company also emphasized that Steam wallet codes can only be used to purchase games, software, hardware, and in-game items on Steam, not for real-world payments. This move is part of Steam's ongoing efforts to combat gift card scams, where fraudsters frequently coerce victims into purchasing and disclosing codes, making fund recovery difficult. By ending physical card sales and reinforcing wallet code restrictions, Steam reduces avenues for fraud and protects users. Digital gift cards will remain available but may face increasing restrictions. Steam had previously limited cross-region code redemption to combat fraud, and users are advised never to share card codes with others.

telegram · zaihuapd · Jun 6, 02:45

**Background**: Steam gift cards and wallet codes are popular payment methods on the platform. Scammers exploit them by tricking victims into buying cards and providing codes, which are quickly redeemed and laundered. Steam previously implemented cross-region redemption restrictions to prevent abuse, and this latest step further tightens controls on physical cards.

<details><summary>References</summary>
<ul>
<li><a href="https://zhuanlan.zhihu.com/p/646898543">Steam转区&跨区小指南 - 知乎</a></li>

</ul>
</details>

**Tags**: `#Steam`, `#gift cards`, `#fraud prevention`, `#gaming`, `#announcement`

---

<a id="item-17"></a>
## [AMD Confirms AM5 Support Until 2029, Delays New Socket for DDR6/PCIe 6.0](https://www.ithome.com/0/960/869.htm) ⭐️ 6.0/10

At Computex 2026, AMD announced that the AM5 platform will be supported until at least 2029, with future Zen-based products still using this socket, and the next CPU socket will only arrive once DDR6 and PCIe 6.0 become mainstream. This extends platform longevity for users, reducing upgrade costs and e-waste, while reflecting broader industry trends of slower memory standard adoption and high component costs. AMD's decision is influenced by the lack of immediate demand for more NVMe slots or higher power delivery, and the delayed arrival of DDR6 beyond previously expected 2027–2028.

telegram · zaihuapd · Jun 6, 09:15

**Background**: Socket AM5 (LGA 1718) is AMD's current CPU socket for Ryzen processors, introduced in 2022 with Zen 4. DDR6 is the upcoming memory standard expected to replace DDR5, offering higher bandwidth. PCIe 6.0 is the next generation of the PCIe interface, doubling throughput over PCIe 5.0.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Socket_AM5">Socket AM5 - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/DDR6_SDRAM">DDR6 SDRAM - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/PCI_Express">PCI Express - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#AMD`, `#AM5`, `#DDR6`, `#PCIe 6.0`, `#Computex2026`

---

<a id="item-18"></a>
## [CXMT DDR5 Prices Comparable to Rivals, Supply Strength Key](https://www.ithome.com/0/960/963.htm) ⭐️ 6.0/10

New reports from Computex 2026 indicate that ChangXin Memory Technologies (CXMT) DDR5 prices are roughly equal to those of Samsung, SK Hynix, and Micron, debunking rumors of significant cost advantages. Its main competitive edge lies in stronger supply capability for conventional DRAM due to limited AI-related production, and Corsair now uses CXMT chips in its Vengeance DDR5-6000 CL36 modules. This reshapes CXMT's market image from a low-cost challenger to a reliable conventional DRAM supplier. Its supply flexibility may help ease shortages and offer system builders an alternative source amid competitors' AI capacity reallocation. CXMT's DDR5 initially targets entry-level and Chinese markets, with plans to expand globally; the company does not require upfront payment, offering more flexibility. Corsair's Vengeance DDR5-6000 CL36 modules using CXMT chips represent a significant design win.

telegram · zaihuapd · Jun 6, 13:27

**Background**: CXMT is a Chinese DRAM manufacturer founded in 2016, producing memory on a 19nm process with expanding capacity. The global DRAM market is led by Samsung, SK Hynix, and Micron. DDR5 is the current-generation memory standard. The surge in AI demand has led major players to allocate more capacity to high-bandwidth memory (HBM), tightening supply for conventional DDR5.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ChangXin_Memory_Technologies">ChangXin Memory Technologies</a></li>

</ul>
</details>

**Tags**: `#CXMT`, `#DDR5`, `#memory market`, `#semiconductors`, `#supply chain`

---