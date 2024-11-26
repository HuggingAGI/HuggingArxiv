# 自我生成的批评能够推动语言模型的奖励建模

发布时间：2024年11月25日

`LLM应用` `语言模型`

> Self-Generated Critiques Boost Reward Modeling for Language Models

# 摘要

> 奖励建模对于让大型语言模型（LLMs）契合人类偏好极为关键，尤其在基于人类反馈的强化学习（RLHF）里。但当下的奖励模型主要产出标量分数，难以将自然语言格式的批评纳入其中。我们推测同时预测批评和标量奖励能够提升奖励建模的能力。受此启发，我们提出了 Critic-RM，这是一个无需额外监督、利用自生成的批评来优化奖励模型的框架。Critic-RM 采用了两阶段流程：生成并筛选出高质量的批评，接着对奖励预测和批评生成进行联合微调。在多个基准测试中的实验显示，与标准奖励模型和 LLM 评判相比，Critic-RM 能将奖励建模的准确率提高 3.7% - 7.3%，展现出强大的性能和数据效率。另外的研究进一步证实了生成的批评在纠正有缺陷的推理步骤方面的有效性，推理准确率提高了 2.5% - 3.2%。

> Reward modeling is crucial for aligning large language models (LLMs) with human preferences, especially in reinforcement learning from human feedback (RLHF). However, current reward models mainly produce scalar scores and struggle to incorporate critiques in a natural language format. We hypothesize that predicting both critiques and the scalar reward would improve reward modeling ability. Motivated by this, we propose Critic-RM, a framework that improves reward models using self-generated critiques without extra supervision. Critic-RM employs a two-stage process: generating and filtering high-quality critiques, followed by joint fine-tuning on reward prediction and critique generation. Experiments across benchmarks show that Critic-RM improves reward modeling accuracy by 3.7%-7.3% compared to standard reward models and LLM judges, demonstrating strong performance and data efficiency. Additional studies further validate the effectiveness of generated critiques in rectifying flawed reasoning steps with 2.5%-3.2% gains in improving reasoning accuracy.

[Arxiv](https://arxiv.org/abs/2411.16646)