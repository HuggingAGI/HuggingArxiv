# 熵可控直接偏好优化

发布时间：2024年11月12日

`LLM应用` `语言模型`

> Entropy Controllable Direct Preference Optimization

# 摘要

> 在大型语言模型（LLM）的后训练中，基于人类反馈的强化学习（RLHF）是实现与人类偏好一致的生成的有效方法。直接偏好优化（DPO）允许使用简单的二元交叉熵损失进行策略训练，而无需奖励模型。DPO 的目标通过反向 KL 散度进行正则化，鼓励寻求模式拟合参考策略。然而，我们指出，最小化反向 KL 散度可能无法捕获参考分布的模式，这可能会损害策略的性能。基于此观察，我们提出了对 DPO 的简单修改，即 H-DPO，它允许控制所得策略的熵，增强分布的锐度，从而更有效地实现模式寻求拟合。在我们的实验中，我们表明 H-DPO 在各种任务中都优于 DPO，在数学任务的 pass@$k$ 评估中展示出卓越的结果。此外，H-DPO 易于实现，只需要对 DPO 的损失计算进行少量修改，这使其在 LLM 训练的广泛应用中具有高度的实用性和前景。

> In the post-training of large language models (LLMs), Reinforcement Learning from Human Feedback (RLHF) is an effective approach to achieve generation aligned with human preferences. Direct Preference Optimization (DPO) allows for policy training with a simple binary cross-entropy loss without a reward model. The objective of DPO is regularized by reverse KL divergence that encourages mode-seeking fitting to the reference policy. Nonetheless, we indicate that minimizing reverse KL divergence could fail to capture a mode of the reference distribution, which may hurt the policy's performance. Based on this observation, we propose a simple modification to DPO, H-DPO, which allows for control over the entropy of the resulting policy, enhancing the distribution's sharpness and thereby enabling mode-seeking fitting more effectively. In our experiments, we show that H-DPO outperformed DPO across various tasks, demonstrating superior results in pass@$k$ evaluations for mathematical tasks. Moreover, H-DPO is simple to implement, requiring only minor modifications to the loss calculation of DPO, which makes it highly practical and promising for wide-ranging applications in the training of LLMs.

[Arxiv](https://arxiv.org/abs/2411.07595)