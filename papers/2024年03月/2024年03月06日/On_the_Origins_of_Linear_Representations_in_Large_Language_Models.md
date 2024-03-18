# [本文深入探讨大型语言模型内部线性表示的起源，揭示其内在机理与构建过程。]

发布时间：2024年03月06日

`LLM理论`

> On the Origins of Linear Representations in Large Language Models

> 最近有研究指出，在大型语言模型的表达空间里，高级别的语义概念以“线性”方式被编码。本研究深入探究了这一线性表示背后的成因，通过构建一个简洁的潜在变量模型来抽象并规范下个标记预测的概念变化规律。借助这一理论框架，我们揭示了下个标记预测目标（即交叉熵softmax函数）以及梯度下降的内在偏置共同推动了概念的线性表示形成。实验证明，在符合潜在变量模型的数据上进行学习时，确实能观察到线性表示的涌现，进一步确认了这一简洁模型结构足以催生线性表示。同时，我们使用LLaMA-2大型语言模型验证了该理论的部分预测，为简化模型能提供通用洞察力提供了有力证据。

> Recent works have argued that high-level semantic concepts are encoded "linearly" in the representation space of large language models. In this work, we study the origins of such linear representations. To that end, we introduce a simple latent variable model to abstract and formalize the concept dynamics of the next token prediction. We use this formalism to show that the next token prediction objective (softmax with cross-entropy) and the implicit bias of gradient descent together promote the linear representation of concepts. Experiments show that linear representations emerge when learning from data matching the latent variable model, confirming that this simple structure already suffices to yield linear representations. We additionally confirm some predictions of the theory using the LLaMA-2 large language model, giving evidence that the simplified model yields generalizable insights.

[Arxiv](https://arxiv.org/abs/2403.03867)