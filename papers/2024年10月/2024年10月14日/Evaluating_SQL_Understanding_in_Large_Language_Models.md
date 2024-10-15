# 探究大型语言模型对 SQL 的理解能力

发布时间：2024年10月14日

`LLM应用` `数据库`

> Evaluating SQL Understanding in Large Language Models

# 摘要

> 大型语言模型 (LLM) 的崛起，使得复杂的计算任务在 NLP 和图像生成等领域变得更加普及。尽管 LLM 的生成能力令人瞩目，但它们在结构化领域（如 SQL）中的“理解”程度仍备受争议。本文通过一系列关键 SQL 任务，评估 LLM 对 SQL 的“理解”深度。这些任务涵盖语法错误检测、缺失标记识别、查询性能预测、查询等价性检查和查询解释，旨在测试模型在识别、上下文感知、语义和连贯性方面的能力。我们基于知名工作负载生成数据集，评估最新 LLM 的性能，发现 GPT4 在识别和上下文任务中表现优异，但在深层次语义理解和连贯性方面，所有模型均显不足，特别是在查询等价性和性能估计上，凸显了当前 LLM 在完全 SQL 理解上的局限。

> The rise of large language models (LLMs) has significantly impacted various domains, including natural language processing (NLP) and image generation, by making complex computational tasks more accessible. While LLMs demonstrate impressive generative capabilities, there is an ongoing debate about their level of "understanding," particularly in structured domains like SQL. In this paper, we evaluate the extent to which LLMs "understand" SQL by testing them on a series of key SQL tasks. These tasks, such as syntax error detection, missing token identification, query performance prediction, query equivalence checking, and query explanation, assess the models' proficiency in recognition, context awareness, semantics, and coherence, which are essential skills for SQL understanding. We generate labeled datasets from well-known workloads, and evaluate the latest LLMs, focusing on how query complexity and syntactic features influence performance. Our results indicate that while GPT4 excels at tasks requiring recognition and context, all models struggle with deeper semantic understanding and coherence, especially in query equivalence and performance estimation, revealing the limitations of current LLMs in achieving full SQL comprehension.

[Arxiv](https://arxiv.org/abs/2410.10680)