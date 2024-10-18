# FaithBench：一个专为现代 LLM 设计的多样化幻觉基准，用于评估其摘要能力。

发布时间：2024年10月17日

`LLM应用` `人工智能`

> FaithBench: A Diverse Hallucination Benchmark for Summarization by Modern LLMs

# 摘要

> 摘要任务在大语言模型（LLM）中尤为常见，尤其是在 RAG 等应用中。然而，现有对 LLM 生成摘要中幻觉的评估，以及对幻觉检测模型的评估，都存在多样性和时效性不足的问题。本文推出的 FaithBench，是一个包含 10 个现代 LLM 家族的 10 个 LLM 生成的具有挑战性幻觉的摘要基准，由人类专家进行真实标注。这里的“具有挑战性”意味着在流行的、最先进的幻觉检测模型（包括 GPT-4o-as-a-judge）之间存在分歧的摘要。研究显示，GPT-4o 和 GPT-3.5-Turbo 产生的幻觉最少，但即使是最好的幻觉检测模型在 FaithBench 上的准确率也接近 50%，未来改进空间巨大。仓库地址：https://github.com/vectara/FaithBench。

> Summarization is one of the most common tasks performed by large language models (LLMs), especially in applications like Retrieval-Augmented Generation (RAG). However, existing evaluations of hallucinations in LLM-generated summaries, and evaluations of hallucination detection models both suffer from a lack of diversity and recency in the LLM and LLM families considered. This paper introduces FaithBench, a summarization hallucination benchmark comprising challenging hallucinations made by 10 modern LLMs from 8 different families, with ground truth annotations by human experts. ``Challenging'' here means summaries on which popular, state-of-the-art hallucination detection models, including GPT-4o-as-a-judge, disagreed on. Our results show GPT-4o and GPT-3.5-Turbo produce the least hallucinations. However, even the best hallucination detection models have near 50\% accuracies on FaithBench, indicating lots of room for future improvement. The repo is https://github.com/vectara/FaithBench

[Arxiv](https://arxiv.org/abs/2410.13210)