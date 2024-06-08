# 通过自我对抗批评的自玩策略，我们提出了一种既可证明又可扩展的语言模型离线对齐方法。

发布时间：2024年06月06日

`LLM理论

理由：这篇论文探讨了通过人类反馈的强化学习（RLHF）来对齐大型语言模型（LLMs）的理论问题，并提出了一个新的方法SPAC，旨在解决现有方法在理论保证和实际应用中的局限性。论文不仅提供了理论证明，还通过实际模型评估展示了其有效性。因此，它更偏向于LLM的理论研究，而不是具体的应用、Agent设计或RAG相关的研究。` `人工智能` `机器学习`

> Self-Play with Adversarial Critic: Provable and Scalable Offline Alignment for Language Models

# 摘要

> 本研究聚焦于通过人类反馈的强化学习（RLHF）来对齐大型语言模型（LLMs）与离线偏好数据。尽管现有的偏好优化方法在实践中表现出色，但它们在理论上无法确保收敛至最优策略，尤其是在数据覆盖不足时。与此同时，一些理论驱动的优化方法虽有保证，却不适用于LLM对齐这类大规模应用。为此，我们创新性地提出了SPAC，一种结合自对弈的离线偏好优化方法，灵感源自离线RL的平均悲观技术，旨在为LLM对齐提供首个既可证明又可扩展的解决方案。我们不仅从理论上证明了SPAC在单策略集中性下的收敛性，还通过在7B Mistral模型上的Open LLM Leaderboard评估，展示了其在LLM对齐中的卓越表现。

> This work studies the challenge of aligning large language models (LLMs) with offline preference data. We focus on alignment by Reinforcement Learning from Human Feedback (RLHF) in particular. While popular preference optimization methods exhibit good empirical performance in practice, they are not theoretically guaranteed to converge to the optimal policy and can provably fail when the data coverage is sparse by classical offline reinforcement learning (RL) results. On the other hand, a recent line of work has focused on theoretically motivated preference optimization methods with provable guarantees, but these are not computationally efficient for large-scale applications like LLM alignment. To bridge this gap, we propose SPAC, a new offline preference optimization method with self-play, inspired by the on-average pessimism technique from the offline RL literature, to be the first provable and scalable approach to LLM alignment. We both provide theoretical analysis for its convergence under single-policy concentrability for the general function approximation setting and demonstrate its competitive empirical performance for LLM alignment on a 7B Mistral model with Open LLM Leaderboard evaluations.

[Arxiv](https://arxiv.org/abs/2406.04274)