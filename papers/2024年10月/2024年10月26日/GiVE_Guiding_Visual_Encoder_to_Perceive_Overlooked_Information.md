# GiVE：引导视觉编码器去察觉被遗漏的信息

发布时间：2024年10月26日

`LLM应用` `人工智能` `多模态`

> GiVE: Guiding Visual Encoder to Perceive Overlooked Information

# 摘要

> 多模态大型语言模型在诸如文本转视频生成和视觉问答等应用中促进了人工智能的进步。这些模型依靠视觉编码器将非文本数据转化为向量，然而当下的编码器要么语义对齐不足，要么忽视了非显著对象。我们提出了“引导视觉编码器感知被忽略信息（GiVE）”的方法。GiVE 借助注意力引导适配器（AG-Adapter）模块和以对象为核心的视觉语义学习模块来强化视觉表征。其中涵盖了三个新颖的损失项：以对象为核心的图像-文本对比（OITC）损失、以对象为核心的图像-图像对比（OIIC）损失以及以对象为核心的图像判别（OID）损失，提升了对对象的考量、检索精准度和全面性。我们的贡献涵盖动态视觉焦点调整、用于增强对象检索的新型损失函数以及多对象指令（MOInst）数据集。实验显示，我们的方法实现了最先进的性能。

> Multimodal Large Language Models have advanced AI in applications like text-to-video generation and visual question answering. These models rely on visual encoders to convert non-text data into vectors, but current encoders either lack semantic alignment or overlook non-salient objects. We propose the Guiding Visual Encoder to Perceive Overlooked Information (GiVE) approach. GiVE enhances visual representation with an Attention-Guided Adapter (AG-Adapter) module and an Object-focused Visual Semantic Learning module. These incorporate three novel loss terms: Object-focused Image-Text Contrast (OITC) loss, Object-focused Image-Image Contrast (OIIC) loss, and Object-focused Image Discrimination (OID) loss, improving object consideration, retrieval accuracy, and comprehensiveness. Our contributions include dynamic visual focus adjustment, novel loss functions to enhance object retrieval, and the Multi-Object Instruction (MOInst) dataset. Experiments show our approach achieves state-of-the-art performance.

[Arxiv](https://arxiv.org/abs/2410.20109)