# 多重元RAG：通过LLM提取的元数据优化数据库过滤，提升RAG对复杂多步查询的响应能力

发布时间：2024年06月19日

`RAG

理由：这篇论文介绍了一种名为Multi-Meta-RAG的新技术，它是检索增强生成（RAG）技术的一个变体，旨在改进大型语言模型（LLMs）在处理多跳问题时的性能。该技术通过利用LLM提取的元数据来优化数据库筛选过程，从而提高从多源中检索相关文档的准确性。这与RAG技术的核心目标——增强LLMs的检索和生成能力——紧密相关，因此将其归类为RAG。` `知识图谱` `问答系统`

> Multi-Meta-RAG: Improving RAG for Multi-Hop Queries using Database Filtering with LLM-Extracted Metadata

# 摘要

> 检索增强生成（RAG）技术使大型语言模型（LLMs）能够从外部知识库中提取相关信息，并解答未曾接触过的文档集合上的查询。然而，传统RAG在应对需跨多个证据元素进行检索与推理的多跳问题时显得力不从心。为此，我们推出了Multi-Meta-RAG这一创新方法，它利用LLM提取的元数据进行精准的数据库筛选，从而优化了从多源中挑选出与问题紧密相关的文档的过程。尽管数据库筛选针对特定领域和格式的问题集，但我们的实验表明，Multi-Meta-RAG在MultiHop-RAG基准测试中显著提升了性能。相关代码已公开于https://github.com/mxpoliakov/Multi-Meta-RAG。

> The retrieval-augmented generation (RAG) enables retrieval of relevant information from an external knowledge source and allows large language models (LLMs) to answer queries over previously unseen document collections. However, it was demonstrated that traditional RAG applications perform poorly in answering multi-hop questions, which require retrieving and reasoning over multiple elements of supporting evidence. We introduce a new method called Multi-Meta-RAG, which uses database filtering with LLM-extracted metadata to improve the RAG selection of the relevant documents from various sources, relevant to the question. While database filtering is specific to a set of questions from a particular domain and format, we found out that Multi-Meta-RAG greatly improves the results on the MultiHop-RAG benchmark. The code is available at https://github.com/mxpoliakov/Multi-Meta-RAG.

![多重元RAG：通过LLM提取的元数据优化数据库过滤，提升RAG对复杂多步查询的响应能力](../../../paper_images/2406.13213/x1.png)

![多重元RAG：通过LLM提取的元数据优化数据库过滤，提升RAG对复杂多步查询的响应能力](../../../paper_images/2406.13213/x2.png)

[Arxiv](https://arxiv.org/abs/2406.13213)