# SAMPart3D：对 3D 对象中的任何部分进行分割

发布时间：2024年11月11日

`其他` `机器人技术` `3D 编辑`

> SAMPart3D: Segment Any Part in 3D Objects

# 摘要

> 3D 部分分割是 3D 感知中一项关键且具有挑战性的任务，在机器人技术、3D 生成和 3D 编辑等应用中发挥着至关重要的作用。最近的方法利用强大的视觉语言模型（VLMs）进行 2D 到 3D 的知识蒸馏，实现了零样本 3D 部分分割。然而，这些方法受到对文本提示依赖的限制，这限制了其对大规模未标记数据集的可扩展性以及处理部分模糊性的灵活性。在这项工作中，我们引入了 SAMPart3D，这是一个可扩展的零样本 3D 部分分割框架，能够将任何 3D 对象分割为多个粒度的语义部分，而无需将预定义的部分标签集作为文本提示。为了实现可扩展性，我们使用与文本无关的视觉基础模型来提炼 3D 特征提取骨干，允许扩展到大型未标记的 3D 数据集以学习丰富的 3D 先验知识。为了实现灵活性，我们为多个粒度的 3D 部分分割提炼了尺度条件的部分感知 3D 特征。一旦从尺度条件的部分感知 3D 特征中获得分割的部分，我们使用 VLMs 根据多视图渲染为每个部分分配语义标签。与以前的方法相比，我们的 SAMPart3D 可以扩展到最近的大规模 3D 对象数据集 Objaverse，并处理复杂的、非普通的对象。此外，我们贡献了一个新的 3D 部分分割基准，以解决现有基准中对象和部分缺乏多样性和复杂性的问题。实验表明，我们的 SAMPart3D 显著优于现有的零样本 3D 部分分割方法，并能够促进诸如部分级编辑和交互式分割等各种应用。

> 3D part segmentation is a crucial and challenging task in 3D perception, playing a vital role in applications such as robotics, 3D generation, and 3D editing. Recent methods harness the powerful Vision Language Models (VLMs) for 2D-to-3D knowledge distillation, achieving zero-shot 3D part segmentation. However, these methods are limited by their reliance on text prompts, which restricts the scalability to large-scale unlabeled datasets and the flexibility in handling part ambiguities. In this work, we introduce SAMPart3D, a scalable zero-shot 3D part segmentation framework that segments any 3D object into semantic parts at multiple granularities, without requiring predefined part label sets as text prompts. For scalability, we use text-agnostic vision foundation models to distill a 3D feature extraction backbone, allowing scaling to large unlabeled 3D datasets to learn rich 3D priors. For flexibility, we distill scale-conditioned part-aware 3D features for 3D part segmentation at multiple granularities. Once the segmented parts are obtained from the scale-conditioned part-aware 3D features, we use VLMs to assign semantic labels to each part based on the multi-view renderings. Compared to previous methods, our SAMPart3D can scale to the recent large-scale 3D object dataset Objaverse and handle complex, non-ordinary objects. Additionally, we contribute a new 3D part segmentation benchmark to address the lack of diversity and complexity of objects and parts in existing benchmarks. Experiments show that our SAMPart3D significantly outperforms existing zero-shot 3D part segmentation methods, and can facilitate various applications such as part-level editing and interactive segmentation.

[Arxiv](https://arxiv.org/abs/2411.07184)