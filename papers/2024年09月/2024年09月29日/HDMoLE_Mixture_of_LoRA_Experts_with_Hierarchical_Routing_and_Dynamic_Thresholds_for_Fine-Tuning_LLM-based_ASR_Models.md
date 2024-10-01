# HDMoLE：结合分层路由与动态阈值的 LoRA 专家混合，专为微调 LLM 驱动的 ASR 模型而设计。

发布时间：2024年09月29日

`LLM应用` `语音识别`

> HDMoLE: Mixture of LoRA Experts with Hierarchical Routing and Dynamic Thresholds for Fine-Tuning LLM-based ASR Models

# 摘要

> 近期，LLM 与 ASR 的结合在通用领域表现卓越。然而，全参数监督微调虽能适应特定领域，却带来高计算成本，并削弱通用领域性能。为此，我们提出 \textit{HDMoLE}，一种参数高效的多领域微调方法，专为多口音领域设计，避免灾难性遗忘。HDMoLE 结合分层路由与动态阈值，基于 LoRA 与 MoE，适用于任何线性层。分层路由明确 LoRA 专家与口音领域的对应，增强跨领域协作；动态阈值则自适应激活不同数量的 LoRA 专家。实验表明，HDMoLE 在多口音与标准普通话数据集上表现优异。应用于 LLM 的 ASR 模型投影器模块，HDMoLE 在多口音领域达到全微调水平，仅用 9.6% 的可训练参数，且通用领域性能几乎无损。

> Recent advancements in integrating Large Language Models (LLM) with automatic speech recognition (ASR) have performed remarkably in general domains. While supervised fine-tuning (SFT) of all model parameters is often employed to adapt pre-trained LLM-based ASR models to specific domains, it imposes high computational costs and notably reduces their performance in general domains. In this paper, we propose a novel parameter-efficient multi-domain fine-tuning method for adapting pre-trained LLM-based ASR models to multi-accent domains without catastrophic forgetting named \textit{HDMoLE}, which leverages hierarchical routing and dynamic thresholds based on combining low-rank adaptation (LoRA) with the mixer of experts (MoE) and can be generalized to any linear layer. Hierarchical routing establishes a clear correspondence between LoRA experts and accent domains, improving cross-domain collaboration among the LoRA experts. Unlike the static Top-K strategy for activating LoRA experts, dynamic thresholds can adaptively activate varying numbers of LoRA experts at each MoE layer. Experiments on the multi-accent and standard Mandarin datasets demonstrate the efficacy of HDMoLE. Applying HDMoLE to an LLM-based ASR model projector module achieves similar performance to full fine-tuning in the target multi-accent domains while using only 9.6% of the trainable parameters required for full fine-tuning and minimal degradation in the source general domain.

[Arxiv](https://arxiv.org/abs/2409.19878)