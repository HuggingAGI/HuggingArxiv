# 通过类别共现概率提升多标签识别性能

发布时间：2024年04月24日

`分类：RAG

这篇论文摘要描述了一种新框架，通过整合类别对的共现信息来优化多标签识别技术中的独立分类器。它使用了视觉-语言模型（VLMs）和图卷积网络（GCN）来改进识别性能。这个研究涉及到了多模态学习（RAG）的领域，因为它结合了图像和文本信息来提高识别性能。` `计算机视觉`

> Improving Multi-label Recognition using Class Co-Occurrence Probabilities

# 摘要

> 多标签识别技术致力于在单一图像中识别多个目标对象。为应对这一挑战，最新研究通过利用大规模图文数据集训练的视觉-语言模型（VLMs），引入了新的解决方案。这些解决方案通常为每个目标类别训练一个独立分类器，但却忽视了类别之间存在的共现关系。我们提出一种新框架，通过整合类别对的共现信息来优化这些独立分类器，从而提升识别性能。具体而言，我们采用图卷积网络（GCN）来调整类别间条件概率，进一步完善了VLMs从图像和文本中提取的初步预测。经过在四个多标签识别数据集上的测试，我们的方法在性能上超越了当前所有顶尖技术。

> Multi-label Recognition (MLR) involves the identification of multiple objects within an image. To address the additional complexity of this problem, recent works have leveraged information from vision-language models (VLMs) trained on large text-images datasets for the task. These methods learn an independent classifier for each object (class), overlooking correlations in their occurrences. Such co-occurrences can be captured from the training data as conditional probabilities between a pair of classes. We propose a framework to extend the independent classifiers by incorporating the co-occurrence information for object pairs to improve the performance of independent classifiers. We use a Graph Convolutional Network (GCN) to enforce the conditional probabilities between classes, by refining the initial estimates derived from image and text sources obtained using VLMs. We validate our method on four MLR datasets, where our approach outperforms all state-of-the-art methods.

[Arxiv](https://arxiv.org/abs/2404.16193)