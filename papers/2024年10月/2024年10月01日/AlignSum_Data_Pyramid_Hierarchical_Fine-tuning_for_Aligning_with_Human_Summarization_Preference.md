# AlignSum：通过数据金字塔层次微调，精准对齐人类摘要偏好

发布时间：2024年10月01日

`LLM应用` `文本摘要`

> AlignSum: Data Pyramid Hierarchical Fine-tuning for Aligning with Human Summarization Preference

# 摘要

> 文本摘要任务中，预训练语言模型（PLM）虽在自动评估中表现优异，但在人类评估中却常显不足，显示出其生成的摘要与人类偏好之间的偏差。这主要源于微调数据集的质量问题和高质量人工标注数据的稀缺。为此，我们提出了 AlignSum 框架，通过构建数据金字塔、高斯重采样和两阶段层次化微调，有效对齐语言模型与人类摘要偏好。实验证明，AlignSum 使 BART-Large 等 PLM 在自动和人类评估中均超越了 175B GPT-3，显著提升了模型与人类偏好的契合度。

> Text summarization tasks commonly employ Pre-trained Language Models (PLMs) to fit diverse standard datasets. While these PLMs excel in automatic evaluations, they frequently underperform in human evaluations, indicating a deviation between their generated summaries and human summarization preferences. This discrepancy is likely due to the low quality of fine-tuning datasets and the limited availability of high-quality human-annotated data that reflect true human preference. To address this challenge, we introduce a novel human summarization preference alignment framework AlignSum. This framework consists of three parts: Firstly, we construct a Data Pymarid with extractive, abstractive, and human-annotated summary data. Secondly, we conduct the Gaussian Resampling to remove summaries with extreme lengths. Finally, we implement the two-stage hierarchical fine-tuning with Data Pymarid after Gaussian Resampling. We apply AlignSum to PLMs on the human-annotated CNN/DailyMail and BBC XSum datasets. Experiments show that with AlignSum, PLMs like BART-Large surpass 175B GPT-3 in both automatic and human evaluations. This demonstrates that AlignSum significantly enhances the alignment of language models with human summarization preferences.

[Arxiv](https://arxiv.org/abs/2410.00409)