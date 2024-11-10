# SVDQunat：通过低秩分量吸收 4 位扩散模型中的异常值

发布时间：2024年11月07日

`其他` `图像生成` `模型量化`

> SVDQunat: Absorbing Outliers by Low-Rank Components for 4-Bit Diffusion Models

# 摘要

> 扩散模型已被证明在生成高质量图像方面非常有效。然而，随着这些模型变得更大，它们需要大量更多的内存，并遭受更高的延迟，这给部署带来了巨大的挑战。在这项工作中，我们旨在通过将其权重和激活量化为 4 位来加速扩散模型。在如此激进的水平下，权重和激活都非常敏感，对于大型语言模型的传统的训练后量化方法，如平滑，变得不够用。为了克服这一限制，我们提出了 SVDQuant，一种新的 4 位量化范式。与在权重和激活之间重新分配异常值的平滑不同，我们的方法使用低秩分支吸收这些异常值。我们首先通过将异常值从激活转移到权重来整合它们，然后使用高精度的低秩分支通过奇异值分解（SVD）接收权重异常值。这个过程缓解了两边的量化。然而，天真地独立运行低秩分支会由于激活的额外数据移动而导致显著的开销，否定了量化加速。为了解决这个问题，我们共同设计了一个推理引擎 Nunchaku，它将低秩分支的内核融合到低位分支的内核中，以切断冗余的内存访问。它还可以无缝支持现成的低秩适配器（LoRAs），而无需重新量化。在 SDXL、PixArt-Σ 和 FLUX.1 上进行的大量实验验证了 SVDQuant 在保持图像质量方面的有效性。我们将 12B FLUX.1 模型的内存使用减少了 3.5 倍，在 16GB 笔记本电脑 4090 GPU 上比仅 4 位权重量化的基线实现了 3.0 倍的加速，为在个人电脑上的更多交互应用铺平了道路。我们的量化库和推理引擎是开源的。

> Diffusion models have been proven highly effective at generating high-quality images. However, as these models grow larger, they require significantly more memory and suffer from higher latency, posing substantial challenges for deployment. In this work, we aim to accelerate diffusion models by quantizing their weights and activations to 4 bits. At such an aggressive level, both weights and activations are highly sensitive, where conventional post-training quantization methods for large language models like smoothing become insufficient. To overcome this limitation, we propose SVDQuant, a new 4-bit quantization paradigm. Different from smoothing which redistributes outliers between weights and activations, our approach absorbs these outliers using a low-rank branch. We first consolidate the outliers by shifting them from activations to weights, then employ a high-precision low-rank branch to take in the weight outliers with Singular Value Decomposition (SVD). This process eases the quantization on both sides. However, naïvely running the low-rank branch independently incurs significant overhead due to extra data movement of activations, negating the quantization speedup. To address this, we co-design an inference engine Nunchaku that fuses the kernels of the low-rank branch into those of the low-bit branch to cut off redundant memory access. It can also seamlessly support off-the-shelf low-rank adapters (LoRAs) without the need for re-quantization. Extensive experiments on SDXL, PixArt-$Σ$, and FLUX.1 validate the effectiveness of SVDQuant in preserving image quality. We reduce the memory usage for the 12B FLUX.1 models by 3.5$\times$, achieving 3.0$\times$ speedup over the 4-bit weight-only quantized baseline on the 16GB laptop 4090 GPU, paving the way for more interactive applications on PCs. Our quantization library and inference engine are open-sourced.

[Arxiv](https://arxiv.org/abs/2411.05007)