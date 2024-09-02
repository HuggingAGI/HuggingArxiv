# 探索用户意图：构建基于意图的排名数据集

发布时间：2024年08月30日

`LLM应用` `信息检索` `数据集`

> Understanding the User: An Intent-Based Ranking Dataset

# 摘要

> 随着信息检索系统的进步，对其进行精确评估和基准测试变得尤为关键。本文针对MS MARCO等数据集，提出了一种增强方法，旨在为查询添加详尽的描述信息，特别关注TREC-DL-21和TREC-DL-22这两个重要基准数据集。我们利用顶尖的LLM技术，深入分析查询中的隐含意图，并据此构建丰富且贴切的查询描述。为确保这些描述的质量，我们通过众包收集广泛的人类反馈，以此验证其准确性和信息价值。这些增强的查询描述将为排名、查询重写等任务提供宝贵的评估资源。

> As information retrieval systems continue to evolve, accurate evaluation and benchmarking of these systems become pivotal. Web search datasets, such as MS MARCO, primarily provide short keyword queries without accompanying intent or descriptions, posing a challenge in comprehending the underlying information need. This paper proposes an approach to augmenting such datasets to annotate informative query descriptions, with a focus on two prominent benchmark datasets: TREC-DL-21 and TREC-DL-22. Our methodology involves utilizing state-of-the-art LLMs to analyze and comprehend the implicit intent within individual queries from benchmark datasets. By extracting key semantic elements, we construct detailed and contextually rich descriptions for these queries. To validate the generated query descriptions, we employ crowdsourcing as a reliable means of obtaining diverse human perspectives on the accuracy and informativeness of the descriptions. This information can be used as an evaluation set for tasks such as ranking, query rewriting, or others.

[Arxiv](https://arxiv.org/abs/2408.17103)