# 大型语言模型是否能媲美语言学家的编码能力？本研究以低资源语音定律归纳为例，深入探讨这一问题。

发布时间：2024年06月18日

`LLM应用

这篇论文探讨了如何利用大型语言模型（LLMs）的能力来辅助历史语言学家在音变规律归纳（SLI）领域的工作。通过生成Python音变规律程序，该研究提出了一种语言无关的解决方案，并评估了这种方法在不同LLMs上的效果。此外，还提出了生成额外语言无关合成数据的方法，以优化LLMs进行SLI。虽然这种方法在某些方面可能不如现有的自动化SLI方法，但它能够弥补现有方法的一些弱点。因此，这篇论文属于LLM应用分类，因为它展示了LLMs在特定应用领域（即语言学研究）的实际应用和改进。` `语言学` `计算语言学`

> Can Large Language Models Code Like a Linguist?: A Case Study in Low Resource Sound Law Induction

# 摘要

> 历史语言学家通过观察原始语言和后代语言的词汇对，构建程序将原始词汇转换为后代词汇，这些程序基于一系列有序的音变规律。尽管编写这些程序既容易出错又耗时，但计算方法已成功辅助了这一过程。然而，音变规律归纳（SLI）领域仍较少被触及。本文将SLI视为通过示例编程，提出了一种利用LLMs编程能力的语言无关解决方案，通过生成Python音变规律程序来实现。我们评估了该方法在不同LLMs上的效果，并提出了生成额外语言无关合成数据的方法，以优化LLMs进行SLI。与现有自动化SLI方法相比，我们的方法虽有不足，但能弥补其某些弱点。

> Historical linguists have long written a kind of incompletely formalized ''program'' that converts reconstructed words in an ancestor language into words in one of its attested descendants that consist of a series of ordered string rewrite functions (called sound laws). They do this by observing pairs of words in the reconstructed language (protoforms) and the descendent language (reflexes) and constructing a program that transforms protoforms into reflexes. However, writing these programs is error-prone and time-consuming. Prior work has successfully scaffolded this process computationally, but fewer researchers have tackled Sound Law Induction (SLI), which we approach in this paper by casting it as Programming by Examples. We propose a language-agnostic solution that utilizes the programming ability of Large Language Models (LLMs) by generating Python sound law programs from sound change examples. We evaluate the effectiveness of our approach for various LLMs, propose effective methods to generate additional language-agnostic synthetic data to fine-tune LLMs for SLI, and compare our method with existing automated SLI methods showing that while LLMs lag behind them they can complement some of their weaknesses.

[Arxiv](https://arxiv.org/abs/2406.12725)