# 在不断变化的环境中，结合知识图谱的LLM多跳问答技术

发布时间：2024年08月28日

`LLM应用` `知识图谱` `问答系统`

> LLM-Based Multi-Hop Question Answering with Knowledge Graph Integration in Evolving Environments

# 摘要

> 随着大型语言模型中信息的迅速过时，我们开发了多种技术来整合新事实。然而，现有知识编辑技术在处理复杂的多跳问题时仍显不足，这些问题需要精确的事实识别和连续的逻辑推理，尤其是在频繁更新事实的情况下。为此，我们提出了基于图记忆的大型语言模型编辑方法 (GMeLLo)，它巧妙地将知识图谱的结构化知识表示与语言模型的灵活性结合，不仅用于问答，还能将自然语言转换为结构化查询，实现与知识图谱的高效互动，支持快速更新和精准的多跳推理。实验表明，GMeLLo 在多跳问答基准 MQuAKE 上大幅领先现有技术，特别是在需要大量知识更新的场景中。

> The rapid obsolescence of information in Large Language Models (LLMs) has driven the development of various techniques to incorporate new facts. However, existing methods for knowledge editing still face difficulties with multi-hop questions that require accurate fact identification and sequential logical reasoning, particularly among numerous fact updates. To tackle these challenges, this paper introduces Graph Memory-based Editing for Large Language Models (GMeLLo), a straitforward and effective method that merges the explicit knowledge representation of Knowledge Graphs (KGs) with the linguistic flexibility of LLMs. Beyond merely leveraging LLMs for question answering, GMeLLo employs these models to convert free-form language into structured queries and fact triples, facilitating seamless interaction with KGs for rapid updates and precise multi-hop reasoning. Our results show that GMeLLo significantly surpasses current state-of-the-art knowledge editing methods in the multi-hop question answering benchmark, MQuAKE, especially in scenarios with extensive knowledge edits.

[Arxiv](https://arxiv.org/abs/2408.15903)