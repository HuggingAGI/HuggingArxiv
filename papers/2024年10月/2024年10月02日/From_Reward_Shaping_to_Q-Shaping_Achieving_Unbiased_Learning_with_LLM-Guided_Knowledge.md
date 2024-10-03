# 从奖励塑造到 Q-Shaping：借助 LLM 引导的知识，实现无偏学习

发布时间：2024年10月02日

`Agent` `人工智能`

> From Reward Shaping to Q-Shaping: Achieving Unbiased Learning with LLM-Guided Knowledge

# 摘要

> Q-shaping 通过直接调整 Q-values，不仅加速了代理训练，还显著提升了样本效率。在 20 个不同环境中，Q-shaping 的表现远超最佳基线，提升高达 16.87%，相较于基于 LLM 的奖励塑造方法，更是实现了 253.80% 的飞跃。这使得 Q-shaping 成为强化学习中传统奖励塑造的更优选择，既高效又无偏。

> Q-shaping is an extension of Q-value initialization and serves as an alternative to reward shaping for incorporating domain knowledge to accelerate agent training, thereby improving sample efficiency by directly shaping Q-values. This approach is both general and robust across diverse tasks, allowing for immediate impact assessment while guaranteeing optimality. We evaluated Q-shaping across 20 different environments using a large language model (LLM) as the heuristic provider. The results demonstrate that Q-shaping significantly enhances sample efficiency, achieving a \textbf{16.87\%} improvement over the best baseline in each environment and a \textbf{253.80\%} improvement compared to LLM-based reward shaping methods. These findings establish Q-shaping as a superior and unbiased alternative to conventional reward shaping in reinforcement learning.

[Arxiv](https://arxiv.org/abs/2410.01458)