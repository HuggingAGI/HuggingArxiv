# 全面识别多模态信息：基于基础的多模态通用信息提取

发布时间：2024年06月05日

`RAG

理由：这篇论文主要介绍了多模态大型语言模型Reamo，并提出了基于实体的多模态通用信息提取（MUIE）框架。这涉及到构建和优化一个能够处理多种模态信息的模型，特别强调了跨模态信息的提取和实体定位。这种类型的研究通常归类于“RAG”（Retrieval-Augmented Generation），因为它涉及通过检索增强生成过程，特别是在多模态环境中。此外，论文中提到的模型Reamo和其多模态处理能力，以及创建的测试集，都是为了提高信息提取任务的性能，这与RAG的研究方向相符。` `信息提取` `多模态分析`

> Recognizing Everything from All Modalities at Once: Grounded Multimodal Universal Information Extraction

# 摘要

> 在信息提取领域，传统研究往往孤立地探讨不同模态的任务，忽视了跨模态信息的深入分析。为此，本研究首次提出了基于实体的多模态通用信息提取（MUIE），构建了一个统一框架，用以分析各种模态下的IE任务及其精细的实体定位。我们开发了多模态大型语言模型Reamo，它能从所有模态中同时提取并定位信息。通过多样化的调优策略，Reamo获得了强大的信息识别和多模态精细定位能力。针对缺乏合适的MUIE基准问题，我们创建了一个高质量、多样且富有挑战性的测试集，覆盖了9种模态组合的IE任务及其多模态实体。与现有MLLMs的比较表明，Reamo在各方面均表现出色，为后续研究设立了高标准。相关资源已公开于https://haofei.vip/MUIE。

> In the field of information extraction (IE), tasks across a wide range of modalities and their combinations have been traditionally studied in isolation, leaving a gap in deeply recognizing and analyzing cross-modal information. To address this, this work for the first time introduces the concept of grounded Multimodal Universal Information Extraction (MUIE), providing a unified task framework to analyze any IE tasks over various modalities, along with their fine-grained groundings. To tackle MUIE, we tailor a multimodal large language model (MLLM), Reamo, capable of extracting and grounding information from all modalities, i.e., recognizing everything from all modalities at once. Reamo is updated via varied tuning strategies, equipping it with powerful capabilities for information recognition and fine-grained multimodal grounding. To address the absence of a suitable benchmark for grounded MUIE, we curate a high-quality, diverse, and challenging test set, which encompasses IE tasks across 9 common modality combinations with the corresponding multimodal groundings. The extensive comparison of Reamo with existing MLLMs integrated into pipeline approaches demonstrates its advantages across all evaluation dimensions, establishing a strong benchmark for the follow-up research. Our resources are publicly released at https://haofei.vip/MUIE.

![全面识别多模态信息：基于基础的多模态通用信息提取](../../../paper_images/2406.03701/x1.png)

![全面识别多模态信息：基于基础的多模态通用信息提取](../../../paper_images/2406.03701/x2.png)

![全面识别多模态信息：基于基础的多模态通用信息提取](../../../paper_images/2406.03701/x3.png)

![全面识别多模态信息：基于基础的多模态通用信息提取](../../../paper_images/2406.03701/x4.png)

![全面识别多模态信息：基于基础的多模态通用信息提取](../../../paper_images/2406.03701/x5.png)

![全面识别多模态信息：基于基础的多模态通用信息提取](../../../paper_images/2406.03701/x6.png)

![全面识别多模态信息：基于基础的多模态通用信息提取](../../../paper_images/2406.03701/x7.png)

[Arxiv](https://arxiv.org/abs/2406.03701)