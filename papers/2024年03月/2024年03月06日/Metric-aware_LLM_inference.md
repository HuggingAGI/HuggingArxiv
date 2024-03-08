# [面向指标的 LLM 推理技术](https://arxiv.org/abs/2403.04182)

发布时间：2024年03月06日

`LLM应用`

> Metric-aware LLM inference

> LLMs在各类NLP任务中表现出色，其输出往往依赖于模型底层分布的自回归采样。然而，这种通用推断策略在某些任务及关联评价指标下并不理想。为此，我们提出了一种“面向度量的LLM推断”新思路——运用决策理论，在推理阶段直接优化特定度量标准。实验证明，该方法在多个学术基准测试以及公开模型上均超越了原有基线性能。

> Large language models (LLMs) have demonstrated strong results on a range of NLP tasks. Typically, outputs are obtained via autoregressive sampling from the LLM's underlying distribution. We show that this inference strategy can be suboptimal for a range of tasks and associated evaluation metrics. As a remedy, we propose metric aware LLM inference: a decision theoretic approach optimizing for custom metrics at inference time. We report improvements over baselines on academic benchmarks and publicly available models.