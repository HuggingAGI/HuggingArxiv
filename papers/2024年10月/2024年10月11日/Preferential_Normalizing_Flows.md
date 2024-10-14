# 偏好归一化流

发布时间：2024年10月11日

`LLM理论` `人工智能` `数据科学`

> Preferential Normalizing Flows

# 摘要

> 从专家的噪声判断中提取高维概率分布极具挑战，但在先验引出和奖励建模等应用中极为有用。我们提出一种基于偏好问题（如比较或排序）的归一化流方法，来引出专家的信念密度。理论上，这能引出任意灵活的密度，但实践中流估计易受概率质量崩溃或发散的影响。为此，我们引入了一种新的功能先验，基于决策理论，并实证表明信念密度可作为函数空间的最大后验估计。我们通过引出模拟专家的多变量信念密度，包括大型语言模型在真实数据集上的先验信念，展示了该方法的有效性。

> Eliciting a high-dimensional probability distribution from an expert via noisy judgments is notoriously challenging, yet useful for many applications, such as prior elicitation and reward modeling. We introduce a method for eliciting the expert's belief density as a normalizing flow based solely on preferential questions such as comparing or ranking alternatives. This allows eliciting in principle arbitrarily flexible densities, but flow estimation is susceptible to the challenge of collapsing or diverging probability mass that makes it difficult in practice. We tackle this problem by introducing a novel functional prior for the flow, motivated by a decision-theoretic argument, and show empirically that the belief density can be inferred as the function-space maximum a posteriori estimate. We demonstrate our method by eliciting multivariate belief densities of simulated experts, including the prior belief of a general-purpose large language model over a real-world dataset.

[Arxiv](https://arxiv.org/abs/2410.08710)