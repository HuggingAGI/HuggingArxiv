# [HeteGen 是专为资源有限的设备设计的，能够实现大型语言模型的异构并行推理技术。这项技术针对大模型在资源受限环境下的高效运行，提供了一种创新的并行处理方案。]

发布时间：2024年03月02日

`Agent`

> HeteGen: Heterogeneous Parallel Inference for Large Language Models on Resource-Constrained Devices

> 随着LLMs的快速发展，其庞大的模型尺寸给低配置设备的推理带来了难题，过往的解决方案虽然尝试通过卸载提高低内存推理性能，却常常因I/O瓶颈而影响效率。为解决这一问题，我们推出了创新方案——HeteGen，它构建了一个基于CPU和GPU异构并行计算的系统化框架。在此框架下，HeteGen巧妙运用异构并行计算与异步重叠技术，有效破除LLMs的I/O瓶颈，实验证明可将推理速度大幅提升，最高可达当前最佳方法的317%以上。

> In recent times, the emergence of Large Language Models (LLMs) has resulted in increasingly larger model size, posing challenges for inference on low-resource devices. Prior approaches have explored offloading to facilitate low-memory inference but often suffer from efficiency due to I/O bottlenecks. To achieve low-latency LLMs inference on resource-constrained devices, we introduce HeteGen, a novel approach that presents a principled framework for heterogeneous parallel computing using CPUs and GPUs. Based on this framework, HeteGen further employs heterogeneous parallel computing and asynchronous overlap for LLMs to mitigate I/O bottlenecks. Our experiments demonstrate a substantial improvement in inference speed, surpassing state-of-the-art methods by over 317% at most.

[Arxiv](https://arxiv.org/abs/2403.01164)