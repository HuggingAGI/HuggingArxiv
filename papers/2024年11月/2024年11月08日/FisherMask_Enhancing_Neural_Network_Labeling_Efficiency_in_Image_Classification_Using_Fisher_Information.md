# FisherMask：在图像分类中使用 Fisher 信息提高神经网络标注效率

发布时间：2024年11月08日

`其他` `主动学习`

> FisherMask: Enhancing Neural Network Labeling Efficiency in Image Classification Using Fisher Information

# 摘要

> 深度学习（DL）模型由于其出色的性能和效率在各个领域都很受欢迎。然而，它们的有效性在很大程度上依赖于大量的有标签数据，而这些数据通常手动生成既耗时又费力。为了克服这一挑战，必须制定减少对大量有标签数据的依赖同时保持模型性能的策略。在本文中，我们提出了 FisherMask，这是一种基于 Fisher 信息的主动学习（AL）方法，通过根据其 Fisher 信息值对关键网络参数进行掩码来识别它们。FisherMask 通过使用 Fisher 信息选择最关键的参数来增强批量 AL，允许在 AL 训练期间识别最具影响力的样本。此外，Fisher 信息具有良好的统计特性，为模型行为提供了有价值的见解，并更好地理解了 AL 管道内的性能特征。我们的大量实验表明，FisherMask 在包括 CIFAR-10 和 FashionMNIST 在内的各种数据集上显著优于最先进的方法，特别是在不平衡设置下。这些改进导致标记效率的大幅提高。因此，它是衡量模型参数对数据样本敏感性的有效工具。我们的代码可在 url{https://github.com/sgchr273/FisherMask} 上获取。

> Deep learning (DL) models are popular across various domains due to their remarkable performance and efficiency. However, their effectiveness relies heavily on large amounts of labeled data, which are often time-consuming and labor-intensive to generate manually. To overcome this challenge, it is essential to develop strategies that reduce reliance on extensive labeled data while preserving model performance. In this paper, we propose FisherMask, a Fisher information-based active learning (AL) approach that identifies key network parameters by masking them based on their Fisher information values. FisherMask enhances batch AL by using Fisher information to select the most critical parameters, allowing the identification of the most impactful samples during AL training. Moreover, Fisher information possesses favorable statistical properties, offering valuable insights into model behavior and providing a better understanding of the performance characteristics within the AL pipeline. Our extensive experiments demonstrate that FisherMask significantly outperforms state-of-the-art methods on diverse datasets, including CIFAR-10 and FashionMNIST, especially under imbalanced settings. These improvements lead to substantial gains in labeling efficiency. Hence serving as an effective tool to measure the sensitivity of model parameters to data samples. Our code is available on url{https://github.com/sgchr273/FisherMask}.

[Arxiv](https://arxiv.org/abs/2411.05752)