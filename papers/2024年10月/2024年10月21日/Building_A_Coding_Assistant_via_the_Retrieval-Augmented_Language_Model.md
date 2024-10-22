# 打造编码助手：基于检索增强的语言模型

发布时间：2024年10月21日

`LLM应用` `软件开发` `人工智能`

> Building A Coding Assistant via the Retrieval-Augmented Language Model

# 摘要

> 预训练语言模型在代码任务中表现出色，如代码检索、生成、摘要和补全。本文提出CONAN，通过模仿人类编码时的知识寻求行为，构建代码助手。CONAN包含代码结构感知的检索器（CONAN-R）和双视图代码表示的生成模型（CONAN-G）。CONAN-R通过Code-Documentation对齐和掩码实体预测任务预训练CodeT5，使其具备代码结构感知能力。CONAN-G则设计双视图代码表示机制，将代码文档描述作为提示，提升代码语义理解。实验显示，CONAN在代码生成任务中表现优异，显著超越以往模型。进一步分析表明，CONAN通过代码-文档对齐和结构语义捕捉，学习了代码片段和文档的定制表示。此外，检索到的代码片段和文档为代码生成提供了必要信息。CONAN还可作为LLM的助手，通过提供外部知识，提升其在代码任务中的表现。它展示了CONAN提取必要信息和过滤噪声的能力。

> Pretrained language models have shown strong effectiveness in code-related tasks, such as code retrieval, code generation, code summarization, and code completion tasks. In this paper, we propose COde assistaNt viA retrieval-augmeNted language model (CONAN), which aims to build a code assistant by mimicking the knowledge-seeking behaviors of humans during coding. Specifically, it consists of a code structure aware retriever (CONAN-R) and a dual-view code representation-based retrieval-augmented generation model (CONAN-G). CONAN-R pretrains CodeT5 using Code-Documentation Alignment and Masked Entity Prediction tasks to make language models code structure-aware and learn effective representations for code snippets and documentation. Then CONAN-G designs a dual-view code representation mechanism for implementing a retrieval-augmented code generation model. CONAN-G regards the code documentation descriptions as prompts, which help language models better understand the code semantics. Our experiments show that CONAN achieves convincing performance on different code generation tasks and significantly outperforms previous retrieval augmented code generation models. Our further analyses show that CONAN learns tailored representations for both code snippets and documentation by aligning code-documentation data pairs and capturing structural semantics by masking and predicting entities in the code data. Additionally, the retrieved code snippets and documentation provide necessary information from both program language and natural language to assist the code generation process. CONAN can also be used as an assistant for Large Language Models (LLMs), providing LLMs with external knowledge in shorter code document lengths to improve their effectiveness on various code tasks. It shows the ability of CONAN to extract necessary information and help filter out the noise from retrieved code documents.

[Arxiv](https://arxiv.org/abs/2410.16229)