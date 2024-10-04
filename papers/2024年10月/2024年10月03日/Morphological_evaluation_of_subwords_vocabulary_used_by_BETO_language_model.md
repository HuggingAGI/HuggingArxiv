# BETO 语言模型的子词词汇形态学评估

发布时间：2024年10月03日

`LLM理论` `机器学习`

> Morphological evaluation of subwords vocabulary used by BETO language model

# 摘要

> 大型语言模型的子词分词算法高效且无需人工干预即可构建词汇。然而，这些子词与真实词素的对齐问题可能影响模型性能。我们提出了一种评估词汇形态质量的方法，发现 BPE、Wordpiece 和 Unigram 生成的词汇形态质量普遍较低。本文将此方法应用于 BETO 分词器，发现其词汇形态质量同样较低，且扩大训练语料库并不能改善这一问题。此外，评估还揭示了 BETO 分词器使用的 Wordpiece 算法与作者声明的不一致。

> Subword tokenization algorithms used by Large Language Models are significantly more efficient and can independently build the necessary vocabulary of words and subwords without human intervention. However, those subwords do not always align with real morphemes, potentially impacting the models' performance, though it remains uncertain when this might occur. In previous research, we proposed a method to assess the morphological quality of vocabularies, focusing on the overlap between these vocabularies and the morphemes of a given language. Our evaluation method was built on three quality measures, relevance, cohesion, and morphological accuracy, and a procedure for their assessment. By applying this method to vocabularies created by three subword tokenization algorithms, BPE, Wordpiece, and Unigram, we concluded that these vocabularies generally exhibit very low morphological quality. In this article, we apply this evaluation to the tokenizer of BETO, a BERT language model trained on large Spanish corpora. This evaluation, along with our previous results, helped us conclude that its vocabulary has a low morphological quality, and we also found that training the tokenizer in a larger corpus does not improve the morphological quality of the generated vocabulary. Additionally, this evaluation helps clarify the algorithm used by the tokenizer, that is, Wordpiece, given the inconsistencies between the authors' claims and the model's configuration.

[Arxiv](https://arxiv.org/abs/2410.02283)