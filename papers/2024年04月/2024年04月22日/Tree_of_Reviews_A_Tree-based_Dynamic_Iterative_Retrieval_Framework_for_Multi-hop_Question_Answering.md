# 《评论之树：面向多步骤问答的基于树形动态迭代检索框架》

发布时间：2024年04月22日

`LLM应用` `问答系统` `信息检索`

> Tree of Reviews: A Tree-based Dynamic Iterative Retrieval Framework for Multi-hop Question Answering

# 摘要

> 多跳问答是一项复杂且知识密集的任务。大型语言模型（LLMs）凭借其“思维链”（CoT）逐步解析难题，而检索增强技术有效减少了因知识过时或未知所导致的错误。近期研究将检索增强应用于CoT推理，以应对多跳问答的挑战。但现有链式方法存在两大问题：一是检索到的无关段落可能干扰推理过程；二是链结构中的任何错误都可能引发连锁反应。本文提出了一种新颖的动态检索框架——“评论树”（ToR），其以问题为根节点，其他节点则为检索所得的段落，形成从根节点向外扩展的不同推理路径。该框架能够根据推理路径上的段落动态决定是否发起新搜索、拒绝或接受。相较于现有研究，我们采用树状结构独立处理每个检索段落，避免了无关段落对推理路径的负面影响；同时，推理路径的多样化扩展也降低了单一推理错误对整体的影响。我们在三个不同的多跳问答数据集上进行了实验，ToR在检索和回答生成方面均实现了业界领先的性能。此外，我们还提出了两种基于树的搜索优化策略——修剪和有效扩展，旨在减少时间成本并提升路径扩展的多样性。我们的代码将开放共享。

> Multi-hop question answering is a knowledge-intensive complex problem. Large Language Models (LLMs) use their Chain of Thoughts (CoT) capability to reason complex problems step by step, and retrieval-augmentation can effectively alleviate factual errors caused by outdated and unknown knowledge in LLMs. Recent works have introduced retrieval-augmentation in the CoT reasoning to solve multi-hop question answering. However, these chain methods have the following problems: 1) Retrieved irrelevant paragraphs may mislead the reasoning; 2) An error in the chain structure may lead to a cascade of errors.
  In this paper, we propose a dynamic retrieval framework called Tree of Reviews (ToR), where the root node is the question, and the other nodes are paragraphs from retrieval, extending different reasoning paths from the root node to other nodes. Our framework dynamically decides to initiate a new search, reject, or accept based on the paragraphs on the reasoning paths. Compared to related work, we introduce a tree structure to handle each retrieved paragraph separately, alleviating the misleading effect of irrelevant paragraphs on the reasoning path; the diversity of reasoning path extension reduces the impact of a single reasoning error on the whole. We conducted experiments on three different multi-hop question answering datasets. The results show that compared to the baseline methods, ToR achieves state-of-the-art performance in both retrieval and response generation. In addition, we propose two tree-based search optimization strategies, pruning and effective expansion, to reduce time overhead and increase the diversity of path extension. We will release our code.

[Arxiv](https://arxiv.org/abs/2404.14464)