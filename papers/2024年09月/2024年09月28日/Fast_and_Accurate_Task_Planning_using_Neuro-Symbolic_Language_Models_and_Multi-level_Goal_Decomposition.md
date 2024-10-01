# 通过神经符号语言模型与多层次目标分解，实现高效精准的任务规划

发布时间：2024年09月28日

`Agent` `机器人` `人工智能`

> Fast and Accurate Task Planning using Neuro-Symbolic Language Models and Multi-level Goal Decomposition

# 摘要

> 在机器人任务规划领域，传统的符号规划器（如PDDL）虽然有效，但在复杂环境中处理长序列任务时，搜索空间呈指数级增长，效率大打折扣。近年来，基于人工神经网络的大型语言模型（LLM）崭露头角，以其快速推理和丰富的常识知识，成为自主机器人任务规划的新星。然而，其成功率往往不尽如人意。为此，我们提出了一种创新的神经符号任务规划器，巧妙地将复杂任务分解为子目标，并根据子目标的复杂性，灵活选择符号或基于MCTS的LLM规划器进行任务规划。这一策略不仅缩小了搜索空间，还让LLM专注于更易管理的小任务，从而显著提升规划效率和成功率。实验证明，我们的方法在保持高成功率的同时，大幅缩短了规划时间，适用于多种任务规划场景和机器人环境。

> In robotic task planning, symbolic planners using rule-based representations like PDDL are effective but struggle with long-sequential tasks in complicated planning environments due to exponentially increasing search space. Recently, Large Language Models (LLMs) based on artificial neural networks have emerged as promising alternatives for autonomous robot task planning, offering faster inference and leveraging commonsense knowledge. However, they typically suffer from lower success rates. In this paper, to address the limitations of the current symbolic (slow speed) or LLM-based approaches (low accuracy), we propose a novel neuro-symbolic task planner that decomposes complex tasks into subgoals using LLM and carries out task planning for each subgoal using either symbolic or MCTS-based LLM planners, depending on the subgoal complexity. Generating subgoals helps reduce planning time and improve success rates by narrowing the overall search space and enabling LLMs to focus on smaller, more manageable tasks. Our method significantly reduces planning time while maintaining a competitive success rate, as demonstrated through experiments in different public task planning domains, as well as real-world and simulated robotics environments.

[Arxiv](https://arxiv.org/abs/2409.19250)