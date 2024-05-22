# PyramidInfer：高效 LLM 推理的 Pyramid KV 缓存压缩技术

发布时间：2024年05月21日

`LLM应用

理由：这篇论文主要关注的是大型语言模型（LLMs）在实时应用中的性能优化问题，特别是在聊天机器人等场景下的推理速度和GPU内存使用效率。论文提出了一种名为PyramidInfer的新方法，用于优化KV缓存的存储和使用，以减少内存消耗并提高推理速度。这种方法直接应用于LLM的实际部署和使用中，因此属于LLM应用类别。论文并未涉及Agent的行为、RAG（检索增强生成）的机制或LLM的理论研究，因此不适合归类到其他三个分类中。` `聊天机器人`

> PyramidInfer: Pyramid KV Cache Compression for High-throughput LLM Inference

# 摘要

> 大型语言模型（LLMs）虽理解力惊人，但在实时应用如聊天机器人中，推理时的GPU内存使用成为扩展瓶颈。为提升推理速度，我们利用GPU内存存储计算的键值对（KV缓存）。现有技术通过压缩预计算的KV缓存来节省内存，却忽视了层间依赖和预计算的高内存消耗。我们发现，影响后续生成结果的关键键值对数量随层级递减，且可通过注意力权重的连续性提取。据此，我们开发了PyramidInfer，一种逐层保留关键上下文的KV缓存压缩方法。PyramidInfer在不损性能的前提下，通过减少计算的键值对大幅节省内存。实验表明，PyramidInfer的吞吐量是Accelerate的2.2倍，同时KV缓存的GPU内存使用减少了54%以上。

> Large Language Models (LLMs) have shown remarkable comprehension abilities but face challenges in GPU memory usage during inference, hindering their scalability for real-time applications like chatbots. To accelerate inference, we store computed keys and values (KV cache) in the GPU memory. Existing methods study the KV cache compression to reduce memory by pruning the pre-computed KV cache. However, they neglect the inter-layer dependency between layers and huge memory consumption in pre-computation. To explore these deficiencies, we find that the number of crucial keys and values that influence future generations decreases layer by layer and we can extract them by the consistency in attention weights. Based on the findings, we propose PyramidInfer, a method that compresses the KV cache by layer-wise retaining crucial context. PyramidInfer saves significant memory by computing fewer keys and values without sacrificing performance. Experimental results show PyramidInfer improves 2.2x throughput compared to Accelerate with over 54% GPU memory reduction in KV cache.

[Arxiv](https://arxiv.org/abs/2405.12532)