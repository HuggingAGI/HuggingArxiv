# 通过在线策略与主动学习构建经济高效的代理奖励模型

发布时间：2024年07月02日

`LLM应用` `人工智能` `机器学习`

> Cost-Effective Proxy Reward Model Construction with On-Policy and Active Learning

# 摘要

> 人类反馈强化学习（RLHF）在大型语言模型中应用广泛，但其效果受限于人类偏好数据量。传统方法依赖离线数据集，而新方法转向在线模式，利用少量标记数据和大量未标记提示，通过自我生成响应和高品质反馈迭代构建新数据。然而，现有在线算法在策略更新时仍依赖给定反馈预言机进行偏好标记，导致高昂的专家查询成本。我们率先探索了成本效益高的代理奖励预言机构建策略，以在有限数据和预算下进行偏好或奖励标记。我们的创新包括：策略内查询避免数据问题，以及主动学习选择关键数据。通过这些方法，我们用最少专家数据训练评估模型，有效标记九倍偏好对，用于RLHF训练。例如，使用DPO的模型在多个测试中平均提升约1%，仅消耗1.7K查询成本。我们的方法与其他专家查询策略正交，有望进一步降低成本。

> Reinforcement learning with human feedback (RLHF), as a widely adopted approach in current large language model pipelines, is \textit{bottlenecked by the size of human preference data}. While traditional methods rely on offline preference dataset constructions, recent approaches have shifted towards online settings, where a learner uses a small amount of labeled seed data and a large pool of unlabeled prompts to iteratively construct new preference data through self-generated responses and high-quality reward/preference feedback. However, most current online algorithms still focus on preference labeling during policy model updating with given feedback oracles, which incurs significant expert query costs. \textit{We are the first to explore cost-effective proxy reward oracles construction strategies for further labeling preferences or rewards with extremely limited labeled data and expert query budgets}. Our approach introduces two key innovations: (1) on-policy query to avoid OOD and imbalance issues in seed data, and (2) active learning to select the most informative data for preference queries. Using these methods, we train a evaluation model with minimal expert-labeled data, which then effectively labels nine times more preference pairs for further RLHF training. For instance, our model using Direct Preference Optimization (DPO) gains around over 1% average improvement on AlpacaEval2, MMLU-5shot and MMLU-0shot, with only 1.7K query cost. Our methodology is orthogonal to other direct expert query-based strategies and therefore might be integrated with them to further reduce query costs.

[Arxiv](https://arxiv.org/abs/2407.02119)