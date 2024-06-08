# 拓展LLMs的多语言疆界：借助跨语言反馈增强其全球沟通力

发布时间：2024年06月03日

`LLM应用

理由：这篇论文主要介绍了如何扩展大型语言模型（LLMs）以支持100种语言，并通过构建新的数据集和采用多语言指令调整及DPO算法来提高模型与人类反馈的契合度。这些工作都是针对实际应用场景，即如何让LLMs更好地服务于多种语言，特别是在资源稀缺的语言上。因此，这篇论文属于LLM应用类别。` `多语言处理`

> LLMs Beyond English: Scaling the Multilingual Capability of LLMs with Cross-Lingual Feedback

# 摘要

> 为了让大型语言模型（LLMs）普及至多种自然语言，尤其是资源稀缺的语言，我们需要让这些模型具备跨语言的理解与生成能力。尽管多语言LLMs近期表现卓越，但受限于低资源语言的训练数据不足，它们仍仅支持少数语言。此外，这些模型在关键的下游任务上尚未与人类偏好完全对齐。本文推出了xLLaMA-100和xBLOOM-100（合称xLLMs-100），将LLaMA和BLOOM的能力扩展至100种语言。我们构建了两个数据集：一个包含100种语言的多语言指令集，覆盖范围空前广泛；另一个是包含30种语言的跨语言人类反馈集。通过多语言指令调整和DPO算法，我们使LLMs与人类反馈更加契合。在五个多语言基准测试中，xLLMs-100的表现均超越同类，树立了支持100种语言的新一代多语言LLM的标杆。

> To democratize large language models (LLMs) to most natural languages, it is imperative to make these models capable of understanding and generating texts in many languages, in particular low-resource ones. While recent multilingual LLMs demonstrate remarkable performance in such capabilities, these LLMs still support a limited number of human languages due to the lack of training data for low-resource languages. Moreover, these LLMs are not yet aligned with human preference for downstream tasks, which is crucial for the success of LLMs in English. In this paper, we introduce xLLaMA-100 and xBLOOM-100 (collectively xLLMs-100), which scale the multilingual capabilities of LLaMA and BLOOM to 100 languages. To do so, we construct two datasets: a multilingual instruction dataset including 100 languages, which represents the largest language coverage to date, and a cross-lingual human feedback dataset encompassing 30 languages. We perform multilingual instruction tuning on the constructed instruction data and further align the LLMs with human feedback using the DPO algorithm on our cross-lingual human feedback dataset. We evaluate the multilingual understanding and generating capabilities of xLLMs-100 on five multilingual benchmarks. Experimental results show that xLLMs-100 consistently outperforms its peers across the benchmarks by considerable margins, defining a new state-of-the-art multilingual LLM that supports 100 languages.

![拓展LLMs的多语言疆界：借助跨语言反馈增强其全球沟通力](../../../paper_images/2406.01771/x1.png)

[Arxiv](https://arxiv.org/abs/2406.01771)