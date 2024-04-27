# 在检索增强生成领域，对检索质量的评估至关重要。

发布时间：2024年04月21日

`分类：RAG` `信息检索`

> Evaluating Retrieval Quality in Retrieval-Augmented Generation

# 摘要

> 对检索增强生成（RAG）进行评估并非易事，尤其是在这些系统中的检索模型。传统的端到端评估方式不仅计算成本高，而且基于查询与文档相关性标签的检索模型性能评估与RAG系统的下游性能关联度并不高。为此，我们提出了一种创新的评估方案——eRAG。在eRAG中，RAG系统中的大型语言模型会单独处理检索列表中的每一个文档，并针对每个文档生成的输出进行下游任务真值标签的评估。这样，每个文档的下游表现就成为了其相关性标签。我们采用多种下游任务的度量标准，对文档进行逐级注解，并利用基于集合或排名的度量进行汇总。广泛的实验结果表明，eRAG与RAG系统的下游性能相关性更高，Kendall的$τ$相关性提升显著，从0.168增至0.494。同时，eRAG在计算上具有显著优势，不仅缩短了运行时间，而且相较于端到端评估，GPU内存消耗减少了高达50倍。

> Evaluating retrieval-augmented generation (RAG) presents challenges, particularly for retrieval models within these systems. Traditional end-to-end evaluation methods are computationally expensive. Furthermore, evaluation of the retrieval model's performance based on query-document relevance labels shows a small correlation with the RAG system's downstream performance. We propose a novel evaluation approach, eRAG, where each document in the retrieval list is individually utilized by the large language model within the RAG system. The output generated for each document is then evaluated based on the downstream task ground truth labels. In this manner, the downstream performance for each document serves as its relevance label. We employ various downstream task metrics to obtain document-level annotations and aggregate them using set-based or ranking metrics. Extensive experiments on a wide range of datasets demonstrate that eRAG achieves a higher correlation with downstream RAG performance compared to baseline methods, with improvements in Kendall's $τ$ correlation ranging from 0.168 to 0.494. Additionally, eRAG offers significant computational advantages, improving runtime and consuming up to 50 times less GPU memory than end-to-end evaluation.

[Arxiv](https://arxiv.org/abs/2404.13781)