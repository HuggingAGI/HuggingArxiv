# 利用大型视觉-语言模型，实现高效且鲁棒的 VQA-NLE 数据生成

发布时间：2024年09月23日

`LLM应用` `计算机视觉`

> Towards Efficient and Robust VQA-NLE Data Generation with Large Vision-Language Models

# 摘要

> 自然语言解释 (NLE) 通过提供详细的自然语言解释，帮助揭开大型视觉语言模型 (LVLMs) 的决策过程。然而，现有的 VQA-NLE 数据集创建方法依赖于耗时且昂贵的人工标注。本研究提出了一种利用 LVLMs 高效生成高质量合成 VQA-NLE 数据集的新方法。实验表明，这种方法比人工标注快 20 倍，且质量几乎相当。结合视觉提示显著提升了文本生成的相关性。这项研究为多模态 NLE 数据的自动化生成提供了高效且稳健的解决方案。

> Natural Language Explanation (NLE) aims to elucidate the decision-making process by providing detailed, human-friendly explanations in natural language. It helps demystify the decision-making processes of large vision-language models (LVLMs) through the use of language models. While existing methods for creating a Vision Question-Answering with Natural Language Explanation (VQA-NLE) datasets can provide explanations, they heavily rely on human annotations that are time-consuming and costly. In this study, we propose a novel approach that leverages LVLMs to efficiently generate high-quality synthetic VQA-NLE datasets. By evaluating our synthetic data, we showcase how advanced prompting techniques can lead to the production of high-quality VQA-NLE data. Our findings indicate that this proposed method achieves up to 20x faster than human annotation, with only a minimal decrease in qualitative metrics, achieving robust quality that is nearly equivalent to human-annotated data. Furthermore, we show that incorporating visual prompts significantly enhances the relevance of text generation. Our study paves the way for a more efficient and robust automated generation of multi-modal NLE data, offering a promising solution to the problem.

[Arxiv](https://arxiv.org/abs/2409.14785)