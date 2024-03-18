# 本研究提出了一种简洁且易于扩展的方法，用于持续预训练大型语言模型，旨在提升模型在不断变化的数据环境中的适应性和性能。

发布时间：2024年03月13日

`LLM应用` `持续学习`

> Simple and Scalable Strategies to Continually Pre-train Large Language Models

> 在面对数十亿标记数据时，LLMs惯常采用预训练后，每逢新数据涌现就得重启训练流程。相比之下，更优的选择是持续预训练模型，能显著节省相较于重新训练所需的计算成本。然而，新数据引入的分布变化往往导致模型在旧数据上的表现下滑，或是对新数据适应不佳。本文揭示，在衡量最终损失及语言模型（LM）评估基准时，只需将学习率（LR）重热、LR重新衰减以及前序数据回放这三项简单且易于扩展的技术结合使用，即可媲美完全基于所有现有数据从零开始重新训练的表现。尤其在405M参数规模的LLM中，针对两个广泛使用的预训练数据集间的弱而真实的分布转移（英语↔英语）以及较强转移场景（英语→德语），且在处理数百亿标记的大数据集时，这一结论依然成立。进一步在更大规模实验中，选取同样弱而真实的分布转移情况，我们发现该持续学习策略对于拥有10B参数的LLM而言，其效果也与重新训练基准持平。这些研究成果证实，通过简洁易行且规模化应用的持续学习策略，LLMs能够有效地与时俱进，在仅消耗较少计算资源的前提下，实现与完全重新训练相当的性能升级。此外，借鉴前人研究成果，我们还提出了一些替代余弦学习率调度方案，以帮助规避LR重热引发的记忆消退问题，并且无需受限于固定的标记预算约束。

> Large language models (LLMs) are routinely pre-trained on billions of tokens, only to start the process over again once new data becomes available. A much more efficient solution is to continually pre-train these models, saving significant compute compared to re-training. However, the distribution shift induced by new data typically results in degraded performance on previous data or poor adaptation to the new data. In this work, we show that a simple and scalable combination of learning rate (LR) re-warming, LR re-decaying, and replay of previous data is sufficient to match the performance of fully re-training from scratch on all available data, as measured by final loss and language model (LM) evaluation benchmarks. Specifically, we show this for a weak but realistic distribution shift between two commonly used LLM pre-training datasets (English$\rightarrow$English) and a stronger distribution shift (English$\rightarrow$German) at the $405$M parameter model scale with large dataset sizes (hundreds of billions of tokens). Selecting the weak but realistic shift for larger-scale experiments, we also find that our continual learning strategies match the re-training baseline for a 10B parameter LLM. Our results demonstrate that LLMs can be successfully updated via simple and scalable continual learning strategies, matching the re-training baseline using only a fraction of the compute. Finally, inspired by previous work, we propose alternatives to the cosine learning rate schedule that help circumvent forgetting induced by LR re-warming and that are not bound to a fixed token budget.

[Arxiv](https://arxiv.org/abs/2403.08763)