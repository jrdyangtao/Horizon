---
layout: default
title: "Horizon Summary: 2026-07-17 (EN)"
date: 2026-07-17
lang: en
---

> From 75 items, 32 important content pieces were selected

---

1. [Mozilla Reports Rapid Shift to Open Source AI](#item-1) ⭐️ 9.0/10
2. [Firefox Running Inside Another Browser via WebAssembly](#item-2) ⭐️ 9.0/10
3. [AWS billing bug shows $1.7 billion erroneous estimated bill](#item-3) ⭐️ 8.0/10
4. [First atmosphere found on Earth-like exoplanet in habitable zone](#item-4) ⭐️ 8.0/10
5. [Moonshot AI Releases Kimi K3, a 2.8T Open-Weight Model](#item-5) ⭐️ 8.0/10
6. [Three non-solution responses to problems](#item-6) ⭐️ 8.0/10
7. [Codex Bug Can Delete $HOME in Full Access Mode](#item-7) ⭐️ 8.0/10
8. [Thinking Machines Lab Releases Inkling, a 975B Open-Weights MoE Model](#item-8) ⭐️ 8.0/10
9. [Linus Torvalds Declares Linux Not Anti-AI](#item-9) ⭐️ 8.0/10
10. [xAI open-sources grok-build after severe privacy incident](#item-10) ⭐️ 8.0/10
11. [EU AI Act OpenRAG: Structured Corpus with Embeddings Released](#item-11) ⭐️ 8.0/10
12. [ExTernD: Expanded-Rank Ternary Decomposition for Accurate LLM PTQ](#item-12) ⭐️ 8.0/10
13. [TSMC Announces $100B More US Investment, Q2 Profit Soars 77%](#item-13) ⭐️ 8.0/10
14. [Huawei unveils Ascend 950 SuperPod, claims 6.7x Nvidia compute](#item-14) ⭐️ 8.0/10
15. [US lawmakers seek ban on Chinese memory chips in allied supply chains](#item-15) ⭐️ 8.0/10
16. [OpenAI CFO proposes 'useful intelligence per dollar' metric for AI ROI](#item-16) ⭐️ 8.0/10
17. [Which Lisp to Choose? A Guide to Common Lisp, Scheme, Clojure, Racket](#item-17) ⭐️ 7.0/10
18. [SSH honeypot live visualization shows bot login attempts](#item-18) ⭐️ 7.0/10
19. [EEG Study Shows Brain Can Encode Two Speech Streams Simultaneously](#item-19) ⭐️ 7.0/10
20. [Apple Sends Retention Letters to Former Employees at OpenAI](#item-20) ⭐️ 7.0/10
21. [Pebble Mega Update Reveals Index 01, Community Criticizes Flaws](#item-21) ⭐️ 7.0/10
22. [Mermaid to ASCII Art Comes to Browser via Go WebAssembly](#item-22) ⭐️ 7.0/10
23. [Prism Bug Leaks Other Users' Papers via Compilation](#item-23) ⭐️ 7.0/10
24. [DABSN: New Recurrent Language Model Architecture Seeks Collaborators](#item-24) ⭐️ 7.0/10
25. [QLoRA default learning rate 2e-4 causes overfitting on small datasets](#item-25) ⭐️ 7.0/10
26. [EU Draft May Force Google to Open Android to Rival AI Assistants](#item-26) ⭐️ 7.0/10
27. [1Password Integrates with Claude for Secure AI Login](#item-27) ⭐️ 7.0/10
28. [Truth Social to Sell Millisecond Access to Trump's Posts to Wall Street](#item-28) ⭐️ 7.0/10
29. [Tesla Cybercab enters production in North America](#item-29) ⭐️ 7.0/10
30. [Rethinking AI Memory: From Facts to Reasoning Patterns](#item-30) ⭐️ 6.0/10
31. [RTCA Workshop at NeurIPS 2026 Issues Call for Papers](#item-31) ⭐️ 6.0/10
32. [Starship 13th Test Flight Auto-Aborts at Last Second](#item-32) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Mozilla Reports Rapid Shift to Open Source AI](https://stateofopensource.ai/) ⭐️ 9.0/10

Mozilla published a comprehensive report on the state of open source AI, highlighting the rapid growth and adoption of open-weight models. The report includes data and analysis on the ecosystem. This report provides an authoritative overview of the open source AI landscape, influencing how developers and companies perceive the shift from closed to open models. It underscores the competitive pressure on proprietary AI companies like OpenAI and Anthropic. The report is hosted at stateofopensource.ai and includes community discussion noting a rapid increase in token processing from open models, with openrouter data showing a shift from 60% closed to 63% open market share in four months.

hackernews · rellem · Jul 17, 14:31 · [Discussion](https://news.ycombinator.com/item?id=48947825)

**Background**: Open source AI refers to AI models where the code, weights, or both are openly available for use, modification, and distribution. Open-weight models, such as Llama and DeepSeek, release the trained parameters but may have usage restrictions. This contrasts with fully closed models like GPT-4. The report surveys the current ecosystem.

<details><summary>References</summary>
<ul>
<li><a href="https://hai.stanford.edu/ai-definitions/what-is-an-open-weight-model">What is an Open-Weight Model? - Stanford HAI</a></li>

</ul>
</details>

**Discussion**: The community expressed mixed reactions: some enthusiastically cited data showing open models' rapid market share growth, while others criticized the report for appearing to be AI-written, undermining its credibility. There was also skepticism about Mozilla's own market position given Firefox's declining usage.

**Tags**: `#open source`, `#AI`, `#Mozilla`, `#machine learning`, `#models`

---

<a id="item-2"></a>
## [Firefox Running Inside Another Browser via WebAssembly](https://simonwillison.net/2026/Jul/16/firefox-in-webassembly/#atom-everything) ⭐️ 9.0/10

Puter has successfully compiled the entire Firefox browser to WebAssembly using AI-assisted compilation with Claude Opus, enabling it to run fully inside another browser as a browser-in-browser demo. This demonstrates unprecedented cross-platform portability for a full browser engine and highlights the potential of large language models to assist in complex software compilation, which could impact future web-based virtual environments and browser engineering. The compilation used Gecko because of its strong single-process support, and all network traffic is proxied via a WebSocket connection using the Wisp protocol through Puter's servers. The project consumed an estimated $25,000 worth of Claude Opus and Fable tokens, but costs were reduced using a Claude Max subscription plan.

rss · Simon Willison · Jul 16, 23:34

**Background**: WebAssembly (Wasm) is a low-level binary instruction format that runs in modern web browsers at near-native speed, allowing code written in languages like C++ and Rust to be executed in the browser. Compiling a full browser engine like Firefox (which uses the Gecko rendering engine) to Wasm is an extremely challenging task due to the sheer size and complexity of the codebase. AI-assisted compilation using large language models like Claude Opus can help automate parts of the translation process. The Wisp protocol is a low-overhead protocol for proxying TCP and UDP connections over a single WebSocket, which is necessary because Wasm code in the browser cannot open raw network sockets.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Gecko_(browser_engine)">Gecko (browser engine)</a></li>
<li><a href="https://github.com/MercuryWorkshop/wisp-protocol">GitHub - MercuryWorkshop/ wisp - protocol : Wisp is a low-overhead...</a></li>

</ul>
</details>

**Tags**: `#WebAssembly`, `#Firefox`, `#AI-assisted compilation`, `#browser-in-browser`, `#demo`

---

<a id="item-3"></a>
## [AWS billing bug shows $1.7 billion erroneous estimated bill](https://news.ycombinator.com/item?id=48945241) ⭐️ 8.0/10

AWS users reported seeing estimated bills as high as $1.7 billion due to a unit conversion bug where billing data was misinterpreted as bytes instead of gigabytes. A former AWS engineer confirmed the error, stating that a pricing plan unit was left as the default (bytes) instead of the intended GB, causing a factor of 1e9 overcharge. This bug highlights systemic risks in cloud billing systems, where small unit errors can cause massive financial discrepancies and erode customer trust. It also underscores the complexity of pricing logic in major cloud providers, affecting millions of users who may have been alarmed by inaccurate estimates. The error was reportedly caused by a field in the pricing plan that defaulted to bytes instead of GB, leading to a billion-fold overcharge for data transfer. AWS support tickets were created, and the issue was fixed within hours, with amendments issued.

hackernews · nprateem · Jul 17, 09:42

**Background**: Cloud providers like AWS charge for services such as data transfer based on units like gigabytes (GB). However, internally billing systems often store metering data in bytes. If a pricing plan mistakenly omits the unit conversion, customers can be charged per byte instead of per GB, resulting in a discrepancy of 1,000,000,000x. This is similar to the more common confusion between gigabytes (GB, base-10) and gibibytes (GiB, base-2).

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Gigabyte">Gigabyte - Wikipedia</a></li>
<li><a href="https://massive.io/file-transfer/gb-vs-gib-whats-the-difference/">GB Vs GiB: What’s The Difference? - MASV</a></li>
<li><a href="https://support.reddigitalcinema.com/hc/en-us/articles/115004488887-DSMC2-RANGER-The-Difference-Between-GB-and-GiB">DSMC2/RANGER - The Difference Between GB and GiB – RED Support</a></li>

</ul>
</details>

**Discussion**: Community comments confirm widespread impact, with multiple users reporting similarly inflated bills. A former AWS engineer provided firsthand insight into the unit error, explaining the fix timeline. Some commenters expressed broader concerns about billing accuracy and potential catastrophic failures in cloud systems.

**Tags**: `#AWS`, `#billing`, `#bug`, `#cloud computing`, `#unit error`

---

<a id="item-4"></a>
## [First atmosphere found on Earth-like exoplanet in habitable zone](https://www.bbc.com/news/articles/cy4kdd1e0ejo) ⭐️ 8.0/10

Astronomers have detected helium in the atmosphere of an Earth-like exoplanet located in the habitable zone of its star, marking the first time an atmosphere has been confirmed on such a world. The discovery was made using transit spectroscopy observations of helium absorption lines. This breakthrough opens the door to studying atmospheres of potentially habitable worlds, advancing the search for signs of life beyond Earth. It also demonstrates helium absorption as a viable technique for probing exoplanet atmospheres, which could be applied to other candidates. The detected gas is helium, which is not itself a biosignature, but its presence indicates an atmosphere that may contain other gases. The exoplanet is approximately 48 light-years away, relatively close in astronomical terms, and could be a target for future detailed study.

hackernews · neversaydie · Jul 17, 14:06 · [Discussion](https://news.ycombinator.com/item?id=48947560)

**Background**: Exoplanets are planets orbiting stars other than our Sun. The habitable zone is the region around a star where conditions might allow liquid water to exist on a planet's surface. Transit spectroscopy analyzes starlight passing through a planet's atmosphere to reveal its composition. Helium absorption at 10830 angstroms has become a key probe for studying exoplanet atmospheres.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Transit_spectroscopy">Transit spectroscopy</a></li>
<li><a href="https://en.wikipedia.org/wiki/Habitable_zone">Habitable zone - Wikipedia</a></li>
<li><a href="https://arxiv.org/pdf/2501.06149">Understanding what helium absorption tells us about atmospheric</a></li>

</ul>
</details>

**Discussion**: Commenters discussed building a solar lens telescope to observe such planets, and considered propulsion methods for sending a probe to this nearby world. One commenter noted that Venus is also an Earth-like planet with an atmosphere in the habitable zone, cautioning against overinterpreting the significance.

**Tags**: `#exoplanets`, `#atmosphere detection`, `#astrobiology`, `#habitable zone`, `#astronomy`

---

<a id="item-5"></a>
## [Moonshot AI Releases Kimi K3, a 2.8T Open-Weight Model](https://simonwillison.net/2026/Jul/16/kimi-k3/#atom-everything) ⭐️ 8.0/10

Moonshot AI announced Kimi K3, a 2.8 trillion parameter open-weight model, with self-reported benchmarks showing it mostly outperforms Claude Opus 4.8 and GPT-5.5 high, but trails Claude Fable 5 and GPT-5.6 Sol. This release marks the first open '3T-class' model, surpassing DeepSeek's 1.6T parameter model and pushing the boundaries of open-weight AI. It also generates community discussion about tokenization quirks and evaluation nuances, highlighting the importance of informal benchmarks like the pelican test. Kimi K3 uses Kimi Delta Attention and Attention Residuals, and is priced at $3 per million input tokens and $15 per million output tokens. On a private evaluation, it achieved an Elo of 1547, using 21% fewer output tokens than its predecessor K2.6.

rss · Simon Willison · Jul 16, 20:19 · [Discussion](https://news.ycombinator.com/item?id=48947717)

**Background**: Kimi K3 is the latest model from Chinese AI lab Moonshot AI, following the open-weights Kimi K2 released in July 2025. The pelican benchmark is an informal test created by developer Simon Willison that asks an LLM to generate an SVG of a pelican riding a bicycle. It is used to compare model quality and cost in a creative, non-standard way.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Kimi_K3">Kimi K3</a></li>
<li><a href="https://www.kimi.com/blog/kimi-k3">Kimi K 3 Tech Blog: Open Frontier Intelligence</a></li>
<li><a href="https://platform.kimi.ai/docs/guide/kimi-k3-quickstart">Kimi K 3 - Kimi API Platform</a></li>

</ul>
</details>

**Discussion**: Commenters noted that the pelican test may be contaminated because Simon's blog posts with pelican SVGs are likely in the training data, and tokenization quirks suggest a hidden system prompt of about 85 tokens. Others compared cost vs speed, finding Kimi K3 cheapest per task but slowest. Overall, the discussion was insightful and focused on evaluation methodology.

**Tags**: `#AI`, `#LLM`, `#Kimi K3`, `#Moonshot AI`, `#model release`

---

<a id="item-6"></a>
## [Three non-solution responses to problems](https://improvesomething.today/responses-to-problems/) ⭐️ 8.0/10

An article categorizes three common but non-solving responses to problems: preserving the problem, deprioritizing it, or misdiagnosing it. This framework helps explain persistent issues in large organizations and government, where solving problems is often not the actual goal due to misaligned incentives. The three responses are preserving problems (e.g., budgets depend on problems), deprioritizing (shifting focus), and misdiagnosing (applying wrong solutions). Hacker News comments expand on these with real-world examples.

hackernews · surprisetalk · Jul 17, 14:00 · [Discussion](https://news.ycombinator.com/item?id=48947490)

**Background**: Organizational behavior literature often notes that incentives can lead to problem perpetuation. This article provides a simple taxonomy of non-solution responses, complementing concepts like risk management strategies.

**Discussion**: Commenters discuss how government agencies preserve problems to maintain budgets and power, and how experts may avoid solving root causes to justify their roles. Some relate the framework to HR departments and political infighting.

**Tags**: `#problem solving`, `#organizational behavior`, `#systems thinking`, `#bureaucracy`, `#psychology`

---

<a id="item-7"></a>
## [Codex Bug Can Delete $HOME in Full Access Mode](https://simonwillison.net/2026/Jul/16/bad-codex-bug/#atom-everything) ⭐️ 8.0/10

Thibault Sottiaux reports a bug in Codex (GPT-5.6) where the model can mistakenly delete the $HOME directory when attempting to override it, particularly in unsandboxed full access mode. This bug poses a serious risk for users running Codex with full system access, as it can lead to unintended file deletions, potentially causing data loss and system instability. It highlights the importance of sandboxing and approval mechanisms in AI coding agents. The issue occurs when full access mode (danger-full-access) is enabled without sandboxing protections and without auto-review enabled. The model attempts to set a temporary directory by overriding $HOME but makes an error and deletes $HOME instead.

rss · Simon Willison · Jul 16, 17:45

**Background**: Codex is an AI coding agent by OpenAI that can execute commands and edit files. By default, Codex runs in a sandbox that limits filesystem and network access. However, users can opt into 'danger-full-access' mode to remove those restrictions. Auto-review is a feature that replaces manual approval with a separate reviewer agent for safer execution. The bug described occurs when full access is granted without these safety measures.

<details><summary>References</summary>
<ul>
<li><a href="https://mintlify.wiki/openai/codex/concepts/sandboxing">Sandboxing - Codex CLI</a></li>
<li><a href="https://alignment.openai.com/auto-review/">Auto-review of agent actions without synchronous human oversight</a></li>
<li><a href="https://azukiazusa.dev/en/blog/codex-sandbox-agent-authorization/">Understanding Codex Sandbox and Agent Approvals</a></li>

</ul>
</details>

**Tags**: `#codex`, `#coding-agents`, `#generative-ai`, `#ai-safety`, `#bug`

---

<a id="item-8"></a>
## [Thinking Machines Lab Releases Inkling, a 975B Open-Weights MoE Model](https://simonwillison.net/2026/Jul/16/inkling/#atom-everything) ⭐️ 8.0/10

Mira Murati's Thinking Machines Lab released Inkling, an open-weights mixture-of-experts multimodal model with 975 billion total parameters and 41 billion active parameters, licensed under Apache-2.0. This release provides a competitive open-weights alternative from the US, strengthening the open ecosystem against models from China, and offers a strong base for fine-tuning via Thinking Machines' Tinker platform. Inkling is trained on 45 trillion tokens of text, images, audio, and video; it is not a frontier model but designed for customization. A smaller 276B-parameter variant (12B active) called Inkling-Small is promised but not yet released.

rss · Simon Willison · Jul 16, 15:35

**Background**: Open-weights models release the final trained parameters, allowing users to download and fine-tune them, but typically do not include training code or data. Mixture-of-experts (MoE) architectures activate only a subset of parameters per input token, enabling very large total parameter counts while keeping computational costs manageable.

<details><summary>References</summary>
<ul>
<li><a href="https://opensource.org/ai/open-weights">Open Weights: not quite what you’ve been told</a></li>
<li><a href="https://www.ibm.com/think/topics/mixture-of-experts">What is mixture of experts? | IBM</a></li>
<li><a href="https://huggingface.co/blog/moe">Mixture of Experts Explained</a></li>

</ul>
</details>

**Tags**: `#AI`, `#open-weights`, `#large language model`, `#mixture-of-experts`, `#multimodal`

---

<a id="item-9"></a>
## [Linus Torvalds Declares Linux Not Anti-AI](https://simonwillison.net/2026/Jul/16/linus-torvalds/#atom-everything) ⭐️ 8.0/10

Linus Torvalds, the creator and lead maintainer of the Linux kernel, publicly stated that Linux is not an anti-AI project and that AI is a clearly useful tool, dismissing critics and threatening that dissenters can fork the project or walk away. This strong stance from a highly influential figure in open source could shape the acceptance and integration of AI tools into Linux development, potentially accelerating adoption across the kernel community and beyond. Torvalds made the remarks on the Linux Media mailing list, emphasizing that AI's usefulness is no longer in question even if other economic aspects remain uncertain, and he positioned himself as willing to 'absolutely put my foot down' as top-level maintainer.

rss · Simon Willison · Jul 16, 13:26

**Background**: Linus Torvalds is the creator and longtime maintainer of the Linux kernel, one of the world's largest open-source projects. AI tools, particularly large language models, have been increasingly used in software development, but some in the open-source community have raised concerns about ethical implications, bias, and corporate control. Torvalds' statement directly addresses this tension, affirming AI as a legitimate tool within Linux development.

**Tags**: `#Linux`, `#AI`, `#open source`, `#kernel`, `#Linus Torvalds`

---

<a id="item-10"></a>
## [xAI open-sources grok-build after severe privacy incident](https://simonwillison.net/2026/Jul/15/grok-build/#atom-everything) ⭐️ 8.0/10

xAI open-sourced the entire Grok Build codebase under Apache 2.0 license after user backlash over its CLI tool uploading entire directories to the cloud. The company also deleted all retained user data and disabled default data retention. This incident highlights serious privacy risks in AI-powered developer tools and the importance of transparency and community trust. Open-sourcing the code allows independent auditing and enables fully local operation, potentially setting a new standard for privacy in coding agents. The Grok Build codebase is 844,530 lines of Rust, with only about 3% vendored code. The repository contains a single commit, so development history is unavailable. Notable components include a Mermaid diagram terminal renderer and tool implementations inspired by Codex and OpenCode.

rss · Simon Willison · Jul 15, 23:59

**Background**: Grok Build is xAI's terminal-based AI coding agent and CLI, powered by Grok models. The tool is designed to assist developers with complex coding tasks by running shell commands and file operations. Prior to the open-source release, user backlash erupted when it was discovered that the CLI uploaded entire directories—including SSH keys and password databases—to xAI's cloud storage.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/xai-org/grok-build">GitHub - xai-org/ grok - build : SpaceXAI's coding agent harness and...</a></li>
<li><a href="https://x.ai/open-source">Open Source : Grok Build Coding Agent & CLI | SpaceXAI</a></li>
<li><a href="https://x.ai/cli">Grok Build | SpaceXAI</a></li>

</ul>
</details>

**Discussion**: The community reaction was intense: one user reported that running the tool in their home directory uploaded SSH keys, password manager data, documents, and photos. Elon Musk responded on Twitter assuring that all uploaded data would be completely deleted, and xAI later disabled the feature and open-sourced the code to regain trust.

**Tags**: `#privacy`, `#open source`, `#AI tools`, `#security`, `#xAI`

---

<a id="item-11"></a>
## [EU AI Act OpenRAG: Structured Corpus with Embeddings Released](https://www.reddit.com/r/MachineLearning/comments/1uytlac/eu_ai_act_openrag_933_legally_structured_chunks/) ⭐️ 8.0/10

A downloadable corpus of the EU AI Act, featuring 933 legally-structured chunks and BGE-M3 embeddings, has been released on Hugging Face for RAG and legal-NLP experimentation. This dataset enables more accurate retrieval-augmented generation and NLP tasks on the EU AI Act by using legal structure-based chunking instead of arbitrary sliding windows, improving recall and QA performance. The corpus includes exact EUR-Lex links, Article 113 application-date metadata, and narrow derived labels; retrieval evaluation showed recall@20 of 0.541 (structural) vs 0.449 (baseline) and QA hit@10 of 0.927 vs 0.898.

reddit · r/MachineLearning · /u/Automatic-Forever-63 · Jul 17, 08:18

**Background**: RAG (Retrieval-Augmented Generation) combines retrieval of relevant document chunks with a language model to answer queries. The EU AI Act (Regulation 2024/1689) is a comprehensive European law on artificial intelligence. BGE-M3 is a multilingual embedding model supporting dense, sparse, and multi-vector retrieval modes for inputs up to 8192 tokens.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/html/2402.03216v3">BGE M 3 - Embedding : Multi-Lingual, Multi-Functionality...</a></li>
<li><a href="https://en.wikipedia.org/wiki/EUR-Lex">EUR-Lex</a></li>

</ul>
</details>

**Tags**: `#RAG`, `#EU AI Act`, `#legal NLP`, `#BGE-M3`, `#SQLite`

---

<a id="item-12"></a>
## [ExTernD: Expanded-Rank Ternary Decomposition for Accurate LLM PTQ](https://www.reddit.com/r/MachineLearning/comments/1uy2zb3/externd_expandedrank_ternary_decomposition/) ⭐️ 8.0/10

ExTernD proposes a novel ternary decomposition method that represents a matrix as the product of two ternary matrices and a diagonal scaling matrix, allowing the inner rank to be arbitrarily large to minimize quantization error. This method enables LLM post-training quantization to achieve accuracy approaching any desired quantization level while requiring only slightly more VRAM than current approaches, making high-quality model compression more practical for deployment. The approach addresses the dead-end of fixed-size ternary matrices by expanding the rank; it leverages ternary arithmetic to maintain efficiency, with the slight VRAM increase justified by the accuracy gains.

reddit · r/MachineLearning · /u/LMTLS5 · Jul 16, 13:31

**Background**: Post-training quantization (PTQ) compresses pre-trained models without retraining by reducing weight precision, commonly to INT8 or ternary values {-1,0,+1}. Existing ternary PTQ methods use fixed-size ternary matrices, which limit representation capacity and accuracy. ExTernD breaks this limitation by decomposing the weight matrix into a product of two ternary matrices and a diagonal scaling matrix, effectively increasing the representational rank.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/html/2602.07374v2">TernaryLM: Memory-Efficient Language Modeling via Native 1.5-Bit Quantization with Adaptive Layer-wise Scaling</a></li>
<li><a href="https://developer.nvidia.com/blog/optimizing-llms-for-performance-and-accuracy-with-post-training-quantization/">Optimizing LLMs for Performance and Accuracy with Post-Training Quantization | NVIDIA Technical Blog</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#quantization`, `#ternary decomposition`, `#PTQ`, `#model compression`

---

<a id="item-13"></a>
## [TSMC Announces $100B More US Investment, Q2 Profit Soars 77%](https://www.reuters.com/world/asia-pacific/tsmcs-second-quarter-profit-seen-hitting-record-ai-boom-2026-07-15/) ⭐️ 8.0/10

TSMC announced an additional $100 billion investment in Arizona, bringing total US investment to $265 billion. The company also reported a 77% year-over-year profit surge to NT$706.6 billion ($22 billion) for Q2 2026, a record high. This massive investment and record profit underscore TSMC's central role in the AI-driven semiconductor boom. The expansion strengthens US chip manufacturing capacity and reshapes global supply chains, with significant geopolitical implications. TSMC raised its 2026 capital expenditure forecast to $60-$64 billion and expects full-year USD revenue growth of slightly over 40%. Arizona currently has 8 fabs under construction or planned, with potential for 4 more.

telegram · zaihuapd · Jul 16, 12:29

**Background**: TSMC is the world's largest dedicated semiconductor foundry, supplying chips to companies like Apple, NVIDIA, and AMD. The AI boom has dramatically increased demand for advanced chips, leading to TSMC's record profits. The US investment is part of a strategic push to diversify manufacturing away from Taiwan, amid geopolitical tensions.

**Tags**: `#semiconductor`, `#TSMC`, `#AI investment`, `#manufacturing`, `#supply chain`

---

<a id="item-14"></a>
## [Huawei unveils Ascend 950 SuperPod, claims 6.7x Nvidia compute](https://www.ithome.com/0/978/019.htm) ⭐️ 8.0/10

At the 2026 World AI Conference (WAIC), Huawei publicly demonstrated the Ascend 950 SuperPod (Atlas 950 SuperPoD) for the first time, based on the Lingqu interconnect protocol and super-node architecture. It achieves a scale of 1024 cards, delivering 1 EFLOPS FP8 and 2 EFLOPS FP4 compute, with 256 TB unified global memory, and is claimed to offer 6.7 times the total compute of Nvidia's 144-card NVL144 system. This announcement positions Huawei as a strong competitor in high-performance AI computing, potentially challenging Nvidia's dominance in the Chinese market amid ongoing export restrictions. If performance claims are verified, it could accelerate AI model training in China and reduce reliance on foreign hardware. The Ascend 950 SuperPod supports TB-scale NPU interconnect bandwidth and 3μs ultra-low RTT latency. Additionally, the Ascend 384 SuperPod has been commercially deployed in over 750 systems across internet, telecom, and finance sectors, and is the only supernode in China that has trained SOTA models.

telegram · zaihuapd · Jul 17, 10:27

**Background**: The Lingqu (UnifiedBus) interconnect protocol is Huawei's proprietary solution for connecting large-scale computational resources in super-node architectures. Super-nodes use high-bandwidth, low-latency interconnects to pool GPUs or NPUs into a single logical unit for AI workloads. FP8 and FP4 are low-precision floating-point formats used to accelerate inference and training with minimal accuracy loss.

<details><summary>References</summary>
<ul>
<li><a href="https://finance.jrj.com.cn/2026/07/17201957836496.shtml">华为昇腾950超节点真机首次公开亮相！业界最大1024卡规模-财经-金融界</a></li>
<li><a href="https://www.nbd.com.cn/articles/2025-09-18/4065524.html">突破大规模超节点 互 联 技术 华为发布 互 联 协 议 “ 灵 衢 ” | 每经网</a></li>
<li><a href="https://www.163.com/dy/article/L21UARTB0511B8LM.html">华为昇腾950超节点真机首次公开亮相|算法|内存|引擎|新模型|知名企业|atlas_网易订阅</a></li>

</ul>
</details>

**Tags**: `#AI hardware`, `#Huawei`, `#Ascend`, `#supercomputing`

---

<a id="item-15"></a>
## [US lawmakers seek ban on Chinese memory chips in allied supply chains](https://www.tomshardware.com/pc-components/dram/lawmakers-want-us-government-to-ban-memory-chips-from-china-even-in-allied-supply-chains-citing-unacceptable-risk-to-national-economic-and-supply-chain-security) ⭐️ 8.0/10

US House committee chair John Moolenaar and Representative George Whitesides sent a letter to Commerce Secretary Howard Lutnick urging a ban on US companies purchasing Chinese memory chips from CXMT and YMTC, and calling for CXMT to be added to the Entity List with further restrictions on YMTC. This move could significantly disrupt global memory chip supply chains, affecting major US tech companies like Apple that are seeking Chinese sources, and escalate the US-China tech war by preventing Chinese manufacturers from gaining a foothold in allied supply chains, especially for AI infrastructure components. The lawmakers argue that Chinese memory chip makers have close ties to the People's Liberation Army, and each purchase could directly fund the development of dual-use technologies, posing an unacceptable risk to national, economic, and supply chain security.

telegram · zaihuapd · Jul 17, 14:00

**Background**: ChangXin Memory Technologies (CXMT) is a Chinese DRAM manufacturer based in Hefei, specializing in DRAM chip design, R&D, and production. Yangtze Memory Technologies Co. (YMTC) is a Chinese NAND flash maker known for its Xtacking technology. The Entity List is a US trade restriction list that can effectively block companies from receiving US-origin goods and technology.

<details><summary>References</summary>
<ul>
<li><a href="https://zh.wikipedia.org/zh-cn/长鑫存储">长 鑫 存 储 - 维基百科，自由的百科全书</a></li>
<li><a href="https://developer.aliyun.com/article/1100149">长 江 存 储 YMTC Xtacking技术演进与芯片级解密-开发者社区-阿里云</a></li>
<li><a href="https://laoyaoba.com/n/958833">突发！ 美 将复旦微等23家中企列入 实 体 清 单 ， 含 13家集成电路企业</a></li>

</ul>
</details>

**Tags**: `#semiconductors`, `#supply chain`, `#geopolitics`, `#memory chips`, `#US-China tech war`

---

<a id="item-16"></a>
## [OpenAI CFO proposes 'useful intelligence per dollar' metric for AI ROI](https://openai.com/index/a-scorecard-for-the-ai-age) ⭐️ 8.0/10

OpenAI CFO Sarah Friar introduced a new framework centered on 'useful intelligence per dollar' to measure AI ROI, moving beyond traditional adoption metrics. She also highlighted the GPT-5.6 series, where the flagship Sol model achieves up to 54% fewer output tokens on coding tasks compared to a leading competitor. This shift provides a more direct measure of AI's business value, helping enterprises evaluate whether AI investments truly generate return beyond cost savings. It also encourages adoption of more capable models that may be more cost-effective per task despite higher per-token prices. The framework includes four dimensions: useful work completed, full cost per successful task, output reliability, and increasing value per dollar with scale. Friar emphasized that lowest token price does not equal lowest task cost, as more powerful models may solve tasks in fewer tokens.

telegram · zaihuapd · Jul 17, 15:00

**Background**: Traditional software ROI metrics like user count or license renewals are inadequate for AI, where value comes from task automation and productivity gains. 'Useful intelligence per dollar' aims to capture the net value created by AI relative to its total cost, akin to metrics like cost per task or intelligence per dollar.

<details><summary>References</summary>
<ul>
<li><a href="https://blogs.nvidia.com/blog/nvidia-vera-rubin-post-training-intelligence-per-dollar/">NVIDIA Vera Rubin Maximizes Intelligence per Dollar ... | NVIDIA Blog</a></li>
<li><a href="https://developers.openai.com/api/docs/models/gpt-5.6-sol">GPT - 5 . 6 Sol Model | OpenAI API</a></li>

</ul>
</details>

**Tags**: `#AI`, `#ROI`, `#指标`, `#OpenAI`, `#成本效益`

---

<a id="item-17"></a>
## [Which Lisp to Choose? A Guide to Common Lisp, Scheme, Clojure, Racket](https://scotto.me/blog/2026-07-17-which-lisp/) ⭐️ 7.0/10

A new article provides a comparative guide to four major Lisp dialects—Common Lisp, Scheme, Clojure, and Racket—helping newcomers decide based on use case and philosophy. This guide addresses a common pain point for developers interested in Lisp but overwhelmed by dialect choices, lowering the barrier to entry and helping learners invest time wisely. The article overlooks the 'liveness' advantage of Common Lisp and Clojure (image-based development) versus Racket's batch compilation, and Common Lisp's arbitrarily extensible syntax via reader macros is not emphasized.

hackernews · silcoon · Jul 17, 13:56 · [Discussion](https://news.ycombinator.com/item?id=48947455)

**Background**: Lisp is a family of programming languages known for fully parenthesized prefix notation and powerful macro systems. Common Lisp is multi-paradigm; Scheme is minimalist; Clojure runs on the JVM, emphasizes immutability; Racket is designed for language creation. Each dialect has distinct communities and tools.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Clojure_(programming_language)">Clojure (programming language)</a></li>
<li><a href="https://en.wikipedia.org/wiki/Racket_(programming_language)">Racket (programming language)</a></li>

</ul>
</details>

**Discussion**: Commenters share personal experiences: one appreciates the 'camps' breakdown while re-studying SICP in DrRacket; another wishes for a hybrid of features; a third credits HTDP with Racket for transforming their learning. A notable point is the lack of emphasis on liveness in CL/Clojure.

**Tags**: `#Lisp`, `#Common Lisp`, `#Scheme`, `#Clojure`, `#Racket`

---

<a id="item-18"></a>
## [SSH honeypot live visualization shows bot login attempts](https://honeypotlive.cc/) ⭐️ 7.0/10

A live visualization at honeypotlive.cc displays real-time SSH login attempts from bots targeting a honeypot, exposing the constant background noise on public IPs. This project makes visible the often invisible automated attacks that constantly probe public-facing servers, raising awareness about internet background noise and the importance of security. The honeypot likely emulates an SSH service to capture bot usernames, passwords, and commands, with the community suggesting improvements like rotating keyed hashes to protect actual credentials displayed.

hackernews · tusksm · Jul 17, 14:05 · [Discussion](https://news.ycombinator.com/item?id=48947548)

**Background**: An SSH honeypot is a decoy server that mimics an SSH service to log attack attempts, helping researchers study bot behavior and attack patterns. Internet background noise refers to unsolicited packets from botnets, scanners, and misconfigured devices that constantly probe IP addresses.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Internet_background_noise">Internet background noise</a></li>
<li><a href="https://www.infragistics.com/blogs/using-an-ssh-honeypot">What I Learned After Using an SSH Honeypot for 7 Days</a></li>

</ul>
</details>

**Discussion**: The community expressed amusement and recognition of the project's value, with users noting the surprising volume of traffic and offering constructive feedback like exposing rotated keyed hashes instead of raw credentials for better privacy.

**Tags**: `#SSH`, `#honeypot`, `#security`, `#visualization`, `#bots`

---

<a id="item-19"></a>
## [EEG Study Shows Brain Can Encode Two Speech Streams Simultaneously](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.3003876) ⭐️ 7.0/10

A study using EEG found that the human brain can simultaneously encode two distinct speech streams, even when attentional focus is on one stream. This challenges the traditional view that the brain processes only one attended speech stream at a time. This finding deepens our understanding of selective attention and auditory processing, with potential implications for improving hearing aids, communication in noisy environments, and cognitive training. The study also resonates with personal anecdotes from pilots and mindfulness practitioners. The study used EEG to measure neural responses to two speech streams presented simultaneously, showing that both streams are encoded in the brain's neural activity, not just the attended one. The effect was observed in a cortical area known to process speech, and the degree of simultaneous encoding varied between individuals.

hackernews · giuliomagnifico · Jul 17, 05:51 · [Discussion](https://news.ycombinator.com/item?id=48943745)

**Background**: EEG (electroencephalogram) measures electrical activity in the brain and is commonly used to study brain function and diagnose conditions. The 'cocktail party effect' is a well-known phenomenon where a person can focus on one conversation in a noisy room, and this study shows that the brain actually processes multiple speech streams at a neural level even when focusing on one. Previous research suggested that unattended speech is largely suppressed, but this study indicates it is still encoded.

<details><summary>References</summary>
<ul>
<li><a href="https://www.mayoclinic.org/tests-procedures/eeg/about/pac-20393875">EEG (electroencephalogram) - Mayo Clinic</a></li>
<li><a href="https://en.wikipedia.org/wiki/Cocktail_party_effect">Cocktail party effect - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters shared personal experiences: a pilot noted they can process two audio streams simultaneously, and a reader mentioned that while reading aloud, they maintain independent thoughts, sometimes causing word substitutions. Others linked the finding to Richard Feynman's self-experiments on divided attention and to mindfulness practices that focus on two things at once.

**Tags**: `#neuroscience`, `#cognitive science`, `#speech`, `#attention`, `#brain`

---

<a id="item-20"></a>
## [Apple Sends Retention Letters to Former Employees at OpenAI](https://www.ft.com/content/1b8c9d52-88a9-426b-ba47-f1811f859166) ⭐️ 7.0/10

Apple has sent document retention letters to dozens of former employees who now work at OpenAI, likely over concerns about non-compete agreements or trade secrets. This legal move signals heightened tension between two major tech players over talent poaching and intellectual property, potentially impacting the AI industry's workforce dynamics. The letters are a standard legal precaution to preserve evidence, but they can be a precursor to litigation if Apple believes trade secrets were misappropriated.

hackernews · merksittich · Jul 17, 12:02 · [Discussion](https://news.ycombinator.com/item?id=48946303)

**Background**: Document retention letters are formal requests to preserve relevant records when litigation is reasonably anticipated, often used in employment disputes. Apple and OpenAI compete for top AI talent, and non-compete clauses are common in the tech industry to protect proprietary information.

**Discussion**: Community opinions vary: some view the letters as standard practice rather than an escalation, while others suggest Apple must have strong evidence to act, and a few criticize OpenAI's history with content theft, implying consistency in their behavior.

**Tags**: `#legal`, `#Apple`, `#OpenAI`, `#talent poaching`, `#employment law`

---

<a id="item-21"></a>
## [Pebble Mega Update Reveals Index 01, Community Criticizes Flaws](https://repebble.com/blog/pebble-mega-update-july-2026) ⭐️ 7.0/10

Pebble's July 2026 mega update announced the Index 01, a wearable ring designed as 'external memory for your brain', but community feedback has highlighted major issues including misleading battery life claims, problematic sizing, a non-rechargeable design, and a 30-day warranty. This controversy matters because it underscores growing consumer skepticism toward wearable devices with aggressive marketing claims and anti-repair design choices, potentially affecting Pebble's reputation and the broader wearable market's trust. The Index 01 is a $75 ring with a microphone that records 3-6 second voice snippets; Pebble claims a 2-year battery life based on this limited daily usage, while actual continuous use yields only 12-15 hours. The device is non-rechargeable and comes with a 30-day warranty.

hackernews · crazysaem · Jul 17, 03:53 · [Discussion](https://news.ycombinator.com/item?id=48943174)

**Background**: The Pebble Index 01 is a wearable ring that stores voice memos and sends them to the user's phone. It is designed to capture fleeting thoughts without needing a screen or internet connection. Pebble, known for its earlier smartwatches, is now focusing on minimalist wearable memory aids.

<details><summary>References</summary>
<ul>
<li><a href="https://repebble.com/index">Pebble Index 01 - External Memory For Your Brain</a></li>
<li><a href="https://repebble.com/blog/meet-pebble-index-01-external-memory-for-your-brain">Meet Pebble Index 01 - External Memory For Your Brain | rePebble Blog</a></li>

</ul>
</details>

**Discussion**: Community sentiment is overwhelmingly negative, with commenters calling the Index 01 'ludicrous' and criticizing the battery life as misrepresentation. Sizing issues and the non-rechargeable design were also heavily criticized. Some users gave Pebble a 'pass' due to the company's early stage, but most demanded better consumer practices.

**Tags**: `#hardware`, `#wearable`, `#controversy`, `#battery-life`, `#product-launch`

---

<a id="item-22"></a>
## [Mermaid to ASCII Art Comes to Browser via Go WebAssembly](https://simonwillison.net/2026/Jul/16/mermaid-ascii/#atom-everything) ⭐️ 7.0/10

Simon Willison compiled the Go-based mermaid-ascii library to WebAssembly, enabling browser-based conversion of Mermaid diagrams to ASCII art with color support, and compared it with a Rust-based version. This provides a practical, browser-accessible tool for developers who want quick ASCII representations of Mermaid diagrams, and highlights the growing trend of compiling existing libraries to WebAssembly for web deployment. The Go library includes color support and more features than the earlier Rust-based version. The tool runs entirely in the browser using WebAssembly, with no server-side processing.

rss · Simon Willison · Jul 16, 14:57

**Background**: Mermaid is an open-source tool for creating diagrams from Markdown-like text. WebAssembly (Wasm) is a binary instruction format that allows code written in languages like Go to run in web browsers at near-native speed. The mermaid-ascii Go library converts Mermaid syntax into ASCII and Unicode box-drawing art.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mermaid_(software)">Mermaid (software) - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/WebAssembly">WebAssembly - Wikipedia</a></li>
<li><a href="https://pkg.go.dev/github.com/pgavlin/mermaid-ascii">mermaid-ascii command - github.com/pgavlin/mermaid-ascii - Go Packages</a></li>

</ul>
</details>

**Tags**: `#Mermaid`, `#ASCII art`, `#WebAssembly`, `#developer tools`, `#Go`

---

<a id="item-23"></a>
## [Prism Bug Leaks Other Users' Papers via Compilation](https://www.reddit.com/r/MachineLearning/comments/1uz75qt/prism_accidentally_leaked_d/) ⭐️ 7.0/10

A bug in Prism's compilation feature inadvertently exposed other users' papers, causing a data leak. The service was taken down within 10 minutes of the report. This raises serious privacy concerns for researchers using Prism, as sensitive unpublished papers could be leaked. It highlights the risks of cloud-based AI research tools. The bug occurred when using the compilation feature, returning another user's paper instead of the intended one. Prism's team responded quickly, but users are worried their own papers may have been exposed.

reddit · r/MachineLearning · /u/Few-Monitor5103 · Jul 17, 17:59

**Background**: Prism is an AI-powered workspace for scientific paper writing, integrated with advanced language models. It offers features like compilation and revision. This bug compromised user data isolation, potentially exposing private research.

<details><summary>References</summary>
<ul>
<li><a href="https://techcrunch.com/2026/01/27/openai-launches-prism-a-new-ai-workspace-for-scientists/">OpenAI launches Prism , a new AI workspace for scientists | TechCrunch</a></li>
<li><a href="https://blog.gopenai.com/openai-prism-free-ai-for-research-papers-in-latex-powered-by-gpt-5-2-472a21dcca07">OpenAI Prism : Free AI for Research Papers in LaTeX... | GoPenAI</a></li>

</ul>
</details>

**Discussion**: The Reddit post shows user concern and appreciation for the quick response. The community is worried about the implications for their own papers but acknowledges the prompt action.

**Tags**: `#machine learning`, `#security`, `#data leak`, `#privacy`, `#paper compilation`

---

<a id="item-24"></a>
## [DABSN: New Recurrent Language Model Architecture Seeks Collaborators](https://www.reddit.com/r/MachineLearning/comments/1uycffg/seeking_collaborators_for_scaling_and_independent/) ⭐️ 7.0/10

An independent researcher has released a preprint and open-source code for DABSN, a novel recurrent architecture that shows strong performance on reasoning and long-sequence benchmarks, and is now seeking collaborators to scale it to larger language models. This work could provide an alternative to Transformer-based architectures, potentially offering better efficiency for long-context tasks. If successfully scaled, DABSN might influence the direction of future language model design, especially for applications requiring long memory and reasoning. The architecture, called Dynamic Adaptive Bias State Network (DABSN), includes PyTorch, C++, and Triton implementations for reproducibility. The author has trained a 24M-parameter language model on 1B tokens using GPT-2 tokenizer and is now writing a second paper focused on scaling and long-context behavior.

reddit · r/MachineLearning · /u/BleedingXiko · Jul 16, 19:17

**Background**: Recurrent neural networks (RNNs) were once dominant for sequential data but were largely superseded by Transformer architectures due to parallelization advantages. However, Transformers suffer from quadratic attention costs for long sequences. New recurrent architectures like DABSN aim to combine the parallel training of RNNs with linear or near-linear memory scaling, reviving interest in alternatives to attention. Benchmarks like MQAR (Multi-Query Associative Recall) test models' ability to perform multiple key-value lookups, a key reasoning capability.

<details><summary>References</summary>
<ul>
<li><a href="https://www.emergentmind.com/topics/multi-query-associative-recall-mqar">MQAR: Multi-Query Associative Recall</a></li>
<li><a href="https://triton-lang.org/main/">Welcome to Triton ’s documentation! — Triton documentation</a></li>

</ul>
</details>

**Tags**: `#machine learning`, `#recurrent neural networks`, `#language models`, `#architecture`, `#open source`

---

<a id="item-25"></a>
## [QLoRA default learning rate 2e-4 causes overfitting on small datasets](https://www.reddit.com/r/MachineLearning/comments/1uy1z8b/the_qlora_2e4_default_is_wrong_under_10k_samples/) ⭐️ 7.0/10

A Reddit user reports that the default QLoRA learning rate of 2e-4 leads to overfitting when fine-tuning on fewer than 10k samples, and reducing it to 1e-4 significantly improves evaluation performance. This finding challenges a widely adopted default in QLoRA fine-tuning tutorials and documentation, potentially saving practitioners weeks of wasted effort on small datasets. It highlights the importance of hyperparameter tuning specific to dataset size. The user observed that training loss decreased but evaluation loss stagnated or increased with 2e-4, symptoms of overfitting. Switching to 1e-4 and increasing epoch count from 3 to 5 yielded the best results, while recommending starting at 1e-4 or lower for datasets under 10k samples.

reddit · r/MachineLearning · /u/Pretty-Ad774 · Jul 16, 12:50

**Background**: QLoRA (Quantized Low-Rank Adaptation) is a method for fine-tuning large language models efficiently by combining 4-bit quantization with LoRA, reducing memory usage. The default learning rate of 2e-4 originated from fine-tuning on the Alpaca dataset with 52k samples, but may not generalize to smaller datasets.

<details><summary>References</summary>
<ul>
<li><a href="https://medium.com/@levxn/lora-and-qlora-effective-methods-to-fine-tune-your-llms-in-detail-6e56a2a13f3c">LoRA and QLoRA - Effective methods to Fine-tune your... | Medium</a></li>
<li><a href="https://github.com/artidoro/qlora">GitHub - artidoro/ qlora : QLoRA : Efficient Finetuning of Quantized LLMs</a></li>
<li><a href="https://unsloth.ai/">Unsloth - Train and Run Models Locally</a></li>

</ul>
</details>

**Tags**: `#QLoRA`, `#fine-tuning`, `#learning rate`, `#overfitting`, `#small datasets`

---

<a id="item-26"></a>
## [EU Draft May Force Google to Open Android to Rival AI Assistants](https://t.me/zaihuapd/42615) ⭐️ 7.0/10

The European Union is considering draft regulations that would require Google to grant rival AI assistants, such as ChatGPT and Claude, the same system-level permissions as its own Gemini assistant on Android devices. This could significantly reshape competition in the AI assistant market by reducing Google's gatekeeper advantage on Android, potentially leading to more choice for users and greater pressure on Google to maintain privacy and security standards. The regulation is based on the EU's Digital Markets Act and is still in draft stage, with possible delays. Violations could result in fines up to 10% of Google's global revenue.

telegram · zaihuapd · Jul 16, 13:19

**Background**: Android is an open-source mobile operating system, but Google controls key system integrations like the default AI assistant. The EU Digital Markets Act aims to prevent large platforms from favoring their own services. Rival AI assistants currently lack full access to certain Android system functions, limiting their capabilities compared to Google's Gemini.

<details><summary>References</summary>
<ul>
<li><a href="https://en.actualidadgadget.com/The-EU-is-putting-pressure-on-Google-and-forcing-it-to-open-Android-to-AI-assistants-that-rival-Gemini./">The EU puts pressure on Google and forces it to open Android to AI ...</a></li>
<li><a href="https://www.heise.de/en/news/EU-Requirements-Android-must-fully-open-up-for-third-party-AI-assistants-11367823.html">EU Requirements: Android must fully open up for third - party AI ...</a></li>
<li><a href="https://www.trendingtopics.eu/eu-forces-google-to-open-android-to-third-party-ai-assistants/">EU Forces Google to Open Android to Third - Party AI Assistants ...</a></li>

</ul>
</details>

**Tags**: `#Android`, `#AI Assistant`, `#EU Regulation`, `#Google`, `#Competition`

---

<a id="item-27"></a>
## [1Password Integrates with Claude for Secure AI Login](https://9to5mac.com/2026/07/16/1password-now-lets-claude-sign-in-to-websites-without-seeing-your-passwords/) ⭐️ 7.0/10

1Password has launched an integration with Anthropic's Claude AI assistant on Mac, allowing Claude to log into websites on behalf of users by injecting credentials directly into the page, without Claude ever seeing the passwords or 2FA codes. This integration addresses a critical privacy and security concern in the age of AI agents: enabling automated tasks like booking travel or managing accounts without exposing sensitive credentials to the AI model. It could set a standard for secure delegation of authentication to AI agents. The feature requires both 1Password and Claude desktop and browser extensions on Mac, and uses biometric approval per session for each credential request. If automatic fill fails, the injected credentials are immediately erased.

telegram · zaihuapd · Jul 16, 15:54

**Background**: Password managers like 1Password store login credentials and can auto-fill them on websites, but traditionally they do not interact with AI agents. With the rise of AI assistants that can perform tasks for users, there is a need to grant them access to websites without handing over passwords. 1Password's approach uses a secure channel for credential injection, ensuring the AI never sees the sensitive data.

<details><summary>References</summary>
<ul>
<li><a href="https://www.engadget.com/2216405/1password-anthropic-claude-integration/">You can now grant Claude access to your 1Password credentials - Engadget</a></li>
<li><a href="https://1password.com/blog/1password-for-claude">1Password for Claude: Give Claude access without giving up your credentials | 1Password</a></li>
<li><a href="https://www.macrumors.com/2026/07/16/1password-claude-integration/">1Password for Claude Lets AI Log In Without Seeing Your Passwords - MacRumors</a></li>

</ul>
</details>

**Tags**: `#password management`, `#AI agent`, `#security`, `#1Password`, `#Claude`

---

<a id="item-28"></a>
## [Truth Social to Sell Millisecond Access to Trump's Posts to Wall Street](https://www.cnn.com/2026/07/16/business/truth-social-data-wall-street) ⭐️ 7.0/10

Truth Social announced it will sell an API called Truth API providing millisecond-speed access to real-time posts from the top 10 accounts to institutional clients for algorithmic trading, starting August 1. This monetization of Trump's social media posts for algorithmic trading raises concerns about market manipulation and the blurring of lines between political communication and financial markets, potentially setting a precedent for other platforms. The API targets the top 10 accounts on Truth Social, with Trump being the primary driver of market impact; pricing has not been disclosed, and TMTG describes this as a strategic step to monetize proprietary assets.

telegram · zaihuapd · Jul 17, 01:02

**Background**: Truth Social is built on a fork of Mastodon, an open-source social platform that has a documented API, but Truth Social never opened a developer program until now. High-frequency traders often use direct market access or colocation services to reduce latency. The API sale marks TMTG's first step into data licensing and a new revenue stream.

<details><summary>References</summary>
<ul>
<li><a href="https://www.theglobeandmail.com/business/article-truth-social-trump-banks-access/">Truth Social sells API granting faster access to... - The Globe and Mail</a></li>
<li><a href="https://1322.io/blog/truth-social-api-guide">Truth Social API : The Complete Guide to Real-Time Monitoring...</a></li>
<li><a href="https://fisf.fudan.edu.cn/show-80-3700.html?tid=0">施东辉： 高 频 交 易 ，天使还是魔鬼？ | 复旦大学国际金融学院(FISF)...</a></li>

</ul>
</details>

**Tags**: `#API`, `#Data Monetization`, `#Algorithmic Trading`, `#Social Media`, `#Politics & Markets`

---

<a id="item-29"></a>
## [Tesla Cybercab enters production in North America](https://t.me/zaihuapd/42621) ⭐️ 7.0/10

Tesla has announced that its fully autonomous Cybercab has entered mass production in North America. The vehicle is designed without a steering wheel, pedals, or mirrors, relying entirely on onboard AI for driving. This milestone advances Tesla's Robotaxi plans, potentially disrupting the ride-hailing industry. It signals growing confidence in fully autonomous vehicle deployment. The Cybercab is a two-passenger battery-electric vehicle designed exclusively for autonomous operation. Production started in February 2026, approximately 16 months after its concept unveiling in October 2024.

telegram · zaihuapd · Jul 17, 03:06

**Background**: Robotaxis are autonomous vehicles (SAE Level 4 or 5) operated by ride-hailing services. Tesla's Cybercab relies on its Full Self-Driving (FSD) software. Tesla launched a limited Robotaxi service in Austin, Texas in June 2025, using current Tesla vehicles equipped with FSD. Despite progress, public trust remains low; a 2025 AAA survey found only 13% of respondents would trust a self-driving vehicle.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Cybercab">Cybercab</a></li>
<li><a href="https://en.wikipedia.org/wiki/Robotaxi">Robotaxi</a></li>
<li><a href="https://www.caranddriver.com/news/a71590701/tesla-cybercab-specs-epa-documents-revealed/">We Have New Tesla Cybercab Specs Before You're Supposed to See Them Thanks to EPA Documents</a></li>

</ul>
</details>

**Tags**: `#Tesla`, `#autonomous driving`, `#Cybercab`, `#Robotaxi`, `#electric vehicles`

---

<a id="item-30"></a>
## [Rethinking AI Memory: From Facts to Reasoning Patterns](https://www.reddit.com/r/MachineLearning/comments/1uy6yht/are_current_ai_memory_architectures_optimizing/) ⭐️ 6.0/10

A Reddit post proposes that AI memory systems should shift from storing descriptive facts about users to inferring higher-level patterns such as reasoning styles and explanatory frameworks. This idea challenges the current design of AI memory and persistent context, potentially leading to more personalized and adaptive AI systems that understand how users think, not just what they say. The post contrasts current memory mechanisms (saved facts, preferences, summaries) with a hypothetical system that continuously refines an evolving model of the user's cognitive patterns, such as preferring explanations via incentives versus systems thinking.

reddit · r/MachineLearning · /u/Boris_Ljevar · Jul 16, 16:00

**Background**: Current AI memory systems typically store explicit facts and summaries to maintain context across interactions. This post suggests an alternative where memory captures abstract reasoning patterns, which could require fundamentally different architectures from today's retrieval-based approaches.

**Tags**: `#AI memory`, `#persistent context`, `#cognitive architectures`, `#machine learning`, `#abstraction`

---

<a id="item-31"></a>
## [RTCA Workshop at NeurIPS 2026 Issues Call for Papers](https://www.reddit.com/r/MachineLearning/comments/1uy8e0v/cfp_rtca_neurips_2026_r/) ⭐️ 6.0/10

The first Real-Time Conversational Agents (RTCA) workshop at NeurIPS 2026 has opened its call for papers and demos, inviting submissions on streaming speech, video, and language generation, natural interaction, and live system evaluation. This workshop addresses the critical challenge of real-time interaction in conversational AI, which is essential for natural human-AI communication and currently lacks shared benchmarks and methodology. Submissions are due August 29, 2026, and can be full papers (up to 8 pages), short papers (up to 4 pages), or demo papers (up to 2 pages), using the NeurIPS 2026 double-blind style. The workshop is non-archival, allowing authors to publish elsewhere.

reddit · r/MachineLearning · /u/Few-Ferret9700 · Jul 16, 16:51

**Background**: Traditional conversational AI systems operate offline, processing input in full before responding, which leads to unnatural pauses. Real-time agents must stream audio and video continuously, handling interruptions, backchannels, and turn-taking. Full-duplex communication allows both parties to speak simultaneously, as in human conversations. This workshop aims to establish evaluation standards and foster research in these emerging capabilities.

<details><summary>References</summary>
<ul>
<li><a href="https://duplexio.ai/">duplexio - Full - Duplex Conversational AI</a></li>
<li><a href="https://en.wikipedia.org/wiki/Backchannel">Backchannel - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#NeurIPS`, `#conversational AI`, `#real-time`, `#multimodal`, `#workshop`

---

<a id="item-32"></a>
## [Starship 13th Test Flight Auto-Aborts at Last Second](https://apnews.com/article/starship-spacex-rocket-musk-nasa-455927b93b0fdc5512a4567a53eb3228) ⭐️ 6.0/10

SpaceX's Starship test flight was automatically aborted about three seconds before liftoff due to four Raptor engines failing to ignite, marking the first last-second abort for the full-size Starship. SpaceX plans to replace two engines and retry as early as next week. This abort demonstrates the reliability of Starship's automated abort system, but also highlights ongoing engine ignition issues that could delay the program's progress. As SpaceX's first Starship test since its Nasdaq listing, the outcome may affect investor confidence and the timeline for deploying Starlink satellites. The abort occurred when the engine controller detected that four of the 33 Raptor engines did not start properly, triggering an automatic shutdown of all 29 remaining engines less than one second before liftoff. The mission was planned to be a one-hour coast flight carrying 20 next-generation Starlink satellites, with no recovery of the first stage or ship.

telegram · zaihuapd · Jul 17, 06:11

**Background**: A rocket launch abort system automatically stops a launch if critical issues are detected, protecting the vehicle and payload. Starship uses 33 Raptor engines on its Super Heavy booster; ignition failures are a known challenge due to the complexity of cryogenic methane-oxygen engines. SpaceX has been iterating rapidly on Starship, with previous flights experiencing engine failures, but this is the first last-second abort for the full stack.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Launch_escape_system">Launch escape system - Wikipedia</a></li>
<li><a href="https://spacedaily.com/sd-the-raptor-3-was-supposed-to-be-the-engine-that-finally-ended-starships-reliability-problem-instead-on-its-first-flight-several-of-them-quit-less-than-20-seconds-into-the-boostback-bu/">The Raptor 3 was supposed to be the engine that finally ended Starship's reliability problem — instead, on its first flight, several of them quit less than 20 seconds into the boostback burn, dropping the booster into the Gulf and grounding the whole program for a federal mishap review</a></li>
<li><a href="https://easternherald.com/2026/07/17/spacex-starship-v3-abort-raptor-engines/">SpaceX Aborts Second Starship V3 Launch After Raptor Engines Fail at Ignition</a></li>

</ul>
</details>

**Tags**: `#SpaceX`, `#Starship`, `#spaceflight`, `#rocket test`, `#engine failure`

---