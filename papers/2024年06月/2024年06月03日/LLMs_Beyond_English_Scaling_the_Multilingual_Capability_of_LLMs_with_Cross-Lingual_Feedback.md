# 拓展LLMs的多语言疆界：借助跨语言反馈增强其全球沟通能力

发布时间：2024年06月03日

`LLM应用

这篇论文主要介绍了如何扩展大型语言模型（LLMs）的多语言能力，使其能够理解和生成多达100种语言的文本。通过构建特定的数据集并采用多语言调整和优化算法，论文中的方法显著提升了模型在多语言环境下的性能，使其更符合人类偏好。这一工作直接应用于提升LLMs的多语言处理能力，因此属于LLM应用分类。` `多语言处理`

> LLMs Beyond English: Scaling the Multilingual Capability of LLMs with Cross-Lingual Feedback

# 摘要

> 为了普及大型语言模型至多种自然语言，尤其是资源稀缺的语言，我们需要让这些模型具备理解和生成多语言文本的能力。尽管多语言LLMs近期表现卓越，但受限于低资源语言的训练数据不足，它们仍仅支持少数语言。此外，这些模型尚未与人类对下游任务的偏好完全对齐，这对LLMs在英语领域的成功至关重要。本文中，我们推出了xLLaMA-100和xBLOOM-100（合称xLLMs-100），将LLaMA和BLOOM的多语言能力扩展至100种语言。我们构建了两个数据集：包含100种语言的多语言指令数据集，以及涵盖30种语言的跨语言人类反馈数据集。通过在指令数据上进行多语言调整，并利用DPO算法在跨语言人类反馈数据集上进一步优化模型，我们使LLMs更符合人类偏好。在五个多语言基准测试中，xLLMs-100的表现显著超越其他模型，成为支持100种语言的新一代多语言LLM。

> To democratize large language models (LLMs) to most natural languages, it is imperative to make these models capable of understanding and generating texts in many languages, in particular low-resource ones. While recent multilingual LLMs demonstrate remarkable performance in such capabilities, these LLMs still support a limited number of human languages due to the lack of training data for low-resource languages. Moreover, these LLMs are not yet aligned with human preference for downstream tasks, which is crucial for the success of LLMs in English. In this paper, we introduce xLLaMA-100 and xBLOOM-100 (collectively xLLMs-100), which scale the multilingual capabilities of LLaMA and BLOOM to 100 languages. To do so, we construct two datasets: a multilingual instruction dataset including 100 languages, which represents the largest language coverage to date, and a cross-lingual human feedback dataset encompassing 30 languages. We perform multilingual instruction tuning on the constructed instruction data and further align the LLMs with human feedback using the DPO algorithm on our cross-lingual human feedback dataset. We evaluate the multilingual understanding and generating capabilities of xLLMs-100 on five multilingual benchmarks. Experimental results show that xLLMs-100 consistently outperforms its peers across the benchmarks by considerable margins, defining a new state-of-the-art multilingual LLM that supports 100 languages.

![拓展LLMs的多语言疆界：借助跨语言反馈增强其全球沟通能力](../../../paper_images/2406.01771/x1.png)

[Arxiv](https://arxiv.org/abs/2406.01771)