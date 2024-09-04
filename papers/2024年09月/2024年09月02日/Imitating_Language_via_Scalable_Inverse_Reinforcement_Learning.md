# 借助可扩展的逆强化学习技术，实现语言的模仿

发布时间：2024年09月02日

`LLM理论` `人工智能` `机器学习`

> Imitating Language via Scalable Inverse Reinforcement Learning

# 摘要

> 语言模型的训练大多依赖于模仿学习，涵盖预训练和监督微调，并影响RLHF的初始条件。MLE因其简单性和可扩展性成为主流范式。然而，模仿学习的广泛领域能更有效利用自回归生成的序列结构。我们探索IRL视角，提取奖励并优化序列，评估其对大型模型微调的益处。我们提出新视角，将逆软Q学习重构为MLE的扩展，建立MLE与IRL的联系，平衡复杂性与性能、多样性。基于IRL的模仿在保持多样性的同时提升任务性能，使其成为SFT数据集上的有力选择，即使无在线数据生成。IRL提取的奖励函数通过更紧密整合监督与偏好，展现出更稳健的潜力。

> The majority of language model training builds on imitation learning. It covers pretraining, supervised fine-tuning, and affects the starting conditions for reinforcement learning from human feedback (RLHF). The simplicity and scalability of maximum likelihood estimation (MLE) for next token prediction led to its role as predominant paradigm. However, the broader field of imitation learning can more effectively utilize the sequential structure underlying autoregressive generation. We focus on investigating the inverse reinforcement learning (IRL) perspective to imitation, extracting rewards and directly optimizing sequences instead of individual token likelihoods and evaluate its benefits for fine-tuning large language models. We provide a new angle, reformulating inverse soft-Q-learning as a temporal difference regularized extension of MLE. This creates a principled connection between MLE and IRL and allows trading off added complexity with increased performance and diversity of generations in the supervised fine-tuning (SFT) setting. We find clear advantages for IRL-based imitation, in particular for retaining diversity while maximizing task performance, rendering IRL a strong alternative on fixed SFT datasets even without online data generation. Our analysis of IRL-extracted reward functions further indicates benefits for more robust reward functions via tighter integration of supervised and preference-based LLM post-training.

[Arxiv](https://arxiv.org/abs/2409.01369)