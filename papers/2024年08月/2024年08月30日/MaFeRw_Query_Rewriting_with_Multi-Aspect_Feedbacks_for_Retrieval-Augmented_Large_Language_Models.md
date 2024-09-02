# MaFeRw：通过多方面反馈优化查询，提升检索增强型大型语言模型的性能

发布时间：2024年08月30日

`RAG` `人工智能`

> MaFeRw: Query Rewriting with Multi-Aspect Feedbacks for Retrieval-Augmented Large Language Models

# 摘要

> 在实际应用的RAG系统中，查询常包含口语省略和模糊引用，需重写以精准反映用户需求。传统重写方法因流程冗长，对生成任务的提升有限。虽有研究尝试通过强化学习改进重写，但稀疏奖励常导致训练不稳定。我们发现，用户需求亦体现在黄金文档和检索结果中，通过密集反馈可优化重写，提升响应质量。本文提出的MaFeRw方法，通过整合检索与生成反馈，显著提升RAG性能。我们首先用人工数据初始化T5模型，再设计三项强化学习指标：重写查询与黄金文档的相似度、排名指标及生成与真实答案的ROUGE值。借鉴RLAIF，我们训练三种奖励模型以加速训练。最终，结合这些模型的分数，运用PPO算法探索最优重写策略。实验显示，MaFeRw在生成质量和训练稳定性上均超越基线方法。

> In a real-world RAG system, the current query often involves spoken ellipses and ambiguous references from dialogue contexts, necessitating query rewriting to better describe user's information needs. However, traditional context-based rewriting has minimal enhancement on downstream generation tasks due to the lengthy process from query rewriting to response generation. Some researchers try to utilize reinforcement learning with generation feedback to assist the rewriter, but these sparse rewards provide little guidance in most cases, leading to unstable training and generation results. We find that user's needs are also reflected in the gold document, retrieved documents and ground truth. Therefore, by feeding back these multi-aspect dense rewards to query rewriting, more stable and satisfactory responses can be achieved. In this paper, we propose a novel query rewriting method MaFeRw, which improves RAG performance by integrating multi-aspect feedback from both the retrieval process and generated results. Specifically, we first use manual data to train a T5 model for the rewriter initialization. Next, we design three metrics as reinforcement learning feedback: the similarity between the rewritten query and the gold document, the ranking metrics, and ROUGE between the generation and the ground truth. Inspired by RLAIF, we train three kinds of reward models for the above metrics to achieve more efficient training. Finally, we combine the scores of these reward models as feedback, and use PPO algorithm to explore the optimal query rewriting strategy. Experimental results on two conversational RAG datasets demonstrate that MaFeRw achieves superior generation metrics and more stable training compared to baselines.

[Arxiv](https://arxiv.org/abs/2408.17072)