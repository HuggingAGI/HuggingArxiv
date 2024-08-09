# 部分专家检查点技术，为稀疏混合专家模型训练提供高效容错机制。

发布时间：2024年08月08日

`LLM理论` `人工智能` `分布式计算`

> Partial Experts Checkpoint: Efficient Fault Tolerance for Sparse Mixture-of-Experts Model Training

# 摘要

> 随着大型语言模型的规模不断扩大，分布式深度学习系统对容错性的需求日益迫切，成为AI基础设施研究的核心议题。Checkpoint技术已成为主流容错策略，但稀疏的Mixture-of-Experts（MoE）模型的出现，因其模型尺寸大幅增加，给传统Checkpoint技术带来了新挑战。为此，我们创新性地提出了部分专家Checkpoint（PEC）机制及相应的PEC容错系统，通过策略性地对部分专家进行Checkpoint，大幅减小了MoE模型的Checkpoint大小，使其与密集模型相当。实证分析显示，PEC方法在不牺牲模型质量的前提下，使非冗余Checkpoint大小减少了54.2%。同时，PEC容错系统在每个数据并行分布式等级上实现了76.9%的Checkpoint工作量减少，显著缩短了Checkpoint时间，并实现了与训练过程的完全重叠。

> As large language models continue to scale up, the imperative for fault tolerance in distributed deep learning systems intensifies, becoming a focal area of AI infrastructure research. Checkpoint has emerged as the predominant fault tolerance strategy, with extensive studies dedicated to optimizing its efficiency. However, the advent of the sparse Mixture-of-Experts (MoE) model presents new challenges for traditional checkpoint techniques due to the substantial increase in model size, despite comparable computational demands to dense models. Breaking new ground in the realm of efficient fault tolerance for MoE model training, we introduce a novel Partial Experts Checkpoint (PEC) mechanism alongside a corresponding PEC fault-tolerant system. Our approach strategically checkpoints a selected subset of experts, thereby significantly reducing the checkpoint size for MoE models to a level comparable with that of dense models. The empirical analysis on our 8-expert GPT-MoE model demonstrates that the proposed PEC approach facilitates a substantial 54.2% decrease in the size of non-redundant checkpoint (no data-parallel duplication), without compromising the final model quality. Moreover, our PEC fault-tolerant system achieves a 76.9% reduction in checkpoint workload per data-parallel distributed rank, thereby correspondingly diminishing the checkpointing time and facilitating complete overlap with the training process.

[Arxiv](https://arxiv.org/abs/2408.04307)