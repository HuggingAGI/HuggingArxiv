# 实体分解结合过滤技术，开创了一种零-shot 临床命名实体识别的新框架。

发布时间：2024年07月05日

`LLM应用` `人工智能`

> Entity Decomposition with Filtering: A Zero-Shot Clinical Named Entity Recognition Framework

# 摘要

> 临床命名实体识别 (NER) 旨在从临床叙述中提取关键信息。最新研究表明，大型语言模型 (LLM) 在此领域表现出色。本文聚焦于开放 NER LLM，探讨其在临床 NER 中的应用。我们提出了一种创新框架——带过滤的实体分解 (EDF)，通过将任务分解为子实体类型检索，并结合过滤机制剔除错误实体，显著提升了识别准确性。实验证明，EDF 在各项评估中均表现优异。此外，我们进行了详尽的错误分析，为后续研究奠定了基础。

> Clinical named entity recognition (NER) aims to retrieve important entities within clinical narratives. Recent works have demonstrated that large language models (LLMs) can achieve strong performance in this task. While previous works focus on proprietary LLMs, we investigate how open NER LLMs, trained specifically for entity recognition, perform in clinical NER. In this paper, we aim to improve them through a novel framework, entity decomposition with filtering, or EDF. Our key idea is to decompose the entity recognition task into several retrievals of sub-entity types. We also introduce a filtering mechanism to remove incorrect entities. Our experimental results demonstrate the efficacy of our framework across all metrics, models, datasets, and entity types. Our analysis reveals that entity decomposition can recognize previously missed entities with substantial improvement. We further provide a comprehensive evaluation of our framework and an in-depth error analysis to pave future works.

[Arxiv](https://arxiv.org/abs/2407.04629)