# WikiCausal：构建因果知识图谱的语料库与评估框架

发布时间：2024年08月30日

`LLM应用` `知识图谱` `人工智能`

> WikiCausal: Corpus and Evaluation Framework for Causal Knowledge Graph Construction

# 摘要

> 近期，构建通用及特定领域因果知识图谱的研究热度攀升。这些图谱助力因果推理与事件预测，应用广泛。虽自动化构建技术进步显著，但评估多聚焦于基础任务或依赖小规模手动评估。本文提出了一套因果知识图谱构建的语料库、任务与评估体系。语料库涵盖维基百科中与事件相关概念的文章。任务是提取事件间的因果关系。评估结合维基数据现有因果关系与大型语言模型，确保高效且无需人工介入。我们验证了基于神经模型的构建流程，并展示了如何利用这套体系精准选模。相关资源已公开。

> Recently, there has been an increasing interest in the construction of general-domain and domain-specific causal knowledge graphs. Such knowledge graphs enable reasoning for causal analysis and event prediction, and so have a range of applications across different domains. While great progress has been made toward automated construction of causal knowledge graphs, the evaluation of such solutions has either focused on low-level tasks (e.g., cause-effect phrase extraction) or on ad hoc evaluation data and small manual evaluations. In this paper, we present a corpus, task, and evaluation framework for causal knowledge graph construction. Our corpus consists of Wikipedia articles for a collection of event-related concepts in Wikidata. The task is to extract causal relations between event concepts from the corpus. The evaluation is performed in part using existing causal relations in Wikidata to measure recall, and in part using Large Language Models to avoid the need for manual or crowd-sourced evaluation. We evaluate a pipeline for causal knowledge graph construction that relies on neural models for question answering and concept linking, and show how the corpus and the evaluation framework allow us to effectively find the right model for each task. The corpus and the evaluation framework are publicly available.

[Arxiv](https://arxiv.org/abs/2409.00331)