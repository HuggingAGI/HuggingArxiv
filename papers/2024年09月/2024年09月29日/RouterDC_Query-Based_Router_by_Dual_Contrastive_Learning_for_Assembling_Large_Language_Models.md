# RouterDC：基于双重对比学习的查询路由器，用于组装大型语言模型

发布时间：2024年09月29日

`LLM应用` `人工智能`

> RouterDC: Query-Based Router by Dual Contrastive Learning for Assembling Large Language Models

# 摘要

> 最新研究发现，将多个现成的LLM组合起来，可以充分发挥它们的互补优势。为此，路由技术应运而生，它通过学习选择最适合每个查询的LLM。然而，现有路由模型在面对多个LLM表现优异的查询时显得力不从心。本文提出了一种名为RouterDC的新方法，通过双重对比学习来优化路由选择。RouterDC包含编码器和LLM嵌入，并采用两种对比学习损失进行训练。实验显示，RouterDC在组合LLM方面表现出色，无论是在分布内还是分布外任务上，均显著超越了单个顶级LLM和现有路由方法。源代码已公开，详见https://github.com/shuhao02/RouterDC。

> Recent works show that assembling multiple off-the-shelf large language models (LLMs) can harness their complementary abilities. To achieve this, routing is a promising method, which learns a router to select the most suitable LLM for each query. However, existing routing models are ineffective when multiple LLMs perform well for a query. To address this problem, in this paper, we propose a method called query-based Router by Dual Contrastive learning (RouterDC). The RouterDC model consists of an encoder and LLM embeddings, and we propose two contrastive learning losses to train the RouterDC model. Experimental results show that RouterDC is effective in assembling LLMs and largely outperforms individual top-performing LLMs as well as existing routing methods on both in-distribution (+2.76\%) and out-of-distribution (+1.90\%) tasks. Source code is available at https://github.com/shuhao02/RouterDC.

[Arxiv](https://arxiv.org/abs/2409.19886)