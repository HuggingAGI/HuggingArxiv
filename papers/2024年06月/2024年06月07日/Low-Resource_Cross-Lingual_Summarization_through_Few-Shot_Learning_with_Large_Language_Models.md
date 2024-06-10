# 借助大型语言模型的少样本学习，实现低资源条件下的跨语言摘要

发布时间：2024年06月07日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）在跨语言摘要（XLS）任务中的少-shot学习性能，特别是在资源有限的环境下。研究了包括Mistral-7B-Instruct-v0.2、GPT-3.5和GPT-4在内的多种模型的表现，并强调了通过少-shot学习优化XLS性能的潜力。这属于LLM在特定应用场景下的性能研究和优化，因此归类为LLM应用。` `跨语言处理`

> Low-Resource Cross-Lingual Summarization through Few-Shot Learning with Large Language Models

# 摘要

> 跨语言摘要（XLS）旨在从源语言文档生成另一种语言的摘要。尽管大型语言模型（LLMs）已展现出零-shot XLS 的潜力，但其在少-shot 环境下的表现，尤其是在资源匮乏、平行数据有限的情况下，仍未得到充分探索。本文探讨了包括 Mistral-7B-Instruct-v0.2、GPT-3.5 和 GPT-4 在内的多种模型的少-shot XLS 性能。实验结果显示，少-shot 学习显著提升了 LLMs，尤其是 GPT-3.5 和 GPT-4 在资源有限环境下的 XLS 性能。然而，开源模型 Mistral-7B-Instruct-v0.2 在面对有限示例时适应性不足。本研究强调了通过少-shot 学习优化 XLS 性能的潜力，并呼吁针对此任务进一步研究 LLM 架构和预训练目标的设计。未来的研究方向包括探索更高效的少-shot 学习策略，以及研究 LLMs 在跨语言摘要中的迁移学习能力。

> Cross-lingual summarization (XLS) aims to generate a summary in a target language different from the source language document. While large language models (LLMs) have shown promising zero-shot XLS performance, their few-shot capabilities on this task remain unexplored, especially for low-resource languages with limited parallel data. In this paper, we investigate the few-shot XLS performance of various models, including Mistral-7B-Instruct-v0.2, GPT-3.5, and GPT-4. Our experiments demonstrate that few-shot learning significantly improves the XLS performance of LLMs, particularly GPT-3.5 and GPT-4, in low-resource settings. However, the open-source model Mistral-7B-Instruct-v0.2 struggles to adapt effectively to the XLS task with limited examples. Our findings highlight the potential of few-shot learning for improving XLS performance and the need for further research in designing LLM architectures and pre-training objectives tailored for this task. We provide a future work direction to explore more effective few-shot learning strategies and to investigate the transfer learning capabilities of LLMs for cross-lingual summarization.

[Arxiv](https://arxiv.org/abs/2406.04630)