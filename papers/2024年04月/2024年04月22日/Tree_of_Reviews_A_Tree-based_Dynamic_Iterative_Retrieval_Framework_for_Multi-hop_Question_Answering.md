# 《评论之树：构建基于树状结构的动态迭代检索系统，以应对多步骤问答挑战》

发布时间：2024年04月22日

`LLM应用` `问答系统` `信息检索`

> Tree of Reviews: A Tree-based Dynamic Iterative Retrieval Framework for Multi-hop Question Answering

# 摘要

> 多跳问答是一项复杂的知识密集型问题。大型语言模型（LLMs）通过其“思维链”（CoT）功能逐步推理解决复杂问题，而检索增强技术能有效减少LLMs因知识过时或未知而产生的事实性错误。近期研究将检索增强技术应用于CoT推理，以应对多跳问答的挑战。但现有链式方法存在两大问题：一是检索到的无关段落可能干扰推理过程；二是链结构中的错误可能引发连锁反应。本文提出了一种名为“评论树”（ToR）的动态检索框架，根节点代表问题，其他节点为检索所得的段落，它们从根节点向外延伸，形成多条独立的推理路径。该框架能够根据推理路径上的段落动态地决定是否发起新的搜索、拒绝或接受。相较于先前研究，我们采用树状结构对每个检索段落进行独立处理，减少了无关段落对推理路径的干扰；同时，推理路径的多样化扩展也降低了单一推理错误对整体结果的影响。我们在三个不同的多跳问答数据集上进行了实验，ToR在检索和回答生成方面均达到了最先进的性能。此外，我们还提出了两种基于树的搜索优化策略——修剪和有效扩展，旨在减少时间开销并提升路径扩展的多样性。我们将公开我们的代码。

> Multi-hop question answering is a knowledge-intensive complex problem. Large Language Models (LLMs) use their Chain of Thoughts (CoT) capability to reason complex problems step by step, and retrieval-augmentation can effectively alleviate factual errors caused by outdated and unknown knowledge in LLMs. Recent works have introduced retrieval-augmentation in the CoT reasoning to solve multi-hop question answering. However, these chain methods have the following problems: 1) Retrieved irrelevant paragraphs may mislead the reasoning; 2) An error in the chain structure may lead to a cascade of errors.
  In this paper, we propose a dynamic retrieval framework called Tree of Reviews (ToR), where the root node is the question, and the other nodes are paragraphs from retrieval, extending different reasoning paths from the root node to other nodes. Our framework dynamically decides to initiate a new search, reject, or accept based on the paragraphs on the reasoning paths. Compared to related work, we introduce a tree structure to handle each retrieved paragraph separately, alleviating the misleading effect of irrelevant paragraphs on the reasoning path; the diversity of reasoning path extension reduces the impact of a single reasoning error on the whole. We conducted experiments on three different multi-hop question answering datasets. The results show that compared to the baseline methods, ToR achieves state-of-the-art performance in both retrieval and response generation. In addition, we propose two tree-based search optimization strategies, pruning and effective expansion, to reduce time overhead and increase the diversity of path extension. We will release our code.

[Arxiv](https://arxiv.org/abs/2404.14464)