# FlashFlex：在异构环境中优化大型语言模型训练

发布时间：2024年09月02日

`LLM理论` `数据中心` `高性能计算`

> FlashFlex: Accommodating Large Language Model Training over Heterogeneous Environment

# 摘要

> 训练大型语言模型（LLM）是一项计算密集型任务，通常在配备同质高性能 GPU 的数据中心进行。本文探索了一种新方法，通过在异构 GPU 上部署训练计算，以提高灵活性和资源利用效率。为此，我们设计了 FlashFlex 系统，该系统支持数据、管道和张量模型并行训练计算的不对称分区，并将其分配问题形式化为受约束的优化问题，提出基于分层图分区算法的解决方案。我们的方法能自适应地在 GPU 间分配训练计算，充分利用计算能力。实证研究表明，FlashFlex 在异构 GPU 上训练不同规模的 LLM 时，与在同质高性能 GPU 上运行的最先进系统相比，能实现相当的训练 MFU，最小 MFU 差距分别为 11.61% 和 0.30%，取决于是否配备 RDMA。代码已开源至 https://github.com/Relaxed-System-Lab/FlashFlex。

> Training large language model (LLM) is a computationally intensive task, which is typically conducted in data centers with homogeneous high-performance GPUs. This paper explores an alternative approach by deploying the training computation across heterogeneous GPUs to enable better flexibility and efficiency for heterogeneous resource utilization. To achieve this goal, we propose a novel system, FlashFlex, that can flexibly support an asymmetric partition of the parallel training computations across the scope of data-, pipeline-, and tensor model parallelism. We further formalize the allocation of asymmetric partitioned training computations over a set of heterogeneous GPUs as a constrained optimization problem and propose an efficient solution based on a hierarchical graph partitioning algorithm. Our approach can adaptively allocate asymmetric training computations across GPUs, fully leveraging the available computational power. We conduct extensive empirical studies to evaluate the performance of FlashFlex, where we find that when training LLMs at different scales (from 7B to 30B), FlashFlex can achieve comparable training MFU when running over a set of heterogeneous GPUs compared with the state of the art training systems running over a set of homogeneous high-performance GPUs with the same amount of total peak FLOPS. The achieved smallest gaps in MFU are 11.61% and 0.30%, depending on whether the homogeneous setting is equipped with and without RDMA. Our implementation is available at https://github.com/Relaxed-System-Lab/FlashFlex.

[Arxiv](https://arxiv.org/abs/2409.01143)