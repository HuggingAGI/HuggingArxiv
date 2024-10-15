# LLM 中的路由与级联统一方法

发布时间：2024年10月14日

`LLM应用` `人工智能` `软件工程`

> A Unified Approach to Routing and Cascading for LLMs

# 摘要

> LLM 的广泛应用使得许多针对特定任务的微调模型变得可用。为了最大化整体性能，为每个用户查询选择最佳模型的策略至关重要。一个有效的策略不仅能显著提升性能，甚至可能超越单一的大型模型。现有方法主要分为两类：路由和级联。路由缺乏灵活性，而级联则可能效率低下。我们在这项研究中推导了这两种方法的最佳策略，并提出了一种结合两者优点的新方法——级联路由。实验结果显示，级联路由在各种场景中均表现优异，不仅提高了输出质量，还降低了计算成本，为模型选择问题提供了一个高效且统一的解决方案。

> The widespread applicability of large language models (LLMs) has increased the availability of many fine-tuned models of various sizes targeting specific tasks. Given a set of such specialized models, to maximize overall performance, it is important to figure out the optimal strategy for selecting the right model for a given user query. An effective strategy could drastically increase overall performance and even offer improvements over a single large monolithic model. Existing approaches typically fall into two categories: routing, where a single model is selected for each query, and cascading, which runs a sequence of increasingly larger models until a satisfactory answer is obtained. However, both have notable limitations: routing commits to an initial model without flexibility, while cascading requires executing every model in sequence, which can be inefficient. Additionally, the conditions under which these strategies are provably optimal remain unclear. In this work, we derive optimal strategies for both routing and cascading. Building on this analysis, we propose a novel approach called cascade routing, which combines the adaptability of routing with the cost-efficiency of cascading. Our experiments demonstrate that cascade routing consistently outperforms both routing and cascading across a variety of settings, improving both output quality and lowering computational cost, thus offering a unified and efficient solution to the model selection problem.

[Arxiv](https://arxiv.org/abs/2410.10347)