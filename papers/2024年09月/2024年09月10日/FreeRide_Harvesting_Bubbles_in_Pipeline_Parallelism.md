# FreeRide：在流水线并行中巧妙利用气泡

发布时间：2024年09月10日

`LLM应用` `人工智能` `云计算`

> FreeRide: Harvesting Bubbles in Pipeline Parallelism

# 摘要

> 管道并行中的气泡现象是 LLM 训练时间延长和 GPU 资源利用不足的主要原因之一。利用这些气泡进行 GPU 侧任务虽能提高资源利用率并降低成本，但面临两大挑战：气泡的不连续性和形状多样性增加了编程难度，而侧任务与管道训练的资源竞争则带来了显著开销。为此，我们推出了 FreeRide 系统，旨在高效利用管道并行中的气泡。FreeRide 简化了侧任务的编程，智能管理气泡与侧任务，并通过优化 GPU 资源访问，大幅降低开销。实验表明，FreeRide 在不影响 LLM 训练的前提下，实现了 7.8% 的成本节省，同时支持模型训练、图形分析和图像处理等多项侧任务。

> The occurrence of bubbles in pipeline parallelism is an inherent limitation that can account for more than 40% of the large language model (LLM) training time and is one of the main reasons for the underutilization of GPU resources in LLM training. Harvesting these bubbles for GPU side tasks can increase resource utilization and reduce training costs but comes with challenges. First, because bubbles are discontinuous with various shapes, programming side tasks becomes difficult while requiring excessive engineering effort. Second, a side task can compete with pipeline training for GPU resources and incur significant overhead. To address these challenges, we propose FreeRide, a system designed to harvest bubbles in pipeline parallelism for side tasks. FreeRide provides programmers with interfaces to implement side tasks easily, manages bubbles and side tasks during pipeline training, and controls access to GPU resources by side tasks to reduce overhead. We demonstrate that FreeRide achieves 7.8% average cost savings with a negligible overhead of about 1% in training LLMs while serving model training, graph analytics, and image processing side tasks.

[Arxiv](https://arxiv.org/abs/2409.06941)