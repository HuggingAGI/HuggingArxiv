# 视觉指令调教下的学习，大型语言模型虽能“看”得更清，却更易在“跟随”指令上失守，从而更易遭受越狱攻击。

发布时间：2024年05月07日

`LLM应用

这篇论文关注的是视觉-语言模型（VLMs）的安全性问题，特别是越狱攻击对这些模型的影响。它分析了不同建模策略下的VLMs在面对越狱攻击时的脆弱性，并提出了加强安全考量的建议。虽然涉及到了大型语言模型（LLMs），但研究的重点是VLMs的应用层面，特别是它们在实际应用中的安全问题，因此归类为LLM应用。` `人工智能安全` `视觉-语言模型`

> Learning To See But Forgetting To Follow: Visual Instruction Tuning Makes LLMs More Prone To Jailbreak Attacks

# 摘要

> 将图像理解能力融入大型语言模型，催生了高性能的视觉-语言模型。尽管LLMs与人类价值观的对齐研究备受瞩目，但VLMs的安全性却鲜有人问津。本文深入分析了越狱对三种尖端VLMs的影响，它们各自采用独特的建模策略。对比各自的LLM基础模型，我们发现VLMs更易被越狱攻破。这揭示了视觉指令调整可能导致LLM的安全防护措施失效。鉴于此，我们建议未来的研究应通过评估策略来揭示VLMs的脆弱性，并在视觉指令调整时加强安全考量。

> Augmenting Large Language Models (LLMs) with image-understanding capabilities has resulted in a boom of high-performing Vision-Language models (VLMs). While studying the alignment of LLMs to human values has received widespread attention, the safety of VLMs has not received the same attention. In this paper, we explore the impact of jailbreaking on three state-of-the-art VLMs, each using a distinct modeling approach. By comparing each VLM to their respective LLM backbone, we find that each VLM is more susceptible to jailbreaking. We consider this as an undesirable outcome from visual instruction-tuning, which imposes a forgetting effect on an LLM's safety guardrails. Therefore, we provide recommendations for future work based on evaluation strategies that aim to highlight the weaknesses of a VLM, as well as take safety measures into account during visual instruction tuning.

[Arxiv](https://arxiv.org/abs/2405.04403)