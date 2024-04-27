# 在检索增强生成领域，对检索质量的评估至关重要。

发布时间：2024年04月21日

`分类：RAG` `信息检索`

> Evaluating Retrieval Quality in Retrieval-Augmented Generation

# 摘要

> 评估检索增强生成（RAG）尤其是其中的检索模型，存在一定的难题。传统的端到端评估方式不仅计算成本高，而且基于查询-文档相关性的检索模型性能评估与 RAG 系统的下游性能相关性并不显著。为此，我们提出了一种创新的评估方案——eRAG，它允许 RAG 系统中的大型语言模型独立地利用检索列表中的每个文档，并根据下游任务的标准真实标签来评估每个文档生成的输出。这样，每个文档的下游表现就成为了其相关性标签。我们使用多种下游任务的度量标准来获取文档级别的注解，并通过集合或排名度量进行聚合。广泛的实验表明，eRAG 与 RAG 系统的下游性能相关性更高，Kendall's $τ$ 相关性提升显著，从 0.168 到 0.494 不等。同时，eRAG 在计算效率上也有显著优势，不仅缩短了运行时间，而且 GPU 内存消耗也减少了高达 50 倍，相较于传统的端到端评估方法。

> Evaluating retrieval-augmented generation (RAG) presents challenges, particularly for retrieval models within these systems. Traditional end-to-end evaluation methods are computationally expensive. Furthermore, evaluation of the retrieval model's performance based on query-document relevance labels shows a small correlation with the RAG system's downstream performance. We propose a novel evaluation approach, eRAG, where each document in the retrieval list is individually utilized by the large language model within the RAG system. The output generated for each document is then evaluated based on the downstream task ground truth labels. In this manner, the downstream performance for each document serves as its relevance label. We employ various downstream task metrics to obtain document-level annotations and aggregate them using set-based or ranking metrics. Extensive experiments on a wide range of datasets demonstrate that eRAG achieves a higher correlation with downstream RAG performance compared to baseline methods, with improvements in Kendall's $τ$ correlation ranging from 0.168 to 0.494. Additionally, eRAG offers significant computational advantages, improving runtime and consuming up to 50 times less GPU memory than end-to-end evaluation.

[Arxiv](https://arxiv.org/abs/2404.13781)