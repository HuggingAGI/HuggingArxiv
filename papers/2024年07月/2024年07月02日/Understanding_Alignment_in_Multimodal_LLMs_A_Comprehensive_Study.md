# 探究多模态LLM中的对齐机制：一项深入研究

发布时间：2024年07月02日

`LLM应用` `人工智能` `计算机视觉`

> Understanding Alignment in Multimodal LLMs: A Comprehensive Study

# 摘要

> 偏好对齐在提升大型语言模型性能中扮演着关键角色，但在多模态大型语言模型中的应用仍待深入探索。多模态模型在图像理解任务中同样面临幻觉挑战，不仅可能因错误信息，还可能因与图像不符的回应。对齐的主要目标之一是使模型回应更贴合图像信息。近期研究引入了多种对齐方法和数据集，但各数据集和方法的差异使得具体改进因素尚不明朗。本文中，我们深入分析了多模态模型中偏好对齐的各个方面，分类并探讨了离线和在线对齐算法的结合效果，回顾了多模态偏好数据集的构建细节及其对性能的影响。基于此，我们创新性地提出了无需额外注释或外部模型的偏差驱动的幻觉采样方法，该方法在多模态模型性能上表现出色，与现有对齐技术相媲美。

> Preference alignment has become a crucial component in enhancing the performance of Large Language Models (LLMs), yet its impact in Multimodal Large Language Models (MLLMs) remains comparatively underexplored. Similar to language models, MLLMs for image understanding tasks encounter challenges like hallucination. In MLLMs, hallucination can occur not only by stating incorrect facts but also by producing responses that are inconsistent with the image content. A primary objective of alignment for MLLMs is to encourage these models to align responses more closely with image information. Recently, multiple works have introduced preference datasets for MLLMs and examined different alignment methods, including Direct Preference Optimization (DPO) and Proximal Policy Optimization (PPO). However, due to variations in datasets, base model types, and alignment methods, it remains unclear which specific elements contribute most significantly to the reported improvements in these works. In this paper, we independently analyze each aspect of preference alignment in MLLMs. We start by categorizing the alignment algorithms into two groups, offline (such as DPO), and online (such as online-DPO), and show that combining offline and online methods can improve the performance of the model in certain scenarios. We review a variety of published multimodal preference datasets and discuss how the details of their construction impact model performance. Based on these insights, we introduce a novel way of creating multimodal preference data called Bias-Driven Hallucination Sampling (BDHS) that needs neither additional annotation nor external models, and show that it can achieve competitive performance to previously published alignment work for multimodal models across a range of benchmarks.

[Arxiv](https://arxiv.org/abs/2407.02477)