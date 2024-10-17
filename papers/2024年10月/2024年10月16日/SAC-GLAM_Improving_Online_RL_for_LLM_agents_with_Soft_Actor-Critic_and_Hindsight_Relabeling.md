# SAC-GLAM：结合软演员-评论家与事后重标记，提升 LLM 代理的在线强化学习效果。

发布时间：2024年10月16日

`Agent` `人工智能`

> SAC-GLAM: Improving Online RL for LLM agents with Soft Actor-Critic and Hindsight Relabeling

# 摘要

> 近年来，大型语言模型 (LLM) 不仅在生成任务中表现出色，还作为文本序列决策任务的智能体大放异彩。面对复杂环境，零-shot 能力不足时，在线强化学习 (RL) 成为 LLM 智能体交互学习高效策略的新途径。然而，现有研究多局限于 on-policy 算法，限制了探索与利用的策略多样性，如经验回放和事后重标记。本文探索了 Soft Actor-Critic 和事后重标记在 LLM 智能体中的应用，不仅为自主内在动机智能体（autotelic 智能体）的在线学习开辟了新路径，还在多目标 RL 环境中超越了传统 on-policy 方法。

> The past years have seen Large Language Models (LLMs) strive not only as generative models but also as agents solving textual sequential decision-making tasks. When facing complex environments where their zero-shot abilities are insufficient, recent work showed online Reinforcement Learning (RL) could be used for the LLM agent to discover and learn efficient strategies interactively. However, most prior work sticks to on-policy algorithms, which greatly reduces the scope of methods such agents could use for both exploration and exploitation, such as experience replay and hindsight relabeling. Yet, such methods may be key for LLM learning agents, and in particular when designing autonomous intrinsically motivated agents sampling and pursuing their own goals (i.e. autotelic agents). This paper presents and studies an adaptation of Soft Actor-Critic and hindsight relabeling to LLM agents. Our method not only paves the path towards autotelic LLM agents that learn online but can also outperform on-policy methods in more classic multi-goal RL environments.

[Arxiv](https://arxiv.org/abs/2410.12481)