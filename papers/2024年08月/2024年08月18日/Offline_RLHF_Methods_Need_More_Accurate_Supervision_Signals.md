# 离线强化学习人类反馈（RLHF）方法亟需更精准的监督信号指引。

发布时间：2024年08月18日

`LLM理论` `人工智能` `机器学习`

> Offline RLHF Methods Need More Accurate Supervision Signals

# 摘要

> 随着大型语言模型的飞速进步，如何使其与人类偏好相匹配变得至关重要。尽管基于人类反馈的强化学习（RLHF）效果显著，但其复杂性和资源需求高。为此，离线 RLHF 应运而生，它通过固定偏好数据集上的排序损失直接优化 LLM。然而，现有方法仅关注响应间的相对顺序，忽略了偏好的具体程度。针对这一缺陷，我们提出了奖励差异优化（RDO），通过引入奖励差异系数重新评估样本对，并构建了一个包含响应间深度交互的差异模型来预测这些系数。实验结果显示，RDO 在自动评估和人类评审中均表现出色，有力证明了其对齐 LLM 与人类价值观的潜力。

> With the rapid advances in Large Language Models (LLMs), aligning LLMs with human preferences become increasingly important. Although Reinforcement Learning with Human Feedback (RLHF) proves effective, it is complicated and highly resource-intensive. As such, offline RLHF has been introduced as an alternative solution, which directly optimizes LLMs with ranking losses on a fixed preference dataset. Current offline RLHF only captures the ``ordinal relationship'' between responses, overlooking the crucial aspect of ``how much'' one is preferred over the others. To address this issue, we propose a simple yet effective solution called \textbf{R}eward \textbf{D}ifference \textbf{O}ptimization, shorted as \textbf{RDO}. Specifically, we introduce {\it reward difference coefficients} to reweigh sample pairs in offline RLHF. We then develop a {\it difference model} involving rich interactions between a pair of responses for predicting these difference coefficients. Experiments with 7B LLMs on the HH and TL;DR datasets substantiate the effectiveness of our method in both automatic metrics and human evaluation, thereby highlighting its potential for aligning LLMs with human intent and values.

[Arxiv](https://arxiv.org/abs/2408.09385)