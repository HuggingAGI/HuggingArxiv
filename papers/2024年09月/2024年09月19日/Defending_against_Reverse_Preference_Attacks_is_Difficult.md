# 抵御反向偏好攻击，实属不易。

发布时间：2024年09月19日

`LLM理论` `网络安全` `人工智能`

> Defending against Reverse Preference Attacks is Difficult

# 摘要

> 尽管在将大型语言模型 (LLM) 与人类价值观对齐并确保推理时的安全行为方面取得了进展，但已知安全对齐的 LLM 容易受到训练时攻击，例如在有害数据集上进行监督微调 (SFT)。在本文中，我们探讨了 LLM 是否容易受到对抗性强化学习的攻击。为此，我们提出了反向偏好攻击 (RPA)，这是一种通过在从人类反馈 (RLHF) 进行强化学习期间使用对抗性奖励来使 LLM 学习有害行为的攻击方法。RPA 暴露了 RL 设置中安全对齐 LLM 的关键安全漏洞：它们很容易探索有害的文本生成策略以优化对抗性奖励。为了防止 RPA，我们探索了一系列缓解策略，并利用约束马尔可夫决策过程，将多种防御有害微调攻击的机制适应到 RL 设置中。我们的实验表明，基于最小化拒绝的负对数似然概念的“在线”防御——防御者控制损失函数——可以有效保护 LLM 免受 RPA 的侵害。然而，试图使用“离线”防御来保护模型权重，这些防御在假设防御者无法控制损失函数的情况下运行，在面对 RPA 时效果较差。这些发现表明，使用 RL 进行的攻击可以成功地撤销开放权重 LLM 中的安全对齐，并将其用于恶意目的。

> While there has been progress towards aligning Large Language Models (LLMs) with human values and ensuring safe behaviour at inference time, safety-aligned LLMs are known to be vulnerable to training-time attacks such as supervised fine-tuning (SFT) on harmful datasets. In this paper, we ask if LLMs are vulnerable to adversarial reinforcement learning. Motivated by this goal, we propose Reverse Preference Attacks (RPA), a class of attacks to make LLMs learn harmful behavior using adversarial reward during reinforcement learning from human feedback (RLHF). RPAs expose a critical safety gap of safety-aligned LLMs in RL settings: they easily explore the harmful text generation policies to optimize adversarial reward. To protect against RPAs, we explore a host of mitigation strategies. Leveraging Constrained Markov-Decision Processes, we adapt a number of mechanisms to defend against harmful fine-tuning attacks into the RL setting. Our experiments show that ``online" defenses that are based on the idea of minimizing the negative log likelihood of refusals -- with the defender having control of the loss function -- can effectively protect LLMs against RPAs. However, trying to defend model weights using ``offline" defenses that operate under the assumption that the defender has no control over the loss function are less effective in the face of RPAs. These findings show that attacks done using RL can be used to successfully undo safety alignment in open-weight LLMs and use them for malicious purposes.

[Arxiv](https://arxiv.org/abs/2409.12914)