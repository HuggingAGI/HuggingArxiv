# CDQuant：借助贪婪坐标下降法，精确量化大型预训练模型的后训练权重

发布时间：2024年06月25日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）的量化技术，特别是GPTQ算法及其改进版本CDQuant。这些技术旨在通过量化方法压缩模型，以减少计算和存储需求，同时保持模型性能。论文中提到的CDQuant算法通过坐标下降法优化层级重建损失，提高了量化权重质量，并在PaLM2系列模型上进行了测试，显示出优于GPTQ的性能。因此，这篇论文属于LLM理论分类，因为它专注于LLMs的技术改进和理论研究。` `模型压缩`

> CDQuant: Accurate Post-training Weight Quantization of Large Pre-trained Models using Greedy Coordinate Descent

# 摘要

> 大型语言模型（LLMs）近期在各类语言任务中表现出色，但部署这些模型常因高昂的计算和存储需求而受限。量化技术成为解决这一难题的关键，它能在不牺牲性能的前提下压缩模型。GPTQ算法，作为一种高效的后训练量化方法，已在LLMs压缩领域展现出巨大潜力，激发了众多以此为核心的研究。鉴于GPTQ在PTQ领域的重要性，我们开发了CDQuant，这一简单且可扩展的方案在性能上超越了GPTQ。CDQuant通过坐标下降法优化层级重建损失，确保量化权重的高质量。该算法实施简便，且能高效处理包含数千亿参数的模型。在PaLM2系列模型上的广泛测试表明，CDQuant在各种模型规模和量化级别上均优于GPTQ，尤其在PaLM2-Otter的INT2量化中，其困惑度比GPTQ降低了10%。

> Large language models (LLMs) have recently demonstrated remarkable performance across diverse language tasks. But their deployment is often constrained by their substantial computational and storage requirements. Quantization has emerged as a key technique for addressing this challenge, enabling the compression of large models with minimal impact on performance. The recent GPTQ algorithm, a post-training quantization (PTQ) method, has proven highly effective for compressing LLMs, sparking a wave of research that leverages GPTQ as a core component. Recognizing the pivotal role of GPTQ in the PTQ landscape, we introduce CDQuant, a simple and scalable alternative to GPTQ with improved performance. CDQuant uses coordinate descent to minimize the layer-wise reconstruction loss to achieve high-quality quantized weights. Our algorithm is easy to implement and scales efficiently to models with hundreds of billions of parameters. Through extensive evaluation on the PaLM2 model family, we demonstrate that CDQuant consistently outperforms GPTQ across diverse model sizes and quantization levels. In particular, for INT2 quantization of PaLM2-Otter, CDQuant achieves a 10% reduction in perplexity compared to GPTQ.

[Arxiv](https://arxiv.org/abs/2406.17542)