# 优化平滑函数，全凭比较之力

发布时间：2024年05月19日

`Agent

理由：这篇论文主要探讨了在强化学习领域中，如何通过基于偏好的方法（即仅通过比较选项）来优化平滑函数。这种方法特别适用于大型语言模型中的人类反馈强化学习。论文中提出的算法和理论分析，虽然涉及到了大型语言模型（LLM），但其核心在于优化算法和强化学习策略，这与Agent的行为和决策优化紧密相关。因此，将其归类为Agent更为合适。` `机器学习优化`

> Comparisons Are All You Need for Optimizing Smooth Functions

# 摘要

> 在优化机器学习模型时，梯度计算有时会变得棘手甚至不可能。特别是在强化学习领域，基于偏好的方法，仅通过比较选项，已广泛应用于如大型语言模型中的人类反馈强化学习。本文深入探讨了在仅有一个能比较两处函数值并指出较大者的神谕的情况下，如何优化平滑函数 $f\colon\mathbb{R}^n\to\mathbb{R}$。对于凸函数 $f$，我们提出了两种算法，分别通过 $\tilde{O}(n/ε)$ 和 $\tilde{O}(n^{2})$ 次比较查询，精准定位 $ε$-最优解。而对于非凸函数，我们的算法仅需 $\tilde{O}(n/ε^2)$ 次比较查询，即可找到近似稳定点。这些成果与依赖于 $n$ 的最佳零阶算法相当，暗示了“比较即优化”的理念。此外，我们还设计了一种算法，通过 $\tilde{O}(n^{1.5}/ε^{2.5})$ 次比较查询，帮助逃离鞍点，达到非凸函数的 $ε$-二阶稳定点。

> When optimizing machine learning models, there are various scenarios where gradient computations are challenging or even infeasible. Furthermore, in reinforcement learning (RL), preference-based RL that only compares between options has wide applications, including reinforcement learning with human feedback in large language models. In this paper, we systematically study optimization of a smooth function $f\colon\mathbb{R}^n\to\mathbb{R}$ only assuming an oracle that compares function values at two points and tells which is larger. When $f$ is convex, we give two algorithms using $\tilde{O}(n/ε)$ and $\tilde{O}(n^{2})$ comparison queries to find an $ε$-optimal solution, respectively. When $f$ is nonconvex, our algorithm uses $\tilde{O}(n/ε^2)$ comparison queries to find an $ε$-approximate stationary point. All these results match the best-known zeroth-order algorithms with function evaluation queries in $n$ dependence, thus suggest that \emph{comparisons are all you need for optimizing smooth functions using derivative-free methods}. In addition, we also give an algorithm for escaping saddle points and reaching an $ε$-second order stationary point of a nonconvex $f$, using $\tilde{O}(n^{1.5}/ε^{2.5})$ comparison queries.

[Arxiv](https://arxiv.org/abs/2405.11454)