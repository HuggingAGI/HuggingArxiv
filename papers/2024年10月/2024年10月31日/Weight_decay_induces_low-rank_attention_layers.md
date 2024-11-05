# 权重衰减导致低秩注意力层

发布时间：2024年10月31日

`LLM理论` `神经网络`

> Weight decay induces low-rank attention layers

# 摘要

> 摘要：在训练深度神经网络时，诸如权重衰减等正则化器的效果尚未得到很好的理解。我们研究了在训练参数矩阵相乘相互作用的神经网络模型时，权重衰减以及 L2 正则化的影响。这种组合特别令人感兴趣，因为这种参数化在注意力层（变形器的主力）中很常见。在这里，关键-查询以及值-投影参数矩阵直接相互相乘：$W_K^TW_Q$ 和 $PW_V$。我们扩展了以前的结果，并一方面表明，形式为 $L(AB^	op) + \lambda (\|A\|^2 + \|B\|^2)$ 的 L2 正则化损失的任何局部最小值都与核范数正则化损失 $L(AB^	op) + \lambda\|AB^	op\|_*$ 的最小值重合，另一方面表明这两种损失在训练期间会以指数速度迅速变得相同。因此，我们补充了现有的将 L2 正则化与低秩正则化联系起来的工作，特别是解释了为什么这种对矩阵乘积的正则化会影响训练的早期阶段。基于这些理论见解，我们通过经验验证，在注意力层内的关键-查询和值-投影矩阵乘积 $W_K^TW_Q$、$PW_V$，当使用权重衰减进行优化时（如在视觉任务和语言建模中通常所做的那样），确实会导致 $W_K^TW_Q$ 和 $PW_V$ 的秩显著降低，即使在完全在线训练中也是如此。我们发现，与现有工作一致，在注意力矩阵乘积中诱导低秩会损害语言模型的性能，并观察到在将注意力层中的权重衰减与其余参数解耦时的优势。

> 
Abstract:The effect of regularizers such as weight decay when training deep neural networks is not well understood. We study the influence of weight decay as well as $L2$-regularization when training neural network models in which parameter matrices interact multiplicatively. This combination is of particular interest as this parametrization is common in attention layers, the workhorse of transformers. Here, key-query, as well as value-projection parameter matrices, are multiplied directly with each other: $W_K^TW_Q$ and $PW_V$. We extend previous results and show on one hand that any local minimum of a $L2$-regularized loss of the form $L(AB^\top) + \lambda (\|A\|^2 + \|B\|^2)$ coincides with a minimum of the nuclear norm-regularized loss $L(AB^\top) + \lambda\|AB^\top\|_*$, and on the other hand that the 2 losses become identical exponentially quickly during training. We thus complement existing works linking $L2$-regularization with low-rank regularization, and in particular, explain why such regularization on the matrix product affects early stages of training. Based on these theoretical insights, we verify empirically that the key-query and value-projection matrix products $W_K^TW_Q, PW_V$ within attention layers, when optimized with weight decay, as usually done in vision tasks and language modelling, indeed induce a significant reduction in the rank of $W_K^TW_Q$ and $PW_V$, even in fully online training. We find that, in accordance with existing work, inducing low rank in attention matrix products can damage language model performance, and observe advantages when decoupling weight decay in attention layers from the rest of the parameters.
    

[Arxiv](https://arxiv.org/pdf/2410.23819)