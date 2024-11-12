# CapeLLM：使用多模态大型语言模型的无支持类别无关姿态估计

发布时间：2024年11月11日

`LLM应用` `姿态估计` `大型语言模型`

> CapeLLM: Support-Free Category-Agnostic Pose Estimation with Multimodal Large Language Models

# 摘要

> 类别无关姿态估计（CAPE）传统上依赖于带有标注关键点的支持图像，这个过程通常很繁琐，并且可能无法完全捕捉不同对象类别之间的必要对应关系。最近的努力已经开始探索使用基于文本的查询，从而消除了对支持关键点的需求。然而，关键点的文本描述的最佳使用仍然是一个未被充分探索的领域。在这项工作中，我们引入了 CapeLLM，这是一种利用基于文本的多模态大型语言模型（MLLM）进行 CAPE 的新方法。我们的方法仅使用查询图像和详细的文本描述作为输入来估计类别无关的关键点。我们进行了广泛的实验，系统地探索了基于 LLM 的 CAPE 的设计空间，研究了诸如为关键点选择最佳描述、神经网络架构和训练策略等因素。由于预训练的 MLLM 的先进推理能力，CapeLLM 表现出卓越的泛化和稳健性能。我们的方法在具有挑战性的 1-shot 设置中的 MP-100 基准上创下了新的最先进水平，标志着类别无关姿态估计领域的重大进步。

> Category-agnostic pose estimation (CAPE) has traditionally relied on support images with annotated keypoints, a process that is often cumbersome and may fail to fully capture the necessary correspondences across diverse object categories. Recent efforts have begun exploring the use of text-based queries, where the need for support keypoints is eliminated. However, the optimal use of textual descriptions for keypoints remains an underexplored area. In this work, we introduce CapeLLM, a novel approach that leverages a text-based multimodal large language model (MLLM) for CAPE. Our method only employs query image and detailed text descriptions as an input to estimate category-agnostic keypoints. We conduct extensive experiments to systematically explore the design space of LLM-based CAPE, investigating factors such as choosing the optimal description for keypoints, neural network architectures, and training strategies. Thanks to the advanced reasoning capabilities of the pre-trained MLLM, CapeLLM demonstrates superior generalization and robust performance. Our approach sets a new state-of-the-art on the MP-100 benchmark in the challenging 1-shot setting, marking a significant advancement in the field of category-agnostic pose estimation.

[Arxiv](https://arxiv.org/abs/2411.06869)