# 借助令牌翻译来适配语言模型

发布时间：2024年11月01日

`LLM应用` `语言模型` `蛋白质序列`

> Adapting Language Models via Token Translation

# 摘要

> 现代大型语言模型借助固定的分词器，能有效压缩源自源域的文本。但将同一分词器用于新的目标域时，往往会致使压缩效果差、推理成本高以及语义对齐度降低。为弥补这一不足，我们推出了稀疏Sinkhorn令牌转换（S2T2）。S2T2为目标域训练专属分词器，并学会在目标与源令牌间转换，从而更有效地复用预训练的下一个源令牌预测器。在针对微调的英语语言模型所做的实验里，S2T2提升了域外蛋白质序列的困惑度和压缩效果，比用源或目标分词器直接微调的效果更优。另外，我们发现为较小、成本较低的模型所学的令牌转换，能够直接迁移到更大、更强的模型中，以更低成本收获S2T2的益处。

> Modern large language models use a fixed tokenizer to effectively compress text drawn from a source domain. However, applying the same tokenizer to a new target domain often leads to inferior compression, more costly inference, and reduced semantic alignment. To address this deficiency, we introduce Sparse Sinkhorn Token Translation (S2T2). S2T2 trains a tailored tokenizer for the target domain and learns to translate between target and source tokens, enabling more effective reuse of the pre-trained next-source-token predictor. In our experiments with finetuned English language models, S2T2 improves both the perplexity and the compression of out-of-domain protein sequences, outperforming direct finetuning with either the source or target tokenizer. In addition, we find that token translations learned for smaller, less expensive models can be directly transferred to larger, more powerful models to reap the benefits of S2T2 at lower cost.

[Arxiv](https://arxiv.org/abs/2411.00593)