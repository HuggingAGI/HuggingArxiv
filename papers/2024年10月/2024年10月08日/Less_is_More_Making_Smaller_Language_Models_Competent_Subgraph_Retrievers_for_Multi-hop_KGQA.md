# 小而精：让小型语言模型也能胜任多跳 KGQA 的子图检索任务

发布时间：2024年10月08日

`RAG` `知识图谱`

> Less is More: Making Smaller Language Models Competent Subgraph Retrievers for Multi-hop KGQA

# 摘要

> RAG 广泛用于将外部知识注入 LLM。最新研究表明，知识图谱 (KG) 是 LLM 的重要知识来源。本文将子图检索任务建模为小型语言模型处理的条件生成任务，仅用 220M 参数就实现了与 7B 参数模型相当的检索性能，证明了小型模型的潜力。结合 LLM 阅读器后，3B 模型在 WebQSP 和 CWQ 基准测试中创下新纪录。模型和数据即将上线：https://github.com/hwy9855/GSR。

> Retrieval-Augmented Generation (RAG) is widely used to inject external non-parametric knowledge into large language models (LLMs). Recent works suggest that Knowledge Graphs (KGs) contain valuable external knowledge for LLMs. Retrieving information from KGs differs from extracting it from document sets. Most existing approaches seek to directly retrieve relevant subgraphs, thereby eliminating the need for extensive SPARQL annotations, traditionally required by semantic parsing methods. In this paper, we model the subgraph retrieval task as a conditional generation task handled by small language models. Specifically, we define a subgraph identifier as a sequence of relations, each represented as a special token stored in the language models. Our base generative subgraph retrieval model, consisting of only 220M parameters, achieves competitive retrieval performance compared to state-of-the-art models relying on 7B parameters, demonstrating that small language models are capable of performing the subgraph retrieval task. Furthermore, our largest 3B model, when plugged with an LLM reader, sets new SOTA end-to-end performance on both the WebQSP and CWQ benchmarks. Our model and data will be made available online: https://github.com/hwy9855/GSR.

[Arxiv](https://arxiv.org/abs/2410.06121)