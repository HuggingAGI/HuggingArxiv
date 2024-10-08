# EnsemW2S：集合多个 LLM，能否打造出更强大的模型？

发布时间：2024年10月06日

`LLM理论` `人工智能` `机器学习`

> EnsemW2S: Can an Ensemble of LLMs be Leveraged to Obtain a Stronger LLM?

# 摘要

> 我们如何整合多个大型语言模型 (LLM) 的力量，打造一个更强大的模型？这一问题是我们研究的基石。我们提出了一种创新的弱到强 (w2s) 泛化方法，这是 AI 对齐中的关键难题。我们设计了一个由易到难 (e2h) 的框架，探讨 w2s 泛化的可行性。在这个框架中，简单任务上训练的弱模型共同指导复杂任务上的强模型，这与现实世界中人类监督有限的挑战相呼应。为此，我们借鉴 AdaBoost 理念，开发了一种新型集成方法，证明弱监督者的集合能显著提升强 LLM 在复杂 QA 数据集上的分类和生成任务表现。在多个实例中，我们的集成方法与基于真实数据训练的模型表现相当，为 w2s 泛化设立了新标杆。我们观察到最高达 14% 的性能提升，二分类和生成任务的平均改进分别为 5% 和 4%。这项研究揭示了通过集体监督提升 AI 的潜力，特别是在标记数据稀缺或不足的场景中。

> How can we harness the collective capabilities of multiple Large Language Models (LLMs) to create an even more powerful model? This question forms the foundation of our research, where we propose an innovative approach to weak-to-strong (w2s) generalization-a critical problem in AI alignment. Our work introduces an easy-to-hard (e2h) framework for studying the feasibility of w2s generalization, where weak models trained on simpler tasks collaboratively supervise stronger models on more complex tasks. This setup mirrors real-world challenges, where direct human supervision is limited. To achieve this, we develop a novel AdaBoost-inspired ensemble method, demonstrating that an ensemble of weak supervisors can enhance the performance of stronger LLMs across classification and generative tasks on difficult QA datasets. In several cases, our ensemble approach matches the performance of models trained on ground-truth data, establishing a new benchmark for w2s generalization. We observe an improvement of up to 14% over existing baselines and average improvements of 5% and 4% for binary classification and generative tasks, respectively. This research points to a promising direction for enhancing AI through collective supervision, especially in scenarios where labeled data is sparse or insufficient.

[Arxiv](https://arxiv.org/abs/2410.04571)