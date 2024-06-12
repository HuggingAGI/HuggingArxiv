# 探究大型语言模型在Tetun语境下的相关性评估能力

发布时间：2024年06月11日

`LLM应用

这篇论文探讨了在低资源语言环境中利用大型语言模型（LLMs）进行自动化相关性评估的可行性。研究中使用了特定语言（Tetun）的查询-文档对，并让LLMs执行相关性评分任务，然后与人类评分进行对比以衡量标注一致性。这属于LLM在特定应用场景中的实际应用，因此应归类为LLM应用。` `信息检索`

> Exploring Large Language Models for Relevance Judgments in Tetun

# 摘要

> Cranfield范式作为开发测试集合的基础方法，其相关性判断传统上依赖于人类评估员。但随着大型语言模型（LLMs）的兴起，自动化这些任务成为可能。本文探讨了在低资源语言环境中，利用LLMs进行自动化相关性评估的可行性。研究中，我们使用Tetun语言的查询-文档对作为输入，让LLMs自动执行相关性评分任务，并将模型评分与人类评分进行对比，以衡量标注一致性。研究结果显示，与高资源语言的研究结果高度一致。

> The Cranfield paradigm has served as a foundational approach for developing test collections, with relevance judgments typically conducted by human assessors. However, the emergence of large language models (LLMs) has introduced new possibilities for automating these tasks. This paper explores the feasibility of using LLMs to automate relevance assessments, particularly within the context of low-resource languages. In our study, LLMs are employed to automate relevance judgment tasks, by providing a series of query-document pairs in Tetun as the input text. The models are tasked with assigning relevance scores to each pair, where these scores are then compared to those from human annotators to evaluate the inter-annotator agreement levels. Our investigation reveals results that align closely with those reported in studies of high-resource languages.

[Arxiv](https://arxiv.org/abs/2406.07299)