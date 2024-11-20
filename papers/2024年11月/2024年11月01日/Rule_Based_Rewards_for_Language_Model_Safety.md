# 语言模型安全的基于规则的奖励

发布时间：2024年11月01日

`LLM应用` `人工智能`

> Rule Based Rewards for Language Model Safety

# 摘要

> 基于人类偏好对大型语言模型（LLMs）进行强化学习微调，已证实能提升其能力与安全表现。然而，在涉及安全的情形中，若未给人类标注员提供精准指示，所收集的数据可能致使模型过度谨慎，或以不良方式回应，比如进行评判。另外，随着模型能力和使用模式的变化，可能得耗费大量成本添加或重新标注数据来修正安全行为。我们提出了一种创新的偏好建模方法，它借助人工智能反馈，且仅需少量人类数据。我们的方法，即基于规则的奖励（RBR），运用一组期望或不期望的行为规则（比如拒绝不应带有评判性）以及一个LLM评分器。与先前使用人工智能反馈的方法不同，我们的方法在RL训练中直接将细粒度、可组合、由LLM评分的少量示例提示用作奖励，从而在控制、准确性和更新便利性方面更具优势。我们证明，RBR是一种有效的训练方法，F1分数达97.1，而人类反馈基线为91.7，通过更优地平衡有用性和安全性，实现了更高的安全行为准确率。

> Reinforcement learning based fine-tuning of large language models (LLMs) on human preferences has been shown to enhance both their capabilities and safety behavior. However, in cases related to safety, without precise instructions to human annotators, the data collected may cause the model to become overly cautious, or to respond in an undesirable style, such as being judgmental. Additionally, as model capabilities and usage patterns evolve, there may be a costly need to add or relabel data to modify safety behavior. We propose a novel preference modeling approach that utilizes AI feedback and only requires a small amount of human data. Our method, Rule Based Rewards (RBR), uses a collection of rules for desired or undesired behaviors (e.g. refusals should not be judgmental) along with a LLM grader. In contrast to prior methods using AI feedback, our method uses fine-grained, composable, LLM-graded few-shot prompts as reward directly in RL training, resulting in greater control, accuracy and ease of updating. We show that RBRs are an effective training method, achieving an F1 score of 97.1, compared to a human-feedback baseline of 91.7, resulting in much higher safety-behavior accuracy through better balancing usefulness and safety.

[Arxiv](https://arxiv.org/abs/2411.01111)