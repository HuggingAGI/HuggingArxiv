# 通过高斯喷溅实现的开放世界场景的自动化 3D 物理模拟

发布时间：2024年11月19日

`LLM应用` `3D 模拟` `物理模拟`

> Automated 3D Physical Simulation of Open-world Scene with Gaussian Splatting

# 摘要

> 近期 3D 生成模型的进步为模拟动态 3D 对象运动和定制行为带来了新契机，然而创建此类内容仍困难重重。当下的方法往往需要为模拟手动设定精确的物理属性，或者依靠视频生成模型进行预测，这计算量极大。在本文中，我们重新审视了多模态大型语言模型（MLLM）在基于物理的模拟中的运用，并推出了 Sim Anything，这是一种基于物理的方法，给静态 3D 对象赋予了交互动态。我们先从细致的场景重建和对象级 3D 开放词汇分割入手，进而开展多视图图像修复。受人类视觉推理的启发，我们提出了基于 MLLM 的物理属性感知（MLLM-P3），能够以零样本的方式预测对象的平均物理属性。依据平均值和对象的几何形状，材料属性分布预测（MPDP）模型接着估算完整的分布，将问题转化为概率分布估计以降低计算成本。最后，我们借助物理 - 几何自适应采样（PGAS）策略采样的粒子在开放世界场景中模拟对象，有效捕捉复杂变形并大幅降低计算成本。大量实验和用户研究表明，我们的 Sim Anything 在单个 GPU 上两分钟内就能实现比前沿方法更逼真的运动。

> Recent advancements in 3D generation models have opened new possibilities for simulating dynamic 3D object movements and customizing behaviors, yet creating this content remains challenging. Current methods often require manual assignment of precise physical properties for simulations or rely on video generation models to predict them, which is computationally intensive. In this paper, we rethink the usage of multi-modal large language model (MLLM) in physics-based simulation, and present Sim Anything, a physics-based approach that endows static 3D objects with interactive dynamics. We begin with detailed scene reconstruction and object-level 3D open-vocabulary segmentation, progressing to multi-view image in-painting. Inspired by human visual reasoning, we propose MLLM-based Physical Property Perception (MLLM-P3) to predict mean physical properties of objects in a zero-shot manner. Based on the mean values and the object's geometry, the Material Property Distribution Prediction model (MPDP) model then estimates the full distribution, reformulating the problem as probability distribution estimation to reduce computational costs. Finally, we simulate objects in an open-world scene with particles sampled via the Physical-Geometric Adaptive Sampling (PGAS) strategy, efficiently capturing complex deformations and significantly reducing computational costs. Extensive experiments and user studies demonstrate our Sim Anything achieves more realistic motion than state-of-the-art methods within 2 minutes on a single GPU.

[Arxiv](https://arxiv.org/abs/2411.12789)