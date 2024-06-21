# EvoAgent：探索利用进化算法自动生成多代理的途径

发布时间：2024年06月20日

`Agent

理由：这篇论文主要探讨了如何利用进化算法自动扩展基于大型语言模型（LLM）的代理至多代理系统，以提升任务解决能力。这种方法涉及创建和优化代理系统，以增强其在复杂任务中的表现，这直接关联到代理（Agent）的构建和应用。因此，将其归类为Agent是合适的。` `人工智能` `自动化系统`

> EvoAgent: Towards Automatic Multi-Agent Generation via Evolutionary Algorithms

# 摘要

> 随着大型语言模型（LLMs）的强大崛起，基于LLM的自主代理构建成为解决复杂任务的新潮流，尤其是多代理系统。尽管进步缓慢，但现有研究大多依赖于人为设计的框架，这限制了代理系统的功能和扩展性。如何自动将专业代理扩展至多代理系统，以提升任务解决能力，仍是一大挑战。本文提出的EvoAgent，利用进化算法，能自动将专家代理扩展至多代理系统，增强基于LLM的代理在任务解决中的效能。我们将现有代理框架视为起点，通过进化操作（如变异、交叉、选择等）生成多样化的代理。EvoAgent适用于任何基于LLM的代理框架，无需额外人为设计，即可自动扩展至多代理系统。实验证明，EvoAgent能自动生成专家代理，显著提升基于LLM的代理的任务解决能力。

> The rise of powerful large language models (LLMs) has spurred a new trend in building LLM-based autonomous agents for solving complex tasks, especially multi-agent systems. Despite the remarkable progress, we notice that existing works are heavily dependent on human-designed frameworks, which greatly limits the functional scope and scalability of agent systems. How to automatically extend the specialized agent to multi-agent systems to improve task-solving capability still remains a significant challenge. In this paper, we introduce EvoAgent, a generic method to automatically extend expert agents to multi-agent systems via the evolutionary algorithm, thereby improving the effectiveness of LLM-based agents in solving tasks. Specifically, we consider the existing agent frameworks as the initial individual and then apply a series of evolutionary operators (e.g., mutation, crossover, selection, etc.) to generate multiple agents with diverse agent settings. EvoAgent can be generalized to any LLM-based agent framework, and can automatically extend the existing agent framework to multi-agent systems without any extra human designs. Experimental results across various tasks have shown that EvoAgent can automatically generate multiple expert agents and significantly enhance the task-solving capabilities of LLM-based agents.

[Arxiv](https://arxiv.org/abs/2406.14228)