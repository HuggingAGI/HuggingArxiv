# BertaQA：探秘语言模型对本土文化的认知深度。

发布时间：2024年06月11日

`LLM应用

这篇论文介绍了BertaQA数据集，这是一个双语（英语和巴斯克语）的多项选择题知识问答数据集，专门设计来评估大型语言模型（LLMs）在处理特定文化主题（如巴斯克文化）的能力。论文通过实验展示了通过在巴斯克语上的持续预训练，模型在处理巴斯克文化相关问题上的性能得到了显著提升。这一发现不仅展示了从低资源语言到高资源语言的知识转移的可能性，还揭示了语言与知识之间的复杂关系。此外，论文还强调了在评估LLMs时，需要考虑到不同文化和语言背景下的表现差异。因此，这篇论文属于LLM应用类别，因为它专注于实际应用中的数据集开发和模型性能评估。` `文化研究`

> BertaQA: How Much Do Language Models Know About Local Culture?

# 摘要

> 大型语言模型（LLMs）虽拥有丰富的世界知识，但评估多聚焦于全球或英语主题，对于网络曝光度较低的其他文化主题表现如何，尚不明确。为此，我们推出了BertaQA，一个英巴双语的多项选择题知识问答数据集，内含聚焦巴斯克文化的本地子集及涵盖广泛兴趣的全球子集。研究发现，即便在全球话题上表现卓越，最先进的LLMs在本地文化知识上仍显吃力。然而，通过在巴斯克语上的持续预训练，模型在巴斯克文化上的表现显著提升，即便使用英语查询亦然。这是首次明确展示从低资源语言到高资源语言的知识转移。我们的分析揭示了语言与知识间的复杂关系，并指出在重新评估本地主题时，某些先前结论未必成立。数据集及评估代码已开放，详情请访问https://github.com/juletx/BertaQA。

> Large Language Models (LLMs) exhibit extensive knowledge about the world, but most evaluations have been limited to global or anglocentric subjects. This raises the question of how well these models perform on topics relevant to other cultures, whose presence on the web is not that prominent. To address this gap, we introduce BertaQA, a multiple-choice trivia dataset that is parallel in English and Basque. The dataset consists of a local subset with questions pertinent to the Basque culture, and a global subset with questions of broader interest. We find that state-of-the-art LLMs struggle with local cultural knowledge, even as they excel on global topics. However, we show that continued pre-training in Basque significantly improves the models' performance on Basque culture, even when queried in English. To our knowledge, this is the first solid evidence of knowledge transfer from a low-resource to a high-resource language. Our analysis sheds light on the complex interplay between language and knowledge, and reveals that some prior findings do not fully hold when reassessed on local topics. Our dataset and evaluation code are available under open licenses at https://github.com/juletx/BertaQA.

[Arxiv](https://arxiv.org/abs/2406.07302)