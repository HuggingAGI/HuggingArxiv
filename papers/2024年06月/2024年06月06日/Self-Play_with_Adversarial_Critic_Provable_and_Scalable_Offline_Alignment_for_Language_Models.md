# 通过自我对抗批评的自我游戏，我们提出了一种可证明且可扩展的离线对齐方法，用于语言模型。

发布时间：2024年06月06日

`LLM理论

理由：该论文摘要主要讨论了通过人类反馈强化学习（RLHF）来调整大型语言模型（LLMs）与离线偏好数据的对齐问题，并提出了新的方法SPAC。这种方法结合了自对弈和离线RL中的平均悲观技术，并且进行了理论分析，证实了其收敛性。这些内容主要涉及LLM的理论优化和对齐策略，因此更适合归类于LLM理论。` `人工智能` `机器学习`

> Self-Play with Adversarial Critic: Provable and Scalable Offline Alignment for Language Models

# 摘要

> 本研究聚焦于通过人类反馈强化学习（RLHF）来调整大型语言模型（LLMs）与离线偏好数据的对齐问题。尽管现有的偏好优化方法在实际应用中表现出色，但它们在理论上无法确保收敛至最优策略，尤其是在数据覆盖不足时。与此同时，一些基于理论的新方法虽有保证，却不适用于大规模的LLM对齐。为此，我们创新性地提出了SPAC方法，它结合了自对弈和离线RL中的平均悲观技术，成为首个既可证明又可扩展的LLM对齐策略。理论分析证实了其在一般函数逼近条件下对单策略集中性的收敛性，并在7B Mistral模型上通过Open LLM Leaderboard的评估，展示了其在LLM对齐中的卓越表现。

> This work studies the challenge of aligning large language models (LLMs) with offline preference data. We focus on alignment by Reinforcement Learning from Human Feedback (RLHF) in particular. While popular preference optimization methods exhibit good empirical performance in practice, they are not theoretically guaranteed to converge to the optimal policy and can provably fail when the data coverage is sparse by classical offline reinforcement learning (RL) results. On the other hand, a recent line of work has focused on theoretically motivated preference optimization methods with provable guarantees, but these are not computationally efficient for large-scale applications like LLM alignment. To bridge this gap, we propose SPAC, a new offline preference optimization method with self-play, inspired by the on-average pessimism technique from the offline RL literature, to be the first provable and scalable approach to LLM alignment. We both provide theoretical analysis for its convergence under single-policy concentrability for the general function approximation setting and demonstrate its competitive empirical performance for LLM alignment on a 7B Mistral model with Open LLM Leaderboard evaluations.

[Arxiv](https://arxiv.org/abs/2406.04274)