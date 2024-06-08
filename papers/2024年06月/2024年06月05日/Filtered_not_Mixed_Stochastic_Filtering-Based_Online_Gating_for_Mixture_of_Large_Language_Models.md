# 非混合过滤：采用随机过滤技术的在线门控机制，用于混合大型语言模型的优化

发布时间：2024年06月05日

`LLM应用

理由：这篇论文介绍了一种新的机制MoE-F，用于动态调整多个预训练的大型语言模型（LLMs）的权重，以进行在线时间序列预测。这种机制特别关注于实时性能和预测下一步最佳的LLM组合，这在实际应用中非常有用，尤其是在金融市场的移动任务中。因此，这篇论文更偏向于LLM的应用领域，而不是理论研究或Agent、RAG相关的研究。` `时间序列预测`

> Filtered not Mixed: Stochastic Filtering-Based Online Gating for Mixture of Large Language Models

# 摘要

> 我们提出了一种名为MoE-F的新机制，它通过在每个时间点动态调整权重，巧妙地将$N$个预训练的大型语言模型（LLMs）融合，用于在线时间序列预测。该机制不仅考虑了每个LLM的实时表现，还预测了下一步最佳的LLM组合。与传统的静态混合专家方法不同，MoE-F采用了时间自适应的随机滤波技术，通过将专家选择视为一个隐马尔可夫模型，利用Wohman-Shiryaev滤波器进行优化。首先，为每个LLM构建一个并行滤波器，每个滤波器根据其信息提出最佳组合。然后，这些滤波器的输出被汇总，以优化一个闭合形式的损失下界，从而形成我们的集成预测器。我们的主要贡献包括：(I) 可即插即用的MoE-F滤波算法，(II) 基于滤波的门控算法的理论最优性保证，以及(III) 在真实金融市场的移动任务上，使用顶尖的基线和MoE LLMs进行的实证评估，结果显示MoE-F相比次优的单个LLM专家，F1度量提升了17%绝对值和48.5%相对值。

> We propose MoE-F -- a formalised mechanism for combining $N$ pre-trained expert Large Language Models (LLMs) in online time-series prediction tasks by adaptively forecasting the best weighting of LLM predictions at every time step. Our mechanism leverages the conditional information in each expert's running performance to forecast the best combination of LLMs for predicting the time series in its next step. Diverging from static (learned) Mixture of Experts (MoE) methods, MoE-F employs time-adaptive stochastic filtering techniques to combine experts. By framing the expert selection problem as a finite state-space, continuous-time Hidden Markov model (HMM), we can leverage the Wohman-Shiryaev filter. Our approach first constructs $N$ parallel filters corresponding to each of the $N$ individual LLMs. Each filter proposes its best combination of LLMs, given the information that they have access to. Subsequently, the $N$ filter outputs are aggregated to optimize a lower bound for the loss of the aggregated LLMs, which can be optimized in closed-form, thus generating our ensemble predictor. Our contributions here are: (I) the MoE-F algorithm -- deployable as a plug-and-play filtering harness, (II) theoretical optimality guarantees of the proposed filtering-based gating algorithm, and (III) empirical evaluation and ablative results using state of the art foundational and MoE LLMs on a real-world Financial Market Movement task where MoE-F attains a remarkable 17% absolute and 48.5% relative F1 measure improvement over the next best performing individual LLM expert.

![非混合过滤：采用随机过滤技术的在线门控机制，用于混合大型语言模型的优化](../../../paper_images/2406.02969/x1.png)

![非混合过滤：采用随机过滤技术的在线门控机制，用于混合大型语言模型的优化](../../../paper_images/2406.02969/x2.png)

![非混合过滤：采用随机过滤技术的在线门控机制，用于混合大型语言模型的优化](../../../paper_images/2406.02969/x3.png)

![非混合过滤：采用随机过滤技术的在线门控机制，用于混合大型语言模型的优化](../../../paper_images/2406.02969/x4.png)

![非混合过滤：采用随机过滤技术的在线门控机制，用于混合大型语言模型的优化](../../../paper_images/2406.02969/x5.png)

![非混合过滤：采用随机过滤技术的在线门控机制，用于混合大型语言模型的优化](../../../paper_images/2406.02969/x6.png)

![非混合过滤：采用随机过滤技术的在线门控机制，用于混合大型语言模型的优化](../../../paper_images/2406.02969/x7.png)

[Arxiv](https://arxiv.org/abs/2406.02969)