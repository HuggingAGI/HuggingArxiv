# MoDeGPT：通过模块化分解实现大型语言模型的高效压缩

发布时间：2024年08月18日

`LLM理论` `人工智能` `计算机硬件`

> MoDeGPT: Modular Decomposition for Large Language Model Compression

# 摘要

> 大型语言模型（LLM）以其卓越的性能在人工智能领域独树一帜，但高昂的计算需求限制了其在资源有限设备上的应用。近期，基于低秩矩阵的压缩技术虽有进展，却常伴随机密度的降低或显著增加的参数与推理延迟。为此，我们提出了MoDeGPT，一种创新的结构化压缩框架，无需繁琐的恢复微调，即可有效克服上述难题。MoDeGPT通过将Transformer模块细分为矩阵对组成的单元，并重构模块级输出以缩减隐藏维度，实现了高效压缩。该框架融合了Nyström近似、CR分解和SVD三种经典矩阵分解算法，并将其应用于重新定义的Transformer模块中。实验结果显示，MoDeGPT在不依赖反向传播的情况下，性能与依赖梯度信息的压缩方法相当甚至更优，且在压缩13B模型时计算成本节省高达98%。在Llama-2/3和OPT模型上，MoDeGPT在压缩率达25-30%时，仍能保持90-95%的零-shot性能，且压缩过程仅需单个GPU数小时即可完成，推理吞吐量提升至多46%。

> Large Language Models (LLMs) have reshaped the landscape of artificial intelligence by demonstrating exceptional performance across various tasks. However, substantial computational requirements make their deployment challenging on devices with limited resources. Recently, compression methods using low-rank matrix techniques have shown promise, yet these often lead to degraded accuracy or introduce significant overhead in parameters and inference latency. This paper introduces \textbf{Mo}dular \textbf{De}composition (MoDeGPT), a novel structured compression framework that does not need recovery fine-tuning while resolving the above drawbacks. MoDeGPT partitions the Transformer block into modules comprised of matrix pairs and reduces the hidden dimensions via reconstructing the module-level outputs. MoDeGPT is developed based on a theoretical framework that utilizes three well-established matrix decomposition algorithms -- Nyström approximation, CR decomposition, and SVD -- and applies them to our redefined transformer modules. Our comprehensive experiments show MoDeGPT, without backward propagation, matches or surpasses previous structured compression methods that rely on gradient information, and saves 98% of compute costs on compressing a 13B model. On \textsc{Llama}-2/3 and OPT models, MoDeGPT maintains 90-95% zero-shot performance with 25-30% compression rates. Moreover, the compression can be done on a single GPU within a few hours and increases the inference throughput by up to 46%.

[Arxiv](https://arxiv.org/abs/2408.09632)