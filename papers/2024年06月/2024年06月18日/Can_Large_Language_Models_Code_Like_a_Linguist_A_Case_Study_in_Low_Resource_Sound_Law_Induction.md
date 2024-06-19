# 大型语言模型是否能媲美语言学家的编码能力？——一项关于低资源环境下语音规律归纳的案例研究

发布时间：2024年06月18日

`LLM应用

这篇论文摘要描述了一种利用大型语言模型（LLMs）生成Python程序来辅助音变规律归纳（SLI）的方法。这种方法通过示例编程，利用LLMs生成语言转换程序，从而辅助历史语言学家在词汇转换过程中的工作。论文还探讨了如何生成语言无关的合成数据来优化LLMs在SLI任务中的表现。虽然这种方法在自动化SLI方面可能存在不足，但它旨在弥补现有方法的弱点。因此，这篇论文属于LLM应用分类，因为它展示了LLMs在特定应用场景（即语言学研究中的音变规律归纳）中的实际应用和优化。` `语言学` `计算语言学`

> Can Large Language Models Code Like a Linguist?: A Case Study in Low Resource Sound Law Induction

# 摘要

> 历史语言学家通过观察原始语言与后代语言的词汇对，构建程序将原始词汇转换为后代词汇，这一过程涉及一系列音变规律。尽管这一过程易错且耗时，但已有计算方法成功辅助。然而，音变规律归纳（SLI）领域研究较少，我们提出一种基于示例编程的新方法，利用LLMs生成Python音变程序。我们测试了该方法在多种LLMs上的效果，并探讨了生成语言无关合成数据以优化LLMs进行SLI的方法。与现有自动化SLI方法相比，我们的方法虽有不足，但能弥补其弱点。

> Historical linguists have long written a kind of incompletely formalized ''program'' that converts reconstructed words in an ancestor language into words in one of its attested descendants that consist of a series of ordered string rewrite functions (called sound laws). They do this by observing pairs of words in the reconstructed language (protoforms) and the descendent language (reflexes) and constructing a program that transforms protoforms into reflexes. However, writing these programs is error-prone and time-consuming. Prior work has successfully scaffolded this process computationally, but fewer researchers have tackled Sound Law Induction (SLI), which we approach in this paper by casting it as Programming by Examples. We propose a language-agnostic solution that utilizes the programming ability of Large Language Models (LLMs) by generating Python sound law programs from sound change examples. We evaluate the effectiveness of our approach for various LLMs, propose effective methods to generate additional language-agnostic synthetic data to fine-tune LLMs for SLI, and compare our method with existing automated SLI methods showing that while LLMs lag behind them they can complement some of their weaknesses.

[Arxiv](https://arxiv.org/abs/2406.12725)