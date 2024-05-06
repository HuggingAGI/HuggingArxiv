# 为基于大型语言模型的对话式推荐系统融入外部知识并引入目标导向。

发布时间：2024年05月03日

`分类：LLM应用` `对话系统` `推荐系统`

> Incorporating External Knowledge and Goal Guidance for LLM-based Conversational Recommender Systems

# 摘要

> 本研究致力于提升大型语言模型（LLMs）在对话式推荐系统（CRS）任务中运用外部知识和目标导向的能力。例如ChatGPT这样的高级LLMs在特定CRS任务上存在局限，这主要体现在两个方面：一是生成基于推荐知识的切实回应；二是通过多样的对话目标引领对话。我们首先通过全面的评估揭示了这些限制，并强调了引入外部知识和目标导向对于提升推荐精准度和语言品质的重要性。基于这些发现，我们设计了创新的ChatCRS框架，该框架通过两个关键组件将复杂的CRS任务细化为多个子任务：一是利用工具辅助方法检索外部知识库的知识检索代理；二是用于对话目标预测的目标规划代理。在两个多目标CRS数据集上的实验结果显示，ChatCRS在设定新的行业标杆的同时，将信息性语言质量提升了17%，主动性提高了27%，并实现了推荐准确度的十倍增长。

> This paper aims to efficiently enable large language models (LLMs) to use external knowledge and goal guidance in conversational recommender system (CRS) tasks. Advanced LLMs (e.g., ChatGPT) are limited in domain-specific CRS tasks for 1) generating grounded responses with recommendation-oriented knowledge, or 2) proactively leading the conversations through different dialogue goals. In this work, we first analyze those limitations through a comprehensive evaluation, showing the necessity of external knowledge and goal guidance which contribute significantly to the recommendation accuracy and language quality. In light of this finding, we propose a novel ChatCRS framework to decompose the complex CRS task into several sub-tasks through the implementation of 1) a knowledge retrieval agent using a tool-augmented approach to reason over external Knowledge Bases and 2) a goal-planning agent for dialogue goal prediction. Experimental results on two multi-goal CRS datasets reveal that ChatCRS sets new state-of-the-art benchmarks, improving language quality of informativeness by 17% and proactivity by 27%, and achieving a tenfold enhancement in recommendation accuracy.

[Arxiv](https://arxiv.org/abs/2405.01868)