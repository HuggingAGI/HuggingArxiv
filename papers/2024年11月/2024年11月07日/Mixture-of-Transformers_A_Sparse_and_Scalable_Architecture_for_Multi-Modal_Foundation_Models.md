# 混合 Transformer：一种用于多模态基础模型的稀疏且可扩展的架构

发布时间：2024年11月07日

`LLM应用` `多模态` `模型架构`

> Mixture-of-Transformers: A Sparse and Scalable Architecture for Multi-Modal Foundation Models

# 摘要

> 大型语言模型（LLM）的发展已经扩展到能够在统一框架内处理文本、图像和语音的多模态系统。与仅处理文本的 LLM 相比，训练这些模型需要更大的数据集和计算资源。为了解决扩展挑战，我们引入了混合变压器（MoT），这是一种稀疏的多模态变压器架构，显著降低了预训练的计算成本。MoT 按模态解耦模型的非嵌入参数——包括前馈网络、注意力矩阵和层归一化——能够对整个输入序列进行全局自注意力的模态特定处理。我们在多个设置和模型规模上评估 MoT。在变色龙 7B 设置（自回归文本和图像生成）中，MoT 仅使用 55.8％的 FLOPs 就达到了密集基线的性能。当扩展到包括语音时，MoT 仅使用 37.2％的 FLOPs 就达到了与密集基线相当的语音性能。在输血设置中，其中文本和图像以不同的目标进行训练，一个 7B 的 MoT 模型仅使用三分之一的 FLOPs 就达到了密集基线的图像模态性能，而一个 760M 的 MoT 模型在关键图像生成指标上超过了 1.4B 的密集基线。系统分析进一步突出了 MoT 的实际好处，在 47.2％的挂钟时间内达到密集基线的图像质量，在 75.6％的挂钟时间内达到文本质量（在具有 NVIDIA A100 GPU 的 AWS p4de.24xlarge 实例上测量）。

> The development of large language models (LLMs) has expanded to multi-modal systems capable of processing text, images, and speech within a unified framework. Training these models demands significantly larger datasets and computational resources compared to text-only LLMs. To address the scaling challenges, we introduce Mixture-of-Transformers (MoT), a sparse multi-modal transformer architecture that significantly reduces pretraining computational costs. MoT decouples non-embedding parameters of the model by modality -- including feed-forward networks, attention matrices, and layer normalization -- enabling modality-specific processing with global self-attention over the full input sequence. We evaluate MoT across multiple settings and model scales. In the Chameleon 7B setting (autoregressive text-and-image generation), MoT matches the dense baseline's performance using only 55.8\% of the FLOPs. When extended to include speech, MoT reaches speech performance comparable to the dense baseline with only 37.2\% of the FLOPs. In the Transfusion setting, where text and image are trained with different objectives, a 7B MoT model matches the image modality performance of the dense baseline with one third of the FLOPs, and a 760M MoT model outperforms a 1.4B dense baseline across key image generation metrics. System profiling further highlights MoT's practical benefits, achieving dense baseline image quality in 47.2\% of the wall-clock time and text quality in 75.6\% of the wall-clock time (measured on AWS p4de.24xlarge instances with NVIDIA A100 GPUs).

[Arxiv](https://arxiv.org/abs/2411.04996)