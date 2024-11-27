# 《文档堆：针对 1000 多篇文档的视觉语言推理》

发布时间：2024年11月23日

`RAG` `视觉语言` `文档检索`

> Document Haystacks: Vision-Language Reasoning Over Piles of 1000+ Documents

# 摘要

> 大型多模态模型（LMMs）在视觉语言理解领域成就斐然，然而在需要针对大量图像进行复杂推理的实际应用中却遭遇瓶颈。现有的多图像问答基准范围有限，每个问题最多仅搭配 30 张图像，难以完全契合现实应用中大规模检索任务的需求。为弥补这些不足，我们推出了两个文档堆基准，分别名为 DocHaystack 和 InfoHaystack，旨在测评 LMM 在大规模视觉文档检索与理解方面的表现。另外，我们提出了 V-RAG，这是一个新颖的、以视觉为核心的检索增强生成（RAG）框架，它借助了一系列多模态视觉编码器，每个编码器都针对特定优势进行了优化，还配备了一个专门的问题 - 文档相关性模块。V-RAG 树立了新标杆，在颇具挑战性的 DocHaystack-1000 和 InfoHaystack-1000 基准上，召回率@1 相较于之前的最优基线模型分别提高了 9％和 11％。而且，将 V-RAG 与 LMMs 相融合，使其能够在数千张图像上高效运作，在我们的 DocHaystack 和 InfoHaystack 基准测试中实现了显著提升。我们的代码和数据集可在 https://github.com/Vision-CAIR/dochaystacks 获取。

> Large multimodal models (LMMs) have achieved impressive progress in vision-language understanding, yet they face limitations in real-world applications requiring complex reasoning over a large number of images. Existing benchmarks for multi-image question-answering are limited in scope, each question is paired with only up to 30 images, which does not fully capture the demands of large-scale retrieval tasks encountered in the real-world usages. To reduce these gaps, we introduce two document haystack benchmarks, dubbed DocHaystack and InfoHaystack, designed to evaluate LMM performance on large-scale visual document retrieval and understanding. Additionally, we propose V-RAG, a novel, vision-centric retrieval-augmented generation (RAG) framework that leverages a suite of multimodal vision encoders, each optimized for specific strengths, and a dedicated question-document relevance module. V-RAG sets a new standard, with a 9% and 11% improvement in Recall@1 on the challenging DocHaystack-1000 and InfoHaystack-1000 benchmarks, respectively, compared to the previous best baseline models. Additionally, integrating V-RAG with LMMs enables them to efficiently operate across thousands of images, yielding significant improvements on our DocHaystack and InfoHaystack benchmarks. Our code and datasets are available at https://github.com/Vision-CAIR/dochaystacks

[Arxiv](https://arxiv.org/abs/2411.16740)