# 探索一个无需训练集的机器阅读理解语言能力评估基准

发布时间：2024年08月09日

`LLM应用` `机器阅读理解`

> Investigating a Benchmark for Training-set free Evaluation of Linguistic Capabilities in Machine Reading Comprehension

# 摘要

> 传统的 NLP 系统评估依赖于大规模众包数据集，但这种方法存在虚假相关性和缺乏多样性挑战示例的问题。我们提出了一种新的评估框架，该框架在无训练集环境下使用合成挑战集来评估优化模型。实验表明，尽管生成方法简单，合成数据在自然性和词汇多样性方面与传统数据集相当，适用于评估 MRC 模型的语言能力。进一步实验显示，最先进的 MRC 系统能在挑战集上表现良好，但未能完全捕捉评估现象的本质。

> Performance of NLP systems is typically evaluated by collecting a large-scale dataset by means of crowd-sourcing to train a data-driven model and evaluate it on a held-out portion of the data. This approach has been shown to suffer from spurious correlations and the lack of challenging examples that represent the diversity of natural language. Instead, we examine a framework for evaluating optimised models in training-set free setting on synthetically generated challenge sets. We find that despite the simplicity of the generation method, the data can compete with crowd-sourced datasets with regard to naturalness and lexical diversity for the purpose of evaluating the linguistic capabilities of MRC models. We conduct further experiments and show that state-of-the-art language model-based MRC systems can learn to succeed on the challenge set correctly, although, without capturing the general notion of the evaluated phenomenon.

[Arxiv](https://arxiv.org/abs/2408.05023)