# 强烈的偏好会削弱价值对齐的稳健性

发布时间：2024年10月03日

`LLM理论` `人工智能`

> Strong Preferences Affect the Robustness of Value Alignment

# 摘要

> 价值对齐旨在确保大型语言模型 (LLM) 和其他 AI 代理的行为符合人类价值观，这对系统的安全性和可信度至关重要。本文通过分析偏好模型的敏感性，探讨了价值对齐的稳健性。我们发现，在 Bradley-Terry 和 Placket-Luce 模型中，当某些偏好占主导地位时，其概率变化会显著影响其他偏好的预测。我们确定了这些模型敏感性显著的特定条件，并讨论了这对 AI 系统中价值对齐的稳健性和安全性的实际影响。

> Value alignment, which aims to ensure that large language models (LLMs) and other AI agents behave in accordance with human values, is critical for ensuring safety and trustworthiness of these systems. A key component of value alignment is the modeling of human preferences as a representation of human values. In this paper, we investigate the robustness of value alignment by examining the sensitivity of preference models. Specifically, we ask: how do changes in the probabilities of some preferences affect the predictions of these models for other preferences? To answer this question, we theoretically analyze the robustness of widely used preference models by examining their sensitivities to minor changes in preferences they model. Our findings reveal that, in the Bradley-Terry and the Placket-Luce model, the probability of a preference can change significantly as other preferences change, especially when these preferences are dominant (i.e., with probabilities near 0 or 1). We identify specific conditions where this sensitivity becomes significant for these models and discuss the practical implications for the robustness and safety of value alignment in AI systems.

[Arxiv](https://arxiv.org/abs/2410.02451)