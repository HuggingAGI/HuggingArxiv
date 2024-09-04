# AdaComp：通过自适应预测器实现提取上下文压缩，专为增强检索功能的大型语言模型设计。

发布时间：2024年09月02日

`RAG` `问答系统` `信息检索`

> AdaComp: Extractive Context Compression with Adaptive Predictor for Retrieval-Augmented Large Language Models

# 摘要

> 噪声文档会拖慢RAG的推理速度并增加成本，因此上下文压缩至关重要。现有方法虽能保留关键信息，但可能过度压缩或计算成本高。我们发现，检索器虽能优先展示相关文档，但确切所需文档数量受查询复杂度和检索质量影响。为此，我们提出AdaComp，一种低成本的抽取式压缩方法，它能根据查询复杂度和检索质量自适应调整压缩率。通过构建查询、文档及其压缩率的三元组并训练预测器，AdaComp在多个QA数据集上实现了成本降低与性能保持的平衡。

> Retrieved documents containing noise will hinder RAG from detecting answer clues and make the inference process slow and expensive. Therefore, context compression is necessary to enhance its accuracy and efficiency. Existing context compression methods use extractive or generative models to retain the most query-relevant sentences or apply the information bottleneck theory to preserve sufficient information. However, these methods may face issues such as over-compression or high computational costs. We observe that the retriever often ranks relevant documents at the top, but the exact number of documents needed to answer the query is uncertain due to the impact of query complexity and retrieval quality: complex queries like multi-hop questions may require retaining more documents than simpler queries, and a low-quality retrieval may need to rely on more documents to generate accurate outputs. Therefore, determining the minimum number of required documents (compression rate) is still a challenge for RAG. In this paper, we introduce AdaComp, a low-cost extractive context compression method that adaptively determines the compression rate based on both query complexity and retrieval quality. Specifically, we first annotate the minimum top-k documents necessary for the RAG system to answer the current query as the compression rate and then construct triplets of the query, retrieved documents, and its compression rate. Then, we use this triplet dataset to train a compression-rate predictor. Experiments on three QA datasets and one conversational Muiti-doc QA dataset show that AdaComp significantly reduces inference costs while maintaining performance nearly identical to uncompressed models, achieving a balance between efficiency and performance.

[Arxiv](https://arxiv.org/abs/2409.01579)