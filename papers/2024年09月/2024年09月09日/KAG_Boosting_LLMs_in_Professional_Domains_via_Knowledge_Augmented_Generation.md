# KAG：借助知识增强生成技术，提升大型语言模型在专业领域的表现。

发布时间：2024年09月09日

`RAG` `电子政务`

> KAG: Boosting LLMs in Professional Domains via Knowledge Augmented Generation

# 摘要

> 新推出的检索增强生成 (RAG) 技术虽能高效构建领域应用，但受限于模糊检索、通用语言模型的“幻觉”问题及复杂系统中的级联损失，专业知识服务效果受阻。在科学计算、医学和法律等领域，知识精准、信息完整及规则逻辑严密尤为关键。为此，我们推出知识增强生成 (KAG) 框架，通过双向增强大型语言模型 (LLM) 和知识图谱 (KG)，提升生成与推理能力，涵盖五大关键增强：LLM 友好的知识语义表示、知识图谱与原始块的相互索引、逻辑形式引导的混合推理、基于语义推理的知识对齐及 KAG 模型。多跳问答测试显示，KAG 显著超越现有 RAG 方法，F1 提升 19.6% 至 33.4%。应用于蚂蚁集团的电子政务与电子健康问答，专业性大幅提升。即将在开源 KG 引擎 OpenSPG 上原生支持 KAG，助力开发者轻松构建严谨知识决策或便捷信息检索服务。

> The recently developed retrieval-augmented generation (RAG) technology enables the efficient construction of domain-specific applications. However, it faces limitations due to fuzzy retrieval processes, the "hallucination" problem of understanding and reasoning capabilities of general language models, and cascading losses in complex systems. These challenges hinder the effectiveness of specialized knowledge services. However, in scenarios such as scientific computing, medicine, and law, the accuracy of knowledge, the completeness of information, and the logical rigor of rules, time, and values are particularly critical. We Introduce professional domain knowledge service framework: Knowledge Augmented Generation(KAG) to improve generation and reasoning performance by bidirectionally enhancing large language model(LLM)s and knowledge graph(KG)s, including five key enhancements: 1) LLM-friendly knowledge semantic representation, 2) mutual indexing between knowledge graph and original chunks, 3) logicalform-guided hybrid reasoning and solving, 4) Knowledge alignment based on semantic reasoning, 5) Model for KAG. We compared KAG with existing RAG methods in multi-hop question answering. The results show that KAG performs significantly better than the state-of-the-art methods, with a relative improvement from 19.6% to 33.4% in F1. We apply KAG to two professional knowledge Q&A tasks of Ant Group, including E-Goverment Q&A and E-Health Q&A, and has achieved significant improvement in professionalism compared with NaiveRAG. We will soon natively support KAG on the open source KG engine OpenSPG, allowing developers to more easily build rigorous knowledge decision-making or convenient information retrieval services.

[Arxiv](https://arxiv.org/abs/2409.13731)