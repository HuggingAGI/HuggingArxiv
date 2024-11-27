# 不确定性受罚的直接偏好优化

发布时间：2024年10月26日

`LLM应用`

> Uncertainty-Penalized Direct Preference Optimization

# 摘要

> 让大型语言模型（LLMs）在内容、风格和呈现上契合人类偏好颇具挑战，这部分是因为偏好多样、依情境而定，有时还天生模糊。虽然基于人类反馈的强化学习（RLHF）和直接偏好优化（DPO）取得了成功，但它们容易出现代理奖励过度优化的问题。对DPO损失的分析揭示，对于误标或模糊的偏好对，关键是要进行正则化，以避免奖励作弊。在本研究中，受离线强化学习的启发，我们通过引入偏好不确定性惩罚方案为DPO构建了一个悲观框架。这种惩罚可校正损失，削弱不确定样本的损失梯度。在Anthropic-HH数据集上用GPT2 Medium，并通过模型集成获取不确定性估计来评估这些方法，结果显示，与普通DPO相比，整体性能得到提升，对于来自高不确定性选择/拒绝响应的提示，完成效果更佳。

> Aligning Large Language Models (LLMs) to human preferences in content, style, and presentation is challenging, in part because preferences are varied, context-dependent, and sometimes inherently ambiguous. While successful, Reinforcement Learning from Human Feedback (RLHF) and Direct Preference Optimization (DPO) are prone to the issue of proxy reward overoptimization. Analysis of the DPO loss reveals a critical need for regularization for mislabeled or ambiguous preference pairs to avoid reward hacking. In this work, we develop a pessimistic framework for DPO by introducing preference uncertainty penalization schemes, inspired by offline reinforcement learning. The penalization serves as a correction to the loss which attenuates the loss gradient for uncertain samples. Evaluation of the methods is performed with GPT2 Medium on the Anthropic-HH dataset using a model ensemble to obtain uncertainty estimates, and shows improved overall performance compared to vanilla DPO, as well as better completions on prompts from high-uncertainty chosen/rejected responses.

[Arxiv](https://arxiv.org/abs/2410.20187)