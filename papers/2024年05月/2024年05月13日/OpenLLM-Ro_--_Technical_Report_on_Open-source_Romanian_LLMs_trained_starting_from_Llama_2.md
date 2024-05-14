# OpenLLM-Ro技术报告：探索从Llama 2启程的罗马尼亚语开源大型语言模型之旅在这份技术报告中，我们将深入探讨如何从Llama 2这一起点出发，训练出适用于罗马尼亚语的开源大型语言模型。我们将详细分析训练过程中的技术挑战、创新方法以及最终模型的性能表现，旨在为罗马尼亚语的自然语言处理领域带来新的突破。

发布时间：2024年05月13日

`LLM应用

这篇论文关注的是大型语言模型（LLMs）在特定语言（罗马尼亚语）上的应用和定制化训练。它旨在填补罗马尼亚语在LLMs领域的空白，这与LLM应用的范畴相符，因为它专注于特定语言模型的开发和评估，而不是探讨LLMs的理论基础或Agent的设计与实现。因此，它不属于Agent、RAG或LLM理论分类。` `多语言技术`

> OpenLLM-Ro -- Technical Report on Open-source Romanian LLMs trained starting from Llama 2

# 摘要

> 大型语言模型（LLMs）近年来在多项任务上展现出近乎人类的性能，尽管它们接受了多语言训练，但主要依赖英文数据，导致英文表现远超其他语言。本文详述了我们的方法，旨在培养和评估首个专为罗马尼亚语定制的基础与聊天型LLM，填补了这一领域的空白。

> In recent years, Large Language Models (LLMs) have achieved almost human-like performance on various tasks. While some LLMs have been trained on multilingual data, most of the training data is in English. Hence, their performance in English greatly exceeds their performance in other languages. This document presents our approach to training and evaluating the first foundational and chat LLM specialized for Romanian.

[Arxiv](https://arxiv.org/abs/2405.07703)