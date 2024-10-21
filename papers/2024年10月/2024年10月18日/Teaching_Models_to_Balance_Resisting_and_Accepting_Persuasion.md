# 训练模型如何巧妙平衡抵抗与接受说服

发布时间：2024年10月18日

`LLM应用` `人工智能` `对话系统`

> Teaching Models to Balance Resisting and Accepting Persuasion

# 摘要

> 大型语言模型 (LLM) 容易受到说服的影响，尤其是在面对对抗性对话者时，这可能带来风险。我们首先提出防御模型免受说服影响的策略，并强调防御负面说服只是问题的一部分：模型还应能接受正面说服以提升答案质量。我们发现，仅优化一方会导致另一方表现不佳。为此，我们引入了说服平衡训练（PBT），通过多代理递归对话树生成数据，并利用偏好优化训练模型在适当时候接受说服。PBT 不仅提高了模型对错误信息的抵抗力，还增强了应对挑战的韧性，并在包含正面和负面说服的综合数据上表现最佳。此外，PBT 模型在多代理辩论中表现更佳，成为更可靠的队友。在没有 PBT 的情况下，强弱模型配对的表现不稳定，答案呈现顺序决定了团队表现。而 PBT 则带来了更稳定、更少依赖顺序的结果，强模型始终能带动弱模型提升。

> Large language models (LLMs) are susceptible to persuasion, which can pose risks when models are faced with an adversarial interlocutor. We take a first step towards defending models against persuasion while also arguing that defense against adversarial (i.e. negative) persuasion is only half of the equation: models should also be able to accept beneficial (i.e. positive) persuasion to improve their answers. We show that optimizing models for only one side results in poor performance on the other. In order to balance positive and negative persuasion, we introduce Persuasion-Balanced Training (or PBT), which leverages multi-agent recursive dialogue trees to create data and trains models via preference optimization to accept persuasion when appropriate. PBT consistently improves resistance to misinformation and resilience to being challenged while also resulting in the best overall performance on holistic data containing both positive and negative persuasion. Crucially, we show that PBT models are better teammates in multi-agent debates. We find that without PBT, pairs of stronger and weaker models have unstable performance, with the order in which the models present their answers determining whether the team obtains the stronger or weaker model's performance. PBT leads to better and more stable results and less order dependence, with the stronger model consistently pulling the weaker one up.

[Arxiv](https://arxiv.org/abs/2410.14596)