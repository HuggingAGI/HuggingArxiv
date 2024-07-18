# NinjaLLM：借助 Amazon SageMaker 与 AWS Trainium 和 Inferentia2，实现高效、可扩展且经济的 RAG 解决方案。

发布时间：2024年07月11日

`RAG` `云计算` `人工智能`

> NinjaLLM: Fast, Scalable and Cost-effective RAG using Amazon SageMaker and AWS Trainium and Inferentia2

# 摘要

> 本文针对大型语言模型（LLM），在 AWS Trainium 和 Inferentia2 AI 芯片上通过 SageMaker 进行微调与托管，提出了一系列对 RAG 技术的改进。这些芯片不仅经济实惠，而且具有出色的弹性与高效性能。改进措施包括提升工具使用效率、增加引用功能，以及减少因上下文偏差引发的问题。在 Natural Questions 和 HotPotQA 数据集上的测试显示，我们的 RAG 系统准确率分别达到 62% 和 59%，优于同类模型。

> Retrieval-augmented generation (RAG) techniques are widely used today to retrieve and present information in a conversational format. This paper presents a set of enhancements to traditional RAG techniques, focusing on large language models (LLMs) fine-tuned and hosted on AWS Trainium and Inferentia2 AI chips via SageMaker. These chips are characterized by their elasticity, affordability, and efficient performance for AI compute tasks. Besides enabling deployment on these chips, this work aims to improve tool usage, add citation capabilities, and mitigate the risks of hallucinations and unsafe responses due to context bias. We benchmark our RAG system's performance on the Natural Questions and HotPotQA datasets, achieving an accuracy of 62% and 59% respectively, exceeding other models such as DBRX and Mixtral Instruct.

[Arxiv](https://arxiv.org/abs/2407.12057)