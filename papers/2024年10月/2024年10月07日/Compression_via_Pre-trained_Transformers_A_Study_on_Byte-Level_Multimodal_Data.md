# 预训练 Transformer 压缩技术：探索字节级多模态数据的奥秘

发布时间：2024年10月07日

`LLM理论` `数据压缩` `多模态处理`

> Compression via Pre-trained Transformers: A Study on Byte-Level Multimodal Data

# 摘要

> 基础模型虽被视为强大的数据压缩器，但考虑到其庞大的参数数量，其压缩效率实际上不如传统算法。简单地减少参数数量反而可能导致预测质量下降，压缩效果更差。本文通过大规模实验，探讨了预训练模型在压缩比上的潜力。我们在165GB的原始数据（涵盖文本、图像、音频及其组合）上训练模型，并压缩每种模态的1GB分布外数据。结果显示，即使参数数量较少，小型模型也能超越通用压缩算法（如gzip、LZMA2）和特定领域压缩器（如PNG、JPEG 2000、FLAC）。例如，我们在音频数据上实现了0.49的压缩比，优于FLAC的0.54。通过深入的模型和数据集规模分析，我们发现小模型在多模态任务中表现出色，但与大型基础模型相比，向新模态的迁移能力较弱。

> Foundation models have recently been shown to be strong data compressors. However, when accounting for their excessive parameter count, their compression ratios are actually inferior to standard compression algorithms. Moreover, naively reducing the number of parameters may not necessarily help as it leads to worse predictions and thus weaker compression. In this paper, we conduct a large-scale empirical study to investigate whether there is a sweet spot where competitive compression ratios with pre-trained vanilla transformers are possible. To this end, we train families of models on 165GB of raw byte sequences of either text, image, or audio data (and all possible combinations of the three) and then compress 1GB of out-of-distribution (OOD) data from each modality. We find that relatively small models (i.e., millions of parameters) can outperform standard general-purpose compression algorithms (gzip, LZMA2) and even domain-specific compressors (PNG, JPEG 2000, FLAC) - even when factoring in parameter count. We achieve, e.g., the lowest compression ratio of 0.49 on OOD audio data (vs. 0.54 for FLAC). To study the impact of model- and dataset scale, we conduct extensive ablations and hyperparameter sweeps, and we investigate the effect of unimodal versus multimodal training. We find that even small models can be trained to perform well on multiple modalities, but, in contrast to previously reported results with large-scale foundation models, transfer to unseen modalities is generally weak.

[Arxiv](https://arxiv.org/abs/2410.05078)