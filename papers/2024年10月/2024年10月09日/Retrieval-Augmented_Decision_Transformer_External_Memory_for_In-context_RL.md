# 检索增强决策变换器：为上下文强化学习引入外部记忆

发布时间：2024年10月09日

`Agent` `机器人`

> Retrieval-Augmented Decision Transformer: External Memory for In-context RL

# 摘要

> ICL 是模型通过观察上下文中的几个示例来学习新任务的能力。虽然常见于 NLP，但最近在 RL 中也发现了这种能力。然而，现有的 in-context RL 方法需要完整的经验片段，这在复杂环境中因长且稀疏的奖励而受限。为此，我们提出了 RA-DT，它利用外部记忆存储并仅检索与当前情境相关的子轨迹，无需训练且领域无关。在网格世界、机器人模拟和程序生成游戏中，RA-DT 表现优异，且上下文长度大幅缩短。我们还探讨了当前 in-context RL 方法的局限性，并展望了未来研究方向。为推动研究，我们公开了四个环境的基准数据集。

> In-context learning (ICL) is the ability of a model to learn a new task by observing a few exemplars in its context. While prevalent in NLP, this capability has recently also been observed in Reinforcement Learning (RL) settings. Prior in-context RL methods, however, require entire episodes in the agent's context. Given that complex environments typically lead to long episodes with sparse rewards, these methods are constrained to simple environments with short episodes. To address these challenges, we introduce Retrieval-Augmented Decision Transformer (RA-DT). RA-DT employs an external memory mechanism to store past experiences from which it retrieves only sub-trajectories relevant for the current situation. The retrieval component in RA-DT does not require training and can be entirely domain-agnostic. We evaluate the capabilities of RA-DT on grid-world environments, robotics simulations, and procedurally-generated video games. On grid-worlds, RA-DT outperforms baselines, while using only a fraction of their context length. Furthermore, we illuminate the limitations of current in-context RL methods on complex environments and discuss future directions. To facilitate future research, we release datasets for four of the considered environments.

[Arxiv](https://arxiv.org/abs/2410.07071)