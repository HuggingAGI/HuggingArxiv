# GLU 变体改进了 Transformer

发布时间：2020年02月12日

`LLM理论`

> GLU Variants Improve Transformer

# 摘要

> 摘要：门控线性单元（arXiv:1612.08083）由两个线性投影的逐元素乘积组成，其中一个首先通过一个 S 型函数。GLU 存在变体，可以使用不同的非线性（甚至线性）函数代替 S 型函数。我们在 Transformer（arXiv:1706.03762）序列到序列模型的前馈子层中测试了这些变体，并发现其中一些变体在质量上比通常使用的 ReLU 或 GELU 激活函数有所提高。

> 
Abstract:Gated Linear Units (arXiv:1612.08083) consist of the component-wise product of two linear projections, one of which is first passed through a sigmoid function. Variations on GLU are possible, using different nonlinear (or even linear) functions in place of sigmoid. We test these variants in the feed-forward sublayers of the Transformer (arXiv:1706.03762) sequence-to-sequence model, and find that some of them yield quality improvements over the typically-used ReLU or GELU activations.
    

[Arxiv](https://arxiv.org/pdf/2002.05202)