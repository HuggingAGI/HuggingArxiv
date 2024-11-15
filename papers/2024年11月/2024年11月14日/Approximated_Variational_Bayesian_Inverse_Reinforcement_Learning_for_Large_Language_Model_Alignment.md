# 近似的变分贝叶斯逆强化学习应用于大型语言模型的对齐

发布时间：2024年11月14日

`LLM应用` `语言模型`

> Approximated Variational Bayesian Inverse Reinforcement Learning for Large Language Model Alignment

# 摘要

> 大型语言模型（LLM）的对齐对于生成有益且无害的内容极为关键。现有的办法借助基于偏好的人类反馈数据来学习奖励函数，并让 LLM 与反馈数据达成一致。然而，这些方法着重于对所选和被拒演示之间的奖励差异进行建模，而非直接对每个演示的真实奖励建模。再者，这些方法假定奖励仅在句末获取，忽略了中间奖励的建模。这些问题致使反馈数据中的训练信号利用不足，限制了奖励的表示和泛化能力，还可能造成奖励被恶意利用。在本文中，我们把 LLM 对齐设定为贝叶斯逆强化学习（BIRL）问题，并提出了全新的训练目标——近似变分对齐（AVA），通过近似变分奖励模仿学习（AVRIL）来实现 LLM 对齐。BIRL 公式有利于中间奖励建模和对每个单独演示的直接奖励建模，增强了反馈数据中训练信号的使用效率。实验显示，在奖励建模、RL 微调以及直接优化方面，AVA 都优于现有的 LLM 对齐方法。

> The alignment of large language models (LLMs) is crucial for generating helpful and harmless content. Existing approaches leverage preference-based human feedback data to learn the reward function and align the LLM with the feedback data. However, these approaches focus on modeling the reward difference between the chosen and rejected demonstrations, rather than directly modeling the true reward from each demonstration. Moreover, these approaches assume that the reward is only obtained at the end of the sentence, which overlooks the modeling of intermediate rewards. These issues lead to insufficient use of training signals in the feedback data, limiting the representation and generalization ability of the reward and potentially resulting in reward hacking. In this paper, we formulate LLM alignment as a Bayesian Inverse Reinforcement Learning (BIRL) problem and propose a novel training objective, Approximated Variational Alignment (AVA), to perform LLM alignment through Approximated Variational Reward Imitation Learning (AVRIL). The BIRL formulation facilitates intermediate reward modeling and direct reward modeling on each single demonstration, which enhances the utilization of training signals in the feedback data. Experiments show that AVA outperforms existing LLM alignment approaches in reward modeling, RL fine-tuning, and direct optimization.

[Arxiv](https://arxiv.org/abs/2411.09341)