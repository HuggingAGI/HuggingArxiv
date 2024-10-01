# QAEncoder：探索问答系统中的对齐表示学习

发布时间：2024年09月30日

`RAG` `问答系统`

> QAEncoder: Towards Aligned Representation Learning in Question Answering System

# 摘要

> 现代问答系统依赖于 RAG 来提供准确可信的答案。然而，用户查询与相关文档间的天然鸿沟阻碍了精准匹配。基于我们的圆锥分布假设——即潜在查询与文档在嵌入空间中呈圆锥状分布，我们提出了 QAEncoder，一种无需训练的解决方案。QAEncoder 通过估计嵌入空间中潜在查询的期望来替代文档嵌入，并附加文档指纹以区分不同嵌入。实验证明，QAEncoder 能有效对齐，为现有 RAG 架构和训练方法提供即插即用的无缝集成。

> Modern QA systems entail retrieval-augmented generation (RAG) for accurate and trustworthy responses. However, the inherent gap between user queries and relevant documents hinders precise matching. Motivated by our conical distribution hypothesis, which posits that potential queries and documents form a cone-like structure in the embedding space, we introduce QAEncoder, a training-free approach to bridge this gap. Specifically, QAEncoder estimates the expectation of potential queries in the embedding space as a robust surrogate for the document embedding, and attaches document fingerprints to effectively distinguish these embeddings. Extensive experiments on fourteen embedding models across six languages and eight datasets validate QAEncoder's alignment capability, which offers a plug-and-play solution that seamlessly integrates with existing RAG architectures and training-based methods.

[Arxiv](https://arxiv.org/abs/2409.20434)