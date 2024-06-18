# THEANINE：重探长期对话中的内存管理，借助时间线增强响应生成技术

发布时间：2024年06月16日

`Agent

这篇论文主要探讨了如何通过记忆增强对话回应，以提高大型语言模型（LLMs）在处理长篇对话历史时的性能。论文提出的Theanine框架和TeaFarm流程，都是为了优化LLMs在对话系统中的应用，特别是通过记忆时间线和反事实问题回答流程来增强对话系统的理解和回应能力。这些方法和框架可以被视为智能代理（Agent）的一部分，因为它们旨在增强模型在交互式环境中的表现和决策能力。因此，这篇论文更适合归类到Agent分类中。` `对话系统` `人工智能`

> THEANINE: Revisiting Memory Management in Long-term Conversations with Timeline-augmented Response Generation

# 摘要

> 大型语言模型（LLMs）虽能处理长篇对话历史，但常忽略或错误回忆过往信息。本文重新探讨了在LLMs时代中，如何利用记忆增强对话回应。与以往研究不同，我们认为过时记忆能提供上下文线索，帮助对话系统理解事件发展，从而优化回应。我们提出的Theanine框架，通过记忆时间线——一系列展示事件发展和因果的记忆——增强LLMs的回应生成。同时，我们推出了TeaFarm，一个基于反事实的问题回答流程，以克服G-Eval在长对话中的不足。相关方法视频及TeaFarm评估所需的TeaBag数据集，请访问https://theanine-693b0.web.app/。

> Large language models (LLMs) are capable of processing lengthy dialogue histories during prolonged interaction with users without additional memory modules; however, their responses tend to overlook or incorrectly recall information from the past. In this paper, we revisit memory-augmented response generation in the era of LLMs. While prior work focuses on getting rid of outdated memories, we argue that such memories can provide contextual cues that help dialogue systems understand the development of past events and, therefore, benefit response generation. We present Theanine, a framework that augments LLMs' response generation with memory timelines -- series of memories that demonstrate the development and causality of relevant past events. Along with Theanine, we introduce TeaFarm, a counterfactual-driven question-answering pipeline addressing the limitation of G-Eval in long-term conversations. Supplementary videos of our methods and the TeaBag dataset for TeaFarm evaluation are in https://theanine-693b0.web.app/.

![THEANINE：重探长期对话中的内存管理，借助时间线增强响应生成技术](../../../paper_images/2406.10996/x5.png)

![THEANINE：重探长期对话中的内存管理，借助时间线增强响应生成技术](../../../paper_images/2406.10996/x6.png)

![THEANINE：重探长期对话中的内存管理，借助时间线增强响应生成技术](../../../paper_images/2406.10996/x8.png)

![THEANINE：重探长期对话中的内存管理，借助时间线增强响应生成技术](../../../paper_images/2406.10996/x14.png)

![THEANINE：重探长期对话中的内存管理，借助时间线增强响应生成技术](../../../paper_images/2406.10996/x16.png)

![THEANINE：重探长期对话中的内存管理，借助时间线增强响应生成技术](../../../paper_images/2406.10996/x25.png)

![THEANINE：重探长期对话中的内存管理，借助时间线增强响应生成技术](../../../paper_images/2406.10996/x28.png)

![THEANINE：重探长期对话中的内存管理，借助时间线增强响应生成技术](../../../paper_images/2406.10996/x32.png)

![THEANINE：重探长期对话中的内存管理，借助时间线增强响应生成技术](../../../paper_images/2406.10996/x34.png)

![THEANINE：重探长期对话中的内存管理，借助时间线增强响应生成技术](../../../paper_images/2406.10996/x44.png)

![THEANINE：重探长期对话中的内存管理，借助时间线增强响应生成技术](../../../paper_images/2406.10996/x47.png)

![THEANINE：重探长期对话中的内存管理，借助时间线增强响应生成技术](../../../paper_images/2406.10996/x48.png)

![THEANINE：重探长期对话中的内存管理，借助时间线增强响应生成技术](../../../paper_images/2406.10996/x49.png)

![THEANINE：重探长期对话中的内存管理，借助时间线增强响应生成技术](../../../paper_images/2406.10996/x50.png)

![THEANINE：重探长期对话中的内存管理，借助时间线增强响应生成技术](../../../paper_images/2406.10996/x51.png)

![THEANINE：重探长期对话中的内存管理，借助时间线增强响应生成技术](../../../paper_images/2406.10996/x52.png)

![THEANINE：重探长期对话中的内存管理，借助时间线增强响应生成技术](../../../paper_images/2406.10996/x53.png)

![THEANINE：重探长期对话中的内存管理，借助时间线增强响应生成技术](../../../paper_images/2406.10996/x54.png)

![THEANINE：重探长期对话中的内存管理，借助时间线增强响应生成技术](../../../paper_images/2406.10996/x55.png)

![THEANINE：重探长期对话中的内存管理，借助时间线增强响应生成技术](../../../paper_images/2406.10996/x56.png)

![THEANINE：重探长期对话中的内存管理，借助时间线增强响应生成技术](../../../paper_images/2406.10996/x57.png)

![THEANINE：重探长期对话中的内存管理，借助时间线增强响应生成技术](../../../paper_images/2406.10996/x58.png)

![THEANINE：重探长期对话中的内存管理，借助时间线增强响应生成技术](../../../paper_images/2406.10996/x59.png)

![THEANINE：重探长期对话中的内存管理，借助时间线增强响应生成技术](../../../paper_images/2406.10996/x60.png)

![THEANINE：重探长期对话中的内存管理，借助时间线增强响应生成技术](../../../paper_images/2406.10996/x61.png)

![THEANINE：重探长期对话中的内存管理，借助时间线增强响应生成技术](../../../paper_images/2406.10996/x62.png)

![THEANINE：重探长期对话中的内存管理，借助时间线增强响应生成技术](../../../paper_images/2406.10996/x63.png)

[Arxiv](https://arxiv.org/abs/2406.10996)