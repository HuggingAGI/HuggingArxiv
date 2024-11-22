# 释放基于结构的分子优化中梯度引导的强大力量

发布时间：2024年11月21日

`其他` `药物设计` `分子优化`

> Structure-Based Molecule Optimization via Gradient-Guided Bayesian Update

# 摘要

> 基于结构的分子优化（SBMO）旨在针对蛋白质靶点，对兼具连续坐标和离散类型的分子进行优化。一个颇具前景的方向是，鉴于其在图像领域的显著成就，对生成模型实施梯度引导。然而，引导离散数据颇具挑战，且存在模态间不一致的风险。为此，我们借助通过贝叶斯推理得出的连续且可微的空间，推出了分子联合优化（MolJO），这是首个基于梯度的SBMO框架，能在不同模态间提供联合引导信号，同时保持SE（3）-等变性。我们引入了新颖的后向校正策略，在过往历史的滑动窗口内进行优化，使得在优化过程中能在探索与利用之间实现无缝平衡。我们提出的MolJO在CrossDocked2020基准测试中表现卓越（成功率51.3％，Vina Dock -9.05和SA 0.78），成功率较基于梯度的同类方法提升4倍有余，“Me-Better”比率为3D基线的2倍。此外，我们将MolJO拓展至众多优化场景，涵盖多目标优化以及药物设计中的挑战性任务，如R-基团优化和支架跳跃，进一步凸显了其通用性和潜力。

> Structure-based molecule optimization (SBMO) aims to optimize molecules with both continuous coordinates and discrete types against protein targets. A promising direction is to exert gradient guidance on generative models given its remarkable success in images, but it is challenging to guide discrete data and risks inconsistencies between modalities. To this end, we leverage a continuous and differentiable space derived through Bayesian inference, presenting Molecule Joint Optimization (MolJO), the first gradient-based SBMO framework that facilitates joint guidance signals across different modalities while preserving SE(3)-equivariance. We introduce a novel backward correction strategy that optimizes within a sliding window of the past histories, allowing for a seamless trade-off between explore-and-exploit during optimization. Our proposed MolJO achieves state-of-the-art performance on CrossDocked2020 benchmark (Success Rate 51.3% , Vina Dock -9.05 and SA 0.78), more than 4x improvement in Success Rate compared to the gradient-based counterpart, and 2x "Me-Better" Ratio as much as 3D baselines. Furthermore, we extend MolJO to a wide range of optimization settings, including multi-objective optimization and challenging tasks in drug design such as R-group optimization and scaffold hopping, further underscoring its versatility and potential.

[Arxiv](https://arxiv.org/abs/2411.13280)