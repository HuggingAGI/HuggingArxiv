# 应对多模态大型语言模型训练中的模型与数据异质性挑战

发布时间：2024年08月08日

`LLM应用` `人工智能` `计算机系统`

> Addressing Model and Data Heterogeneity in Multimodal Large Language Model Training

# 摘要

> 多模态大型语言模型在众多 AI 应用中展现出巨大潜力，但其训练因模态间的模型与数据异质性而效率低下且难以扩展。为此，我们推出了 MMScale 框架，该框架高效自适应，旨在优化大规模集群上的多模态 LLM 训练。MMScale 通过利用多模态训练的系统特性，实现了高效与可扩展性，其核心技术包括自适应资源分配与数据感知重排序，分别解决模型与数据的异质性问题。此外，我们还针对多模态 LLM 训练进行了系统优化，以减轻 GPU 负担。实验表明，MMScale 在大型集群上训练 72B 多模态 LLM 时，模型 FLOPs 利用率达到 54.7%，吞吐量比 Megatron-LM 提升高达 2.2 倍，且其关键技术既高效又轻量。

> Multimodal large language models (LLMs) have demonstrated significant potential in a wide range of AI applications. Yet, training multimodal LLMs suffers from low efficiency and scalability, due to the inherent model heterogeneity and data heterogeneity across different modalities.
  We present MMScale, an efficient and adaptive framework to reform the training of multimodal large language models on large-scale clusters. MMScale exploits the system characteristics of multimodal LLM training to achieve high efficiency and scalability. The core of MMScale is the adaptive resource allocation and data-aware reordering techniques to eliminate the model and data heterogeneity respectively. We also tailor system optimizations for multimodal LLM training to offload certain operations from the GPU training. We evaluate MMScale across different sizes of multimodal LLMs on a large-scale production cluster with thousands of GPUs. The experimental results show that MMScale achieves 54.7% Model FLOPs Utilization (MFU) when training a 72B multimodal LLM on 1172 GPUs and outperforms Megatron-LM by up to 2.2$\times$ on throughput. The ablation study shows the main techniques of MMScale are both effective and lightweight.

[Arxiv](https://arxiv.org/abs/2408.04275)