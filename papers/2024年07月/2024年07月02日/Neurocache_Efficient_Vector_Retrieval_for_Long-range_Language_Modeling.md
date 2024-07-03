# Neurocache：实现长距离语言建模的高效向量检索技术

发布时间：2024年07月02日

`LLM应用` `人工智能` `软件开发`

> Neurocache: Efficient Vector Retrieval for Long-range Language Modeling

# 摘要

> 本文提出 Neurocache，一种利用外部向量缓存存储模型历史状态，从而扩展 LLM 上下文大小的创新方法。Neurocache 采用高效的 kNN 算法，快速检索并整合相关历史状态至注意力机制中，从而实现以下优化：(1) 压缩状态存储，减小缓存空间；(2) 单次检索操作每令牌，加速推理过程；(3) 扩展检索范围至邻近状态，提升语言模型及下游任务准确性。实验证明，无论是全新训练还是预训练模型（如 Llama2-7B 和 Mistral-7B），Neurocache 均能显著提升性能。此外，与传统文本检索相比，Neurocache 在单文档问答和少样本学习任务中表现更优。源代码已公开于：https://github.com/alisafaya/neurocache

> This paper introduces Neurocache, an approach to extend the effective context size of large language models (LLMs) using an external vector cache to store its past states. Like recent vector retrieval approaches, Neurocache uses an efficient k-nearest-neighbor (kNN) algorithm to retrieve relevant past states and incorporate them into the attention process. Neurocache improves upon previous methods by (1) storing compressed states, which reduces cache size; (2) performing a single retrieval operation per token which increases inference speed; and (3) extending the retrieval window to neighboring states, which improves both language modeling and downstream task accuracy. Our experiments show the effectiveness of Neurocache both for models trained from scratch and for pre-trained models such as Llama2-7B and Mistral-7B when enhanced with the cache mechanism. We also compare Neurocache with text retrieval methods and show improvements in single-document question-answering and few-shot learning tasks. We made the source code available under: https://github.com/alisafaya/neurocache

[Arxiv](https://arxiv.org/abs/2407.02486)