# 本研究提出了一种基于稀疏逻辑回归的方法，通过高阶特征自动从树库中提取语法规则。

发布时间：2024年03月26日

`LLM应用` `语言学` `语料库`

> Sparse Logistic Regression with High-order Features for Automatic Grammar Rule Extraction from Treebanks

# 摘要

> 描述性语法虽极具价值，但其编写过程却既费时又充满挑战。传统上，语言学家依赖语料库来构建这类语法，但往往缺少量化数据支持。形式语法的解释同样令人头疼。本文提出了一种创新方法，旨在从树库中挖掘出精细的语法模式和潜在句法规则，以构建一部通俗易懂的语料库语法书。我们针对一致性和词序这两个语言现象，跨越不同语言进行规则和描述的提取，注重规则的排序。通过运用线性分类器，我们筛选出最能预示特定语言现象的关键特征，并为每条规则附上统计数据，进一步将模型结果的排序与其他量化统计指标进行对比。此方法成功揭示了西班牙语、法语和沃洛夫语中显著的语法规则，既包括广为人知的，也包括较为隐蔽的。

> Descriptive grammars are highly valuable, but writing them is time-consuming and difficult. Furthermore, while linguists typically use corpora to create them, grammar descriptions often lack quantitative data. As for formal grammars, they can be challenging to interpret. In this paper, we propose a new method to extract and explore significant fine-grained grammar patterns and potential syntactic grammar rules from treebanks, in order to create an easy-to-understand corpus-based grammar. More specifically, we extract descriptions and rules across different languages for two linguistic phenomena, agreement and word order, using a large search space and paying special attention to the ranking order of the extracted rules. For that, we use a linear classifier to extract the most salient features that predict the linguistic phenomena under study. We associate statistical information to each rule, and we compare the ranking of the model's results to those of other quantitative and statistical measures. Our method captures both well-known and less well-known significant grammar rules in Spanish, French, and Wolof.

[Arxiv](https://arxiv.org/abs/2403.17534)