# 超越英语界限：借助跨语言反馈，拓展大型语言模型的多语言潜能

发布时间：2024年06月03日

`LLM应用

这篇论文主要介绍了xLLaMA-100和xBLOOM-100（合称xLLMs-100），这两个模型旨在扩展大型语言模型（LLMs）的多语言能力至100种语言。论文中提到了创建新的数据集、进行多语言微调以及使用DPO算法来调整模型以更好地符合人类偏好。这些内容主要关注于LLM的实际应用，特别是在多语言环境下的应用，因此将其归类为LLM应用。` `多语言技术`

> LLMs Beyond English: Scaling the Multilingual Capability of LLMs with Cross-Lingual Feedback

# 摘要

> 为了让大型语言模型（LLMs）普及至更多语言，尤其是资源稀缺的语言，我们需要它们能理解和产出多种语言文本。尽管多语言LLMs近期表现卓越，但因低资源语言训练数据不足，它们支持的语言种类有限。此外，这些模型尚未与人类对下游任务的偏好完全对齐，这对LLMs在英语领域的成功至关重要。本文介绍了xLLaMA-100和xBLOOM-100（合称xLLMs-100），它们将LLaMA和BLOOM的多语言能力扩展至100种语言。我们创建了两个数据集：一个包含100种语言的多语言指令集，覆盖面最广；另一个是包含30种语言的跨语言人类反馈集。通过在指令数据上进行多语言微调，并利用DPO算法在跨语言人类反馈数据集上进一步调整模型，使其更符合人类偏好。在五个多语言测试基准上，xLLMs-100的表现均显著超越同类模型，确立了支持100种语言的新一代多语言LLM的领先地位。

> To democratize large language models (LLMs) to most natural languages, it is imperative to make these models capable of understanding and generating texts in many languages, in particular low-resource ones. While recent multilingual LLMs demonstrate remarkable performance in such capabilities, these LLMs still support a limited number of human languages due to the lack of training data for low-resource languages. Moreover, these LLMs are not yet aligned with human preference for downstream tasks, which is crucial for the success of LLMs in English. In this paper, we introduce xLLaMA-100 and xBLOOM-100 (collectively xLLMs-100), which scale the multilingual capabilities of LLaMA and BLOOM to 100 languages. To do so, we construct two datasets: a multilingual instruction dataset including 100 languages, which represents the largest language coverage to date, and a cross-lingual human feedback dataset encompassing 30 languages. We perform multilingual instruction tuning on the constructed instruction data and further align the LLMs with human feedback using the DPO algorithm on our cross-lingual human feedback dataset. We evaluate the multilingual understanding and generating capabilities of xLLMs-100 on five multilingual benchmarks. Experimental results show that xLLMs-100 consistently outperforms its peers across the benchmarks by considerable margins, defining a new state-of-the-art multilingual LLM that supports 100 languages.

![超越英语界限：借助跨语言反馈，拓展大型语言模型的多语言潜能](../../../paper_images/2406.01771/x1.png)

[Arxiv](https://arxiv.org/abs/2406.01771)