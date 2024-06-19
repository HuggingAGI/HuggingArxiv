# 增强生成检索的统一主动检索方法

发布时间：2024年06月18日

`RAG

理由：这篇论文主要关注的是RAG（Retrieval-Augmented Generation）模型中的检索机制优化问题，特别是提出了统一主动检索（UAR）方法来决定何时进行检索。这种方法旨在通过四个独立标准来优化检索时机的判断，减少系统复杂度和响应延迟。因此，这篇论文的内容与RAG模型的改进和优化直接相关，属于RAG分类。` `信息检索`

> Unified Active Retrieval for Retrieval Augmented Generation

# 摘要

> 在RAG中，并非每次指令都适合应用检索，盲目检索并非最佳选择。因此，决定何时进行检索，即主动检索，对RAG至关重要。但现有方法存在两大难题：一是依赖单一标准，难以应对多样指令；二是流程复杂且高度特化，增加了系统复杂度和响应延迟。为此，我们提出统一主动检索（UAR），它采用四个独立标准，并将其转化为易于整合的分类任务，实现了高效的检索时机判断，几乎不增加额外成本。我们还设计了统一主动检索标准（UAR-Criteria），通过标准化流程应对各种检索场景。实验证明，UAR在检索时机判断和下游任务表现上均显著优于现有方法，展现了其有效性和对下游任务的积极影响。

> In Retrieval-Augmented Generation (RAG), retrieval is not always helpful and applying it to every instruction is sub-optimal. Therefore, determining whether to retrieve is crucial for RAG, which is usually referred to as Active Retrieval. However, existing active retrieval methods face two challenges: 1. They usually rely on a single criterion, which struggles with handling various types of instructions. 2. They depend on specialized and highly differentiated procedures, and thus combining them makes the RAG system more complicated and leads to higher response latency. To address these challenges, we propose Unified Active Retrieval (UAR). UAR contains four orthogonal criteria and casts them into plug-and-play classification tasks, which achieves multifaceted retrieval timing judgements with negligible extra inference cost. We further introduce the Unified Active Retrieval Criteria (UAR-Criteria), designed to process diverse active retrieval scenarios through a standardized procedure. Experiments on four representative types of user instructions show that UAR significantly outperforms existing work on the retrieval timing judgement and the performance of downstream tasks, which shows the effectiveness of UAR and its helpfulness to downstream tasks.

![增强生成检索的统一主动检索方法](../../../paper_images/2406.12534/x1.png)

![增强生成检索的统一主动检索方法](../../../paper_images/2406.12534/x2.png)

![增强生成检索的统一主动检索方法](../../../paper_images/2406.12534/snowflake.png)

![增强生成检索的统一主动检索方法](../../../paper_images/2406.12534/flame.png)

![增强生成检索的统一主动检索方法](../../../paper_images/2406.12534/x3.png)

[Arxiv](https://arxiv.org/abs/2406.12534)