# SeLoRA：医学图像合成中，潜在扩散模型的自扩展低秩适应技术

发布时间：2024年08月13日

`LLM应用` `图像处理`

> SeLoRA: Self-Expanding Low-Rank Adaptation of Latent Diffusion Model for Medical Image Synthesis

# 摘要

> 医学图像合成领域，由于标注数据稀缺和多模态分析中“缺失模态”的合成需求，迫切需要开发高效合成方法。近期，结合低秩适应（LoRA）与潜在扩散模型（LDMs）的方法在医学领域崭露头角，成为适应预训练大型语言模型的有效途径。然而，传统LoRA方法忽视了不同权重矩阵的重要性，导致效果不佳。为此，我们创新提出SeLoRA，一种自扩展低秩适应模块，能在训练中动态调整各层排名，重点提升关键层的合成质量。这一方法不仅使LDMs在医学数据上高效微调，还能以最小成本提升图像质量。SeLoRA方法代码已公开，供业界参考。

> The persistent challenge of medical image synthesis posed by the scarcity of annotated data and the need to synthesize `missing modalities' for multi-modal analysis, underscored the imperative development of effective synthesis methods. Recently, the combination of Low-Rank Adaptation (LoRA) with latent diffusion models (LDMs) has emerged as a viable approach for efficiently adapting pre-trained large language models, in the medical field. However, the direct application of LoRA assumes uniform ranking across all linear layers, overlooking the significance of different weight matrices, and leading to sub-optimal outcomes. Prior works on LoRA prioritize the reduction of trainable parameters, and there exists an opportunity to further tailor this adaptation process to the intricate demands of medical image synthesis. In response, we present SeLoRA, a Self-Expanding Low-Rank Adaptation Module, that dynamically expands its ranking across layers during training, strategically placing additional ranks on crucial layers, to allow the model to elevate synthesis quality where it matters most. The proposed method not only enables LDMs to fine-tune on medical data efficiently but also empowers the model to achieve improved image quality with minimal ranking. The code of our SeLoRA method is publicly available on https://anonymous.4open.science/r/SeLoRA-980D .

[Arxiv](https://arxiv.org/abs/2408.07196)