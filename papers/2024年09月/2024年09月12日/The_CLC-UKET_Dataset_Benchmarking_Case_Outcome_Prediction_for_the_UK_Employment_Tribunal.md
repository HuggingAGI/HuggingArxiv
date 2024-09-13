# CLC-UKET 数据集：英国就业法庭案件结果预测的基准测试

发布时间：2024年09月12日

`LLM应用` `人力资源`

> The CLC-UKET Dataset: Benchmarking Case Outcome Prediction for the UK Employment Tribunal

# 摘要

> 本文通过开发预测英国就业法庭案件结果的基准，探讨了技术创新与司法公正的结合。为解决手动标注的难题，我们利用大型语言模型自动生成 CLC-UKET 数据集，包含约 19,000 个案件及其详细法律信息。借助此数据集，我们研究了多类案件结果预测任务，并收集人类预测作为模型性能的参考。实证显示，微调的变压器模型在预测任务中表现优于零-shot 和少-shot LLM。通过整合任务相关信息，零-shot LLM 的性能得以提升。我们期待 CLC-UKET 数据集及其相关研究能为就业纠纷解决提供有力支持。

> This paper explores the intersection of technological innovation and access to justice by developing a benchmark for predicting case outcomes in the UK Employment Tribunal (UKET). To address the challenge of extensive manual annotation, the study employs a large language model (LLM) for automatic annotation, resulting in the creation of the CLC-UKET dataset. The dataset consists of approximately 19,000 UKET cases and their metadata. Comprehensive legal annotations cover facts, claims, precedent references, statutory references, case outcomes, reasons and jurisdiction codes. Facilitated by the CLC-UKET data, we examine a multi-class case outcome prediction task in the UKET. Human predictions are collected to establish a performance reference for model comparison. Empirical results from baseline models indicate that finetuned transformer models outperform zero-shot and few-shot LLMs on the UKET prediction task. The performance of zero-shot LLMs can be enhanced by integrating task-related information into few-shot examples. We hope that the CLC-UKET dataset, along with human annotations and empirical findings, can serve as a valuable benchmark for employment-related dispute resolution.

[Arxiv](https://arxiv.org/abs/2409.08098)