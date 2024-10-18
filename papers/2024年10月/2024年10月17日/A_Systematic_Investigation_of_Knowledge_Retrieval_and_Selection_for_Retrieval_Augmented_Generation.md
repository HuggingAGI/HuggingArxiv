# 系统性探究知识检索与选择，助力增强生成技术

发布时间：2024年10月17日

`RAG` `人工智能`

> A Systematic Investigation of Knowledge Retrieval and Selection for Retrieval Augmented Generation

# 摘要

> RAG 通过整合外部知识，已成为提升自然语言生成的强大工具。尽管改进知识检索对生成质量至关重要，但知识选择的作用仍不明确。本文深入分析了知识检索与选择对 RAG 系统下游生成性能的影响。通过模拟不同检索与选择条件，我们发现生成器模型能力及任务复杂性显著影响 RAG 性能。在典型情况下，提升知识召回率是关键，而强大生成器模型在清晰任务中，知识选择器作用有限。然而，对于较弱模型或模糊任务，知识 F1 分数及选择器的作用则更为显著。

> Retrieval-augmented generation (RAG) has emerged as a powerful method for enhancing natural language generation by integrating external knowledge into a model's output. While prior work has demonstrated the importance of improving knowledge retrieval for boosting generation quality, the role of knowledge selection remains less clear. In this paper, we perform a comprehensive analysis of how knowledge retrieval and selection influence downstream generation performance in RAG systems. By simulating different retrieval and selection conditions through a controlled mixture of gold and distractor knowledge, we assess the impact of these factors on generation outcomes. Our findings indicate that the downstream generator model's capability, as well as the complexity of the task and dataset, significantly influence the impact of knowledge retrieval and selection on the overall RAG system performance. In typical scenarios, improving the knowledge recall score is key to enhancing generation outcomes, with the knowledge selector providing a limited additional benefit when a strong generator model is used on clear, well-defined tasks. For weaker generator models or more ambiguous tasks and datasets, the knowledge F1 score becomes a critical factor, and the knowledge selector plays a more prominent role in improving overall performance.

[Arxiv](https://arxiv.org/abs/2410.13258)