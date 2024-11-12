# 锚点注意力，小缓存：使用大型语言模型进行代码生成

发布时间：2024年11月10日

`LLM应用` `代码生成`

> Anchor Attention, Small Cache: Code Generation with Large Language Models

# 摘要

> 大型语言模型（LLMs）的发展彻底改变了自动化代码生成。然而，它们对计算资源的高需求阻碍了更广泛的部署，并引发了环境问题。减少计算需求的一个常见策略是缓存主流 LLMs 主要采用的注意力机制中的键值（KV）状态。它可以减轻重复注意力计算的需求，但带来了显著的内存开销。当前自然语言处理中的实践经常使用稀疏注意力，不幸的是，这可能会在代码生成任务中导致大量的不准确或幻觉。在本文中，我们通过一项实证研究分析了代码生成模型中的注意力权重分布，揭示了一种稀疏模式，即特定锚点处的信息聚合。基于这一观察，我们提出了一种新的方法，即 AnchorCoder，其特点是具有旨在提取和压缩上下文信息的逐标记锚注意力，以及能够实现跨层通信以减轻压缩导致的过度叠加问题的逐层锚注意力。在多个基准数据集上进行的大量实验证实了 AnchorCoder 的有效性，它可以始终实现 KV 缓存需求的显著（至少 70％）减少，同时保留模型的大部分性能。

> The development of large language models (LLMs) has revolutionized automated code generation. However, their high demand of computation resources has hindered a broader deployment and raised environmental concerns. A common strategy for diminishing computational demands is to cache Key-Value (KV) states from the attention mechanism which is adopted predominately by mainstream LLMs. It can mitigate the need of repeated attention computations, but brings significant memory overhead. Current practices in NLP often use sparse attention which may, unfortunately, lead to substantial inaccuracies, or hallucinations, in code generation tasks. In this paper, we analyze the attention weights distribution within code generation models via an empirical study, uncovering a sparsity pattern, i.e., the aggregation of information at specific anchor points. Based on this observation, we propose a novel approach, AnchorCoder, which features token-wise anchor attention designed to extract and compress the contextual information, and layer-wise anchor attention enabling cross-layer communication to mitigate the issue of excessive superposition caused by the compression. The extensive experiments across multiple benchmark datasets confirm the effectiveness of AnchorCoder, which can consistently achieve a significant (at least 70%) reduction in KV cache requirements, while preserving the majority of model's performance.

[Arxiv](https://arxiv.org/abs/2411.06680)