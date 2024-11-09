# 理解深度学习中具有中心流的优化

发布时间：2024年10月31日

`其他` `优化算法`

> Understanding Optimization in Deep Learning with Central Flows

# 摘要

> 摘要：深度学习中的优化仍然知之甚少，即使在确定性（即全批次）训练的简单设置中也是如此。一个关键的困难是，优化器的许多行为是由复杂的振荡动力学隐式决定的，被称为“稳定性边缘”。本文的主要贡献在于表明，优化器的隐式行为可以通过“中心流”明确捕获：一个微分方程，它对时间平均的优化轨迹进行建模。我们表明，这些流可以凭经验以高度的数值精度预测通用神经网络的长期优化轨迹。通过解释这些流，我们首次揭示了 1）RMSProp 适应局部损失景观的确切意义，以及 2）一种“通过正则化加速”的机制，其中自适应优化器隐式地朝着低曲率区域导航，在这些区域它们可以采取更大的步骤。这种机制是这些自适应优化器有效性的关键。总的来说，我们认为中心流构成了一个有前途的工具，用于推理深度学习中的优化。

> 
Abstract:Optimization in deep learning remains poorly understood, even in the simple setting of deterministic (i.e. full-batch) training. A key difficulty is that much of an optimizer's behavior is implicitly determined by complex oscillatory dynamics, referred to as the "edge of stability." The main contribution of this paper is to show that an optimizer's implicit behavior can be explicitly captured by a "central flow:" a differential equation which models the time-averaged optimization trajectory. We show that these flows can empirically predict long-term optimization trajectories of generic neural networks with a high degree of numerical accuracy. By interpreting these flows, we reveal for the first time 1) the precise sense in which RMSProp adapts to the local loss landscape, and 2) an "acceleration via regularization" mechanism, wherein adaptive optimizers implicitly navigate towards low-curvature regions in which they can take larger steps. This mechanism is key to the efficacy of these adaptive optimizers. Overall, we believe that central flows constitute a promising tool for reasoning about optimization in deep learning.
    

[Arxiv](https://arxiv.org/pdf/2410.24206)