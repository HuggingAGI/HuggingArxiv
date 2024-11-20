# 主动开展基于偏好的学习以实现多维个性化

发布时间：2024年11月01日

`LLM应用` `语言生成` `个性化学习`

> Active Preference-based Learning for Multi-dimensional Personalization

# 摘要

> 大型语言模型（LLMs）在各类任务中展现出非凡的通用性，然而因个人偏好复杂多样，要让其与个人偏好契合仍困难重重。现有方法往往忽视偏好具有多目标、多元化且难以清晰表述的特点，导致难以完全契合。为此，我们提出一种主动偏好学习框架，借助二元反馈来估算用户在多个目标上的偏好。我们的方法运用贝叶斯推理高效更新偏好，并通过能最优选择查询的获取函数减少用户反馈。另外，我们引入一个参数来应对反馈噪声，增强鲁棒性。我们通过理论分析及语言生成任务上的实验对我们的方法予以验证，表明其在反馈效率和个性化模型响应方面的成效。

> Large language models (LLMs) have shown remarkable versatility across tasks, but aligning them with individual human preferences remains challenging due to the complexity and diversity of these preferences. Existing methods often overlook the fact that preferences are multi-objective, diverse, and hard to articulate, making full alignment difficult. In response, we propose an active preference learning framework that uses binary feedback to estimate user preferences across multiple objectives. Our approach leverages Bayesian inference to update preferences efficiently and reduces user feedback through an acquisition function that optimally selects queries. Additionally, we introduce a parameter to handle feedback noise and improve robustness. We validate our approach through theoretical analysis and experiments on language generation tasks, demonstrating its feedback efficiency and effectiveness in personalizing model responses.

[Arxiv](https://arxiv.org/abs/2411.00524)