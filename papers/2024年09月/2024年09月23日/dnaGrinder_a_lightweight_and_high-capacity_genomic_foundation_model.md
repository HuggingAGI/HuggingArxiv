# dnaGrinder：一款轻巧且高容量的基因组基础模型

发布时间：2024年09月23日

`LLM应用` `生物学` `临床研究`

> dnaGrinder: a lightweight and high-capacity genomic foundation model

# 摘要

> 解读基因组序列中的复杂信息仍是生物学和临床应用的重大挑战。近期，大语言模型研究推动了仅编码器和仅解码器模型的诞生，旨在解析DNA的复杂性。然而，长程依赖性管理、核苷酸变异表示及高计算成本等问题依然存在。当前模型常在性能与规模间权衡。为此，我们推出dnaGrinder，一种高效基因组模型，擅长处理长程依赖，降低成本，性能不减，甚至超越Nucleotide Transformer和DNABERT-2。它支持超长序列，单GPU即可处理140,000+标记，成为生物学和临床研究的高效利器。

> The task of understanding and interpreting the complex information encoded within genomic sequences remains a grand challenge in biological research and clinical applications. In this context, recent advancements in large language model research have led to the development of both encoder-only and decoder-only foundation models designed to decode intricate information in DNA sequences. However, several issues persist, particularly regarding the efficient management of long-range dependencies inherent in genomic sequences, the effective representation of nucleotide variations, and the considerable computational costs associated with large model architectures and extensive pretraining datasets. Current genomic foundation models often face a critical tradeoff: smaller models with mediocre performance versus large models with improved performance. To address these challenges, we introduce dnaGrinder, a unique and efficient genomic foundation model. dnaGrinder excels at managing long-range dependencies within genomic sequences while minimizing computational costs without compromising performance. It achieves results that are not just comparable but often superior to leading DNA models such as Nucleotide Transformer and DNABERT-2. Furthermore, dnaGrinder is designed for easy fine-tuning on workstation-grade GPUs, accommodating input lengths exceeding 17,000 tokens. On a single high-performance GPU, it supports sequences longer than 140,000 tokens, making it a highly efficient and accessible tool for both basic biological research and clinical applications.

[Arxiv](https://arxiv.org/abs/2409.15697)