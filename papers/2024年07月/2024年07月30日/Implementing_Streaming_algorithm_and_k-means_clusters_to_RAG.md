# 将流算法与 k-means 聚类技术应用于 RAG

发布时间：2024年07月30日

`RAG` `信息检索` `数据处理`

> Implementing Streaming algorithm and k-means clusters to RAG

# 摘要

> RAG 在信息检索领域大放异彩，得益于其构建的外部知识库。然而，庞大的数据库也带来了内存消耗过大的问题，尤其在处理海量流数据时，无法及时更新索引。为此，我们创新性地结合流算法与 k-means 聚类，提出了一种既能节省内存又能保持高准确性的新 RAG 方法。该方法通过流算法动态更新索引，降低内存占用，同时利用 k-means 聚类缩短查询时间。实验对比表明，我们的方法在处理大规模流数据时，性能优于传统 RAG，实现了内存与准确性的双赢。

> Retrieval-augmented generation (RAG) has achieved great success in information retrieval to assist large models because it builds an external knowledge database. However, it also has many problems: it consumes a lot of memory because of the huge database. When faced with massive streaming data, it is unable to update the established index database in time. To save the memory of building the database and maintain accuracy simultaneously, we proposed a new approach combining a streaming algorithm and k-means cluster with RAG. Our approach applies a streaming algorithm to update the index and reduce memory consumption. Then use the k-means algorithm to cluster documents with high similarities together, the query time will be shortened by doing this. We conducted comparative experiments on four methods, and the results show that RAG with streaming algorithm and k-means cluster performs well in accuracy and memory. For massive streaming data, we find that our method behaves better than traditional RAG

[Arxiv](https://arxiv.org/abs/2407.21300)