# LEGO-GraphRAG：用于设计空间探索的基于图的检索增强生成之模块化

发布时间：2024年11月06日

`RAG` `语言模型` `知识检索`

> LEGO-GraphRAG: Modularizing Graph-based Retrieval-Augmented Generation for Design Space Exploration

# 摘要

> GraphRAG 借助嵌入知识的图来增强大型语言模型（LLMs）的推理能力，从而应对了检索增强生成（RAG）中的重大挑战。尽管前景可观，但当前 GraphRAG 领域缺少一个能对基于图的知识检索流程进行精细分解的统一框架。而且，检索流程中的现有方案既未得到系统分类，也未得到评估。在本文中，我们推出了 LEGO-GraphRAG，这是一个把 GraphRAG 的检索流程拆解为三个相互关联的模块的模块化框架，分别是：子图提取、路径过滤和路径优化。我们对每个模块相关的算法和神经网络（NN）模型进行了系统的总结与分类，让人们对 GraphRAG 实例的设计空间有了更清晰的认识。此外，我们还明确了关键的设计因素，比如图形耦合和计算成本，它们会影响 GraphRAG 实现的效果。通过大量的实证研究，我们运用具有代表性的方案选择构建了高品质的 GraphRAG 实例，并剖析了它们对检索和推理性能的作用。我们的研究成果为优化 GraphRAG 实例设计提供了重要的思路，最终有助于更精准和贴合语境的 LLM 应用的推进。

> GraphRAG addresses significant challenges in Retrieval-Augmented Generation (RAG) by leveraging graphs with embedded knowledge to enhance the reasoning capabilities of Large Language Models (LLMs). Despite its promising potential, the GraphRAG community currently lacks a unified framework for fine-grained decomposition of the graph-based knowledge retrieval process. Furthermore, there is no systematic categorization or evaluation of existing solutions within the retrieval process. In this paper, we present LEGO-GraphRAG, a modular framework that decomposes the retrieval process of GraphRAG into three interconnected modules: subgraph-extraction, path-filtering, and path-refinement. We systematically summarize and classify the algorithms and neural network (NN) models relevant to each module, providing a clearer understanding of the design space for GraphRAG instances. Additionally, we identify key design factors, such as Graph Coupling and Computational Cost, that influence the effectiveness of GraphRAG implementations. Through extensive empirical studies, we construct high-quality GraphRAG instances using a representative selection of solutions and analyze their impact on retrieval and reasoning performance. Our findings offer critical insights into optimizing GraphRAG instance design, ultimately contributing to the advancement of more accurate and contextually relevant LLM applications.

[Arxiv](https://arxiv.org/abs/2411.05844)