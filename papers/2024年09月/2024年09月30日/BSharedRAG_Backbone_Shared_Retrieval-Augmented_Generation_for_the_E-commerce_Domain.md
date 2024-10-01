# BSharedRAG：电商领域的主干共享检索增强生成技术

发布时间：2024年09月30日

`RAG` `电子商务` `信息检索`

> BSharedRAG: Backbone Shared Retrieval-Augmented Generation for the E-commerce Domain

# 摘要

> 在电子商务等长尾实体和信息频繁更新的领域，Retrieval Augmented Generation (RAG) 系统至关重要。现有方法通常将检索和生成任务分开处理，未能充分利用两者的协同效应。为此，我们提出了 Backbone Shared RAG (BSharedRAG) 框架，通过特定领域的预训练和低秩适应模块，实现检索与生成的无缝结合。实验显示，BSharedRAG 在检索和生成任务上均显著优于传统模型。详细信息及资源请访问 https://bsharedrag.github.io。

> Retrieval Augmented Generation (RAG) system is important in domains such as e-commerce, which has many long-tail entities and frequently updated information. Most existing works adopt separate modules for retrieval and generation, which may be suboptimal since the retrieval task and the generation task cannot benefit from each other to improve performance. We propose a novel Backbone Shared RAG framework (BSharedRAG). It first uses a domain-specific corpus to continually pre-train a base model as a domain-specific backbone model and then trains two plug-and-play Low-Rank Adaptation (LoRA) modules based on the shared backbone to minimize retrieval and generation losses respectively. Experimental results indicate that our proposed BSharedRAG outperforms baseline models by 5% and 13% in Hit@3 upon two datasets in retrieval evaluation and by 23% in terms of BLEU-3 in generation evaluation. Our codes, models, and dataset are available at https://bsharedrag.github.io.

[Arxiv](https://arxiv.org/abs/2409.20075)