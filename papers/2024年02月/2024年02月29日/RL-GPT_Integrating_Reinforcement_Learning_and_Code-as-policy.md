# [RL-GPT：融汇强化学习与“代码即策略”思想，实现两者深度整合。](https://arxiv.org/abs/2402.19299)

> RL-GPT: Integrating Reinforcement Learning and Code-as-policy

发布时间：2024年02月29日

> LLMs擅长通过编码手段运用各类工具，但对于复杂逻辑及精准操控仍面临挑战。在实体交互任务中，高层规划易于直接编码实现，而底层动作往往需要针对具体任务进行细化调优，比如采用RL技术。为将两者完美融合，我们创新提出了一种双层递阶框架——RL-GPT，该框架包括一个负责深思熟虑的慢速代理与一个执行编码任务的快速代理。这样的拆解设计让两个代理各司其职，显著提升了整体流程的效率。相较于传统RL方法及现存GPT代理，我们的方案表现出更优的效能。实验表明，在Minecraft游戏中，仅用一天时间便能借助RTX3090显卡迅速挖到钻石；同时，它还在所有预设的MineDojo任务中都达到了顶尖水平。

> Large Language Models (LLMs) have demonstrated proficiency in utilizing various tools by coding, yet they face limitations in handling intricate logic and precise control. In embodied tasks, high-level planning is amenable to direct coding, while low-level actions often necessitate task-specific refinement, such as Reinforcement Learning (RL). To seamlessly integrate both modalities, we introduce a two-level hierarchical framework, RL-GPT, comprising a slow agent and a fast agent. The slow agent analyzes actions suitable for coding, while the fast agent executes coding tasks. This decomposition effectively focuses each agent on specific tasks, proving highly efficient within our pipeline. Our approach outperforms traditional RL methods and existing GPT agents, demonstrating superior efficiency. In the Minecraft game, it rapidly obtains diamonds within a single day on an RTX3090. Additionally, it achieves SOTA performance across all designated MineDojo tasks.

`Agent`