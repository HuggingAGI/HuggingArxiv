# 大型模型在视觉-语言任务中的表现，我们能否精准预测？

发布时间：2024年10月13日

`LLM应用` `计算机视觉` `机器学习`

> Can We Predict Performance of Large Models across Vision-Language Tasks?

# 摘要

> 评估大型视觉-语言模型 (LVLMs) 成本高昂，涉及高计算成本和多样任务。好消息是，若已有观察到的性能分数，我们或许能推断未知分数。本研究提出新框架，基于其他 LVLMs 或任务的观察分数预测未知性能。首先，将性能预测视为矩阵补全任务，构建稀疏性能矩阵 $\boldsymbol{R}$，其中 $R_{mn}$ 表示第 $m$ 模型在第 $n$ 数据集的分数。通过概率矩阵分解 (PMF) 结合马尔可夫链蒙特卡罗 (MCMC)，完成矩阵，预测未知分数。同时，基于 MCMC 估计预测不确定性。从业者可优先评估高不确定性任务，快速减少预测误差。此外，针对稀疏数据场景，我们提出多项改进以增强 PMF 效果。实验中，评估 108 个 LVLMs 在 36 基准的 176 数据集上，验证框架。结果显示，PMF 预测准确，不确定性估计可靠，稀疏数据处理有效。

> Evaluating large vision-language models (LVLMs) is very expensive, due to the high computational costs and the wide variety of tasks. The good news is that if we already have some observed performance scores, we may be able to infer unknown ones. In this study, we propose a new framework for predicting unknown performance scores based on observed ones from other LVLMs or tasks. We first formulate the performance prediction as a matrix completion task. Specifically, we construct a sparse performance matrix $\boldsymbol{R}$, where each entry $R_{mn}$ represents the performance score of the $m$-th model on the $n$-th dataset. By applying probabilistic matrix factorization (PMF) with Markov chain Monte Carlo (MCMC), we can complete the performance matrix, that is, predict unknown scores. Additionally, we estimate the uncertainty of performance prediction based on MCMC. Practitioners can evaluate their models on untested tasks with higher uncertainty first, quickly reducing errors in performance prediction. We further introduce several improvements to enhance PMF for scenarios with sparse observed performance scores. In experiments, we systematically evaluate 108 LVLMs on 176 datasets from 36 benchmarks, constructing training and testing sets for validating our framework. Our experiments demonstrate the accuracy of PMF in predicting unknown scores, the reliability of uncertainty estimates in ordering evaluations, and the effectiveness of our enhancements for handling sparse data.

[Arxiv](https://arxiv.org/abs/2410.10112)