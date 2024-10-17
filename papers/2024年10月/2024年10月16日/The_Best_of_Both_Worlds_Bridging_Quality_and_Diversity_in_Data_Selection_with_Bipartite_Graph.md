# 双赢之道：利用二分图在数据选择中兼顾质量和多样性

发布时间：2024年10月16日

`LLM理论` `机器学习`

> The Best of Both Worlds: Bridging Quality and Diversity in Data Selection with Bipartite Graph

# 摘要

> 大型语言模型（LLM）在自然语言处理（NLP）任务中的表现，很大程度上取决于监督微调（SFT）所用数据的质量与多样性。然而，现有数据选择方法往往只侧重于质量或多样性，导致模型表现不佳。为此，我们提出了GraphFilter，一种将数据集表示为二分图的新方法，通过连接句子与n-gram，有效捕捉句子间及语言模式的关系，从而提升n-gram的多样性。为平衡质量和多样性，我们设计了一个结合两者指标的优先级函数。GraphFilter通过迭代选择高优先级句子，更新二分图并重新计算优先级，以适应数据环境的变化。实验结果显示，GraphFilter在六个广泛使用的基准测试中，超越了所有九种基线方法，不仅提升了模型性能，还提高了计算效率。我们的分析不仅验证了设计选择的有效性，还强调了指令多样性的重要性，并探讨了质量与多样性在不同子集大小下的关系。GraphFilter为LLM的数据选择策略开辟了新路径，鼓励未来在此领域的深入研究。

> The performance of large language models (LLMs) in natural language processing (NLP) tasks is significantly influenced by the quality and diversity of data used for supervised fine-tuning (SFT). Current data selection methods often focus solely on quality or diversity, leading to underperforming models due to suboptimal training data. In this paper, we introduce GraphFilter, a novel method that represents the dataset as a bipartite graph, linking sentences to their constituent n-grams. This representation effectively captures the relationships between sentences and linguistic patterns, facilitating the selection of sentences that enhance n-gram diversity. To balance quality and diversity during selection, we propose a priority function that combines the quality metric with the diversity metric in a multiplicative manner. GraphFilter iteratively selects high-priority sentences, updates the bipartite graph by removing covered n-grams, and re-calculates priorities to reflect the evolving data landscape. We conduct extensive experiments using three model backbones across six widely used benchmarks. The results demonstrate that GraphFilter outperforms all nine baseline approaches, achieving superior model performance and computational efficiency. Our analyses validate the effectiveness of our design choices, examine the subsets selected by GraphFilter and other methods, highlight the importance of instruction diversity, and explore the role of quality and diversity in relation to subset sizes. GraphFilter establishes a new foundation for effective data selection strategies, encouraging further research in data selection for LLMs.

[Arxiv](https://arxiv.org/abs/2410.12458)