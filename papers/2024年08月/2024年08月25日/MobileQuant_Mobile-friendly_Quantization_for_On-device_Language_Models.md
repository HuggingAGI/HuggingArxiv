# MobileQuant：专为移动设备设计的语言模型量化方案

发布时间：2024年08月25日

`LLM应用` `移动设备` `人工智能`

> MobileQuant: Mobile-friendly Quantization for On-device Language Models

# 摘要

> 大型语言模型 (LLM) 在语言处理领域取得了革命性进展，广泛应用于多个领域并取得了卓越成果。然而，在边缘设备上部署这些模型时，内存、能源和计算成本成为主要障碍，尤其是在移动设备上。为了解决这一问题，减少权重和激活的位数成为一种有前景的方案。尽管现有研究在将 LLM 量化至较低位宽（如 4 位权重）方面取得了一定进展，但激活量化超过 16 位时，常因设备量化支持不足或精度大幅下降而导致高计算开销。相比之下，8 位激活量化因其能充分利用移动友好型硬件（如神经处理单元 NPU）而备受青睐。本研究首次尝试通过仅整数量化技术来促进 LLM 在设备上的部署。我们深入分析了现有量化方法在设备部署中的局限性，特别是激活量化方面，并提出了一种名为 MobileQuant 的简单后训练量化方法。该方法通过端到端地联合优化权重转换和激活范围参数，显著提升了量化性能，实现了以下优势：1) 在广泛的 LLM 基准测试中近乎无损的量化效果，2) 相比现有设备上量化策略，延迟和能源消耗降低 20%-50%，3) 计算预算需求有限，4) 与移动友好型计算单元（如 NPU）高度兼容。

> Large language models (LLMs) have revolutionized language processing, delivering outstanding results across multiple applications. However, deploying LLMs on edge devices poses several challenges with respect to memory, energy, and compute costs, limiting their widespread use in devices such as mobile phones. A promising solution is to reduce the number of bits used to represent weights and activations. While existing works have found partial success at quantizing LLMs to lower bitwidths, e.g. 4-bit weights, quantizing activations beyond 16 bits often leads to large computational overheads due to poor on-device quantization support, or a considerable accuracy drop. Yet, 8-bit activations are very attractive for on-device deployment as they would enable LLMs to fully exploit mobile-friendly hardware, e.g. Neural Processing Units (NPUs). In this work, we make a first attempt to facilitate the on-device deployment of LLMs using integer-only quantization. We first investigate the limitations of existing quantization methods for on-device deployment, with a special focus on activation quantization. We then address these limitations by introducing a simple post-training quantization method, named MobileQuant, that extends previous weight equivalent transformation works by jointly optimizing the weight transformation and activation range parameters in an end-to-end manner. MobileQuant demonstrates superior capabilities over existing methods by 1) achieving near-lossless quantization on a wide range of LLM benchmarks, 2) reducing latency and energy consumption by 20\%-50\% compared to current on-device quantization strategies, 3) requiring limited compute budget, 4) being compatible with mobile-friendly compute units, e.g. NPU.

[Arxiv](https://arxiv.org/abs/2408.13933)