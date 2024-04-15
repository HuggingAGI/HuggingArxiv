# 针对大型语言模型，采用数据增强技术进行方言适配。

发布时间：2024年04月11日

`LLM应用` `南斯拉夫方言`

> Data-Augmentation-Based Dialectal Adaptation for LLMs

# 摘要

> 本报告展示了 GMUNLP 在 VarDial 2024 的 Dialect-Copa 任务中的参与情况，该任务旨在测试大型语言模型（LLMs）对南斯拉夫微型方言的常识推理能力。我们探索了 LLMs 在处理非标准方言方面的表现，尽管它们在标准语言上已有出色表现。我们采用了一种融合各类语言模型优势的方法，并通过数据增强技术提升了对 Chakavian、Cherkano 和 Torlak 三种方言的处理能力。通过使用专注于语言家族的编码器模型（BERTić）和多领域通用的多语言模型（AYA-101），我们的实验结果显示，这些数据增强技术在开源模型的三个测试数据集中均显著提高了性能。这一研究不仅展示了数据增强的实用性，也证明了 LLMs 在处理非标准方言方面的潜力，为推动方言和低资源环境下的自然语言理解做出了贡献。代码链接：https://github.com/ffaisal93/dialect_copa

> This report presents GMUNLP's participation to the Dialect-Copa shared task at VarDial 2024, which focuses on evaluating the commonsense reasoning capabilities of large language models (LLMs) on South Slavic micro-dialects. The task aims to assess how well LLMs can handle non-standard dialectal varieties, as their performance on standard languages is already well-established. We propose an approach that combines the strengths of different types of language models and leverages data augmentation techniques to improve task performance on three South Slavic dialects: Chakavian, Cherkano, and Torlak. We conduct experiments using a language-family-focused encoder-based model (BERTić) and a domain-agnostic multilingual model (AYA-101). Our results demonstrate that the proposed data augmentation techniques lead to substantial performance gains across all three test datasets in the open-source model category. This work highlights the practical utility of data augmentation and the potential of LLMs in handling non-standard dialectal varieties, contributing to the broader goal of advancing natural language understanding in low-resource and dialectal settings. Code:https://github.com/ffaisal93/dialect_copa

[Arxiv](https://arxiv.org/abs/2404.08092)