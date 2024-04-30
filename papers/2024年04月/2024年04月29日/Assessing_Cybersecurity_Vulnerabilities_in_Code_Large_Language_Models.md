# 探究大型语言模型代码中的网络安全薄弱环节

发布时间：2024年04月29日

`LLM应用` `网络安全` `软件开发`

> Assessing Cybersecurity Vulnerabilities in Code Large Language Models

# 摘要

> 随着AI编程助手的广泛应用，指令调整的代码大型语言模型（Code LLMs）正逐渐成为开发领域的新宠。但这些模型的网络安全风险尚未充分揭示，主要原因在于相关领域的研究尚不深入。为填补这一研究空白，本文介绍了EvilInstructCoder框架，旨在专门评估这些模型在面对敌意攻击时的网络安全脆弱性。该框架通过引入对抗性代码注入引擎，自动化生成并注入恶意代码片段，以此污染指令调整的数据集。它还模拟了多种现实世界的威胁模式，以评估Code LLMs在不同对抗性攻击情境下的脆弱性。通过EvilInstructCoder，我们对三款顶尖的Code LLM模型——CodeLlama、DeepSeek-Coder和StarCoder2——在多样的敌意攻击情境下的安全性进行了深入分析。研究发现，这些模型存在显著的安全漏洞，攻击者可以轻易诱导模型在良性代码中嵌入恶意负载。特别是在后门攻击情境中，仅需污染0.5%的指令数据集样本，就能使攻击成功率达到76%至86%。本研究不仅揭示了指令调整的Code LLMs所面临的严峻网络安全挑战，也强调了开发强大防御机制以应对这些风险的紧迫性。

> Instruction-tuned Code Large Language Models (Code LLMs) are increasingly utilized as AI coding assistants and integrated into various applications. However, the cybersecurity vulnerabilities and implications arising from the widespread integration of these models are not yet fully understood due to limited research in this domain. To bridge this gap, this paper presents EvilInstructCoder, a framework specifically designed to assess the cybersecurity vulnerabilities of instruction-tuned Code LLMs to adversarial attacks. EvilInstructCoder introduces the Adversarial Code Injection Engine to automatically generate malicious code snippets and inject them into benign code to poison instruction tuning datasets. It incorporates practical threat models to reflect real-world adversaries with varying capabilities and evaluates the exploitability of instruction-tuned Code LLMs under these diverse adversarial attack scenarios. Through the use of EvilInstructCoder, we conduct a comprehensive investigation into the exploitability of instruction tuning for coding tasks using three state-of-the-art Code LLM models: CodeLlama, DeepSeek-Coder, and StarCoder2, under various adversarial attack scenarios. Our experimental results reveal a significant vulnerability in these models, demonstrating that adversaries can manipulate the models to generate malicious payloads within benign code contexts in response to natural language instructions. For instance, under the backdoor attack setting, by poisoning only 81 samples (0.5\% of the entire instruction dataset), we achieve Attack Success Rate at 1 (ASR@1) scores ranging from 76\% to 86\% for different model families. Our study sheds light on the critical cybersecurity vulnerabilities posed by instruction-tuned Code LLMs and emphasizes the urgent necessity for robust defense mechanisms to mitigate the identified vulnerabilities.

[Arxiv](https://arxiv.org/abs/2404.18567)