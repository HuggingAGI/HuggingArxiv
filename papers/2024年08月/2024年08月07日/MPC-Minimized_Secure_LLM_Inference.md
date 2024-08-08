# 最小化 MPC 的安全 LLM 推理

发布时间：2024年08月07日

`LLM应用` `网络安全` `云计算`

> MPC-Minimized Secure LLM Inference

# 摘要

> 基于大型语言模型 (LLM) 的推理服务常涉及隐私泄露问题，无论是用户提示还是专有权重。虽然安全多方计算 (MPC) 提供了安全推理的解决方案，但其高昂的开销使其不适用于现代 LLM 工作负载。为此，我们设计了 Marill 框架，通过优化 LLM 微调过程，显著减少安全推理中 MPC 的使用。Marill 在微调阶段进行架构调整，通过精简和重定位操作，大幅降低了 MPC 内的昂贵操作，确保了安全性不受影响。因此，Marill 生成的模型在所有安全推理协议中表现更佳，并优化了 MPC 友好型操作。相较于传统微调，Marill 在不同 MPC 环境下，安全推理的运行时间和通信效率分别提升了 3.6-11.3 倍和 2.4-6.9 倍，同时保持了下游任务性能的 90% 以上。

> Many inference services based on large language models (LLMs) pose a privacy concern, either revealing user prompts to the service or the proprietary weights to the user. Secure inference offers a solution to this problem through secure multi-party computation (MPC), however, it is still impractical for modern LLM workload due to the large overhead imposed by MPC. To address this overhead, we propose Marill, a framework that adapts LLM fine-tuning to minimize MPC usage during secure inference. Marill introduces high-level architectural changes during fine-tuning that significantly reduce the number of expensive operations needed within MPC during inference, by removing some and relocating others outside MPC without compromising security. As a result, Marill-generated models are more efficient across all secure inference protocols and our approach complements MPC-friendly approximations for such operations. Compared to standard fine-tuning, Marill results in 3.6-11.3x better runtime and 2.4-6.9x better communication during secure inference across various MPC settings, while typically preserving over 90% performance across downstream tasks.

[Arxiv](https://arxiv.org/abs/2408.03561)