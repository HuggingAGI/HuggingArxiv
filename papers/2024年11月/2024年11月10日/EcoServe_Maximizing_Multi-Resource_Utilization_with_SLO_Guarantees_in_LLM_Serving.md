# EcoServe：在 LLM 服务中以 SLO 保证实现多资源利用率最大化

发布时间：2024年11月10日

`LLM应用` `语言模型` `资源调度`

> EcoServe: Maximizing Multi-Resource Utilization with SLO Guarantees in LLM Serving

# 摘要

> 随着大型语言模型（LLMs）不断发展，降低成本和减轻 GPU 需求变得越来越关键。然而，现有的调度器主要针对 GPU 计算或键值缓存（KVC）利用率，无法在每次迭代中充分优化 GPU 计算和 KVC 使用，也无法在需要时保证及时的 KVC 分配。为了应对这些挑战，我们进行了基于跟踪的实验分析并得出了有洞察力的观察结果，从而设计了一个名为 EcoServe 的系统。EcoServe 在确保 LLM 服务中的服务级别目标（SLO）保证的同时，最大限度地提高了多资源利用率。为了能够在每次迭代中将提示添加到批次中以最大化 GPU 利用率，EcoServe 为提示处理任务（PTs）和生成任务（GTs）维护单独的等待队列。它将具有相同预测响应长度（RL）的 GTs 进行批处理以节省调度时间，并为预测的 RL 分配 KVC 空间以避免 KVC 分配失败。它还具有一种新颖的 KVC 流水线方法，允许共享已分配但未使用的 KVC 空间以提高 KVC 利用率。此外，它优先处理占用更多 KVC 的排队请求，以便更早释放 KVC 并满足请求服务级别目标（SLO）。实验结果表明，与 vLLM 相比，EcoServe 在相同的延迟水平下吞吐量提高了多达 4 倍，作业完成时间减少了多达 91％，SLO 满意度提高了多达 91％。它还将 DistServe 中使用的 GPU 数量减少了多达 78％，同时保持相同水平的良好输出。

> As Large Language Models (LLMs) continue to grow, reducing costs and alleviating GPU demands has become increasingly critical. However, existing schedulers primarily target either GPU compute or Key-Value Cache (KVC) utilization, failing to fully optimize both GPU compute and KVC usage during each iteration or guarantee timely KVC allocations when needed. To address these challenges, we conducted a trace-based experimental analysis and made insightful observations, leading to the design of a system called EcoServe. EcoServe maximizes multi-resource utilization while ensuring service-level objective (SLO) guarantees in LLM serving. To enable adding prompts to a batch to maximize GPU utilization in each iteration, EcoServe maintains separate waiting queues for prompt processing tasks (PTs) and generation tasks (GTs). It batches GTs with the same predicted response lengths (RL) to save scheduling time and allocates KVC space for the predicted RL to avoid KVC allocation failures. It further has a novel KVC pipelining method, allowing sharing allocated but unused KVC space to enhance KVC utilization. In addition, it prioritizes queued requests that occupy more KVC to release KVC earlier and satisfy request service-level-objective (SLO). Experimental results demonstrate that EcoServe increases throughput by up to 4$\times$ with the same level of latency, generates up to 91\% lower job completion time and up to 91\% higher SLO satisfaction ratio compared to vLLM. It also reduces the number of GPUs used in DistServe by up to 78\% while maintaining the same level of goodput.

[Arxiv](https://arxiv.org/abs/2411.06364)