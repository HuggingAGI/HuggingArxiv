# Reasoning3D - 三维空间中的精准推理：借助大型视觉-语言模型，实现细粒度零-shot开放词汇下的3D部件分割推理

发布时间：2024年05月29日

`Agent

理由：这篇论文介绍了一种新型的3D分割任务——零样本3D推理分割，并开发了一种基线方法Reasoning3D，该方法能够理解复杂指令并对3D网格进行精细分割。这种方法利用了预训练的大型语言模型来解析用户查询，并利用模型的世界知识来实现高效的分割。这表明该方法是一个能够执行特定任务的智能Agent，它能够理解和执行指令，进行推理，并在3D分割任务中提供交互式答案。因此，这篇论文更适合归类为Agent，因为它描述了一个能够自主执行任务的智能系统。` `3D建模` `人工智能`

> Reasoning3D -- Grounding and Reasoning in 3D: Fine-Grained Zero-Shot Open-Vocabulary 3D Reasoning Part Segmentation via Large Vision-Language Models

# 摘要

> 本文提出了一种新型3D分割任务——零样本3D推理分割，旨在实现对象部件的精准搜索与定位，突破了传统3D分割的类别限制。我们开发的Reasoning3D基线方法，能理解并执行复杂指令，对3D网格进行精细分割，并提供交互式推理答案。该方法借助预训练的大型语言模型，以零样本方式解析用户查询，利用预训练模型的世界知识，实现对有限3D数据集的高效分割。实验证明，我们的方法不仅适用于多种3D对象和真实扫描数据，还能生成相应的自然语言解释。此外，无需训练即可快速部署，为未来多领域部件级3D对象理解研究提供了一个通用基线。相关资源及评估细节请访问：http://tianrun-chen.github.io/Reason3D/。

> In this paper, we introduce a new task: Zero-Shot 3D Reasoning Segmentation for parts searching and localization for objects, which is a new paradigm to 3D segmentation that transcends limitations for previous category-specific 3D semantic segmentation, 3D instance segmentation, and open-vocabulary 3D segmentation. We design a simple baseline method, Reasoning3D, with the capability to understand and execute complex commands for (fine-grained) segmenting specific parts for 3D meshes with contextual awareness and reasoned answers for interactive segmentation. Specifically, Reasoning3D leverages an off-the-shelf pre-trained 2D segmentation network, powered by Large Language Models (LLMs), to interpret user input queries in a zero-shot manner. Previous research have shown that extensive pre-training endows foundation models with prior world knowledge, enabling them to comprehend complex commands, a capability we can harness to "segment anything" in 3D with limited 3D datasets (source efficient). Experimentation reveals that our approach is generalizable and can effectively localize and highlight parts of 3D objects (in 3D mesh) based on implicit textual queries, including these articulated 3d objects and real-world scanned data. Our method can also generate natural language explanations corresponding to these 3D models and the decomposition. Moreover, our training-free approach allows rapid deployment and serves as a viable universal baseline for future research of part-level 3d (semantic) object understanding in various fields including robotics, object manipulation, part assembly, autonomous driving applications, augment reality and virtual reality (AR/VR), and medical applications. The code, the model weight, the deployment guide, and the evaluation protocol are: http://tianrun-chen.github.io/Reason3D/

![Reasoning3D - 三维空间中的精准推理：借助大型视觉-语言模型，实现细粒度零-shot开放词汇下的3D部件分割推理](../../../paper_images/2405.19326/x1.png)

![Reasoning3D - 三维空间中的精准推理：借助大型视觉-语言模型，实现细粒度零-shot开放词汇下的3D部件分割推理](../../../paper_images/2405.19326/x2.png)

![Reasoning3D - 三维空间中的精准推理：借助大型视觉-语言模型，实现细粒度零-shot开放词汇下的3D部件分割推理](../../../paper_images/2405.19326/x3.png)

![Reasoning3D - 三维空间中的精准推理：借助大型视觉-语言模型，实现细粒度零-shot开放词汇下的3D部件分割推理](../../../paper_images/2405.19326/x4.png)

![Reasoning3D - 三维空间中的精准推理：借助大型视觉-语言模型，实现细粒度零-shot开放词汇下的3D部件分割推理](../../../paper_images/2405.19326/x5.png)

![Reasoning3D - 三维空间中的精准推理：借助大型视觉-语言模型，实现细粒度零-shot开放词汇下的3D部件分割推理](../../../paper_images/2405.19326/x6.png)

[Arxiv](https://arxiv.org/abs/2405.19326)