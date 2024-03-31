# 在直接偏好优化过程中，区分长度与质量的影响

发布时间：2024年03月28日

`LLM理论` `人工智能` `对话系统`

> Disentangling Length from Quality in Direct Preference Optimization

# 摘要

> 在大型语言模型的成功背后，人类反馈强化学习（RLHF）扮演了至关重要的角色。然而，RLHF倾向于放大人类偏好中的倾向，例如过度赘述。即便实用性和客观性不足，用户仍倾向于给予那些格式规范、措辞得体的答案更高的评价。尽管已有多种方法试图在传统RLHF中平衡这些偏见，但对于直接偏好优化（DPO）等直接对齐算法，这一问题仍待深入研究。与传统RLHF不同，DPO不依赖单独的奖励模型，也不直接应用强化学习，因此以往的控制策略在此并不适用。我们的研究首次聚焦于DPO中的长度问题，揭示了其对分布外自举的显著依赖。接着，我们提出了一种既系统又简洁的正则化策略，有效避免了长度上的不当利用，同时确保了模型性能的持续提升。在摘要和对话任务的多个数据集上，我们实现了最高达20%的胜率提升，即便面对GPT4裁判的明显啰嗦倾向。

> Reinforcement Learning from Human Feedback (RLHF) has been a crucial component in the recent success of Large Language Models. However, RLHF is know to exploit biases in human preferences, such as verbosity. A well-formatted and eloquent answer is often more highly rated by users, even when it is less helpful and objective. A number of approaches have been developed to control those biases in the classical RLHF literature, but the problem remains relatively under-explored for Direct Alignment Algorithms such as Direct Preference Optimization (DPO). Unlike classical RLHF, DPO does not train a separate reward model or use reinforcement learning directly, so previous approaches developed to control verbosity cannot be directly applied to this setting. Our work makes several contributions. For the first time, we study the length problem in the DPO setting, showing significant exploitation in DPO and linking it to out-of-distribution bootstrapping. We then develop a principled but simple regularization strategy that prevents length exploitation, while still maintaining improvements in model quality. We demonstrate these effects across datasets on summarization and dialogue, where we achieve up to 20\% improvement in win rates when controlling for length, despite the GPT4 judge's well-known verbosity bias.

![在直接偏好优化过程中，区分长度与质量的影响](../../../paper_images/2403.19159/lengths.png)

![在直接偏好优化过程中，区分长度与质量的影响](../../../paper_images/2403.19159/HH_b0.5_chosen_rejected_dpo.png)

![在直接偏好优化过程中，区分长度与质量的影响](../../../paper_images/2403.19159/TLDR_b0.5_chosen_rejected_dpo.png)

![在直接偏好优化过程中，区分长度与质量的影响](../../../paper_images/2403.19159/HH_b0.5_sft_dpo_rdpo.png)

![在直接偏好优化过程中，区分长度与质量的影响](../../../paper_images/2403.19159/TLDR_b0.5_sft_dpo_rdpo.png)

![在直接偏好优化过程中，区分长度与质量的影响](../../../paper_images/2403.19159/HH_b0.1_chosen_rejected_dpo.png)

![在直接偏好优化过程中，区分长度与质量的影响](../../../paper_images/2403.19159/TLDR_b0.1_chosen_rejected_dpo.png)

![在直接偏好优化过程中，区分长度与质量的影响](../../../paper_images/2403.19159/HH_b0.1_sft_dpo_rdpo.png)

![在直接偏好优化过程中，区分长度与质量的影响](../../../paper_images/2403.19159/TLDR_b0.1_sft_dpo_rdpo.png)

![在直接偏好优化过程中，区分长度与质量的影响](../../../paper_images/2403.19159/HH_b0.05_chosen_rejected_dpo.png)

![在直接偏好优化过程中，区分长度与质量的影响](../../../paper_images/2403.19159/TLDR_b0.05_chosen_rejected_dpo.png)

![在直接偏好优化过程中，区分长度与质量的影响](../../../paper_images/2403.19159/HH_b0.05_sft_dpo_rdpo.png)

![在直接偏好优化过程中，区分长度与质量的影响](../../../paper_images/2403.19159/TLDR_b0.05_sft_dpo_rdpo.png)

![在直接偏好优化过程中，区分长度与质量的影响](../../../paper_images/2403.19159/HH_sampled_len_vs_win.png)

![在直接偏好优化过程中，区分长度与质量的影响](../../../paper_images/2403.19159/TLDR_sampled_len_vs_win.png)

![在直接偏好优化过程中，区分长度与质量的影响](../../../paper_images/2403.19159/HH_reward_vs_win.png)

![在直接偏好优化过程中，区分长度与质量的影响](../../../paper_images/2403.19159/TLDR_reward_vs_win.png)

![在直接偏好优化过程中，区分长度与质量的影响](../../../paper_images/2403.19159/HH_sampled_len_evolution.png)

![在直接偏好优化过程中，区分长度与质量的影响](../../../paper_images/2403.19159/HH_win_evolution.png)

![在直接偏好优化过程中，区分长度与质量的影响](../../../paper_images/2403.19159/HH_reward_evolution.png)

![在直接偏好优化过程中，区分长度与质量的影响](../../../paper_images/2403.19159/HH_rewards_ood_b0.1_a0.0.png)

![在直接偏好优化过程中，区分长度与质量的影响](../../../paper_images/2403.19159/HH_rewards_ood_b0.1_a0.005.png)

![在直接偏好优化过程中，区分长度与质量的影响](../../../paper_images/2403.19159/HH_rewards_ood_b0.1_a0.01.png)

![在直接偏好优化过程中，区分长度与质量的影响](../../../paper_images/2403.19159/TLDR_rewards_ood_b0.1_a0.0.png)

![在直接偏好优化过程中，区分长度与质量的影响](../../../paper_images/2403.19159/TLDR_rewards_ood_b0.1_a0.02.png)

![在直接偏好优化过程中，区分长度与质量的影响](../../../paper_images/2403.19159/TLDR_rewards_ood_b0.1_a0.05.png)

[Arxiv](https://arxiv.org/abs/2403.19159)