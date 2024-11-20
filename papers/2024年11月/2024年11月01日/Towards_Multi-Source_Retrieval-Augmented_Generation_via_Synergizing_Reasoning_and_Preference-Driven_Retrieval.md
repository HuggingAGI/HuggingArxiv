# 旨在通过协同推理与偏好驱动检索来达成多源检索增强生成

发布时间：2024年11月01日

`RAG` `语言模型` `检索技术`

> Towards Multi-Source Retrieval-Augmented Generation via Synergizing Reasoning and Preference-Driven Retrieval

# 摘要

> 检索增强生成（RAG）已成为缓解大型语言模型（LLMs）中幻觉问题和参数化知识局限的可靠外部知识增强技术。现有的自适应 RAG（ARAG）系统因无法在恰当时间选对检索源，难以有效探索多个检索源。为此，我们提出了一个名为 MSPR 的多源 ARAG 框架，它融合推理和偏好驱动的检索，自适应决定“何时、检索何物”以及“使用哪个检索源”。为更好适应不同特性的检索源，我们还运用了检索动作调整和答案反馈策略。这使得我们的框架能充分挖掘高质量的主要来源，同时适时用次要来源加以补充。在三个数据集上开展的广泛且多维的实验，彰显了 MSPR 的优越性和有效性。

> Retrieval-Augmented Generation (RAG) has emerged as a reliable external knowledge augmentation technique to mitigate hallucination issues and parameterized knowledge limitations in Large Language Models (LLMs). Existing Adaptive RAG (ARAG) systems struggle to effectively explore multiple retrieval sources due to their inability to select the right source at the right time. To address this, we propose a multi-source ARAG framework, termed MSPR, which synergizes reasoning and preference-driven retrieval to adaptive decide "when and what to retrieve" and "which retrieval source to use". To better adapt to retrieval sources of differing characteristics, we also employ retrieval action adjustment and answer feedback strategy. They enable our framework to fully explore the high-quality primary source while supplementing it with secondary sources at the right time. Extensive and multi-dimensional experiments conducted on three datasets demonstrate the superiority and effectiveness of MSPR.

[Arxiv](https://arxiv.org/abs/2411.00689)