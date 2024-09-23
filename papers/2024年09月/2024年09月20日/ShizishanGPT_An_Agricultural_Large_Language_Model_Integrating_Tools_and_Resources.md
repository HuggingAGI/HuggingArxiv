# ShizishanGPT：一款集成了工具与资源的农业领域大型语言模型

发布时间：2024年09月20日

`Agent` `智能问答系统`

> ShizishanGPT: An Agricultural Large Language Model Integrating Tools and Resources

# 摘要

> 大型语言模型 (LLM) 的进步显著提升了智能对话系统处理复杂查询的能力，但在农业等专业领域仍显不足。为此，我们推出了 ShizishanGPT，一个基于 RAG 框架和代理架构的智能农业问答系统。ShizishanGPT 包含五个核心模块：通用 GPT-4 模块、搜索引擎模块、农业知识图谱模块、RAG 检索模块和农业代理模块，分别负责回答一般问题、知识更新、提供领域事实、补充领域知识以及进行作物表型预测和基因表达分析。我们通过 100 个专门设计的农业问题数据集进行了评估，结果显示 ShizishanGPT 因模块化设计和多源知识整合，显著优于一般 LLM，提供更精准详细的答案。所有资源已在 https://github.com/Zaiwen/CropGPT 公开。

> Recent developments in large language models (LLMs) have led to significant improvements in intelligent dialogue systems'ability to handle complex inquiries. However, current LLMs still exhibit limitations in specialized domain knowledge, particularly in technical fields such as agriculture. To address this problem, we propose ShizishanGPT, an intelligent question answering system for agriculture based on the Retrieval Augmented Generation (RAG) framework and agent architecture. ShizishanGPT consists of five key modules: including a generic GPT-4 based module for answering general questions; a search engine module that compensates for the problem that the large language model's own knowledge cannot be updated in a timely manner; an agricultural knowledge graph module for providing domain facts; a retrieval module which uses RAG to supplement domain knowledge; and an agricultural agent module, which invokes specialized models for crop phenotype prediction, gene expression analysis, and so on. We evaluated the ShizishanGPT using a dataset containing 100 agricultural questions specially designed for this study. The experimental results show that the tool significantly outperforms general LLMs as it provides more accurate and detailed answers due to its modular design and integration of different domain knowledge sources. Our source code, dataset, and model weights are publicly available at https://github.com/Zaiwen/CropGPT.

[Arxiv](https://arxiv.org/abs/2409.13537)