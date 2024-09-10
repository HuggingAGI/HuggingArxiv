# OneGen：为 LLM 打造高效的一步式生成与检索解决方案

发布时间：2024年09月08日

`RAG` `人工智能` `信息检索`

> OneGen: Efficient One-Pass Unified Generation and Retrieval for LLMs

# 摘要

> 尽管大型语言模型 (LLM) 在生成能力上取得了显著进步，但在直接处理检索任务时仍显不足。本文提出了一种创新的 One-pass Generation and retrieval 框架 (OneGen)，旨在提升 LLM 在生成与检索并存任务中的表现。通过自回归生成检索标记，OneGen 打破了生成与检索的传统界限，使 LLM 能在一轮正向传递中同时处理这两项任务。我们在 RAG 和实体链接任务上验证了 OneGen 的卓越性能，结果显示，它不仅保留了 LLM 的生成优势，还显著提升了检索效率。OneGen 首次实现了 LLM 在生成过程中的向量检索，为实际应用开辟了新路径。

> Despite the recent advancements in Large Language Models (LLMs), which have significantly enhanced the generative capabilities for various NLP tasks, LLMs still face limitations in directly handling retrieval tasks. However, many practical applications demand the seamless integration of both retrieval and generation. This paper introduces a novel and efficient One-pass Generation and retrieval framework (OneGen), designed to improve LLMs' performance on tasks that require both generation and retrieval. The proposed framework bridges the traditionally separate training approaches for generation and retrieval by incorporating retrieval tokens generated autoregressively. This enables a single LLM to handle both tasks simultaneously in a unified forward pass. We conduct experiments on two distinct types of composite tasks, RAG and Entity Linking, to validate the pluggability, effectiveness, and efficiency of OneGen in training and inference. Furthermore, our results show that integrating generation and retrieval within the same context preserves the generative capabilities of LLMs while improving retrieval performance. To the best of our knowledge, OneGen is the first to enable LLMs to conduct vector retrieval during the generation.

[Arxiv](https://arxiv.org/abs/2409.05152)