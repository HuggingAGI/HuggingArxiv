# 视觉语言模型在开放世界环境下，针对单张图像的测试时间适应能力展现出了显著的有效性。

发布时间：2024年06月01日

`Agent

理由：这篇论文介绍了一个框架（ROSITA），该框架能够在开放且动态的环境中对单张图像进行测试时间适应。这个框架利用了大规模视觉语言模型（如CLIP），并引入了分布外（OOD）检测机制和基于对比学习的目标函数，以提升模型对未知类别的适应能力。这种框架可以被视为一个智能代理（Agent），因为它能够在没有原始数据或标签的情况下，对环境中的新情况做出适应和响应。因此，这篇论文更适合归类为Agent，而不是RAG、LLM应用或LLM理论。` `计算机视觉` `机器学习`

> Effectiveness of Vision Language Models for Open-world Single Image Test Time Adaptation

# 摘要

> 我们创新性地提出了一种框架，专门应对在开放且动态的环境中单张图像的测试时间适应挑战。通过运用如CLIP这样的大规模视觉语言模型，我们实现了对每张图像的即时适应，无需原始数据或标签。考虑到模型在开放环境中可能遭遇未知类别，我们首先引入了一个高效的分布外（OOD）检测机制，以区分不同程度的OOD样本。进一步，我们设计了一种基于对比学习的目标函数，通过动态更新的特征库，提升弱和强OOD样本的区分能力。此外，我们还采用了分类目标，利用可靠的弱OOD样本进行模型适应。ROSITA框架整合了这些要素，使得视觉语言模型能够基于单张图像进行持续的在线适应。在多个域适应基准上的广泛测试证实了我们的框架的有效性，相关代码已发布于https://manogna-s.github.io/rosita/。

> We propose a novel framework to address the real-world challenging task of Single Image Test Time Adaptation in an open and dynamic environment. We leverage large scale Vision Language Models like CLIP to enable real time adaptation on a per-image basis without access to source data or ground truth labels. Since the deployed model can also encounter unseen classes in an open world, we first employ a simple and effective Out of Distribution (OOD) detection module to distinguish between weak and strong OOD samples. We propose a novel contrastive learning based objective to enhance the discriminability between weak and strong OOD samples by utilizing small, dynamically updated feature banks. Finally, we also employ a classification objective for adapting the model using the reliable weak OOD samples. The proposed framework ROSITA combines these components, enabling continuous online adaptation of Vision Language Models on a single image basis. Extensive experimentation on diverse domain adaptation benchmarks validates the effectiveness of the proposed framework. Our code can be found at the project site https://manogna-s.github.io/rosita/

[Arxiv](https://arxiv.org/abs/2406.00481)