# 探索多模态大型语言模型中的分层分子图表示

发布时间：2024年11月07日

`LLM应用` `生物化学`

> Exploring Hierarchical Molecular Graph Representation in Multimodal LLMs

# 摘要

> 在大型语言模型（LLMs）和多模态模型的里程碑之后，我们看到了将 LLMs 应用于生化任务的热潮。利用图形特征和分子文本表示，LLMs 可以处理各种任务，例如预测化学反应结果和描述分子特性。然而，目前大多数工作都忽略了图形特征的多层次性质。不同特征级别对 LLMs 的影响以及每个级别的重要性仍未得到探索，并且不同的化学任务可能需要不同的特征级别。在这项工作中，我们首先通过融合 GNN 生成的特征标记来研究特征粒度的影响，发现即使将所有标记减少到单个标记也不会显著影响性能。然后，我们探索了各种特征级别对性能的影响，发现 LLM 生成的分子的质量和不同任务的性能都受益于不同的特征级别。我们得出两个关键见解：（1）当前的分子多模态 LLMs（MLLMs）对图形特征缺乏全面的理解，（2）对于分层图形特征，静态处理是不够的。我们的代码很快将公开可用。

> Following the milestones in large language models (LLMs) and multimodal models, we have seen a surge in applying LLMs to biochemical tasks. Leveraging graph features and molecular text representations, LLMs can tackle various tasks, such as predicting chemical reaction outcomes and describing molecular properties. However, most current work overlooks the multi-level nature of graph features. The impact of different feature levels on LLMs and the importance of each level remain unexplored, and it is possible that different chemistry tasks require different feature levels. In this work, we first investigate the effect of feature granularity by fusing GNN-generated feature tokens, discovering that even reducing all tokens to a single token does not significantly impact performance. We then explore the effect of various feature levels on performance, finding that both the quality of LLM-generated molecules and performance on different tasks benefit from different feature levels. We conclude with two key insights: (1) current molecular Multimodal LLMs(MLLMs) lack a comprehensive understanding of graph features, and (2) static processing is not sufficient for hierarchical graph feature. Our code will be publicly available soon.

[Arxiv](https://arxiv.org/abs/2411.04708)