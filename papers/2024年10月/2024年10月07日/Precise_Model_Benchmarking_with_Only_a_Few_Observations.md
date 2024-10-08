# 少量观察也能实现精准模型基准测试

发布时间：2024年10月07日

`LLM理论` `数据分析` `机器学习`

> Precise Model Benchmarking with Only a Few Observations

# 摘要

> 如何精准评估大型语言模型（LLM）在特定主题问题上的准确性？传统方法可能因样本量小而波动大，而依赖其他主题的合成回归又可能偏差过大。我们提出一种简便有效的经验贝叶斯（EB）估计法，平衡各子组的直接与回归估计，显著提升评估精度。实验证明，EB法在多个数据集上均优于传统方法，大幅降低误差，且置信区间更窄、覆盖更准。此外，对表格和视觉数据的实验也验证了EB法的优越性。

> How can we precisely estimate a large language model's (LLM) accuracy on questions belonging to a specific topic within a larger question-answering dataset? The standard direct estimator, which averages the model's accuracy on the questions in each subgroup, may exhibit high variance for subgroups (topics) with small sample sizes. Synthetic regression modeling, which leverages the model's accuracy on questions about other topics, may yield biased estimates that are too unreliable for large subgroups. We prescribe a simple yet effective solution: an empirical Bayes (EB) estimator that balances direct and regression estimates for each subgroup separately, improving the precision of subgroup-level estimates of model performance. Our experiments on multiple datasets show that this approach consistently provides more precise estimates of the LLM performance compared to the direct and regression approaches, achieving substantial reductions in the mean squared error. Confidence intervals for EB estimates also have near-nominal coverage and are narrower compared to those for the direct estimator. Additional experiments on tabular and vision data validate the benefits of this EB approach.

[Arxiv](https://arxiv.org/abs/2410.05222)