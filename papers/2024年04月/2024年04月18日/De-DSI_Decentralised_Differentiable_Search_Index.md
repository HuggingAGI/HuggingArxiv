# De-DSI：分布式可微搜索索引

发布时间：2024年04月18日

`分类：LLM应用` `信息检索` `去中心化技术`

> De-DSI: Decentralised Differentiable Search Index

# 摘要

> 本研究提出了 De-DSI，这是一个创新框架，它融合了大型语言模型（LLMs）和真正的去中心化技术，特别在去中心化环境中应用了可微搜索索引（DSI）的概念，以提升信息检索效率。De-DSI 旨在无需直接访问文档的情况下，高效地将用户查询与文档标识符相匹配，仅基于查询-docid对进行操作。为提高可扩展性，本框架采用了 DSI 模型集合，将数据集分割成较小的片段，以便独立训练各个模型。这一方法不仅通过减少单个模型需处理的数据量来保持准确度，还通过聚合多个模型的结果来增强可扩展性。聚合过程采用束搜索技术来筛选出排名靠前的 docids，并通过 softmax 函数进行得分标准化，最终选出得分最高的文档进行检索。去中心化的实现方式不仅确保了与集中式方法相媲美的检索成功率，还带来了在网络中分散计算负载的优势。此外，该系统还支持通过磁力链接检索多媒体内容，省去了对平台或中介的依赖。

> This study introduces De-DSI, a novel framework that fuses large language models (LLMs) with genuine decentralization for information retrieval, particularly employing the differentiable search index (DSI) concept in a decentralized setting. Focused on efficiently connecting novel user queries with document identifiers without direct document access, De-DSI operates solely on query-docid pairs. To enhance scalability, an ensemble of DSI models is introduced, where the dataset is partitioned into smaller shards for individual model training. This approach not only maintains accuracy by reducing the number of data each model needs to handle but also facilitates scalability by aggregating outcomes from multiple models. This aggregation uses a beam search to identify top docids and applies a softmax function for score normalization, selecting documents with the highest scores for retrieval. The decentralized implementation demonstrates that retrieval success is comparable to centralized methods, with the added benefit of the possibility of distributing computational complexity across the network. This setup also allows for the retrieval of multimedia items through magnet links, eliminating the need for platforms or intermediaries.

[Arxiv](https://arxiv.org/abs/2404.12237)