# 自适应多模态检索增强生成技术

发布时间：2024年10月15日

`RAG` `多模态` `信息检索`

> Self-adaptive Multimodal Retrieval-Augmented Generation

# 摘要

> 传统的 RAG 方法因依赖固定数量的检索文档，常导致信息不完整或嘈杂，影响任务效果。尽管近期适应性方法有所改善，但在复杂多模态任务中的应用仍有限。为此，我们推出了专为多模态设计的 SAM-RAG 方法。SAM-RAG 不仅能动态筛选相关文档，包括图像标题，还能验证检索和输出的质量。实验证明，SAM-RAG 在检索和生成方面均超越现有顶尖技术。通过深入分析，SAM-RAG 在保持高召回率的同时，显著提升了多模态任务的整体表现。代码已公开，详见 https://github.com/SAM-RAG/SAM_RAG。

> Traditional Retrieval-Augmented Generation (RAG) methods are limited by their reliance on a fixed number of retrieved documents, often resulting in incomplete or noisy information that undermines task performance. Although recent adaptive approaches alleviated these problems, their application in intricate and real-world multimodal tasks remains limited. To address these, we propose a new approach called Self-adaptive Multimodal Retrieval-Augmented Generation (SAM-RAG), tailored specifically for multimodal contexts. SAM-RAG not only dynamically filters relevant documents based on the input query, including image captions when needed, but also verifies the quality of both the retrieved documents and the output. Extensive experimental results show that SAM-RAG surpasses existing state-of-the-art methods in both retrieval accuracy and response generation. By further ablation experiments and effectiveness analysis, SAM-RAG maintains high recall quality while improving overall task performance in multimodal RAG task. Our codes are available at https://github.com/SAM-RAG/SAM_RAG.

[Arxiv](https://arxiv.org/abs/2410.11321)