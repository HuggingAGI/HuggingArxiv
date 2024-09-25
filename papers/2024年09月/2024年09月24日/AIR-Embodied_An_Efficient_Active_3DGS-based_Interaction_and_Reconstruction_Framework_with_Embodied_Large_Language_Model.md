# AIR-Embodied：一个高效结合3DGS和具身大型语言模型的主动交互与重建框架

发布时间：2024年09月24日

`Agent` `计算机视觉` `机器人`

> AIR-Embodied: An Efficient Active 3DGS-based Interaction and Reconstruction Framework with Embodied Large Language Model

# 摘要

> 近期，3D重建与神经渲染技术的进步虽提升了数字资产的质量，但在处理多样化的物体形状、纹理及遮挡时，现有方法仍显不足。尽管Next Best View (NBV)规划与基于学习的方法有所贡献，但它们常受限于预设标准，难以像人类般灵活应对遮挡。为此，我们推出了AIR-Embodied框架，它巧妙融合了具身AI与大规模预训练的多模态语言模型，旨在优化主动3DGS重建。AIR-Embodied通过三步走策略：首先，借助多模态提示精准把握重建现状；其次，通过视角选择与交互动作精心规划任务；最后，运用闭环推理确保执行无误。AI代理还能根据计划与实际效果的差异，灵活调整策略。实验证明，无论在虚拟还是现实环境中，AIR-Embodied均大幅提升了重建的效率与品质，为主动3D重建领域带来了强有力的解决方案。

> Recent advancements in 3D reconstruction and neural rendering have enhanced the creation of high-quality digital assets, yet existing methods struggle to generalize across varying object shapes, textures, and occlusions. While Next Best View (NBV) planning and Learning-based approaches offer solutions, they are often limited by predefined criteria and fail to manage occlusions with human-like common sense. To address these problems, we present AIR-Embodied, a novel framework that integrates embodied AI agents with large-scale pretrained multi-modal language models to improve active 3DGS reconstruction. AIR-Embodied utilizes a three-stage process: understanding the current reconstruction state via multi-modal prompts, planning tasks with viewpoint selection and interactive actions, and employing closed-loop reasoning to ensure accurate execution. The agent dynamically refines its actions based on discrepancies between the planned and actual outcomes. Experimental evaluations across virtual and real-world environments demonstrate that AIR-Embodied significantly enhances reconstruction efficiency and quality, providing a robust solution to challenges in active 3D reconstruction.

[Arxiv](https://arxiv.org/abs/2409.16019)