# 思维蓝图：借助大型语言模型实现启发式问题解决策略

发布时间：2024年04月29日

`分类：LLM应用

这篇论文讨论了语言模型在零样本推理任务中的应用，特别是针对需要连续推理的问题。作者提出了一种基于规划的方法，通过部分可观测马尔可夫决策过程（POMDPs）和在线POMDP求解器POMCP来提高语言模型在复杂推理任务中的表现。这篇论文的研究重点在于提高语言模型在特定任务上的应用效果，因此可以归类为LLM应用。` `人工智能`

> Plan of Thoughts: Heuristic-Guided Problem Solving with Large Language Models

# 摘要

> 语言模型在众多领域的零样本推理任务中展现出强大的能力，但面对需要连续推理的问题时，它们的表现尚有不足。传统解决方案是将复杂任务拆解为多个子任务，让语言模型为每个子任务提出方案，并采用深度优先搜索等策略来整合答案。本研究在此基础上提出了两项创新：一是将基于规划的方法应用于LMs的多步问题解决，通过部分可观测马尔可夫决策过程（POMDPs），并以LM对状态价值的自我评估作为搜索策略；二是借助在线POMDP求解器POMCP，在24点游戏中实现了89.4%的高解决率，超越了现有技术，并在随时性能上优于以往的固定树搜索方法。这些贡献使得现代语言模型能够更高效地分解和处理更复杂的推理任务。

> While language models (LMs) offer significant capability in zero-shot reasoning tasks across a wide range of domains, they do not perform satisfactorily in problems which requires multi-step reasoning. Previous approaches to mitigate this involves breaking a larger, multi-step task into sub-tasks and asking the language model to generate proposals ("thoughts") for each sub-task and using exhaustive planning approaches such as DFS to compose a solution. In this work, we leverage this idea to introduce two new contributions: first, we formalize a planning-based approach to perform multi-step problem solving with LMs via Partially Observable Markov Decision Processes (POMDPs), with the LM's own reflections about the value of a state used as a search heuristic; second, leveraging the online POMDP solver POMCP, we demonstrate a superior success rate of 89.4% on the Game of 24 task as compared to existing approaches while also offering better anytime performance characteristics than fixed tree-search which is used previously. Taken together, these contributions allow modern LMs to decompose and solve larger-scale reasoning tasks more effectively.

[Arxiv](https://arxiv.org/abs/2404.19055)