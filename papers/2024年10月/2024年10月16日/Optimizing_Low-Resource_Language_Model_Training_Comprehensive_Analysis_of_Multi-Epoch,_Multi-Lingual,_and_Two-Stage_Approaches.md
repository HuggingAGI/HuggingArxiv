# 优化低资源语言模型训练：深入探讨多时期、多语言及两阶段策略的综合分析

发布时间：2024年10月16日

`LLM理论` `语言学` `计算语言学`

> Optimizing Low-Resource Language Model Training: Comprehensive Analysis of Multi-Epoch, Multi-Lingual, and Two-Stage Approaches

# 摘要

> 本文探讨了如何优化低资源语言 LLM 的训练设置。现有方法虽采用多时期、多语言和两阶段训练，但最佳超参数组合仍不明朗。我们通过全面实验发现：(1) 目标语言语料库减少时，最佳训练方法从单语言单阶段转向多语言两阶段，计算预算成关键；(2) 最佳模型规模稳定，可沿用单语言训练的计算最优规模；(3) 最佳时期数可从小规模实验外推。此外，单阶段训练中，目标语言验证损失与语料比例呈幂律关系，且指数与数据量、模型规模和语言对无关。

> In this paper, we address the challenge of optimizing training setups for Large Language Models (LLMs) of low-resource language with a limited amount of corpus. Existing works adopt multi-epoch, multi-lingual, and two-stage training to utilize the limited target language corpus efficiently. However, there is still a lack of understanding about the optimal hyperparameter setups for combining these three approaches to train LLMs. We exhaustively explore training setups for low-resource language LLM, combining these three approaches, and found the following insights for efficiently reducing the cost of hyperparameter search: (1) As the amount of target language corpus decreases, the optimal training approach shifts from monolingual single-stage training to multi-lingual two-stage training at a compute budget dependent threshold. (2) The optimal model scale remains stable regardless of the amount of target language corpus, allowing the use of the compute-optimal scale of monolingual training. (3) The optimal number of epochs can be extrapolated from smaller-scale experiments to larger scale using our proposed model. Also, we provide evidence that, in single-stage training, the target language validation loss follows a power law with respect to the target language ratio, with an exponent independent of the amount of data, model scale, and language pair.

[Arxiv](https://arxiv.org/abs/2410.12325)