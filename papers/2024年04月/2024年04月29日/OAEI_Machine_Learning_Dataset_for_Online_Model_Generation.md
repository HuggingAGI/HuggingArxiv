# OAEI 为在线模型生成提供了一个机器学习数据集。

发布时间：2024年04月29日

`分类：Agent` `本体对齐` `机器学习`

> OAEI Machine Learning Dataset for Online Model Generation

# 摘要

> 每年，本体对齐评估计划（OAEI）对本体和知识图谱匹配系统进行评估。随着基于机器学习的方法，尤其是大型语言模型的广泛应用，系统开发者通常会根据参考对齐的子集来确定训练和验证数据集，这违反了OAEI的规定，导致无法进行公正的比较。此外，这些模型采用离线训练方式，即训练好的模型被封装进匹配器中，专为特定任务定制。本文提出了一个新的数据集，涵盖了OAEI大多数赛道的训练集、验证集和测试集，从而使得在线模型学习（系统需在无人干预的情况下自动适应输入对齐）成为可能，为基于机器学习（ML）的系统提供了一个公平的比较平台。我们还通过微调流行系统的信任阈值，展示了该数据集的实用价值。

> Ontology and knowledge graph matching systems are evaluated annually by the Ontology Alignment Evaluation Initiative (OAEI). More and more systems use machine learning-based approaches, including large language models. The training and validation datasets are usually determined by the system developer and often a subset of the reference alignments are used. This sampling is against the OAEI rules and makes a fair comparison impossible. Furthermore, those models are trained offline (a trained and optimized model is packaged into the matcher) and therefore the systems are specifically trained for those tasks. In this paper, we introduce a dataset that contains training, validation, and test sets for most of the OAEI tracks. Thus, online model learning (the systems must adapt to the given input alignment without human intervention) is made possible to enable a fair comparison for ML-based systems. We showcase the usefulness of the dataset by fine-tuning the confidence thresholds of popular systems.

[Arxiv](https://arxiv.org/abs/2404.18542)