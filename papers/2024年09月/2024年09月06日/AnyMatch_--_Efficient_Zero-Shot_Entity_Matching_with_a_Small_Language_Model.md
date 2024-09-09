# AnyMatch -- 利用小型语言模型实现高效零-shot 实体匹配

发布时间：2024年09月06日

`LLM应用` `数据集成` `人工智能`

> AnyMatch -- Efficient Zero-Shot Entity Matching with a Small Language Model

# 摘要

> 实体匹配 (EM) 旨在确定两个记录是否指向同一现实实体，这在数据集成中至关重要，如产品目录或地址数据库。许多 EM 方法依赖标注示例，限制了其应用。我们专注于零-shot 实体匹配，即在没有标注示例的情况下进行匹配。尽管大型语言模型 (LLM) 在零-shot EM 中表现出色，但其低吞吐量和高成本限制了其应用。  我们通过 AnyMatch，一个在迁移学习中微调的小型语言模型，重新审视零-shot EM。我们提出多种创新数据选择技术，如通过 AutoML 过滤器选择难匹配对，生成额外属性级示例，以及控制标签不平衡。  在九个基准数据集上与十三个基线对比，AnyMatch 虽参数少，但预测质量优异：总体 F1 分数第二高，优于其他大型模型方法。此外，AnyMatch 成本优势显著：与使用 GPT-4 的 MatchGPT 相比，预测质量仅差 4.4%，但参数少四个数量级，推理成本降低 3,899 倍。

> Entity matching (EM) is the problem of determining whether two records refer to same real-world entity, which is crucial in data integration, e.g., for product catalogs or address databases. A major drawback of many EM approaches is their dependence on labelled examples. We thus focus on the challenging setting of zero-shot entity matching where no labelled examples are available for an unseen target dataset. Recently, large language models (LLMs) have shown promising results for zero-shot EM, but their low throughput and high deployment cost limit their applicability and scalability.
  We revisit the zero-shot EM problem with AnyMatch, a small language model fine-tuned in a transfer learning setup. We propose several novel data selection techniques to generate fine-tuning data for our model, e.g., by selecting difficult pairs to match via an AutoML filter, by generating additional attribute-level examples, and by controlling label imbalance in the data.
  We conduct an extensive evaluation of the prediction quality and deployment cost of our model, in a comparison to thirteen baselines on nine benchmark datasets. We find that AnyMatch provides competitive prediction quality despite its small parameter size: it achieves the second-highest F1 score overall, and outperforms several other approaches that employ models with hundreds of billions of parameters. Furthermore, our approach exhibits major cost benefits: the average prediction quality of AnyMatch is within 4.4% of the state-of-the-art method MatchGPT with the proprietary trillion-parameter model GPT-4, yet AnyMatch requires four orders of magnitude less parameters and incurs a 3,899 times lower inference cost (in dollars per 1,000 tokens).

[Arxiv](https://arxiv.org/abs/2409.04073)