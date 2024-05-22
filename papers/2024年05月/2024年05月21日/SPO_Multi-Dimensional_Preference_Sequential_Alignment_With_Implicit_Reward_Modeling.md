# SPO：隐式奖励建模下的多维偏好序列对齐

发布时间：2024年05月21日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLM）与人类偏好的对齐问题，并提出了一种新的优化策略——顺序偏好优化（SPO）。该研究不仅涉及理论分析，如损失函数的最优闭合形式和梯度分析，还通过实证研究验证了其方法的有效性。这些内容主要关注LLM的理论优化和性能提升，而非具体的应用场景或Agent的设计，因此更适合归类于LLM理论。` `人工智能`

> SPO: Multi-Dimensional Preference Sequential Alignment With Implicit Reward Modeling

# 摘要

> 构建强大且可靠的LLMs，关键在于与人类偏好精准对齐。现有方法或忽视人类偏好的多维性，或难以驾驭多重奖励模型的复杂性。为此，我们创新提出顺序偏好优化（SPO），一种逐次微调LLMs以契合人类多维偏好的策略。SPO摒弃了传统的奖励建模，直击要害，精准优化模型以捕捉人类偏好的细微差别。理论分析揭示了SPO策略与损失函数的最优闭合形式。梯度分析进一步阐释了SPO如何在微调过程中保持与先前优化维度的和谐对齐。实证研究横跨不同规模的LLMs及多样的评估数据集，结果清晰表明，SPO在多维度上成功对齐了LLMs，并显著超越了传统方法。

> Human preference alignment is critical in building powerful and reliable large language models (LLMs). However, current methods either ignore the multi-dimensionality of human preferences (e.g. helpfulness and harmlessness) or struggle with the complexity of managing multiple reward models. To address these issues, we propose Sequential Preference Optimization (SPO), a method that sequentially fine-tunes LLMs to align with multiple dimensions of human preferences. SPO avoids explicit reward modeling, directly optimizing the models to align with nuanced human preferences. We theoretically derive closed-form optimal SPO policy and loss function. Gradient analysis is conducted to show how SPO manages to fine-tune the LLMs while maintaining alignment on previously optimized dimensions. Empirical results on LLMs of different size and multiple evaluation datasets demonstrate that SPO successfully aligns LLMs across multiple dimensions of human preferences and significantly outperforms the baselines.

[Arxiv](https://arxiv.org/abs/2405.12739)