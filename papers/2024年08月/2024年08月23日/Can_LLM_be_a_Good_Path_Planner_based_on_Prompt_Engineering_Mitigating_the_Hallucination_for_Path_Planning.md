# LLM 能否借助提示工程成为出色的路径规划器？我们探讨如何减少路径规划中的幻觉现象。

发布时间：2024年08月23日

`LLM应用` `人工智能` `机器人学`

> Can LLM be a Good Path Planner based on Prompt Engineering? Mitigating the Hallucination for Path Planning

# 摘要

> 大型语言模型（LLM）中的空间推理是实现具身智能的关键。然而，即使在简单的迷宫环境中，LLM在长期路径规划方面仍面临挑战，主要原因是空间幻觉和长期推理导致的上下文不一致幻觉。为此，我们提出了一种创新模型——空间到关系转换与课程Q学习（S2RCQL）。该模型通过将空间提示转换为实体关系和路径，有效挖掘了LLM在序列思维方面的潜力。同时，我们设计了基于Q学习的路径规划算法，利用状态-动作的Q值辅助信息，纠正LLM的幻觉，引导其学习最优路径。此外，我们还引入了逆向课程学习技术，通过降低任务难度，帮助LLM快速积累成功经验，应对更复杂的任务。在ERNIE-Bot 4.0上的实验结果表明，S2RCQL在成功率和最优性率方面分别提升了23%--40%，显著优于现有的提示工程方法。

> Spatial reasoning in Large Language Models (LLMs) is the foundation for embodied intelligence. However, even in simple maze environments, LLMs still encounter challenges in long-term path-planning, primarily influenced by their spatial hallucination and context inconsistency hallucination by long-term reasoning. To address this challenge, this study proposes an innovative model, Spatial-to-Relational Transformation and Curriculum Q-Learning (S2RCQL). To address the spatial hallucination of LLMs, we propose the Spatial-to-Relational approach, which transforms spatial prompts into entity relations and paths representing entity relation chains. This approach fully taps the potential of LLMs in terms of sequential thinking. As a result, we design a path-planning algorithm based on Q-learning to mitigate the context inconsistency hallucination, which enhances the reasoning ability of LLMs. Using the Q-value of state-action as auxiliary information for prompts, we correct the hallucinations of LLMs, thereby guiding LLMs to learn the optimal path. Finally, we propose a reverse curriculum learning technique based on LLMs to further mitigate the context inconsistency hallucination. LLMs can rapidly accumulate successful experiences by reducing task difficulty and leveraging them to tackle more complex tasks. We performed comprehensive experiments based on Baidu's self-developed LLM: ERNIE-Bot 4.0. The results showed that our S2RCQL achieved a 23%--40% improvement in both success and optimality rates compared with advanced prompt engineering.

[Arxiv](https://arxiv.org/abs/2408.13184)