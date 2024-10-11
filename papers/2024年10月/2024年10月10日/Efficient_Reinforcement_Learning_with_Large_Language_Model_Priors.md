# 利用大型语言模型先验实现高效强化学习

发布时间：2024年10月10日

`LLM应用` `人工智能`

> Efficient Reinforcement Learning with Large Language Model Priors

# 摘要

> 在顺序决策任务中，尽管强化学习和启发式搜索在某些情况下取得了进展，但它们往往需要大量探索，并且在跨环境泛化方面存在挑战。相比之下，大型语言模型（LLM）凭借其丰富的领域知识，成为了解决复杂任务的强大工具。我们提出将LLM视为先验动作分布，并通过贝叶斯推理将其融入RL框架，利用变分推理和直接后验采样。这种方法不仅简化了先验知识在RL中的应用，还显著提升了样本效率，例如在离线学习中，所需样本数量减少了90%以上。

> In sequential decision-making (SDM) tasks, methods like reinforcement learning (RL) and heuristic search have made notable advances in specific cases. However, they often require extensive exploration and face challenges in generalizing across diverse environments due to their limited grasp of the underlying decision dynamics. In contrast, large language models (LLMs) have recently emerged as powerful general-purpose tools, due to their capacity to maintain vast amounts of domain-specific knowledge. To harness this rich prior knowledge for efficiently solving complex SDM tasks, we propose treating LLMs as prior action distributions and integrating them into RL frameworks through Bayesian inference methods, making use of variational inference and direct posterior sampling. The proposed approaches facilitate the seamless incorporation of fixed LLM priors into both policy-based and value-based RL frameworks. Our experiments show that incorporating LLM-based action priors significantly reduces exploration and optimization complexity, substantially improving sample efficiency compared to traditional RL techniques, e.g., using LLM priors decreases the number of required samples by over 90% in offline learning scenarios.

[Arxiv](https://arxiv.org/abs/2410.07927)