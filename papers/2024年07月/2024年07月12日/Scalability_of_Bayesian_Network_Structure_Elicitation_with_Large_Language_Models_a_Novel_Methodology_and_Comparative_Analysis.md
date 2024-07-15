# 大型语言模型在贝叶斯网络结构启发中的可扩展性：创新方法论与对比分析

发布时间：2024年07月12日

`LLM应用` `人工智能` `数据分析`

> Scalability of Bayesian Network Structure Elicitation with Large Language Models: a Novel Methodology and Comparative Analysis

# 摘要

> 本研究提出一种创新方法，通过初始化多个经验各异的 LLM，独立构建贝叶斯网络 (BN) 结构，并采用多数投票确定最终结构。我们对比了该方法与另一种替代方案在不同规模和知名度的 BN 上的表现，并探讨了它们的可扩展性。此外，我们开发了一种检测 LLM 中 BN 污染的方法，发现某些知名 BN 不适用于评估 LLM 在 BN 结构诱导中的应用。实验还揭示，由于节点名称难以区分，部分 BN 不适合此类实验。对其他 BN 的测试显示，我们的方法在某一 LLM 上优于现有技术，但两种方法的性能均随 BN 规模增大而显著下降。

> In this work, we propose a novel method for Bayesian Networks (BNs) structure elicitation that is based on the initialization of several LLMs with different experiences, independently querying them to create a structure of the BN, and further obtaining the final structure by majority voting. We compare the method with one alternative method on various widely and not widely known BNs of different sizes and study the scalability of both methods on them. We also propose an approach to check the contamination of BNs in LLM, which shows that some widely known BNs are inapplicable for testing the LLM usage for BNs structure elicitation. We also show that some BNs may be inapplicable for such experiments because their node names are indistinguishable. The experiments on the other BNs show that our method performs better than the existing method with one of the three studied LLMs; however, the performance of both methods significantly decreases with the increase in BN size.

[Arxiv](https://arxiv.org/abs/2407.09311)