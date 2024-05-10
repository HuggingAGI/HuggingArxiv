# NetsDB 采用 Transformer 架构，该架构在自然语言处理领域展现了卓越的性能，为数据处理和分析提供了强大的支持。

发布时间：2024年05月09日

`LLM应用

这篇论文讨论了基于Transformer模型的编码器实现，并专注于优化模型权重加载以支持分布式处理、部署和高效推理。它还进行了与其他深度学习平台的性能对比，展示了其优越的推理速度和模型尺寸优化。这些内容与大型语言模型（LLM）的应用相关，特别是在模型部署和服务方面，因此将其归类为LLM应用。` `数据库技术`

> Transformer Architecture for NetsDB

# 摘要

> Transformer模型已成为语言、视觉和多模态领域的顶尖技术，其核心在于利用多头自注意力机制，动态捕捉上下文信息，并建模长距离依赖，以实现精准的上下文理解。Lixi等学者提出了一种基于关系数据库的大规模深度学习模型部署方法，并开发了开源工具NetsDB。我们在此基础上，实现了Transformer编码器的端到端服务，构建了一个集多头注意力、自注意力机制、层归一化、丢弃、前馈层和残差连接于一体的两块编码器。我们优化了模型权重加载，以支持分布式处理、部署和高效推理。通过与PyTorch、Tensorflow、Flax和MxNet等平台的全面性能对比，我们的实现展现了卓越的推理速度和模型尺寸优化。

> Transformers models have become the backbone of the current state-of-the-art models in language, vision, and multimodal domains. These models, at their core, utilize multi-head self-attention to selectively aggregate context, generating dynamic contextual embeddings and modeling long-range dependencies for a clear contextual understanding. Lixi et al. \cite{zhou2022serving} proposed a method to use relational databases for deploying large-scale deep learning models and created an open-source implementation called NetsDB for the same. We build upon the previous work of these authors by creating an end-to-end implementation of the Encoder part of the transformer for model serving in NetsDB. Specifically, we construct a two-block encoder that includes Multi-Head Attention and its accompanying self-attention mechanism, Layer-Norm, Dropout, FeedForward Layers, and the necessary residual connections. We load out weights from our model for distributed processing, deployment, and efficient inferencing. To prove the efficacy of our implementation, we conduct a comprehensive performance analysis by comparing it with existing implementations in PyTorch, Tensorflow, Flax, and MxNet across key metrics such as inference time and model size.

[Arxiv](https://arxiv.org/abs/2405.04807)