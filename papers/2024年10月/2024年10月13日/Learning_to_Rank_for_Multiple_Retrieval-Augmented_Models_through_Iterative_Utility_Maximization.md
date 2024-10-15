# 通过迭代效用最大化，学习对多个检索增强模型进行排序

发布时间：2024年10月13日

`RAG` `搜索引擎` `人工智能`

> Learning to Rank for Multiple Retrieval-Augmented Models through Iterative Utility Maximization

# 摘要

> 本文探讨了如何为多个具有不同任务、LLM 和检索策略的 RAG 代理设计统一搜索引擎。我们提出了一种迭代方法，通过离线阶段收集检索文档的反馈，并利用期望最大化算法优化搜索引擎，以最大化每个代理的效用。此外，我们还将其应用于在线环境，使搜索引擎能根据实时反馈进行调整，更好地服务每个代理。实验结果显示，我们的方法在 KILT 基准数据集上显著优于 18 个 RAG 模型的基线。我们还展示了该方法如何根据反馈为每个 RAG 代理个性化检索过程。最后，通过全面的消融研究，我们深入分析了该方法的各个方面。

> This paper investigates the design of a unified search engine to serve multiple retrieval-augmented generation (RAG) agents, each with a distinct task, backbone large language model (LLM), and retrieval-augmentation strategy. We introduce an iterative approach where the search engine generates retrieval results for these RAG agents and gathers feedback on the quality of the retrieved documents during an offline phase. This feedback is then used to iteratively optimize the search engine using a novel expectation-maximization algorithm, with the goal of maximizing each agent's utility function. Additionally, we adapt this approach to an online setting, allowing the search engine to refine its behavior based on real-time individual agents feedback to better serve the results for each of them. Experiments on diverse datasets from the Knowledge-Intensive Language Tasks (KILT) benchmark demonstrates that our approach significantly on average outperforms competitive baselines across 18 RAG models. We also demonstrate that our method effectively ``personalizes'' the retrieval process for each RAG agent based on the collected feedback. Finally, we provide a comprehensive ablation study to explore various aspects of our method.

[Arxiv](https://arxiv.org/abs/2410.09942)