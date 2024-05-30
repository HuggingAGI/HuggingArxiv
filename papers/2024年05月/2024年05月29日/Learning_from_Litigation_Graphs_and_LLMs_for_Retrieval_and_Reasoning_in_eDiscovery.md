# 诉讼智慧：图与LLMs在电子发现检索与推理中的应用

发布时间：2024年05月29日

`LLM应用

理由：这篇论文介绍了一种名为DISCOvery Graph（DISCOG）的创新混合方法，它结合了异构图方法的精确相关性预测和大型语言模型（LLM）的推理能力，用于电子发现（eDiscovery）领域。这种方法特别强调了在处理大量文档时提高性能和效率，同时保持可解释性。因此，它属于LLM在特定应用领域的应用，即LLM应用分类。`

> Learning from Litigation: Graphs and LLMs for Retrieval and Reasoning in eDiscovery

# 摘要

> 电子发现（eDiscovery）利用AI和NLP技术，从海量文档中精准筛选出法律请求所需的信息，显著提升了审查效率和成本效益。尽管传统方法如BM25或微调模型在eDiscovery中广泛应用，但它们在性能、计算效率和可解释性方面存在局限。相反，基于大型语言模型（LLM）的方法虽强调可解释性，却牺牲了性能和处理速度。本文提出的DISCOvery Graph（DISCOG）是一种创新混合方法，它融合了异构图方法的精确相关性预测和LLM的推理能力。通过图表示学习，我们生成嵌入并预测链接，为特定请求优化语料库排序，同时LLMs提供深入的文档相关性推理。我们的方法在处理不同数据分布时表现出色，F1分数、精确度和召回率分别平均提升12%、3%和16%。在企业应用中，DISCOG与传统手动方法相比，文档审查成本大幅降低99.9%，与LLM分类方法相比也减少了95%。

> Electronic Discovery (eDiscovery) involves identifying relevant documents from a vast collection based on legal production requests. The integration of artificial intelligence (AI) and natural language processing (NLP) has transformed this process, helping document review and enhance efficiency and cost-effectiveness. Although traditional approaches like BM25 or fine-tuned pre-trained models are common in eDiscovery, they face performance, computational, and interpretability challenges. In contrast, Large Language Model (LLM)-based methods prioritize interpretability but sacrifice performance and throughput. This paper introduces DISCOvery Graph (DISCOG), a hybrid approach that combines the strengths of two worlds: a heterogeneous graph-based method for accurate document relevance prediction and subsequent LLM-driven approach for reasoning. Graph representational learning generates embeddings and predicts links, ranking the corpus for a given request, and the LLMs provide reasoning for document relevance. Our approach handles datasets with balanced and imbalanced distributions, outperforming baselines in F1-score, precision, and recall by an average of 12%, 3%, and 16%, respectively. In an enterprise context, our approach drastically reduces document review costs by 99.9% compared to manual processes and by 95% compared to LLM-based classification methods

[Arxiv](https://arxiv.org/abs/2405.19164)