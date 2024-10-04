# RAG 究竟能为 LLM 的推理能力带来多大提升？

发布时间：2024年10月03日

`RAG` `人工智能`

> How Much Can RAG Help the Reasoning of LLM?

# 摘要

> RAG 在 LLM 中因其引入新知识和减少幻觉的能力而广受欢迎，但其深层机制仍待探索。RAG 如何助力推理，能否提升推理能力，仍是未知。外部文档不仅包含领域信息，还蕴含查询相关的推理线索，暗示其能增强 LLM 的推理能力，这一潜力尚未被挖掘。本文深入探讨，发现 RAG 虽能辅助推理，但效果有限。若将推理比作固定深度的树，RAG 难以助 LLM 深入推理。此外，文档信息需预处理去噪，这难以仅通过微调 LLM 实现，常需额外 transformer 层。为此，我们提出 DPrompt 调优，以有限层数高效解决问题，提升性能。

> Retrieval-Augmented Generation (RAG) has gained significant popularity in modern Large Language Models (LLMs) due to its effectiveness in introducing new knowledge and reducing hallucinations. However, the deep understanding of RAG remains limited, how does RAG help the reasoning process and can RAG help improve the reasoning capability remains question. While external documents are typically considered as a method to incorporate domain-specific information, they also contain intermediate reasoning results related to the query, this suggests that documents could enhance the reasoning capability of LLMs, which has not been previously explored. In this paper, we investigate this issue in depth and find that while RAG can assist with reasoning, the help is limited. If we conceptualize the reasoning process as a tree with fixed depth, then RAG struggles to assist LLMs in performing deeper reasoning. Additionally, the information in the documents requires preprocessing to filter out noise. We demonstrate that this preprocessing is difficult to achieve simply fine-tuning of the LLM, it often necessitates numerous additional transformer layers to solve the problem. To simplify the problem, we propose DPrompt tuning, which effectively resolves the issue within just limited transformer layers, leading to improved performance.

[Arxiv](https://arxiv.org/abs/2410.02338)