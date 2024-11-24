# 用于医学视觉问答的高效双线性注意力融合

发布时间：2024年10月28日

`LLM应用` `计算机视觉`

> Efficient Bilinear Attention-based Fusion for Medical Visual Question Answering

# 摘要

> 医疗视觉问答（MedVQA）在计算机视觉与自然语言处理的交叉领域愈发受到关注。它能解读放射图像，并为临床咨询给出精准答案，使 MedVQA 成为辅助医生诊断决策、减轻放射科医生工作负担的得力工具。尽管当下的方法多着眼于运用统一的预训练大型模型进行多模态融合，例如跨模态 Transformer，但在这个领域，有关更高效融合方法的研究仍相对稀缺。本文引入了一种全新的融合模型，即集成了正交损失、多头注意力和双线性注意力网络（OMniBAN），无需预训练就能达成高计算效率和强劲性能。我们开展了全面实验，阐明了如何强化双线性注意力融合以获得与大型模型媲美的性能。实验结果显示，OMniBAN 在关键的 MedVQA 基准测试中胜过传统模型，同时计算成本更低，这表明其在放射学和病理学图像问答方面具有高效临床应用的潜力。

> Medical Visual Question Answering (MedVQA) has gained increasing attention at the intersection of computer vision and natural language processing. Its capability to interpret radiological images and deliver precise answers to clinical inquiries positions MedVQA as a valuable tool for supporting diagnostic decision-making for physicians and alleviating the workload on radiologists. While recent approaches focus on using unified pre-trained large models for multi-modal fusion like cross-modal Transformers, research on more efficient fusion methods remains relatively scarce within this discipline. In this paper, we introduce a novel fusion model that integrates Orthogonality loss, Multi-head attention and Bilinear Attention Network (OMniBAN) to achieve high computational efficiency and strong performance without the need for pre-training. We conduct comprehensive experiments and clarify aspects of how to enhance bilinear attention fusion to achieve performance comparable to that of large models. Experimental results show that OMniBAN outperforms traditional models on key MedVQA benchmarks while maintaining a lower computational cost, which indicates its potential for efficient clinical application in radiology and pathology image question answering.

[Arxiv](https://arxiv.org/abs/2410.21000)