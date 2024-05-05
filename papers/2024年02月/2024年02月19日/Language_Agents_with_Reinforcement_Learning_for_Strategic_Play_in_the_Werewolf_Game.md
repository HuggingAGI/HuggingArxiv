# 通过强化学习训练的语言代理，能够在狼人杀这一策略游戏中发挥出色的作用。

发布时间：2024年02月19日

`Agent` `人工智能`

> Language Agents with Reinforcement Learning for Strategic Play in the Werewolf Game

# 摘要

> 基于大型语言模型（LLM）的智能体在多元领域内展现出巨大潜力。但在复杂的决策制定任务中，纯粹的LLM智能体往往在其选择的行动中表现出内在偏见，这种偏见源自模型的训练数据，导致表现不尽人意。为了培育出既能够灵活运用语言行动又具备卓越决策力的战略性语言智能体，我们提出了一个创新框架，该框架利用强化学习（RL）技术赋予LLM智能体新动力。我们以广受欢迎的社交推理游戏“狼人杀”作为测试平台，它考验的是智能体的沟通多样性和策略游戏技巧。我们的智能体利用LLM进行逻辑推理，提出多样化的行动选项，随后一个经过特别训练以提升决策能力的RL策略会从这些选项中挑选出最佳行动来参与游戏。大量实验证明，我们的智能体成功克服了内在偏见，在“狼人杀”游戏中的表现超越了传统LLM智能体。此外，我们还进行了人机对比实验，发现我们的智能体不仅达到了人类的水平，而且在策略运用上表现出色。

> Agents built with large language models (LLMs) have shown great potential across a wide range of domains. However, in complex decision-making tasks, pure LLM-based agents tend to exhibit intrinsic bias in their choice of actions, which is inherited from the model's training data and results in suboptimal performance. To develop strategic language agents, i.e., agents that generate flexible language actions and possess strong decision-making abilities, we propose a novel framework that powers LLM-based agents with reinforcement learning (RL). We consider Werewolf, a popular social deduction game, as a challenging testbed that emphasizes versatile communication and strategic gameplay. To mitigate the intrinsic bias in language actions, our agents use an LLM to perform deductive reasoning and generate a diverse set of action candidates. Then an RL policy trained to optimize the decision-making ability chooses an action from the candidates to play in the game. Extensive experiments show that our agents overcome the intrinsic bias and outperform existing LLM-based agents in the Werewolf game. We also conduct human-agent experiments and find that our agents achieve human-level performance and demonstrate strong strategic play.

[Arxiv](https://arxiv.org/abs/2310.18940)