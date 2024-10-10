# 长上下文 LLM 与 RAG 相遇：解决 RAG 中长输入的难题

发布时间：2024年10月08日

`RAG` `人工智能`

> Long-Context LLMs Meet RAG: Overcoming Challenges for Long Inputs in RAG

# 摘要

> RAG 让 LLM 能够利用外部知识源，随着 LLM 处理长输入序列的能力增强，提供更多检索信息成为可能，从而提升生成质量。然而，实证发现，长上下文 LLM 的生成质量在检索段落增多时先升后降。本文揭示了“硬负样本”的关键影响，并提出无训练与基于训练的方法来增强 RAG 的鲁棒性。我们展示了检索重排序的简单高效，并探索了 RAG 特定微调与推理导向微调，以显著提升性能。最后，系统分析了这些方法的设计选择，包括数据分布、检索器选择及训练上下文长度。

> Retrieval-augmented generation (RAG) empowers large language models (LLMs) to utilize external knowledge sources. The increasing capacity of LLMs to process longer input sequences opens up avenues for providing more retrieved information, to potentially enhance the quality of generated outputs. It is plausible to assume that a larger retrieval set would contain more relevant information (higher recall), that might result in improved performance. However, our empirical findings demonstrate that for many long-context LLMs, the quality of generated output initially improves first, but then subsequently declines as the number of retrieved passages increases. This paper investigates this phenomenon, identifying the detrimental impact of retrieved "hard negatives" as a key contributor. To mitigate this and enhance the robustness of long-context LLM-based RAG, we propose both training-free and training-based approaches. We first showcase the effectiveness of retrieval reordering as a simple yet powerful training-free optimization. Furthermore, we explore training-based methods, specifically RAG-specific implicit LLM fine-tuning and RAG-oriented fine-tuning with intermediate reasoning, demonstrating their capacity for substantial performance gains. Finally, we conduct a systematic analysis of design choices for these training-based methods, including data distribution, retriever selection, and training context length.

[Arxiv](https://arxiv.org/abs/2410.05983)