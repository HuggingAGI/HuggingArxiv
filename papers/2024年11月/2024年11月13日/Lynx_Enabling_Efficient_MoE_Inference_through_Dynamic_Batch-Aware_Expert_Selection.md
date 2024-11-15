# Lynx：借由动态批量感知的专家选择达成高效的 MoE 推理

发布时间：2024年11月13日

`LLM应用` `语言模型` `推理系统`

> Lynx: Enabling Efficient MoE Inference through Dynamic Batch-Aware Expert Selection

# 摘要

> MoE 架构近来在助力大型语言模型高效扩展方面大受欢迎。然而，我们发现了一个根本矛盾：MoE 本是为选择性激活专家而设计，可生产服务却需要请求批处理，这就迫使所有专家都被激活，从而在解码阶段抵消了 MoE 的效率优势。我们推出了 Lynx 系统，它通过动态、具有批处理感知的专家选择来实现高效的 MoE 推理。我们的关键发现是，专家的重要性在不同的令牌和推理阶段差异显著，这为运行时优化创造了契机。Lynx 借助一个轻量级框架利用这一发现，在保持模型准确性的同时动态减少活跃专家。我们的评估显示，在复杂的代码生成和数学推理任务中，Lynx 在保持与基线模型相比可忽略不计的精度损失的同时，推理延迟最多降低了 1.55 倍。

> Mixture-of-Experts (MoE) architectures have recently gained popularity in enabling efficient scaling of large language models. However, we uncover a fundamental tension: while MoEs are designed for selective expert activation, production serving requires request batching, which forces the activation of all experts and negates MoE's efficiency benefits during the decode phase. We present Lynx, a system that enables efficient MoE inference through dynamic, batch-aware expert selection. Our key insight is that expert importance varies significantly across tokens and inference phases, creating opportunities for runtime optimization. Lynx leverages this insight through a lightweight framework that dynamically reduces active experts while preserving model accuracy. Our evaluations show that Lynx achieves up to 1.55x reduction in inference latency while maintaining negligible accuracy loss from baseline model across complex code generation and mathematical reasoning tasks.

[Arxiv](https://arxiv.org/abs/2411.08982)