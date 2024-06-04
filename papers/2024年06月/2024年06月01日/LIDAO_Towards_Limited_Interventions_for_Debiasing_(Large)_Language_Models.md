# LIDAO：探索有限干预策略，以减少大型语言模型的偏见

发布时间：2024年06月01日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）在生成内容时可能出现的偏见问题，并从信息论的角度提出了一个新的框架（LIDAO）来平衡公平性和流畅性。此外，论文还关注了模型在对抗环境下的表现，确保模型能够遵循指令，避免公平性问题。这些内容主要涉及LLM的理论研究和方法改进，因此归类为LLM理论。` `公平性`

> LIDAO: Towards Limited Interventions for Debiasing (Large) Language Models

# 摘要

> 大型语言模型（LLMs）在自然语言生成任务上表现出色，但它们生成的内容有时带有对特定群体（如女性）的偏见，引发了公平性担忧。以往的解决方案通过移除相关信息来干预生成，虽提升了公平性，却牺牲了流畅性。本研究首次从信息论视角探讨了为实现公平性，流畅性应受多大影响。我们发现之前的去偏方法过于极端，并提出了LIDAO框架，旨在更平衡地提升公平性与流畅性。此外，我们还强化了LIDAO在对抗环境下的表现，确保在精心设计的提示下，模型能遵循指令，避免公平性问题。实验结果显示，我们的方法在不同规模的模型上均表现优异。

> Large language models (LLMs) have achieved impressive performance on various natural language generation tasks. Nonetheless, they suffer from generating negative and harmful contents that are biased against certain demographic groups (e.g., female), raising severe fairness concerns. As remedies, prior works intervened the generation by removing attitude or demographic information, inevitably degrading the generation quality and resulting in notable \textit{fairness-fluency} trade-offs. However, it is still under-explored to what extent the fluency \textit{has to} be affected in order to achieve a desired level of fairness. In this work, we conduct the first formal study from an information-theoretic perspective. We show that previous approaches are excessive for debiasing and propose LIDAO, a general framework to debias a (L)LM at a better fluency provably. We further robustify LIDAO in adversarial scenarios, where a carefully-crafted prompt may stimulate LLMs exhibiting instruction-following abilities to generate texts with fairness issue appears only when the prompt is also taken into account. Experiments on three LMs ranging from 0.7B to 7B parameters demonstrate the superiority of our method.

[Arxiv](https://arxiv.org/abs/2406.00548)