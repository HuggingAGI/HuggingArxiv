# 少样本成对排序提示：一种高效的非参数检索模型

发布时间：2024年09月26日

`LLM应用` `搜索引擎` `信息检索`

> Few-shot Pairwise Rank Prompting: An Effective Non-Parametric Retrieval Model

# 摘要

> 尽管监督排序模型效果显著，但其复杂的预训练和微调过程令人望而却步。为此，我们转向了能够零-shot 工作的大型语言模型 (LLM)。然而，零-shot 推理缺乏训练集的支持，性能往往不如监督模型。基于训练示例能提升零-shot 性能的发现，我们探索了这一原则是否适用于排序模型。具体而言，通过引入相似查询的偏好示例，我们改进了查询与文档对的偏好预测任务。实验证明，我们的成对少-shot 排序器在 TREC DL 和 BEIR 子集上均优于零-shot 基线，且性能接近监督模型，却无需繁琐的训练流程。

> A supervised ranking model, despite its advantage of being effective, usually involves complex processing - typically multiple stages of task-specific pre-training and fine-tuning. This has motivated researchers to explore simpler pipelines leveraging large language models (LLMs) that are capable of working in a zero-shot manner. However, since zero-shot inference does not make use of a training set of pairs of queries and their relevant documents, its performance is mostly worse than that of supervised models, which are trained on such example pairs. Motivated by the existing findings that training examples generally improve zero-shot performance, in our work, we explore if this also applies to ranking models. More specifically, given a query and a pair of documents, the preference prediction task is improved by augmenting examples of preferences for similar queries from a training set. Our proposed pairwise few-shot ranker demonstrates consistent improvements over the zero-shot baseline on both in-domain (TREC DL) and out-domain (BEIR subset) retrieval benchmarks. Our method also achieves a close performance to that of a supervised model without requiring any complex training pipeline.

[Arxiv](https://arxiv.org/abs/2409.17745)