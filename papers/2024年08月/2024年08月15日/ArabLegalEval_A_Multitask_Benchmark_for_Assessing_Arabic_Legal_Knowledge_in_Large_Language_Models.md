# ArabLegalEval：一项多任务基准，旨在评估大型语言模型对阿拉伯法律知识的掌握程度。

发布时间：2024年08月15日

`LLM应用` `人工智能`

> ArabLegalEval: A Multitask Benchmark for Assessing Arabic Legal Knowledge in Large Language Models

# 摘要

> 随着大型语言模型的飞速进步，自然语言处理任务取得了显著提升。然而，对于阿拉伯语等非英语语言的法律知识评估，LLM 的研究仍显不足。为此，我们推出了 ArabLegalEval，一个专为评估阿拉伯法律知识而设计的多任务基准数据集。借鉴 MMLU 和 LegalBench 的灵感，ArabLegalEval 汇集了来自沙特法律文件的多样化任务及合成问题。本研究旨在剖析解决阿拉伯法律问题所需的核心能力，并对当前顶尖的 LLM 进行性能评测。我们深入探讨了情境学习的作用，并尝试了多种评估策略。同时，我们开发了自动验证的问题生成流程，以提升数据集的精准度。我们分别对多语言模型 GPT-4 和专注于阿拉伯语的 Jais 进行了基准测试。此外，我们还公开了数据集构建与验证的方法，这些方法具有跨领域的应用潜力。我们期待通过发布 ArabLegalEval 数据集和相关代码，推动阿拉伯法律领域的 AI 研究进展：https://github.com/Thiqah/ArabLegalEval

> The rapid advancements in Large Language Models (LLMs) have led to significant improvements in various natural language processing tasks. However, the evaluation of LLMs' legal knowledge, particularly in non-English languages such as Arabic, remains under-explored. To address this gap, we introduce ArabLegalEval, a multitask benchmark dataset for assessing the Arabic legal knowledge of LLMs. Inspired by the MMLU and LegalBench datasets, ArabLegalEval consists of multiple tasks sourced from Saudi legal documents and synthesized questions. In this work, we aim to analyze the capabilities required to solve legal problems in Arabic and benchmark the performance of state-of-the-art LLMs. We explore the impact of in-context learning and investigate various evaluation methods. Additionally, we explore workflows for generating questions with automatic validation to enhance the dataset's quality. We benchmark multilingual and Arabic-centric LLMs, such as GPT-4 and Jais, respectively. We also share our methodology for creating the dataset and validation, which can be generalized to other domains. We hope to accelerate AI research in the Arabic Legal domain by releasing the ArabLegalEval dataset and code: https://github.com/Thiqah/ArabLegalEval

[Arxiv](https://arxiv.org/abs/2408.07983)