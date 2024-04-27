# 通过类别共现概率提升多标签识别的性能

发布时间：2024年04月24日

`分类：Agent

这篇论文提出了一种新的框架，通过整合类别对的共现信息，优化独立分类器的性能。该框架利用图卷积网络（GCN）来调整类别间条件概率，从而精细化视觉-语言模型（VLMs）从图像和文本源得到的初步预测。这表明该研究涉及到智能代理（Agent）在多标签识别（MLR）任务中的应用，因此将其归类为Agent。` `计算机视觉` `机器学习`

> Improving Multi-label Recognition using Class Co-Occurrence Probabilities

# 摘要

> 多标签识别（MLR）技术致力于在单张图像中识别多个对象。面对这一问题的复杂性，最新研究开始借助视觉-语言模型（VLMs）——它们在海量图文数据集上进行训练——来提升任务效率。传统方法通常为每个类别独立训练一个分类器，却忽视了类别间存在的共现关系。我们提出一种新框架，通过整合类别对的共现信息，优化独立分类器的性能。该框架利用图卷积网络（GCN）来调整类别间条件概率，从而精细化VLMs从图像和文本源得到的初步预测。经过在四个MLR数据集上的测试，我们的方法在性能上超越了所有现有的顶尖技术。

> Multi-label Recognition (MLR) involves the identification of multiple objects within an image. To address the additional complexity of this problem, recent works have leveraged information from vision-language models (VLMs) trained on large text-images datasets for the task. These methods learn an independent classifier for each object (class), overlooking correlations in their occurrences. Such co-occurrences can be captured from the training data as conditional probabilities between a pair of classes. We propose a framework to extend the independent classifiers by incorporating the co-occurrence information for object pairs to improve the performance of independent classifiers. We use a Graph Convolutional Network (GCN) to enforce the conditional probabilities between classes, by refining the initial estimates derived from image and text sources obtained using VLMs. We validate our method on four MLR datasets, where our approach outperforms all state-of-the-art methods.

[Arxiv](https://arxiv.org/abs/2404.16193)