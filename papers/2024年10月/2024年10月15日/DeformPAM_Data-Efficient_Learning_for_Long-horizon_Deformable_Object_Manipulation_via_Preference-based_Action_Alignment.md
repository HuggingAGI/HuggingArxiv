# DeformPAM：利用基于偏好的动作对齐，高效学习长时变形物体的操作。

发布时间：2024年10月15日

`Agent` `机器人` `制造业`

> DeformPAM: Data-Efficient Learning for Long-horizon Deformable Object Manipulation via Preference-based Action Alignment

# 摘要

> 近年来，模仿学习在机器人操作领域有所突破，但在处理复杂的长时变形物体任务时仍显不足，如高维状态空间、复杂动力学和多模态动作分布。传统方法需大量数据且易出现分布偏移和累积误差。为此，我们提出DeformPAM框架，结合偏好学习和奖励引导，将长时任务分解为多个动作原语，利用3D点云和扩散模型建模动作分布，并训练隐式奖励模型。推理时，奖励模型筛选最佳动作，减少异常并提升任务质量。实验证明，即使在数据有限的情况下，DeformPAM也能显著提升任务完成质量和效率。代码和数据即将在https://deform-pam.robotflow.ai发布。

> In recent years, imitation learning has made progress in the field of robotic manipulation. However, it still faces challenges when dealing with complex long-horizon deformable object tasks, such as high-dimensional state spaces, complex dynamics, and multimodal action distributions. Traditional imitation learning methods often require a large amount of data and encounter distributional shifts and accumulative errors in these tasks. To address these issues, we propose a data-efficient general learning framework (DeformPAM) based on preference learning and reward-guided action selection. DeformPAM decomposes long-horizon tasks into multiple action primitives, utilizes 3D point cloud inputs and diffusion models to model action distributions, and trains an implicit reward model using human preference data. During the inference phase, the reward model scores multiple candidate actions, selecting the optimal action for execution, thereby reducing the occurrence of anomalous actions and improving task completion quality. Experiments conducted on three challenging real-world long-horizon deformable object manipulation tasks demonstrate the effectiveness of this method. Results show that DeformPAM improves both task completion quality and efficiency compared to baseline methods even with limited data. Code and data will be available at https://deform-pam.robotflow.ai.

[Arxiv](https://arxiv.org/abs/2410.11584)