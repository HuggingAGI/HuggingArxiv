# 语言模型的奖励建模与弱监督

发布时间：2024年10月28日

`LLM应用` `语言模型`

> Reward Modeling with Weak Supervision for Language Models

# 摘要

> 近期，大型语言模型（LLMs）的发展促使其在各类任务中的应用增多，从人类反馈中进行强化学习（RLHF）成为其训练的关键一环，以让响应契合用户的意图。在 RLHF 流程中，依据人类标注员或 AI 系统确定的响应偏好来训练奖励模型，接着通过强化学习来改进 LLM。此项工作将弱监督引入，作为拓展 RLHF 数据集和提升奖励模型性能的策略。弱监督运用有噪声或不精准的数据标注，降低对高价手动标注数据的依赖。通过对 RLHF 数据集加以分析，找出与响应偏好相关的启发式方法，我们编写了简单的标注函数，随后校准了一个标注模型，对未标注数据进行弱标注。我们的评估显示，弱监督虽能显著提升较小数据集的奖励模型性能，但随着原本标注的大型数据集增多，其效果会减弱。另外，利用 LLM 生成并弱标注响应，为扩展偏好数据提供了颇具前景的方法。

> Recent advancements in large language models (LLMs) have led to their increased application across various tasks, with reinforcement learning from human feedback (RLHF) being a crucial part of their training to align responses with user intentions. In the RLHF process, a reward model is trained using responses preferences determined by human labelers or AI systems, which then refines the LLM through reinforcement learning. This work introduces weak supervision as a strategy to extend RLHF datasets and enhance reward model performance. Weak supervision employs noisy or imprecise data labeling, reducing reliance on expensive manually labeled data. By analyzing RLHF datasets to identify heuristics that correlate with response preference, we wrote simple labeling functions and then calibrated a label model to weakly annotate unlabeled data. Our evaluation show that while weak supervision significantly benefits smaller datasets by improving reward model performance, its effectiveness decreases with larger, originally labeled datasets. Additionally, using an LLM to generate and then weakly label responses offers a promising method for extending preference data.

[Arxiv](https://arxiv.org/abs/2410.20869)