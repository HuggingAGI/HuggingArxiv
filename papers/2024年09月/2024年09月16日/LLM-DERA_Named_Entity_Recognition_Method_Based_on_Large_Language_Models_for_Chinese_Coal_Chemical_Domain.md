# LLM-DER：基于大型语言模型的中文煤炭化工领域命名实体识别新方法

发布时间：2024年09月16日

`LLM应用` `煤化工` `知识图谱`

> LLM-DER:A Named Entity Recognition Method Based on Large Language Models for Chinese Coal Chemical Domain

# 摘要

> 领域特定的命名实体识别 (NER) 对于构建领域知识图谱至关重要。尽管基于深度学习的方法在 NER 任务中表现出色，但其对大规模标注数据的依赖限制了其在特定领域的应用。为此，少样本方法应运而生，但面对复杂实体结构时仍显不足。以中国煤化工领域为例，复杂的实体关系使得传统方法难以应对。本文提出的 LLM-DER 框架，通过 LLM 生成实体关系列表并进行合理性评估，有效解决了这一难题。实验结果显示，LLM-DER 不仅超越了现有基线，还在全监督基线之上，证明了其在实体识别中的卓越性能。

> Domain-specific Named Entity Recognition (NER), whose goal is to recognize domain-specific entities and their categories, provides an important support for constructing domain knowledge graphs. Currently, deep learning-based methods are widely used and effective in NER tasks, but due to the reliance on large-scale labeled data. As a result, the scarcity of labeled data in a specific domain will limit its application.Therefore, many researches started to introduce few-shot methods and achieved some results. However, the entity structures in specific domains are often complex, and the current few-shot methods are difficult to adapt to NER tasks with complex features.Taking the Chinese coal chemical industry domain as an example,there exists a complex structure of multiple entities sharing a single entity, as well as multiple relationships for the same pair of entities, which affects the NER task under the sample less condition.In this paper, we propose a Large Language Models (LLMs)-based entity recognition framework LLM-DER for the domain-specific entity recognition problem in Chinese, which enriches the entity information by generating a list of relationships containing entity types through LLMs, and designing a plausibility and consistency evaluation method to remove misrecognized entities, which can effectively solve the complex structural entity recognition problem in a specific domain.The experimental results of this paper on the Resume dataset and the self-constructed coal chemical dataset Coal show that LLM-DER performs outstandingly in domain-specific entity recognition, not only outperforming the existing GPT-3.5-turbo baseline, but also exceeding the fully-supervised baseline, verifying its effectiveness in entity recognition.

[Arxiv](https://arxiv.org/abs/2409.10077)