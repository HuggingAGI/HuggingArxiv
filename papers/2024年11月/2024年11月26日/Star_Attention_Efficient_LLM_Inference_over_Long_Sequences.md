# Star Attention：针对长序列的高效 LLM 推理

发布时间：2024年11月26日

`LLM应用` `语言模型` `计算效率`

> Star Attention: Efficient LLM Inference over Long Sequences

# 摘要

> 基于 Transformer 的大型语言模型（LLMs）在长序列上进行推理，因自注意力机制的二次复杂性，成本高且速度慢。我们推出了星型注意力，这是一种两阶段的块稀疏近似方法，能通过在多台主机间分配注意力并最小化通信开销来提升计算效率。第一阶段，利用跨主机的分块局部注意力并行处理上下文。第二阶段，查询和响应标记通过序列全局注意力关注所有先前缓存的标记。星型注意力与大多数用全局注意力训练的基于 Transformer 的 LLMs 完美融合，在保证 95 - 100%准确率的同时，将内存需求和推理时间最多降低 11 倍。

> Inference with Transformer-based Large Language Models (LLMs) on long sequences is both costly and slow due to the quadratic complexity of the self-attention mechanism. We introduce Star Attention, a two-phase block-sparse approximation that improves computational efficiency by sharding attention across multiple hosts while minimizing communication overhead. In the first phase, the context is processed using blockwise-local attention across hosts, in parallel. In the second phase, query and response tokens attend to all prior cached tokens through sequence-global attention. Star Attention integrates seamlessly with most Transformer-based LLMs trained with global attention, reducing memory requirements and inference time by up to 11x while preserving 95-100% of accuracy.

[Arxiv](https://arxiv.org/abs/2411.17116)