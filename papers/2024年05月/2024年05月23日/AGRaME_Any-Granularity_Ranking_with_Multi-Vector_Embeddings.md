# AGRaME：多向量嵌入下的任意粒度排序技术

发布时间：2024年05月23日

`RAG

理由：这篇论文主要关注的是搜索领域的排名问题，并提出了一种任意粒度排名方法，这种方法通过多向量嵌入技术在不同粒度级别上进行排名。这与检索增强生成（RAG）模型中的技术相似，RAG模型结合了检索和生成两种方法来提高语言模型的性能。因此，这篇论文的内容与RAG模型的应用和技术改进相关，适合归类到RAG分类中。` `问答系统`

> AGRaME: Any-Granularity Ranking with Multi-Vector Embeddings

# 摘要

> 在搜索领域，排名问题至关重要且广受欢迎。然而，现有排名算法往往将排名粒度固定在全文或特定密集索引上，这种缺乏灵活性的做法限制了其在需要更细粒度排名场景中的应用，如开放域问答的句子级排名或归因的命题级排名。本研究提出了一种任意粒度排名方法，通过多向量嵌入技术，在不同粒度级别上进行排名，同时保持单一（较粗）粒度级别的编码。我们设计了一种多粒度对比损失函数来训练多向量方法，并通过句子和命题作为排名单位验证了其有效性。最终，我们将命题级排名应用于检索增强生成中的后验引用添加，其性能超越了基于提示的引用生成方法。

> Ranking is a fundamental and popular problem in search. However, existing ranking algorithms usually restrict the granularity of ranking to full passages or require a specific dense index for each desired level of granularity. Such lack of flexibility in granularity negatively affects many applications that can benefit from more granular ranking, such as sentence-level ranking for open-domain question-answering, or proposition-level ranking for attribution. In this work, we introduce the idea of any-granularity ranking, which leverages multi-vector embeddings to rank at varying levels of granularity while maintaining encoding at a single (coarser) level of granularity. We propose a multi-granular contrastive loss for training multi-vector approaches, and validate its utility with both sentences and propositions as ranking units. Finally, we demonstrate the application of proposition-level ranking to post-hoc citation addition in retrieval-augmented generation, surpassing the performance of prompt-driven citation generation.

![AGRaME：多向量嵌入下的任意粒度排序技术](../../../paper_images/2405.15028/Any_Granularity_Ranking.png)

![AGRaME：多向量嵌入下的任意粒度排序技术](../../../paper_images/2405.15028/sentence_scoring_v2.png)

![AGRaME：多向量嵌入下的任意粒度排序技术](../../../paper_images/2405.15028/q2s_loss_v2.png)

![AGRaME：多向量嵌入下的任意粒度排序技术](../../../paper_images/2405.15028/q2p_loss_v2.png)

![AGRaME：多向量嵌入下的任意粒度排序技术](../../../paper_images/2405.15028/attribution.png)

[Arxiv](https://arxiv.org/abs/2405.15028)