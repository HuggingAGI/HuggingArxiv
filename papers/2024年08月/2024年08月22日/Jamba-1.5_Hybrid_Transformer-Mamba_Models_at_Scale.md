# Jamba-1.5：融合 Transformer 与 Mamba 的大规模混合模型

发布时间：2024年08月22日

`LLM应用` `人工智能` `软件开发`

> Jamba-1.5: Hybrid Transformer-Mamba Models at Scale

# 摘要

> 我们发布了基于Jamba架构的新型指令调优大型语言模型Jamba-1.5，该架构结合了Transformer和Mamba的优点，不仅在不同上下文长度下提供高吞吐量和低内存使用，还保持了与传统Transformer模型相同或更优的质量。我们推出了两种尺寸的模型：Jamba-1.5-Large（94B参数）和Jamba-1.5-Mini（12B参数），两者均针对多样的对话和指令遵循任务进行了优化，拥有业界领先的256K令牌上下文长度。为降低推理成本，我们创新性地开发了ExpertsInt8量化技术，使得Jamba-1.5-Large能在配备8个80GB GPU的设备上高效运行，且不影响性能。在多项学术和聊天机器人评测中，Jamba-1.5模型表现卓越，尤其在处理长上下文任务时，性能超越了同类开放权重模型。我们已将模型权重和ExpertsInt8技术开源，供公众使用。

> We present Jamba-1.5, new instruction-tuned large language models based on our Jamba architecture. Jamba is a hybrid Transformer-Mamba mixture of experts architecture, providing high throughput and low memory usage across context lengths, while retaining the same or better quality as Transformer models. We release two model sizes: Jamba-1.5-Large, with 94B active parameters, and Jamba-1.5-Mini, with 12B active parameters. Both models are fine-tuned for a variety of conversational and instruction-following capabilties, and have an effective context length of 256K tokens, the largest amongst open-weight models. To support cost-effective inference, we introduce ExpertsInt8, a novel quantization technique that allows fitting Jamba-1.5-Large on a machine with 8 80GB GPUs when processing 256K-token contexts without loss of quality. When evaluated on a battery of academic and chatbot benchmarks, Jamba-1.5 models achieve excellent results while providing high throughput and outperforming other open-weight models on long-context benchmarks. The model weights for both sizes are publicly available under the Jamba Open Model License and we release ExpertsInt8 as open source.

[Arxiv](https://arxiv.org/abs/2408.12570)