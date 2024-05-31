# 在无奖励环境下的强化学习中，优化群体的鲁棒偏好

发布时间：2024年05月30日

`LLM应用

这篇论文探讨了如何通过一种名为“群体稳健偏好优化（GRPO）”的方法来微调大型语言模型（LLMs），以更好地适应不同群体的偏好。这种方法特别关注提升表现不佳的群体的性能，并通过动态调整群体权重来实现这一目标。论文中的实验结果表明，使用GRPO微调的LLMs在多样群体数据上表现出色，显著提升了最差群体的性能，减少了群体间的性能差异，并提高了整体准确性。因此，这篇论文属于“LLM应用”类别，因为它专注于实际应用中的模型微调和性能优化。` `人工智能` `机器学习`

> Group Robust Preference Optimization in Reward-free RLHF

# 摘要

> 为了使大型语言模型（LLMs）更好地适应特定任务，通常需要通过人类反馈强化学习（RLHF）在偏好数据上进行微调。然而，传统的RLHF方法采用“一刀切”策略，忽视了不同群体的独特需求，导致性能不够稳健。为此，我们提出了一种创新的群体稳健偏好优化（GRPO）方法，旨在使LLMs更贴合各群体的偏好。GRPO基于直接偏好优化技术，但特别关注于提升最差群体的性能，通过动态调整群体权重，优先改善表现不佳的群体。理论分析表明，GRPO在特定策略类中具有良好的收敛性。实验结果显示，采用GRPO微调的LLMs在多样群体数据上表现出色，显著提升了最差群体的性能，减少了群体间的性能差异，并提高了整体准确性。

> Adapting large language models (LLMs) for specific tasks usually involves fine-tuning through reinforcement learning with human feedback (RLHF) on preference data. While these data often come from diverse labelers' groups (e.g., different demographics, ethnicities, company teams, etc.), traditional RLHF approaches adopt a "one-size-fits-all" approach, i.e., they indiscriminately assume and optimize a single preference model, thus not being robust to unique characteristics and needs of the various groups. To address this limitation, we propose a novel Group Robust Preference Optimization (GRPO) method to align LLMs to individual groups' preferences robustly. Our approach builds upon reward-free direct preference optimization methods, but unlike previous approaches, it seeks a robust policy which maximizes the worst-case group performance. To achieve this, GRPO adaptively and sequentially weights the importance of different groups, prioritizing groups with worse cumulative loss. We theoretically study the feasibility of GRPO and analyze its convergence for the log-linear policy class. By fine-tuning LLMs with GRPO using diverse group-based global opinion data, we significantly improved performance for the worst-performing groups, reduced loss imbalances across groups, and improved probability accuracies compared to non-robust baselines.

[Arxiv](https://arxiv.org/abs/2405.20304)