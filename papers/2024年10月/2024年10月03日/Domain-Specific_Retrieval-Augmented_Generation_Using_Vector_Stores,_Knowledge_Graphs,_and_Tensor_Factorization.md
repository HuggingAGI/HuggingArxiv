# 结合向量存储、知识图谱与张量分解，实现特定领域的检索增强生成技术。

发布时间：2024年10月03日

`RAG` `网络安全` `知识图谱`

> Domain-Specific Retrieval-Augmented Generation Using Vector Stores, Knowledge Graphs, and Tensor Factorization

# 摘要

> 大型语言模型 (LLM) 在通用 NLP 任务中表现优异，但在特定领域和知识密集型任务中存在幻觉、知识截断和缺乏归属的问题。微调 LLM 到特定领域既昂贵又耗时。检索增强生成 (RAG) 通过参考预定义本体优化 LLM 响应，使用知识图谱 (KG) 本体可提高 QA 准确性。本文介绍的 SMART-SLIC 框架集成了 RAG、KG 和存储领域特定信息的向量存储 (VS)，避免 KG 幻觉，通过 NLP、数据挖掘和非负张量分解构建。结合特定领域的 KG 和 VS，SMART-SLIC 开发的聊天机器人能归属信息来源、减少幻觉、减少微调需求，并在特定领域问答中表现出色。该框架可泛化适应任何专业领域，本文展示了其在恶意软件分析和异常检测领域的问答能力。

> Large Language Models (LLMs) are pre-trained on large-scale corpora and excel in numerous general natural language processing (NLP) tasks, such as question answering (QA). Despite their advanced language capabilities, when it comes to domain-specific and knowledge-intensive tasks, LLMs suffer from hallucinations, knowledge cut-offs, and lack of knowledge attributions. Additionally, fine tuning LLMs' intrinsic knowledge to highly specific domains is an expensive and time consuming process. The retrieval-augmented generation (RAG) process has recently emerged as a method capable of optimization of LLM responses, by referencing them to a predetermined ontology. It was shown that using a Knowledge Graph (KG) ontology for RAG improves the QA accuracy, by taking into account relevant sub-graphs that preserve the information in a structured manner. In this paper, we introduce SMART-SLIC, a highly domain-specific LLM framework, that integrates RAG with KG and a vector store (VS) that store factual domain specific information. Importantly, to avoid hallucinations in the KG, we build these highly domain-specific KGs and VSs without the use of LLMs, but via NLP, data mining, and nonnegative tensor factorization with automatic model selection. Pairing our RAG with a domain-specific: (i) KG (containing structured information), and (ii) VS (containing unstructured information) enables the development of domain-specific chat-bots that attribute the source of information, mitigate hallucinations, lessen the need for fine-tuning, and excel in highly domain-specific question answering tasks. We pair SMART-SLIC with chain-of-thought prompting agents. The framework is designed to be generalizable to adapt to any specific or specialized domain. In this paper, we demonstrate the question answering capabilities of our framework on a corpus of scientific publications on malware analysis and anomaly detection.

[Arxiv](https://arxiv.org/abs/2410.02721)