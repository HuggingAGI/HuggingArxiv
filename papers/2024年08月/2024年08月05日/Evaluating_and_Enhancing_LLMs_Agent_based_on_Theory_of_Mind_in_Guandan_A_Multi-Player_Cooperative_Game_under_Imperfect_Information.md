# 在不完全信息的多人合作游戏中，我们评估并增强了基于心智理论的关丹大型语言模型代理。

发布时间：2024年08月05日

`Agent` `人工智能`

> Evaluating and Enhancing LLMs Agent based on Theory of Mind in Guandan: A Multi-Player Cooperative Game under Imperfect Information

# 摘要

> 大型语言模型 (LLM) 在处理不完美信息的简单游戏和多代理协调方面已取得成功，但在复杂非英语环境中的实际协作能力仍待探索。本研究评估了开源和基于 API 的 LLM 在需要代理协作的复杂文本游戏中的表现，并与传统代理进行了比较。我们提出了一种心智理论 (ToM) 规划技术，使 LLM 代理能根据游戏规则、当前状态和历史上下文调整策略。为应对纸牌游戏中动态广泛的动作空间，我们引入了外部工具。研究显示，尽管 LLM 与顶尖强化学习模型存在差距，但它们在此游戏中展现了 ToM 能力，持续提升与对手的对抗表现，表明其理解并协作盟友的能力。为促进深入研究，我们公开了代码库。

> Large language models (LLMs) have shown success in handling simple games with imperfect information and enabling multi-agent coordination, but their ability to facilitate practical collaboration against other agents in complex, imperfect information environments, especially in a non-English environment, still needs to be explored. This study investigates the applicability of knowledge acquired by open-source and API-based LLMs to sophisticated text-based games requiring agent collaboration under imperfect information, comparing their performance to established baselines using other types of agents. We propose a Theory of Mind (ToM) planning technique that allows LLM agents to adapt their strategy against various adversaries using only game rules, current state, and historical context as input. An external tool was incorporated to mitigate the challenge of dynamic and extensive action spaces in this card game. Our results show that although a performance gap exists between current LLMs and state-of-the-art reinforcement learning (RL) models, LLMs demonstrate ToM capabilities in this game setting. It consistently improves their performance against opposing agents, suggesting their ability to understand the actions of allies and adversaries and establish collaboration with allies. To encourage further research and understanding, we have made our codebase openly accessible.

[Arxiv](https://arxiv.org/abs/2408.02559)