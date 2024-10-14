# StructRAG：通过推理时的混合信息结构化，大幅提升 LLM 在知识密集型推理中的表现。

发布时间：2024年10月11日

`RAG` `人工智能` `知识管理`

> StructRAG: Boosting Knowledge Intensive Reasoning of LLMs via Inference-time Hybrid Information Structurization

# 摘要

> RAG 是提升 LLM 在知识密集型任务中表现的关键技术。然而，现有方法在处理复杂推理任务时，由于信息分散，难以准确提取关键信息。本文借鉴人类将信息结构化的认知过程，提出了 StructRAG 框架，通过识别并重构任务所需的最佳结构，实现更精准的推理。实验证明，StructRAG 在多任务中表现卓越，尤其在挑战性场景中，展现了其在复杂应用中提升 LLM 能力的巨大潜力。

> Retrieval-augmented generation (RAG) is a key means to effectively enhance large language models (LLMs) in many knowledge-based tasks. However, existing RAG methods struggle with knowledge-intensive reasoning tasks, because useful information required to these tasks are badly scattered. This characteristic makes it difficult for existing RAG methods to accurately identify key information and perform global reasoning with such noisy augmentation. In this paper, motivated by the cognitive theories that humans convert raw information into various structured knowledge when tackling knowledge-intensive reasoning, we proposes a new framework, StructRAG, which can identify the optimal structure type for the task at hand, reconstruct original documents into this structured format, and infer answers based on the resulting structure. Extensive experiments across various knowledge-intensive tasks show that StructRAG achieves state-of-the-art performance, particularly excelling in challenging scenarios, demonstrating its potential as an effective solution for enhancing LLMs in complex real-world applications.

[Arxiv](https://arxiv.org/abs/2410.08815)