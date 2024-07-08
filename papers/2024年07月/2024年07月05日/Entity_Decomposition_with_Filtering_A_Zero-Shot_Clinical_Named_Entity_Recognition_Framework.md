# 实体分解结合过滤技术，开创了一种零-shot 临床命名实体识别的新框架。

发布时间：2024年07月05日

`LLM应用` `人工智能`

> Entity Decomposition with Filtering: A Zero-Shot Clinical Named Entity Recognition Framework

# 摘要

> 临床命名实体识别（NER）任务中，大型语言模型（LLMs）表现出色。本文聚焦于开放NER LLMs，通过创新的带过滤的实体分解（EDF）框架，将复杂的实体识别任务简化为子实体类型的检索，并有效剔除错误实体。实验证明，EDF框架在各类评估中均表现优异，显著提升了对遗漏实体的识别能力。此外，我们还进行了详尽的评估与错误分析，为后续研究奠定基础。

> Clinical named entity recognition (NER) aims to retrieve important entities within clinical narratives. Recent works have demonstrated that large language models (LLMs) can achieve strong performance in this task. While previous works focus on proprietary LLMs, we investigate how open NER LLMs, trained specifically for entity recognition, perform in clinical NER. In this paper, we aim to improve them through a novel framework, entity decomposition with filtering, or EDF. Our key idea is to decompose the entity recognition task into several retrievals of sub-entity types. We also introduce a filtering mechanism to remove incorrect entities. Our experimental results demonstrate the efficacy of our framework across all metrics, models, datasets, and entity types. Our analysis reveals that entity decomposition can recognize previously missed entities with substantial improvement. We further provide a comprehensive evaluation of our framework and an in-depth error analysis to pave future works.

[Arxiv](https://arxiv.org/abs/2407.04629)