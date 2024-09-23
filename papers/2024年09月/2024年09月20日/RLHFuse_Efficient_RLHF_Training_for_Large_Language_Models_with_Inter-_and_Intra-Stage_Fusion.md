# RLHFuse：通过跨阶段与阶段内融合，为大型语言模型带来高效的 RLHF 训练。

发布时间：2024年09月20日

`LLM应用` `人工智能` `云计算`

> RLHFuse: Efficient RLHF Training for Large Language Models with Inter- and Intra-Stage Fusion

# 摘要

> 从人类反馈中进行强化学习 (RLHF) 是一种关键的后训练技术，旨在增强大型语言模型 (LLM) 与人类偏好之间的对齐。然而，现有的 RLHF 系统在生产部署中存在 GPU 利用率低的问题，主要因为生成阶段的数据偏斜和训练阶段的管道气泡。RLHFuse 通过将任务分解为更细粒度的子任务，并执行阶段融合，打破了传统 RLHF 工作流程的局限。对于生成和推理任务，RLHFuse 通过样本级别的子任务分解，缓解了长尾样本带来的生成瓶颈。对于训练任务，RLHFuse 通过微批量子任务的分解和内部阶段融合，减少了管道气泡，提高了 GPU 利用率。此外，RLHFuse 还包含一系列针对 RLHF 每个阶段的系统优化，使其在我们的内部产品使用中高效且可扩展。实验结果显示，与现有的最先进系统相比，RLHFuse 将训练吞吐量提高了多达 3.7 倍。

> Reinforcement Learning from Human Feedback (RLHF) stands as a pivotal post-training technique to enhance the alignment between LLMs and human preference. The workflow of RLHF typically involves several models and tasks in a series of distinct stages. Existing RLHF training systems view each task as the smallest execution unit thus overlooking the opportunities for subtask-level optimizations. Due to the intrinsic nature of RLHF training, i.e., the data skewness in the generation stage, and the pipeline bubbles in the training stage, existing RLHF systems suffer from low GPU utilization in production deployments.
  RLHFuse breaks the traditional view of RLHF workflow as a composition of individual tasks, splitting each task into finer-grained subtasks, and performing stage fusion to improve GPU utilization. RLHFuse contains two key ideas. First, for generation and inference tasks, RLHFuse splits them into sample-level subtasks, enabling efficient inter-stage fusion to mitigate the original generation bottleneck dominated by long-tailed samples. Second, for training tasks, RLHFuse breaks them into subtasks of micro-batches. By leveraging the intuition that pipeline execution can be essentially complemented by another pipeline, RLHFuse performs intra-stage fusion to concurrently execute these subtasks in the training stage with a fused pipeline schedule, resulting in fewer pipeline bubbles. In addition, RLHFuse incorporates a series of system optimizations tailored for each stage of RLHF, making it efficient and scalable for our internal product usage. We evaluate RLHFuse on various popular LLMs and the results show that RLHFuse increases the training throughput by up to 3.7x, compared to existing state-of-the-art systems.

[Arxiv](https://arxiv.org/abs/2409.13221)