# 融合动态方程：基于 LLM 代理的社会意见预测算法

发布时间：2024年09月13日

`LLM应用` `社交媒体` `社会运动`

> Fusing Dynamics Equation: A Social Opinions Prediction Algorithm with LLM-based Agents

# 摘要

> 随着社交媒体成为社会运动和舆论形成的重要平台，准确模拟和预测用户意见动态变得至关重要。然而，现有方法难以捕捉用户行为的复杂性。为此，本文提出了创新的FDE-LLM算法，结合意见动态和流行病模型，有效约束LLM的行为，使其更贴近现实。FDE-LLM将用户分为领袖和追随者，领袖基于LLM角色扮演并受CA模型约束，追随者则融入CA和SIR模型的动态系统。这一设计显著提升了模拟的准确性和效率。实验结果显示，FDE-LLM在准确性和可解释性上优于传统ABM和LLM算法。

> In the context where social media is increasingly becoming a significant platform for social movements and the formation of public opinion, accurately simulating and predicting the dynamics of user opinions is of great importance for understanding social phenomena, policy making, and guiding public opinion. However, existing simulation methods face challenges in capturing the complexity and dynamics of user behavior. Addressing this issue, this paper proposes an innovative simulation method for the dynamics of social media user opinions, the FDE-LLM algorithm, which incorporates opinion dynamics and epidemic model. This effectively constrains the actions and opinion evolution process of large language models (LLM), making them more aligned with the real cyber world. In particular, the FDE-LLM categorizes users into opinion leaders and followers. Opinion leaders are based on LLM role-playing and are constrained by the CA model, while opinion followers are integrated into a dynamic system that combines the CA model with the SIR model. This innovative design significantly improves the accuracy and efficiency of the simulation. Experiments were conducted on four real Weibo datasets and validated using the open-source model ChatGLM. The results show that, compared to traditional agent-based modeling (ABM) opinion dynamics algorithms and LLM-based opinion diffusion algorithms, our FDE-LLM algorithm demonstrates higher accuracy and interpretability.

[Arxiv](https://arxiv.org/abs/2409.08717)