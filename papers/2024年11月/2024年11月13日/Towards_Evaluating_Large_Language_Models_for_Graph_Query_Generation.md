# 对于图查询生成评估大型语言模型

发布时间：2024年11月13日

`LLM应用` `数据库` `图数据库`

> Towards Evaluating Large Language Models for Graph Query Generation

# 摘要

> 大型语言模型（LLMs）正在彻底改变生成式人工智能（GenAI）的格局，创新的基于 LLM 的解决方案迅速涌现。然而，当应用于数据库技术时，特别是针对图数据库和知识图谱（KGs）的查询生成，LLMs 仍然面临重大挑战。虽然存在关于 LLM 驱动的结构化查询语言（SQL）查询生成的研究，但针对图数据库的类似系统仍不发达。本文提出了一项比较研究，解决了使用开放访问的 LLM 生成用于与图数据库交互的强大语言 Cypher 查询的挑战。我们使用设计的少样本学习提示和由思维链（CoT）推理支持的检索增强生成（RAG），严格评估了几个 LLM 代理（OpenAI ChatGPT 4o、Claude Sonnet 3.5、Google Gemini Pro 1.5 和本地部署的 Llama 3.1 8B）。我们对查询生成准确性的实证分析表明，Claude Sonnet 3.5 在这个特定领域的表现优于其他同类产品。此外，我们强调了有前景的未来研究方向，以解决已确定的局限性，并推进 LLM 驱动的图数据库查询生成。

> Large Language Models (LLMs) are revolutionizing the landscape of Generative Artificial Intelligence (GenAI), with innovative LLM-backed solutions emerging rapidly. However, when applied to database technologies, specifically query generation for graph databases and Knowledge Graphs (KGs), LLMs still face significant challenges. While research on LLM-driven query generation for Structured Query Language (SQL) exists, similar systems for graph databases remain underdeveloped. This paper presents a comparative study addressing the challenge of generating Cypher queries a powerful language for interacting with graph databases using open-access LLMs. We rigorously evaluate several LLM agents (OpenAI ChatGPT 4o, Claude Sonnet 3.5, Google Gemini Pro 1.5, and a locally deployed Llama 3.1 8B) using a designed few-shot learning prompt and Retrieval Augmented Generation (RAG) backed by Chain-of-Thoughts (CoT) reasoning. Our empirical analysis of query generation accuracy reveals that Claude Sonnet 3.5 outperforms its counterparts in this specific domain. Further, we highlight promising future research directions to address the identified limitations and advance LLM-driven query generation for graph databases.

[Arxiv](https://arxiv.org/abs/2411.08449)