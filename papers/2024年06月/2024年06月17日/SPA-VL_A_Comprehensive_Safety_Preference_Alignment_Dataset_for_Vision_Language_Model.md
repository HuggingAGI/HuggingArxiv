# SPA-VL：视觉语言模型安全偏好对齐的综合数据集

发布时间：2024年06月17日

`RAG

理由：这篇论文主要关注的是视觉语言模型（VLMs）的安全性问题，特别是如何通过创建一个大规模、高质量的数据集（SPA-VL）来提升模型的安全偏好对齐。这与RAG（Retrieval-Augmented Generation）的范畴相符，因为RAG模型通常涉及通过检索增强生成过程，而这里的数据集建设可以看作是一种检索增强的策略，用于提升模型的安全性和有效性。此外，论文中提到的数据集建设和实验验证，都是为了改进模型的性能，特别是在处理有害内容时的表现，这与RAG模型中对数据和检索机制的依赖相吻合。` `人工智能安全` `多模态学习`

> SPA-VL: A Comprehensive Safety Preference Alignment Dataset for Vision Language Model

# 摘要

> 视觉语言模型（VLMs）的兴起极大地推动了多模态信息的理解，但其文本与视觉语义的复杂结合使得安全对齐成为一大挑战。由于相关研究不足，目前缺乏大规模、高质量的数据集。为此，我们推出了SPA-VL，一个专为VLMs设计的安全偏好对齐数据集。SPA-VL覆盖了6大有害领域、13类和53子类，共100,788个样本，包括问题、图像及对应的优选和淘汰响应。这些响应来自12种开源与闭源VLMs，确保了多样性。实验显示，基于SPA-VL训练的模型在保持核心能力的同时，显著提升了无害性和帮助性。SPA-VL的推出，标志着我们在确保VLMs既无害又具帮助性方面迈出了重要一步。我们已将相关代码和数据集链接公开，供大家访问和使用。

> The emergence of Vision Language Models (VLMs) has brought unprecedented advances in understanding multimodal information. The combination of textual and visual semantics in VLMs is highly complex and diverse, making the safety alignment of these models challenging. Furthermore, due to the limited study on the safety alignment of VLMs, there is a lack of large-scale, high-quality datasets. To address these limitations, we propose a Safety Preference Alignment dataset for Vision Language Models named SPA-VL. In terms of breadth, SPA-VL covers 6 harmfulness domains, 13 categories, and 53 subcategories, and contains 100,788 samples of the quadruple (question, image, chosen response, rejected response). In terms of depth, the responses are collected from 12 open- (e.g., QwenVL) and closed-source (e.g., Gemini) VLMs to ensure diversity. The experimental results indicate that models trained with alignment techniques on the SPA-VL dataset exhibit substantial improvements in harmlessness and helpfulness while maintaining core capabilities. SPA-VL, as a large-scale, high-quality, and diverse dataset, represents a significant milestone in ensuring that VLMs achieve both harmlessness and helpfulness. We have made our code https://github.com/EchoseChen/SPA-VL-RLHF and SPA-VL dataset url https://huggingface.co/datasets/sqrti/SPA-VL publicly available.

![SPA-VL：视觉语言模型安全偏好对齐的综合数据集](../../../paper_images/2406.12030/x1.png)

![SPA-VL：视觉语言模型安全偏好对齐的综合数据集](../../../paper_images/2406.12030/x2.png)

![SPA-VL：视觉语言模型安全偏好对齐的综合数据集](../../../paper_images/2406.12030/x3.png)

![SPA-VL：视觉语言模型安全偏好对齐的综合数据集](../../../paper_images/2406.12030/x4.png)

![SPA-VL：视觉语言模型安全偏好对齐的综合数据集](../../../paper_images/2406.12030/x5.png)

![SPA-VL：视觉语言模型安全偏好对齐的综合数据集](../../../paper_images/2406.12030/x6.png)

![SPA-VL：视觉语言模型安全偏好对齐的综合数据集](../../../paper_images/2406.12030/x7.png)

![SPA-VL：视觉语言模型安全偏好对齐的综合数据集](../../../paper_images/2406.12030/x8.png)

![SPA-VL：视觉语言模型安全偏好对齐的综合数据集](../../../paper_images/2406.12030/x9.png)

![SPA-VL：视觉语言模型安全偏好对齐的综合数据集](../../../paper_images/2406.12030/x10.png)

![SPA-VL：视觉语言模型安全偏好对齐的综合数据集](../../../paper_images/2406.12030/x11.png)

![SPA-VL：视觉语言模型安全偏好对齐的综合数据集](../../../paper_images/2406.12030/x12.png)

![SPA-VL：视觉语言模型安全偏好对齐的综合数据集](../../../paper_images/2406.12030/x13.png)

![SPA-VL：视觉语言模型安全偏好对齐的综合数据集](../../../paper_images/2406.12030/x14.png)

![SPA-VL：视觉语言模型安全偏好对齐的综合数据集](../../../paper_images/2406.12030/x15.png)

![SPA-VL：视觉语言模型安全偏好对齐的综合数据集](../../../paper_images/2406.12030/x16.png)

[Arxiv](https://arxiv.org/abs/2406.12030)