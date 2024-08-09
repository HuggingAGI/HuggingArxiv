# wav2graph：一款专为从语音数据中构建监督学习知识图谱的框架

发布时间：2024年08月07日

`LLM应用` `语音识别` `知识图谱`

> wav2graph: A Framework for Supervised Learning Knowledge Graph from Speech

# 摘要

> 知识图谱 (KGs) 通过提供结构化、互联的数据，显著提升了大型语言模型 (LLMs) 和搜索引擎的推理与上下文感知能力。然而，KGs 主要聚焦于文本数据，忽视了语音等其他模态。为此，我们推出了 wav2graph，首个从语音数据中构建监督学习知识图谱的框架。我们的流程简明扼要：首先，基于转录的口语和命名实体数据库构建 KG；其次，将 KG 转化为嵌入向量；最后，训练图神经网络 (GNNs) 进行节点分类和链接预测。通过一系列实验，我们使用最先进的 GNN 模型，在归纳和转导学习环境中，为节点分类和链接预测任务提供了基线结果和错误分析，涵盖了基于编码器和解码器的节点嵌入，以及单语和多语种声学预训练模型。所有相关资源均已在线公开。

> Knowledge graphs (KGs) enhance the performance of large language models (LLMs) and search engines by providing structured, interconnected data that improves reasoning and context-awareness. However, KGs only focus on text data, thereby neglecting other modalities such as speech. In this work, we introduce wav2graph, the first framework for supervised learning knowledge graph from speech data. Our pipeline are straightforward: (1) constructing a KG based on transcribed spoken utterances and a named entity database, (2) converting KG into embedding vectors, and (3) training graph neural networks (GNNs) for node classification and link prediction tasks. Through extensive experiments conducted in inductive and transductive learning contexts using state-of-the-art GNN models, we provide baseline results and error analysis for node classification and link prediction tasks on human transcripts and automatic speech recognition (ASR) transcripts, including evaluations using both encoder-based and decoder-based node embeddings, as well as monolingual and multilingual acoustic pre-trained models. All related code, data, and models are published online.

[Arxiv](https://arxiv.org/abs/2408.04174)