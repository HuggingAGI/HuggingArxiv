# SynSUM -- 结合结构化与非结构化医疗记录的合成基准

发布时间：2024年09月13日

`LLM应用` `数据科学`

> SynSUM -- Synthetic Benchmark with Structured and Unstructured Medical Records

# 摘要

> 我们推出了 SynSUM 基准，一个将非结构化临床笔记与结构化背景变量结合的合成数据集。该数据集包含 10,000 个虚构的呼吸疾病患者记录，涵盖症状、诊断等表格变量及相应的临床笔记。表格数据通过贝叶斯网络生成，专家根据领域知识定义变量间的因果关系和概率。随后，我们利用 GPT-4o 生成描述患者症状和背景的临床笔记。SynSUM 主要用于研究表格背景变量下的临床信息提取，次要用途包括临床推理自动化、因果效应估计及多模态数据生成。数据集可从 https://github.com/prabaey/SynSUM 获取。

> We present the SynSUM benchmark, a synthetic dataset linking unstructured clinical notes to structured background variables. The dataset consists of 10,000 artificial patient records containing tabular variables (like symptoms, diagnoses and underlying conditions) and related notes describing the fictional patient encounter in the domain of respiratory diseases. The tabular portion of the data is generated through a Bayesian network, where both the causal structure between the variables and the conditional probabilities are proposed by an expert based on domain knowledge. We then prompt a large language model (GPT-4o) to generate a clinical note related to this patient encounter, describing the patient symptoms and additional context. The SynSUM dataset is primarily designed to facilitate research on clinical information extraction in the presence of tabular background variables, which can be linked through domain knowledge to concepts of interest to be extracted from the text - the symptoms, in the case of SynSUM. Secondary uses include research on the automation of clinical reasoning over both tabular data and text, causal effect estimation in the presence of tabular and/or textual confounders, and multi-modal synthetic data generation. The dataset can be downloaded from https://github.com/prabaey/SynSUM.

[Arxiv](https://arxiv.org/abs/2409.08936)