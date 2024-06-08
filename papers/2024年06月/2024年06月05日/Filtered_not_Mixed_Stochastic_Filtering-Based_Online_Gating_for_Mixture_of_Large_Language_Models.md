# 随机过滤而非混合：大型语言模型的在线门控机制

发布时间：2024年06月05日

`LLM应用

这篇论文介绍了一种创新的机制MoE-F，用于动态调整多个预训练大型语言模型(LLMs)的权重，以实现实时时间序列预测。该方法通过时间自适应滤波技术和隐马尔可夫模型框架，优化了集成模型的性能，并在金融市场变动预测任务中展示了显著的性能提升。这表明论文主要关注于LLM的实际应用，特别是在时间序列预测领域，因此应归类为LLM应用。` `金融市场` `时间序列预测`

> Filtered not Mixed: Stochastic Filtering-Based Online Gating for Mixture of Large Language Models

# 摘要

> 我们创新性地提出了MoE-F机制，它通过动态调整权重，将多个预训练的大型语言模型(LLMs)智慧融合，用于实时时间序列预测。不同于传统的静态混合专家方法，MoE-F运用时间自适应滤波技术，根据各模型实时表现调整组合策略。我们采用隐马尔可夫模型框架，借助Wohman-Shiryaev滤波器，为每个LLM构建并行滤波器，进而优化集成模型的损失下界，形成高效预测器。我们的成果包括：(I) 即插即用的MoE-F滤波算法，(II) 基于滤波的门控算法的理论最优性保证，以及(III) 在金融市场变动预测任务中，MoE-F相较于最佳单个LLM专家，实现了17%的绝对和48.5%的相对F1分数提升。

> We propose MoE-F -- a formalised mechanism for combining $N$ pre-trained expert Large Language Models (LLMs) in online time-series prediction tasks by adaptively forecasting the best weighting of LLM predictions at every time step. Our mechanism leverages the conditional information in each expert's running performance to forecast the best combination of LLMs for predicting the time series in its next step. Diverging from static (learned) Mixture of Experts (MoE) methods, MoE-F employs time-adaptive stochastic filtering techniques to combine experts. By framing the expert selection problem as a finite state-space, continuous-time Hidden Markov model (HMM), we can leverage the Wohman-Shiryaev filter. Our approach first constructs $N$ parallel filters corresponding to each of the $N$ individual LLMs. Each filter proposes its best combination of LLMs, given the information that they have access to. Subsequently, the $N$ filter outputs are aggregated to optimize a lower bound for the loss of the aggregated LLMs, which can be optimized in closed-form, thus generating our ensemble predictor. Our contributions here are: (I) the MoE-F algorithm -- deployable as a plug-and-play filtering harness, (II) theoretical optimality guarantees of the proposed filtering-based gating algorithm, and (III) empirical evaluation and ablative results using state of the art foundational and MoE LLMs on a real-world Financial Market Movement task where MoE-F attains a remarkable 17% absolute and 48.5% relative F1 measure improvement over the next best performing individual LLM expert.

![随机过滤而非混合：大型语言模型的在线门控机制](../../../paper_images/2406.02969/x1.png)

![随机过滤而非混合：大型语言模型的在线门控机制](../../../paper_images/2406.02969/x2.png)

![随机过滤而非混合：大型语言模型的在线门控机制](../../../paper_images/2406.02969/x3.png)

![随机过滤而非混合：大型语言模型的在线门控机制](../../../paper_images/2406.02969/x4.png)

![随机过滤而非混合：大型语言模型的在线门控机制](../../../paper_images/2406.02969/x5.png)

![随机过滤而非混合：大型语言模型的在线门控机制](../../../paper_images/2406.02969/x6.png)

![随机过滤而非混合：大型语言模型的在线门控机制](../../../paper_images/2406.02969/x7.png)

[Arxiv](https://arxiv.org/abs/2406.02969)