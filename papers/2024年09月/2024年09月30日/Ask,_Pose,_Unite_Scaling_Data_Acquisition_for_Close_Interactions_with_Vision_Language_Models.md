# 问、提、合：扩展与视觉语言模型互动的数据收集

发布时间：2024年09月30日

`LLM应用` `人机交互` `计算机视觉`

> Ask, Pose, Unite: Scaling Data Acquisition for Close Interactions with Vision Language Models

# 摘要

> 在紧密人类互动中，社会动态对人类网格估计（HME）构成了重大挑战，主要源于物理接触的复杂性和训练数据的匮乏。为此，我们创新性地利用大型视觉语言模型（LVLMs）生成接触图，指导测试时优化，从而生成配对的图像和伪真实网格。这一方法不仅减轻了注释负担，还构建了一个专为HME紧密互动设计的综合数据集。我们的Ask Pose Unite（APU）数据集，包含超过6.2k个接触中的人类网格对，涵盖多种互动类型，源自自然人物场景的图像。实证显示，使用该数据集训练的扩散接触先验，在优化中作为指导，显著提升了对未见互动的网格估计。这项工作有效解决了HME中紧密互动数据稀缺的难题，大幅增强了处理复杂互动场景的能力。

> Social dynamics in close human interactions pose significant challenges for Human Mesh Estimation (HME), particularly due to the complexity of physical contacts and the scarcity of training data. Addressing these challenges, we introduce a novel data generation method that utilizes Large Vision Language Models (LVLMs) to annotate contact maps which guide test-time optimization to produce paired image and pseudo-ground truth meshes. This methodology not only alleviates the annotation burden but also enables the assembly of a comprehensive dataset specifically tailored for close interactions in HME. Our Ask Pose Unite (APU) dataset, comprising over 6.2k human mesh pairs in contact covering diverse interaction types, is curated from images depicting naturalistic person-to-person scenes. We empirically show that using our dataset to train a diffusion-based contact prior, used as guidance during optimization, improves mesh estimation on unseen interactions. Our work addresses longstanding challenges of data scarcity for close interactions in HME enhancing the field's capabilities of handling complex interaction scenarios.

[Arxiv](https://arxiv.org/abs/2410.00309)