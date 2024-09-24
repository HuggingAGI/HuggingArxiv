# 何时提问 -- 连接大型语言模型与数据

发布时间：2024年09月10日

`RAG` `数据分析` `人工智能`

> Knowing When to Ask -- Bridging Large Language Models and Data

# 摘要

> 大型语言模型 (LLM) 在处理数值和统计数据查询时，常常出现事实错误。本文提出了一种通过与 Data Commons 集成来提升 LLM 准确性的方法。Data Commons 是一个包含联合国、CDC 等权威机构提供的公共统计数据的开源库。我们探索了两种方法：RIG 和 RAG。前者训练 LLM 生成自然语言查询以检索数据，后者则从 Data Commons 获取相关数据表来增强 LLM 的提示。通过多样化的查询测试，我们证明了这些方法能有效提升 LLM 输出的事实准确性。这项研究为构建基于可验证统计数据、具备复杂事实推理能力的更可信 LLM 奠定了基础。

> Large Language Models (LLMs) are prone to generating factually incorrect information when responding to queries that involve numerical and statistical data or other timely facts. In this paper, we present an approach for enhancing the accuracy of LLMs by integrating them with Data Commons, a vast, open-source repository of public statistics from trusted organizations like the United Nations (UN), Center for Disease Control and Prevention (CDC) and global census bureaus. We explore two primary methods: Retrieval Interleaved Generation (RIG), where the LLM is trained to produce natural language queries to retrieve data from Data Commons, and Retrieval Augmented Generation (RAG), where relevant data tables are fetched from Data Commons and used to augment the LLM's prompt. We evaluate these methods on a diverse set of queries, demonstrating their effectiveness in improving the factual accuracy of LLM outputs. Our work represents an early step towards building more trustworthy and reliable LLMs that are grounded in verifiable statistical data and capable of complex factual reasoning.

[Arxiv](https://arxiv.org/abs/2409.13741)