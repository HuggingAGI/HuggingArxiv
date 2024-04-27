# 在检索增强生成领域，对检索质量的评估至关重要。

发布时间：2024年04月21日

`RAG` `信息检索`

> Evaluating Retrieval Quality in Retrieval-Augmented Generation

# 摘要

> 评估增强检索生成（RAG）存在难题，尤其是在这些系统的检索模型上。传统的端到端评估不仅计算成本高，而且基于查询-文档相关性的评估与RAG系统的实际下游性能关联度不高。为此，我们引入了一种创新的评估方案——eRAG。在eRAG中，RAG系统中的大型语言模型会独立处理检索列表中的每一个文档，并针对每个文档生成的输出进行下游任务真值标签的评估。这样，每个文档的下游表现就成为了其相关性的评价标准。我们利用多种下游任务的度量标准来获取文档级别的标注，并通过集合或排名度量进行整合。广泛的实验显示，eRAG与RAG系统下游性能的相关性显著优于传统方法，Kendall's τ相关系数提升介于0.168至0.494之间。同时，eRAG在计算效率上也具有明显优势，不仅缩短了运行时间，而且GPU内存消耗降低了高达50倍。

> Evaluating retrieval-augmented generation (RAG) presents challenges, particularly for retrieval models within these systems. Traditional end-to-end evaluation methods are computationally expensive. Furthermore, evaluation of the retrieval model's performance based on query-document relevance labels shows a small correlation with the RAG system's downstream performance. We propose a novel evaluation approach, eRAG, where each document in the retrieval list is individually utilized by the large language model within the RAG system. The output generated for each document is then evaluated based on the downstream task ground truth labels. In this manner, the downstream performance for each document serves as its relevance label. We employ various downstream task metrics to obtain document-level annotations and aggregate them using set-based or ranking metrics. Extensive experiments on a wide range of datasets demonstrate that eRAG achieves a higher correlation with downstream RAG performance compared to baseline methods, with improvements in Kendall's $τ$ correlation ranging from 0.168 to 0.494. Additionally, eRAG offers significant computational advantages, improving runtime and consuming up to 50 times less GPU memory than end-to-end evaluation.

[Arxiv](https://arxiv.org/abs/2404.13781)