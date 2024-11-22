# 挖掘多模态基础模型和视频扩散在 4D 动态物理场景模拟中的潜力

发布时间：2024年11月21日

`其他` `计算机图形学` `物理模拟`

> Unleashing the Potential of Multi-modal Foundation Models and Video Diffusion for 4D Dynamic Physical Scene Simulation

# 摘要

> 要逼真地模拟动态场景，就得精确捕捉各类材料特性，并依据物理原理对复杂的物体交互进行建模。但现有的方法受限于基础材料类型，其可预测参数有限，难以展现现实世界材料的复杂性。我们推出了一种新方法，借助多模态基础模型和视频扩散来强化 4D 动态场景模拟。我们的方法通过多模态模型，依据图像查询来识别材料类型并初始化材料参数，同时推导出用于详细场景呈现的 3D 高斯斑点。我们还利用带有可微材料点法（MPM）和光流引导的视频扩散，而非渲染损失或分数蒸馏采样（SDS）损失，来进一步优化这些材料参数。这一集成框架能够在现实场景中精准预测并逼真模拟动态交互，提升了基于物理模拟的准确性与灵活性。

> Realistic simulation of dynamic scenes requires accurately capturing diverse material properties and modeling complex object interactions grounded in physical principles. However, existing methods are constrained to basic material types with limited predictable parameters, making them insufficient to represent the complexity of real-world materials. We introduce a novel approach that leverages multi-modal foundation models and video diffusion to achieve enhanced 4D dynamic scene simulation. Our method utilizes multi-modal models to identify material types and initialize material parameters through image queries, while simultaneously inferring 3D Gaussian splats for detailed scene representation. We further refine these material parameters using video diffusion with a differentiable Material Point Method (MPM) and optical flow guidance rather than render loss or Score Distillation Sampling (SDS) loss. This integrated framework enables accurate prediction and realistic simulation of dynamic interactions in real-world scenarios, advancing both accuracy and flexibility in physics-based simulations.

[Arxiv](https://arxiv.org/abs/2411.14423)