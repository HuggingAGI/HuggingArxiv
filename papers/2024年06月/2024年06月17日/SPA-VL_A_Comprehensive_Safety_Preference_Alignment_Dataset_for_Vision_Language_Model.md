# SPA-VL：视觉语言模型的全面安全偏好对齐数据集

发布时间：2024年06月17日

`LLM应用

这篇论文主要关注的是视觉语言模型（VLMs）的安全性问题，特别是如何通过创建一个大规模、高质量的数据集（SPA-VL）来提升模型的安全偏好对齐。论文中提到的数据集构建和实验验证，都是为了改进VLMs在实际应用中的表现，即在保持其核心能力的同时，提高其无害性和帮助性。因此，这项工作更偏向于LLM的应用层面，而不是理论研究或Agent、RAG的范畴。` `人工智能安全` `数据集构建`

> SPA-VL: A Comprehensive Safety Preference Alignment Dataset for Vision Language Model

# 摘要

> 视觉语言模型（VLMs）的兴起极大地推动了多模态信息的理解，但其文本与视觉语义的复杂结合使得安全对齐成为一大挑战。由于相关研究不足，目前缺乏大规模、高质量的数据集。为此，我们推出了SPA-VL，一个专为VLMs设计的安全偏好对齐数据集。SPA-VL覆盖了6大危害领域、13个类别及53个子类别，包含100,788个四元组样本，确保了广度与深度。通过从12个不同来源（包括开源和闭源模型）收集响应，我们确保了数据的多样性。实验证明，基于SPA-VL训练的模型在保持核心能力的同时，显著提升了无害性和帮助性。SPA-VL的推出，标志着我们在确保VLMs既无害又具帮助性方面迈出了重要一步。我们已将相关代码和数据集公开，供大家访问和使用。

> The emergence of Vision Language Models (VLMs) has brought unprecedented advances in understanding multimodal information. The combination of textual and visual semantics in VLMs is highly complex and diverse, making the safety alignment of these models challenging. Furthermore, due to the limited study on the safety alignment of VLMs, there is a lack of large-scale, high-quality datasets. To address these limitations, we propose a Safety Preference Alignment dataset for Vision Language Models named SPA-VL. In terms of breadth, SPA-VL covers 6 harmfulness domains, 13 categories, and 53 subcategories, and contains 100,788 samples of the quadruple (question, image, chosen response, rejected response). In terms of depth, the responses are collected from 12 open- (e.g., QwenVL) and closed-source (e.g., Gemini) VLMs to ensure diversity. The experimental results indicate that models trained with alignment techniques on the SPA-VL dataset exhibit substantial improvements in harmlessness and helpfulness while maintaining core capabilities. SPA-VL, as a large-scale, high-quality, and diverse dataset, represents a significant milestone in ensuring that VLMs achieve both harmlessness and helpfulness. We have made our code https://github.com/EchoseChen/SPA-VL-RLHF and SPA-VL dataset url https://huggingface.co/datasets/sqrti/SPA-VL publicly available.

![SPA-VL：视觉语言模型的全面安全偏好对齐数据集](../../../paper_images/2406.12030/x1.png)

![SPA-VL：视觉语言模型的全面安全偏好对齐数据集](../../../paper_images/2406.12030/x2.png)

![SPA-VL：视觉语言模型的全面安全偏好对齐数据集](../../../paper_images/2406.12030/x3.png)

![SPA-VL：视觉语言模型的全面安全偏好对齐数据集](../../../paper_images/2406.12030/x4.png)

![SPA-VL：视觉语言模型的全面安全偏好对齐数据集](../../../paper_images/2406.12030/x5.png)

![SPA-VL：视觉语言模型的全面安全偏好对齐数据集](../../../paper_images/2406.12030/x6.png)

![SPA-VL：视觉语言模型的全面安全偏好对齐数据集](../../../paper_images/2406.12030/x7.png)

![SPA-VL：视觉语言模型的全面安全偏好对齐数据集](../../../paper_images/2406.12030/x8.png)

![SPA-VL：视觉语言模型的全面安全偏好对齐数据集](../../../paper_images/2406.12030/x9.png)

![SPA-VL：视觉语言模型的全面安全偏好对齐数据集](../../../paper_images/2406.12030/x10.png)

![SPA-VL：视觉语言模型的全面安全偏好对齐数据集](../../../paper_images/2406.12030/x11.png)

![SPA-VL：视觉语言模型的全面安全偏好对齐数据集](../../../paper_images/2406.12030/x12.png)

![SPA-VL：视觉语言模型的全面安全偏好对齐数据集](../../../paper_images/2406.12030/x13.png)

![SPA-VL：视觉语言模型的全面安全偏好对齐数据集](../../../paper_images/2406.12030/x14.png)

![SPA-VL：视觉语言模型的全面安全偏好对齐数据集](../../../paper_images/2406.12030/x15.png)

![SPA-VL：视觉语言模型的全面安全偏好对齐数据集](../../../paper_images/2406.12030/x16.png)

[Arxiv](https://arxiv.org/abs/2406.12030)