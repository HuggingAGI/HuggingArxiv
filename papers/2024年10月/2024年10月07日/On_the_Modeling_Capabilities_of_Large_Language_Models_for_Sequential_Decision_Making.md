# 探讨大型语言模型在顺序决策中的建模潜力

发布时间：2024年10月07日

`Agent` `人工智能`

> On the Modeling Capabilities of Large Language Models for Sequential Decision Making

# 摘要

> 大型预训练模型在跨模态的推理和规划任务中表现日益优异，为解决复杂序列决策问题提供了新思路。本文探讨了大型语言模型（LLM）在多领域交互环境中的强化学习能力。我们评估了它们直接生成策略或间接通过构建奖励模型来训练代理的能力。结果表明，即使未经特定任务微调，LLM 在奖励建模上表现卓越。特别是，通过 AI 反馈设计奖励的方法最为通用，能通过优化信用分配和探索提升性能。此外，在不熟悉的环境中，利用合成数据微调 LLM 不仅能显著增强其奖励建模能力，还能避免灾难性遗忘，进一步拓宽其在序列决策任务中的应用前景。

> Large pretrained models are showing increasingly better performance in reasoning and planning tasks across different modalities, opening the possibility to leverage them for complex sequential decision making problems. In this paper, we investigate the capabilities of Large Language Models (LLMs) for reinforcement learning (RL) across a diversity of interactive domains. We evaluate their ability to produce decision-making policies, either directly, by generating actions, or indirectly, by first generating reward models to train an agent with RL. Our results show that, even without task-specific fine-tuning, LLMs excel at reward modeling. In particular, crafting rewards through artificial intelligence (AI) feedback yields the most generally applicable approach and can enhance performance by improving credit assignment and exploration. Finally, in environments with unfamiliar dynamics, we explore how fine-tuning LLMs with synthetic data can significantly improve their reward modeling capabilities while mitigating catastrophic forgetting, further broadening their utility in sequential decision-making tasks.

[Arxiv](https://arxiv.org/abs/2410.05656)