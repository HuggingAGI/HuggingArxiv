# 双曲线学习与多模态大型语言模型

发布时间：2024年08月09日

`LLM应用` `计算机视觉`

> Hyperbolic Learning with Multimodal Large Language Models

# 摘要

> 双曲嵌入技术在深度学习任务中，如图像分割和主动学习，有效捕捉不确定性和层次关系。然而，其在现代视觉-语言模型中的应用尚有限。MERU是一个例外，它利用双曲空间的层次特性优化了CLIP ViT-大型模型。我们通过BLIP-2架构，大幅提升了多模态双曲模型的参数数量和训练复杂度。尽管双曲嵌入能揭示欧几里得嵌入无法捕捉的不确定性，但扩展这些模型极具挑战。为此，我们设计了一种新的训练策略，使双曲版BLIP-2在保持训练稳定性的同时，达到与欧几里得版相当的性能，并能有效指示每个嵌入的不确定性。

> Hyperbolic embeddings have demonstrated their effectiveness in capturing measures of uncertainty and hierarchical relationships across various deep-learning tasks, including image segmentation and active learning. However, their application in modern vision-language models (VLMs) has been limited. A notable exception is MERU, which leverages the hierarchical properties of hyperbolic space in the CLIP ViT-large model, consisting of hundreds of millions parameters. In our work, we address the challenges of scaling multi-modal hyperbolic models by orders of magnitude in terms of parameters (billions) and training complexity using the BLIP-2 architecture. Although hyperbolic embeddings offer potential insights into uncertainty not present in Euclidean embeddings, our analysis reveals that scaling these models is particularly difficult. We propose a novel training strategy for a hyperbolic version of BLIP-2, which allows to achieve comparable performance to its Euclidean counterpart, while maintaining stability throughout the training process and showing a meaningful indication of uncertainty with each embedding.

[Arxiv](https://arxiv.org/abs/2408.05097)