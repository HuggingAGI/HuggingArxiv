# FunnelRAG：一种从粗到细的渐进式 RAG 检索方法

发布时间：2024年10月14日

`RAG` `人工智能` `信息检索`

> FunnelRAG: A Coarse-to-Fine Progressive Retrieval Paradigm for RAG

# 摘要

> 在大规模语言模型中，Retrieval-Augmented Generation (RAG) 已成为主流。它由检索和生成两部分组成，检索器负责寻找有用信息，以辅助生成器的工作。然而，现有的检索范式存在两个问题：一是对单个检索器负担过重，二是检索粒度固定，限制了性能提升。为此，我们提出了FunnelRAG，一种渐进式检索方法，通过从粗到细的粒度、从多到少的数量和从低到高的容量，有效平衡了检索的有效性和效率。实验结果显示，FunnelRAG不仅保持了高检索性能，还将时间开销降低了近40%。

> Retrieval-Augmented Generation (RAG) prevails in Large Language Models. It mainly consists of retrieval and generation. The retrieval modules (a.k.a. retrievers) aim to find useful information used to facilitate generation modules (a.k.a. generators). As such, generators' performance largely depends on the effectiveness and efficiency of retrievers. However, the retrieval paradigm that we design and use remains flat, which treats the retrieval procedures as a one-off deal with constant granularity. Despite effectiveness, we argue that they suffer from two limitations: (1) flat retrieval exerts a significant burden on one retriever; (2) constant granularity limits the ceiling of retrieval performance. In this work, we propose a progressive retrieval paradigm with coarse-to-fine granularity for RAG, termed FunnelRAG, so as to balance effectiveness and efficiency. Specifically, FunnelRAG establishes a progressive retrieval pipeline by collaborating coarse-to-fine granularity, large-to-small quantity, and low-to-high capacity, which can relieve the burden on one retriever and also promote the ceiling of retrieval performance. Extensive experiments manifest that FunnelRAG achieves comparable retrieval performance while the time overhead is reduced by nearly 40 percent.

[Arxiv](https://arxiv.org/abs/2410.10293)