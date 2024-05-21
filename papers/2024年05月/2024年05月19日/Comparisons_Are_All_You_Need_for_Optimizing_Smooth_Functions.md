# 优化平滑函数，关键在于比较

发布时间：2024年05月19日

`LLM理论

这篇论文主要探讨了在机器学习模型优化中，特别是在强化学习领域，如何通过比较函数值而非依赖梯度信息来优化光滑函数。论文中提出的算法针对凸函数和非凸函数，通过比较查询次数来找到近似最优解或稳定点。这些研究成果展示了“比较即优化”的理念，并且与现有的零阶算法性能相当。由于这些研究是关于优化算法和理论的，特别是在语言模型（LLM）的背景下，因此将其归类为LLM理论。` `机器学习`

> Comparisons Are All You Need for Optimizing Smooth Functions

# 摘要

> 在优化机器学习模型时，梯度计算有时会变得复杂甚至不可行。特别是在强化学习领域，基于偏好的方法通过简单的选项比较就能广泛应用，如在大规模语言模型中结合人类反馈的强化学习。本文深入探讨了如何仅通过比较两个点的函数值来优化光滑函数 $f$，无需梯度信息。对于凸函数 $f$，我们设计了两种算法，分别以 $\tilde{O}(n/ε)$ 和 $\tilde{O}(n^{2})$ 次比较查询找到近似最优解。对于非凸函数，我们的算法以 $\tilde{O}(n/ε^2)$ 次比较查询找到近似稳定点，这些结果与最佳的零阶算法相当，证明了“比较即优化”的理念。此外，我们还开发了一种算法，帮助模型逃离鞍点，达到非凸函数的 $ε$-二阶稳定点，仅需 $\tilde{O}(n^{1.5}/ε^{2.5})$ 次比较查询。

> When optimizing machine learning models, there are various scenarios where gradient computations are challenging or even infeasible. Furthermore, in reinforcement learning (RL), preference-based RL that only compares between options has wide applications, including reinforcement learning with human feedback in large language models. In this paper, we systematically study optimization of a smooth function $f\colon\mathbb{R}^n\to\mathbb{R}$ only assuming an oracle that compares function values at two points and tells which is larger. When $f$ is convex, we give two algorithms using $\tilde{O}(n/ε)$ and $\tilde{O}(n^{2})$ comparison queries to find an $ε$-optimal solution, respectively. When $f$ is nonconvex, our algorithm uses $\tilde{O}(n/ε^2)$ comparison queries to find an $ε$-approximate stationary point. All these results match the best-known zeroth-order algorithms with function evaluation queries in $n$ dependence, thus suggest that \emph{comparisons are all you need for optimizing smooth functions using derivative-free methods}. In addition, we also give an algorithm for escaping saddle points and reaching an $ε$-second order stationary point of a nonconvex $f$, using $\tilde{O}(n^{1.5}/ε^{2.5})$ comparison queries.

[Arxiv](https://arxiv.org/abs/2405.11454)