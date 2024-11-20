# ReverseNER：一个用于大型语言模型零样本命名实体识别的自生成示例驱动式框架

发布时间：2024年11月01日

`LLM应用` `命名实体识别`

> ReverseNER: A Self-Generated Example-Driven Framework for Zero-Shot Named Entity Recognition with Large Language Models

# 摘要

> 这篇论文呈现了 ReverseNER 框架，旨在攻克大型语言模型（LLMs）于零样本命名实体识别（NER）任务里的局限，尤其是在某些实体类型边界含混的情形中。ReverseNER 借助构建具备 NER 逆流程的可靠示例库来应对此挑战。该方法并非由句子起始，而是运用 LLM 依据实体定义生成实体，再将其拓展为完整句子。在句子生成期间，通过从任务句子聚类提取特定的“特征句子”，引导 LLM 复制其结构。这造就了带有清晰标注实体、同时保留与任务句子语义和结构相似性的良好注释句子。示例库构建完成后，该方法为每个任务句子选取语义最相近的示例标签，以支撑 LLM 的推断。我们还提议了一种实体级自一致性评分机制，用以提升 LLM 的 NER 表现。实验显示，ReverseNER 在 LLMs 的零样本 NER 中大幅超越传统方法，且胜过若干少样本方法，在标记数据有限的领域中实现了 NER 的显著提升。

> This paper presents ReverseNER, a framework aimed at overcoming the limitations of large language models (LLMs) in zero-shot Named Entity Recognition (NER) tasks, particularly in cases where certain entity types have ambiguous boundaries. ReverseNER tackles this challenge by constructing a reliable example library with the reversed process of NER. Rather than beginning with sentences, this method uses an LLM to generate entities based on their definitions and then expands them into full sentences. During sentence generation, the LLM is guided to replicate the structure of a specific 'feature sentence', extracted from the task sentences by clustering. This results in well-annotated sentences with clearly labeled entities, while preserving semantic and structural similarity to the task sentences. Once the example library is constructed, the method selects the most semantically similar example labels for each task sentence to support the LLM's inference. We also propose an entity-level self-consistency scoring mechanism to improve NER performance with LLMs. Experiments show that ReverseNER significantly outperforms traditional zero-shot NER with LLMs and surpasses several few-shot methods, marking a notable improvement in NER for domains with limited labeled data.

[Arxiv](https://arxiv.org/abs/2411.00533)