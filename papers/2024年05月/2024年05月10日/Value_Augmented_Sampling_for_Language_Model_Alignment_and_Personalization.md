# 语言模型的价值增强采样：对齐与个性化之道

发布时间：2024年05月10日

`LLM应用

这篇论文探讨了如何调整大型语言模型以适应人类多样化的偏好，并提出了一个名为价值增强采样（VAS）的新框架。该框架旨在优化多重奖励函数，同时保持较低的推理成本，这对于个性化调整LLM至关重要。论文中提到的VAS框架超越了传统方法，如PPO和DPO，并且在推理成本方面与Best-of-128相媲美。这种方法特别适用于那些仅提供API的模型，如ChatGPT，并且为在部署时灵活组合和微调多重奖励提供了新的可能性。因此，这篇论文的内容与LLM的应用紧密相关，特别是在个性化调整和优化方面，而不是专注于Agent的设计、RAG（Retrieval-Augmented Generation）的构建或LLM的理论研究。` `人工智能个性化`

> Value Augmented Sampling for Language Model Alignment and Personalization

# 摘要

> 调整大型语言模型以适应人类多样化的偏好、学习新技能并消除有害行为，是当前亟待解决的挑战。虽然搜索方法如Best-of-N或蒙特卡洛树搜索性能卓越，但高昂的推理成本使其不适用于LLM的个性化调整。相比之下，强化学习虽计算高效，却在共同优化价值函数与策略时遭遇瓶颈，表现不佳。我们提出的价值增强采样（VAS）框架，能在不触及LLM原始权重的前提下，仅凭初始冻结模型的数据，精准优化多重奖励函数。VAS避免了策略与价值函数的共同训练，确保了优化过程的稳定性，不仅在标准测试中超越了PPO和DPO等传统方法，更以较低的推理成本，实现了与Best-of-128相媲美的成果。这一创新不仅适用于如ChatGPT这类仅提供API的模型，还开启了在部署时灵活组合并微调多重奖励的新篇章，预示着个性化、高度对齐的LLM的未来发展方向。

> Aligning Large Language Models (LLMs) to cater to different human preferences, learning new skills, and unlearning harmful behavior is an important problem. Search-based methods, such as Best-of-N or Monte-Carlo Tree Search, are performant, but impractical for LLM adaptation due to their high inference cost. On the other hand, using Reinforcement Learning (RL) for adaptation is computationally efficient, but performs worse due to the optimization challenges in co-training the value function and the policy. We present a new framework for reward optimization, Value Augmented Sampling (VAS), that can maximize different reward functions using data sampled from only the initial, frozen LLM. VAS solves for the optimal reward-maximizing policy without co-training the policy and the value function, making the optimization stable, outperforming established baselines, such as PPO and DPO, on standard benchmarks, and achieving comparable results to Best-of-128 with lower inference cost. Unlike existing RL methods that require changing the weights of the LLM, VAS does not require access to the weights of the pre-trained LLM. Thus, it can even adapt LLMs (e.g., ChatGPT), which are available only as APIs. In addition, our algorithm unlocks the new capability of composing several rewards and controlling the extent of each one during deployment time, paving the road ahead for the future of aligned, personalized LLMs.

[Arxiv](https://arxiv.org/abs/2405.06639)