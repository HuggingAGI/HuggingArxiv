# 优化语言模型偏好：高效注释策略

发布时间：2024年05月22日

`LLM应用

这篇论文主要讨论了如何高效地构建偏好数据集以优化大型语言模型（LLM）的微调过程，以匹配人类偏好。论文提出了一种名为高效注释偏好优化（AEPO）的方法，该方法专注于对高质量且多样化的响应子集进行偏好标注，以提高注释效率。这种方法直接应用于LLM的微调过程中，属于LLM应用的范畴。` `人工智能` `数据标注`

> Annotation-Efficient Preference Optimization for Language Model Alignment

# 摘要

> 偏好优化是微调大型语言模型以匹配人类偏好的常规手段。偏好数据集的质量、多样性和规模对其有效性至关重要。然而，获取大量高质量且多样化的偏好注释在许多场景下颇具挑战。这让我们思考：如何在有限的注释预算下构建一个高效的偏好数据集？为此，我们提出了高效注释偏好优化（AEPO）。AEPO并非对所有响应文本进行全面偏好注释，而是精选出质量和多样性最优的响应子集进行偏好标注。如此一来，AEPO将注释资源聚焦于对一小部分高质量且多样化的响应进行偏好标注。我们通过AEPO评估了直接偏好优化（DPO）的效果，并证实其在相同注释预算下优于标准DPO训练的模型。我们的代码已公开在https://github.com/CyberAgentAILab/annotation-efficient-po。

> Preference optimization is a standard approach to fine-tuning large language models to align with human preferences. The quality, diversity, and quantity of the preference dataset are critical to the effectiveness of preference optimization. However, obtaining a large amount of high-quality and diverse preference annotations is difficult in many applications. This raises the question of how to use the limited annotation budget to create an effective preference dataset. To this end, we propose Annotation-Efficient Preference Optimization (AEPO). Instead of exhaustively annotating preference over all available response texts, AEPO selects a subset of responses that maximizes quality and diversity from the available responses, and then annotates preference over the selected ones. In this way, AEPO focuses the annotation budget on labeling preference over a smaller subset of responses with diversity and of high quality. We evaluate the performance of Direct Preference Optimization (DPO) using AEPO and show that it outperforms models trained using a standard DPO with the same annotation budget. Our code is available at https://github.com/CyberAgentAILab/annotation-efficient-po

[Arxiv](https://arxiv.org/abs/2405.13541)