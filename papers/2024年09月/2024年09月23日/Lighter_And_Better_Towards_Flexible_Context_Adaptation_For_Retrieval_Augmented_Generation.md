# 更轻巧，更出色：探索检索增强生成中的灵活上下文适应

发布时间：2024年09月23日

`RAG` `人工智能`

> Lighter And Better: Towards Flexible Context Adaptation For Retrieval Augmented Generation

# 摘要

> 现有的 RAG 系统在成本和效果上存在显著挑战。一方面，它们需要在处理任务前对大量检索到的上下文进行编码，导致高昂的计算成本。另一方面，直接使用通用 LLM 往往生成次优答案，而特定任务的微调又可能削弱 LLM 的通用能力。为此，我们提出了 FlexRAG，一种灵活的上下文适应方法。FlexRAG 通过将检索到的上下文压缩成紧凑嵌入，再由 LLM 编码，同时优化这些嵌入以提升 RAG 性能。其灵活性使其能支持多种压缩比，并保留关键上下文。实验证明，FlexRAG 不仅显著降低成本，还提高了生成质量，成为 RAG 系统的理想选择。

> The existing Retrieval-Augmented Generation (RAG) systems face significant challenges in terms of cost and effectiveness. On one hand, they need to encode the lengthy retrieved contexts before responding to the input tasks, which imposes substantial computational overhead. On the other hand, directly using generic Large Language Models (LLMs) often leads to sub-optimal answers, while task-specific fine-tuning may compromise the LLMs' general capabilities. To address these challenges, we introduce a novel approach called FlexRAG (Flexible Context Adaptation for RAG). In this approach, the retrieved contexts are compressed into compact embeddings before being encoded by the LLMs. Simultaneously, these compressed embeddings are optimized to enhance downstream RAG performance. A key feature of FlexRAG is its flexibility, which enables effective support for diverse compression ratios and selective preservation of important contexts. Thanks to these technical designs, FlexRAG achieves superior generation quality while significantly reducing running costs. Comprehensive experiments on various question-answering datasets validate our approach as a cost-effective and flexible solution for RAG systems.

[Arxiv](https://arxiv.org/abs/2409.15699)