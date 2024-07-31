# JaColBERTv2.5 通过优化多向量检索器，在资源有限的环境下打造出顶尖的日本语检索工具。

发布时间：2024年07月30日

`LLM应用` `信息技术` `语言处理`

> JaColBERTv2.5: Optimising Multi-Vector Retrievers to Create State-of-the-Art Japanese Retrievers with Constrained Resources

# 摘要

> 在高资源语言中，神经信息检索技术取得了飞速进展，然而在数据稀缺的低资源语言如日语中，发展却步履维艰。尽管多语言模型在日语检索领域占据主导地位，但其计算效率低下且难以捕捉语言细微差异。近期，多向量单语言模型如JaColBERT虽有所突破，但在大规模评估中仍显逊色。本研究聚焦于低资源环境下多向量检索器的训练优化，特别是日语领域。我们全面评估并优化了JaColBERT及多向量模型的关键训练与推理环节，并创新性地引入了检查点合并技术，有效融合了微调与原始模型的泛化优势。基于此，我们推出了JaColBERTv2.5模型，该模型以1.1亿参数在4块A100 GPU上仅用15小时训练，便在各项基准测试中以0.754的平均分大幅领先，刷新了0.720的历史最佳纪录。为推动后续研究，我们公开了所有相关模型、检查点及数据资源。

> Neural Information Retrieval has advanced rapidly in high-resource languages, but progress in lower-resource ones such as Japanese has been hindered by data scarcity, among other challenges. Consequently, multilingual models have dominated Japanese retrieval, despite their computational inefficiencies and inability to capture linguistic nuances. While recent multi-vector monolingual models like JaColBERT have narrowed this gap, they still lag behind multilingual methods in large-scale evaluations. This work addresses the suboptimal training methods of multi-vector retrievers in lower-resource settings, focusing on Japanese. We systematically evaluate and improve key aspects of the inference and training settings of JaColBERT, and more broadly, multi-vector models. We further enhance performance through a novel checkpoint merging step, showcasing it to be an effective way of combining the benefits of fine-tuning with the generalization capabilities of the original checkpoint. Building on our analysis, we introduce a novel training recipe, resulting in the JaColBERTv2.5 model. JaColBERTv2.5, with only 110 million parameters and trained in under 15 hours on 4 A100 GPUs, significantly outperforms all existing methods across all common benchmarks, reaching an average score of 0.754, significantly above the previous best of 0.720. To support future research, we make our final models, intermediate checkpoints and all data used publicly available.

[Arxiv](https://arxiv.org/abs/2407.20750)