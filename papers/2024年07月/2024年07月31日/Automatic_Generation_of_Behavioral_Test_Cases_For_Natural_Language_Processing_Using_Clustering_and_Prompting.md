# 通过聚类与提示技术，自动生成自然语言处理的行为测试用例

发布时间：2024年07月31日

`LLM应用` `软件工程`

> Automatic Generation of Behavioral Test Cases For Natural Language Processing Using Clustering and Prompting

# 摘要

> 近期，NLP模型行为测试的研究，如Checklist，借鉴了软件工程测试的理念，旨在评估语言通用性和领域理解，进而检验模型概念的合理性并揭示其弱点。然而，测试用例的构建是一大难题。现有的方法依赖于半自动化的手动开发，这不仅需要专业知识，还可能耗时。本文提出了一种自动化方案，利用大型语言模型和统计技术，通过文本表示的聚类来精心构建意义组，并运用提示技术自动生成最小功能测试（MFT）。我们以知名的Amazon Reviews语料库为例，展示了这一方法，并分析了四种分类算法的行为测试概况，探讨了各模型的优劣。

> Recent work in behavioral testing for natural language processing (NLP) models, such as Checklist, is inspired by related paradigms in software engineering testing. They allow evaluation of general linguistic capabilities and domain understanding, hence can help evaluate conceptual soundness and identify model weaknesses. However, a major challenge is the creation of test cases. The current packages rely on semi-automated approach using manual development which requires domain expertise and can be time consuming. This paper introduces an automated approach to develop test cases by exploiting the power of large language models and statistical techniques. It clusters the text representations to carefully construct meaningful groups and then apply prompting techniques to automatically generate Minimal Functionality Tests (MFT). The well-known Amazon Reviews corpus is used to demonstrate our approach. We analyze the behavioral test profiles across four different classification algorithms and discuss the limitations and strengths of those models.

[Arxiv](https://arxiv.org/abs/2408.00161)