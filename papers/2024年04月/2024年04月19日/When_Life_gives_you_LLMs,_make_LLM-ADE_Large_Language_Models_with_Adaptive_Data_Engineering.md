# 生活赋予你大型语言模型（LLMs），便创造 LLM-ADE：融入自适应数据工程的先进语言模型。

发布时间：2024年04月19日

`LLM理论` `人工智能` `机器学习`

> When Life gives you LLMs, make LLM-ADE: Large Language Models with Adaptive Data Engineering

# 摘要

> 本研究介绍了 LLM-ADE 框架，这是一种创新的持续预训练大型语言模型（LLMs）的方法，有效应对了灾难性遗忘和性能双重下降的问题。该框架通过动态调整架构，如选择性冻结和扩展模块，来适应不同的数据集，从而在吸收新知识的同时，保留已有的知识储备。我们在 TinyLlama 模型上对 LLM-ADE 进行了验证，通过多项通用知识测试，证实了其在性能上的显著提升，并避免了传统持续训练方法的不足。这一策略为保持 LLMs 在实际应用中的前沿性和高效性，提供了一种更为灵活和强大的解决方案。

> This paper presents the LLM-ADE framework, a novel methodology for continued pre-training of large language models (LLMs) that addresses the challenges of catastrophic forgetting and double descent. LLM-ADE employs dynamic architectural adjustments, including selective block freezing and expansion, tailored to specific datasets. This strategy enhances model adaptability to new data while preserving previously acquired knowledge. We demonstrate LLM-ADE's effectiveness on the TinyLlama model across various general knowledge benchmarks, showing significant performance improvements without the drawbacks of traditional continuous training methods. This approach promises a more versatile and robust way to keep LLMs current and efficient in real-world applications.

[Arxiv](https://arxiv.org/abs/2404.13028)