# 探究在低资源环境下，语言模型在提取式问答任务中的泛化表现。

发布时间：2024年09月27日

`LLM应用`

> Exploring Language Model Generalization in Low-Resource Extractive QA

# 摘要

> 本文探讨了在领域漂移情况下，大型语言模型（LLMs）在提取式问答（EQA）中的表现，特别是它们能否在无需额外领域训练的情况下，零-shot泛化到需要专业知识的封闭领域，如医学和法律。通过一系列实验，我们揭示了性能差距的原因：LLMs在处理封闭领域的长答案检索时表现不佳；某些模型虽整体表现出色，但在区分领域特定词汇含义上存在不足；扩大模型参数并不总能提升跨领域泛化能力；封闭领域数据集与开放领域EQA数据集差异显著，LLMs难以应对。这些发现为改进现有LLMs提供了重要方向。

> In this paper, we investigate Extractive Question Answering (EQA) with Large Language Models (LLMs) under domain drift, i.e., can LLMs generalize well to closed-domains that require specific knowledge such as medicine and law in a zero-shot fashion without additional in-domain training? To this end, we devise a series of experiments to empirically explain the performance gap. Our findings suggest that: a) LLMs struggle with dataset demands of closed-domains such as retrieving long answer-spans; b) Certain LLMs, despite showing strong overall performance, display weaknesses in meeting basic requirements as discriminating between domain-specific senses of words which we link to pre-processing decisions; c) Scaling model parameters is not always effective for cross-domain generalization; and d) Closed-domain datasets are quantitatively much different than open-domain EQA datasets and current LLMs struggle to deal with them. Our findings point out important directions for improving existing LLMs.

[Arxiv](https://arxiv.org/abs/2409.18446)