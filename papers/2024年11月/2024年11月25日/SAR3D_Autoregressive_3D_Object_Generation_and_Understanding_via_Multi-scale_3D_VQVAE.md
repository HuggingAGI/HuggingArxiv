# SAR3D：借助多尺度 3D VQVAE 实现自回归 3D 对象的生成与理解

发布时间：2024年11月25日

`LLM应用` `3D 生成` `多模态`

> SAR3D: Autoregressive 3D Object Generation and Understanding via Multi-scale 3D VQVAE

# 摘要

> 自回归模型在诸如大型语言模型（LLMs）、大型多模态模型（LMMs）以及 2D 内容生成等众多领域大获成功，不断向通用人工智能（AGI）靠近。尽管如此，将自回归方法用于 3D 对象生成与理解方面，很大程度上仍未被探索。本文引入了 Scale AutoRegressive 3D（SAR3D）这一全新框架，它借助多尺度 3D 向量量化变分自编码器（VQVAE）对 3D 对象进行标记，从而实现高效的自回归生成及细致理解。SAR3D 通过预测多尺度潜在表示中的下一个尺度而非下一个单个标记，大幅缩短了生成时间，在 A6000 GPU 上仅 0.82 秒就能完成快速 3D 对象生成。另外，鉴于拥有富含分层 3D 感知信息的标记，我们对预训练的 LLM 进行微调，使得能够对 3D 内容进行多模态理解。我们的实验显示，SAR3D 在速度和质量上均超越了当前的 3D 生成方法，并能让 LLM 全面解读和标注 3D 模型。

> Autoregressive models have demonstrated remarkable success across various fields, from large language models (LLMs) to large multimodal models (LMMs) and 2D content generation, moving closer to artificial general intelligence (AGI). Despite these advances, applying autoregressive approaches to 3D object generation and understanding remains largely unexplored. This paper introduces Scale AutoRegressive 3D (SAR3D), a novel framework that leverages a multi-scale 3D vector-quantized variational autoencoder (VQVAE) to tokenize 3D objects for efficient autoregressive generation and detailed understanding. By predicting the next scale in a multi-scale latent representation instead of the next single token, SAR3D reduces generation time significantly, achieving fast 3D object generation in just 0.82 seconds on an A6000 GPU. Additionally, given the tokens enriched with hierarchical 3D-aware information, we finetune a pretrained LLM on them, enabling multimodal comprehension of 3D content. Our experiments show that SAR3D surpasses current 3D generation methods in both speed and quality and allows LLMs to interpret and caption 3D models comprehensively.

[Arxiv](https://arxiv.org/abs/2411.16856)