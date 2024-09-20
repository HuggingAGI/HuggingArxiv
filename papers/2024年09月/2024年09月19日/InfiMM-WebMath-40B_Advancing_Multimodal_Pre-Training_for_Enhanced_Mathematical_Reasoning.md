# InfiMM-WebMath-40B：通过多模态预训练提升数学推理能力

发布时间：2024年09月19日

`LLM理论` `数据科学`

> InfiMM-WebMath-40B: Advancing Multimodal Pre-Training for Enhanced Mathematical Reasoning

# 摘要

> 在高质量数据集上的预训练，对于提升大型语言模型（LLMs）在数学等专业领域的推理能力至关重要。然而，多模态LLMs（MLLMs）领域目前缺乏一个专门为数学推理设计的开源预训练数据集。为此，我们推出了InfiMM-WebMath-40B，一个包含2400万个网页、8500万个图像URL和400亿文本标记的高质量数据集。通过精心从CommonCrawl中提取和过滤，我们详细介绍了数据收集和处理流程。在纯文本和多模态设置中的评估显示，尽管仅使用400亿标记，我们的数据集显著提升了13亿模型的性能，达到了与使用1200亿标记的DeepSeekMath-1.3B相当的结果。而在多模态数学基准上，我们的模型更是创下了开源模型的新纪录。数据已发布在https://huggingface.co/datasets/Infi-MM/InfiMM-WebMath-40B。

> Pre-training on large-scale, high-quality datasets is crucial for enhancing the reasoning capabilities of Large Language Models (LLMs), especially in specialized domains such as mathematics. Despite the recognized importance, the Multimodal LLMs (MLLMs) field currently lacks a comprehensive open-source pre-training dataset specifically designed for mathematical reasoning. To address this gap, we introduce InfiMM-WebMath-40B, a high-quality dataset of interleaved image-text documents. It comprises 24 million web pages, 85 million associated image URLs, and 40 billion text tokens, all meticulously extracted and filtered from CommonCrawl. We provide a detailed overview of our data collection and processing pipeline. To demonstrate the robustness of InfiMM-WebMath-40B, we conducted evaluations in both text-only and multimodal settings. Our evaluations on text-only benchmarks show that, despite utilizing only 40 billion tokens, our dataset significantly enhances the performance of our 1.3B model, delivering results comparable to DeepSeekMath-1.3B, which uses 120 billion tokens for the same model size. Nevertheless, with the introduction of our multi-modal math pre-training dataset, our models set a new state-of-the-art among open-source models on multi-modal math benchmarks such as MathVerse and We-Math. We release our data at https://huggingface.co/datasets/Infi-MM/InfiMM-WebMath-40B.

[Arxiv](https://arxiv.org/abs/2409.12568)