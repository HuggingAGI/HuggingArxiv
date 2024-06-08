# 物理属性情境学习：快速适应分布外的分子图

发布时间：2024年06月03日

`Agent

理由：这篇论文探讨了如何通过情境学习结合几何感知图神经网络来预测非典型材料属性，特别是在结构属性预测领域。这种方法涉及构建一个复合模型，其中GPT-2与图神经网络协同工作，以优化情境信息的处理。这种集成模型可以被视为一个智能Agent，因为它能够处理复杂任务并作出决策，特别是在处理分布外示例时表现出色。这与Agent的定义相符，即一个能够感知环境并采取行动以达到目标的系统。因此，这篇论文更适合归类为Agent。` `材料科学` `机器学习`

> In-Context Learning of Physical Properties: Few-Shot Adaptation to Out-of-Distribution Molecular Graphs

# 摘要

> 大型语言模型通过情境学习，能够仅凭推理时提供的一系列示例，完成复杂的机器学习任务。本研究探索了是否能借助情境学习预测非典型材料属性，但这一挑战在结构属性预测领域尤为艰巨，除非我们能有效传递原子级几何特征至转换器模型。为此，我们构建了一个复合模型，其中GPT-2与几何感知图神经网络协同工作，以优化情境信息的处理。通过将QM9数据集中的分子按共同子结构分组，并用于情境学习，我们的模型在处理分布外示例时表现卓越，超越了传统图神经网络的性能。

> Large language models manifest the ability of few-shot adaptation to a sequence of provided examples. This behavior, known as in-context learning, allows for performing nontrivial machine learning tasks during inference only. In this work, we address the question: can we leverage in-context learning to predict out-of-distribution materials properties? However, this would not be possible for structure property prediction tasks unless an effective method is found to pass atomic-level geometric features to the transformer model. To address this problem, we employ a compound model in which GPT-2 acts on the output of geometry-aware graph neural networks to adapt in-context information. To demonstrate our model's capabilities, we partition the QM9 dataset into sequences of molecules that share a common substructure and use them for in-context learning. This approach significantly improves the performance of the model on out-of-distribution examples, surpassing the one of general graph neural network models.

![物理属性情境学习：快速适应分布外的分子图](../../../paper_images/2406.01808/toc.png)

![物理属性情境学习：快速适应分布外的分子图](../../../paper_images/2406.01808/ester_oxime.png)

![物理属性情境学习：快速适应分布外的分子图](../../../paper_images/2406.01808/mxmnet.png)

![物理属性情境学习：快速适应分布外的分子图](../../../paper_images/2406.01808/ablation.png)

[Arxiv](https://arxiv.org/abs/2406.01808)