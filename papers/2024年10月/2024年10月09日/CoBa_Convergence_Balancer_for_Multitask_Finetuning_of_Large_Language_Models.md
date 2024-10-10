# CoBa：为大型语言模型的多任务微调提供收敛平衡

发布时间：2024年10月09日

`LLM应用` `人工智能` `机器学习`

> CoBa: Convergence Balancer for Multitask Finetuning of Large Language Models

# 摘要

> 多任务学习 (MTL) 通过提供一个在多个任务中表现更佳且更具泛化能力的单一模型，为大型语言模型 (LLM) 的微调提供了高效资源的选择。然而，现有的 MTL 策略在计算量或任务同步收敛方面往往表现不佳。本文提出的 CoBa 方法，通过动态调整任务权重，确保所有任务的验证损失均匀收敛，同时最小化计算开销。实验结果显示，CoBa 不仅平衡了任务改进，还将 LLM 的性能提升了高达 13%。代码已开源，详见 https://github.com/codefuse-ai/MFTCoder。

> Multi-task learning (MTL) benefits the fine-tuning of large language models (LLMs) by providing a single model with improved performance and generalization ability across tasks, presenting a resource-efficient alternative to developing separate models for each task. Yet, existing MTL strategies for LLMs often fall short by either being computationally intensive or failing to ensure simultaneous task convergence. This paper presents CoBa, a new MTL approach designed to effectively manage task convergence balance with minimal computational overhead. Utilizing Relative Convergence Scores (RCS), Absolute Convergence Scores (ACS), and a Divergence Factor (DF), CoBa dynamically adjusts task weights during the training process, ensuring that the validation loss of all tasks progress towards convergence at an even pace while mitigating the issue of individual task divergence. The results of our experiments involving three disparate datasets underscore that this approach not only fosters equilibrium in task improvement but enhances the LLMs' performance by up to 13% relative to the second-best baselines. Code is open-sourced at https://github.com/codefuse-ai/MFTCoder.

[Arxiv](https://arxiv.org/abs/2410.06741)