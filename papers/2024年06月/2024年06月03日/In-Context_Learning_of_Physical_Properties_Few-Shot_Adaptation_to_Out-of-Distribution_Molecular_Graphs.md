# 物理属性情境学习：快速适应分布外的分子图结构

发布时间：2024年06月03日

`LLM应用

这篇论文探讨了如何利用大型语言模型（LLM）通过上下文学习来预测未知材料的特性，特别是在结构属性预测领域。研究者设计了一个结合GPT-2与几何感知图神经网络的复合模型，以有效地传递和利用原子级的几何信息。这种方法在处理QM9数据集中的未知分子时表现出了优越的性能，超越了传统的图神经网络模型。因此，这项工作属于LLM应用类别，因为它展示了LLM在特定任务（即材料特性预测）中的实际应用和效果。` `材料科学`

> In-Context Learning of Physical Properties: Few-Shot Adaptation to Out-of-Distribution Molecular Graphs

# 摘要

> 大型语言模型通过上下文学习，能够仅凭少量示例就适应新任务，这在推理阶段尤为重要。我们的研究聚焦于一个挑战：是否能借助上下文学习预测未知材料的特性？但这一目标在结构属性预测领域面临难题，除非我们能将原子级的几何信息有效传递给Transformer模型。为此，我们设计了一个结合GPT-2与几何感知图神经网络的复合模型，以捕捉并利用上下文信息。通过将QM9数据集中的分子按共享子结构分组，并进行上下文学习，我们的模型在处理未知材料时表现出色，其性能超越了传统图神经网络模型。

> Large language models manifest the ability of few-shot adaptation to a sequence of provided examples. This behavior, known as in-context learning, allows for performing nontrivial machine learning tasks during inference only. In this work, we address the question: can we leverage in-context learning to predict out-of-distribution materials properties? However, this would not be possible for structure property prediction tasks unless an effective method is found to pass atomic-level geometric features to the transformer model. To address this problem, we employ a compound model in which GPT-2 acts on the output of geometry-aware graph neural networks to adapt in-context information. To demonstrate our model's capabilities, we partition the QM9 dataset into sequences of molecules that share a common substructure and use them for in-context learning. This approach significantly improves the performance of the model on out-of-distribution examples, surpassing the one of general graph neural network models.

![物理属性情境学习：快速适应分布外的分子图结构](../../../paper_images/2406.01808/toc.png)

![物理属性情境学习：快速适应分布外的分子图结构](../../../paper_images/2406.01808/ester_oxime.png)

![物理属性情境学习：快速适应分布外的分子图结构](../../../paper_images/2406.01808/mxmnet.png)

![物理属性情境学习：快速适应分布外的分子图结构](../../../paper_images/2406.01808/ablation.png)

[Arxiv](https://arxiv.org/abs/2406.01808)