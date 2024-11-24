# 简单有效：图和大型语言模型于基于知识图谱的检索增强生成所起的作用

发布时间：2024年10月28日

`RAG` `知识图谱` `语言模型`

> Simple is Effective: The Roles of Graphs and Large Language Models in Knowledge-Graph-Based Retrieval-Augmented Generation

# 摘要

> 大型语言模型（LLMs）具备强大的推理能力，不过也存在诸如产生幻觉、知识陈旧等局限。基于知识图谱（KG）的检索增强生成（RAG），将LLM的输出建立在KG的结构化外部知识基础上，从而化解这些难题。然而，当下基于KG的RAG框架在为LLM确定适量相关图形信息时，仍难以在检索效果和效率之间实现最佳平衡。我们推出SubgraphRAG，对基于KG的RAG框架予以拓展，它能检索子图，并借助LLM进行推理和答案预测。我们的方法开创性地将轻量级多层感知器与并行三元组评分机制相融合，实现了高效且灵活的子图检索，同时对方向结构距离进行编码，提升了检索效果。所检索子图的大小能够灵活调节，以契合查询需求和下游LLM的能力。这一设计在模型复杂度和推理能力之间达成平衡，促成了可扩展且通用的检索流程。尤为值得一提的是，基于我们检索的子图，像Llama3.1-8B-Instruct这类较小的LLM能给出具备可解释推理的出色结果，而像GPT-4o这样的大型模型与以往基线相比达到了最先进的精度——且均无需微调。在WebQSP和CWQ基准上的大量评估表明，SubgraphRAG在效率、准确性和可靠性方面表现出色，减少了幻觉，增强了响应基础。

> Large Language Models (LLMs) demonstrate strong reasoning abilities but face limitations such as hallucinations and outdated knowledge. Knowledge Graph (KG)-based Retrieval-Augmented Generation (RAG) addresses these issues by grounding LLM outputs in structured external knowledge from KGs. However, current KG-based RAG frameworks still struggle to optimize the trade-off between retrieval effectiveness and efficiency in identifying a suitable amount of relevant graph information for the LLM to digest. We introduce SubgraphRAG, extending the KG-based RAG framework that retrieves subgraphs and leverages LLMs for reasoning and answer prediction. Our approach innovatively integrates a lightweight multilayer perceptron with a parallel triple-scoring mechanism for efficient and flexible subgraph retrieval while encoding directional structural distances to enhance retrieval effectiveness. The size of retrieved subgraphs can be flexibly adjusted to match the query's need and the downstream LLM's capabilities. This design strikes a balance between model complexity and reasoning power, enabling scalable and generalizable retrieval processes. Notably, based on our retrieved subgraphs, smaller LLMs like Llama3.1-8B-Instruct deliver competitive results with explainable reasoning, while larger models like GPT-4o achieve state-of-the-art accuracy compared with previous baselines -- all without fine-tuning. Extensive evaluations on the WebQSP and CWQ benchmarks highlight SubgraphRAG's strengths in efficiency, accuracy, and reliability by reducing hallucinations and improving response grounding.

[Arxiv](https://arxiv.org/abs/2410.20724)