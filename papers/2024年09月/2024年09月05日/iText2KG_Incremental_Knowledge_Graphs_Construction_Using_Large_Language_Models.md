# iText2KG：借助大型语言模型实现知识图谱的增量构建

发布时间：2024年09月05日

`LLM应用` `知识图谱` `信息检索`

> iText2KG: Incremental Knowledge Graphs Construction Using Large Language Models

# 摘要

> 大多数数据都是非结构化的，难以提取有价值的信息。自动构建知识图谱（KGs）是解决这一问题的关键，它不仅使数据结构化，便于用户高效搜索，还能促进洞察和推理。传统的自然语言处理方法，如命名实体识别和关系提取，虽在信息检索中起重要作用，但受限于预定义实体类型和监督学习需求。当前研究利用大型语言模型的零-或少量-shot 学习能力，但仍面临未解决和语义重复的实体与关系问题，导致图谱不一致和大量后处理需求。此外，多数方法依赖特定主题。本文提出 iText2KG，一种无需后处理的增量、主题无关的 KG 构建方法。该即插即用、零-shot 方法包含文档提取、增量实体与关系提取及图谱集成与可视化四大模块，适用于多种场景，如科学论文、网站和简历的图谱转换，性能优于现有基线方法。

> Most available data is unstructured, making it challenging to access valuable information. Automatically building Knowledge Graphs (KGs) is crucial for structuring data and making it accessible, allowing users to search for information effectively. KGs also facilitate insights, inference, and reasoning. Traditional NLP methods, such as named entity recognition and relation extraction, are key in information retrieval but face limitations, including the use of predefined entity types and the need for supervised learning. Current research leverages large language models' capabilities, such as zero- or few-shot learning. However, unresolved and semantically duplicated entities and relations still pose challenges, leading to inconsistent graphs and requiring extensive post-processing. Additionally, most approaches are topic-dependent. In this paper, we propose iText2KG, a method for incremental, topic-independent KG construction without post-processing. This plug-and-play, zero-shot method is applicable across a wide range of KG construction scenarios and comprises four modules: Document Distiller, Incremental Entity Extractor, Incremental Relation Extractor, and Graph Integrator and Visualization. Our method demonstrates superior performance compared to baseline methods across three scenarios: converting scientific papers to graphs, websites to graphs, and CVs to graphs.

[Arxiv](https://arxiv.org/abs/2409.03284)