# LLM-PQA：利用 LLM 提升预测查询回答能力

发布时间：2024年09月02日

`LLM应用` `数据库` `人工智能`

> LLM-PQA: LLM-enhanced Prediction Query Answering

# 摘要

> 随着大型语言模型 (LLM) 的兴起，我们有了超越传统 SQL 数据库系统限制，革新查询处理方式的可能。然而，利用 LLM 解答预测查询依旧充满挑战，需借助外部 ML 模型并执行推理。为此，我们推出了 LLM-PQA 这一创新工具，专门应对自然语言形式的预测查询。LLM-PQA 首次将 LLM 的强大能力与检索增强机制相结合，通过融合数据湖与模型库，为用户打开了访问海量异构数据与多元 ML 模型的大门，助力动态预测查询的高效解答。更值得一提的是，LLM-PQA 还能按需动态训练模型，确保即使在模型库中缺乏相应预训练模型的情况下，依然能输出精准且贴合需求的结果。

> The advent of Large Language Models (LLMs) provides an opportunity to change the way queries are processed, moving beyond the constraints of conventional SQL-based database systems. However, using an LLM to answer a prediction query is still challenging, since an external ML model has to be employed and inference has to be performed in order to provide an answer. This paper introduces LLM-PQA, a novel tool that addresses prediction queries formulated in natural language. LLM-PQA is the first to combine the capabilities of LLMs and retrieval-augmented mechanism for the needs of prediction queries by integrating data lakes and model zoos. This integration provides users with access to a vast spectrum of heterogeneous data and diverse ML models, facilitating dynamic prediction query answering. In addition, LLM-PQA can dynamically train models on demand, based on specific query requirements, ensuring reliable and relevant results even when no pre-trained model in a model zoo, available for the task.

[Arxiv](https://arxiv.org/abs/2409.01140)