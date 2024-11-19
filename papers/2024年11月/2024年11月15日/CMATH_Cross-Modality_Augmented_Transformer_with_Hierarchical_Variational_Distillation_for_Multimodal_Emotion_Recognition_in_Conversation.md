# CMATH：用于对话中多模态情感识别的具备分层变分蒸馏的跨模态增强 Transformer

发布时间：2024年11月15日

`其他` `情感识别` `对话系统`

> CMATH: Cross-Modality Augmented Transformer with Hierarchical Variational Distillation for Multimodal Emotion Recognition in Conversation

# 摘要

> 对话中的多模态情感识别（MER）旨在借助多模态信息的整合，精准识别对话中的情感。以往的方法往往将多模态信息视作同等质量，并运用对称架构来进行多模态融合。然而，实际上，不同模态的质量通常差别显著，在处理不均衡的模态信息时，采用对称架构难以准确识别对话中的情感。另外，于单一粒度融合多模态信息可能无法充分整合模态信息，从而加剧情感识别的不准确性。在本文中，我们提出了一种新颖的带有分层变分蒸馏的跨模态增强变压器，名为CMATH，它包含两个主要部分，即多模态交互融合和分层变分蒸馏。前者由两个子模块构成，分别是模态重建和跨模态增强变压器（CMA-Transformer），其中模态重建致力于获取每种模态的高质量压缩表示，CMA-Transformer采用非对称融合策略，将一种模态当作中心模态，把其他模态视为辅助模态。后者首先设计一个变分融合网络，把CMA-Transformer学习到的细粒度表示融合为粗粒度表示。接着，它引入一个分层蒸馏框架，以维持不同粒度模态表示之间的一致性。在IEMOCAP和MELD数据集上的实验表明，我们所提出的模型优于先前的最先进基线。实现代码可在https://github.com/ cjw-MER/CMATH获取。

> Multimodal emotion recognition in conversation (MER) aims to accurately identify emotions in conversational utterances by integrating multimodal information. Previous methods usually treat multimodal information as equal quality and employ symmetric architectures to conduct multimodal fusion. However, in reality, the quality of different modalities usually varies considerably, and utilizing a symmetric architecture is difficult to accurately recognize conversational emotions when dealing with uneven modal information. Furthermore, fusing multi-modality information in a single granularity may fail to adequately integrate modal information, exacerbating the inaccuracy in emotion recognition. In this paper, we propose a novel Cross-Modality Augmented Transformer with Hierarchical Variational Distillation, called CMATH, which consists of two major components, i.e., Multimodal Interaction Fusion and Hierarchical Variational Distillation. The former is comprised of two submodules, including Modality Reconstruction and Cross-Modality Augmented Transformer (CMA-Transformer), where Modality Reconstruction focuses on obtaining high-quality compressed representation of each modality, and CMA-Transformer adopts an asymmetric fusion strategy which treats one modality as the central modality and takes others as auxiliary modalities. The latter first designs a variational fusion network to fuse the fine-grained representations learned by CMA- Transformer into a coarse-grained representations. Then, it introduces a hierarchical distillation framework to maintain the consistency between modality representations with different granularities. Experiments on the IEMOCAP and MELD datasets demonstrate that our proposed model outperforms previous state-of-the-art baselines. Implementation codes can be available at https://github.com/ cjw-MER/CMATH.

[Arxiv](https://arxiv.org/abs/2411.10060)