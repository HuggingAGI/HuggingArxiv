# 基于知识的特征选择与工程，应用于基因型数据，借助大型语言模型之力。

发布时间：2024年10月02日

`LLM应用` `生物医学` `遗传学`

> Knowledge-Driven Feature Selection and Engineering for Genotype Data with Large Language Models

# 摘要

> 预测复杂遗传基础的表型，即使基于少量可解释的变体特征，依然充满挑战。传统数据驱动方法虽被广泛应用，但基因型数据的高维度特性使其分析与预测困难重重。受预训练LLMs在处理复杂生物医学概念上的成功启发，我们探索了LLMs在基因型数据特征选择与工程中的潜力，并构建了FREEFORM这一知识驱动框架。FREEFORM结合思维链与集成原则，利用LLMs的内在知识进行特征优化与建模。在遗传祖先与遗传性听力损失两个数据集上的测试表明，FREEFORM在低样本情况下表现尤为出色，超越了多种数据驱动方法。该框架现已开源，可在GitHub上获取：https://github.com/PennShenLab/FREEFORM。

> Predicting phenotypes with complex genetic bases based on a small, interpretable set of variant features remains a challenging task. Conventionally, data-driven approaches are utilized for this task, yet the high dimensional nature of genotype data makes the analysis and prediction difficult. Motivated by the extensive knowledge encoded in pre-trained LLMs and their success in processing complex biomedical concepts, we set to examine the ability of LLMs in feature selection and engineering for tabular genotype data, with a novel knowledge-driven framework. We develop FREEFORM, Free-flow Reasoning and Ensembling for Enhanced Feature Output and Robust Modeling, designed with chain-of-thought and ensembling principles, to select and engineer features with the intrinsic knowledge of LLMs. Evaluated on two distinct genotype-phenotype datasets, genetic ancestry and hereditary hearing loss, we find this framework outperforms several data-driven methods, particularly on low-shot regimes. FREEFORM is available as open-source framework at GitHub: https://github.com/PennShenLab/FREEFORM.

[Arxiv](https://arxiv.org/abs/2410.01795)