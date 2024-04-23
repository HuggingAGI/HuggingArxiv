# 在对大型语言模型进行偏好微调时，应充分考虑并利用那些并非最优但符合当前策略的数据。

发布时间：2024年04月22日

`分类：LLM应用` `人工智能`

> Preference Fine-Tuning of LLMs Should Leverage Suboptimal, On-Policy Data

# 摘要

> 偏好标签的学习对于精细调整大型语言模型至关重要。在偏好微调的多种策略中，包括监督学习、策略性强化学习（RL）和对比学习，各有其实现上的权衡与性能差异。现有研究结果对此看法不一：一些研究表明在线RL对于获得优秀的微调效果至关重要，而其他研究则认为离线对比学习或纯粹的监督学习已足够。这引出了一个关键问题：偏好数据微调中哪些方法更为关键，原因何在？本文通过深入分析教学型和全面型大型语言模型（LLM）问题上的多种微调技术来回答这一问题。我们的主要发现是，总体而言，采用策略性抽样或通过“负梯度”降低特定响应可能性的方法，通常优于离线和最大似然目标方法。我们将这些使用策略性抽样或负梯度的方法归纳为一种针对分类分布的模态寻求目标的概念。模态寻求目标能够迅速改变分类分布特定区间的概率质量，从而更有效地在区间之间重新分配质量。我们的分析为LLM的偏好微调提供了实用的见解，并指导了如何收集数据以实现最佳提升。

> Learning from preference labels plays a crucial role in fine-tuning large language models. There are several distinct approaches for preference fine-tuning, including supervised learning, on-policy reinforcement learning (RL), and contrastive learning. Different methods come with different implementation tradeoffs and performance differences, and existing empirical findings present different conclusions, for instance, some results show that online RL is quite important to attain good fine-tuning results, while others find (offline) contrastive or even purely supervised methods sufficient. This raises a natural question: what kind of approaches are important for fine-tuning with preference data and why? In this paper, we answer this question by performing a rigorous analysis of a number of fine-tuning techniques on didactic and full-scale LLM problems. Our main finding is that, in general, approaches that use on-policy sampling or attempt to push down the likelihood on certain responses (i.e., employ a "negative gradient") outperform offline and maximum likelihood objectives. We conceptualize our insights and unify methods that use on-policy sampling or negative gradient under a notion of mode-seeking objectives for categorical distributions. Mode-seeking objectives are able to alter probability mass on specific bins of a categorical distribution at a fast rate compared to maximum likelihood, allowing them to relocate masses across bins more effectively. Our analysis prescribes actionable insights for preference fine-tuning of LLMs and informs how data should be collected for maximal improvement.

![在对大型语言模型进行偏好微调时，应充分考虑并利用那些并非最优但符合当前策略的数据。](../../../paper_images/2404.14367/x1.png)

![在对大型语言模型进行偏好微调时，应充分考虑并利用那些并非最优但符合当前策略的数据。](../../../paper_images/2404.14367/bandit_data_distribution.png)

![在对大型语言模型进行偏好微调时，应充分考虑并利用那些并非最优但符合当前策略的数据。](../../../paper_images/2404.14367/x2.png)

![在对大型语言模型进行偏好微调时，应充分考虑并利用那些并非最优但符合当前策略的数据。](../../../paper_images/2404.14367/batch_size_experiments_bofn.png)

![在对大型语言模型进行偏好微调时，应充分考虑并利用那些并非最优但符合当前策略的数据。](../../../paper_images/2404.14367/ppo_min_length_batch_size_ablation.png)

![在对大型语言模型进行偏好微调时，应充分考虑并利用那些并非最优但符合当前策略的数据。](../../../paper_images/2404.14367/ppo_mode_length_batch_size_ablation.png)

![在对大型语言模型进行偏好微调时，应充分考虑并利用那些并非最优但符合当前策略的数据。](../../../paper_images/2404.14367/ppo_skew_length_batch_size_ablation.png)

![在对大型语言模型进行偏好微调时，应充分考虑并利用那些并非最优但符合当前策略的数据。](../../../paper_images/2404.14367/batch_size_llm_length_summary_line_plot.png)

![在对大型语言模型进行偏好微调时，应充分考虑并利用那些并非最优但符合当前策略的数据。](../../../paper_images/2404.14367/alpacafarm_batch_size_rwr_reinforce.png)

![在对大型语言模型进行偏好微调时，应充分考虑并利用那些并非最优但符合当前策略的数据。](../../../paper_images/2404.14367/inner_iteration_steps.png)

![在对大型语言模型进行偏好微调时，应充分考虑并利用那些并非最优但符合当前策略的数据。](../../../paper_images/2404.14367/t_ablation_main_paper.png)

![在对大型语言模型进行偏好微调时，应充分考虑并利用那些并非最优但符合当前策略的数据。](../../../paper_images/2404.14367/negative_gradient_experiments.png)

![在对大型语言模型进行偏好微调时，应充分考虑并利用那些并非最优但符合当前策略的数据。](../../../paper_images/2404.14367/negative_gradients.png)

![在对大型语言模型进行偏好微调时，应充分考虑并利用那些并非最优但符合当前策略的数据。](../../../paper_images/2404.14367/negative_gradient_full_scale_finetuning_bar_plot.png)

![在对大型语言模型进行偏好微调时，应充分考虑并利用那些并非最优但符合当前策略的数据。](../../../paper_images/2404.14367/log_prob_difference.png)

![在对大型语言模型进行偏好微调时，应充分考虑并利用那些并非最优但符合当前策略的数据。](../../../paper_images/2404.14367/responses_bandit.png)

![在对大型语言模型进行偏好微调时，应充分考虑并利用那些并非最优但符合当前策略的数据。](../../../paper_images/2404.14367/ultra_fb_alpaca_reward_during_training.png)

![在对大型语言模型进行偏好微调时，应充分考虑并利用那些并非最优但符合当前策略的数据。](../../../paper_images/2404.14367/compliment.png)

![在对大型语言模型进行偏好微调时，应充分考虑并利用那些并非最优但符合当前策略的数据。](../../../paper_images/2404.14367/complimentarity.png)

![在对大型语言模型进行偏好微调时，应充分考虑并利用那些并非最优但符合当前策略的数据。](../../../paper_images/2404.14367/mode_length_results.png)

![在对大型语言模型进行偏好微调时，应充分考虑并利用那些并非最优但符合当前策略的数据。](../../../paper_images/2404.14367/rwr_min_length_batch_size_ablation.png)

![在对大型语言模型进行偏好微调时，应充分考虑并利用那些并非最优但符合当前策略的数据。](../../../paper_images/2404.14367/rwr_skew_length_batch_size_ablation.png)

![在对大型语言模型进行偏好微调时，应充分考虑并利用那些并非最优但符合当前策略的数据。](../../../paper_images/2404.14367/t_ablation_appendix.png)

[Arxiv](https://arxiv.org/abs/2404.14367)