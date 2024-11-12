# 通过量化优化大型语言模型：PTQ 和 QAT 技术的比较分析

发布时间：2024年11月09日

`LLM理论` `计算机硬件` `边缘计算`

> Optimizing Large Language Models through Quantization: A Comparative Analysis of PTQ and QAT Techniques

# 摘要

> 本文对用于优化大型语言模型（LLM）的量化技术进行了全面分析，特别关注了训练后量化（PTQ）和量化感知训练（QAT）。通过对从 1000 万到 10 亿参数的模型进行实证评估，我们证明，利用我们提出的缩放因子γ，量化可以使模型大小减少多达 68％，同时将性能保持在全精度基线的 6％以内。我们的实验表明，INT8 量化使计算成本和功耗降低 40％，而 INT4 量化进一步将这些指标提高 60％。我们引入了一个用于混合精度量化的新理论框架，根据层敏感度和权重方差推导出最优位分配策略。在边缘设备上的硬件效率评估表明，与全精度模型相比，我们的量化方法使 INT8 的吞吐量提高多达 2.4 倍，INT4 提高多达 3 倍，功耗降低 60％。

> This paper presents a comprehensive analysis of quantization techniques for optimizing Large Language Models (LLMs), specifically focusing on Post-Training Quantization (PTQ) and Quantization-Aware Training (QAT). Through empirical evaluation across models ranging from 10M to 1B parameters, we demonstrate that quantization can achieve up to 68% reduction in model size while maintaining performance within 6% of full-precision baselines when utilizing our proposed scaling factor γ. Our experiments show that INT8 quantization delivers a 40% reduction in computational cost and power consumption, while INT4 quantization further improves these metrics by 60%. We introduce a novel theoretical framework for mixed-precision quantization, deriving optimal bit allocation strategies based on layer sensitivity and weight variance. Hardware efficiency evaluations on edge devices reveal that our quantization approach enables up to 2.4x throughput improvement for INT8 and 3x for INT4, with 60% power reduction compared to full-precision models.

[Arxiv](https://arxiv.org/abs/2411.06084)