# PIANIST：借助 LLMs 学习部分可观测的世界模型，服务于多智能体决策

发布时间：2024年11月24日

`LLM应用`

> PIANIST: Learning Partially Observable World Models with LLMs for Multi-Agent Decision Making

# 摘要

> 有效从 LLMs 中提取世界知识以用于复杂决策任务，这仍是个难题。我们提出了一个叫 PIANIST 的框架，把世界模型分解为七个直观的组件，利于零样本 LLM 生成。只要给出游戏的自然语言描述以及输入观察的格式，我们的方法就能生成一个可用的世界模型，用于快速高效的 MCTS 模拟。我们证明，我们的方法在两个不同的游戏中效果出色，这两个游戏在基于语言和非语言的行动方面都考验了智能体的规划和决策能力，而且无需特定领域的训练数据或明确界定的世界模型训练。

> Effective extraction of the world knowledge in LLMs for complex decision-making tasks remains a challenge. We propose a framework PIANIST for decomposing the world model into seven intuitive components conducive to zero-shot LLM generation. Given only the natural language description of the game and how input observations are formatted, our method can generate a working world model for fast and efficient MCTS simulation. We show that our method works well on two different games that challenge the planning and decision making skills of the agent for both language and non-language based action taking, without any training on domain-specific training data or explicitly defined world model.

[Arxiv](https://arxiv.org/abs/2411.15998)