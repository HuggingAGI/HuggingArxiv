# 挖掘合成数据的最大潜力：随机矩阵理论的启示

发布时间：2024年10月11日

`LLM理论` `机器学习` `数据科学`

> Maximizing the Potential of Synthetic Data: Insights from Random Matrix Theory

# 摘要

> 合成数据虽受关注，但质量不佳会损害模型性能（如 Shumailov 2023 和 Seddik 2024 所示）。数据修剪，即基于评分函数（人或机器反馈）保留高质量数据，是一个潜在解决方案。Feng 2024 曾分析样本量增加时合成数据训练的模型。我们运用随机矩阵理论，在高维环境中研究真实与修剪合成数据混合训练的二元分类器性能。研究发现，合成数据在特定条件下能提升性能，关键在于生成模型质量与验证策略。此外，合成标签噪声呈现平滑相变，与以往无限样本下的急剧变化不同。实验验证了理论，涵盖玩具模型与大型语言模型。

> Synthetic data has gained attention for training large language models, but poor-quality data can harm performance (see, e.g., Shumailov et al. (2023); Seddik et al. (2024)). A potential solution is data pruning, which retains only high-quality data based on a score function (human or machine feedback). Previous work Feng et al. (2024) analyzed models trained on synthetic data as sample size increases. We extend this by using random matrix theory to derive the performance of a binary classifier trained on a mix of real and pruned synthetic data in a high dimensional setting. Our findings identify conditions where synthetic data could improve performance, focusing on the quality of the generative model and verification strategy. We also show a smooth phase transition in synthetic label noise, contrasting with prior sharp behavior in infinite sample limits. Experiments with toy models and large language models validate our theoretical results.

[Arxiv](https://arxiv.org/abs/2410.08942)