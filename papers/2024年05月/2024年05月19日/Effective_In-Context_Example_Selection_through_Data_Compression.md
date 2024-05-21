# 利用数据压缩精妙筛选上下文示例

发布时间：2024年05月19日

`LLM理论

理由：这篇论文关注的是大型语言模型（LLM）中的情境学习机制和策略，特别是提出了一种新的数据压缩方法来优化情境示例的选择。这种方法涉及对模型内部工作机制的深入理解和改进，因此属于LLM理论研究的范畴。论文中提到的实验结果验证了这种方法的有效性，进一步强化了其在理论研究中的地位。` `机器学习`

> Effective In-Context Example Selection through Data Compression

# 摘要

> 大型语言模型中的情境学习已得到充分验证，但关于如何选择情境示例的关键机制和策略，仍缺乏系统深入的研究。本文提出了一种新颖的数据压缩方法，用于优化情境示例的选择。通过引入两阶段策略，我们能精准挑选相关示例，并确保这些示例充分反映训练数据的关键信息。实验结果显示，该方法在四个语言模型上针对五个真实世界数据集，平均性能提升了5.90%。

> In-context learning has been extensively validated in large language models. However, the mechanism and selection strategy for in-context example selection, which is a crucial ingredient in this approach, lacks systematic and in-depth research. In this paper, we propose a data compression approach to the selection of in-context examples. We introduce a two-stage method that can effectively choose relevant examples and retain sufficient information about the training dataset within the in-context examples. Our method shows a significant improvement of an average of 5.90% across five different real-world datasets using four language models.

[Arxiv](https://arxiv.org/abs/2405.11465)