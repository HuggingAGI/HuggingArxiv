# ACDC：通过扩散校正实现的自回归连贯多模态生成

发布时间：2024年10月06日

`LLM应用` `多模态生成` `计算机视觉`

> ACDC: Autoregressive Coherent Multimodal Generation using Diffusion Correction

# 摘要

> 自回归模型 (ARMs) 和扩散模型 (DMs) 在生成建模中各有所长：ARMs 擅长全局上下文和长序列生成，而 DMs 则在图像和短视频等连续数据的局部细节生成上表现优异。然而，ARMs 在长序列中易出现误差累积，导致结果不真实，而 DMs 则受限于局部生成能力。为此，我们提出了自回归一致性多模态生成与扩散校正 (ACDC)，这是一种无需额外微调的零-shot 方法，结合了 ARMs 和 DMs 的优势。ACDC 通过 ARMs 生成全局上下文，并利用记忆条件 DMs 进行局部校正，确保高质量输出。我们还设计了一个基于大型语言模型 (LLMs) 的记忆模块，动态调整 DMs 的条件文本，保留全局关键信息。实验证明，ACDC 在多模态任务中有效减少了误差累积，显著提升了生成质量，且不依赖于特定模型架构。项目页面：https://acdc2025.github.io/

> Autoregressive models (ARMs) and diffusion models (DMs) represent two leading paradigms in generative modeling, each excelling in distinct areas: ARMs in global context modeling and long-sequence generation, and DMs in generating high-quality local contexts, especially for continuous data such as images and short videos. However, ARMs often suffer from exponential error accumulation over long sequences, leading to physically implausible results, while DMs are limited by their local context generation capabilities. In this work, we introduce Autoregressive Coherent multimodal generation with Diffusion Correction (ACDC), a zero-shot approach that combines the strengths of both ARMs and DMs at the inference stage without the need for additional fine-tuning. ACDC leverages ARMs for global context generation and memory-conditioned DMs for local correction, ensuring high-quality outputs by correcting artifacts in generated multimodal tokens. In particular, we propose a memory module based on large language models (LLMs) that dynamically adjusts the conditioning texts for the DMs, preserving crucial global context information. Our experiments on multimodal tasks, including coherent multi-frame story generation and autoregressive video generation, demonstrate that ACDC effectively mitigates the accumulation of errors and significantly enhances the quality of generated outputs, achieving superior performance while remaining agnostic to specific ARM and DM architectures. Project page: https://acdc2025.github.io/

[Arxiv](https://arxiv.org/abs/2410.04721)