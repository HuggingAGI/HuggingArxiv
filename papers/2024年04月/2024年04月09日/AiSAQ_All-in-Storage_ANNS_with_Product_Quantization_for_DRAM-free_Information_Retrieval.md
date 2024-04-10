# AiSAQ: 采用产品量化技术的全存储式近似最近邻搜索（ANNS），免除了对动态随机存取存储器（DRAM）的依赖，实现了高效的信息检索功能。

发布时间：2024年04月09日

`RAG` `计算机科学` `数据检索`

> AiSAQ: All-in-Storage ANNS with Product Quantization for DRAM-free Information Retrieval

# 摘要

> 在基于近似邻近图的近似最近邻搜索（ANNS）方法中，DiskANN在利用RAM和存储资源的同时，为大规模数据集带来了召回率与速度的优化平衡。尽管它声称通过产品量化（PQ）技术加载压缩向量以节省内存，但实际上内存消耗却随数据集规模扩大而增长。本文提出了一种全新的全存储ANNS与产品量化（AiSAQ）策略，将压缩向量移至存储层面。该方法在处理十亿级数据集的查询搜索时，仅需约10MB的内存，且性能损失微乎其微。AiSAQ还缩短了查询前的索引加载时间，使得在众多十亿级数据集间快速切换索引成为现实，极大提升了检索增强生成（RAG）的灵活性。此方法普适于各类基于图的ANNS算法，并有望与未来更高性能的ANNS技术相融合。

> In approximate nearest neighbor search (ANNS) methods based on approximate proximity graphs, DiskANN achieves good recall-speed balance for large-scale datasets using both of RAM and storage. Despite it claims to save memory usage by loading compressed vectors by product quantization (PQ), its memory usage increases in proportion to the scale of datasets. In this paper, we propose All-in-Storage ANNS with Product Quantization (AiSAQ), which offloads the compressed vectors to storage. Our method achieves $\sim$10 MB memory usage in query search even with billion-scale datasets with minor performance degradation. AiSAQ also reduces the index load time before query search, which enables the index switch between muitiple billion-scale datasets and significantly enhances the flexibility of retrieval-augmented generation (RAG). This method is applicable to all graph-based ANNS algorithms and can be combined with higher-spec ANNS methods in the future.

![AiSAQ: 采用产品量化技术的全存储式近似最近邻搜索（ANNS），免除了对动态随机存取存储器（DRAM）的依赖，实现了高效的信息检索功能。](../../../paper_images/2404.06004/x1.png)

![AiSAQ: 采用产品量化技术的全存储式近似最近邻搜索（ANNS），免除了对动态随机存取存储器（DRAM）的依赖，实现了高效的信息检索功能。](../../../paper_images/2404.06004/x2.png)

![AiSAQ: 采用产品量化技术的全存储式近似最近邻搜索（ANNS），免除了对动态随机存取存储器（DRAM）的依赖，实现了高效的信息检索功能。](../../../paper_images/2404.06004/recall_latency_sift1m.png)

![AiSAQ: 采用产品量化技术的全存储式近似最近邻搜索（ANNS），免除了对动态随机存取存储器（DRAM）的依赖，实现了高效的信息检索功能。](../../../paper_images/2404.06004/recall_latency_sift1b.png)

![AiSAQ: 采用产品量化技术的全存储式近似最近邻搜索（ANNS），免除了对动态随机存取存储器（DRAM）的依赖，实现了高效的信息检索功能。](../../../paper_images/2404.06004/recall_latency_kilt_e5.png)

![AiSAQ: 采用产品量化技术的全存储式近似最近邻搜索（ANNS），免除了对动态随机存取存储器（DRAM）的依赖，实现了高效的信息检索功能。](../../../paper_images/2404.06004/latency_mem_usage.png)

[Arxiv](https://arxiv.org/abs/2404.06004)