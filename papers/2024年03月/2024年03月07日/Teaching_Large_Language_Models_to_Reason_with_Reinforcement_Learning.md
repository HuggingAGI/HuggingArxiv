# [运用强化学习策略，训练大型语言模型掌握推理技能](https://arxiv.org/abs/2403.04642)

发布时间：2024年03月07日

`Agent`

> Teaching Large Language Models to Reason with Reinforcement Learning

> RLHF 已成为引导LLM输出贴近人类偏好的主流手段。鉴于其成功实践，我们着眼于多种能根据反馈进行学习的算法（如专家迭代、近端策略优化\textbf{PPO}及基于回报条件的RL），以研究它们能否提升LLM推理效能。在这一过程中，我们不仅采用了启发式稀疏和密集奖励策略，并通过预先训练的奖励模型为LLM提供指导，还尝试了不同规模和初始状态的模型，包括有监督微调(\textbf{SFT})数据和无监督数据的情况。最终结果显示，这些算法表现旗鼓相当，其中专家迭代在多数场景下最优。令人意外的是，专家迭代所需的样本复杂度竟与PPO相近，仅需约$10^6$个样本就可使预训练模型快速收敛。究其原因，我们发现强化学习训练阶段，模型并未能充分探索超出已有SFT模型生成解决方案的空间。此外，我们还探讨了在SFT训练阶段maj@1与pass@96指标间存在的取舍关系，有趣的是，强化学习训练反而能使这两个指标同步提升。最后，我们通过分析所得成果，讨论了这对RLHF的意义及其对未来强化学习在LLM微调领域中角色的影响。

> Reinforcement Learning from Human Feedback (\textbf{RLHF}) has emerged as a dominant approach for aligning LLM outputs with human preferences. Inspired by the success of RLHF, we study the performance of multiple algorithms that learn from feedback (Expert Iteration, Proximal Policy Optimization (\textbf{PPO}), Return-Conditioned RL) on improving LLM reasoning capabilities. We investigate both sparse and dense rewards provided to the LLM both heuristically and via a learned reward model. We additionally start from multiple model sizes and initializations both with and without supervised fine-tuning (\textbf{SFT}) data. Overall, we find all algorithms perform comparably, with Expert Iteration performing best in most cases. Surprisingly, we find the sample complexity of Expert Iteration is similar to that of PPO, requiring at most on the order of $10^6$ samples to converge from a pretrained checkpoint. We investigate why this is the case, concluding that during RL training models fail to explore significantly beyond solutions already produced by SFT models. Additionally, we discuss a trade off between maj@1 and pass@96 metric performance during SFT training and how conversely RL training improves both simultaneously. We then conclude by discussing the implications of our findings for RLHF and the future role of RL in LLM fine-tuning.

[Arxiv](https://arxiv.org/abs/2403.04642)