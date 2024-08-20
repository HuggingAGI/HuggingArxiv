# 大型语言模型的性能法则

发布时间：2024年08月19日

`LLM理论` `人工智能` `教育评估`

> Performance Law of Large Language Models

# 摘要

> 在规模法则的指导下，大型语言模型（LLMs）近年来表现卓越。然而，规模法则仅提供损失的定性估计，受多种因素影响。因此，在实际应用中，评估不同训练设置下LLMs的真实性能至关重要。本文介绍了一种名为“性能法则”的经验方程，它能直接预测LLM的MMLU分数，这是衡量LLM在实际应用中能力的重要指标。通过分析LLM架构的关键超参数和训练数据规模，我们能精确预测不同LLMs的MMLU分数。这一法则有助于优化LLM架构选择和计算资源分配，无需繁琐实验。

> Guided by the belief of the scaling law, large language models (LLMs) have achieved impressive performance in recent years. However, scaling law only gives a qualitative estimation of loss, which is influenced by various factors such as model architectures, data distributions, tokenizers, and computation precision. Thus, estimating the real performance of LLMs with different training settings rather than loss may be quite useful in practical development. In this article, we present an empirical equation named "Performance Law" to directly predict the MMLU score of an LLM, which is a widely used metric to indicate the general capability of LLMs in real-world conversations and applications. Based on only a few key hyperparameters of the LLM architecture and the size of training data, we obtain a quite accurate MMLU prediction of various LLMs with diverse sizes and architectures developed by different organizations in different years. Performance law can be used to guide the choice of LLM architecture and the effective allocation of computational resources without extensive experiments.

[Arxiv](https://arxiv.org/abs/2408.09895)