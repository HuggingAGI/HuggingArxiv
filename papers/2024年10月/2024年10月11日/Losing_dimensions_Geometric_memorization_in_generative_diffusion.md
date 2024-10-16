# 维度迷失：生成扩散中的几何记忆

发布时间：2024年10月11日

`其他` `物理学` `机器学习`

> Losing dimensions: Geometric memorization in generative diffusion

# 摘要

> 摘要：生成扩散模型是与统计物理学紧密相关的尖端机器学习模型。根据数据集和网络容量，它们的行为会从记忆模式过渡到泛化模式，这种现象被称为玻璃态相变。我们运用统计物理方法，将记忆化理论扩展至流形数据。理论与实验显示，不同切线子空间因记忆效应在不同临界时刻和数据集大小下丢失，这与数据局部方差有关。令人意外的是，某些条件下高方差子空间反而先丢失。这导致数据特征的选择性记忆，而非完全依赖单个训练点。我们在图像和线性流形数据集上的实验，验证了理论预测，取得了显著的定性一致。

> 
Abstract:Generative diffusion processes are state-of-the-art machine learning models deeply connected with fundamental concepts in statistical physics. Depending on the dataset size and the capacity of the network, their behavior is known to transition from an associative memory regime to a generalization phase in a phenomenon that has been described as a glassy phase transition. Here, using statistical physics techniques, we extend the theory of memorization in generative diffusion to manifold-supported data. Our theoretical and experimental findings indicate that different tangent subspaces are lost due to memorization effects at different critical times and dataset sizes, which depend on the local variance of the data along their directions. Perhaps counterintuitively, we find that, under some conditions, subspaces of higher variance are lost first due to memorization effects. This leads to a selective loss of dimensionality where some prominent features of the data are memorized without a full collapse on any individual training point. We validate our theory with a comprehensive set of experiments on networks trained both in image datasets and on linear manifolds, which result in a remarkable qualitative agreement with the theoretical predictions.
    

[Arxiv](https://arxiv.org/pdf/2410.08727)