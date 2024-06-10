# 二阶RNN的张量分解视角

发布时间：2024年06月07日

`LLM理论

这篇论文主要探讨了二阶循环神经网络（2RNNs）及其变体CPRNN的理论性质，包括参数张量分解对模型表达力的影响，以及秩和隐藏大小对模型容量的影响。这些研究内容属于对大型语言模型（LLM）的理论分析和改进，因此归类为LLM理论。` `机器学习`

> A Tensor Decomposition Perspective on Second-order RNNs

# 摘要

> 二阶循环神经网络（2RNNs）通过引入序列间的二阶交互，提升了传统RNN的表达能力，并与形式语言理论中的模型有所关联。但庞大的参数张量使得计算变得棘手。为此，MIRNN限制了交互类型，而另一种策略则是通过张量分解减少参数。本研究聚焦于采用CP分解的2RNNs，即CPRNN。理论上，分解的秩会削弱模型的表达力。我们探讨了秩和隐藏大小对模型容量的影响，并揭示了RNN、2RNNs、MIRNNs与CPRNN在这些参数上的联系。通过Penn Treebank数据集的实验，我们验证了在固定参数预算下，CPRNN在恰当的秩和隐藏大小设置下，超越了其他模型。

> Second-order Recurrent Neural Networks (2RNNs) extend RNNs by leveraging second-order interactions for sequence modelling. These models are provably more expressive than their first-order counterparts and have connections to well-studied models from formal language theory. However, their large parameter tensor makes computations intractable. To circumvent this issue, one approach known as MIRNN consists in limiting the type of interactions used by the model. Another is to leverage tensor decomposition to diminish the parameter count. In this work, we study the model resulting from parameterizing 2RNNs using the CP decomposition, which we call CPRNN. Intuitively, the rank of the decomposition should reduce expressivity. We analyze how rank and hidden size affect model capacity and show the relationships between RNNs, 2RNNs, MIRNNs, and CPRNNs based on these parameters. We support these results empirically with experiments on the Penn Treebank dataset which demonstrate that, with a fixed parameter budget, CPRNNs outperforms RNNs, 2RNNs, and MIRNNs with the right choice of rank and hidden size.

[Arxiv](https://arxiv.org/abs/2406.05045)