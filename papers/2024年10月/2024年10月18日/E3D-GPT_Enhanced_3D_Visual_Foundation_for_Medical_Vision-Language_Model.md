# E3D-GPT：为医疗视觉-语言模型打造的增强版 3D 视觉基础

发布时间：2024年10月18日

`LLM应用` `计算机视觉`

> E3D-GPT: Enhanced 3D Visual Foundation for Medical Vision-Language Model

# 摘要

> 3D 医学视觉-语言模型在疾病诊断和治疗中潜力巨大，但 3D 医学图像（如 CT 扫描）的训练数据有限和高维度问题，严重阻碍了其发展。为此，我们收集了大量未标记的 3D CT 数据，通过自监督学习构建 3D 视觉基础模型，提取 3D 视觉特征。同时，应用 3D 空间卷积聚合高级图像特征，降低计算复杂度并保留空间信息。基于 BIMCV-R 和 CT-RATE，我们构建了两个指令微调数据集，进一步优化模型。在报告生成、视觉问答和疾病诊断方面，我们的模型表现卓越。代码和数据即将公开。

> The development of 3D medical vision-language models holds significant potential for disease diagnosis and patient treatment. However, compared to 2D medical images, 3D medical images, such as CT scans, face challenges related to limited training data and high dimension, which severely restrict the progress of 3D medical vision-language models. To address these issues, we collect a large amount of unlabeled 3D CT data and utilize self-supervised learning to construct a 3D visual foundation model for extracting 3D visual features. Then, we apply 3D spatial convolutions to aggregate and project high-level image features, reducing computational complexity while preserving spatial information. We also construct two instruction-tuning datasets based on BIMCV-R and CT-RATE to fine-tune the 3D vision-language model. Our model demonstrates superior performance compared to existing methods in report generation, visual question answering, and disease diagnosis. Code and data will be made publicly available soon.

[Arxiv](https://arxiv.org/abs/2410.14200)