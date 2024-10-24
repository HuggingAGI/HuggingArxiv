# 几何轨迹扩散模型

发布时间：2024年10月16日

`其他` `自然科学` `3D 几何系统`

> Geometric Trajectory Diffusion Models

# 摘要

> 摘要：生成模型在生成 3D 几何系统方面显示出巨大的前景，这在许多自然科学领域，如分子和蛋白质设计中是一个基本问题。然而，现有的方法仅对静态结构起作用，忽略了物理系统本质上总是动态的这一事实。在这项工作中，我们提出了几何轨迹扩散模型（GeoTDM），这是第一个用于对 3D 几何轨迹的时间分布进行建模的扩散模型。对这种分布进行建模具有挑战性，因为它需要捕获具有物理对称性的复杂空间相互作用以及动态中封装的时间对应关系。我们从理论上证明，具有等变时间核的扩散模型可以导致具有所需对称性的密度，并开发了一种利用 SE(3)-等变空间卷积和时间注意力的新型转换核。此外，为了在有条件生成中诱导出一种富有表现力的轨迹分布，我们在前向扩散过程中引入了一种广义的可学习几何先验，以增强时间条件。我们在各种场景下对无条件和有条件生成进行了广泛的实验，包括物理模拟、分子动力学和行人运动。在一系列广泛的指标上的实证结果表明，GeoTDM 可以生成具有显著更高质量的逼真的几何轨迹。

> 
Abstract:Generative models have shown great promise in generating 3D geometric systems, which is a fundamental problem in many natural science domains such as molecule and protein design. However, existing approaches only operate on static structures, neglecting the fact that physical systems are always dynamic in nature. In this work, we propose geometric trajectory diffusion models (GeoTDM), the first diffusion model for modeling the temporal distribution of 3D geometric trajectories. Modeling such distribution is challenging as it requires capturing both the complex spatial interactions with physical symmetries and temporal correspondence encapsulated in the dynamics. We theoretically justify that diffusion models with equivariant temporal kernels can lead to density with desired symmetry, and develop a novel transition kernel leveraging SE(3)-equivariant spatial convolution and temporal attention. Furthermore, to induce an expressive trajectory distribution for conditional generation, we introduce a generalized learnable geometric prior into the forward diffusion process to enhance temporal conditioning. We conduct extensive experiments on both unconditional and conditional generation in various scenarios, including physical simulation, molecular dynamics, and pedestrian motion. Empirical results on a wide suite of metrics demonstrate that GeoTDM can generate realistic geometric trajectories with significantly higher quality.
    

[Arxiv](https://arxiv.org/pdf/2410.13027)