# IntelliCare：利用大型语言模型中的变异控制患者级知识，提升医疗保健分析的精准度。

发布时间：2024年08月23日

`LLM应用` `个性化医疗`

> IntelliCare: Improving Healthcare Analysis with Variance-Controlled Patient-Level Knowledge from Large Language Models

# 摘要

> 深度学习虽在 EHR 数据分析上取得显著进展，但常难以全面捕捉医疗代码的复杂语义。为此，我们提出 IntelliCare 框架，借助 LLM 的外部知识，提升医疗预测的准确性。该框架通过识别患者群体和利用相关统计信息，有效解决 LLM 的歧义问题，并通过混合方法优化知识输出。实验证明，IntelliCare 在多个临床预测任务中显著提升性能，为个性化医疗预测和决策支持系统开辟了新路径。

> While pioneering deep learning methods have made great strides in analyzing electronic health record (EHR) data, they often struggle to fully capture the semantics of diverse medical codes from limited data. The integration of external knowledge from Large Language Models (LLMs) presents a promising avenue for improving healthcare predictions. However, LLM analyses may exhibit significant variance due to ambiguity problems and inconsistency issues, hindering their effective utilization. To address these challenges, we propose IntelliCare, a novel framework that leverages LLMs to provide high-quality patient-level external knowledge and enhance existing EHR models. Concretely, IntelliCare identifies patient cohorts and employs task-relevant statistical information to augment LLM understanding and generation, effectively mitigating the ambiguity problem. Additionally, it refines LLM-derived knowledge through a hybrid approach, generating multiple analyses and calibrating them using both the EHR model and perplexity measures. Experimental evaluations on three clinical prediction tasks across two large-scale EHR datasets demonstrate that IntelliCare delivers significant performance improvements to existing methods, highlighting its potential in advancing personalized healthcare predictions and decision support systems.

[Arxiv](https://arxiv.org/abs/2408.13073)