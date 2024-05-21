# 利用数据压缩精妙选取上下文示例

发布时间：2024年05月19日

`LLM理论

理由：这篇论文探讨了在大规模语言模型中如何优化上下文示例的选择，提出了一种新颖的数据压缩方法，并对其效果进行了实验验证。这涉及到语言模型内部的工作机制和优化策略，属于对LLM理论层面的研究。因此，将其归类为LLM理论。` `机器学习`

> Effective In-Context Example Selection through Data Compression

# 摘要

> 在大规模语言模型中，上下文学习已被广泛证实有效。但关于如何选择合适的上下文示例，这一关键步骤的机制和策略，目前研究尚不充分。本文提出了一种新颖的数据压缩方法，用于优化上下文示例的选择。通过两阶段策略，我们能精准挑选相关示例，并确保这些示例充分反映训练数据的关键信息。实验结果显示，在四个语言模型上，我们的方法在五个真实数据集上的表现平均提升了5.90%。

> In-context learning has been extensively validated in large language models. However, the mechanism and selection strategy for in-context example selection, which is a crucial ingredient in this approach, lacks systematic and in-depth research. In this paper, we propose a data compression approach to the selection of in-context examples. We introduce a two-stage method that can effectively choose relevant examples and retain sufficient information about the training dataset within the in-context examples. Our method shows a significant improvement of an average of 5.90% across five different real-world datasets using four language models.

[Arxiv](https://arxiv.org/abs/2405.11465)