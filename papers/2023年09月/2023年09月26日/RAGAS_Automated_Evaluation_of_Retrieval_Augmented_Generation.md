# RAGAS：实现检索增强生成的自动化评估

发布时间：2023年09月26日

`RAG` `人工智能`

> RAGAS: Automated Evaluation of Retrieval Augmented Generation

# 摘要

> 我们推出 RAGAs 框架，用于无参考评估 RAG 系统。RAG 系统结合检索与 LLM 生成模块，让 LLM 从文本数据库获取知识，充当用户与数据库间的自然语言接口，减少幻觉风险。评估 RAG 架构颇具挑战，需考量多维度：检索系统筛选相关上下文的能力、LLM 忠实利用这些上下文的能力及生成质量。RAGAs 提出一套无需依赖人工注释的评估指标，助力 RAG 架构的快速迭代，这对 LLM 的广泛应用至关重要。

> 
Abstract:We introduce RAGAs (Retrieval Augmented Generation Assessment), a framework for reference-free evaluation of Retrieval Augmented Generation (RAG) pipelines. RAG systems are composed of a retrieval and an LLM based generation module, and provide LLMs with knowledge from a reference textual database, which enables them to act as a natural language layer between a user and textual databases, reducing the risk of hallucinations. Evaluating RAG architectures is, however, challenging because there are several dimensions to consider: the ability of the retrieval system to identify relevant and focused context passages, the ability of the LLM to exploit such passages in a faithful way, or the quality of the generation itself. With RAGAs, we put forward a suite of metrics which can be used to evaluate these different dimensions \textit{without having to rely on ground truth human annotations}. We posit that such a framework can crucially contribute to faster evaluation cycles of RAG architectures, which is especially important given the fast adoption of LLMs.
    

[Arxiv](https://arxiv.org/pdf/2309.15217)