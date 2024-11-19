# ZeFaV：助力大型语言模型实现零样本事实验证能力的提升

发布时间：2024年11月17日

`LLM应用` `事实核查` `语言模型`

> ZeFaV: Boosting Large Language Models for Zero-shot Fact Verification

# 摘要

> 在本文中，我们提出了 ZeFaV——一个基于零样本的事实核查验证框架，旨在借助大型语言模型的上下文学习能力，提取声明中实体间的关系，以关系逻辑形式重新整理来自证据的信息，并将这些信息与原始证据相结合来生成上下文，让我们的事实核查模型为输入的声明给出裁决，以此提升大型语言模型在事实核查任务上的表现。我们在 HoVer 和 FEVEROUS 这两个多跳事实核查数据集上开展了实证实验来评估我们的方法，取得了能与其他先进的事实核查任务方法相媲美的潜在成果。

> In this paper, we propose ZeFaV - a zero-shot based fact-checking verification framework to enhance the performance on fact verification task of large language models by leveraging the in-context learning ability of large language models to extract the relations among the entities within a claim, re-organized the information from the evidence in a relationally logical form, and combine the above information with the original evidence to generate the context from which our fact-checking model provide verdicts for the input claims. We conducted empirical experiments to evaluate our approach on two multi-hop fact-checking datasets including HoVer and FEVEROUS, and achieved potential results results comparable to other state-of-the-art fact verification task methods.

[Arxiv](https://arxiv.org/abs/2411.11247)