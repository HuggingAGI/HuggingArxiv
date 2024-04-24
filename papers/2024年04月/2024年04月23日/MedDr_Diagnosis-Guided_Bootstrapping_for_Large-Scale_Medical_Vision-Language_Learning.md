# MedDr：一种诊断导向的自举策略，专为大规模医学视觉与语言学习而设计。

发布时间：2024年04月23日

`分类：LLM应用` `人工智能`

> MedDr: Diagnosis-Guided Bootstrapping for Large-Scale Medical Vision-Language Learning

# 摘要

> 大规模视觉-语言模型的迅猛进步在众多任务中彰显了其卓越性能。但医学图像-文本数据的匮乏限制了医疗视觉-语言模型的进一步发展。本研究提出了一种以诊断为导向的自举方法，充分利用图像和标签信息来构建视觉-语言数据集。据此数据集，我们开发了MedDr，这是一个通用的医疗基础模型，能够应对放射、病理、皮肤、视网膜和内窥镜等多种医疗数据类型。在推理阶段，我们还提出了一种简洁高效的检索增强型医疗诊断策略，进一步提升了模型的泛化性能。通过在视觉问答、医疗报告撰写和医疗图像诊断等方面的广泛测试，证实了我们方法的优势。

> The rapid advancement of large-scale vision-language models has showcased remarkable capabilities across various tasks. However, the lack of extensive and high-quality image-text data in medicine has greatly hindered the development of large-scale medical vision-language models. In this work, we present a diagnosis-guided bootstrapping strategy that exploits both image and label information to construct vision-language datasets. Based on the constructed dataset, we developed MedDr, a generalist foundation model for healthcare capable of handling diverse medical data modalities, including radiology, pathology, dermatology, retinography, and endoscopy. Moreover, during inference, we propose a simple but effective retrieval-augmented medical diagnosis strategy, which enhances the model's generalization ability. Extensive experiments on visual question answering, medical report generation, and medical image diagnosis demonstrate the superiority of our method.

[Arxiv](https://arxiv.org/abs/2404.15127)