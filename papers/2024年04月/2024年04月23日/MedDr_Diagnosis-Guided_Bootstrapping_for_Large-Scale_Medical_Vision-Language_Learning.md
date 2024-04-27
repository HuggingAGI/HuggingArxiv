# MedDr：一种为大规模医学视觉-语言学习设计的诊断引导自举策略

发布时间：2024年04月23日

`分类：LLM应用` `人工智能`

> MedDr: Diagnosis-Guided Bootstrapping for Large-Scale Medical Vision-Language Learning

# 摘要

> 大规模视觉-语言模型的迅猛进展在众多任务中展现了非凡的才能。但医学界高质量图文数据的匮乏，严重限制了这一模型在医疗领域的应用。本研究提出了一种新颖的诊断引导自举策略，充分利用图像与标签数据构建视觉-语言数据库。依托此数据库，我们研发了 MedDr，一个能够应对多种医疗数据形式的通用基础模型，涵盖了放射、病理、皮肤、视网膜和内窥镜等多个领域。在推理阶段，我们还引入了一种简洁高效的检索增强医疗诊断策略，进一步提升了模型的泛化性能。通过在视觉问答、医疗报告撰写和医疗图像诊断等任务上的广泛测试，证实了我们方法的优势。

> The rapid advancement of large-scale vision-language models has showcased remarkable capabilities across various tasks. However, the lack of extensive and high-quality image-text data in medicine has greatly hindered the development of large-scale medical vision-language models. In this work, we present a diagnosis-guided bootstrapping strategy that exploits both image and label information to construct vision-language datasets. Based on the constructed dataset, we developed MedDr, a generalist foundation model for healthcare capable of handling diverse medical data modalities, including radiology, pathology, dermatology, retinography, and endoscopy. Moreover, during inference, we propose a simple but effective retrieval-augmented medical diagnosis strategy, which enhances the model's generalization ability. Extensive experiments on visual question answering, medical report generation, and medical image diagnosis demonstrate the superiority of our method.

[Arxiv](https://arxiv.org/abs/2404.15127)