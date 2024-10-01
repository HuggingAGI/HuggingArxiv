# HybridFlow：灵活高效的 RLHF 框架

发布时间：2024年09月28日

`LLM应用` `人工智能` `分布式计算`

> HybridFlow: A Flexible and Efficient RLHF Framework

# 摘要

> RLHF 在 LLM 对齐中广泛应用。传统 RL 模型化为数据流，节点代表神经网络计算，边表示数据依赖。RLHF 通过将节点扩展为分布式 LLM 训练或生成程序，边扩展为多对多组播，复杂化了数据流。传统 RL 框架使用单控制器指导节点内计算和节点间通信，在 RLHF 中效率低下。现有 RLHF 系统采用多控制器范式，但因嵌套分布式计算和数据通信而不够灵活。我们提出 HybridFlow，结合单控制器和多控制器范式，实现 RLHF 数据流的灵活表示和高效执行。我们设计了分层 API，解耦和封装复杂 RLHF 数据流中的计算和数据依赖，允许高效操作编排和灵活计算映射。我们还设计了 3D-HybridEngine，实现训练和生成阶段间 actor 模型的高效重新分片，零内存冗余并显著减少通信开销。实验结果显示，与最先进基线相比，使用 HybridFlow 运行 RLHF 算法时，吞吐量提高了 1.53 倍至 20.57 倍。源代码可在 https://github.com/volcengine/verl 获取。

> Reinforcement Learning from Human Feedback (RLHF) is widely used in Large Language Model (LLM) alignment. Traditional RL can be modeled as a dataflow, where each node represents computation of a neural network (NN) and each edge denotes data dependencies between the NNs. RLHF complicates the dataflow by expanding each node into a distributed LLM training or generation program, and each edge into a many-to-many multicast. Traditional RL frameworks execute the dataflow using a single controller to instruct both intra-node computation and inter-node communication, which can be inefficient in RLHF due to large control dispatch overhead for distributed intra-node computation. Existing RLHF systems adopt a multi-controller paradigm, which can be inflexible due to nesting distributed computation and data communication. We propose HybridFlow, which combines single-controller and multi-controller paradigms in a hybrid manner to enable flexible representation and efficient execution of the RLHF dataflow. We carefully design a set of hierarchical APIs that decouple and encapsulate computation and data dependencies in the complex RLHF dataflow, allowing efficient operation orchestration to implement RLHF algorithms and flexible mapping of the computation onto various devices. We further design a 3D-HybridEngine for efficient actor model resharding between training and generation phases, with zero memory redundancy and significantly reduced communication overhead. Our experimental results demonstrate 1.53$\times$~20.57$\times$ throughput improvement when running various RLHF algorithms using HybridFlow, as compared with state-of-the-art baselines. HybridFlow source code is available at https://github.com/volcengine/verl.

[Arxiv](https://arxiv.org/abs/2409.19256)