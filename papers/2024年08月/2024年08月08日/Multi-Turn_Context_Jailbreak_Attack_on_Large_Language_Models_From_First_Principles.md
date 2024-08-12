# 从基本原理出发，对大型语言模型进行多轮上下文越狱攻击

发布时间：2024年08月08日

`LLM应用` `网络安全` `人工智能`

> Multi-Turn Context Jailbreak Attack on Large Language Models From First Principles

# 摘要

> 大型语言模型（LLM）在智能对话和文本生成等众多应用中展现出卓越性能，但其固有的安全漏洞，尤其是在越狱攻击方面，已成为严峻挑战。攻击者能绕过安全机制，引发有害输出。针对多轮语义越狱攻击，我们发现现有方法未充分考虑多轮对话在攻击中的作用，导致交互中的语义偏差。为此，本文为多轮攻击奠定理论基础，并提出一种名为上下文融合攻击（CFA）的新型黑盒攻击方法。CFA 通过筛选目标关键词、构建上下文场景、动态融合目标并替换恶意关键词，巧妙隐藏恶意意图。实验表明，CFA 在成功率、分歧和危害性方面均优于其他多轮攻击策略，尤其在 Llama3 和 GPT-4 上表现突出。

> Large language models (LLMs) have significantly enhanced the performance of numerous applications, from intelligent conversations to text generation. However, their inherent security vulnerabilities have become an increasingly significant challenge, especially with respect to jailbreak attacks. Attackers can circumvent the security mechanisms of these LLMs, breaching security constraints and causing harmful outputs. Focusing on multi-turn semantic jailbreak attacks, we observe that existing methods lack specific considerations for the role of multiturn dialogues in attack strategies, leading to semantic deviations during continuous interactions. Therefore, in this paper, we establish a theoretical foundation for multi-turn attacks by considering their support in jailbreak attacks, and based on this, propose a context-based contextual fusion black-box jailbreak attack method, named Context Fusion Attack (CFA). This method approach involves filtering and extracting key terms from the target, constructing contextual scenarios around these terms, dynamically integrating the target into the scenarios, replacing malicious key terms within the target, and thereby concealing the direct malicious intent. Through comparisons on various mainstream LLMs and red team datasets, we have demonstrated CFA's superior success rate, divergence, and harmfulness compared to other multi-turn attack strategies, particularly showcasing significant advantages on Llama3 and GPT-4.

[Arxiv](https://arxiv.org/abs/2408.04686)