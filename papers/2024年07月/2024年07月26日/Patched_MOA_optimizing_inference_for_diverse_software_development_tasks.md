# Patched MOA 旨在为各类软件开发任务提供优化的推理方案。

发布时间：2024年07月26日

`LLM应用` `软件开发` `人工智能`

> Patched MOA: optimizing inference for diverse software development tasks

# 摘要

> 本文介绍的 Patched MOA 技术，通过优化推理过程，显著提升了大型语言模型在软件开发任务中的表现。我们对比了三种优化算法，发现 Patched MOA 能让小型模型在性能上超越大型、高成本模型。特别是在 Arena-Hard-Auto 测试中，gpt-4o-mini 模型性能提升了 15.52%，以更低成本胜过了 gpt-4-turbo。此外，Patched MOA 在多种软件开发流程中均展现了稳定的性能提升。该方法不仅模型无关、用户透明，还能无缝融入现有 LLM 系统，为 LLM 优化领域提供了一种高效且经济的性能提升方案。

> This paper introduces Patched MOA (Mixture of Agents), an inference optimization technique that significantly enhances the performance of large language models (LLMs) across diverse software development tasks. We evaluate three inference optimization algorithms - Best of N, Mixture of Agents, and Monte Carlo Tree Search and demonstrate that Patched MOA can boost the performance of smaller models to surpass that of larger, more expensive models. Notably, our approach improves the gpt-4o-mini model's performance on the Arena-Hard-Auto benchmark by 15.52%, outperforming gpt-4-turbo at a fraction of the cost. We also apply Patched MOA to various software development workflows, showing consistent improvements in task completion rates. Our method is model-agnostic, transparent to end-users, and can be easily integrated into existing LLM pipelines. This work contributes to the growing field of LLM optimization, offering a cost-effective solution for enhancing model performance without the need for fine-tuning or larger models.

[Arxiv](https://arxiv.org/abs/2407.18521)