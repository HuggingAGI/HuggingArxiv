# 开放词汇表的目标检测通过检索增强技术得以实现。

发布时间：2024年04月08日

`RAG` `计算机视觉`

> Retrieval-Augmented Open-Vocabulary Object Detection

# 摘要

> 通过视觉-语言模型（VLMs），开放词汇目标检测（OVD）的研究旨在识别超出预设类别的新物体。传统方法通过引入如袜子、iPod、鳄鱼等“正”伪标签，提升了检测器的泛化能力和知识库。为了在这两个维度上进一步优化，我们提出了一种新方法——检索增强损失和视觉特征（RALF）。该方法通过检索相关的“负”类别并调整损失函数，同时利用大型语言模型中的“言语化概念”来增强视觉特征，例如“穿在脚上”、“手持音乐播放器”和“锋利的牙齿”。RALF包含两个核心部分：检索增强损失（RAL）和检索增强视觉特征（RAF）。RAL通过两个损失函数捕捉与负面词汇的语义相似度，而RAF则将这些言语化概念融入视觉特征中。实验显示，RALF在COCO和LVIS数据集上取得了显著成效，COCO数据集中新类别的框AP$_{50}^{\text{N}}$提升了3.4，LVIS数据集上的掩模AP$_{\text{r}}$增加了3.6。相关代码已在GitHub上公开。

> Open-vocabulary object detection (OVD) has been studied with Vision-Language Models (VLMs) to detect novel objects beyond the pre-trained categories. Previous approaches improve the generalization ability to expand the knowledge of the detector, using 'positive' pseudo-labels with additional 'class' names, e.g., sock, iPod, and alligator. To extend the previous methods in two aspects, we propose Retrieval-Augmented Losses and visual Features (RALF). Our method retrieves related 'negative' classes and augments loss functions. Also, visual features are augmented with 'verbalized concepts' of classes, e.g., worn on the feet, handheld music player, and sharp teeth. Specifically, RALF consists of two modules: Retrieval Augmented Losses (RAL) and Retrieval-Augmented visual Features (RAF). RAL constitutes two losses reflecting the semantic similarity with negative vocabularies. In addition, RAF augments visual features with the verbalized concepts from a large language model (LLM). Our experiments demonstrate the effectiveness of RALF on COCO and LVIS benchmark datasets. We achieve improvement up to 3.4 box AP$_{50}^{\text{N}}$ on novel categories of the COCO dataset and 3.6 mask AP$_{\text{r}}$ gains on the LVIS dataset. Code is available at https://github.com/mlvlab/RALF .

![开放词汇表的目标检测通过检索增强技术得以实现。](../../../paper_images/2404.05687/x1.png)

![开放词汇表的目标检测通过检索增强技术得以实现。](../../../paper_images/2404.05687/x2.png)

![开放词汇表的目标检测通过检索增强技术得以实现。](../../../paper_images/2404.05687/x3.png)

![开放词汇表的目标检测通过检索增强技术得以实现。](../../../paper_images/2404.05687/x4.png)

![开放词汇表的目标检测通过检索增强技术得以实现。](../../../paper_images/2404.05687/x5.png)

![开放词汇表的目标检测通过检索增强技术得以实现。](../../../paper_images/2404.05687/x6.png)

![开放词汇表的目标检测通过检索增强技术得以实现。](../../../paper_images/2404.05687/x7.png)

![开放词汇表的目标检测通过检索增强技术得以实现。](../../../paper_images/2404.05687/x8.png)

![开放词汇表的目标检测通过检索增强技术得以实现。](../../../paper_images/2404.05687/qual_3.png)

![开放词汇表的目标检测通过检索增强技术得以实现。](../../../paper_images/2404.05687/qual_5.png)

![开放词汇表的目标检测通过检索增强技术得以实现。](../../../paper_images/2404.05687/x9.png)

![开放词汇表的目标检测通过检索增强技术得以实现。](../../../paper_images/2404.05687/x10.png)

![开放词汇表的目标检测通过检索增强技术得以实现。](../../../paper_images/2404.05687/qual_4.png)

![开放词汇表的目标检测通过检索增强技术得以实现。](../../../paper_images/2404.05687/qual_6.png)

![开放词汇表的目标检测通过检索增强技术得以实现。](../../../paper_images/2404.05687/x11.png)

![开放词汇表的目标检测通过检索增强技术得以实现。](../../../paper_images/2404.05687/x12.png)

[Arxiv](https://arxiv.org/abs/2404.05687)