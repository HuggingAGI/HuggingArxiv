# 神经空间交互模型中的起源-目的地矩阵生成

发布时间：2024年10月09日

`Agent` `流行病学`

> Generating Origin-Destination Matrices in Neural Spatial Interaction Models

# 摘要

> 基于代理的模型 (ABMs) 在交通、经济和流行病学等领域的决策工具中日益普及。这些模型中的关键对象是起点-终点矩阵，它记录了地点间的交互和行程。现有方法通过连续近似和临时离散化来处理该矩阵，这限制了对部分观测数据的调整，无法全面探索矩阵分布，并引入了误差。为此，我们提出了一种高效框架，直接在离散空间上操作，并通过神经微分方程学习行程强度。该框架在重建精度和覆盖率上超越了现有技术，且计算成本大幅降低。我们在剑桥和华盛顿特区的大规模模型中验证了这些优势。

> Agent-based models (ABMs) are proliferating as decision-making tools across policy areas in transportation, economics, and epidemiology. In these models, a central object of interest is the discrete origin-destination matrix which captures spatial interactions and agent trip counts between locations. Existing approaches resort to continuous approximations of this matrix and subsequent ad-hoc discretisations in order to perform ABM simulation and calibration. This impedes conditioning on partially observed summary statistics, fails to explore the multimodal matrix distribution over a discrete combinatorial support, and incurs discretisation errors. To address these challenges, we introduce a computationally efficient framework that scales linearly with the number of origin-destination pairs, operates directly on the discrete combinatorial space, and learns the agents' trip intensity through a neural differential equation that embeds spatial interactions. Our approach outperforms the prior art in terms of reconstruction error and ground truth matrix coverage, at a fraction of the computational cost. We demonstrate these benefits in large-scale spatial mobility ABMs in Cambridge, UK and Washington, DC, USA.

[Arxiv](https://arxiv.org/abs/2410.07352)