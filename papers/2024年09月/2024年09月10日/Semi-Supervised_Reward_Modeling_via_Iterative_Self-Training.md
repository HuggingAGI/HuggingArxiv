# 半监督奖励建模：迭代自训练的艺术

发布时间：2024年09月10日

`LLM应用` `人工智能` `机器学习`

> Semi-Supervised Reward Modeling via Iterative Self-Training

# 摘要

> 奖励模型 (RM) 在 RLHF 中至关重要，用于捕捉人类价值观并调整 LLM。传统上，RM 训练依赖大量人工标注数据，面临可扩展性和成本挑战。为此，我们提出半监督奖励建模 (SSRM)，利用未标注数据提升 RM 训练。SSRM 通过伪标注、置信度筛选和监督微调三个步骤，显著改进 RM 性能，且无需额外标注成本。实验表明，SSRM 性能可媲美全标注数据训练的模型。SSRM 大幅减少对人工标注数据的依赖，降低训练成本和时间。

> Reward models (RM) capture the values and preferences of humans and play a central role in Reinforcement Learning with Human Feedback (RLHF) to align pretrained large language models (LLMs). Traditionally, training these models relies on extensive human-annotated preference data, which poses significant challenges in terms of scalability and cost. To overcome these limitations, we propose Semi-Supervised Reward Modeling (SSRM), an approach that enhances RM training using unlabeled data. Given an unlabeled dataset, SSRM involves three key iterative steps: pseudo-labeling unlabeled examples, selecting high-confidence examples through a confidence threshold, and supervised finetuning on the refined dataset. Across extensive experiments on various model configurations, we demonstrate that SSRM significantly improves reward models without incurring additional labeling costs. Notably, SSRM can achieve performance comparable to models trained entirely on labeled data of equivalent volumes. Overall, SSRM substantially reduces the dependency on large volumes of human-annotated data, thereby decreasing the overall cost and time involved in training effective reward models.

[Arxiv](https://arxiv.org/abs/2409.06903)