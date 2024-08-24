# 大型语言模型在多模态可变形图像配准中的应用

发布时间：2024年08月20日

`LLM应用` `计算机视觉`

> Large Language Models for Multimodal Deformable Image Registration

# 摘要

> 多模态图像配准的难题在于不同模态间特征的转换与对齐。生成模型难以保留跨模态的必要信息，而非生成模型则在模态间特征对齐上力不从心。为此，我们创新性地提出了LLM-Morph框架，该框架利用预训练的大型语言模型(LLMs)，通过深度特征对齐来解决这一难题。首先，我们用CNN编码器提取跨模态图像的深层视觉特征，随后通过适配器调整这些特征，并利用LoRA技术微调LLMs的权重，以弥合预训练模型与MDIR任务间的领域差异。接着，我们运用多个适配器将LLMs编码的特征转换为多尺度视觉特征，生成多尺度变形场，从而实现由粗到细的图像配准。实验结果显示，我们的框架在MR-CT腹部和SR-Reg脑部数据集上表现出色，展现了预训练LLMs在MDIR任务中的巨大潜力。代码已公开，详见：https://github.com/ninjannn/LLM-Morph。

> The challenge of Multimodal Deformable Image Registration (MDIR) lies in the conversion and alignment of features between images of different modalities. Generative models (GMs) cannot retain the necessary information enough from the source modality to the target one, while non-GMs struggle to align features across these two modalities. In this paper, we propose a novel coarse-to-fine MDIR framework,LLM-Morph, which is applicable to various pre-trained Large Language Models (LLMs) to solve these concerns by aligning the deep features from different modal medical images. Specifically, we first utilize a CNN encoder to extract deep visual features from cross-modal image pairs, then we use the first adapter to adjust these tokens, and use LoRA in pre-trained LLMs to fine-tune their weights, both aimed at eliminating the domain gap between the pre-trained LLMs and the MDIR task. Third, for the alignment of tokens, we utilize other four adapters to transform the LLM-encoded tokens into multi-scale visual features, generating multi-scale deformation fields and facilitating the coarse-to-fine MDIR task. Extensive experiments in MR-CT Abdomen and SR-Reg Brain datasets demonstrate the effectiveness of our framework and the potential of pre-trained LLMs for MDIR task. Our code is availabel at: https://github.com/ninjannn/LLM-Morph.

[Arxiv](https://arxiv.org/abs/2408.10703)