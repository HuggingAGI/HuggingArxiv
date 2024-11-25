# FuseGPT：生成式预训练 Transformer 的可学习层融合技术

发布时间：2024年11月21日

`LLM应用` `语言模型` `多模态模型`

> FuseGPT: Learnable Layers Fusion of Generative Pre-trained Transformers

# 摘要

> 生成式预训练 Transformer（GPTs）凭借大规模扩展模型参数，在众多领域表现出色。近期研究发现 Transformer 块存在冗余，于是通过对不重要的块进行结构化剪枝来开发压缩方法。但这种简单的删减总会造成不可逆转的性能降低。在本文中，我们提出了 FuseGPT 这一全新方法，用于回收被剪枝的 Transformer 块，以进一步提升模型性能。首先，我们引入了新的重要性检测指标——宏观影响（MI），通过计算每个 Transformer 块移除后的信息损失来检测其长期影响。接着，我们提出了组级层融合，它将不重要块的层中的参数注入到相邻块内的相应层中。融合并非一蹴而就，而是通过轻量级组级微调的迭代参数更新来实现。具体而言，这些注入的参数被冻结，但用可学习的秩分解矩阵加权，以降低微调时的开销。我们的方法不仅在大型语言模型中效果显著，在大型多模态模型中也表现不凡。实验显示，使用适量数据，FuseGPT 在困惑度和零样本任务性能方面均优于以往的研究成果。

> Generative Pre-trained Transformers (GPTs) have demonstrated remarkable performance across diverse domains through the extensive scaling of model parameters. Recent works observe the redundancy across the transformer blocks and develop compression methods by structured pruning of the unimportant blocks. However, such straightforward elimination will always provide irreversible performance degradation. In this paper, we propose FuseGPT, a novel methodology to recycle the pruned transformer blocks to further recover the model performance. Firstly we introduce a new importance detection metric, Macro Influence (MI), to detect the long-term influence of each transformer block by calculating their loss of information after removal. Then we propose group-level layers fusion, which adopts the parameters in layers of the unimportant blocks and injects them into the corresponding layers inside the neighboring blocks. The fusion is not one-off but through iterative parameter updates by lightweight group-level fine-tuning. Specifically, these injected parameters are frozen but weighted with learnable rank decomposition matrices to reduce the overhead during fine-tuning. Our approach not only works well on large language models but also on large multimodal models. The experiments have shown that, by using modest amounts of data, FuseGPT can outperform previous works in both perplexity and zero-shot task performance.

[Arxiv](https://arxiv.org/abs/2411.14507)