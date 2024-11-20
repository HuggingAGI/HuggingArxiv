# GRS-QA —— 图推理结构化问答的数据集

发布时间：2024年11月01日

`LLM应用` `问答系统` `语言模型`

> GRS-QA -- Graph Reasoning-Structured Question Answering Dataset

# 摘要

> 大型语言模型（LLMs）凭借其出色的推理能力，在多跳问答（M-QA）领域表现出众。然而，内在推理结构对 LLM M-QA 性能的影响尚不明确，主要是因为缺少能提供细粒度推理结构的问答数据集。为填补这一空白，我们推出了图推理结构问答数据集（GRS-QA），它涵盖了问答对的语义上下文和推理结构。不像现有的 M-QA 数据集，其中不同的推理结构相互交织，GRS-QA 通过构建推理图清晰地捕捉到复杂的推理路径，节点代表文本上下文，边代表逻辑流向。这些不同结构的推理图能够对不同推理结构下的 LLM 推理能力进行精细评估。我们的实证分析显示，LLMs 在处理不同推理结构的问题时表现各异。这一发现有利于对比语义来探索文本结构。

> Large Language Models (LLMs) have excelled in multi-hop question-answering (M-QA) due to their advanced reasoning abilities. However, the impact of the inherent reasoning structures on LLM M-QA performance remains unclear, largely due to the absence of QA datasets that provide fine-grained reasoning structures. To address this gap, we introduce the Graph Reasoning-Structured Question Answering Dataset (GRS-QA), which includes both semantic contexts and reasoning structures for QA pairs. Unlike existing M-QA datasets, where different reasoning structures are entangled together, GRS-QA explicitly captures intricate reasoning pathways by constructing reasoning graphs, where nodes represent textual contexts and edges denote logical flows. These reasoning graphs of different structures enable a fine-grained evaluation of LLM reasoning capabilities across various reasoning structures. Our empirical analysis reveals that LLMs perform differently when handling questions with varying reasoning structures. This finding facilitates the exploration of textual structures as compared with semantics.

[Arxiv](https://arxiv.org/abs/2411.00369)