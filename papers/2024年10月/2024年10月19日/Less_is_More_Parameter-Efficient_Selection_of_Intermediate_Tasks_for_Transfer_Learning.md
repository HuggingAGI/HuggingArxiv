# 少即是多：精简中间任务，优化迁移学习

发布时间：2024年10月19日

`LLM应用` `机器学习`

> Less is More: Parameter-Efficient Selection of Intermediate Tasks for Transfer Learning

# 摘要

> 中间任务迁移学习能大幅提升模型性能。比如，情感检测数据少时，先在情感分类数据集上微调语言模型，效果会显著提升。但该选哪个任务迁移呢？传统方法在大数据源下不实用，因需遍历所有源模型。我们用嵌入空间映射（ESM）解决了这问题，ESM 是轻量神经网络，能模拟微调效果。我们研究了 12k 对源-目标任务，发现 ESM 使执行时间和空间分别减少 10 倍和 278 倍，选择性能依旧出色（平均 regret@5 2.95）。

> Intermediate task transfer learning can greatly improve model performance. If, for example, one has little training data for emotion detection, first fine-tuning a language model on a sentiment classification dataset may improve performance strongly. But which task to choose for transfer learning? Prior methods producing useful task rankings are infeasible for large source pools, as they require forward passes through all source language models. We overcome this by introducing Embedding Space Maps (ESMs), light-weight neural networks that approximate the effect of fine-tuning a language model. We conduct the largest study on NLP task transferability and task selection with 12k source-target pairs. We find that applying ESMs on a prior method reduces execution time and disk space usage by factors of 10 and 278, respectively, while retaining high selection performance (avg. regret@5 score of 2.95).

[Arxiv](https://arxiv.org/abs/2410.15148)