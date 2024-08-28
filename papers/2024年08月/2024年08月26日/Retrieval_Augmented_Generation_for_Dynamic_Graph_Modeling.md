# 动态图建模中的增强生成检索技术

发布时间：2024年08月26日

`RAG` `图神经网络` `时间序列分析`

> Retrieval Augmented Generation for Dynamic Graph Modeling

# 摘要

> 动态图建模在分析演变模式中至关重要。现有方法虽结合图神经网络与时间模块，但常局限于单一节点的历史上下文，忽视了其他节点的相关模式。为此，我们提出RAG4DyG框架，通过借鉴上下文和时间相似的示例，拓宽节点视角。该方法面临两大挑战：如何精准检索相关示例，以及如何有效整合这些示例以提升建模。为此，RAG4DyG通过对比学习模块精准检索相关案例，并采用图融合策略增强历史上下文，从而提升预测性能。跨领域真实数据集的实验验证了RAG4DyG的有效性。

> Dynamic graph modeling is crucial for analyzing evolving patterns in various applications. Existing approaches often integrate graph neural networks with temporal modules or redefine dynamic graph modeling as a generative sequence task. However, these methods typically rely on isolated historical contexts of the target nodes from a narrow perspective, neglecting occurrences of similar patterns or relevant cases associated with other nodes. In this work, we introduce the Retrieval-Augmented Generation for Dynamic Graph Modeling (RAG4DyG) framework, which leverages guidance from contextually and temporally analogous examples to broaden the perspective of each node. This approach presents two critical challenges: (1) How to identify and retrieve high-quality demonstrations that are contextually and temporally analogous to dynamic graph samples? (2) How can these demonstrations be effectively integrated to improve dynamic graph modeling? To address these challenges, we propose RAG4DyG, which enriches the understanding of historical contexts by retrieving and learning from contextually and temporally pertinent demonstrations. Specifically, we employ a time- and context-aware contrastive learning module to identify and retrieve relevant cases for each query sequence. Moreover, we design a graph fusion strategy to integrate the retrieved cases, thereby augmenting the inherent historical contexts for improved prediction. Extensive experiments on real-world datasets across different domains demonstrate the effectiveness of RAG4DyG for dynamic graph modeling.

[Arxiv](https://arxiv.org/abs/2408.14523)