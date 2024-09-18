# 通过基于证据的归因和学习拒绝，我们旨在提升 LLMs 在 RAG 中的可信度。

发布时间：2024年09月17日

`RAG` `人工智能`

> Measuring and Enhancing Trustworthiness of LLMs in RAG through Grounded Attributions and Learning to Refuse

# 摘要

> LLM 是 RAG 系统的核心。尽管许多研究评估了 RAG 系统的整体质量，但关于 LLM 是否适合 RAG 任务的研究却不多。为此，我们提出了 Trust-Score，一个全面评估 LLM 在 RAG 框架中可信度的新指标。研究表明，现有的提示方法，如 in-context learning，无法有效适应 RAG 任务。因此，我们设计了 Trust-Align 框架，以提升 LLM 的 Trust-Score。实验证明，经过 Trust-Align 对齐的 LLaMA-3-8b 在 ASQA、QAMPARI 和 ELI5 任务上，分别提升了 10.7、29.2 和 14.9，显著超越了同等规模的开放源代码 LLM。代码已发布在：https://github.com/declare-lab/trust-align。

> LLMs are an integral part of retrieval-augmented generation (RAG) systems. While many studies focus on evaluating the quality of end-to-end RAG systems, there is a lack of research on understanding the appropriateness of an LLM for the RAG task. Thus, we introduce a new metric, Trust-Score, that provides a holistic evaluation of the trustworthiness of LLMs in an RAG framework. We show that various prompting methods, such as in-context learning, fail to adapt LLMs effectively to the RAG task. Thus, we propose Trust-Align, a framework to align LLMs for higher Trust-Score. LLaMA-3-8b, aligned with our method, significantly outperforms open-source LLMs of comparable sizes on ASQA (up 10.7), QAMPARI (up 29.2) and ELI5 (up 14.9). We release our code at: https://github.com/declare-lab/trust-align.

[Arxiv](https://arxiv.org/abs/2409.11242)