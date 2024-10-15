# MIRAGE：探索与揭示语言模型中的归纳推理奥秘

发布时间：2024年10月12日

`LLM理论` `人工智能` `数据科学`

> MIRAGE: Evaluating and Explaining Inductive Reasoning Process in Language Models

# 摘要

> 归纳推理是 LLM 提升智能的关键，要求模型从观察中提炼规则并应用于新案例。我们推出的 {\scshape Mirage} 数据集，弥补了以往研究在全面评估和灵活测试数据上的不足。通过在输入分布、任务场景和难度上的灵活调整，我们深入分析了影响 LLM 归纳推理的因素，发现 LLM 在规则推理上表现不佳，常在不依赖正确规则的情况下进行推理。然而，LLM 在基于邻居的推理上表现出色，通过关注特征空间中相近的观察事实，模型在局部区域内展现出强大的归纳能力，显著提升了演绎性能。

> Inductive reasoning is an essential capability for large language models (LLMs) to achieve higher intelligence, which requires the model to generalize rules from observed facts and then apply them to unseen examples. We present {\scshape Mirage}, a synthetic dataset that addresses the limitations of previous work, specifically the lack of comprehensive evaluation and flexible test data. In it, we evaluate LLMs' capabilities in both the inductive and deductive stages, allowing for flexible variation in input distribution, task scenario, and task difficulty to analyze the factors influencing LLMs' inductive reasoning. Based on these multi-faceted evaluations, we demonstrate that the LLM is a poor rule-based reasoner. In many cases, when conducting inductive reasoning, they do not rely on a correct rule to answer the unseen case. From the perspectives of different prompting methods, observation numbers, and task forms, models tend to consistently conduct correct deduction without correct inductive rules. Besides, we find that LLMs are good neighbor-based reasoners. In the inductive reasoning process, the model tends to focus on observed facts that are close to the current test example in feature space. By leveraging these similar examples, the model maintains strong inductive capabilities within a localized region, significantly improving its deductive performance.

[Arxiv](https://arxiv.org/abs/2410.09542)