# 遗忘学习视作多任务优化：一种采用自适应学习率的归一化梯度差方法

发布时间：2024年10月29日

`LLM理论` `机器学习`

> Unlearning as multi-task optimization: A normalized gradient difference approach with an adaptive learning rate

# 摘要

> 机器遗忘学习已用于清除大型语言模型（LLMs）获取的无用知识。在本文中，我们从优化视角审视机器遗忘学习，将其视作一个正则化的多任务优化问题，其中一项任务优化遗忘目标，另一项优化模型性能。特别地，我们引入了归一化梯度差（NGDiff）算法，能更好地把控目标间的权衡，同时整合了一个全新的自动学习率调度器。我们进行了理论分析，并通过实验在 TOFU 和 MUSE 数据集上证实了 NGDiff 在前沿遗忘学习方法中的卓越性能，且训练稳定。

> Machine unlearning has been used to remove unwanted knowledge acquired by large language models (LLMs). In this paper, we examine machine unlearning from an optimization perspective, framing it as a regularized multi-task optimization problem, where one task optimizes a forgetting objective and another optimizes the model performance. In particular, we introduce a normalized gradient difference (NGDiff) algorithm, enabling us to have better control over the trade-off between the objectives, while integrating a new, automatic learning rate scheduler. We provide a theoretical analysis and empirically demonstrate the superior performance of NGDiff among state-of-the-art unlearning methods on the TOFU and MUSE datasets while exhibiting stable training.

[Arxiv](https://arxiv.org/abs/2410.22086)