# 利用句子结尾的多层感知器重新加权技术，破解指令调整的大型语言模型。

发布时间：2024年10月14日

`LLM理论` `网络安全` `人工智能`

> Jailbreak Instruction-Tuned LLMs via end-of-sentence MLP Re-weighting

# 摘要

> 本文探讨了指令微调大型语言模型（LLM）的安全机制。研究发现，重新调整多层感知器（MLP）神经元的权重会严重威胁模型安全，尤其是在句子结尾的推理过程中。我们推测，LLM在句子结尾推理时评估提示的危害性，而MLP层在此过程中至关重要。基于此，我们提出了两种新型白盒破解方法：针对特定提示的实时优化攻击和预训练的通用提示攻击。这些方法在从2B到72B的7个开源LLM上表现出色。研究不仅揭示了指令微调LLM的安全漏洞，还深化了对LLM内部机制的理解。

> In this paper, we investigate the safety mechanisms of instruction fine-tuned large language models (LLMs). We discover that re-weighting MLP neurons can significantly compromise a model's safety, especially for MLPs in end-of-sentence inferences. We hypothesize that LLMs evaluate the harmfulness of prompts during end-of-sentence inferences, and MLP layers plays a critical role in this process. Based on this hypothesis, we develop 2 novel white-box jailbreak methods: a prompt-specific method and a prompt-general method. The prompt-specific method targets individual prompts and optimizes the attack on the fly, while the prompt-general method is pre-trained offline and can generalize to unseen harmful prompts. Our methods demonstrate robust performance across 7 popular open-source LLMs, size ranging from 2B to 72B. Furthermore, our study provides insights into vulnerabilities of instruction-tuned LLM's safety and deepens the understanding of the internal mechanisms of LLMs.

[Arxiv](https://arxiv.org/abs/2410.10150)