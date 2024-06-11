# 探究对齐与越狱机制：借助中间隐藏状态揭示LLM安全性的奥秘

发布时间：2024年06月09日

`LLM理论

这篇论文探讨了大型语言模型（LLMs）的安全对齐机制及其如何被越狱行为绕过的问题。通过分析模型的中间隐藏状态，研究揭示了LLMs在预训练阶段已经内化了道德观念，并能够在早期阶段识别恶意与正常输入。这种分析不仅深入理解了LLMs的安全机制，还揭示了越狱行为的规避方式，从而为提高LLMs的安全性提供了理论基础和实践指导。因此，这篇论文属于对LLM理论的深入研究。` `人工智能安全` `道德伦理`

> How Alignment and Jailbreak Work: Explain LLM Safety through Intermediate Hidden States

# 摘要

> 大型语言模型（LLMs）依赖安全对齐机制以抵御恶意输入，但越狱行为却能绕过这些防护，产生有害内容，引发安全顾虑。由于这些模型复杂如黑箱，其安全对齐与越狱的运作机制难以明晰。本文通过弱分类器分析中间隐藏状态，揭示LLMs在预训练中已内化道德观念，而非依赖后期对齐。它们能在初期识别恶意与正常输入，并通过情感猜测与细化拒绝令牌确保生成安全内容。越狱则扰乱了这一道德判断向负面情感的转化过程。我们在7B至70B参数的多个模型上验证了这一发现，为LLM的安全机制提供了深入洞察，并揭示了越狱的规避方式，从而减轻了对LLM安全性的担忧。

> Large language models (LLMs) rely on safety alignment to avoid responding to malicious user inputs. Unfortunately, jailbreak can circumvent safety guardrails, resulting in LLMs generating harmful content and raising concerns about LLM safety. Due to language models with intensive parameters often regarded as black boxes, the mechanisms of alignment and jailbreak are challenging to elucidate. In this paper, we employ weak classifiers to explain LLM safety through the intermediate hidden states. We first confirm that LLMs learn ethical concepts during pre-training rather than alignment and can identify malicious and normal inputs in the early layers. Alignment actually associates the early concepts with emotion guesses in the middle layers and then refines them to the specific reject tokens for safe generations. Jailbreak disturbs the transformation of early unethical classification into negative emotions. We conduct experiments on models from 7B to 70B across various model families to prove our conclusion. Overall, our paper indicates the intrinsical mechanism of LLM safety and how jailbreaks circumvent safety guardrails, offering a new perspective on LLM safety and reducing concerns.

[Arxiv](https://arxiv.org/abs/2406.05644)