# 任务导向模型微调中的数据精选

发布时间：2024年10月15日

`LLM应用` `机器学习` `数据科学`

> Data Selection for Task-Specific Model Finetuning

# 摘要

> 在现代机器学习中，针对特定任务微调基础模型是一个新兴趋势。微调效果很大程度上取决于训练数据的选择。我们提出了一种框架，通过目标任务中的少量代表性示例来指导数据选择。我们将数据选择问题转化为优化任务，利用最优传输理论来衡量数据与目标分布的差异。同时，我们引入正则化项以确保数据多样性，并采用核密度估计来减少数据重复。通过与最近邻搜索结合，我们设计了高效的算法来求解最优数据集。实验表明，使用我们方法选择的1%数据进行指令微调，效果通常优于全数据集，且在F1分数上平均领先基线方法1.5分。

> Finetuning foundation models for specific tasks is an emerging paradigm in modern machine learning. The efficacy of task-specific finetuning largely depends on the selection of appropriate training data. We present a framework to select data for task-specific model finetuning, guided by a small but representative set of examples from the target task. To do so, we formulate data selection for task-specific finetuning as an optimization problem with a distribution alignment loss based on optimal transport to capture the discrepancy between the selected data and the target distribution. In addition, we add a regularizer to encourage the diversity of the selected data and incorporate kernel density estimation into the regularizer to reduce the negative effects of near-duplicates among the candidate data. We connect our optimization problem to nearest neighbor search and design efficient algorithms to compute the optimal solution based on approximate nearest neighbor search techniques. We evaluate our method on data selection for both continued pretraining and instruction tuning of language models. We show that instruction tuning using data selected by our method with a 1% selection ratio often outperforms using the full dataset and beats the baseline selection methods by 1.5 points in F1 score on average.

[Arxiv](https://arxiv.org/abs/2410.11303)