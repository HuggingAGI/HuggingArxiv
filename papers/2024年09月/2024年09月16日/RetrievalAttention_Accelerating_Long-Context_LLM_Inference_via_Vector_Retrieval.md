# RetrievalAttention：利用向量检索技术，加速长上下文 LLM 的推理过程。

发布时间：2024年09月16日

`LLM应用` `人工智能` `云计算`

> RetrievalAttention: Accelerating Long-Context LLM Inference via Vector Retrieval

# 摘要

> 基于Transformer的LLMs在各领域日益重要，但注意力操作的二次时间复杂度限制了其在长上下文中的应用，主要因为推理延迟和GPU内存消耗过高。本文提出RetrievalAttention，一种无需训练的注意力计算加速方法。通过在CPU内存中构建KV向量的ANNS索引，RetrievalAttention在生成时通过向量搜索高效检索相关向量。针对查询与键向量间的OOD问题，RetrievalAttention采用注意力感知向量搜索算法，仅访问1-3%的数据，实现亚线性时间复杂度。这不仅大幅降低推理成本，还保持了模型精度，仅需16GB GPU内存即可处理8B参数LLM中的128K标记，单个RTX4090上生成一个标记仅需0.188秒。

> Transformer-based large Language Models (LLMs) become increasingly important in various domains. However, the quadratic time complexity of attention operation poses a significant challenge for scaling to longer contexts due to the extremely high inference latency and GPU memory consumption for caching key-value (KV) vectors. This paper proposes RetrievalAttention, a training-free approach to accelerate attention computation. To leverage the dynamic sparse property of attention, RetrievalAttention builds approximate nearest neighbor search (ANNS) indexes upon KV vectors in CPU memory and retrieves the most relevant ones via vector search during generation. Due to the out-of-distribution (OOD) between query vectors and key vectors, off-the-shelf ANNS indexes still need to scan O(N) (usually 30% of all keys) data for accurate retrieval, which fails to exploit the high sparsity. RetrievalAttention first identifies the OOD challenge of ANNS-based attention, and addresses it via an attention-aware vector search algorithm that can adapt to queries and only access 1--3% of data, thus achieving a sub-linear time complexity. RetrievalAttention greatly reduces the inference cost of long-context LLM with much lower GPU memory requirements while maintaining the model accuracy. Especially, RetrievalAttention only needs 16GB GPU memory for serving 128K tokens in LLMs with 8B parameters, which is capable of generating one token in 0.188 seconds on a single NVIDIA RTX4090 (24GB).

[Arxiv](https://arxiv.org/abs/2409.10516)