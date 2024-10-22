# EPIC：为大型语言模型服务提供高效的位置无关上下文缓存

发布时间：2024年10月20日

`LLM应用` `人工智能` `云计算`

> EPIC: Efficient Position-Independent Context Caching for Serving Large Language Models

# 摘要

> 大型语言模型 (LLM) 在众多应用中不可或缺，但随着输入复杂性增加，高效服务变得愈发困难。上下文缓存通过利用请求间的依赖性并重用 KV 缓存，显著提升了首次令牌时间 (TTFT)。然而，现有基于前缀的缓存方法限制了在少样本学习、多文档问答等前缀多变的任务中的缓存重用。为此，我们推出了 EPIC，一个引入位置无关上下文缓存 (PIC) 的 LLM 服务系统，无论令牌块位置如何，都能实现 KV 缓存的重用。EPIC 包含两大创新：AttnLink 利用静态注意力稀疏性减少重新计算，KVSplit 则通过定制分块方法保持语义连贯。实验显示，Epic 在 TTFT 上提升高达 8 倍，吞吐量提升 7 倍，且几乎不影响准确性。通过突破传统缓存方法的局限，Epic 为 LLM 推理带来了更高的扩展性和效率。

> Large Language Models (LLMs) are critical for a wide range of applications, but serving them efficiently becomes increasingly challenging as inputs become more complex. Context caching improves serving performance by exploiting inter-request dependency and reusing key-value (KV) cache across requests, thus improving time-to-first-token (TTFT). However, existing prefix-based context caching requires exact token prefix matches, limiting cache reuse in few-shot learning, multi-document QA, or retrieval-augmented generation, where prefixes may vary. In this paper, we present EPIC, an LLM serving system that introduces position-independent context caching (PIC), enabling modular KV cache reuse regardless of token chunk position (or prefix). EPIC features two key designs: AttnLink, which leverages static attention sparsity to minimize recomputation for accuracy recovery, and KVSplit, a customizable chunking method that preserves semantic coherence. Our experiments demonstrate that Epic delivers up to 8x improvements in TTFT and 7x throughput over existing systems, with negligible or no accuracy loss. By addressing the limitations of traditional caching approaches, Epic enables more scalable and efficient LLM inference.

[Arxiv](https://arxiv.org/abs/2410.15332)