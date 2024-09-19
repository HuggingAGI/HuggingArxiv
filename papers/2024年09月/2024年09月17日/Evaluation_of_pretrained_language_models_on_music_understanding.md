# 预训练语言模型在音乐理解领域的评估

发布时间：2024年09月17日

`LLM应用` `人工智能`

> Evaluation of pretrained language models on music understanding

# 摘要

> 音乐-文本多模态系统为音乐信息研究（MIR）应用带来了创新，如音频与文本的互转、基于文本的歌曲生成和音乐字幕。然而，对大型语言模型（LLM）音乐知识的评估却鲜有研究。本文揭示了LLM在音乐领域的三大问题：提示敏感、否定建模困难（如“无吉他摇滚”）以及对特定词汇的敏感性。我们通过三元组准确性量化这些问题，评估模型在层次本体中处理标签相似性的能力。利用Audioset本体，我们生成了用于流派和乐器子树的三元组，并评估了六个通用Transformer模型的音乐知识。尽管准确性较高，但所有模型均存在不一致性，表明现成的LLM在应用于音乐前需进行调整。

> Music-text multimodal systems have enabled new approaches to Music Information Research (MIR) applications such as audio-to-text and text-to-audio retrieval, text-based song generation, and music captioning. Despite the reported success, little effort has been put into evaluating the musical knowledge of Large Language Models (LLM). In this paper, we demonstrate that LLMs suffer from 1) prompt sensitivity, 2) inability to model negation (e.g. 'rock song without guitar'), and 3) sensitivity towards the presence of specific words. We quantified these properties as a triplet-based accuracy, evaluating the ability to model the relative similarity of labels in a hierarchical ontology. We leveraged the Audioset ontology to generate triplets consisting of an anchor, a positive (relevant) label, and a negative (less relevant) label for the genre and instruments sub-tree. We evaluated the triplet-based musical knowledge for six general-purpose Transformer-based models. The triplets obtained through this methodology required filtering, as some were difficult to judge and therefore relatively uninformative for evaluation purposes. Despite the relatively high accuracy reported, inconsistencies are evident in all six models, suggesting that off-the-shelf LLMs need adaptation to music before use.

[Arxiv](https://arxiv.org/abs/2409.11449)