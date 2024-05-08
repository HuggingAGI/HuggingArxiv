# QServe：W4A8KV4 量化与系统协同设计，为大型语言模型服务提供高效解决方案

发布时间：2024年05月07日

`LLM应用

这篇论文讨论了一种创新的量化方案QoQ，以及基于此方案的QServe推理库，旨在加速大型语言模型（LLM）的推理过程。它专注于解决现有INT4量化方法在GPU上去量化时产生的运行时开销问题，并通过实验展示了其在提高吞吐量和降低服务成本方面的有效性。这些内容与LLM的实际应用紧密相关，特别是在优化推理性能和降低成本方面，因此将其归类为LLM应用。` `云计算` `人工智能服务`

> QServe: W4A8KV4 Quantization and System Co-design for Efficient LLM Serving

# 摘要

> 量化技术正在推动大型语言模型（LLM）推理的加速，尤其是INT4精度的探索。然而，现有的INT4量化方法在云端大批量LLM服务中遇到了瓶颈，因为它们在GPU上去量化时产生了巨大的运行时开销。为此，我们推出了QoQ——一种创新的W4A8KV4量化方案，它通过QServe推理库实现了显著的加速效果。QoQ巧妙地结合了4位权重、8位激活和4位KV缓存，并通过渐进式量化和SmoothAttention技术，有效降低了去量化开销并保持了模型精度。QServe系统通过计算感知权重排序和寄存器级并行，进一步优化了去量化延迟，并利用KV4量化提升了性能。实验结果显示，QServe在Llama和Qwen模型上实现了显著的吞吐量提升，甚至在L40S GPU上超越了TensorRT-LLM在A100上的表现，大幅降低了LLM服务的成本。代码已公开，供研究者探索。

> Quantization can accelerate large language model (LLM) inference. Going beyond INT8 quantization, the research community is actively exploring even lower precision, such as INT4. Nonetheless, state-of-the-art INT4 quantization techniques only accelerate low-batch, edge LLM inference, failing to deliver performance gains in large-batch, cloud-based LLM serving. We uncover a critical issue: existing INT4 quantization methods suffer from significant runtime overhead (20-90%) when dequantizing either weights or partial sums on GPUs. To address this challenge, we introduce QoQ, a W4A8KV4 quantization algorithm with 4-bit weight, 8-bit activation, and 4-bit KV cache. QoQ stands for quattuor-octo-quattuor, which represents 4-8-4 in Latin. QoQ is implemented by the QServe inference library that achieves measured speedup. The key insight driving QServe is that the efficiency of LLM serving on GPUs is critically influenced by operations on low-throughput CUDA cores. Building upon this insight, in QoQ algorithm, we introduce progressive quantization that can allow low dequantization overhead in W4A8 GEMM. Additionally, we develop SmoothAttention to effectively mitigate the accuracy degradation incurred by 4-bit KV quantization. In the QServe system, we perform compute-aware weight reordering and take advantage of register-level parallelism to reduce dequantization latency. We also make fused attention memory-bound, harnessing the performance gain brought by KV4 quantization. As a result, QServe improves the maximum achievable serving throughput of Llama-3-8B by 1.2x on A100, 1.4x on L40S; and Qwen1.5-72B by 2.4x on A100, 3.5x on L40S, compared to TensorRT-LLM. Remarkably, QServe on L40S GPU can achieve even higher throughput than TensorRT-LLM on A100. Thus, QServe effectively reduces the dollar cost of LLM serving by 3x. Code is available at https://github.com/mit-han-lab/qserve.

[Arxiv](https://arxiv.org/abs/2405.04532)