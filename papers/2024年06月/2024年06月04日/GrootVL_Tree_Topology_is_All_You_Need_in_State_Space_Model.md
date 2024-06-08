# GrootVL: 状态空间模型中，树状拓扑结构独领风骚。

发布时间：2024年06月04日

`Agent

理由：这篇论文介绍了一种新的网络结构GrootVL，它通过动态构建树形结构来处理长距离依赖问题，并设计了一种线性复杂度的动态规划算法来增强长距离交互。虽然论文中提到了微调大型语言模型以提升文本任务性能，但这并不是论文的主要贡献或重点。相反，论文的核心在于提出了一种新的模型结构和算法，这些可以被视为一种智能体（Agent），因为它能够处理多模态任务并自主地进行特征传播和交互。因此，这篇论文更适合归类为Agent。` `计算机视觉`

> GrootVL: Tree Topology is All You Need in State Space Model

# 摘要

> 状态空间模型通过递归特征传播，展现了与Transformer媲美的表示力，同时效率更佳。但序列的几何限制使其在处理长距离依赖上力不从心。为此，我们开发了GrootVL网络，它先依据空间与输入特征动态构建树形结构，再以此图进行特征传播，突破序列束缚，提升表示力。我们还设计了一种线性复杂度的动态规划算法，增强长距离交互而不增计算负担。GrootVL是一个多才多艺的多模态框架，适用于视觉与文本任务。实验证明，它在图像分类、检测与分割上远超现有结构化状态空间模型。通过微调大型语言模型，我们的方法在文本任务上以低成本持续提升性能。

> The state space models, employing recursively propagated features, demonstrate strong representation capabilities comparable to Transformer models and superior efficiency. However, constrained by the inherent geometric constraints of sequences, it still falls short in modeling long-range dependencies. To address this issue, we propose the GrootVL network, which first dynamically generates a tree topology based on spatial relationships and input features. Then, feature propagation is performed based on this graph, thereby breaking the original sequence constraints to achieve stronger representation capabilities. Additionally, we introduce a linear complexity dynamic programming algorithm to enhance long-range interactions without increasing computational cost. GrootVL is a versatile multimodal framework that can be applied to both visual and textual tasks. Extensive experiments demonstrate that our method significantly outperforms existing structured state space models on image classification, object detection and segmentation. Besides, by fine-tuning large language models, our approach achieves consistent improvements in multiple textual tasks at minor training cost.

![GrootVL: 状态空间模型中，树状拓扑结构独领风骚。](../../../paper_images/2406.02395/x1.png)

![GrootVL: 状态空间模型中，树状拓扑结构独领风骚。](../../../paper_images/2406.02395/x2.png)

![GrootVL: 状态空间模型中，树状拓扑结构独领风骚。](../../../paper_images/2406.02395/x3.png)

![GrootVL: 状态空间模型中，树状拓扑结构独领风骚。](../../../paper_images/2406.02395/x4.png)

![GrootVL: 状态空间模型中，树状拓扑结构独领风骚。](../../../paper_images/2406.02395/x5.png)

![GrootVL: 状态空间模型中，树状拓扑结构独领风骚。](../../../paper_images/2406.02395/x6.png)

[Arxiv](https://arxiv.org/abs/2406.02395)