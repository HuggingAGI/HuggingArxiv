# RAG 会否在 LLM 中造成不公平？探讨检索增强生成系统中的公平性问题。

发布时间：2024年09月29日

`RAG` `人工智能` `公平性研究`

> Does RAG Introduce Unfairness in LLMs? Evaluating Fairness in Retrieval-Augmented Generation Systems

# 摘要

> RAG 在开放域问答任务中因其整合外部知识的能力而备受瞩目，但其处理公平性问题的能力仍不明朗，尤其是涉及性别、地理位置等敏感属性时。随着语言模型优先提升实用性，公平性常被忽视。RAG 的复杂性也使得识别和解决偏见变得困难。本文通过实证研究，提出一个针对 RAG 的公平性评估框架，分析不同人口统计属性间的差异。实验显示，尽管实用性有所提升，检索和生成阶段的公平性问题依然存在，呼吁在 RAG 管道中进行更有针对性的公平性干预。论文被接受后，我们将公开数据集和代码。

> RAG (Retrieval-Augmented Generation) have recently gained significant attention for their enhanced ability to integrate external knowledge sources in open-domain question answering (QA) tasks. However, it remains unclear how these models address fairness concerns, particularly with respect to sensitive attributes such as gender, geographic location, and other demographic factors. First, as language models evolve to prioritize utility, like improving exact match accuracy, fairness may have been largely overlooked. Second, RAG methods are complex pipelines, making it hard to identify and address biases, as each component is optimized for different goals. In this paper, we aim to empirically evaluate fairness in several RAG methods. We propose a fairness evaluation framework tailored to RAG methods, using scenario-based questions and analyzing disparities across demographic attributes. The experimental results indicate that, despite recent advances in utility-driven optimization, fairness issues persist in both the retrieval and generation stages, highlighting the need for more targeted fairness interventions within RAG pipelines. We will release our dataset and code upon acceptance of the paper.

[Arxiv](https://arxiv.org/abs/2409.19804)