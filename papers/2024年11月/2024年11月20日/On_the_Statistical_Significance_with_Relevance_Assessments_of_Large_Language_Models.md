# 有关大型语言模型相关性评估的统计意义

发布时间：2024年11月20日

`LLM应用` `信息检索` `语言模型`

> On the Statistical Significance with Relevance Assessments of Large Language Models

# 摘要

> 测试集合是信息检索（IR）研究的重要组成部分。它们能让研究人员以快捷、简便且可重复的方式评估和对比排序算法。不过，构建这些数据集得在人工标注和物流方面下大功夫，而且少量的人工相关性判断可能会给比较带来偏差。近来的研究探索利用大型语言模型（LLMs）标注文档相关性，以构建新的检索测试集合。跟人工判断相比，其强大的文本理解能力和低成本，使之成为收集相关性判断的诱人工具。结果显示，在排名相关性方面，LLM 生成的标签前景可观，但在统计显著性方面的影响未提及。在这项工作中，我们探究 LLM 生成的判断怎样保留与人类判断相同的成对显著性评估。我们的成果表明，LLM 判断能检测出大部分显著差异，同时保持可接受的假阳性数量。然而，我们也发现，在 LLM 生成的标签下，有些系统的处理方式不同，这意味着用 LLM 判断进行评估或许并非完全公平。我们的工作是 LLM 判断所提供的统计测试结果评估的一次进步。我们期望这能为其他研究人员开发可靠的自动相关性评估模型提供基础。

> Test collections are an integral part of Information Retrieval (IR) research. They allow researchers to evaluate and compare ranking algorithms in a quick, easy and reproducible way. However, constructing these datasets requires great efforts in manual labelling and logistics, and having only few human relevance judgements can introduce biases in the comparison. Recent research has explored the use of Large Language Models (LLMs) for labelling the relevance of documents for building new retrieval test collections. Their strong text-understanding capabilities and low cost compared to human-made judgements makes them an appealing tool for gathering relevance judgements. Results suggest that LLM-generated labels are promising for IR evaluation in terms of ranking correlation, but nothing is said about the implications in terms of statistical significance. In this work, we look at how LLM-generated judgements preserve the same pairwise significance evaluation as human judgements. Our results show that LLM judgements detect most of the significant differences while maintaining acceptable numbers of false positives. However, we also show that some systems are treated differently under LLM-generated labels, suggesting that evaluation with LLM judgements might not be entirely fair. Our work represents a step forward in the evaluation of statistical testing results provided by LLM judgements. We hope that this will serve as a basis for other researchers to develop reliable models for automatic relevance assessments.

[Arxiv](https://arxiv.org/abs/2411.13212)