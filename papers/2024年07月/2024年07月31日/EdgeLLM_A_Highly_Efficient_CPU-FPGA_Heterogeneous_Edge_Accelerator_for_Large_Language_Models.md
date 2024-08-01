# EdgeLLM：专为大型语言模型设计的高效 CPU-FPGA 异构边缘加速器

发布时间：2024年07月31日

`LLM应用` `边缘计算` `人工智能`

> EdgeLLM: A Highly Efficient CPU-FPGA Heterogeneous Edge Accelerator for Large Language Models

# 摘要

> 随着人工智能（AI），尤其是大型语言模型（LLM）的迅猛发展，我们的工作和交流方式正经历深刻变革。然而，LLM的庞大体量在资源有限的边缘设备（如智能手机、机器人和嵌入式系统）上部署时，面临重大操作难题。为此，我们创新性地提出了EdgeLLM框架，通过CPU-FPGA异构加速，大幅提升LLM在边缘端的计算效能。我们首先对AI模型中的操作符进行了全面分析，并设计了通用的数据并行策略，适用于各类AI算法。接着，依据特定数据格式，我们定制了硬件操作符，并融入了多项优化技术，包括近似计算引擎、组向量脉动阵列、对数尺度稀疏性以及数据传输与处理的异步机制。最终，我们构建了端到端的编译方案，实现操作符的动态编译与模型在异构系统上的高效映射。在AMD Xilinx VCU128 FPGA上的实际部署显示，我们的加速器在ChatGLM2-6B模型上，吞吐量提升1.67倍，能效比提高7.4倍，超越了商业GPU（NVIDIA A100-SXM4-80G），并在HBM带宽利用率和LLM吞吐量方面，较FlightLLM的FPGA加速器有10%~20%的性能优势。

> The rapid advancements in artificial intelligence (AI), particularly the Large Language Models (LLMs), have profoundly affected our daily work and communication forms. However, the colossal scale of LLM presents significant operational challenges, particularly when attempting to deploy them on resource-constrained edge devices such as smartphones, robots, and embedded systems. In this work, we proposed EdgeLLM, an efficient CPU-FPGA heterogeneous acceleration framework, to markedly enhance the computational efficiency of LLMs on edge. We first analyzed the whole operators within AI models and developed a universal data parallelism scheme, which is generic and can be adapted to any type of AI algorithm. Then, we developed fully-customized hardware operators according to the designated data formats. A multitude of optimization techniques have been integrated in the design, such as approximate FP16*INT4 and FP16*FP16 computation engines, group vector systolic arrays, log-scale structured sparsity, asynchronous between data transfer and processing. Finally, we proposed an end-to-end compilation scheme that can dynamically compile all of the operators and map the whole model on CPU-FPGA heterogeneous system. The design has been deployed on AMD Xilinx VCU128 FPGA, our accelerator achieves 1.67x higher throughput and 7.4x higher energy efficiency than the commercial GPU (NVIDIA A100-SXM4-80G) on ChatGLM2-6B, and shows 10%~20% better performance than state-of-the-art FPGA accelerator of FlightLLM in terms of HBM bandwidth utilization and LLM throughput.

[Arxiv](https://arxiv.org/abs/2407.21325)