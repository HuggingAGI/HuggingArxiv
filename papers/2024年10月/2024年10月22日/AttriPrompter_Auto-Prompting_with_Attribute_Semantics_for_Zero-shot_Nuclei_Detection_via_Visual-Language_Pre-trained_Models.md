# AttriPrompter：通过属性语义进行自动提示，用于通过视觉语言预训练模型进行零样本细胞核检测

发布时间：2024年10月22日

`LLM应用` `细胞核检测`

> AttriPrompter: Auto-Prompting with Attribute Semantics for Zero-shot Nuclei Detection via Visual-Language Pre-trained Models

# 摘要

> 大规模视觉语言预训练模型（VLPMs）在通过自然场景的文本提示进行下游对象检测方面表现出色。然而，它们在组织病理学图像上的零样本细胞核检测中的应用相对未被探索，主要是由于医学图像的特征与用于预训练的源自网络的文本-图像对之间存在显著差距。本文旨在研究对象级 VLPM，即基于语言-图像基础的预训练（GLIP）在零样本细胞核检测中的潜力。具体而言，我们提出了一个创新的自动提示管道，名为 AttriPrompter，包括属性生成、属性增强和相关性排序，以避免主观的手动提示设计。AttriPrompter 利用 VLPMs 的文本到图像对齐来创建语义丰富的文本提示，然后将其输入 GLIP 进行初始的零样本细胞核检测。此外，我们提出了一个自训练的知识蒸馏框架，其中 GLIP 作为教师，其初始预测用作伪标签，以解决高细胞核密度带来的挑战，包括漏检、误报和重叠实例。我们的方法在无标签细胞核检测中表现出色，优于所有现有的无监督方法，并表现出出色的通用性。值得注意的是，这项工作还突出了在自然图像-文本对上预训练的 VLPMs 在医学领域下游任务中的惊人潜力。代码将在 https://github.com/wuyongjianCODE/AttriPrompter 上发布。

> Large-scale visual-language pre-trained models (VLPMs) have demonstrated exceptional performance in downstream object detection through text prompts for natural scenes. However, their application to zero-shot nuclei detection on histopathology images remains relatively unexplored, mainly due to the significant gap between the characteristics of medical images and the web-originated text-image pairs used for pre-training. This paper aims to investigate the potential of the object-level VLPM, Grounded Language-Image Pre-training (GLIP), for zero-shot nuclei detection. Specifically, we propose an innovative auto-prompting pipeline, named AttriPrompter, comprising attribute generation, attribute augmentation, and relevance sorting, to avoid subjective manual prompt design. AttriPrompter utilizes VLPMs' text-to-image alignment to create semantically rich text prompts, which are then fed into GLIP for initial zero-shot nuclei detection. Additionally, we propose a self-trained knowledge distillation framework, where GLIP serves as the teacher with its initial predictions used as pseudo labels, to address the challenges posed by high nuclei density, including missed detections, false positives, and overlapping instances. Our method exhibits remarkable performance in label-free nuclei detection, outperforming all existing unsupervised methods and demonstrating excellent generality. Notably, this work highlights the astonishing potential of VLPMs pre-trained on natural image-text pairs for downstream tasks in the medical field as well. Code will be released at https://github.com/wuyongjianCODE/AttriPrompter.

[Arxiv](https://arxiv.org/abs/2410.16820)