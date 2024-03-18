# [通过“试错”方式，研究针对LLM智能体的探索式轨迹优化策略。]

发布时间：2024年03月04日

`Agent`

> Trial and Error: Exploration-Based Trajectory Optimization for LLM Agents

> 现今，LLMs已成为各类自主智能系统的中坚力量。本次研究介绍了一种创新的探索式轨迹优化方案——ETO，它专为提升开放型LLM智能体表现而设计。不同于以往仅依赖成功专家轨迹训练的研究，ETO让智能体能够从探索中的失败经历中汲取教训，并通过迭代优化框架逐步提升性能。在探索环节，智能体在执行任务时与环境互动，积累失败轨迹并构造对比性的轨迹对；到了后续的训练阶段，则借助DPO等对比学习技术，使用这些轨迹对调整策略。这一探索与训练的反复循环有助于智能体不断进步。实验证明，在三项复杂的任务上，ETO均能显著优于基础线性性能。而且，在缺乏专家轨迹指导的情况下，观察到的任务解决效率和潜力增长，有力地证明了ETO方法的有效性。

> Large Language Models (LLMs) have become integral components in various autonomous agent systems. In this study, we present an exploration-based trajectory optimization approach, referred to as ETO. This learning method is designed to enhance the performance of open LLM agents. Contrary to previous studies that exclusively train on successful expert trajectories, our method allows agents to learn from their exploration failures. This leads to improved performance through an iterative optimization framework. During the exploration phase, the agent interacts with the environment while completing given tasks, gathering failure trajectories to create contrastive trajectory pairs. In the subsequent training phase, the agent utilizes these trajectory preference pairs to update its policy using contrastive learning methods like DPO. This iterative cycle of exploration and training fosters continued improvement in the agents. Our experiments on three complex tasks demonstrate that ETO consistently surpasses baseline performance by a large margin. Furthermore, an examination of task-solving efficiency and potential in scenarios lacking expert trajectory underscores the effectiveness of our approach.

[Arxiv](https://arxiv.org/abs/2403.02502)