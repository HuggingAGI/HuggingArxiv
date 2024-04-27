# MedDr：一种诊断引导的自举策略，专为大规模医学视觉-语言学习而设计。

发布时间：2024年04月23日

`分类：LLM应用

这篇论文摘要讨论了大规模视觉-语言模型在医学领域的应用，提出了一种诊断驱动的自举策略来构建视觉-语言数据集，并开发了一款名为MedDr的通用基础模型。该模型在多种医疗数据类型上表现出色，并通过检索增强型医疗诊断策略提升了泛化性能。这篇论文主要关注于大型语言模型（LLM）在特定领域的应用，因此归类为LLM应用。` `计算机视觉`

> MedDr: Diagnosis-Guided Bootstrapping for Large-Scale Medical Vision-Language Learning

# 摘要

> 大规模视觉-语言模型的迅猛进步在众多任务中彰显了其卓越性能。但医学领域高质量图文数据的匮乏，严重制约了医学视觉-语言模型的规模化发展。本研究提出了一种诊断驱动的自举策略，充分利用图像与标签信息构建视觉-语言数据集。依托此数据集，我们研发了MedDr——一款能够应对多种医疗数据类型的通用基础模型，涵盖了放射、病理、皮肤、视网膜摄影和内窥镜检查等医疗领域。在推理阶段，我们还引入了一种简洁高效的检索增强型医疗诊断策略，显著提升了模型的泛化性能。通过在视觉问答、医疗报告生成和医学图像诊断等任务上的广泛测试，证实了我们方法的卓越成效。

> The rapid advancement of large-scale vision-language models has showcased remarkable capabilities across various tasks. However, the lack of extensive and high-quality image-text data in medicine has greatly hindered the development of large-scale medical vision-language models. In this work, we present a diagnosis-guided bootstrapping strategy that exploits both image and label information to construct vision-language datasets. Based on the constructed dataset, we developed MedDr, a generalist foundation model for healthcare capable of handling diverse medical data modalities, including radiology, pathology, dermatology, retinography, and endoscopy. Moreover, during inference, we propose a simple but effective retrieval-augmented medical diagnosis strategy, which enhances the model's generalization ability. Extensive experiments on visual question answering, medical report generation, and medical image diagnosis demonstrate the superiority of our method.

[Arxiv](https://arxiv.org/abs/2404.15127)