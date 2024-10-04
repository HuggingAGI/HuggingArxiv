# LLM 增强的符号强化学习，结合基于地标的任务分解技术

发布时间：2024年10月02日

`Agent` `人工智能`

> LLM-Augmented Symbolic Reinforcement Learning with Landmark-Based Task Decomposition

# 摘要

> 在强化学习中，将复杂任务分解为更简单的子任务是一个核心挑战。本文中，我们通过分析正负轨迹，成功识别出这些子任务。我们采用一阶谓词逻辑表示状态，并设计了新算法来识别子任务。随后，利用大型语言模型生成一阶逻辑规则模板，并通过归纳逻辑编程进一步优化，形成基于规则的策略。实验证明，我们的算法能准确识别所有子任务，且生成的常识规则质量高。这不仅简化了复杂任务的解决，还减少了对环境预定义逻辑的依赖。

> One of the fundamental challenges in reinforcement learning (RL) is to take a complex task and be able to decompose it to subtasks that are simpler for the RL agent to learn. In this paper, we report on our work that would identify subtasks by using some given positive and negative trajectories for solving the complex task. We assume that the states are represented by first-order predicate logic using which we devise a novel algorithm to identify the subtasks. Then we employ a Large Language Model (LLM) to generate first-order logic rule templates for achieving each subtask. Such rules were then further fined tuned to a rule-based policy via an Inductive Logic Programming (ILP)-based RL agent. Through experiments, we verify the accuracy of our algorithm in detecting subtasks which successfully detect all of the subtasks correctly. We also investigated the quality of the common-sense rules produced by the language model to achieve the subtasks. Our experiments show that our LLM-guided rule template generation can produce rules that are necessary for solving a subtask, which leads to solving complex tasks with fewer assumptions about predefined first-order logic predicates of the environment.

[Arxiv](https://arxiv.org/abs/2410.01929)