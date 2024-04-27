# MedDr：一种诊断驱动的自举策略，旨在推进大规模医学视觉与语言学习领域的发展。

发布时间：2024年04月23日

`分类：LLM应用` `人工智能`

> MedDr: Diagnosis-Guided Bootstrapping for Large-Scale Medical Vision-Language Learning

# 摘要

> 大规模视觉-语言模型的迅猛进步在众多任务中展现了非凡的才能。但由于医学领域缺少广泛且高品质的图文数据，大规模医学视觉-语言模型的发展受到了严重阻碍。本研究提出了一种以诊断为导向的自举策略，充分利用图像和标签信息构建视觉-语言数据集。依托此数据集，我们开发了 MedDr，这是一个通用的医疗基础模型，能够应对包括放射、病理、皮肤学、视网膜摄影和内窥镜检查在内的多样化医疗数据形式。在推理阶段，我们还提出了一种简洁高效的检索增强型医疗诊断策略，显著提升了模型的泛化性能。通过在视觉问答、医疗报告生成和医疗图像诊断等任务上的广泛测试，证明了我们方法的优势。

> The rapid advancement of large-scale vision-language models has showcased remarkable capabilities across various tasks. However, the lack of extensive and high-quality image-text data in medicine has greatly hindered the development of large-scale medical vision-language models. In this work, we present a diagnosis-guided bootstrapping strategy that exploits both image and label information to construct vision-language datasets. Based on the constructed dataset, we developed MedDr, a generalist foundation model for healthcare capable of handling diverse medical data modalities, including radiology, pathology, dermatology, retinography, and endoscopy. Moreover, during inference, we propose a simple but effective retrieval-augmented medical diagnosis strategy, which enhances the model's generalization ability. Extensive experiments on visual question answering, medical report generation, and medical image diagnosis demonstrate the superiority of our method.

[Arxiv](https://arxiv.org/abs/2404.15127)