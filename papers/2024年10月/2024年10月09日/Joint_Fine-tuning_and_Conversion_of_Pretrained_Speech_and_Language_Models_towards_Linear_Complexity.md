# 联合微调与转换预训练语音和语言模型，以实现线性复杂度

发布时间：2024年10月09日

`LLM理论` `人工智能`

> Joint Fine-tuning and Conversion of Pretrained Speech and Language Models towards Linear Complexity

# 摘要

> Linformer 和 Mamba 等新型架构作为 Transformer 的线性时间替代方案崭露头角，但在非文本领域，相应的大型预训练模型却往往缺失。为此，我们推出了跨架构逐层蒸馏（CALD）技术，既能将 Transformer 模型转换为线性时间替代品，又能针对目标任务进行微调。我们还探讨了多种引导微调的方法，以确保原始模型的推理能力得以保留。这些方法在目标模型和参数轨迹的运用上各有千秋。通过一系列语言处理、语言建模和语音处理的实验，我们验证了 CALD 的有效性，并揭示了引导策略对结果的积极影响。此外，我们还探讨了结果差异背后的原因。

> Architectures such as Linformer and Mamba have recently emerged as competitive linear time replacements for transformers. However, corresponding large pretrained models are often unavailable, especially in non-text domains. To remedy this, we present a Cross-Architecture Layerwise Distillation (CALD) approach that jointly converts a transformer model to a linear time substitute and fine-tunes it to a target task. We also compare several means to guide the fine-tuning to optimally retain the desired inference capability from the original model. The methods differ in their use of the target model and the trajectory of the parameters. In a series of empirical studies on language processing, language modeling, and speech processing, we show that CALD can effectively recover the result of the original model, and that the guiding strategy contributes to the result. Some reasons for the variation are suggested.

[Arxiv](https://arxiv.org/abs/2410.06846)