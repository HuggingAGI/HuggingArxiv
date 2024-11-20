# 用于查询生成的令牌级近端策略优化

发布时间：2024年11月01日

`LLM应用` `搜索引擎` `推荐系统`

> Token-level Proximal Policy Optimization for Query Generation

# 摘要

> 查询生成对于网络搜索引擎（如谷歌、必应）和推荐系统是关键任务。近来，前沿的查询生成方法借助大型语言模型（LLMs），因其在上下文理解和文本生成方面能力强大。但它们依据用户网络搜索交互历史推断用户意图以生成高质量查询时仍面临挑战。本文中，我们提出了令牌级近端策略优化（TPPO），这一创新方法旨在通过微调让LLMs在查询生成上表现更佳。TPPO基于AI反馈的强化学习（RLAIF）范式，包含令牌级奖励模型和令牌级近端策略优化模块，以应对传统RLAIF框架中的稀疏奖励难题。为评估TPPO的有效性和稳健性，我们在开源数据集和从全球使用的搜索引擎采集的工业数据集上开展了实验。实验结果显示，TPPO显著提升了LLMs的查询生成性能，且优于现有的竞品。

> Query generation is a critical task for web search engines (e.g. Google, Bing) and recommendation systems. Recently, state-of-the-art query generation methods leverage Large Language Models (LLMs) for their strong capabilities in context understanding and text generation. However, they still face challenges in generating high-quality queries in terms of inferring user intent based on their web search interaction history. In this paper, we propose Token-level Proximal Policy Optimization (TPPO), a noval approach designed to empower LLMs perform better in query generation through fine-tuning. TPPO is based on the Reinforcement Learning from AI Feedback (RLAIF) paradigm, consisting of a token-level reward model and a token-level proximal policy optimization module to address the sparse reward challenge in traditional RLAIF frameworks. To evaluate the effectiveness and robustness of TPPO, we conducted experiments on both open-source dataset and an industrial dataset that was collected from a globally-used search engine. The experimental results demonstrate that TPPO significantly improves the performance of query generation for LLMs and outperforms its existing competitors.

[Arxiv](https://arxiv.org/abs/2411.00722)