# 超越文本：以多模态输入优化 RAG 用于工业应用

发布时间：2024年10月29日

`RAG` `多模态模型`

> Beyond Text: Optimizing RAG with Multimodal Inputs for Industrial Applications

# 摘要

> 大型语言模型（LLMs）在回答问题时能力出众，令人赞叹，然而它们缺少特定领域的知识，还容易产生幻觉。检索增强生成（RAG）是应对这些难题的一种手段，而多模态模型正逐渐成为处理文本和图像的极具潜力的人工智能助手。在本文里，我们阐述了一系列实验，旨在探究如何将多模态模型最优地融入工业领域的 RAG 系统。实验的目的在于明确在工业领域的文档中同时纳入图像和文本能否提升 RAG 性能，并找出此类多模态 RAG 系统的最佳配置。我们的实验涵盖了两种图像处理与检索的方式，以及两个用于答案合成的大型语言模型（GPT4-Vision 和 LLaVA）。这些图像处理策略包含使用多模态嵌入以及从图像生成文本摘要。我们通过 LLM-as-a-Judge 方法来评估实验。我们的成果显示，多模态 RAG 能够胜过单模态 RAG 设定，尽管图像检索比文本检索的难度更大。另外，利用图像的文本摘要相比使用多模态嵌入更具前景，为未来的进步提供了更多可能。

> Large Language Models (LLMs) have demonstrated impressive capabilities in answering questions, but they lack domain-specific knowledge and are prone to hallucinations. Retrieval Augmented Generation (RAG) is one approach to address these challenges, while multimodal models are emerging as promising AI assistants for processing both text and images. In this paper we describe a series of experiments aimed at determining how to best integrate multimodal models into RAG systems for the industrial domain. The purpose of the experiments is to determine whether including images alongside text from documents within the industrial domain increases RAG performance and to find the optimal configuration for such a multimodal RAG system. Our experiments include two approaches for image processing and retrieval, as well as two LLMs (GPT4-Vision and LLaVA) for answer synthesis. These image processing strategies involve the use of multimodal embeddings and the generation of textual summaries from images. We evaluate our experiments with an LLM-as-a-Judge approach. Our results reveal that multimodal RAG can outperform single-modality RAG settings, although image retrieval poses a greater challenge than text retrieval. Additionally, leveraging textual summaries from images presents a more promising approach compared to the use of multimodal embeddings, providing more opportunities for future advancements.

[Arxiv](https://arxiv.org/abs/2410.21943)