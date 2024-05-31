# 在无奖励强化学习中，优化群体的鲁棒偏好

发布时间：2024年05月30日

`LLM应用

这篇论文主要讨论了如何通过群体稳健偏好优化（GRPO）方法来微调大型语言模型（LLMs），以更好地适应不同群体的偏好。这种方法特别关注于提高模型对表现较差群体的适应性，并减少群体间的性能差异。因此，这项工作属于LLM应用类别，因为它专注于改进LLM在特定任务和不同群体中的应用性能。` `人工智能` `语言模型`

> Group Robust Preference Optimization in Reward-free RLHF

# 摘要

> 为了使大型语言模型（LLMs）更好地适应特定任务，通常需要通过人类反馈强化学习（RLHF）在偏好数据上进行微调。然而，传统RLHF方法采用“一刀切”策略，忽视了不同群体的独特需求。为此，我们提出了群体稳健偏好优化（GRPO）方法，旨在使LLMs更稳健地适应各群体的偏好。GRPO基于直接偏好优化，但专注于最大化最差群体的表现，通过自适应调整群体权重来优先改善表现较差的群体。理论分析表明，GRPO在对数线性策略类中是可行的，并且能够收敛。实验结果显示，使用GRPO微调的LLMs在多样群体数据上表现更佳，显著提升了最差群体的性能，减少了群体间的性能差异，并提高了整体准确性。

> Adapting large language models (LLMs) for specific tasks usually involves fine-tuning through reinforcement learning with human feedback (RLHF) on preference data. While these data often come from diverse labelers' groups (e.g., different demographics, ethnicities, company teams, etc.), traditional RLHF approaches adopt a "one-size-fits-all" approach, i.e., they indiscriminately assume and optimize a single preference model, thus not being robust to unique characteristics and needs of the various groups. To address this limitation, we propose a novel Group Robust Preference Optimization (GRPO) method to align LLMs to individual groups' preferences robustly. Our approach builds upon reward-free direct preference optimization methods, but unlike previous approaches, it seeks a robust policy which maximizes the worst-case group performance. To achieve this, GRPO adaptively and sequentially weights the importance of different groups, prioritizing groups with worse cumulative loss. We theoretically study the feasibility of GRPO and analyze its convergence for the log-linear policy class. By fine-tuning LLMs with GRPO using diverse group-based global opinion data, we significantly improved performance for the worst-performing groups, reduced loss imbalances across groups, and improved probability accuracies compared to non-robust baselines.

[Arxiv](https://arxiv.org/abs/2405.20304)