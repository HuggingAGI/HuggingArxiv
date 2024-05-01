# 利用大型语言模型，实现在知识图谱上的多步推理问答。

发布时间：2024年04月29日

`LLM应用` `知识图谱` `问答系统`

> Multi-hop Question Answering over Knowledge Graphs using Large Language Models

# 摘要

> 知识图谱（KGs）是结构化的海量数据集，它们构成了庞大的知识库（KB），每个节点代表一个核心实体，实体间的关系则以类型化的边来表示。要从KB中提取信息，自然语言查询需要从特定节点出发，沿着KG的多条边进行推理，以找到正确的答案节点集。在KG上的问答传统方法包括：（a）语义解析（SP），通过节点和边的嵌入生成逻辑形式（如S表达式、SPARQL查询等），然后在这些表示上进行推理，或调整语言模型以直接生成最终答案；（b）基于信息检索的方法，它通过顺序提取实体和关系来实现。本研究评估了大型语言模型（LLMs）在处理涉及多跳推理的KG问答任务上的能力。我们发现，根据不同KG的规模和特点，我们需要采取不同的策略来提取并向LLM提供相关信息，因为每个LLM都有一个固定的上下文窗口。我们在六个KG上进行了评估，包括有和没有特定子图的示例，结果表明，无论是基于信息检索（IR）还是语义解析（SP）的方法，LLMs都能采纳并展现出极其有竞争力的性能。

> Knowledge graphs (KGs) are large datasets with specific structures representing large knowledge bases (KB) where each node represents a key entity and relations amongst them are typed edges. Natural language queries formed to extract information from a KB entail starting from specific nodes and reasoning over multiple edges of the corresponding KG to arrive at the correct set of answer nodes. Traditional approaches of question answering on KG are based on (a) semantic parsing (SP), where a logical form (e.g., S-expression, SPARQL query, etc.) is generated using node and edge embeddings and then reasoning over these representations or tuning language models to generate the final answer directly, or (b) information-retrieval based that works by extracting entities and relations sequentially. In this work, we evaluate the capability of (LLMs) to answer questions over KG that involve multiple hops. We show that depending upon the size and nature of the KG we need different approaches to extract and feed the relevant information to an LLM since every LLM comes with a fixed context window. We evaluate our approach on six KGs with and without the availability of example-specific sub-graphs and show that both the IR and SP-based methods can be adopted by LLMs resulting in an extremely competitive performance.

[Arxiv](https://arxiv.org/abs/2404.19234)