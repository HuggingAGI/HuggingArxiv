# 多实例 GPU 上的工作负载优化分配

发布时间：2024年09月10日

`LLM应用` `人工智能`

> Optimal Workload Placement on Multi-Instance GPUs

# 摘要

> 当前，优化 GPU 使用已成为当务之急，毕竟 GPU 已成为 IT 领域最昂贵且抢手的资源之一。为此，新一代 GPU 引入了多实例 GPU (MIG) 功能，允许多个工作负载共享同一 GPU，尽管存在一定限制。本文探讨了如何优化基于大型语言模型 (LLM) 的 AI 推理工作负载在 GPU 上的部署。我们首先分析了实际应用中常见的几种场景，这些场景要求高效地放置或迁移工作负载，以便为新任务腾出空间。我们的核心目标是用最少的 GPU 资源，最大限度地减少内存和计算浪费。为此，我们提出了两种解决方案：优化方法和启发式方法。通过与两种工作负载调度启发式方法的对比测试，我们发现，与基线方法相比，GPU 使用量最多可减少 2.85 倍，浪费率最多可降低 70%。我们期待 SRE 社区能在实际生产环境中应用我们的方法，进一步提升资源利用效率。

> There is an urgent and pressing need to optimize usage of Graphical Processing Units (GPUs), which have arguably become one of the most expensive and sought after IT resources. To help with this goal, several of the current generation of GPUs support a partitioning feature, called Multi-Instance GPU (MIG) to allow multiple workloads to share a GPU, albeit with some constraints. In this paper we investigate how to optimize the placement of Large Language Model (LLM)-based AI Inferencing workloads on GPUs. We first identify and present several use cases that are encountered in practice that require workloads to be efficiently placed or migrated to other GPUs to make room for incoming workloads. The overarching goal is to use as few GPUs as possible and to further minimize memory and compute wastage on GPUs that are utilized. We have developed two approaches to address this problem: an optimization method and a heuristic method. We benchmark these with two workload scheduling heuristics for multiple use cases. Our results show up to 2.85x improvement in the number of GPUs used and up to 70% reduction in GPU wastage over baseline heuristics. We plan to enable the SRE community to leverage our proposed method in production environments.

[Arxiv](https://arxiv.org/abs/2409.06646)