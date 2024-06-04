# 粒度混合优化：提升检索增强生成中的分块效率

发布时间：2024年06月01日

`RAG

这篇论文主要探讨了检索增强生成（RAG）系统中如何有效整合不同参考数据源的信息，并提出了混合粒度（MoG）方法以及其升级版混合粒度图（MoGG）来优化信息检索和利用。这些方法和改进直接应用于RAG系统，以提高其在下游任务的表现。因此，这篇论文应归类于RAG。` `信息检索`

> Mix-of-Granularity: Optimize the Chunking Granularity for Retrieval-Augmented Generation

# 摘要

> 整合不同参考数据源的信息对检索增强生成（RAG）系统构成重大挑战，因各知识源的数据结构和规范各异。单一检索策略常导致信息利用不足。为此，我们借鉴混合专家（Mix-of-Expert）概念，提出混合粒度（MoG）方法，通过路由器动态调整知识库粒度以匹配查询需求。路由器训练采用新型损失函数，利用软标签优化效率。此外，我们将MoG升级为混合粒度图（MoGG），预处理文档为图结构，便于远距离信息块的检索。实验证明，MoG与MoGG能精准预测粒度，大幅提升RAG系统在下游任务的表现。相关代码即将公开。

> Integrating information from different reference data sources is a major challenge for Retrieval-Augmented Generation (RAG) systems because each knowledge source adopts a unique data structure and follows different conventions. Retrieving from multiple knowledge sources with one fixed strategy usually leads to under-exploitation of information. To mitigate this drawback, inspired by Mix-of-Expert, we introduce Mix-of-Granularity (MoG), a method that dynamically determines the optimal granularity of a knowledge database based on input queries using a router. The router is efficiently trained with a newly proposed loss function employing soft labels. We further extend MoG to Mix-of-Granularity-Graph (MoGG), where reference documents are pre-processed into graphs, enabling the retrieval of relevant information from distantly situated chunks. Extensive experiments demonstrate that both MoG and MoGG effectively predict optimal granularity levels, significantly enhancing the performance of the RAG system in downstream tasks. The code of both MoG and MoGG will be made public.

![粒度混合优化：提升检索增强生成中的分块效率](../../../paper_images/2406.00456/Showcase.png)

![粒度混合优化：提升检索增强生成中的分块效率](../../../paper_images/2406.00456/MoG_principal.png)

![粒度混合优化：提升检索增强生成中的分块效率](../../../paper_images/2406.00456/build_MoGG.png)

![粒度混合优化：提升检索增强生成中的分块效率](../../../paper_images/2406.00456/granularity_distribution.png)

![粒度混合优化：提升检索增强生成中的分块效率](../../../paper_images/2406.00456/rag_k.png)

![粒度混合优化：提升检索增强生成中的分块效率](../../../paper_images/2406.00456/flag_plot.png)

[Arxiv](https://arxiv.org/abs/2406.00456)