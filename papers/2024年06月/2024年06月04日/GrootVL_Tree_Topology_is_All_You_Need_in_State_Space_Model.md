# GrootVL：状态空间模型中，树状拓扑结构独领风骚。

发布时间：2024年06月04日

`LLM应用

理由：这篇论文介绍了GrootVL网络，它是一个多模态框架，适用于视觉与文本任务。论文中提到通过微调大型语言模型（LLM），在多个文本任务上以极低的训练成本实现了显著提升。这表明论文主要关注的是如何应用LLM来改进文本处理任务，因此属于LLM应用分类。虽然论文中涉及了模型的创新和改进，但其核心在于应用这些改进来提升特定任务的性能，而不是探讨LLM的理论基础或Agent的设计与实现。` `计算机视觉`

> GrootVL: Tree Topology is All You Need in State Space Model

# 摘要

> 状态空间模型通过递归特征传播，展现了与Transformer媲美的表示力，同时效率更胜一筹。但序列的几何限制使其在处理长距离依赖上略显不足。为此，我们开发了GrootVL网络，它首先依据空间关系和输入特征构建动态树状结构，进而基于此图进行特征传播，突破序列束缚，提升表示力。我们还引入了一种线性复杂度的动态规划算法，增强长距离交互，而不增加计算负担。GrootVL是一个多才多艺的多模态框架，适用于视觉与文本任务。实验证明，它在图像分类、目标检测和分割上远超现有结构化状态空间模型。通过微调大型语言模型，我们的方法在多个文本任务上以极低的训练成本实现了显著提升。

> The state space models, employing recursively propagated features, demonstrate strong representation capabilities comparable to Transformer models and superior efficiency. However, constrained by the inherent geometric constraints of sequences, it still falls short in modeling long-range dependencies. To address this issue, we propose the GrootVL network, which first dynamically generates a tree topology based on spatial relationships and input features. Then, feature propagation is performed based on this graph, thereby breaking the original sequence constraints to achieve stronger representation capabilities. Additionally, we introduce a linear complexity dynamic programming algorithm to enhance long-range interactions without increasing computational cost. GrootVL is a versatile multimodal framework that can be applied to both visual and textual tasks. Extensive experiments demonstrate that our method significantly outperforms existing structured state space models on image classification, object detection and segmentation. Besides, by fine-tuning large language models, our approach achieves consistent improvements in multiple textual tasks at minor training cost.

![GrootVL：状态空间模型中，树状拓扑结构独领风骚。](../../../paper_images/2406.02395/x1.png)

![GrootVL：状态空间模型中，树状拓扑结构独领风骚。](../../../paper_images/2406.02395/x2.png)

![GrootVL：状态空间模型中，树状拓扑结构独领风骚。](../../../paper_images/2406.02395/x3.png)

![GrootVL：状态空间模型中，树状拓扑结构独领风骚。](../../../paper_images/2406.02395/x4.png)

![GrootVL：状态空间模型中，树状拓扑结构独领风骚。](../../../paper_images/2406.02395/x5.png)

![GrootVL：状态空间模型中，树状拓扑结构独领风骚。](../../../paper_images/2406.02395/x6.png)

[Arxiv](https://arxiv.org/abs/2406.02395)