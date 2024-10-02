# 不确定性感知奖励模型：让奖励模型学会识别未知

发布时间：2024年10月01日

`LLM理论` `人工智能`

> Uncertainty-aware Reward Model: Teaching Reward Models to Know What is Unknown

# 摘要

> 奖励模型 (RM) 在将 LLM 的生成与人类期望对齐方面至关重要。然而，现有 RM 未能捕捉人类偏好中的随机性，也无法有效评估奖励预测的可靠性。为此，我们提出了不确定性感知的 RM (URM) 和 RM 集成 (URME)，以纳入和管理奖励建模中的不确定性。URM 能建模人类偏好中解耦属性的分布，而 URME 通过集成差异量化不确定性，识别奖励评估中的潜在知识缺乏。实验显示，URM 在相同规模模型中达到最先进性能，证明了在人类偏好中建模不确定性的有效性。此外，通过不确定性量化，URM 和 URME 能识别不可靠预测，提升奖励评估质量。

> Reward models (RM) play a critical role in aligning generations of large language models (LLM) to human expectations. However, prevailing RMs fail to capture the stochasticity within human preferences and cannot effectively evaluate the reliability of reward predictions. To address these issues, we propose Uncertain-aware RM (URM) and Uncertain-aware RM Ensemble (URME) to incorporate and manage uncertainty in reward modeling. URM can model the distribution of disentangled attributes within human preferences, while URME quantifies uncertainty through discrepancies in the ensemble, thereby identifying potential lack of knowledge during reward evaluation. Experiment results indicate that the proposed URM achieves state-of-the-art performance compared to models with the same size, demonstrating the effectiveness of modeling uncertainty within human preferences. Furthermore, empirical results show that through uncertainty quantification, URM and URME can identify unreliable predictions to improve the quality of reward evaluations.

[Arxiv](https://arxiv.org/abs/2410.00847)