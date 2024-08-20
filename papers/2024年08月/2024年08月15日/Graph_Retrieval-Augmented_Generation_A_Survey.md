# 图检索增强生成技术综述

发布时间：2024年08月15日

`RAG` `人工智能` `知识图谱`

> Graph Retrieval-Augmented Generation: A Survey

# 摘要

> 近期，RAG 技术在无需重新训练的情况下，成功应对了 LLM 的诸多挑战。通过引入外部知识库，RAG 显著提升了 LLM 输出的质量，有效解决了“幻觉”、领域知识缺失及信息过时等问题。然而，数据库中实体关系的复杂性对 RAG 构成了挑战。GraphRAG 技术应运而生，它利用实体间的结构信息，实现更精准的检索，增强关系知识的捕捉，并生成更符合上下文的响应。鉴于 GraphRAG 的独特优势，本文首次系统梳理了其方法论，涵盖了基于图的索引、图引导的检索及图增强的生成等关键环节。我们详细介绍了各阶段的核心技术与训练策略，并探讨了 GraphRAG 在下游任务、应用领域、评估体系及工业实践中的表现。最后，我们展望了未来的研究方向，旨在激发更多探索，推动该领域的持续发展。

> Recently, Retrieval-Augmented Generation (RAG) has achieved remarkable success in addressing the challenges of Large Language Models (LLMs) without necessitating retraining. By referencing an external knowledge base, RAG refines LLM outputs, effectively mitigating issues such as ``hallucination'', lack of domain-specific knowledge, and outdated information. However, the complex structure of relationships among different entities in databases presents challenges for RAG systems. In response, GraphRAG leverages structural information across entities to enable more precise and comprehensive retrieval, capturing relational knowledge and facilitating more accurate, context-aware responses. Given the novelty and potential of GraphRAG, a systematic review of current technologies is imperative. This paper provides the first comprehensive overview of GraphRAG methodologies. We formalize the GraphRAG workflow, encompassing Graph-Based Indexing, Graph-Guided Retrieval, and Graph-Enhanced Generation. We then outline the core technologies and training methods at each stage. Additionally, we examine downstream tasks, application domains, evaluation methodologies, and industrial use cases of GraphRAG. Finally, we explore future research directions to inspire further inquiries and advance progress in the field.

[Arxiv](https://arxiv.org/abs/2408.08921)