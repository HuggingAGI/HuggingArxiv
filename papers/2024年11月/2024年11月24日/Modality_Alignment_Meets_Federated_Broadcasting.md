# 模态对齐与联邦广播的相遇

发布时间：2024年11月24日

`其他` `联邦学习` `多模态学习`

> Modality Alignment Meets Federated Broadcasting

# 摘要

> 联邦学习（FL）已成为保护数据隐私的有力手段，它能在分布式边缘设备上训练模型，无需集中本地数据。尽管在同质数据场景中有进步，但在异构数据下，要保持联邦学习中全局和本地客户端的性能仍具挑战，因为数据分布的变化会降低模型收敛性，增加计算成本。本文引入了一个借助模态对齐的新型联邦学习框架，文本编码器在服务器端，图像编码器在本地设备运行。受像 CLIP 这样的多模态学习范式启发，此设计将服务器 - 客户端通信视作多模态广播，从而实现跨客户端学习的对齐。我们以预训练模型初始化来减轻过拟合，通过低秩自适应（LoRA）更新选定参数，满足计算需求和性能效率。本地模型独立训练并向服务器传递更新，服务器通过基于查询的方法聚合参数，促进跨客户端知识共享，提升极端异构环境下的性能。在基准数据集上的大量实验表明，即便在高度异构的情况下，其在保持泛化和鲁棒性方面也卓有成效。

> Federated learning (FL) has emerged as a powerful approach to safeguard data privacy by training models across distributed edge devices without centralizing local data. Despite advancements in homogeneous data scenarios, maintaining performance between the global and local clients in FL over heterogeneous data remains challenging due to data distribution variations that degrade model convergence and increase computational costs. This paper introduces a novel FL framework leveraging modality alignment, where a text encoder resides on the server, and image encoders operate on local devices. Inspired by multi-modal learning paradigms like CLIP, this design aligns cross-client learning by treating server-client communications akin to multi-modal broadcasting. We initialize with a pre-trained model to mitigate overfitting, updating select parameters through low-rank adaptation (LoRA) to meet computational demand and performance efficiency. Local models train independently and communicate updates to the server, which aggregates parameters via a query-based method, facilitating cross-client knowledge sharing and performance improvement under extreme heterogeneity. Extensive experiments on benchmark datasets demonstrate the efficacy in maintaining generalization and robustness, even in highly heterogeneous settings.

[Arxiv](https://arxiv.org/abs/2411.15837)