# 无梯度优化：集成方法

发布时间：2024年08月01日

`LLM理论` `机器学习` `优化算法`

> Gradient-free optimization via integration

# 摘要

> 摘要：本文提出了一种新颖的通用算法，用于优化非凸、非可微甚至非连续的函数 $l\colon \mathbb{R}^d \rightarrow \mathbb{R}$。核心思想是通过贝叶斯更新和重新投影，依次拟合具有集中性质的参数化概率密度。选择指数族序列时，重新投影简化为期望计算，便于蒙特卡罗近似。该算法简单易行，并在机器学习分类任务中展示了其性能。此外，该方法适用于仅能获取噪声测量值的场景，保持了简易性和高效性。理论分析表明，该框架可视为在平滑近似上隐式执行时间非均匀梯度下降，为算法收敛性和理论保证提供了可能。同时，我们为非均匀梯度下降算法提供了新的理论成果。

> 
Abstract:In this paper we propose a novel, general purpose, algorithm to optimize functions $l\colon \mathbb{R}^d \rightarrow \mathbb{R}$ not assumed to be convex or differentiable or even continuous. The main idea is to sequentially fit a sequence of parametric probability densities, possessing a concentration property, to $l$ using a Bayesian update followed by a reprojection back onto the chosen parametric sequence. Remarkably, with the sequence chosen to be from the exponential family, reprojection essentially boils down to the computation of expectations. Our algorithm therefore lends itself to Monte Carlo approximation, ranging from plain to Sequential Monte Carlo (SMC) methods.
The algorithm is therefore particularly simple to implement and we illustrate performance on a challenging Machine Learning classification problem. Our methodology naturally extends to the scenario where only noisy measurements of $l$ are available and retains ease of implementation and performance. At a theoretical level we establish, in a fairly general scenario, that our framework can be viewed as implicitly implementing a time inhomogeneous gradient descent algorithm on a sequence of smoothed approximations of $l$. This opens the door to establishing convergence of the algorithm and provide theoretical guarantees. Along the way, we establish new results for inhomogeneous gradient descent algorithms of independent interest.
    

[Arxiv](https://arxiv.org/pdf/2408.00888)