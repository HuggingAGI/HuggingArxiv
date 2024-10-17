# CoFE-RAG：一个全面的全链路评估框架，专为提升数据多样性的检索增强生成而设计。

发布时间：2024年10月16日

`RAG` `人工智能`

> CoFE-RAG: A Comprehensive Full-chain Evaluation Framework for Retrieval-Augmented Generation with Enhanced Data Diversity

# 摘要

> RAG 通过从外部知识源检索上下文，旨在提升 LLM 生成答案的准确性和可靠性，减少幻觉。然而，评估这些系统仍面临挑战：(1) 数据多样性不足；(2) 问题定位困难；(3) 检索评估不稳定。为此，我们提出 CoFE-RAG 框架，全面评估 RAG 管道的各个阶段。引入多粒度关键词评估检索上下文，并发布多样数据场景的基准数据集。实验显示，CoFE-RAG 框架能深入理解 RAG 系统在多样场景中的表现及其局限。

> Retrieval-Augmented Generation (RAG) aims to enhance large language models (LLMs) to generate more accurate and reliable answers with the help of the retrieved context from external knowledge sources, thereby reducing the incidence of hallucinations. Despite the advancements, evaluating these systems remains a crucial research area due to the following issues: (1) Limited data diversity: The insufficient diversity of knowledge sources and query types constrains the applicability of RAG systems; (2) Obscure problems location: Existing evaluation methods have difficulty in locating the stage of the RAG pipeline where problems occur; (3) Unstable retrieval evaluation: These methods often fail to effectively assess retrieval performance, particularly when the chunking strategy changes. To tackle these challenges, we propose a Comprehensive Full-chain Evaluation (CoFE-RAG) framework to facilitate thorough evaluation across the entire RAG pipeline, including chunking, retrieval, reranking, and generation. To effectively evaluate the first three phases, we introduce multi-granularity keywords, including coarse-grained and fine-grained keywords, to assess the retrieved context instead of relying on the annotation of golden chunks. Moreover, we release a holistic benchmark dataset tailored for diverse data scenarios covering a wide range of document formats and query types. We demonstrate the utility of the CoFE-RAG framework by conducting experiments to evaluate each stage of RAG systems. Our evaluation method provides unique insights into the effectiveness of RAG systems in handling diverse data scenarios, offering a more nuanced understanding of their capabilities and limitations.

[Arxiv](https://arxiv.org/abs/2410.12248)