# 《缩放法则估计的搭便车指南》

发布时间：2024年10月15日

`LLM理论` `机器学习` `数据集`

> A Hitchhiker's Guide to Scaling Law Estimation

# 摘要

> 缩放定律通过外推更简单的模型来预测目标模型的损失，为比较预训练决策提供了一种高效方法。尽管广泛用于语言模型训练，但如何最佳估计和解释缩放定律的研究仍显不足。我们收集并发布了一个包含485个预训练模型损失和下游评估的大规模数据集，用于估计超过1000个缩放定律，并推导出在新模型系列中估计缩放定律的最佳实践。我们发现，拟合训练中间检查点的缩放定律显著提高准确性，且从相似大小的模型中得出的性能估计通常最准确。然而，由于模型种子间的变异性，训练多个小模型有时比单个大模型更有用。此外，尽管不同模型系列的缩放行为各异，但通常相似到足以从相同架构的单个模型中预测目标模型的行为，并结合其他模型系列的缩放参数估计。

> Scaling laws predict the loss of a target machine learning model by extrapolating from easier-to-train models with fewer parameters or smaller training sets. This provides an efficient way for practitioners and researchers alike to compare pretraining decisions involving optimizers, datasets, and model architectures. Despite the widespread use of scaling laws to model the dynamics of language model training, there has been little work on understanding how to best estimate and interpret them. We collect (and release) a large-scale dataset containing losses and downstream evaluations for 485 previously published pretrained models. We use these to estimate more than 1000 scaling laws, then derive a set of best practices for estimating scaling laws in new model families. We find that fitting scaling laws to intermediate checkpoints of training runs (and not just their final losses) substantially improves accuracy, and that -- all else equal -- estimates of performance are generally most accurate when derived from other models of similar sizes. However, because there is a significant degree of variability across model seeds, training multiple small models is sometimes more useful than training a single large one. Moreover, while different model families differ scaling behavior, they are often similar enough that a target model's behavior can be predicted from a single model with the same architecture, along with scaling parameter estimates derived from other model families.

[Arxiv](https://arxiv.org/abs/2410.11840)