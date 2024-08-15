# WeKnow-RAG：融合网络搜索与知识图谱，实现检索增强生成的自适应策略

发布时间：2024年08月14日

`RAG` `人工智能` `知识图谱`

> WeKnow-RAG: An Adaptive Approach for Retrieval-Augmented Generation Integrating Web Search and Knowledge Graphs

# 摘要

> 大型语言模型（LLM）在推动智能代理发展方面功不可没，被视为通往人工通用智能（AGI）的关键路径。但它们常生成不实信息，甚至“幻影”内容，严重威胁其可靠性，限制了实际应用。为此，我们创新提出WeKnow-RAG方法，融合网络搜索与知识图谱，构建“检索增强生成”系统，提升LLM响应的精准与可信。通过特定领域知识图谱与多阶段检索技术，我们优化了事实信息与复杂推理任务的表现，并巧妙平衡了检索效率与准确性。此外，引入自我评估机制，确保LLM生成答案的可靠性。实践证明，我们的方法在众多实验与应用中表现卓越。

> Large Language Models (LLMs) have greatly contributed to the development of adaptive intelligent agents and are positioned as an important way to achieve Artificial General Intelligence (AGI). However, LLMs are prone to produce factually incorrect information and often produce "phantom" content that undermines their reliability, which poses a serious challenge for their deployment in real-world scenarios. Enhancing LLMs by combining external databases and information retrieval mechanisms is an effective path. To address the above challenges, we propose a new approach called WeKnow-RAG, which integrates Web search and Knowledge Graphs into a "Retrieval-Augmented Generation (RAG)" system. First, the accuracy and reliability of LLM responses are improved by combining the structured representation of Knowledge Graphs with the flexibility of dense vector retrieval. WeKnow-RAG then utilizes domain-specific knowledge graphs to satisfy a variety of queries and domains, thereby improving performance on factual information and complex reasoning tasks by employing multi-stage web page retrieval techniques using both sparse and dense retrieval methods. Our approach effectively balances the efficiency and accuracy of information retrieval, thus improving the overall retrieval process. Finally, we also integrate a self-assessment mechanism for the LLM to evaluate the trustworthiness of the answers it generates. Our approach proves its outstanding effectiveness in a wide range of offline experiments and online submissions.

[Arxiv](https://arxiv.org/abs/2408.07611)