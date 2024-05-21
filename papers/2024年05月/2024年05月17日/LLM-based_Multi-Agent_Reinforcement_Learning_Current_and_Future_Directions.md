# 大型语言模型驱动的多智能体强化学习：现状与未来展望

发布时间：2024年05月17日

`Agent

理由：这篇论文主要探讨了大型语言模型（LLMs）在多代理系统（MAS）中的应用，特别是在强化学习（RL）环境下的代理间协调与通信问题。它关注的是如何将LLMs作为代理应用于多代理系统中，并探讨了多代理合作任务及代理间的沟通，以及语言元素在框架中带来的新场景。这与Agent分类下的研究内容相符，即研究智能代理的设计、行为和交互。` `多代理系统`

> LLM-based Multi-Agent Reinforcement Learning: Current and Future Directions

# 摘要

> 大型语言模型（LLMs）近年来在问答、算术解题、诗歌创作等多项任务中大放异彩。虽然研究显示，LLM作为代理在强化学习（RL）中表现出色，但将其应用于多代理系统（MAS）却面临挑战，因为涉及代理间协调与通信的复杂性在单代理RL框架中未被充分考虑。本研究旨在探索基于LLM的多代理RL，回顾现有框架，并提出未来研究方向，特别聚焦于多代理合作任务及它们之间的沟通，同时探讨了框架中语言元素带来的“人在环”新场景。

> In recent years, Large Language Models (LLMs) have shown great abilities in various tasks, including question answering, arithmetic problem solving, and poem writing, among others. Although research on LLM-as-an-agent has shown that LLM can be applied to Reinforcement Learning (RL) and achieve decent results, the extension of LLM-based RL to Multi-Agent System (MAS) is not trivial, as many aspects, such as coordination and communication between agents, are not considered in the RL frameworks of a single agent. To inspire more research on LLM-based MARL, in this letter, we survey the existing LLM-based single-agent and multi-agent RL frameworks and provide potential research directions for future research. In particular, we focus on the cooperative tasks of multiple agents with a common goal and communication among them. We also consider human-in/on-the-loop scenarios enabled by the language component in the framework.

[Arxiv](https://arxiv.org/abs/2405.11106)