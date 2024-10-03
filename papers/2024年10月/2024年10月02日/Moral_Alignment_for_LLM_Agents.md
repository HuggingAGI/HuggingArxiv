# LLM 代理的道德对齐

发布时间：2024年10月02日

`Agent` `人工智能` `伦理学`

> Moral Alignment for LLM Agents

# 摘要

> 基于预训练大型语言模型 (LLM) 的决策代理正广泛应用于人类活动的各个领域。尽管目前这些应用较为专业化，但研究者们正致力于开发更通用的代理。随着这些基于 LLM 的系统变得更加主动，它们对人类活动的影响将日益显著，而透明度却可能下降。因此，将这些系统与人类价值观对齐显得尤为重要。当前的对齐方法多依赖于人类偏好数据，如在 RLHF 或 DPO 中，这些方法通过相对偏好来隐含地推断价值观。我们则提出了一种新方法，通过设计明确编码核心人类价值观的奖励函数，来进行基于强化学习的代理模型微调。具体而言，我们利用内在奖励来实现 LLM 代理的道德对齐。我们采用义务论伦理学和功利主义等传统哲学框架，量化代理在迭代囚徒困境 (IPD) 环境中的道德奖励。此外，我们还展示了如何通过道德微调使代理放弃利己策略。最终发现，IPD 游戏中学习的某些道德策略可推广至其他矩阵游戏环境。总之，我们的研究表明，利用内在奖励进行微调是将对齐 LLM 代理与人类价值观的有效通用解决方案，且可能比当前主流方法更具透明度和成本效益。

> Decision-making agents based on pre-trained Large Language Models (LLMs) are increasingly being deployed across various domains of human activity. While their applications are currently rather specialized, several research efforts are under way to develop more generalist agents. As LLM-based systems become more agentic, their influence on human activity will grow and the transparency of this will decrease. Consequently, developing effective methods for aligning them to human values is vital.
  The prevailing practice in alignment often relies on human preference data (e.g., in RLHF or DPO), in which values are implicit and are essentially deduced from relative preferences over different model outputs. In this work, instead of relying on human feedback, we introduce the design of reward functions that explicitly encode core human values for Reinforcement Learning-based fine-tuning of foundation agent models. Specifically, we use intrinsic rewards for the moral alignment of LLM agents.
  We evaluate our approach using the traditional philosophical frameworks of Deontological Ethics and Utilitarianism, quantifying moral rewards for agents in terms of actions and consequences on the Iterated Prisoner's Dilemma (IPD) environment. We also show how moral fine-tuning can be deployed to enable an agent to unlearn a previously developed selfish strategy. Finally, we find that certain moral strategies learned on the IPD game generalize to several other matrix game environments. In summary, we demonstrate that fine-tuning with intrinsic rewards is a promising general solution for aligning LLM agents to human values, and it might represent a more transparent and cost-effective alternative to currently predominant alignment techniques.

[Arxiv](https://arxiv.org/abs/2410.01639)