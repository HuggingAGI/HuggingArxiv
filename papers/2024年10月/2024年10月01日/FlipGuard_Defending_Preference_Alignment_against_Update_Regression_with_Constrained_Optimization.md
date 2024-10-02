# FlipGuard：利用约束优化技术，有效抵御偏好对齐中的更新回归问题。

发布时间：2024年10月01日

`LLM理论` `人工智能`

> FlipGuard: Defending Preference Alignment against Update Regression with Constrained Optimization

# 摘要

> 近期，偏好对齐技术的突破大幅提升了大型语言模型生成符合人类价值观文本的能力。然而，现有对齐指标多关注整体改进，却忽视了“回归”这一关键问题——即更新后对先前正确处理数据的倒退。这可能源于过度微调已对齐数据，导致过度对齐和性能退化。为此，我们推出 FlipGuard，一种约束优化方法，旨在检测并缓解更新中的回归问题。FlipGuard 通过定制奖励特征识别性能下降，并在训练中施加策略性约束，确保更新与预对齐模型保持一致。实验证明，FlipGuard 不仅有效减少更新回归，还展现出卓越的整体性能，并在偏好对齐过程中保留了知识。

> Recent breakthroughs in preference alignment have significantly improved Large Language Models' ability to generate texts that align with human preferences and values. However, current alignment metrics typically emphasize the post-hoc overall improvement, while overlooking a critical aspect: regression, which refers to the backsliding on previously correctly-handled data after updates. This potential pitfall may arise from excessive fine-tuning on already well-aligned data, which subsequently leads to over-alignment and degeneration. To address this challenge, we propose FlipGuard, a constrained optimization approach to detect and mitigate update regression with focal attention. Specifically, FlipGuard identifies performance degradation using a customized reward characterization and strategically enforces a constraint to encourage conditional congruence with the pre-aligned model during training. Comprehensive experiments demonstrate that FlipGuard effectively alleviates update regression while demonstrating excellent overall performance, with the added benefit of knowledge preservation while aligning preferences.

[Arxiv](https://arxiv.org/abs/2410.00508)