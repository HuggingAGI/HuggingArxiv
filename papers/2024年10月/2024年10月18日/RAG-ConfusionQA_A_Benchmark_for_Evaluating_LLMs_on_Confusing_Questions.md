# RAG-ConfusionQA：评估 LLM 应对混淆问题的基准

发布时间：2024年10月18日

`RAG` `人工智能`

> RAG-ConfusionQA: A Benchmark for Evaluating LLMs on Confusing Questions

# 摘要

> 对话式 AI 代理通过 RAG 技术提供基于文档的可验证回答，但许多自然问题难以解答：约 25% 包含错误假设，超过 50% 模糊不清。为提升 RAG 代理应对复杂问题的能力，本文提出了一种高效的合成数据生成方法，从现有文档中创建多样化的混乱问题。我们还对多个大型语言模型进行了实证评估，以测试其混淆检测和适当回答的能力，并公开了一个基准数据集。

> Conversational AI agents use Retrieval Augmented Generation (RAG) to provide verifiable document-grounded responses to user inquiries. However, many natural questions do not have good answers: about 25\% contain false assumptions~\cite{Yu2023:CREPE}, and over 50\% are ambiguous~\cite{Min2020:AmbigQA}. RAG agents need high-quality data to improve their responses to confusing questions. This paper presents a novel synthetic data generation method to efficiently create a diverse set of context-grounded confusing questions from a given document corpus. We conduct an empirical comparative evaluation of several large language models as RAG agents to measure the accuracy of confusion detection and appropriate response generation. We contribute a benchmark dataset to the public domain.

[Arxiv](https://arxiv.org/abs/2410.14567)