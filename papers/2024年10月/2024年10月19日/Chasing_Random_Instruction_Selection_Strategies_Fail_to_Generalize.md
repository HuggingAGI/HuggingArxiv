# 随机追逐：指令选择策略未能实现泛化

发布时间：2024年10月19日

`LLM理论` `人工智能` `数据科学`

> Chasing Random: Instruction Selection Strategies Fail to Generalize

# 摘要

> 已有研究表明，语言模型只需少量高质量指令即可调整以遵循用户指令，从而推动了从大型嘈杂数据集中筛选出高效子集的方法发展。然而，这些方法的泛化能力因缺乏统一实验验证而未被充分证实。我们在此分析了不同数据集、预算和基准下的选择策略，发现其泛化能力不佳，常无法超越随机基线。此外，我们还探讨了数据选择的成本效益，发现其成本常高于全数据集微调，且增益微乎其微，有时甚至为零。

> Prior work has shown that language models can be tuned to follow user instructions using only a small set of high-quality instructions. This has accelerated the development of methods that filter a large, noisy instruction-tuning datasets down to high-quality subset which works just as well. However, typically, the performance of these methods is not demonstrated across a uniform experimental setup and thus their generalization capabilities are not well established. In this work, we analyze popular selection strategies across different source datasets, selection budgets and evaluation benchmarks: Our results indicate that selection strategies generalize poorly, often failing to consistently outperform even random baselines. We also analyze the cost-performance trade-offs of using data selection. Our findings reveal that data selection can often exceed the cost of fine-tuning on the full dataset, yielding only marginal and sometimes no gains compared to tuning on the full dataset or a random subset.

[Arxiv](https://arxiv.org/abs/2410.15225)