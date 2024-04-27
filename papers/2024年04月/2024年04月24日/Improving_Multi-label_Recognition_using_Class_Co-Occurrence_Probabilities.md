# 通过类别共现概率提升多标签识别性能

发布时间：2024年04月24日

`分类：Agent` `计算机视觉`

> Improving Multi-label Recognition using Class Co-Occurrence Probabilities

# 摘要

> 多标签识别技术致力于在单一图像中识别多个对象。面对这一任务的复杂性，最新研究开始借助大规模文本图像数据集训练的视觉-语言模型，以提升识别能力。传统方法通常独立地为每个类别训练分类器，却忽视了类别间存在的共现关系。我们提出一种新框架，通过整合类别对的共现信息，优化独立分类器的性能。具体而言，我们采用图卷积网络来处理类别间条件概率，以此优化由视觉-语言模型初步提取的图像和文本信息。经过在四个多标签识别数据集上的测试，我们的方案在性能上超越了当前所有顶尖方法。

> Multi-label Recognition (MLR) involves the identification of multiple objects within an image. To address the additional complexity of this problem, recent works have leveraged information from vision-language models (VLMs) trained on large text-images datasets for the task. These methods learn an independent classifier for each object (class), overlooking correlations in their occurrences. Such co-occurrences can be captured from the training data as conditional probabilities between a pair of classes. We propose a framework to extend the independent classifiers by incorporating the co-occurrence information for object pairs to improve the performance of independent classifiers. We use a Graph Convolutional Network (GCN) to enforce the conditional probabilities between classes, by refining the initial estimates derived from image and text sources obtained using VLMs. We validate our method on four MLR datasets, where our approach outperforms all state-of-the-art methods.

[Arxiv](https://arxiv.org/abs/2404.16193)