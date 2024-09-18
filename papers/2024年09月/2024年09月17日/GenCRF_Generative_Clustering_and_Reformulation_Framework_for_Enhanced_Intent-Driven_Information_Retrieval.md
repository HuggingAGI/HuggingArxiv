# GenCRF：一个旨在提升意图驱动信息检索的生成聚类与重构框架

发布时间：2024年09月17日

`LLM应用` `信息检索` `搜索引擎`

> GenCRF: Generative Clustering and Reformulation Framework for Enhanced Intent-Driven Information Retrieval

# 摘要

> 查询重构是信息检索中的关键问题，旨在通过自动调整用户查询来提高搜索成功率。尽管最近利用大型语言模型（LLM）改进了这一过程，但往往生成的查询扩展有限且冗余，难以捕捉多样化意图。为此，我们提出了 GenCRF：一个创新的生成聚类与重构框架，首次在检索阶段通过多个差异化查询自适应捕捉多样化意图。GenCRF 利用 LLM 生成多样化的查询，并通过聚类明确表示这些意图。此外，框架采用创新的加权聚合策略优化检索效果，并引入查询评估奖励模型（QERM）通过反馈循环持续改进。实验表明，GenCRF 在 BEIR 基准上超越了现有最先进方法高达 12%，为信息检索领域带来了显著进步。

> Query reformulation is a well-known problem in Information Retrieval (IR) aimed at enhancing single search successful completion rate by automatically modifying user's input query. Recent methods leverage Large Language Models (LLMs) to improve query reformulation, but often generate limited and redundant expansions, potentially constraining their effectiveness in capturing diverse intents. In this paper, we propose GenCRF: a Generative Clustering and Reformulation Framework to capture diverse intentions adaptively based on multiple differentiated, well-generated queries in the retrieval phase for the first time. GenCRF leverages LLMs to generate variable queries from the initial query using customized prompts, then clusters them into groups to distinctly represent diverse intents. Furthermore, the framework explores to combine diverse intents query with innovative weighted aggregation strategies to optimize retrieval performance and crucially integrates a novel Query Evaluation Rewarding Model (QERM) to refine the process through feedback loops. Empirical experiments on the BEIR benchmark demonstrate that GenCRF achieves state-of-the-art performance, surpassing previous query reformulation SOTAs by up to 12% on nDCG@10. These techniques can be adapted to various LLMs, significantly boosting retriever performance and advancing the field of Information Retrieval.

[Arxiv](https://arxiv.org/abs/2409.10909)