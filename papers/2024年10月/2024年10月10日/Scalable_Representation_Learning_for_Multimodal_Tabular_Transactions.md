# 多模态表格交易的可扩展表示学习

发布时间：2024年10月10日

`LLM应用` `数据分析`

> Scalable Representation Learning for Multimodal Tabular Transactions

# 摘要

> 大型语言模型（LLM）擅长处理非结构化文本，但面对表格数据时，往往难以捕捉内在关系和关键模式。尽管现有的表格表示学习方法有所改进，但在处理稀疏高基数字段、精确数值推理和复杂表格时仍显不足。此外，如何通过语言接口有效利用这些表示进行下游任务，仍是一个难题。本文提出了一种创新且可扩展的解决方案：我们设计了多层分区机制来处理大词汇表，采用自适应量化机制确保数值连续性，并独特处理核心列与元信息列。为提升LLM的指令调整能力，我们开发了参数高效的解码器，通过适配器层融合交易与文本模态，从而挖掘跨任务的丰富知识。实验结果表明，我们的方法在大规模合成支付交易数据集上表现优异。

> Large language models (LLMs) are primarily designed to understand unstructured text. When directly applied to structured formats such as tabular data, they may struggle to discern inherent relationships and overlook critical patterns. While tabular representation learning methods can address some of these limitations, existing efforts still face challenges with sparse high-cardinality fields, precise numerical reasoning, and column-heavy tables. Furthermore, leveraging these learned representations for downstream tasks through a language based interface is not apparent. In this paper, we present an innovative and scalable solution to these challenges. Concretely, our approach introduces a multi-tier partitioning mechanism that utilizes power-law dynamics to handle large vocabularies, an adaptive quantization mechanism to impose priors on numerical continuity, and a distinct treatment of core-columns and meta-information columns. To facilitate instruction tuning on LLMs, we propose a parameter efficient decoder that interleaves transaction and text modalities using a series of adapter layers, thereby exploiting rich cross-task knowledge. We validate the efficacy of our solution on a large-scale dataset of synthetic payments transactions.

[Arxiv](https://arxiv.org/abs/2410.07851)