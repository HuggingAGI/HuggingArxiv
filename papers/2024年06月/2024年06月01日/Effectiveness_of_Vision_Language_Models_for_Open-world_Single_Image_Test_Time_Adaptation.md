# 视觉语言模型在开放世界环境下，针对单张图像的测试时间适应能力展现出的有效性

发布时间：2024年06月01日

`Agent

理由：这篇论文介绍了一个框架（ROSITA），该框架能够在开放动态环境中实现单张图像的实时适应，利用了大规模视觉语言模型（如CLIP）。这个框架包括了分布外（OOD）检测模块和基于对比学习的目标，以及利用弱OOD样本进行模型分类适应。这些特性表明，该框架能够作为一个智能体（Agent），在未知环境中自主地进行适应和决策，因此归类为Agent。` `计算机视觉` `机器学习`

> Effectiveness of Vision Language Models for Open-world Single Image Test Time Adaptation

# 摘要

> 我们提出了一种创新框架，旨在解决在开放动态环境中单张图像的实时适应难题。通过利用如CLIP这样的大规模视觉语言模型，我们实现了无需源数据或真实标签的图像级实时适应。考虑到模型可能遇到未知类别，我们首先引入了一个高效的分布外（OOD）检测模块，以区分不同程度的OOD样本。接着，我们采用了一种基于对比学习的新目标，通过动态更新的特征库，增强这些样本的区分性。此外，我们还利用可靠的弱OOD样本进行模型分类适应。ROSITA框架整合了这些技术，使得视觉语言模型能够基于单张图像进行持续在线适应。在多个域适应基准上的广泛测试证明了我们框架的有效性，相关代码可在https://manogna-s.github.io/rosita/获取。

> We propose a novel framework to address the real-world challenging task of Single Image Test Time Adaptation in an open and dynamic environment. We leverage large scale Vision Language Models like CLIP to enable real time adaptation on a per-image basis without access to source data or ground truth labels. Since the deployed model can also encounter unseen classes in an open world, we first employ a simple and effective Out of Distribution (OOD) detection module to distinguish between weak and strong OOD samples. We propose a novel contrastive learning based objective to enhance the discriminability between weak and strong OOD samples by utilizing small, dynamically updated feature banks. Finally, we also employ a classification objective for adapting the model using the reliable weak OOD samples. The proposed framework ROSITA combines these components, enabling continuous online adaptation of Vision Language Models on a single image basis. Extensive experimentation on diverse domain adaptation benchmarks validates the effectiveness of the proposed framework. Our code can be found at the project site https://manogna-s.github.io/rosita/

[Arxiv](https://arxiv.org/abs/2406.00481)