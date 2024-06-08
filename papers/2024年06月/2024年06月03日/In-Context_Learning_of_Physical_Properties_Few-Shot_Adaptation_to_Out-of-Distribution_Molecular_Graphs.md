# 物理属性的上下文学习：快速适应分布外的分子图

发布时间：2024年06月03日

`Agent

理由：这篇论文探讨了如何利用大型语言模型（如GPT-2）与几何感知图神经网络结合，以优化情境信息的处理，并应用于预测非典型材料属性。这种结合模型可以被视为一个智能Agent，它通过情境学习适应新任务，并在特定领域（如材料科学）中进行推理和预测。因此，这篇论文更符合Agent分类，因为它涉及构建和应用一个能够处理特定任务的智能系统。` `材料科学` `机器学习`

> In-Context Learning of Physical Properties: Few-Shot Adaptation to Out-of-Distribution Molecular Graphs

# 摘要

> 大型语言模型通过情境学习，能够仅凭少量示例就适应新任务，这种能力在推理时尤为显著。我们在此研究中提出疑问：是否能借助情境学习预测非典型材料属性？然而，在结构属性预测领域，这一设想受限于如何将原子级几何特征有效传递给变压器模型。为此，我们构建了一个复合模型，其中GPT-2与几何感知图神经网络协同工作，以优化情境信息的处理。通过将QM9数据集中的分子按共同子结构分组，并以此进行情境学习，我们的模型在处理非典型示例时表现出色，超越了传统图神经网络的性能。

> Large language models manifest the ability of few-shot adaptation to a sequence of provided examples. This behavior, known as in-context learning, allows for performing nontrivial machine learning tasks during inference only. In this work, we address the question: can we leverage in-context learning to predict out-of-distribution materials properties? However, this would not be possible for structure property prediction tasks unless an effective method is found to pass atomic-level geometric features to the transformer model. To address this problem, we employ a compound model in which GPT-2 acts on the output of geometry-aware graph neural networks to adapt in-context information. To demonstrate our model's capabilities, we partition the QM9 dataset into sequences of molecules that share a common substructure and use them for in-context learning. This approach significantly improves the performance of the model on out-of-distribution examples, surpassing the one of general graph neural network models.

![物理属性的上下文学习：快速适应分布外的分子图](../../../paper_images/2406.01808/toc.png)

![物理属性的上下文学习：快速适应分布外的分子图](../../../paper_images/2406.01808/ester_oxime.png)

![物理属性的上下文学习：快速适应分布外的分子图](../../../paper_images/2406.01808/mxmnet.png)

![物理属性的上下文学习：快速适应分布外的分子图](../../../paper_images/2406.01808/ablation.png)

[Arxiv](https://arxiv.org/abs/2406.01808)