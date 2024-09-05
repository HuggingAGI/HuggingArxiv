# 在基于LLM的嵌入模型中，池化与注意力机制的设计何者更为高效？

发布时间：2024年09月04日

`LLM应用` `信息技术`

> Pooling And Attention: What Are Effective Designs For LLm-Based Embedding Models?

# 摘要

> 大型语言模型（LLM）在生成任务上的显著进步催生了许多基于LLM的嵌入模型研究。尽管这些模型通过不同的池化和注意力策略在公共基准上取得了顶尖成绩，但关于有效设计的疑问依然存在。这些模型常在不同数据集上训练，使用不同的LLM基础模型或训练设置，且公共基准评估往往未报告统计显著性，这使得确定哪些设计真正提升性能变得困难。本研究通过使用相同数据和基础模型，但采用不同池化和注意力策略，训练了一系列LLM嵌入模型。结果表明，没有万能方案：双向注意力和额外可训练池化层在文本相似性和信息检索中表现优异，但在聚类和分类任务中并未显著超越简单设计。此外，我们提出了一种新池化策略——多层可训练池化，通过交叉注意力网络转换所有隐藏层输出，而非仅最后一层，该方法在文本相似性和检索任务中显示出统计上的优越性。总体而言，本文揭示了LLM嵌入模型的有效训练策略。

> The significant advancements of Large Language Models (LLMs) in generative tasks have led to a growing body of work exploring LLM-based embedding models. While these models, employing different pooling and attention strategies, have achieved state-of-the-art performance on public embedding benchmarks, questions still arise about what constitutes an effective design for LLM-based embedding models. However, these models are often trained on different datasets, using different LLM base models or training settings. Moreover, evaluations on public embedding benchmarks often fail to report statistical significance, making it difficult to determine which designs truly contribute to final performance. This complicates the process for practitioners seeking optimal training recipes for LLM-based embedding models. In this study, we conduct a large-scale experiment by training a series of LLM-based embedding models using the same training data and base model but differing in their pooling and attention strategies. The results show that there is no one-size-fits-all solution: while bidirectional attention and an additional trainable pooling layer outperform in text similarity and information retrieval tasks, they do not significantly surpass simpler designs like EOS-last token pooling and default causal attention in clustering and classification tasks. Furthermore, we propose a new pooling strategy, Multi-Layers Trainable Pooling, which transforms the outputs of all hidden layers, rather than just the last layer, using a cross-attention network. This method proves to be statistically superior in text similarity and retrieval tasks compared to existing pooling methods. Overall, this paper sheds light on effective training strategies for LLM-based embedding models.

[Arxiv](https://arxiv.org/abs/2409.02727)