# MoE-Lightning：在内存受限的 GPU 上实现高吞吐量的 MoE 推理

发布时间：2024年11月17日

`LLM应用` `语言模型` `推理系统`

> MoE-Lightning: High-Throughput MoE Inference on Memory-constrained GPUs

# 摘要

> 在资源受限的平台上高效部署大型语言模型，尤其是专家混合模型（MoE），面临着诸多重大挑战，特别是在计算效率和内存使用方面。MoE 架构因能在不相应增加推理成本的情况下提升模型容量而著称，与密集模型相比，它大幅降低了令牌生成的延迟。然而，庞大的模型规模致使没有高端 GPU 的个人难以使用 MoE 模型。在本文中，我们提出了一个高吞吐量的 MoE 批量推理系统，其表现远超以往成果。MoE-Lightning 引入了新颖的 CPU-GPU-I/O 流水线调度 CGOPipe，带有分页权重以实现高资源利用率，还有一个基于我们引入的分层屋顶线模型的性能模型 HRM，用于帮助找到比现有系统吞吐量更高的策略。MoE-Lightning 在单个 T4 GPU（16GB）上针对 Mixtral 8x7B 能够实现比最先进的支持卸载的 LLM 推理系统高达 10.3 倍的吞吐量。当理论系统吞吐量受 GPU 内存限制时，MoE-Lightning 只需 2 - 3 倍更少的 CPU 内存就能达到吞吐量上限，显著提升了资源利用率。MoE-Lightning 还支持在多个低成本 GPU（如 2 - 4 个 T4）上对更大的 MoE（如 Mixtral 8x22B 和 DBRX）进行高效的批量推理。

> Efficient deployment of large language models, particularly Mixture of Experts (MoE), on resource-constrained platforms presents significant challenges, especially in terms of computational efficiency and memory utilization. The MoE architecture, renowned for its ability to increase model capacity without a proportional increase in inference cost, greatly reduces the token generation latency compared with dense models. However, the large model size makes MoE models inaccessible to individuals without high-end GPUs. In this paper, we propose a high-throughput MoE batch inference system, that significantly outperforms past work. MoE-Lightning introduces a novel CPU-GPU-I/O pipelining schedule, CGOPipe, with paged weights to achieve high resource utilization, and a performance model, HRM, based on a Hierarchical Roofline Model we introduce to help find policies with higher throughput than existing systems. MoE-Lightning can achieve up to 10.3x higher throughput than state-of-the-art offloading-enabled LLM inference systems for Mixtral 8x7B on a single T4 GPU (16GB). When the theoretical system throughput is bounded by the GPU memory, MoE-Lightning can reach the throughput upper bound with 2-3x less CPU memory, significantly increasing resource utilization. MoE-Lightning also supports efficient batch inference for much larger MoEs (e.g., Mixtral 8x22B and DBRX) on multiple low-cost GPUs (e.g., 2-4 T4).

[Arxiv](https://arxiv.org/abs/2411.11217)