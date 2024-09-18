# THaMES：一款专为大型语言模型设计的端到端工具，旨在缓解幻觉问题并进行性能评估。

发布时间：2024年09月17日

`LLM应用` `人工智能`

> THaMES: An End-to-End Tool for Hallucination Mitigation and Evaluation in Large Language Models

# 摘要

> 幻觉问题在 LLM 中愈发严峻，现有方法难以满足特定领域需求，缺乏标准化流程。为此，我们推出了 THaMES，一个集成的幻觉缓解和评估框架。THaMES 提供端到端解决方案，自动生成高质量测试集，多维度评估模型，并灵活应用缓解策略。通过批处理、加权采样等技术，THaMES 确保数据多样性和成本效益。它评估模型在文本生成和分类等任务中的幻觉检测能力，应用 ICL、RAG 和 PEFT 等策略。评估显示，GPT-4o 更受益于 RAG，而 Llama-3.1-8B-Instruct 和 Mistral-Nemo 则从 ICL 中获益更多。此外，PEFT 显著提升了 Llama-3.1-8B-Instruct 的表现。

> Hallucination, the generation of factually incorrect content, is a growing challenge in Large Language Models (LLMs). Existing detection and mitigation methods are often isolated and insufficient for domain-specific needs, lacking a standardized pipeline. This paper introduces THaMES (Tool for Hallucination Mitigations and EvaluationS), an integrated framework and library addressing this gap. THaMES offers an end-to-end solution for evaluating and mitigating hallucinations in LLMs, featuring automated test set generation, multifaceted benchmarking, and adaptable mitigation strategies. It automates test set creation from any corpus, ensuring high data quality, diversity, and cost-efficiency through techniques like batch processing, weighted sampling, and counterfactual validation. THaMES assesses a model's ability to detect and reduce hallucinations across various tasks, including text generation and binary classification, applying optimal mitigation strategies like In-Context Learning (ICL), Retrieval Augmented Generation (RAG), and Parameter-Efficient Fine-tuning (PEFT). Evaluations of state-of-the-art LLMs using a knowledge base of academic papers, political news, and Wikipedia reveal that commercial models like GPT-4o benefit more from RAG than ICL, while open-weight models like Llama-3.1-8B-Instruct and Mistral-Nemo gain more from ICL. Additionally, PEFT significantly enhances the performance of Llama-3.1-8B-Instruct in both evaluation tasks.

[Arxiv](https://arxiv.org/abs/2409.11353)