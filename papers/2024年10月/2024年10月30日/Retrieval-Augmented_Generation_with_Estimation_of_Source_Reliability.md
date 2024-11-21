# 带有源可靠性估计的检索增强生成

发布时间：2024年10月30日

`RAG` `数据库` `语言模型`

> Retrieval-Augmented Generation with Estimation of Source Reliability

# 摘要

> 检索增强生成（RAG）借助外部数据库，化解了大型语言模型（LLMs）的关键短板，像产生幻觉、知识陈旧等。这些数据库通常会整合多个来源，以涵盖最新且多样的信息。但标准的 RAG 方法往往忽视多源数据库中不同来源的可靠性，仅依据相关性来检索文档，这就容易导致错误信息的传播。为此，我们提出了可靠性感知的 RAG（RA-RAG），它能估算多个来源的可靠性，并将此信息融入检索和聚合流程。具体而言，它会对一组无标签的查询反复估算来源可靠性和真实答案。接着，它从少数可靠的来源中有选择性地检索相关文档，并通过加权多数投票进行聚合，这种选择性检索既保证了可扩展性，又不影响性能。我们还引入了一个基准，旨在反映具有异构源可靠性的真实场景，并证明了 RA-RAG 相较于一组基线的有效性。

> Retrieval-augmented generation (RAG) addresses key limitations of large language models (LLMs), such as hallucinations and outdated knowledge, by incorporating external databases. These databases typically consult multiple sources to encompass up-to-date and various information. However, standard RAG methods often overlook the heterogeneous source reliability in the multi-source database and retrieve documents solely based on relevance, making them prone to propagating misinformation. To address this, we propose Reliability-Aware RAG (RA-RAG) which estimates the reliability of multiple sources and incorporates this information into both retrieval and aggregation processes. Specifically, it iteratively estimates source reliability and true answers for a set of queries with no labelling. Then, it selectively retrieves relevant documents from a few of reliable sources and aggregates them using weighted majority voting, where the selective retrieval ensures scalability while not compromising the performance. We also introduce a benchmark designed to reflect real-world scenarios with heterogeneous source reliability and demonstrate the effectiveness of RA-RAG compared to a set of baselines.

[Arxiv](https://arxiv.org/abs/2410.22954)