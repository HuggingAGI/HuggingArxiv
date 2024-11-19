# Bi-Mamba：致力于实现精确的 1 位状态空间模型

发布时间：2024年11月18日

`LLM应用` `语言模型` `硬件设计`

> Bi-Mamba: Towards Accurate 1-Bit State Space Models

# 摘要

> 曼巴的典型选择性状态空间模型（SSM）化解了 Transformer 的一些局限，像随序列长度递增的二次计算复杂度，还有因键值缓存造成的显著推理时内存需求。但曼巴模型规模的持续扩大，依旧给训练和部署带来难题，且因能耗巨大引发环境忧虑。在此项工作中，我们推出了双曼巴，这是一种可扩展且强大的 1 位曼巴架构，专为涵盖 780M、1.3B 和 2.7B 等多种规模的更高效大型语言模型打造。双曼巴模型在与常规 LLM 相关的数据量上从零开始训练，采用自回归蒸馏损失。语言建模的大量实验结果显示，双曼巴的性能可与全精度的同类模型（如 FP16 或 BF16）媲美，且比训练后二值化（PTB）的曼巴基线精度更高，同时相比原始曼巴模型，大幅降低了内存占用和能耗。我们的研究开创了低比特表示下新的线性计算复杂度 LLM 框架，为未来针对高效 1 位曼巴的 LLM 定制专用硬件的设计铺平了道路。

> The typical selective state-space model (SSM) of Mamba addresses several limitations of Transformers, such as quadratic computational complexity with sequence length and significant inference-time memory requirements due to the key-value cache. However, the growing size of Mamba models continues to pose training and deployment challenges and raises environmental concerns due to considerable energy consumption. In this work, we introduce Bi-Mamba, a scalable and powerful 1-bit Mamba architecture designed for more efficient large language models with multiple sizes across 780M, 1.3B, and 2.7B. Bi-Mamba models are trained from scratch on data volume as regular LLM pertaining using an autoregressive distillation loss. Extensive experimental results on language modeling demonstrate that Bi-Mamba achieves performance comparable to its full-precision counterparts (e.g., FP16 or BF16) and much better accuracy than post-training-binarization (PTB) Mamba baselines, while significantly reducing memory footprint and energy consumption compared to the original Mamba model. Our study pioneers a new linear computational complexity LLM framework under low-bit representation and facilitates the future design of specialized hardware tailored for efficient 1-bit Mamba-based LLMs.

[Arxiv](https://arxiv.org/abs/2411.11843)