# ProMoE: 借助主动缓存实现基于快速 MoE 的 LLM 服务

发布时间：2024年10月29日

`LLM应用` `计算机硬件` `边缘计算`

> ProMoE: Fast MoE-based LLM Serving using Proactive Caching

# 摘要

> 大型语言模型的应用前景广阔，但常受边缘设备有限的 GPU 内存容量所限。混合专家（MoE）模型在计算时仅激活部分模型参数，将未用参数卸载至主机内存，从而降低 GPU 内存总需求，有助于缓解这一问题。然而，现有的基于缓存的卸载方案对缓存未命中采取被动处理，严重影响系统性能。本文提出 ProMoE，这是一种创新的主动缓存系统，借助中间模型结果预测后续参数使用情况。通过提前主动获取专家，ProMoE 消除了关键路径上的加载时间，降低了卸载的性能开销。我们的评估显示，与现有卸载方案相比，ProMoE 在预填充和解码阶段分别实现了平均 2.13 倍和 2.84 倍的加速。

> The promising applications of large language models are often constrained by the limited GPU memory capacity available on edge devices. Mixture-of-Experts (MoE) models help mitigate this issue by activating only a subset of the model's parameters during computation, allowing the unused parameters to be offloaded to host memory and reducing overall GPU memory demand. However, existing cache-based offloading solutions handle cache misses reactively and significantly impact system performance. In this paper, we propose ProMoE, a novel proactive caching system that leverages intermediate model results to predict subsequent parameter usage. By proactively fetching experts in advance, ProMoE removes the loading time from the critical path and diminishes the performance overhead of offloading. Our evaluations demonstrate that ProMoE achieves an average speedup of 2.13x and 2.84x in the prefill and decode stages respectively, compared to existing offloading solutions.

[Arxiv](https://arxiv.org/abs/2410.22134)