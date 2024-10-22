# ConTReGen：一种基于上下文的树结构检索方法，专为开放域长文本生成设计。

发布时间：2024年10月20日

`RAG` `人工智能`

> ConTReGen: Context-driven Tree-structured Retrieval for Open-domain Long-form Text Generation

# 摘要

> 开放域长文本生成需要生成连贯且全面的响应，以应对复杂查询的广度和深度。由于需要准确捕捉查询的多样性，这一任务颇具挑战。现有的RAG方法往往难以深入探讨复杂查询的每个方面，并有效整合多源知识。本文介绍的ConTReGen框架，通过上下文驱动的树结构检索方法，增强了检索内容的深度和相关性。ConTReGen结合了层次化的深入探索与系统的综合，确保全面覆盖和连贯整合多方面信息。实验表明，ConTReGen在多个数据集上均优于现有最先进的RAG模型。

> Open-domain long-form text generation requires generating coherent, comprehensive responses that address complex queries with both breadth and depth. This task is challenging due to the need to accurately capture diverse facets of input queries. Existing iterative retrieval-augmented generation (RAG) approaches often struggle to delve deeply into each facet of complex queries and integrate knowledge from various sources effectively. This paper introduces ConTReGen, a novel framework that employs a context-driven, tree-structured retrieval approach to enhance the depth and relevance of retrieved content. ConTReGen integrates a hierarchical, top-down in-depth exploration of query facets with a systematic bottom-up synthesis, ensuring comprehensive coverage and coherent integration of multifaceted information. Extensive experiments on multiple datasets, including LFQA and ODSUM, alongside a newly introduced dataset, ODSUM-WikiHow, demonstrate that ConTReGen outperforms existing state-of-the-art RAG models.

[Arxiv](https://arxiv.org/abs/2410.15511)