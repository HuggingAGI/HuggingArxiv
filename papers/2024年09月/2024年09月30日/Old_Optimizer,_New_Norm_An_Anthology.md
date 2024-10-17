# 经典优化器，焕发新规：精选集

发布时间：2024年09月30日

`LLM理论` `机器学习` `人工智能`

> Old Optimizer, New Norm: An Anthology

# 摘要

> 深度学习优化器常结合凸理论与近似二阶理论。我们选取了 Adam、Shampoo 和 Prodigy 三种方法，并认为它们均可视为无凸性假设的一阶方法。关闭指数移动平均后，这些方法在特定范数下等同于最陡下降。由此，我们开辟了新的训练算法设计空间。根据张量在网络中的角色，应为其分配不同的算子范数。例如，尽管线性与嵌入层的权重空间相同，但角色不同，范数也应不同。我们期待这种精细度量神经架构的方法能带来更稳定、可扩展且更快的训练效果。

> 
Abstract:Deep learning optimizers are often motivated through a mix of convex and approximate second-order theory. We select three such methods -- Adam, Shampoo and Prodigy -- and argue that each method can instead be understood as a squarely first-order method without convexity assumptions. In fact, after switching off exponential moving averages, each method is equivalent to steepest descent under a particular norm. By generalizing this observation, we chart a new design space for training algorithms. Different operator norms should be assigned to different tensors based on the role that the tensor plays within the network. For example, while linear and embedding layers may have the same weight space of $\mathbb{R}^{m\times n}$, these layers play different roles and should be assigned different norms. We hope that this idea of carefully metrizing the neural architecture might lead to more stable, scalable and indeed faster training.
    

[Arxiv](https://arxiv.org/pdf/2409.20325)