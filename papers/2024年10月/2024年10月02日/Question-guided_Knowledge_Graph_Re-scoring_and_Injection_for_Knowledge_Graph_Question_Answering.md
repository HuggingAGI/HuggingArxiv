# 问题引导的知识图谱重评与注入，助力知识图谱问答

发布时间：2024年10月02日

`LLM应用` `知识图谱` `问答系统`

> Question-guided Knowledge Graph Re-scoring and Injection for Knowledge Graph Question Answering

# 摘要

> KGQA 通过利用知识图谱中的结构化信息来回答自然语言问题。然而，检索到的子图往往包含干扰信息，影响推理准确性。为此，我们提出了 Q-KGR 方法，消除噪声路径，聚焦相关知识。同时，我们引入了 Knowformer，一种高效参数的方法，将重新评分的知识图谱注入大型语言模型，提升其推理能力。实验证明，我们的方法在多个 KGQA 基准上表现优异。

> Knowledge graph question answering (KGQA) involves answering natural language questions by leveraging structured information stored in a knowledge graph. Typically, KGQA initially retrieve a targeted subgraph from a large-scale knowledge graph, which serves as the basis for reasoning models to address queries. However, the retrieved subgraph inevitably brings distraction information for knowledge utilization, impeding the model's ability to perform accurate reasoning. To address this issue, we propose a Question-guided Knowledge Graph Re-scoring method (Q-KGR) to eliminate noisy pathways for the input question, thereby focusing specifically on pertinent factual knowledge. Moreover, we introduce Knowformer, a parameter-efficient method for injecting the re-scored knowledge graph into large language models to enhance their ability to perform factual reasoning. Extensive experiments on multiple KGQA benchmarks demonstrate the superiority of our method over existing systems.

[Arxiv](https://arxiv.org/abs/2410.01401)