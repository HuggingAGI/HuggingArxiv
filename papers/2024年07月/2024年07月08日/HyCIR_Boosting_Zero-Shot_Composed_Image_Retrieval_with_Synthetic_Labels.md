# HyCIR 技术通过合成标签，显著提升了零-shot组合图像检索的性能。

发布时间：2024年07月08日

`LLM应用` `图像检索` `机器学习`

> HyCIR: Boosting Zero-Shot Composed Image Retrieval with Synthetic Labels

# 摘要

> 组合图像检索（CIR）旨在根据带有文本的查询图像检索图像。当前的零样本CIR（ZS-CIR）方法试图在不使用昂贵的三元组标记训练数据集的情况下解决CIR任务。然而，ZS-CIR与三元组监督的CIR之间的差距仍然很大。在这项工作中，我们提出了混合CIR（HyCIR），它使用合成标签来提升ZS-CIR的性能。我们提出了一种新的CIR标签合成流程（SynCir），其中仅需要未标记的图像。首先，基于视觉相似性提取图像对。其次，基于视觉-语言模型和LLM为每个图像对生成查询文本。第三，基于语义相似性在语言空间中进一步过滤数据。为了提高ZS-CIR性能，我们提出了一种混合训练策略，结合ZS-CIR监督和合成CIR三元组。采用了两种对比学习方法。一种是使用大规模未标记图像数据集学习具有良好泛化的图像到文本映射。另一种是使用合成CIR三元组学习更适合CIR任务的映射。我们的方法在常见的CIR基准测试（CIRR和CIRCO）上实现了SOTA的零样本性能。

> Composed Image Retrieval (CIR) aims to retrieve images based on a query image with text. Current Zero-Shot CIR (ZS-CIR) methods try to solve CIR tasks without using expensive triplet-labeled training datasets. However, the gap between ZS-CIR and triplet-supervised CIR is still large. In this work, we propose Hybrid CIR (HyCIR), which uses synthetic labels to boost the performance of ZS-CIR. A new label Synthesis pipeline for CIR (SynCir) is proposed, in which only unlabeled images are required. First, image pairs are extracted based on visual similarity. Second, query text is generated for each image pair based on vision-language model and LLM. Third, the data is further filtered in language space based on semantic similarity. To improve ZS-CIR performance, we propose a hybrid training strategy to work with both ZS-CIR supervision and synthetic CIR triplets. Two kinds of contrastive learning are adopted. One is to use large-scale unlabeled image dataset to learn an image-to-text mapping with good generalization. The other is to use synthetic CIR triplets to learn a better mapping for CIR tasks. Our approach achieves SOTA zero-shot performance on the common CIR benchmarks: CIRR and CIRCO.

[Arxiv](https://arxiv.org/abs/2407.05795)