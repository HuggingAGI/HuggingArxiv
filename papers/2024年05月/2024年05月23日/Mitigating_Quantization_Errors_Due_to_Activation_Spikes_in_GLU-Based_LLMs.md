# 缓解基于GLU的LLMs中激活尖峰导致的量化误差问题

发布时间：2024年05月23日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）中的激活量化问题，特别是GLU变体中的激活尖峰问题，并提出了相应的解决方案（无量化模块QFeM和无量化前缀QFeP）。这些问题和解决方案都是关于LLMs内部机制的理论性探讨，而非直接的应用或Agent行为。因此，它更符合LLM理论的分类。` `人工智能` `模型优化`

> Mitigating Quantization Errors Due to Activation Spikes in GLU-Based LLMs

# 摘要

> 现代大型语言模型（LLMs）虽通过架构优化达到顶尖性能，但推理成本依旧高昂。为此，后训练量化（PTQ）应运而生，将模型参数压缩至低精度，如INT8，以节省资源。然而，我们发现GLU变体中的激活量化面临难题：这些变体在LLaMA等模型中广泛应用，其激活值的极端波动导致量化误差剧增，严重损害模型性能。我们称这些极端激活为“激活尖峰”。观察表明，这些尖峰主要出现在模型的特定层，尤其是开头和结尾，且仅影响少数特定令牌，而非整个序列。基于此，我们提出了两种策略：无量化模块（QFeM）和无量化前缀（QFeP），旨在量化过程中隔离这些尖峰。实验证明，这些方法显著提升了包括LLaMA-2/3、Mistral、Mixtral、SOLAR和Gemma在内的最新LLMs的激活量化效果，尤其是在粗粒度量化方案下。此外，我们的方法还强化了现有技术（如SmoothQuant），这些技术原本未能有效控制激活尖峰。相关代码已公开于https://github.com/onnoo/activation-spikes。

> Modern large language models (LLMs) have established state-of-the-art performance through architectural improvements, but still require significant computational cost for inference. In an effort to reduce the inference cost, post-training quantization (PTQ) has become a popular approach, quantizing weights and activations to lower precision, such as INT8. In this paper, we reveal the challenges of activation quantization in GLU variants, which are widely used in feed-forward network (FFN) of modern LLMs, such as LLaMA family. The problem is that severe local quantization errors, caused by excessive magnitudes of activation in GLU variants, significantly degrade the performance of the quantized LLM. We denote these activations as activation spikes. Our further observations provide a systematic pattern of activation spikes: 1) The activation spikes occur in the FFN of specific layers, particularly in the early and late layers, 2) The activation spikes are dedicated to a couple of tokens, rather than being shared across a sequence. Based on our observations, we propose two empirical methods, Quantization-free Module (QFeM) and Quantization-free Prefix (QFeP), to isolate the activation spikes during quantization. Our extensive experiments validate the effectiveness of the proposed methods for the activation quantization, especially with coarse-grained scheme, of latest LLMs with GLU variants, including LLaMA-2/3, Mistral, Mixtral, SOLAR, and Gemma. In particular, our methods enhance the current alleviation techniques (e.g., SmoothQuant) that fail to control the activation spikes. Code is available at https://github.com/onnoo/activation-spikes.

[Arxiv](https://arxiv.org/abs/2405.14428)