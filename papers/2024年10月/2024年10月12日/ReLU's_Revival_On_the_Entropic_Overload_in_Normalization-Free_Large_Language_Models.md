# ReLU 的复兴：探讨无归一化大型语言模型中的熵过载问题

发布时间：2024年10月12日

`LLM理论` `人工智能`

> ReLU's Revival: On the Entropic Overload in Normalization-Free Large Language Models

# 摘要

> LayerNorm 在现代 LLM 中至关重要，但它在机制可解释性和计算复杂性等方面带来了挑战。我们研究发现，在无 LayerNorm 的 LLM 中，ReLU 比传统的 GELU 表现更优，困惑度降低了 8.2%。GELU 在早期层中存在熵过载问题，导致注意力头的能力未充分利用。相比之下，ReLU 的几何特性在没有 LayerNorm 的情况下优化了学习动态和信息保留。这一发现为优化 LayerNorm 带来的挑战提供了新思路。

> LayerNorm is a critical component in modern large language models (LLMs) for stabilizing training and ensuring smooth optimization. However, it introduces significant challenges in mechanistic interpretability, outlier feature suppression, faithful signal propagation, and computational and communication complexity of private inference. This work explores desirable activation functions in normalization-free decoder-only LLMs. Contrary to the conventional preference for the GELU in transformer-based models, our empirical findings demonstrate an {\em opposite trend} -- ReLU significantly outperforms GELU in LayerNorm-free models, leading to an {\bf 8.2\%} perplexity improvement. We discover a key issue with GELU, where early layers experience entropic overload, leading to the under-utilization of the representational capacity of attention heads. This highlights that smoother activations like GELU are {\em ill-suited} for LayerNorm-free architectures, whereas ReLU's geometrical properties -- specialization in input space and intra-class selectivity -- lead to improved learning dynamics and better information retention in the absence of LayerNorm. This study offers key insights for optimizing transformer architectures where LayerNorm introduces significant challenges.

[Arxiv](https://arxiv.org/abs/2410.09637)