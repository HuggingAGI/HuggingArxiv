# 大语言模型中混合量化的缩放法则

发布时间：2024年10月09日

`LLM理论` `人工智能` `硬件设计`

> Scaling Laws for Mixed quantization in Large Language Models

# 摘要

> 大型语言模型 (LLM) 的训练后量化在减少推理计算需求方面表现出色。我们探讨了一个核心问题：在低精度量化中，随着模型规模扩大，如何确保高精度性能？我们引入了量化比率这一关键指标，并通过多维度实验，揭示了两个重要现象：1) 模型越大，通过提高量化比率，性能保持得越好；2) 混合精度量化的粒度越细，量化比率提升空间越大。这些发现为未来 AI 硬件设计和高效算法开发提供了重要启示。

> Post-training quantization of Large Language Models (LLMs) has proven effective in reducing the computational requirements for running inference on these models. In this study, we focus on a straightforward question: When aiming for a specific accuracy or perplexity target for low-precision quantization, how many high-precision numbers or calculations are required to preserve as we scale LLMs to larger sizes? We first introduce a critical metric named the quantization ratio, which compares the number of parameters quantized to low-precision arithmetic against the total parameter count. Through extensive and carefully controlled experiments across different model families, arithmetic types, and quantization granularities (e.g. layer-wise, matmul-wise), we identify two central phenomenons. 1) The larger the models, the better they can preserve performance with an increased quantization ratio, as measured by perplexity in pre-training tasks or accuracy in downstream tasks. 2) The finer the granularity of mixed-precision quantization (e.g., matmul-wise), the more the model can increase the quantization ratio. We believe these observed phenomena offer valuable insights for future AI hardware design and the development of advanced Efficient AI algorithms.

[Arxiv](https://arxiv.org/abs/2410.06722)