# TacoERE：事件关系抽取的集群感知压缩技术

发布时间：2024年05月10日

`LLM应用

这篇论文探讨了事件关系抽取（ERE）问题，并提出了一种新的方法——TacoERE，该方法通过文档聚类和信息压缩来提高抽取性能。论文中提到了在RoBERTa、ChatGPT和GPT-4等大型语言模型（LLM）上的实验，这表明论文关注的是LLM在特定NLP任务（即ERE）中的应用。因此，这篇论文应归类为LLM应用。` `事件关系抽取`

> TacoERE: Cluster-aware Compression for Event Relation Extraction

# 摘要

> 事件关系抽取（ERE）是自然语言处理领域的一项关键挑战。传统方法直接对文档整体建模，难以应对长距离依赖和信息冗余问题。为此，我们提出了一种新颖的集群感知压缩方法——TacoERE，它采用先压缩后抽取的策略。首先，通过文档聚类划分内部与外部集群，强化集群内关系，同时捕捉任意距离的事件关联。接着，利用集群摘要精炼并凸显关键信息，减少冗余，缩短事件间距。我们在RoBERTa、ChatGPT和GPT-4等模型上，针对MAVEN-ERE、EventStoryLine和HiEve等数据集进行了深入实验。结果显示，TacoERE在ERE任务上表现出色，有效提升了性能。

> Event relation extraction (ERE) is a critical and fundamental challenge for natural language processing. Existing work mainly focuses on directly modeling the entire document, which cannot effectively handle long-range dependencies and information redundancy. To address these issues, we propose a cluster-aware compression method for improving event relation extraction (TacoERE), which explores a compression-then-extraction paradigm. Specifically, we first introduce document clustering for modeling event dependencies. It splits the document into intra- and inter-clusters, where intra-clusters aim to enhance the relations within the same cluster, while inter-clusters attempt to model the related events at arbitrary distances. Secondly, we utilize cluster summarization to simplify and highlight important text content of clusters for mitigating information redundancy and event distance. We have conducted extensive experiments on both pre-trained language models, such as RoBERTa, and large language models, such as ChatGPT and GPT-4, on three ERE datasets, i.e., MAVEN-ERE, EventStoryLine and HiEve. Experimental results demonstrate that TacoERE is an effective method for ERE.

[Arxiv](https://arxiv.org/abs/2405.06890)