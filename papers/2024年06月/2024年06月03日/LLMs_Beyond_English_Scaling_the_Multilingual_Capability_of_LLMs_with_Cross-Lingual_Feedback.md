# 拓展LLMs的多语言疆界：借助跨语言反馈提升其全球适应性

发布时间：2024年06月03日

`LLM应用

这篇论文主要讨论了如何提升大型语言模型（LLMs）在多语言文本理解和生成上的能力，特别是针对资源稀缺的语言。论文介绍了xLLaMA-100和xBLOOM-100模型的开发，并通过创建特定的数据集和使用DPO算法来增强这些模型的多语言性能。这些工作直接应用于实际的LLM技术改进和扩展，因此属于LLM应用分类。` `多语言处理`

> LLMs Beyond English: Scaling the Multilingual Capability of LLMs with Cross-Lingual Feedback

# 摘要

> 为了让大型语言模型（LLMs）普及至多种自然语言，尤其是资源稀缺的语言，我们必须提升这些模型在多语言文本理解和生成上的能力。尽管最新的多语言LLMs已展现出卓越性能，但受限于低资源语言的训练数据不足，它们仍仅支持少数语言。此外，这些模型在关键的下游任务上尚未与人类偏好完全对齐。本文中，我们推出了xLLaMA-100和xBLOOM-100（合称xLLMs-100），将LLaMA和BLOOM的多语言能力扩展至100种语言。为此，我们创建了两个数据集：一个包含100种语言的多语言指令数据集，以及一个涵盖30种语言的跨语言人类反馈数据集。通过在这些数据集上进行多语言指令调整和使用DPO算法对齐人类反馈，我们显著提升了模型的性能。在五个多语言基准测试中，xLLMs-100均展现出领先优势，确立了支持100种语言的新一代多语言LLM的标杆。

> To democratize large language models (LLMs) to most natural languages, it is imperative to make these models capable of understanding and generating texts in many languages, in particular low-resource ones. While recent multilingual LLMs demonstrate remarkable performance in such capabilities, these LLMs still support a limited number of human languages due to the lack of training data for low-resource languages. Moreover, these LLMs are not yet aligned with human preference for downstream tasks, which is crucial for the success of LLMs in English. In this paper, we introduce xLLaMA-100 and xBLOOM-100 (collectively xLLMs-100), which scale the multilingual capabilities of LLaMA and BLOOM to 100 languages. To do so, we construct two datasets: a multilingual instruction dataset including 100 languages, which represents the largest language coverage to date, and a cross-lingual human feedback dataset encompassing 30 languages. We perform multilingual instruction tuning on the constructed instruction data and further align the LLMs with human feedback using the DPO algorithm on our cross-lingual human feedback dataset. We evaluate the multilingual understanding and generating capabilities of xLLMs-100 on five multilingual benchmarks. Experimental results show that xLLMs-100 consistently outperforms its peers across the benchmarks by considerable margins, defining a new state-of-the-art multilingual LLM that supports 100 languages.

![拓展LLMs的多语言疆界：借助跨语言反馈提升其全球适应性](../../../paper_images/2406.01771/x1.png)

[Arxiv](https://arxiv.org/abs/2406.01771)