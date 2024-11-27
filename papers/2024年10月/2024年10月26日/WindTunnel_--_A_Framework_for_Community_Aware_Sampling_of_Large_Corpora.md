# WindTunnel —— 一个针对大型语料库进行社区感知采样的框架

发布时间：2024年10月26日

`其他` `信息检索` `大数据`

> WindTunnel -- A Framework for Community Aware Sampling of Large Corpora

# 摘要

> 在诸如搜索或检索增强生成等方面开展全面的信息检索实验，往往会产生高昂的计算成本。这是由于评估一个检索算法需要对整个语料库进行索引，其规模远大于所评估的（查询，结果）对集合。此问题在大数据和神经检索中尤为显著，索引工作变得愈发耗时且复杂。在本文中，我们推出了 WindTunnel，这是 Yext 开发的一个全新框架，用于生成大型语料库的代表性样本，以实现高效的端到端信息检索实验。凭借对数据集社区结构的保留，WindTunnel 克服了当前采样方法的局限，提供了更精准的评估。

> Conducting comprehensive information retrieval experiments, such as in search or retrieval augmented generation, often comes with high computational costs. This is because evaluating a retrieval algorithm requires indexing the entire corpus, which is significantly larger than the set of (query, result) pairs under evaluation. This issue is especially pronounced in big data and neural retrieval, where indexing becomes increasingly time-consuming and complex. In this paper, we present WindTunnel, a novel framework developed at Yext to generate representative samples of large corpora, enabling efficient end-to-end information retrieval experiments. By preserving the community structure of the dataset, WindTunnel overcomes limitations in current sampling methods, providing more accurate evaluations.

[Arxiv](https://arxiv.org/abs/2410.20301)