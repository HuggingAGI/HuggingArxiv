# RLPF：利用预测反馈进行用户摘要的强化学习，结合大型语言模型技术。

发布时间：2024年09月06日

`LLM应用` `个性化系统` `机器学习`

> RLPF: Reinforcement Learning from Prediction Feedback for User Summarization with LLMs

# 摘要

> LLM驱动的个性化系统通过分析用户历史行为来预测其未来行为。然而，这些系统的有效性很大程度上依赖于如何处理庞大且嘈杂的用户历史数据。现有的LLM虽然能生成简洁的摘要，但往往缺乏下游任务所需的上下文信息。为此，我们提出了预测反馈强化学习（RLPF），它通过微调LLM生成既简洁又富含信息的摘要，从而优化下游任务表现。实验结果显示，RLPF不仅在下游任务性能上提升了22%，还在摘要的事实性、抽象性和可读性上达到了84.59%的胜率。此外，RLPF在减少74%上下文长度的同时，仍能在19个未见任务中的16个上提升性能，显示出其强大的通用性。这一方法为将复杂用户历史转化为实用信息提供了新途径，有望大幅提升LLM在个性化应用中的表现。

> LLM-powered personalization agent systems employ Large Language Models (LLMs) to predict users' behavior from their past activities. However, their effectiveness often hinges on the ability to effectively leverage extensive, long user historical data due to its inherent noise and length of such data. Existing pretrained LLMs may generate summaries that are concise but lack the necessary context for downstream tasks, hindering their utility in personalization systems. To address these challenges, we introduce Reinforcement Learning from Prediction Feedback (RLPF). RLPF fine-tunes LLMs to generate concise, human-readable user summaries that are optimized for downstream task performance. By maximizing the usefulness of the generated summaries, RLPF effectively distills extensive user history data while preserving essential information for downstream tasks. Our empirical evaluation demonstrates significant improvements in both extrinsic downstream task utility and intrinsic summary quality, surpassing baseline methods by up to 22% on downstream task performance and achieving an up to 84.59% win rate on Factuality, Abstractiveness, and Readability. RLPF also achieves a remarkable 74% reduction in context length while improving performance on 16 out of 19 unseen tasks and/or datasets, showcasing its generalizability. This approach offers a promising solution for enhancing LLM personalization by effectively transforming long, noisy user histories into informative and human-readable representations.

[Arxiv](https://arxiv.org/abs/2409.04421)