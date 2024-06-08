# 物理属性情境学习：快速适应分布外的分子图结构

发布时间：2024年06月03日

`LLM应用

这篇论文探讨了大型语言模型（LLM）在上下文学习中的应用，特别是在预测非典型材料属性方面的能力。通过结合GPT-2与几何感知图神经网络，研究者设计了一种复合模型来优化上下文信息的处理，并在处理分布外示例时展示了优越的性能。这种应用展示了LLM在特定领域（如材料科学）中的实际应用潜力，因此属于LLM应用分类。` `材料科学` `机器学习`

> In-Context Learning of Physical Properties: Few-Shot Adaptation to Out-of-Distribution Molecular Graphs

# 摘要

> 大型语言模型通过上下文学习，能够仅凭少量示例就适应新任务，这种能力在推理阶段尤为突出。我们研究的核心问题是：能否借助上下文学习预测非典型材料属性？对于结构属性预测，这一挑战在于如何将原子级几何特征有效传递给变压器模型。为此，我们设计了一种结合GPT-2与几何感知图神经网络的复合模型，以优化上下文信息的处理。通过将QM9数据集中的分子按共享子结构分组，并进行上下文学习，我们的模型在处理分布外示例时表现出色，超越了传统图神经网络模型。

> Large language models manifest the ability of few-shot adaptation to a sequence of provided examples. This behavior, known as in-context learning, allows for performing nontrivial machine learning tasks during inference only. In this work, we address the question: can we leverage in-context learning to predict out-of-distribution materials properties? However, this would not be possible for structure property prediction tasks unless an effective method is found to pass atomic-level geometric features to the transformer model. To address this problem, we employ a compound model in which GPT-2 acts on the output of geometry-aware graph neural networks to adapt in-context information. To demonstrate our model's capabilities, we partition the QM9 dataset into sequences of molecules that share a common substructure and use them for in-context learning. This approach significantly improves the performance of the model on out-of-distribution examples, surpassing the one of general graph neural network models.

![物理属性情境学习：快速适应分布外的分子图结构](../../../paper_images/2406.01808/toc.png)

![物理属性情境学习：快速适应分布外的分子图结构](../../../paper_images/2406.01808/ester_oxime.png)

![物理属性情境学习：快速适应分布外的分子图结构](../../../paper_images/2406.01808/mxmnet.png)

![物理属性情境学习：快速适应分布外的分子图结构](../../../paper_images/2406.01808/ablation.png)

[Arxiv](https://arxiv.org/abs/2406.01808)