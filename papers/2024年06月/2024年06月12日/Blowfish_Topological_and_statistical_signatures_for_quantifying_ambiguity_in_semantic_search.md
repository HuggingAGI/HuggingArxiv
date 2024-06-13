# Blowfish：揭示语义搜索模糊性的拓扑与统计特征

发布时间：2024年06月12日

`RAG

理由：这篇论文主要关注句子嵌入中的模糊性及其在RAG（Retrieval-Augmented Generation）系统中的应用，特别是在向量搜索、排名和解释方面的潜力。RAG系统是一种结合了检索和生成模型的方法，用于提高语言模型的性能。论文通过实验探讨了模糊性的特征，并提出了一种新的语义相似性评分策略，这些都是RAG系统中的关键技术。因此，这篇论文最适合归类为RAG。` `信息检索`

> Blowfish: Topological and statistical signatures for quantifying ambiguity in semantic search

# 摘要

> 本研究揭示了句子嵌入中模糊性的拓扑特征，这些特征在向量搜索和RAG系统中具有排名和解释的潜力。我们定义了模糊性，并通过实验将数据集细分为3、5、10行的块，用作查询和答案集，以排除干扰因素，测试模糊性特征。结果表明，模糊查询（10行对3行）与清晰查询（5行对10行）在特征分布上存在差异。我们探讨了这些结果，涉及流形复杂度的增加和不连续子流形的近似。最后，我们提出了一种基于这些发现的新语义相似性评分策略。

> This works reports evidence for the topological signatures of ambiguity in sentence embeddings that could be leveraged for ranking and/or explanation purposes in the context of vector search and Retrieval Augmented Generation (RAG) systems. We proposed a working definition of ambiguity and designed an experiment where we have broken down a proprietary dataset into collections of chunks of varying size - 3, 5, and 10 lines and used the different collections successively as queries and answers sets. It allowed us to test the signatures of ambiguity with removal of confounding factors. Our results show that proxy ambiguous queries (size 10 queries against size 3 documents) display different distributions of homologies 0 and 1 based features than proxy clear queries (size 5 queries against size 10 documents). We then discuss those results in terms increased manifold complexity and/or approximately discontinuous embedding submanifolds. Finally we propose a strategy to leverage those findings as a new scoring strategy of semantic similarities.

![Blowfish：揭示语义搜索模糊性的拓扑与统计特征](../../../paper_images/2406.07990/blowfish_package_logo.jpg)

![Blowfish：揭示语义搜索模糊性的拓扑与统计特征](../../../paper_images/2406.07990/exp_diagram.png)

![Blowfish：揭示语义搜索模糊性的拓扑与统计特征](../../../paper_images/2406.07990/homologies_plots.png)

![Blowfish：揭示语义搜索模糊性的拓扑与统计特征](../../../paper_images/2406.07990/homologies_with_scale.png)

![Blowfish：揭示语义搜索模糊性的拓扑与统计特征](../../../paper_images/2406.07990/h0h1_correlation.png)

![Blowfish：揭示语义搜索模糊性的拓扑与统计特征](../../../paper_images/2406.07990/homology1_anisotropy.png)

![Blowfish：揭示语义搜索模糊性的拓扑与统计特征](../../../paper_images/2406.07990/nearest_neighbours_distributions.png)

![Blowfish：揭示语义搜索模糊性的拓扑与统计特征](../../../paper_images/2406.07990/toy_model_W1H0_3clusters.png)

![Blowfish：揭示语义搜索模糊性的拓扑与统计特征](../../../paper_images/2406.07990/toy_model_W1H0_Allclusters.png)

[Arxiv](https://arxiv.org/abs/2406.07990)