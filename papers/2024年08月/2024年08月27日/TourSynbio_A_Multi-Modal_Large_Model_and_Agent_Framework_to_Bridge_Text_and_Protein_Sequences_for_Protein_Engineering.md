# TourSynbio：一款多模态大型模型与代理框架，旨在搭建文本与蛋白质序列之间的桥梁，推动蛋白质工程的发展。

发布时间：2024年08月27日

`Agent` `生物技术` `蛋白质工程`

> TourSynbio: A Multi-Modal Large Model and Agent Framework to Bridge Text and Protein Sequences for Protein Engineering

# 摘要

> 蛋白质与语言的结构相似性推动了深度学习在两领域的共同进步。大型语言模型（LLMs）虽在自然语言处理领域成绩斐然，但在蛋白质工程领域尚待探索。传统方法通过添加外部蛋白质编码器提升LLMs的蛋白质理解能力，但未能充分挖掘两者间的固有相似性，导致性能受限且模型复杂。为此，我们推出了TourSynbio-7B，首个无需外部编码器的多模态大型模型，专为蛋白质工程设计。TourSynbio-7B证明LLMs能自然学会将蛋白质视为语言。该模型在包含174.6亿标记的ProteinLMDataset上进行自监督预训练，并通过89.3万指令进行监督微调，其在ProteinLMBench基准测试中以62.18%的准确率超越GPT-4。基于此，我们开发了TourSynbio-Agent框架，整合了蛋白质工程领域的分散模型，提供统一对话界面，支持突变分析、逆折叠、蛋白质折叠及可视化等任务。通过两个湿实验室案例研究，我们验证了TourSynbio-7B和TourSynbio-Agent在酶修饰和化合物催化中的实际效能。

> The structural similarities between protein sequences and natural languages have led to parallel advancements in deep learning across both domains. While large language models (LLMs) have achieved much progress in the domain of natural language processing, their potential in protein engineering remains largely unexplored. Previous approaches have equipped LLMs with protein understanding capabilities by incorporating external protein encoders, but this fails to fully leverage the inherent similarities between protein sequences and natural languages, resulting in sub-optimal performance and increased model complexity. To address this gap, we present TourSynbio-7B, the first multi-modal large model specifically designed for protein engineering tasks without external protein encoders. TourSynbio-7B demonstrates that LLMs can inherently learn to understand proteins as language. The model is post-trained and instruction fine-tuned on InternLM2-7B using ProteinLMDataset, a dataset comprising 17.46 billion tokens of text and protein sequence for self-supervised pretraining and 893K instructions for supervised fine-tuning. TourSynbio-7B outperforms GPT-4 on the ProteinLMBench, a benchmark of 944 manually verified multiple-choice questions, with 62.18% accuracy. Leveraging TourSynbio-7B's enhanced protein sequence understanding capability, we introduce TourSynbio-Agent, an innovative framework capable of performing various protein engineering tasks, including mutation analysis, inverse folding, protein folding, and visualization. TourSynbio-Agent integrates previously disconnected deep learning models in the protein engineering domain, offering a unified conversational user interface for improved usability. Finally, we demonstrate the efficacy of TourSynbio-7B and TourSynbio-Agent through two wet lab case studies on vanilla key enzyme modification and steroid compound catalysis.

[Arxiv](https://arxiv.org/abs/2408.15299)