# 利用 LLM 进行视频搜索查询的改写

发布时间：2024年07月17日

`LLM应用` `视频检索` `人工智能`

> LLM-based query paraphrasing for video search

# 摘要

> 文本到视频检索通过概念和嵌入搜索来回应用户查询，但由于概念库和训练数据的限制，常因词汇外问题导致效果不佳。此外，现有搜索方法无法处理包含逻辑和空间约束的复杂查询。为此，我们采用大型语言模型（LLM）通过文本到文本（T2T）、文本到图像（T2I）和图像到文本（I2T）转换来简化查询，有效应对词汇外问题，并将复杂查询分解为简单子查询，提升检索性能。针对LLM可能产生的错误，我们提出了一种基于一致性的验证策略，确保改述查询的准确性。在TRECVid数据集上进行的实验显示，通过查询改述，传统难以回答的查询得到了有效解决。

> Text-to-video retrieval answers user queries through search by concepts and embeddings. Limited by the size of the concept bank and the amount of training data, answering queries in the wild is not always effective due to the out-of-vocabulary problem. Furthermore, neither concept-based nor embedding-based search can perform reasoning to consolidate the search results for complex queries mixed with logical and spatial constraints. To address these problems, we leverage large language models (LLM) to paraphrase the query by text-to-text (T2T), text-to-image (T2I), and image-to-text (I2T) transformations. These transformations rephrase abstract concepts into simple words to address the out-of-vocabulary problem. Furthermore, the complex relationship in a query can be decoupled into simpler sub-queries, yielding better retrieval performance when fusing the search results of these sub-queries. To address the LLM hallucination problem, this paper also proposes a novel consistency-based verification strategy to filter the paraphrased queries that are factually incorrect. Extensive experiments are conducted for ad-hoc video search and known-item search on the TRECVid datasets. We provide empirical insights into how traditionally difficult-to-answer queries can be resolved by query paraphrasing.

[Arxiv](https://arxiv.org/abs/2407.12341)