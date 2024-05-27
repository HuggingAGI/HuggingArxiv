# DAGER：大型语言模型的精准梯度反演

发布时间：2024年05月24日

`Agent

理由：这篇论文主要介绍了一种名为DAGER的新算法，该算法能够在联邦学习场景下精确恢复整个文本输入批次。它利用了自注意力层梯度的低秩特性及令牌嵌入的离散性，通过高效的验证过程来确定令牌序列是否属于客户端数据。这种算法的设计和实现涉及到对模型内部机制的深入理解和操作，类似于一个智能Agent的行为，因此将其归类为Agent。此外，虽然论文中涉及到了梯度反转攻击，但主要关注点是新算法的设计和应用，而不是LLM的理论研究或应用开发，因此不适合归类为LLM理论或LLM应用。同时，由于论文内容与RAG（Retrieval-Augmented Generation）无关，也不应归类为RAG。` `联邦学习` `数据隐私`

> DAGER: Exact Gradient Inversion for Large Language Models

# 摘要

> 联邦学习通过聚合本地计算的梯度，实现了无需共享私人数据的协作训练。但已有研究显示，服务器可通过梯度反转攻击恢复数据，尽管这在图像处理中效果显著，但在文本领域仅能近似重建小批量短序列。本研究首次提出 DAGER 算法，能精确恢复整个文本输入批次。DAGER 利用自注意力层梯度的低秩特性及令牌嵌入的离散性，高效验证令牌序列是否属于客户端数据。在诚实但好奇的场景下，无需数据先验知识，DAGER 能精确恢复完整批次，适用于编码器和解码器架构，分别采用穷举启发式搜索和贪婪策略。我们提供了 DAGER 的 GPU 高效实现，并通过实验验证，它能恢复高达 128 大小的完整批次，在速度、可扩展性和重建质量上均超越以往攻击，ROUGE-1/2 得分超过 0.99。

> Federated learning works by aggregating locally computed gradients from multiple clients, thus enabling collaborative training without sharing private client data. However, prior work has shown that the data can actually be recovered by the server using so-called gradient inversion attacks. While these attacks perform well when applied on images, they are limited in the text domain and only permit approximate reconstruction of small batches and short input sequences. In this work, we propose DAGER, the first algorithm to recover whole batches of input text exactly. DAGER leverages the low-rank structure of self-attention layer gradients and the discrete nature of token embeddings to efficiently check if a given token sequence is part of the client data. We use this check to exactly recover full batches in the honest-but-curious setting without any prior on the data for both encoder- and decoder-based architectures using exhaustive heuristic search and a greedy approach, respectively. We provide an efficient GPU implementation of DAGER and show experimentally that it recovers full batches of size up to 128 on large language models (LLMs), beating prior attacks in speed (20x at same batch size), scalability (10x larger batches), and reconstruction quality (ROUGE-1/2 > 0.99).

[Arxiv](https://arxiv.org/abs/2405.15586)