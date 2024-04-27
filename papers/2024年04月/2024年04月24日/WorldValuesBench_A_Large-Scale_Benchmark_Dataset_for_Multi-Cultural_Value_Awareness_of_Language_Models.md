# WorldValuesBench：为语言模型量身打造的大规模多文化价值意识基准数据集

发布时间：2024年04月24日

`LLM应用` `计算机科学` `社会科学`

> WorldValuesBench: A Large-Scale Benchmark Dataset for Multi-Cultural Value Awareness of Language Models

# 摘要

> 认识多元文化中的人文价值对于语言模型（LMs）生成安全且个性化的回复极为关键。但目前对LMs在这方面的认知研究尚显不足，主要原因在于计算机科学界难以获取大规模的、关于多元文化价值的真实世界数据。本文介绍了WorldValuesBench，这是一个覆盖全球、大规模的基准数据集，专门用于预测多文化价值的任务。该任务要求模型基于人口统计学背景，对价值问题给出评分性回答。数据集基于著名的社会科学项目——世界价值观调查（WVS），该项目已收集了来自全球94,728名参与者对数百个价值问题的回答。我们从WVS的数据中构建了超过2000万个“（人口统计属性，价值问题）→答案”的实例。通过案例研究，我们发现即使是先进的开放和闭源模型，面对这一任务也面临挑战。例如，Alpaca-7B、Vicuna-7B-v1.5、Mixtral-8x7B-Instruct-v0.1和GPT-3.5 Turbo在分别只有11.1%、25.0%、72.2%和75.0%的问题上，才能达到与人类答案分布的Wasserstein 1-距离小于0.2。WorldValuesBench的推出为探索LMs在多元文化价值认知方面的限制和可能性提供了新的研究方向。

> The awareness of multi-cultural human values is critical to the ability of language models (LMs) to generate safe and personalized responses. However, this awareness of LMs has been insufficiently studied, since the computer science community lacks access to the large-scale real-world data about multi-cultural values. In this paper, we present WorldValuesBench, a globally diverse, large-scale benchmark dataset for the multi-cultural value prediction task, which requires a model to generate a rating response to a value question based on demographic contexts. Our dataset is derived from an influential social science project, World Values Survey (WVS), that has collected answers to hundreds of value questions (e.g., social, economic, ethical) from 94,728 participants worldwide. We have constructed more than 20 million examples of the type "(demographic attributes, value question) $\rightarrow$ answer" from the WVS responses. We perform a case study using our dataset and show that the task is challenging for strong open and closed-source models. On merely $11.1\%$, $25.0\%$, $72.2\%$, and $75.0\%$ of the questions, Alpaca-7B, Vicuna-7B-v1.5, Mixtral-8x7B-Instruct-v0.1, and GPT-3.5 Turbo can respectively achieve $<0.2$ Wasserstein 1-distance from the human normalized answer distributions. WorldValuesBench opens up new research avenues in studying limitations and opportunities in multi-cultural value awareness of LMs.

[Arxiv](https://arxiv.org/abs/2404.16308)