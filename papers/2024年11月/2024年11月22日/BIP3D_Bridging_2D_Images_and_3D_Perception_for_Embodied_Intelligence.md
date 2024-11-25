# BIP3D：为实现具身智能，架起二维图像与三维感知之间的桥梁

发布时间：2024年11月22日

`其他` `具身智能` `3D 感知`

> BIP3D: Bridging 2D Images and 3D Perception for Embodied Intelligence

# 摘要

> 在具身智能系统里，3D 感知算法是关键的组成部分，能让智能体理解其周边环境。以往的算法主要依靠点云，虽说能提供精确的几何信息，可因其固有的稀疏性、噪声和数据稀缺，还是限制了感知性能。在本次研究中，我们推出了新颖的以图像为核心的 3D 感知模型 BIP3D，它借助具有明确 3D 位置编码的富有表现力的图像特征，克服了以点为核心的方法的局限。具体而言，我们运用预训练的 2D 视觉基础模型来强化语义理解，并引入空间增强模块来提升空间理解。这些模块共同促使 BIP3D 达成多视图、多模态特征融合以及端到端 3D 感知。在我们的实验里，BIP3D 在 EmbodiedScan 基准测试中超越了当前的顶尖成果，在 3D 检测任务中进步了 5.69%，在 3D 视觉基础任务中提高了 15.25%。

> In embodied intelligence systems, a key component is 3D perception algorithm, which enables agents to understand their surrounding environments. Previous algorithms primarily rely on point cloud, which, despite offering precise geometric information, still constrain perception performance due to inherent sparsity, noise, and data scarcity. In this work, we introduce a novel image-centric 3D perception model, BIP3D, which leverages expressive image features with explicit 3D position encoding to overcome the limitations of point-centric methods. Specifically, we leverage pre-trained 2D vision foundation models to enhance semantic understanding, and introduce a spatial enhancer module to improve spatial understanding. Together, these modules enable BIP3D to achieve multi-view, multi-modal feature fusion and end-to-end 3D perception. In our experiments, BIP3D outperforms current state-of-the-art results on the EmbodiedScan benchmark, achieving improvements of 5.69% in the 3D detection task and 15.25% in the 3D visual grounding task.

[Arxiv](https://arxiv.org/abs/2411.14869)