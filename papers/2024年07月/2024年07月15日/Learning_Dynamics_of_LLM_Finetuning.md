# LLM 微调的学习机制

发布时间：2024年07月15日

`LLM理论` `人工智能`

> Learning Dynamics of LLM Finetuning

# 摘要

> 学习动态揭示了特定训练样本如何影响模型对其他样本的预测，是理解深度学习系统的关键。我们通过分析微调过程中不同响应间的逐步分解和累积影响，深入探讨了大型语言模型的学习动态。这一框架为指令调整和偏好调整算法的训练提供了统一解释，不仅阐明了这些方法的优势来源，还启发了一种简单高效的方法来进一步提升对齐性能。实验代码已公开在 https://github.com/Joshua-Ren/Learning_dynamics_LLM。

> Learning dynamics, which describes how the learning of specific training examples influences the model's prediction of other examples, give us a powerful tool for understanding the behavior of deep learning systems. We study the learning dynamics of large language models during finetuning, by analyzing the step-wise decomposition and accumulated influence among different responses. Our framework allows a uniform interpretation of many interesting observations about the training of popular algorithms for both instruction tuning and preference tuning. The analysis not only explains where the benefits of these methods come from but also inspires a simple, effective method to further improve the alignment performance. Code for experiments is available at https://github.com/Joshua-Ren/Learning_dynamics_LLM.

[Arxiv](https://arxiv.org/abs/2407.10490)