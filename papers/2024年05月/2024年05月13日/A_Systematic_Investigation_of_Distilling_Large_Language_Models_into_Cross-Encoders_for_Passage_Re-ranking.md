# 系统探索：将大型语言模型精炼为跨编码器，以优化段落排序策略

发布时间：2024年05月13日

`LLM理论

这篇论文探讨了从大型语言模型（LLM）中蒸馏出的交叉编码器在重新排序任务上的性能，并推出了一个新的数据集Rank-DistiLLM，以研究微调策略是否能提升蒸馏模型的性能。这属于对LLM理论的深入研究，特别是关于模型蒸馏和微调策略的探索，因此归类为LLM理论。` `数据集` `信息检索`

> A Systematic Investigation of Distilling Large Language Models into Cross-Encoders for Passage Re-ranking

# 摘要

> 我们发现，从 LLM 中蒸馏出的交叉编码器在重新排序任务上比传统微调方法更胜一筹，但仍未触及 LLM 的巅峰。为此，我们推出了 Rank-DistiLLM 数据集，旨在探索微调策略如硬负采样、深度采样和列表损失函数，能否助力蒸馏模型更接近 LLM 的卓越性能。这一创新数据集将培育出既高效又强大的交叉编码器，代码与数据已公开于 GitHub。

> Cross-encoders distilled from large language models are more effective re-rankers than cross-encoders fine-tuned using manually labeled data. However, the distilled models do not reach the language model's effectiveness. We construct and release a new distillation dataset, named Rank-DistiLLM, to investigate whether insights from fine-tuning cross-encoders on manually labeled data -- hard-negative sampling, deep sampling, and listwise loss functions -- are transferable to large language model ranker distillation. Our dataset can be used to train cross-encoders that reach the effectiveness of large language models while being orders of magnitude more efficient. Code and data is available at: https://github.com/webis-de/msmarco-llm-distillation

[Arxiv](https://arxiv.org/abs/2405.07920)