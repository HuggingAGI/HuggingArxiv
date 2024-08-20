# 元知识在增强检索型大型语言模型中的应用

发布时间：2024年08月16日

`RAG` `信息技术` `人工智能`

> Meta Knowledge for Retrieval Augmented Large Language Models

# 摘要

> RAG 技术通过增强 LLM 的上下文相关信息，提升了其处理时效性和领域特定问题的能力，但构建高效综合多样化文档信息的 RAG 系统仍具挑战。我们创新性地将传统“检索-阅读”流程升级为“准备-重写-检索-阅读”框架，通过生成元数据和合成问答，以及引入元知识摘要，实现了对知识库的专家级理解。研究显示，增强查询在性能上显著超越传统 RAG 方法，且元知识查询进一步提升了检索和答案质量。该方法成本低廉，适应性强，为 RAG 流程的性能提升开辟了新路径。

> Retrieval Augmented Generation (RAG) is a technique used to augment Large Language Models (LLMs) with contextually relevant, time-critical, or domain-specific information without altering the underlying model parameters. However, constructing RAG systems that can effectively synthesize information from large and diverse set of documents remains a significant challenge. We introduce a novel data-centric RAG workflow for LLMs, transforming the traditional retrieve-then-read system into a more advanced prepare-then-rewrite-then-retrieve-then-read framework, to achieve higher domain expert-level understanding of the knowledge base. Our methodology relies on generating metadata and synthetic Questions and Answers (QA) for each document, as well as introducing the new concept of Meta Knowledge Summary (MK Summary) for metadata-based clusters of documents. The proposed innovations enable personalized user-query augmentation and in-depth information retrieval across the knowledge base. Our research makes two significant contributions: using LLMs as evaluators and employing new comparative performance metrics, we demonstrate that (1) using augmented queries with synthetic question matching significantly outperforms traditional RAG pipelines that rely on document chunking (p < 0.01), and (2) meta knowledge-augmented queries additionally significantly improve retrieval precision and recall, as well as the final answers breadth, depth, relevancy, and specificity. Our methodology is cost-effective, costing less than $20 per 2000 research papers using Claude 3 Haiku, and can be adapted with any fine-tuning of either the language or embedding models to further enhance the performance of end-to-end RAG pipelines.

[Arxiv](https://arxiv.org/abs/2408.09017)