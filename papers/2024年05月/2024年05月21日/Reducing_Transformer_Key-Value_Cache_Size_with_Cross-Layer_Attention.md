# 利用跨层注意力优化Transformer键值缓存尺寸

发布时间：2024年05月21日

`LLM理论

这篇论文主要探讨了大型语言模型（LLM）中的键值缓存优化技术，特别是提出了跨层注意力（CLA）设计来减少内存需求并保持模型准确性。这种研究属于对LLM内部机制的理论探讨和优化，因此应归类为LLM理论。` `模型优化`

> Reducing Transformer Key-Value Cache Size with Cross-Layer Attention

# 摘要

> 键值缓存是加速基于变换器的自回归大型语言模型解码的关键技术。但随着序列长度和批量增大，其内存需求激增。为此，多查询注意力（MQA）和分组查询注意力（GQA）应运而生，它们通过共享查询头，显著减少了键值头的数量，且对准确性影响甚微。本文提出了一种新的跨层注意力（CLA）设计，通过在相邻层间共享键值头，进一步压缩了KV缓存的大小，同时几乎不损失准确性。实验表明，CLA在内存与准确性的权衡上实现了优化，使得模型能在更大的批量和更长的序列上进行推理，这是传统MQA所不及的。

> Key-value (KV) caching plays an essential role in accelerating decoding for transformer-based autoregressive large language models (LLMs). However, the amount of memory required to store the KV cache can become prohibitive at long sequence lengths and large batch sizes. Since the invention of the transformer, two of the most effective interventions discovered for reducing the size of the KV cache have been Multi-Query Attention (MQA) and its generalization, Grouped-Query Attention (GQA). MQA and GQA both modify the design of the attention block so that multiple query heads can share a single key/value head, reducing the number of distinct key/value heads by a large factor while only minimally degrading accuracy. In this paper, we show that it is possible to take Multi-Query Attention a step further by also sharing key and value heads between adjacent layers, yielding a new attention design we call Cross-Layer Attention (CLA). With CLA, we find that it is possible to reduce the size of the KV cache by another 2x while maintaining nearly the same accuracy as unmodified MQA. In experiments training 1B- and 3B-parameter models from scratch, we demonstrate that CLA provides a Pareto improvement over the memory/accuracy tradeoffs which are possible with traditional MQA, enabling inference with longer sequence lengths and larger batch sizes than would otherwise be possible

[Arxiv](https://arxiv.org/abs/2405.12981)