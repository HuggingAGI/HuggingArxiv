# NeuReg：关于人类和小鼠大脑的域不变 3D 图像配准

发布时间：2024年11月09日

`其他` `图像配准`

> NeuReg: Domain-invariant 3D Image Registration on Human and Mouse Brains

# 摘要

> 医学脑成像在很大程度上依赖于图像配准，以便为各种医疗保健应用准确地整理大脑特征的结构边界。近年来，深度学习模型在图像配准方面表现出了显著的性能。然而，它们常常难以处理 3D 脑体积的多样性，受到其结构和对比度变化以及成像域的挑战。在这项工作中，我们提出了 NeuReg，这是一种具有域不变性特征的神经启发式 3D 图像配准架构。NeuReg 生成成像特征的域无关表示，并将基于移位窗口的 Swin Transformer 块作为编码器。这使我们的模型能够捕捉跨脑成像模式和物种的变化。我们在包括人类和小鼠 3D 脑体积的多域公开可用数据集中展示了一个新的基准。大量实验表明，我们的模型（NeuReg）优于现有的基于深度学习的图像配准基线模型，并在跨域数据集上提供了高性能提升，其中模型在“仅源”域上进行训练，并在完全“未见过”的目标域上进行测试。我们的工作建立了基于神经启发的基于 Transformer 架构的域无关 3D 脑图像配准的新的最先进水平。

> Medical brain imaging relies heavily on image registration to accurately curate structural boundaries of brain features for various healthcare applications. Deep learning models have shown remarkable performance in image registration in recent years. Still, they often struggle to handle the diversity of 3D brain volumes, challenged by their structural and contrastive variations and their imaging domains. In this work, we present NeuReg, a Neuro-inspired 3D image registration architecture with the feature of domain invariance. NeuReg generates domain-agnostic representations of imaging features and incorporates a shifting window-based Swin Transformer block as the encoder. This enables our model to capture the variations across brain imaging modalities and species. We demonstrate a new benchmark in multi-domain publicly available datasets comprising human and mouse 3D brain volumes. Extensive experiments reveal that our model (NeuReg) outperforms the existing baseline deep learning-based image registration models and provides a high-performance boost on cross-domain datasets, where models are trained on 'source-only' domain and tested on completely 'unseen' target domains. Our work establishes a new state-of-the-art for domain-agnostic 3D brain image registration, underpinned by Neuro-inspired Transformer-based architecture.

[Arxiv](https://arxiv.org/abs/2411.06315)