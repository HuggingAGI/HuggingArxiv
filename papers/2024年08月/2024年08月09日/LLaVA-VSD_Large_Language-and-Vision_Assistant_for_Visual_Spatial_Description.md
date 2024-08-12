# LLaVA-VSD：专为视觉空间描述设计的大型语言与视觉智能助手

发布时间：2024年08月09日

`LLM应用` `计算机视觉` `人工智能`

> LLaVA-VSD: Large Language-and-Vision Assistant for Visual Spatial Description

# 摘要

> 视觉空间描述（VSD）旨在生成描述图像中物体空间关系的文本。传统方法如VSRC常忽略世界知识，缺乏通用语言能力。本文提出LLaVA-VSD，一个大型语言与视觉助手，专为视觉空间关系的分类、描述及开放式描述设计。模型首先构建VSD指令遵循数据集，然后通过LoRA微调130亿参数的助手，支持高分辨率图像。最后，利用大型语言模型Qwen-2优化生成句子的多样性与准确性。LLaVA-VSD展现卓越的多模态对话能力，能遵循开放式指令，协助查询图像中物体关系。

> Visual Spatial Description (VSD) aims to generate texts that describe the spatial relationships between objects within images. Traditional visual spatial relationship classification (VSRC) methods typically output the spatial relationship between two objects in an image, often neglecting world knowledge and lacking general language capabilities. In this paper, we propose a Large Language-and-Vision Assistant for Visual Spatial Description, named LLaVA-VSD, which is designed for the classification, description, and open-ended description of visual spatial relationships. Specifically, the model first constructs a VSD instruction-following dataset using given figure-caption pairs for the three tasks. It then employs LoRA to fine-tune a Large Language and Vision Assistant for VSD, which has 13 billion parameters and supports high-resolution images. Finally, a large language model (Qwen-2) is used to refine the generated sentences, enhancing their diversity and accuracy. LLaVA-VSD demonstrates excellent multimodal conversational capabilities and can follow open-ended instructions to assist with inquiries about object relationships in images.

[Arxiv](https://arxiv.org/abs/2408.04957)