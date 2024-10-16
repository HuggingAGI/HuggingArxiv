# 大型语言模型中的因果推理：借助知识图谱的新方法

发布时间：2024年10月15日

`LLM应用` `人工智能` `知识图谱`

> Causal Reasoning in Large Language Models: A Knowledge Graph Approach

# 摘要

> 大型语言模型 (LLM) 通常通过检索语义相似信息或利用结构化提示（如思维链）来提升推理能力，从而提高性能。然而，哪种策略对模型性能影响更大，或是否需要两者结合，仍未明确。本文提出一种基于知识图谱 (KG) 的随机游走推理方法，利用因果关系来解答此问题。实验基于 KG 的常识问答任务，KG 不仅提供相关实体信息，还通过节点连接构建推理结构。结果显示，该方法显著提升了 LLM 的推理能力和性能。更有趣的是，将三个看似无关的句子通过 KG 随机游走推理纳入查询，反而增强了 LLM 性能，这与传统认知相悖。这些发现揭示了因果结构在提示中的重要性，为优化 LLM 性能提供了新视角。

> Large language models (LLMs) typically improve performance by either retrieving semantically similar information, or enhancing reasoning abilities through structured prompts like chain-of-thought. While both strategies are considered crucial, it remains unclear which has a greater impact on model performance or whether a combination of both is necessary. This paper answers this question by proposing a knowledge graph (KG)-based random-walk reasoning approach that leverages causal relationships. We conduct experiments on the commonsense question answering task that is based on a KG. The KG inherently provides both relevant information, such as related entity keywords, and a reasoning structure through the connections between nodes. Experimental results show that the proposed KG-based random-walk reasoning method improves the reasoning ability and performance of LLMs. Interestingly, incorporating three seemingly irrelevant sentences into the query using KG-based random-walk reasoning enhances LLM performance, contrary to conventional wisdom. These findings suggest that integrating causal structures into prompts can significantly improve reasoning capabilities, providing new insights into the role of causality in optimizing LLM performance.

[Arxiv](https://arxiv.org/abs/2410.11588)