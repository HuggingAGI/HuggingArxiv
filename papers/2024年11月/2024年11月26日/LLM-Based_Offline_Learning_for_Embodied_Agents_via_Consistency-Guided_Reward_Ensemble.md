# 通过一致性引导奖励集成实现基于 LLM 的具身智能体离线学习

发布时间：2024年11月26日

`Agent` `具身智能` `离线强化学习`

> LLM-Based Offline Learning for Embodied Agents via Consistency-Guided Reward Ensemble

# 摘要

> 使用大型语言模型（LLMs）实现具身智能体已颇为流行，然而在实际应用中存在不少限制。在本研究中，我们并非直接把LLMs当作智能体，而是探索将其作为具身智能体学习的工具。具体而言，为通过离线强化学习（RL）训练单独的智能体，利用LLM在训练数据集中为单个动作提供密集的奖励反馈。在此过程中，我们提出了一致性引导的奖励集成框架（CoREN），旨在解决将LLM生成的估计值落实到目标环境领域的难题。该框架采用时空一致奖励的自适应集成，在训练数据集中得出基于领域的奖励，从而能在不同环境领域对具身智能体进行有效的离线学习。在VirtualHome基准上的实验表明，CoREN显著优于其他离线RL智能体，而且尽管CoREN的智能体策略网络仅有1.17亿个参数且仅在训练时使用LLMs，其性能也能与拥有80亿参数的最先进的基于LLM的智能体相媲美。

> Employing large language models (LLMs) to enable embodied agents has become popular, yet it presents several limitations in practice. In this work, rather than using LLMs directly as agents, we explore their use as tools for embodied agent learning. Specifically, to train separate agents via offline reinforcement learning (RL), an LLM is used to provide dense reward feedback on individual actions in training datasets. In doing so, we present a consistency-guided reward ensemble framework (CoREN), designed for tackling difficulties in grounding LLM-generated estimates to the target environment domain. The framework employs an adaptive ensemble of spatio-temporally consistent rewards to derive domain-grounded rewards in the training datasets, thus enabling effective offline learning of embodied agents in different environment domains. Experiments with the VirtualHome benchmark demonstrate that CoREN significantly outperforms other offline RL agents, and it also achieves comparable performance to state-of-the-art LLM-based agents with 8B parameters, despite CoREN having only 117M parameters for the agent policy network and using LLMs only for training.

[Arxiv](https://arxiv.org/abs/2411.17135)