# WorldValuesBench：为语言模型量身打造的大规模多文化价值意识基准数据集

发布时间：2024年04月24日

`LLM应用` `计算机科学` `多元文化价值观`

> WorldValuesBench: A Large-Scale Benchmark Dataset for Multi-Cultural Value Awareness of Language Models

# 摘要

> 语言模型（LMs）能否生成安全且个性化的回应，关键在于对多元文化价值观的认知。遗憾的是，这一领域对LMs的研究尚显不足，主要原因在于计算机科学界难以获取大规模的现实世界多元文化价值观数据。本文介绍了WorldValuesBench，这是一个涵盖全球多样性、用于多元文化价值预测任务的大规模基准数据集。该任务要求模型基于人口统计背景对价值问题给出评分回应。数据集基于著名的社会科学项目——世界价值观调查（WVS），该项目汇集了全球94,728名参与者对数百个价值问题的回答。我们从WVS的数据中构建了超过2000万个“（人口统计特征，价值问题）→答案”的样本。通过案例研究，我们发现即使是先进的开放和闭源模型，面对这一任务也显得力不从心。Alpaca-7B、Vicuna-7B-v1.5、Mixtral-8x7B-Instruct-v0.1和GPT-3.5 Turbo在分别只有11.1%、25.0%、72.2%和75.0%的问题上，才能达到与人类答案分布的Wasserstein 1距离小于0.2。WorldValuesBench的推出为探索LMs在多元文化价值认知方面的限制和机遇提供了新的研究路径。

> The awareness of multi-cultural human values is critical to the ability of language models (LMs) to generate safe and personalized responses. However, this awareness of LMs has been insufficiently studied, since the computer science community lacks access to the large-scale real-world data about multi-cultural values. In this paper, we present WorldValuesBench, a globally diverse, large-scale benchmark dataset for the multi-cultural value prediction task, which requires a model to generate a rating response to a value question based on demographic contexts. Our dataset is derived from an influential social science project, World Values Survey (WVS), that has collected answers to hundreds of value questions (e.g., social, economic, ethical) from 94,728 participants worldwide. We have constructed more than 20 million examples of the type "(demographic attributes, value question) $\rightarrow$ answer" from the WVS responses. We perform a case study using our dataset and show that the task is challenging for strong open and closed-source models. On merely $11.1\%$, $25.0\%$, $72.2\%$, and $75.0\%$ of the questions, Alpaca-7B, Vicuna-7B-v1.5, Mixtral-8x7B-Instruct-v0.1, and GPT-3.5 Turbo can respectively achieve $<0.2$ Wasserstein 1-distance from the human normalized answer distributions. WorldValuesBench opens up new research avenues in studying limitations and opportunities in multi-cultural value awareness of LMs.

[Arxiv](https://arxiv.org/abs/2404.16308)