# ZeroDL：借助大型语言模型，实现文本聚类的零-shot分布学习

发布时间：2024年06月19日

`LLM应用

这篇论文探讨了如何通过情境学习（ICL）来优化大型语言模型（LLMs）在特定任务中的表现，特别是在文本聚类任务中的应用。它介绍了一种方法，通过观察LLM如何描述目标数据集来进行开放式零-shot推理，并将这些推理结果汇总，以定制任务情境。这种方法直接应用于LLM的实际任务中，属于LLM应用的范畴。` `文本聚类`

> ZeroDL: Zero-shot Distribution Learning for Text Clustering via Large Language Models

# 摘要

> 大型语言模型（LLMs）的最新进展极大地推动了自然语言处理（NLP）任务的解决，其中情境学习（ICL）是关键，它帮助LLMs理解任务细节并捕捉微妙之处。本文介绍了一种简便高效的方法，通过观察LLM如何描述目标数据集（全部或部分），进行开放式零-shot推理，并汇总这些推理结果，最终将这些元信息融入实际任务中，从而为特定LLM定制任务情境。我们在文本聚类任务中验证了此方法的有效性，并通过具体示例阐明了情境化的重要性。

> The recent advancements in large language models (LLMs) have brought significant progress in solving NLP tasks. Notably, in-context learning (ICL) is the key enabling mechanism for LLMs to understand specific tasks and grasping nuances. In this paper, we propose a simple yet effective method to contextualize a task toward a specific LLM, by (1) observing how a given LLM describes (all or a part of) target datasets, i.e., open-ended zero-shot inference, and (2) aggregating the open-ended inference results by the LLM, and (3) finally incorporate the aggregated meta-information for the actual task. We show the effectiveness of this approach in text clustering tasks, and also highlight the importance of the contextualization through examples of the above procedure.

![ZeroDL：借助大型语言模型，实现文本聚类的零-shot分布学习](../../../paper_images/2406.13342/framework.png)

[Arxiv](https://arxiv.org/abs/2406.13342)