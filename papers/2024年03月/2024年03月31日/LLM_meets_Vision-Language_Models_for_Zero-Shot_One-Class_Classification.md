# 大型语言模型携手视觉-语言模型，共同应对零样本单类识别挑战。

发布时间：2024年03月31日

`RAG` `计算机视觉`

> LLM meets Vision-Language Models for Zero-Shot One-Class Classification

# 摘要

> 在零-shot单类视觉分类的挑战中，我们只需目标类别的标签，便需辨别出正负样本。我们提出了一种新颖的两步策略：首先，利用大型语言模型识别视觉上容易混淆的对象；其次，借助视觉-语言预训练模型（如CLIP）进行样本分类。通过对大规模视觉基准的调整，我们的方法在性能上超越了市面上的现成解决方案。我们设计了一个实际的测试基准，负样本与正样本源自同一数据集，并且在iNaturalist的分类树中，负样本与正样本保持恒定的层级距离。我们的研究显示，仅凭类别标签，就能有效地将单一类别与其语义相近的类别区分开来。

> We consider the problem of zero-shot one-class visual classification. In this setting, only the label of the target class is available, and the goal is to discriminate between positive and negative query samples without requiring any validation example from the target task. We propose a two-step solution that first queries large language models for visually confusing objects and then relies on vision-language pre-trained models (e.g., CLIP) to perform classification. By adapting large-scale vision benchmarks, we demonstrate the ability of the proposed method to outperform adapted off-the-shelf alternatives in this setting. Namely, we propose a realistic benchmark where negative query samples are drawn from the same original dataset as positive ones, including a granularity-controlled version of iNaturalist, where negative samples are at a fixed distance in the taxonomy tree from the positive ones. Our work shows that it is possible to discriminate between a single category and other semantically related ones using only its label

[Arxiv](https://arxiv.org/abs/2404.00675)