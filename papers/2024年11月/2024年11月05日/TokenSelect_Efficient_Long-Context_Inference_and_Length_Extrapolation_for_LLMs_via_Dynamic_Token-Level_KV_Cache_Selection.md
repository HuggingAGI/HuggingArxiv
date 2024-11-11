# TokenSelect：通过动态令牌级 KV 缓存选择实现大型语言模型的高效长上下文推理和长度外推

发布时间：2024年11月05日

`LLM应用` `搜索系统`

> TokenSelect: Efficient Long-Context Inference and Length Extrapolation for LLMs via Dynamic Token-Level KV Cache Selection

# 摘要

> 随着大型语言模型（LLMs）的发展，处理更长上下文的能力已成为网络应用（如跨文档理解和由 LLM 驱动的搜索系统）的关键能力。然而，这一进展面临两个主要挑战：由于序列长度超出分布导致的性能下降，以及注意力的二次计算复杂性导致的过长推理时间。这些问题阻碍了 LLMs 在长上下文场景中的应用。在本文中，我们提出了动态令牌级 KV 缓存选择（TokenSelect），这是一种与模型无关、无需训练的高效准确的长上下文推理方法。TokenSelect 基于对非连续注意力稀疏性的观察，使用查询-键点积在令牌级别测量每个头的 KV 缓存关键性。通过每个头的软投票机制，TokenSelect 在不牺牲准确性的情况下，有选择地在注意力计算中涉及少量关键的 KV 缓存令牌。为了进一步加速 TokenSelect，我们根据连续查询相似性的观察设计了选择缓存，并实现了高效的点积内核，显著降低了令牌选择的开销。对 TokenSelect 的全面评估表明，在注意力计算中速度提高了高达 23.84 倍，端到端延迟加速了高达 2.28 倍，同时与最先进的长上下文推理方法相比提供了优越的性能。

> With the development of large language models (LLMs), the ability to handle longer contexts has become a key capability for Web applications such as cross-document understanding and LLM-powered search systems. However, this progress faces two major challenges: performance degradation due to sequence lengths out-of-distribution, and excessively long inference times caused by the quadratic computational complexity of attention. These issues hinder the application of LLMs in long-context scenarios. In this paper, we propose Dynamic Token-Level KV Cache Selection (TokenSelect), a model-agnostic, training-free method for efficient and accurate long-context inference. TokenSelect builds upon the observation of non-contiguous attention sparsity, using Query-Key dot products to measure per-head KV Cache criticality at token-level. By per-head soft voting mechanism, TokenSelect selectively involves a small number of critical KV cache tokens in the attention calculation without sacrificing accuracy. To further accelerate TokenSelect, we designed the Selection Cache based on observations of consecutive Query similarity and implemented efficient dot product kernel, significantly reducing the overhead of token selection. A comprehensive evaluation of TokenSelect demonstrates up to 23.84x speedup in attention computation and up to 2.28x acceleration in end-to-end latency, while providing superior performance compared to state-of-the-art long-context inference methods.

[Arxiv](https://arxiv.org/abs/2411.02886)