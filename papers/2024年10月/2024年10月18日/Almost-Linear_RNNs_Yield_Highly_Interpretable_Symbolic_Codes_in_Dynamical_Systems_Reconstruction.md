# 在动力系统重建中，近乎线性的 RNN 产生了高度可解释的符号代码。

发布时间：2024年10月18日

`其他` `动力系统`

> Almost-Linear RNNs Yield Highly Interpretable Symbolic Codes in Dynamical Systems Reconstruction

# 摘要

> 摘要：动力系统（DS）理论对于科学和工程的许多领域都是基础的。它可以为随时间演变的系统的行为提供深刻的见解，通常由微分或递归方程来描述。促进 DS 模型的数学可处理性和可解释性的常见方法包括将非线性 DS 分解为通过切换流形分隔的多个线性 DS，即分段线性（PWL）系统。PWL 模型在工程中很受欢迎，并且在数学中经常被选择用于分析 DS 的拓扑特性。然而，手工制作这样的模型是繁琐的，并且仅适用于非常低维的场景，而从数据推断它们通常会产生具有非常多线性子区域的不必要的复杂表示。在这里，我们引入了近似线性循环神经网络（AL-RNNs），它可以从时间序列数据中自动且稳健地生成 DS 的最简约 PWL 表示，尽可能使用少的 PWL 非线性。AL-RNNs 可以使用任何用于动力系统重建（DSR）的 SOTA 算法进行有效训练，并且自然地产生底层 DS 的符号编码，可证明保留重要的拓扑特性。我们表明，对于洛伦兹和罗斯勒系统，AL-RNNs 以纯数据驱动的方式发现了相应混沌吸引子的已知拓扑最小 PWL 表示。我们进一步在两个具有挑战性的经验数据集上说明，可以实现动态的可解释符号编码，极大地促进了对底层系统的数学和计算分析。

> 
Abstract:Dynamical systems (DS) theory is fundamental for many areas of science and engineering. It can provide deep insights into the behavior of systems evolving in time, as typically described by differential or recursive equations. A common approach to facilitate mathematical tractability and interpretability of DS models involves decomposing nonlinear DS into multiple linear DS separated by switching manifolds, i.e. piecewise linear (PWL) systems. PWL models are popular in engineering and a frequent choice in mathematics for analyzing the topological properties of DS. However, hand-crafting such models is tedious and only possible for very low-dimensional scenarios, while inferring them from data usually gives rise to unnecessarily complex representations with very many linear subregions. Here we introduce Almost-Linear Recurrent Neural Networks (AL-RNNs) which automatically and robustly produce most parsimonious PWL representations of DS from time series data, using as few PWL nonlinearities as possible. AL-RNNs can be efficiently trained with any SOTA algorithm for dynamical systems reconstruction (DSR), and naturally give rise to a symbolic encoding of the underlying DS that provably preserves important topological properties. We show that for the Lorenz and Rössler systems, AL-RNNs discover, in a purely data-driven way, the known topologically minimal PWL representations of the corresponding chaotic attractors. We further illustrate on two challenging empirical datasets that interpretable symbolic encodings of the dynamics can be achieved, tremendously facilitating mathematical and computational analysis of the underlying systems.
    

[Arxiv](https://arxiv.org/pdf/2410.14240)