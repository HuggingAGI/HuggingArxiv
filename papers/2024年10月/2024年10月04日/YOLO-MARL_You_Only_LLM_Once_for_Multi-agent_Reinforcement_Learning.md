# YOLO-MARL：一次 LLM，多智能体强化学习无忧

发布时间：2024年10月04日

`Agent` `人工智能`

> YOLO-MARL: You Only LLM Once for Multi-agent Reinforcement Learning

# 摘要

> 深度多智能体强化学习 (MARL) 在合作游戏中的决策方面展现出巨大潜力，但某些游戏环境中的合作策略学习仍具挑战。近期，大型语言模型 (LLM) 的涌现推理能力为增强智能体间的协调提供了新思路，但频繁调用 LLM 进行决策推断成本高昂。为此，我们提出 YOLO-MARL 框架，利用 LLM 的高级规划能力优化 MARL 策略学习。每个游戏环境仅需一次 LLM 交互，即可完成策略生成、状态解释和规划功能，避免了训练期间的频繁 API 调用成本。训练后的去中心化神经网络策略独立于 LLM 运行。实验表明，YOLO-MARL 在多个环境中均优于传统 MARL 算法。

> Advancements in deep multi-agent reinforcement learning (MARL) have positioned it as a promising approach for decision-making in cooperative games. However, it still remains challenging for MARL agents to learn cooperative strategies for some game environments. Recently, large language models (LLMs) have demonstrated emergent reasoning capabilities, making them promising candidates for enhancing coordination among the agents. However, due to the model size of LLMs, it can be expensive to frequently infer LLMs for actions that agents can take. In this work, we propose You Only LLM Once for MARL (YOLO-MARL), a novel framework that leverages the high-level task planning capabilities of LLMs to improve the policy learning process of multi-agents in cooperative games. Notably, for each game environment, YOLO-MARL only requires one time interaction with LLMs in the proposed strategy generation, state interpretation and planning function generation modules, before the MARL policy training process. This avoids the ongoing costs and computational time associated with frequent LLMs API calls during training. Moreover, the trained decentralized normal-sized neural network-based policies operate independently of the LLM. We evaluate our method across three different environments and demonstrate that YOLO-MARL outperforms traditional MARL algorithms.

[Arxiv](https://arxiv.org/abs/2410.03997)