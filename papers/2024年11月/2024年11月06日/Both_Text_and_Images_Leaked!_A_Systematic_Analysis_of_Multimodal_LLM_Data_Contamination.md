# 文本和图像都泄露了！对多模态 LLM 数据污染的系统分析

发布时间：2024年11月06日

`LLM应用` `多模态` `语言模型`

> Both Text and Images Leaked! A Systematic Analysis of Multimodal LLM Data Contamination

# 摘要

> 多模态大型语言模型（MLLMs）的快速发展在各种多模态基准测试中表现出了卓越的性能。然而，训练期间的数据污染问题给性能评估和比较带来了挑战。虽然存在许多用于检测大型语言模型（LLMs）中数据集污染的方法，但由于 MLLMs 的多种模态和多个训练阶段，这些方法对 MLLMs 效果较差。在本研究中，我们引入了一个专为 MLLMs 设计的多模态数据污染检测框架，MM-Detect。我们的实验结果表明，MM-Detect 对不同程度的污染敏感，并且能够突出由于多模态基准测试的训练集泄漏而带来的显著性能改进。此外，我们还探讨了 MLLMs 所使用的 LLM 的预训练阶段和 MLLMs 的微调阶段可能产生污染的可能性，为污染可能引入的阶段提供了新的见解。

> The rapid progression of multimodal large language models (MLLMs) has demonstrated superior performance on various multimodal benchmarks. However, the issue of data contamination during training creates challenges in performance evaluation and comparison. While numerous methods exist for detecting dataset contamination in large language models (LLMs), they are less effective for MLLMs due to their various modalities and multiple training phases. In this study, we introduce a multimodal data contamination detection framework, MM-Detect, designed for MLLMs. Our experimental results indicate that MM-Detect is sensitive to varying degrees of contamination and can highlight significant performance improvements due to leakage of the training set of multimodal benchmarks. Furthermore, We also explore the possibility of contamination originating from the pre-training phase of LLMs used by MLLMs and the fine-tuning phase of MLLMs, offering new insights into the stages at which contamination may be introduced.

[Arxiv](https://arxiv.org/abs/2411.03823)