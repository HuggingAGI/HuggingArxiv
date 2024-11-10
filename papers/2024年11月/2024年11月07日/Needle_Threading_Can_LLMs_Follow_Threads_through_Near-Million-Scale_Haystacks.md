# 穿针引线：大型语言模型能否在近百万规模的干草堆中循线而行？

发布时间：2024年11月07日

`LLM应用` `信息检索` `语言模型`

> Needle Threading: Can LLMs Follow Threads through Near-Million-Scale Haystacks?

# 摘要

> 随着大型语言模型（LLMs）的上下文限制增加，可能的应用范围和下游功能也扩大了。在许多现实世界的任务中，决策取决于分散在通常不同的文档集合中的细节，这些文档大多包含不相关的信息。长上下文的 LLMs 似乎非常适合这种复杂的信息检索和推理形式，传统上这被证明是昂贵和耗时的。然而，尽管近年来更长上下文模型的发展取得了快速进展，但我们对 LLMs 如何有效地使用其上下文的理解却没有跟上。为了解决这个问题，我们进行了一组检索实验，旨在评估 17 个领先的 LLMs 的能力，例如它们通过上下文窗口跟踪信息线索的能力。令人惊讶的是，我们发现许多模型具有显著的线程安全性：能够同时跟踪多个线程而不会显著降低性能。不过，对于许多模型，我们发现有效的上下文限制明显短于支持的上下文长度，随着上下文窗口的增长，准确性会下降。我们的研究还强调了一个重要的点，即来自不同分词器的令牌计数不应直接比较 - 它们通常对应于数量大不相同的书面字符。我们发布了我们的代码和长上下文实验数据。

> As the context limits of Large Language Models (LLMs) increase, the range of possible applications and downstream functions broadens. In many real-world tasks, decisions depend on details scattered across collections of often disparate documents containing mostly irrelevant information. Long-context LLMs appear well-suited to this form of complex information retrieval and reasoning, which has traditionally proven costly and time-consuming. However, although the development of longer context models has seen rapid gains in recent years, our understanding of how effectively LLMs use their context has not kept pace. To address this, we conduct a set of retrieval experiments designed to evaluate the capabilities of 17 leading LLMs, such as their ability to follow threads of information through the context window. Strikingly, we find that many models are remarkably threadsafe: capable of simultaneously following multiple threads without significant loss in performance. Still, for many models, we find the effective context limit is significantly shorter than the supported context length, with accuracy decreasing as the context window grows. Our study also highlights the important point that token counts from different tokenizers should not be directly compared -- they often correspond to substantially different numbers of written characters. We release our code and long-context experimental data.

[Arxiv](https://arxiv.org/abs/2411.05000)