# 动态数据集中的递归抽象检索

发布时间：2024年10月02日

`RAG` `信息检索` `数据管理`

> Recursive Abstractive Processing for Retrieval in Dynamic Datasets

# 摘要

> 最近，增强型检索模型通过递归嵌入、聚类和总结，在检索到的文本块上构建分层结构，从而提升了基本方法。然而，这种方法在动态数据集上存在局限，因为文档的增删会使分层表示的更新变得复杂。我们提出了一种新算法，高效维护动态数据集中的递归-抽象树结构，同时不影响性能。此外，我们引入了一种查询焦点递归抽象处理的后检索方法，显著提升上下文质量。我们的方法作为与任何检索算法兼容的黑箱后检索层，克服了其他方法的局限。这两种算法在真实世界数据集上的广泛实验中得到了验证，展示了它们在处理动态数据和提高检索性能方面的有效性。

> Recent retrieval-augmented models enhance basic methods by building a hierarchical structure over retrieved text chunks through recursive embedding, clustering, and summarization. The most relevant information is then retrieved from both the original text and generated summaries. However, such approaches face limitations with dynamic datasets, where adding or removing documents over time complicates the updating of hierarchical representations formed through clustering. We propose a new algorithm to efficiently maintain the recursive-abstractive tree structure in dynamic datasets, without compromising performance. Additionally, we introduce a novel post-retrieval method that applies query-focused recursive abstractive processing to substantially improve context quality. Our method overcomes the limitations of other approaches by functioning as a black-box post-retrieval layer compatible with any retrieval algorithm. Both algorithms are validated through extensive experiments on real-world datasets, demonstrating their effectiveness in handling dynamic data and improving retrieval performance.

[Arxiv](https://arxiv.org/abs/2410.01736)