# ADOPT：修改后的 Adam 可以在任何 $β_2$ 下以最优速率收敛。

发布时间：2024年11月05日

`其他` `优化算法`

> ADOPT: Modified Adam Can Converge with Any $β_2$ with the Optimal Rate

# 摘要

> 摘要：Adam 是深度学习中最流行的优化算法之一。然而，众所周知，除非以问题相关的方式选择一个超参数，即 $eta_2$，Adam 在理论上不会收敛。已经有许多尝试来解决不收敛的问题（例如，AMSGrad），但它们需要一个不切实际的假设，即梯度噪声是均匀有界的。在本文中，我们提出了一种名为 ADOPT 的新的自适应梯度方法，它在任何选择的 $eta_2$ 下都能达到 $\mathcal{O} ( 1 / \sqrt{T} )$ 的最优收敛率，而不依赖于有界噪声假设。ADOPT 通过从二阶矩估计中去除当前梯度，并改变动量更新和二阶矩估计的归一化顺序，解决了 Adam 的不收敛问题。我们还进行了大量的数值实验，并验证了在包括图像分类、生成建模、自然语言处理和深度强化学习等广泛的任务中，我们的 ADOPT 与 Adam 及其变体相比取得了优越的结果。该实现可在这个 https URL 获得。

> 
Abstract:Adam is one of the most popular optimization algorithms in deep learning. However, it is known that Adam does not converge in theory unless choosing a hyperparameter, i.e., $\beta_2$, in a problem-dependent manner. There have been many attempts to fix the non-convergence (e.g., AMSGrad), but they require an impractical assumption that the gradient noise is uniformly bounded. In this paper, we propose a new adaptive gradient method named ADOPT, which achieves the optimal convergence rate of $\mathcal{O} ( 1 / \sqrt{T} )$ with any choice of $\beta_2$ without depending on the bounded noise assumption. ADOPT addresses the non-convergence issue of Adam by removing the current gradient from the second moment estimate and changing the order of the momentum update and the normalization by the second moment estimate. We also conduct intensive numerical experiments, and verify that our ADOPT achieves superior results compared to Adam and its variants across a wide range of tasks, including image classification, generative modeling, natural language processing, and deep reinforcement learning. The implementation is available at this https URL.
    

[Arxiv](https://arxiv.org/pdf/2411.02853)