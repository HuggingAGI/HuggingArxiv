# DeltaDQ：利用分组丢弃与单独量化技术，实现微调 LLM 的超高 Delta 压缩效果。

发布时间：2024年10月11日

`LLM理论` `人工智能` `云计算`

> DeltaDQ: Ultra-High Delta Compression for Fine-Tuned LLMs via Group-wise Dropout and Separate Quantization

# 摘要

> 大型语言模型通过监督微调在多种任务中表现出色，但任务多样性和实际需求使得部署多个全参数微调模型变得困难。现有方法在压缩增量权重时难以实现超高压缩，无法有效降低部署成本。为此，我们提出了 DeltaDQ 框架，通过分组 Dropout 和单独量化技术，实现增量权重的超高压缩。实验表明，DeltaDQ 在 WizardMath 和 WizardCoder 模型上实现了 16 倍压缩，且精度优于基线。此外，DeltaDQ 还能实现 WizardMath-7B 模型的 128 倍压缩和 WizardMath-70B 模型的 512 倍压缩。

> Large language models achieve exceptional performance on various downstream tasks through supervised fine-tuning. However, the diversity of downstream tasks and practical requirements makes deploying multiple full-parameter fine-tuned models challenging. Current methods that compress the delta weight struggle to achieve ultra-high compression, failing to minimize the deployment overhead. To address the above issue, we propose a novel distribution-driven delta compression framework DeltaDQ, which utilizes Group-wise Dropout and Separate Quantization to achieve ultra-high compression for the delta weight. We have observed that the matrix-computed intermediate results for the delta weight exhibit extremely small variance and min-max range characteristics, referred to as Balanced Intermediate Results. Exploiting this phenomenon, we introduce Group-wise Dropout to perform dropout on the delta weight using an optimal group size. Furthermore, using Separate Quantization, sparse weights are quantized and decomposed to achieve a lower bit. Experimental results show that DeltaDQ achieves 16x compression with improved accuracy compared to baselines for WizardMath and WizardCoder models across different parameter scales. Moreover, DeltaDQ demonstrates the ability for ultra-high compression ratio, achieving 128x compression for the WizardMath-7B model and 512x compression for the WizardMath-70B model.

[Arxiv](https://arxiv.org/abs/2410.08666)