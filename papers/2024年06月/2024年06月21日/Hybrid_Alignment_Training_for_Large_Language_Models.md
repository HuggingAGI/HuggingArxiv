# 大型语言模型的混合对齐训练

发布时间：2024年06月21日

`LLM理论

这篇论文探讨了大型语言模型（LLMs）的对齐训练问题，并提出了一种新的方法——混合对齐训练（Hbat）。这种方法旨在解决遵循指令的对齐和符合人类偏好的对齐之间的潜在冲突，通过交替对齐和改进的弹性权重巩固技术，实现在不同目标间的灵活切换。这种研究属于LLM理论范畴，因为它关注的是模型训练的理论和方法，而不是具体的应用或Agent的行为。因此，将其归类为LLM理论是合适的。` `机器学习`

> Hybrid Alignment Training for Large Language Models

# 摘要

> 对齐训练是让大型语言模型（LLMs）更好地理解并满足人类意图和偏好的关键。这一过程通常分为两个阶段：遵循指令的对齐和符合人类偏好的对齐。但问题在于，这两个目标可能相互冲突，导致LLMs难以同时完美地满足两者。为此，我们提出了一种名为混合对齐训练（Hbat）的新方法，它通过交替对齐和改进的弹性权重巩固技术，实现了在不同目标间的灵活切换，从而促进了两个对齐任务间的协同。我们在总结和对话任务上测试了Hbat，结果显示它显著超越了所有基线方法。特别是在采用近端策略优化和直接偏好优化时，Hbat相较于传统的两阶段对齐训练，展现出了持续的性能提升。

> Alignment training is crucial for enabling large language models (LLMs) to cater to human intentions and preferences. It is typically performed based on two stages with different objectives: instruction-following alignment and human-preference alignment. However, aligning LLMs with these objectives in sequence suffers from an inherent problem: the objectives may conflict, and the LLMs cannot guarantee to simultaneously align with the instructions and human preferences well. To response to these, in this work, we propose a Hybrid Alignment Training (Hbat) approach, based on alternating alignment and modified elastic weight consolidation methods. The basic idea is to alternate between different objectives during alignment training, so that better collaboration can be achieved between the two alignment tasks.We experiment with Hbat on summarization and dialogue tasks. Experimental results show that the proposed \textsc{Hbat} can significantly outperform all baselines. Notably, Hbat yields consistent performance gains over the traditional two-stage alignment training when using both proximal policy optimization and direct preference optimization.

[Arxiv](https://arxiv.org/abs/2406.15178)