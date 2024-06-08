# Quixer：量子Transformer新模型

发布时间：2024年06月06日

`LLM理论

理由：这篇论文介绍了一种创新的量子机器学习模型Quixer，并将其应用于语言建模任务。虽然它涉及到了量子计算和语言模型的结合，但主要关注的是量子变压器模型的理论设计和性能评估，而不是具体的应用场景或Agent的行为。因此，它更符合LLM理论的分类，而不是Agent、RAG或LLM应用。` `量子计算` `机器学习`

> Quixer: A Quantum Transformer Model

# 摘要

> 随着可靠大规模量子计算机的发展，量子机器学习模型的设计研究日益受到关注。我们创新性地提出了Quixer：一种基于线性组合单位和量子奇异值变换的量子变压器模型。Quixer通过叠加令牌并施加可训练的非线性变换来运作。首次将量子变压器模型应用于实际语言建模任务，其表现与经典模型不相上下。我们还提供了量子硬件上的模型评估资源估算，并开放了经典模拟的开源实现。最后，我们展示了Quixer的灵活性，其参数化组件可替换为固定结构，从而衍生出新的量子变压器类别。

> Progress in the realisation of reliable large-scale quantum computers has motivated research into the design of quantum machine learning models. We present Quixer: a novel quantum transformer model which utilises the Linear Combination of Unitaries and Quantum Singular Value Transform primitives as building blocks. Quixer operates by preparing a superposition of tokens and applying a trainable non-linear transformation to this mix. We present the first results for a quantum transformer model applied to a practical language modelling task, obtaining results competitive with an equivalent classical baseline. In addition, we include resource estimates for evaluating the model on quantum hardware, and provide an open-source implementation for classical simulation. We conclude by highlighting the generality of Quixer, showing that its parameterised components can be substituted with fixed structures to yield new classes of quantum transformers.

![Quixer：量子Transformer新模型](../../../paper_images/2406.04305/x1.png)

![Quixer：量子Transformer新模型](../../../paper_images/2406.04305/x2.png)

[Arxiv](https://arxiv.org/abs/2406.04305)