# 战壕经验谈：语言模型评估的可重复性之道

发布时间：2024年05月23日

`LLM理论

理由：这篇论文主要关注的是大型语言模型（LLM）的评估问题，并提供了解决这些问题的实用指南和工具。它讨论了评估过程中的挑战，并提出了具体的实践方法和工具（如开源工具包 lm-eval）来改善评估的独立性、可重复性和可扩展性。这些内容更偏向于理论和方法论的探讨，而不是具体的应用或Agent的设计，因此归类为LLM理论。` `模型评估`

> Lessons from the Trenches on Reproducible Evaluation of Language Models

# 摘要

> 在 NLP 领域，如何有效评估语言模型仍是一大挑战。研究人员和工程师在评估过程中常遇到模型对评估设置的敏感性、方法间的比较难度以及可重复性和透明度的缺失等问题。本文基于我们三年来在大型语言模型评估方面的经验，为研究者提供实用指南。首先，我们概述了语言模型评估中的常见难题。接着，我们提出了应对这些挑战的**实践。最后，我们介绍了开源工具包 lm-eval，它旨在解决上述问题，支持独立、可重复且可扩展的语言模型评估，并分享了使用该工具包解决方法论问题的实际案例。

> Effective evaluation of language models remains an open challenge in NLP. Researchers and engineers face methodological issues such as the sensitivity of models to evaluation setup, difficulty of proper comparisons across methods, and the lack of reproducibility and transparency. In this paper we draw on three years of experience in evaluating large language models to provide guidance and lessons for researchers. First, we provide an overview of common challenges faced in language model evaluation. Second, we delineate best practices for addressing or lessening the impact of these challenges on research. Third, we present the Language Model Evaluation Harness (lm-eval): an open source library for independent, reproducible, and extensible evaluation of language models that seeks to address these issues. We describe the features of the library as well as case studies in which the library has been used to alleviate these methodological concerns.

[Arxiv](https://arxiv.org/abs/2405.14782)