# 为高性能机器学习推理，对边缘 AI 平台进行基准测试

发布时间：2024年09月23日

`LLM应用` `边缘计算` `人工智能`

> Benchmarking Edge AI Platforms for High-Performance ML Inference

# 摘要

> 边缘计算因其降低延迟和实现实时处理的能力而备受瞩目，推动了高性能异构片上系统的发展。尽管现有方法常通过缩小硬件规模来实现，但这些平台上的神经网络性能差异显著，尤其是在并行处理方面。为此，我们对比了仅CPU、CPU/GPU和CPU/NPU集成方案在各类线性代数和神经网络任务中的延迟与吞吐量。结果显示，NPU在矩阵向量乘法和某些神经网络任务中表现突出，GPU则在矩阵乘法和LSTM网络中占优，而CPU在点积等操作中表现优异。NPU在低功耗下实现了延迟与吞吐量的平衡，GPU虽能耗较高，但在大维度和大批量处理中表现最佳。这表明，异构计算在边缘AI中具有巨大潜力，通过合理利用多样化的计算单元，可显著提升推理的准确性和实时性。

> Edge computing's growing prominence, due to its ability to reduce communication latency and enable real-time processing, is promoting the rise of high-performance, heterogeneous System-on-Chip solutions. While current approaches often involve scaling down modern hardware, the performance characteristics of neural network workloads on these platforms can vary significantly, especially when it comes to parallel processing, which is a critical consideration for edge deployments. To address this, we conduct a comprehensive study comparing the latency and throughput of various linear algebra and neural network inference tasks across CPU-only, CPU/GPU, and CPU/NPU integrated solutions. {We find that the Neural Processing Unit (NPU) excels in matrix-vector multiplication (58.6% faster) and some neural network tasks (3.2$\times$ faster for video classification and large language models). GPU outperforms in matrix multiplication (22.6% faster) and LSTM networks (2.7$\times$ faster) while CPU excels at less parallel operations like dot product. NPU-based inference offers a balance of latency and throughput at lower power consumption. GPU-based inference, though more energy-intensive, performs best with large dimensions and batch sizes. We highlight the potential of heterogeneous computing solutions for edge AI, where diverse compute units can be strategically leveraged to boost accurate and real-time inference.

[Arxiv](https://arxiv.org/abs/2409.14803)