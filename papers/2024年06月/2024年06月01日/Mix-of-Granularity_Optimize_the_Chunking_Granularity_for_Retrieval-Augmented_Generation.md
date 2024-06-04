# 粒度混合优化：提升检索增强生成中的分块效率

发布时间：2024年06月01日

`RAG

这篇论文主要探讨了在检索增强生成（RAG）系统中如何有效整合来自不同数据源的信息，并提出了混合粒度（MoG）和混合粒度图（MoGG）的方法来优化信息检索过程。这些方法通过动态选择知识库的最佳粒度，并利用图结构来增强信息检索的能力，从而提升RAG系统在下游任务中的表现。因此，这篇论文应归类于RAG。` `信息检索` `数据处理`

> Mix-of-Granularity: Optimize the Chunking Granularity for Retrieval-Augmented Generation

# 摘要

> 在检索增强生成（RAG）系统中，整合来自不同数据源的信息是一大挑战，因为每个知识源都有其独特的数据结构和约定。单一的检索策略往往无法充分利用这些信息。为此，我们借鉴了混合专家（Mix-of-Expert）的概念，提出了混合粒度（Mix-of-Granularity，MoG）方法，它通过一个路由器根据查询动态选择知识库的最佳粒度。该路由器利用一种新的软标签损失函数进行训练。此外，我们将MoG扩展为混合粒度图（Mix-of-Granularity-Graph，MoGG），将参考文档预处理成图，从而能够从远距离的数据块中检索信息。实验证明，MoG和MoGG都能有效提升RAG系统在下游任务中的表现，相关代码也将公开。

> Integrating information from different reference data sources is a major challenge for Retrieval-Augmented Generation (RAG) systems because each knowledge source adopts a unique data structure and follows different conventions. Retrieving from multiple knowledge sources with one fixed strategy usually leads to under-exploitation of information. To mitigate this drawback, inspired by Mix-of-Expert, we introduce Mix-of-Granularity (MoG), a method that dynamically determines the optimal granularity of a knowledge database based on input queries using a router. The router is efficiently trained with a newly proposed loss function employing soft labels. We further extend MoG to Mix-of-Granularity-Graph (MoGG), where reference documents are pre-processed into graphs, enabling the retrieval of relevant information from distantly situated chunks. Extensive experiments demonstrate that both MoG and MoGG effectively predict optimal granularity levels, significantly enhancing the performance of the RAG system in downstream tasks. The code of both MoG and MoGG will be made public.

![粒度混合优化：提升检索增强生成中的分块效率](../../../paper_images/2406.00456/Showcase.png)

![粒度混合优化：提升检索增强生成中的分块效率](../../../paper_images/2406.00456/MoG_principal.png)

![粒度混合优化：提升检索增强生成中的分块效率](../../../paper_images/2406.00456/build_MoGG.png)

![粒度混合优化：提升检索增强生成中的分块效率](../../../paper_images/2406.00456/granularity_distribution.png)

![粒度混合优化：提升检索增强生成中的分块效率](../../../paper_images/2406.00456/rag_k.png)

![粒度混合优化：提升检索增强生成中的分块效率](../../../paper_images/2406.00456/flag_plot.png)

[Arxiv](https://arxiv.org/abs/2406.00456)