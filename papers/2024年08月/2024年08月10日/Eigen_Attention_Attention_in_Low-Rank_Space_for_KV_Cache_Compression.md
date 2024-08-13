# 特征注意力：通过低秩空间中的注意力机制，实现KV缓存的高效压缩。

发布时间：2024年08月10日

`LLM理论` `计算机科学`

> Eigen Attention: Attention in Low-Rank Space for KV Cache Compression

# 摘要

> 大型语言模型 (LLM) 因其卓越的推理能力，在自然语言处理领域取得了显著进展。近期，为了提升模型对复杂任务的处理能力，增加上下文长度成为研究热点。然而，长上下文和大批量处理时，存储注意力键值的 KV 缓存成为内存使用的新瓶颈。为此，我们创新性地提出了特征注意力 (Eigen Attention)，通过在低秩空间执行注意力操作，有效降低了 KV 缓存的内存负担。该方法与现有缓存压缩技术互补，可协同增效。实验表明，特征注意力在保持性能几乎不变的同时，将 KV 缓存大小缩减了高达 40%，注意力操作速度提升了高达 60%。

> Large language models (LLMs) represent a groundbreaking advancement in the domain of natural language processing due to their impressive reasoning abilities. Recently, there has been considerable interest in increasing the context lengths for these models to enhance their applicability to complex tasks. However, at long context lengths and large batch sizes, the key-value (KV) cache, which stores the attention keys and values, emerges as the new bottleneck in memory usage during inference. To address this, we propose Eigen Attention, which performs the attention operation in a low-rank space, thereby reducing the KV cache memory overhead. Our proposed approach is orthogonal to existing KV cache compression techniques and can be used synergistically with them. Through extensive experiments over OPT, MPT, and Llama model families, we demonstrate that Eigen Attention results in up to 40% reduction in KV cache sizes and up to 60% reduction in attention operation latency with minimal drop in performance.

[Arxiv](https://arxiv.org/abs/2408.05646)