# TIS-DPO：一种基于估计权重，通过令牌级重要性采样实现直接偏好优化的方法

发布时间：2024年10月06日

`LLM理论` `人工智能`

> TIS-DPO: Token-level Importance Sampling for Direct Preference Optimization With Estimated Weights

# 摘要

> 直接偏好优化 (DPO) 因其简便高效，广泛应用于大型语言模型 (LLM) 的偏好对齐。然而，DPO 将整个响应视为单一臂，忽略了令牌间的重要性差异，这可能降低优化效率，难以达到最佳效果。我们提出，DPO 的最佳数据应使获胜和失败响应中的每个令牌具有相等预期奖励，但实践中难以实现。因此，我们建议使用原始数据集进行重要性采样，并提出 TIS-DPO 目标，根据令牌奖励分配权重。我们借鉴先前研究，通过对比 LLM 的预测概率差异估计令牌重要性。我们探索了三种构建对比 LLM 的方法，实验证明 TIS-DPO 在无害性、有用性对齐及摘要任务上表现优异。我们还通过可视化展示了其识别关键令牌的能力。

> Direct Preference Optimization (DPO) has been widely adopted for preference alignment of Large Language Models (LLMs) due to its simplicity and effectiveness. However, DPO is derived as a bandit problem in which the whole response is treated as a single arm, ignoring the importance differences between tokens, which may affect optimization efficiency and make it difficult to achieve optimal results. In this work, we propose that the optimal data for DPO has equal expected rewards for each token in winning and losing responses, as there is no difference in token importance. However, since the optimal dataset is unavailable in practice, we propose using the original dataset for importance sampling to achieve unbiased optimization. Accordingly, we propose a token-level importance sampling DPO objective named TIS-DPO that assigns importance weights to each token based on its reward. Inspired by previous works, we estimate the token importance weights using the difference in prediction probabilities from a pair of contrastive LLMs. We explore three methods to construct these contrastive LLMs: (1) guiding the original LLM with contrastive prompts, (2) training two separate LLMs using winning and losing responses, and (3) performing forward and reverse DPO training with winning and losing responses. Experiments show that TIS-DPO significantly outperforms various baseline methods on harmlessness and helpfulness alignment and summarization tasks. We also visualize the estimated weights, demonstrating their ability to identify key token positions.

[Arxiv](https://arxiv.org/abs/2410.04350)