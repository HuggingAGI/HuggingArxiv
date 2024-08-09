# 利用 LLMs 进行迭代简化，为儿童量身定制翻译，考虑其语言习得年龄。

发布时间：2024年08月08日

`LLM应用` `机器翻译`

> Simplifying Translations for Children: Iterative Simplification Considering Age of Acquisition with LLMs

# 摘要

> 近年来，神经机器翻译（NMT）在日常生活中广泛应用，但缺乏根据用户语言水平调整翻译难度的机制。此外，NMT训练数据的偏差导致简单句子的翻译常使用复杂词汇，这对儿童理解构成挑战。为此，我们提出一种方法，通过替换翻译中的高获取年龄（AoA）词汇为更简单词汇，以适应用户水平。我们利用大型语言模型（LLMs），提供源句、翻译及目标替换词的三元组，通过Simple English Wikipedia的回译创建基准数据集。实验结果表明，该方法能有效替换高AoA词汇，且能迭代替换多数高AoA词汇，同时保持高BLEU和COMET评分。

> In recent years, neural machine translation (NMT) has been widely used in everyday life. However, the current NMT lacks a mechanism to adjust the difficulty level of translations to match the user's language level. Additionally, due to the bias in the training data for NMT, translations of simple source sentences are often produced with complex words. In particular, this could pose a problem for children, who may not be able to understand the meaning of the translations correctly. In this study, we propose a method that replaces words with high Age of Acquisitions (AoA) in translations with simpler words to match the translations to the user's level. We achieve this by using large language models (LLMs), providing a triple of a source sentence, a translation, and a target word to be replaced. We create a benchmark dataset using back-translation on Simple English Wikipedia. The experimental results obtained from the dataset show that our method effectively replaces high-AoA words with lower-AoA words and, moreover, can iteratively replace most of the high-AoA words while still maintaining high BLEU and COMET scores.

[Arxiv](https://arxiv.org/abs/2408.04217)