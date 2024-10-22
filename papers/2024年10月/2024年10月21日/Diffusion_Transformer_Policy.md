# 扩散变压器策略

发布时间：2024年10月21日

`Agent` `机器人` `人工智能`

> Diffusion Transformer Policy

# 摘要

> 最近，预训练于多样化机器人数据集的大型视觉-语言动作模型展示了通过少量域内数据泛化到新环境的潜力。然而，这些方法通常通过小型动作头预测离散或连续动作，限制了处理多样化动作空间的能力。相比之下，我们采用大型多模态扩散变换器建模连续动作，称为扩散变换器策略，直接通过大型变换器模型去噪动作块，而非小型动作头。借助变换器的扩展能力，该方法能有效建模大型多样化机器人数据集中的连续末端执行器动作，实现更佳泛化性能。实验证明，预训练于多样化机器人数据的扩散变换器策略可泛化至不同实体，包括Maniskill2、Calvin模拟环境及现实世界的Franka臂。具体而言，在Calvin新任务设置（ABC->D）中，仅用单一第三视角摄像头流，该方法即达最先进性能，将连续完成任务平均数从5提升至3.6，预训练阶段显著提升Calvin上成功序列长度超1.2。代码将公开。

> Recent large visual-language action models pretrained on diverse robot datasets have demonstrated the potential for generalizing to new environments with a few in-domain data. However, those approaches usually predict discretized or continuous actions by a small action head, which limits the ability in handling diverse action spaces. In contrast, we model the continuous action with a large multi-modal diffusion transformer, dubbed as Diffusion Transformer Policy, in which we directly denoise action chunks by a large transformer model rather than a small action head. By leveraging the scaling capability of transformers, the proposed approach can effectively model continuous end-effector actions across large diverse robot datasets, and achieve better generalization performance. Extensive experiments demonstrate Diffusion Transformer Policy pretrained on diverse robot data can generalize to different embodiments, including simulation environments like Maniskill2 and Calvin, as well as the real-world Franka arm. Specifically, without bells and whistles, the proposed approach achieves state-of-the-art performance with only a single third-view camera stream in the Calvin novel task setting (ABC->D), improving the average number of tasks completed in a row of 5 to 3.6, and the pretraining stage significantly facilitates the success sequence length on the Calvin by over 1.2. The code will be publicly available.

[Arxiv](https://arxiv.org/abs/2410.15959)