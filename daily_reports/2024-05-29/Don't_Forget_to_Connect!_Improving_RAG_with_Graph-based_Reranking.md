# 别忘了连线！利用图结构重新排序提升 RAG 性能
发布时间：2024年05月28日

`RAG`
> Don't Forget to Connect! Improving RAG with Graph-based Reranking
>
> Retrieval Augmented Generation (RAG) 通过结合现有文档的上下文，显著提升了大型语言模型 (LLM) 的响应质量。然而，当文档仅提供部分信息或与问题上下文的关联不明显时，RAG 的表现如何？我们又该如何理解文档间的关联？本研究旨在解答这些关于 RAG 生成的关键问题。我们提出了 G-RAG，一种基于图神经网络 (GNNs) 的重新排序机制，它位于 RAG 的检索器和阅读器之间，能够结合文档间的联系和语义信息（通过抽象意义表示图），为 RAG 提供更精准的上下文排序。G-RAG 不仅在性能上超越了现有技术，而且计算成本更低。我们还评估了 PaLM 2 作为重新排序器的性能，发现其表现远不如 G-RAG，这进一步凸显了在大型语言模型中，重新排序对于 RAG 的重要性。
>
> https://arxiv.org/abs/2405.18414

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.18414/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.18414/nq_num_node_train.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.18414/nq_num_edge_train.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.18414/nq_num_node_dev.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.18414/nq_num_edge_dev.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.18414/nq_num_node_test.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.18414/nq_num_edge_test.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.18414/tqa_num_node_train.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.18414/tqa_num_edge_train.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.18414/tqa_num_node_dev.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.18414/tqa_num_edge_dev.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.18414/tqa_num_node_test.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.18414/tqa_num_edge_test.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.18414/nq_num_pos_path_train.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.18414/nq_num_neg_path_train.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.18414/tqa_num_pos_path_train.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.18414/tqa_num_neg_path_train.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.18414/diagram.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.18414/x2.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2405.18414](https://arxiv.org/abs/2405.18414)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886