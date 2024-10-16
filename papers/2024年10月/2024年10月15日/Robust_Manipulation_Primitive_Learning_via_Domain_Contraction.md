# 通过领域收缩，实现操作原语的鲁棒学习

发布时间：2024年10月15日

`Agent` `机器人` `自动化`

> Robust Manipulation Primitive Learning via Domain Contraction

# 摘要

> 接触丰富的操作在人类生活中至关重要，但不确定的参数让机器人难以通过规划和控制达到同等水平。为此，领域适应和随机化被提出用于鲁棒策略学习，但它们要么失去跨实例的泛化能力，要么因忽略实例特定信息而表现保守。本文提出一种双层方法，结合参数增强的多模型策略学习和领域收缩的参数条件策略检索，既保持泛化能力又提供最优行为。我们在打击、推动和重定向三个操作任务上验证了该方法，实验结果显示其在处理多样物理参数实例时的鲁棒策略生成能力。

> Contact-rich manipulation plays an important role in human daily activities, but uncertain parameters pose significant challenges for robots to achieve comparable performance through planning and control. To address this issue, domain adaptation and domain randomization have been proposed for robust policy learning. However, they either lose the generalization ability across diverse instances or perform conservatively due to neglecting instance-specific information. In this paper, we propose a bi-level approach to learn robust manipulation primitives, including parameter-augmented policy learning using multiple models, and parameter-conditioned policy retrieval through domain contraction. This approach unifies domain randomization and domain adaptation, providing optimal behaviors while keeping generalization ability. We validate the proposed method on three contact-rich manipulation primitives: hitting, pushing, and reorientation. The experimental results showcase the superior performance of our approach in generating robust policies for instances with diverse physical parameters.

[Arxiv](https://arxiv.org/abs/2410.11600)