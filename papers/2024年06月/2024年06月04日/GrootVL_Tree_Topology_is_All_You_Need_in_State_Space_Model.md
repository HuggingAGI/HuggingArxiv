# GrootVL：在状态空间模型中，树状拓扑结构至关重要。

发布时间：2024年06月04日

`LLM应用

理由：这篇论文介绍了一种名为GrootVL的新网络架构，它通过构建树状结构和引入动态规划算法来提升处理长距离依赖的能力，并在视觉和文本任务上展示了优越的性能。论文中提到通过微调大型语言模型（LLM），GrootVL在多个文本任务上实现了显著提升。这表明该研究是关于如何应用LLM来改进特定任务的性能，因此属于LLM应用类别。` `计算机视觉`

> GrootVL: Tree Topology is All You Need in State Space Model

# 摘要

> 状态空间模型通过递归特征传播，展现了与Transformer媲美的表示力，同时效率更佳。但序列的几何限制使其在处理长距离依赖上力不从心。为此，我们开发了GrootVL网络，它首先基于空间关系和输入特征动态构建树状结构，进而以此为基础进行特征传播，突破序列束缚，提升表示能力。我们还引入了一种线性复杂度的动态规划算法，以增强长距离交互，而不增加计算负担。GrootVL是一个多才多艺的多模态框架，适用于视觉与文本任务。实验证明，我们的方法在图像分类、目标检测和分割上大幅超越现有状态空间模型。通过微调大型语言模型，我们的方法在多个文本任务上以低成本实现了显著提升。

> The state space models, employing recursively propagated features, demonstrate strong representation capabilities comparable to Transformer models and superior efficiency. However, constrained by the inherent geometric constraints of sequences, it still falls short in modeling long-range dependencies. To address this issue, we propose the GrootVL network, which first dynamically generates a tree topology based on spatial relationships and input features. Then, feature propagation is performed based on this graph, thereby breaking the original sequence constraints to achieve stronger representation capabilities. Additionally, we introduce a linear complexity dynamic programming algorithm to enhance long-range interactions without increasing computational cost. GrootVL is a versatile multimodal framework that can be applied to both visual and textual tasks. Extensive experiments demonstrate that our method significantly outperforms existing structured state space models on image classification, object detection and segmentation. Besides, by fine-tuning large language models, our approach achieves consistent improvements in multiple textual tasks at minor training cost.

![GrootVL：在状态空间模型中，树状拓扑结构至关重要。](../../../paper_images/2406.02395/x1.png)

![GrootVL：在状态空间模型中，树状拓扑结构至关重要。](../../../paper_images/2406.02395/x2.png)

![GrootVL：在状态空间模型中，树状拓扑结构至关重要。](../../../paper_images/2406.02395/x3.png)

![GrootVL：在状态空间模型中，树状拓扑结构至关重要。](../../../paper_images/2406.02395/x4.png)

![GrootVL：在状态空间模型中，树状拓扑结构至关重要。](../../../paper_images/2406.02395/x5.png)

![GrootVL：在状态空间模型中，树状拓扑结构至关重要。](../../../paper_images/2406.02395/x6.png)

[Arxiv](https://arxiv.org/abs/2406.02395)