# 多跳问答中的分层检索增强生成模型与重新思考机制

发布时间：2024年08月20日

`RAG` `问答系统` `信息检索`

> Hierarchical Retrieval-Augmented Generation Model with Rethink for Multi-hop Question Answering

# 摘要

> 多跳问答（QA）系统需整合多条信息进行复杂推理，但现有系统常遇过时信息、上下文限制及准确性与数量间的权衡难题。为此，我们创新提出HiRAG框架，含分解、定义、检索、过滤、总结五大模块，并采用分层检索策略，融合文档级稀疏与块级密集检索优势。同时，我们改进单候选检索法，并构建索引与档案维基语料库，以应对知识过时与不足。实验显示，HiRAG在多数据集上超越前沿模型，其代码已公开于GitHub。

> Multi-hop Question Answering (QA) necessitates complex reasoning by integrating multiple pieces of information to resolve intricate questions. However, existing QA systems encounter challenges such as outdated information, context window length limitations, and an accuracy-quantity trade-off. To address these issues, we propose a novel framework, the Hierarchical Retrieval-Augmented Generation Model with Rethink (HiRAG), comprising Decomposer, Definer, Retriever, Filter, and Summarizer five key modules. We introduce a new hierarchical retrieval strategy that incorporates both sparse retrieval at the document level and dense retrieval at the chunk level, effectively integrating their strengths. Additionally, we propose a single-candidate retrieval method to mitigate the limitations of multi-candidate retrieval. We also construct two new corpora, Indexed Wikicorpus and Profile Wikicorpus, to address the issues of outdated and insufficient knowledge.
  Our experimental results on four datasets demonstrate that HiRAG outperforms state-of-the-art models across most metrics, and our Indexed Wikicorpus is effective. The code for HiRAG is available at https://github.com/2282588541a/HiRAG

[Arxiv](https://arxiv.org/abs/2408.11875)