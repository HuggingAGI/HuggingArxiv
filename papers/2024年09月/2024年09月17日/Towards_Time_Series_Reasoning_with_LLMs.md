# 迈向 LLM 驱动的时间序列推理

发布时间：2024年09月17日

`LLM应用` `时间序列分析` `人工智能`

> Towards Time Series Reasoning with LLMs

# 摘要

> 多模态大型语言模型（MLLM）在视觉等领域取得了显著进展，但在时间序列领域尚未取得同样广泛的成功。尽管已有研究在时间序列预测方面表现出色，但如何利用LLM进行自然语言中的时间序列推理仍鲜有探讨。我们提出了一种创新的多模态时间序列LLM方法，该方法通过强大的零-shot性能，跨领域学习可泛化的信息。首先，我们在LLM基础上训练一个轻量级的时间序列编码器，直接提取时间序列信息。接着，通过链式思维增强的时间序列任务微调模型，促使模型生成推理路径。实验表明，我们的模型不仅学习了反映时间序列特征（如斜率、频率）的潜在表示，还在多种领域的零-shot推理任务中超越了GPT-4o。

> Multi-modal large language models (MLLMs) have enabled numerous advances in understanding and reasoning in domains like vision, but we have not yet seen this broad success for time-series. Although prior works on time-series MLLMs have shown promising performance in time-series forecasting, very few works show how an LLM could be used for time-series reasoning in natural language. We propose a novel multi-modal time-series LLM approach that learns generalizable information across various domains with powerful zero-shot performance. First, we train a lightweight time-series encoder on top of an LLM to directly extract time-series information. Then, we fine-tune our model with chain-of-thought augmented time-series tasks to encourage the model to generate reasoning paths. We show that our model learns a latent representation that reflects specific time-series features (e.g. slope, frequency), as well as outperforming GPT-4o on a set of zero-shot reasoning tasks on a variety of domains.

[Arxiv](https://arxiv.org/abs/2409.11376)