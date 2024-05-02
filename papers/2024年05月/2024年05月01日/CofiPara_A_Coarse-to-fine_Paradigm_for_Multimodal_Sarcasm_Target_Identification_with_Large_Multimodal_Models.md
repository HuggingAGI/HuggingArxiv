# CofiPara：一种从粗略到精细的多模态讽刺目标识别方法，适用于大型多模态模型。

发布时间：2024年05月01日

`分类：LLM应用

这篇论文提出了一种新颖的识别框架，用于识别社交媒体上的多模态讽刺目标。它利用大型多模态模型生成初步的解释，然后对小型语言模型进行微调，以实现更精细的讽刺目标识别。这篇论文的研究重点是提高讽刺目标识别的准确性和可解释性，因此它属于LLM应用类别。` `社交媒体分析` `人工智能`

> CofiPara: A Coarse-to-fine Paradigm for Multimodal Sarcasm Target Identification with Large Multimodal Models

# 摘要

> 社交媒体上的多模态讽刺层出不穷，识别其目标颇具挑战，因为文本和图像中隐含的不一致性并不明显。现行的多模态讽刺目标识别技术大多只关注表面现象，忽略了对讽刺深层次理解的必要性。本文提出了一种新颖的识别框架，它采用由粗到细的方法，通过增强推理能力和预训练知识来提升讽刺的可解释性。借鉴大型多模态模型在多模态推理上的卓越表现，我们首先利用这些模型为多模态讽刺检测生成初步的竞争性解释，然后对小型语言模型进行微调，以实现更精细的讽刺目标识别。我们的框架能够有效地揭示多模态讽刺中的微妙目标，并减少大型模型中固有噪声的负面影响。实验结果显示，我们的模型在识别多模态讽刺目标方面大大超越了现有的顶尖方法，并且在解释讽刺方面表现出了显著的可解释性。

> Social media abounds with multimodal sarcasm, and identifying sarcasm targets is particularly challenging due to the implicit incongruity not directly evident in the text and image modalities. Current methods for Multimodal Sarcasm Target Identification (MSTI) predominantly focus on superficial indicators in an end-to-end manner, overlooking the nuanced understanding of multimodal sarcasm conveyed through both the text and image. This paper proposes a versatile MSTI framework with a coarse-to-fine paradigm, by augmenting sarcasm explainability with reasoning and pre-training knowledge. Inspired by the powerful capacity of Large Multimodal Models (LMMs) on multimodal reasoning, we first engage LMMs to generate competing rationales for coarser-grained pre-training of a small language model on multimodal sarcasm detection. We then propose fine-tuning the model for finer-grained sarcasm target identification. Our framework is thus empowered to adeptly unveil the intricate targets within multimodal sarcasm and mitigate the negative impact posed by potential noise inherently in LMMs. Experimental results demonstrate that our model far outperforms state-of-the-art MSTI methods, and markedly exhibits explainability in deciphering sarcasm as well.

[Arxiv](https://arxiv.org/abs/2405.00390)