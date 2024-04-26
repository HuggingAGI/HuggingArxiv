# WorldValuesBench：一个旨在衡量语言模型对多元文化价值认知的大型基准数据集

发布时间：2024年04月24日

`LLM应用` `人工智能` `跨文化交流`

> WorldValuesBench: A Large-Scale Benchmark Dataset for Multi-Cultural Value Awareness of Language Models

# 摘要

> 认识多文化人类价值观对于语言模型生成安全且个性化的回应极为关键。但对语言模型在这方面的认知研究尚显不足，主要原因在于计算机科学界难以获取大规模的多文化价值观现实世界数据。本文提出了WorldValuesBench，这是一个涵盖全球多样性、大规模的基准数据集，旨在预测多文化价值，要求模型能够根据人口统计背景对价值问题给出评分反馈。该数据集基于著名的社会科学项目——世界价值观调查（WVS），该项目已搜集了来自全球94,728名受访者对数百个价值问题的回答。我们据此构建了超过2000万个“（人口统计属性，价值问题）→答案”的样本。通过案例研究，我们发现即使是先进的开源和闭源模型，面对这一任务也面临挑战。Alpaca-7B、Vicuna-7B-v1.5、Mixtral-8x7B-Instruct-v0.1和GPT-3.5 Turbo在分别只有11.1%、25.0%、72.2%和75.0%的问题上，才能达到与人类答案分布的Wasserstein 1-距离小于0.2。WorldValuesBench的推出为探索语言模型在多文化价值认知方面的限制和潜力提供了新的研究路径。

> The awareness of multi-cultural human values is critical to the ability of language models (LMs) to generate safe and personalized responses. However, this awareness of LMs has been insufficiently studied, since the computer science community lacks access to the large-scale real-world data about multi-cultural values. In this paper, we present WorldValuesBench, a globally diverse, large-scale benchmark dataset for the multi-cultural value prediction task, which requires a model to generate a rating response to a value question based on demographic contexts. Our dataset is derived from an influential social science project, World Values Survey (WVS), that has collected answers to hundreds of value questions (e.g., social, economic, ethical) from 94,728 participants worldwide. We have constructed more than 20 million examples of the type "(demographic attributes, value question) $\rightarrow$ answer" from the WVS responses. We perform a case study using our dataset and show that the task is challenging for strong open and closed-source models. On merely $11.1\%$, $25.0\%$, $72.2\%$, and $75.0\%$ of the questions, Alpaca-7B, Vicuna-7B-v1.5, Mixtral-8x7B-Instruct-v0.1, and GPT-3.5 Turbo can respectively achieve $<0.2$ Wasserstein 1-distance from the human normalized answer distributions. WorldValuesBench opens up new research avenues in studying limitations and opportunities in multi-cultural value awareness of LMs.

[Arxiv](https://arxiv.org/abs/2404.16308)