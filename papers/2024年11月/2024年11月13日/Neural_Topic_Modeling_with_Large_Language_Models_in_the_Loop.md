# 在循环中使用大型语言模型的神经主题建模

发布时间：2024年11月13日

`LLM应用` `主题建模`

> Neural Topic Modeling with Large Language Models in the Loop

# 摘要

> 主题建模是自然语言处理中的一项基本任务，允许在文本语料库中发现潜在的主题结构。虽然大型语言模型（LLM）在主题发现方面展示了有前景的能力，但它们直接应用于主题建模存在诸如主题覆盖不完整、主题不对齐和效率低下等问题。为了解决这些限制，我们提出了 LLM-ITL，这是一种新颖的 LLM 循环框架，将 LLM 与许多现有的神经主题模型（NTM）集成在一起。在 LLM-ITL 中，全局主题和文档表示通过 NTM 学习，而 LLM 通过基于置信度加权的最优传输（OT）对齐目标来优化主题。这个过程增强了所学习主题的可解释性和连贯性，同时保持了 NTM 的效率。大量实验表明，LLM-ITL 可以帮助 NTM 在保持文档表示质量的同时显著提高其主题可解释性。

> Topic modeling is a fundamental task in natural language processing, allowing the discovery of latent thematic structures in text corpora. While Large Language Models (LLMs) have demonstrated promising capabilities in topic discovery, their direct application to topic modeling suffers from issues such as incomplete topic coverage, misalignment of topics, and inefficiency. To address these limitations, we propose LLM-ITL, a novel LLM-in-the-loop framework that integrates LLMs with many existing Neural Topic Models (NTMs). In LLM-ITL, global topics and document representations are learned through the NTM, while an LLM refines the topics via a confidence-weighted Optimal Transport (OT)-based alignment objective. This process enhances the interpretability and coherence of the learned topics, while maintaining the efficiency of NTMs. Extensive experiments demonstrate that LLM-ITL can help NTMs significantly improve their topic interpretability while maintaining the quality of document representation.

[Arxiv](https://arxiv.org/abs/2411.08534)