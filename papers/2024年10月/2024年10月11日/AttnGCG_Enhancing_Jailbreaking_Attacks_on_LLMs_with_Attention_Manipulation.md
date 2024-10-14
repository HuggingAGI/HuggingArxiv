# AttnGCG：利用注意力操纵强化对 LLM 的越狱攻击

发布时间：2024年10月11日

`LLM应用` `网络安全` `人工智能`

> AttnGCG: Enhancing Jailbreaking Attacks on LLMs with Attention Manipulation

# 摘要

> 本文探讨了基于transformer的LLM在面对越狱攻击时的脆弱性，特别是基于优化的GCG策略。我们发现，攻击效果与模型内部行为密切相关。例如，当模型更关注安全提示时，攻击效果减弱。基于此，我们提出了AttnGCG方法，通过调整注意力分数来增强越狱效果。实证结果显示，AttnGCG在不同LLM中均提升了攻击效果，Llama-2系列提升约7%，Gemma系列提升约10%。此外，该策略对未见目标和黑箱模型（如GPT-3.5和GPT-4）也表现出强大的攻击可转移性。通过注意力分数的可视化，我们能更清晰地理解其工作机制。相关代码已发布在https://github.com/UCSC-VLAA/AttnGCG-attack。

> This paper studies the vulnerabilities of transformer-based Large Language Models (LLMs) to jailbreaking attacks, focusing specifically on the optimization-based Greedy Coordinate Gradient (GCG) strategy. We first observe a positive correlation between the effectiveness of attacks and the internal behaviors of the models. For instance, attacks tend to be less effective when models pay more attention to system prompts designed to ensure LLM safety alignment. Building on this discovery, we introduce an enhanced method that manipulates models' attention scores to facilitate LLM jailbreaking, which we term AttnGCG. Empirically, AttnGCG shows consistent improvements in attack efficacy across diverse LLMs, achieving an average increase of ~7% in the Llama-2 series and ~10% in the Gemma series. Our strategy also demonstrates robust attack transferability against both unseen harmful goals and black-box LLMs like GPT-3.5 and GPT-4. Moreover, we note our attention-score visualization is more interpretable, allowing us to gain better insights into how our targeted attention manipulation facilitates more effective jailbreaking. We release the code at https://github.com/UCSC-VLAA/AttnGCG-attack.

[Arxiv](https://arxiv.org/abs/2410.09040)