# TrustSQL 是一个专为评估Text-to-SQL模型可靠性的基准，它特别设计了多样化的无法回答问题，以全面检验模型在面对复杂SQL查询挑战时的性能与可靠性。

发布时间：2024年03月23日

`LLM应用` `数据库`

> TrustSQL: A Reliability Benchmark for Text-to-SQL Models with Diverse Unanswerable Questions

# 摘要

> 近年来LLMs技术的进步极大地提升了将自然语言问题精准转换为SQL查询的能力，但当面对真实应用中的多样化问题，特别是无法回答的问题时，这类文本转SQL模型的可靠性尚待深入探究。为此，我们推出了TrustSQL这一全新基准，旨在评估文本转SQL模型在单数据库和跨数据库环境下的可靠性。该基准要求模型在生成SQL时，要么做出预测，要么在发现潜在错误或遇到无解问题时选择放弃预测。在模型评估阶段，我们针对此任务尝试了多种专门设计的建模方法，一是分别优化可答性检测、SQL生成和错误检测三个模块，再集成至一个流水线中；二是研发一体化方案，训练单一模型来应对这一综合任务。采用我们新提出的可靠性评分进行的实验证明，应对这一挑战涉及多领域的研究，并为模型开发开启新方向。然而，目前所有的方法都无法超越仅对所有问题均不作答的朴素基线的可靠性水平。

> Recent advances in large language models (LLMs) have led to significant improvements in translating natural language questions into SQL queries. While achieving high accuracy in SQL generation is crucial, little is known about the extent to which these text-to-SQL models can reliably handle diverse types of questions encountered during real-world deployment, including unanswerable ones. To explore this aspect, we present TrustSQL, a new benchmark designed to assess the reliability of text-to-SQL models in both single-database and cross-database settings. The benchmark tasks models with providing one of two outcomes: 1) SQL prediction; or 2) abstention from making a prediction, either when there is a potential error in the generated SQL or when faced with unanswerable questions. For model evaluation, we explore various modeling approaches specifically designed for this task. These include: 1) optimizing separate models for answerability detection, SQL generation, and error detection, which are then integrated into a single pipeline; and 2) developing a unified approach that optimizes a single model to address the proposed task. Experimental results using our new reliability score show that addressing this challenge involves many different areas of research and opens new avenues for model development. Nonetheless, none of the methods surpass the reliability performance of the naive baseline, which abstains from answering all questions.

[Arxiv](https://arxiv.org/abs/2403.15879)