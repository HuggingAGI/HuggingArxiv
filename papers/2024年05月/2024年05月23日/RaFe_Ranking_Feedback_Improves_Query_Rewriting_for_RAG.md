# RaFe：通过排名反馈优化RAG的查询重写策略

发布时间：2024年05月23日

`RAG

理由：这篇论文主要关注的是RAG（Retrieval-Augmented Generation）技术中的查询重写问题，并提出了一种新的训练框架。虽然涉及到了LLMs，但重点在于RAG系统中的查询重写优化，而不是LLMs的理论研究或应用。因此，将其归类为RAG更为合适。` `问答系统`

> RaFe: Ranking Feedback Improves Query Rewriting for RAG

# 摘要

> 随着LLMs和RAG技术的进步，查询重写已成为开放领域问答等下游任务中RAG系统的标配。尽管许多研究尝试用小型模型结合强化学习来替代昂贵的LLMs进行查询重写，但现有方法依赖于标注或预设奖励，缺乏泛化且未能针对查询重写优化。本文提出了一种无需标注的查询重写模型训练框架，通过公开重排器提供精准反馈，实验证明其性能超越了现有基线。

> As Large Language Models (LLMs) and Retrieval Augmentation Generation (RAG) techniques have evolved, query rewriting has been widely incorporated into the RAG system for downstream tasks like open-domain QA. Many works have attempted to utilize small models with reinforcement learning rather than costly LLMs to improve query rewriting. However, current methods require annotations (e.g., labeled relevant documents or downstream answers) or predesigned rewards for feedback, which lack generalization, and fail to utilize signals tailored for query rewriting. In this paper, we propose ours, a framework for training query rewriting models free of annotations. By leveraging a publicly available reranker, ours~provides feedback aligned well with the rewriting objectives. Experimental results demonstrate that ours~can obtain better performance than baselines.

[Arxiv](https://arxiv.org/abs/2405.14431)