# 重探基于邻近图的近似最近邻搜索索引构建

发布时间：2024年10月02日

`RAG` `信息检索` `大数据`

> Revisiting the Index Construction of Proximity Graph-Based Approximate Nearest Neighbor Search

# 摘要

> 近邻图 (PG) 在高维数据上的 $k$-近似最近邻 ($k$-ANN) 搜索中表现出色，成为信息检索和检索增强生成 (RAG) 等领域的关键技术。然而，尽管 PG 方法在 $k$-ANN 搜索中表现优异，但其构建成本与数据点数量呈超线性关系，限制了其在大数据环境中的应用。本文旨在提升 PG 方法的构建速度，同时保持其 $k$-ANN 搜索性能。为此，我们重新审视了两种主流 PG 方法：相对邻域图 (RNG) 和可导航小世界图 (NSWG)，并发现了构建效率的问题。我们提出了一种新的构建框架，通过创新的边选择剪枝策略，加速了 RNG 的构建，同时保持了其 $k$-ANN 搜索性能。随后，我们将此框架应用于 NSWG，进一步提升了构建效率和 $k$-ANN 搜索性能。实验结果显示，该框架显著降低了 PG 构建成本，实现了高达 5.6 倍的加速，且不影响 $k$-ANN 搜索性能。

> Proximity graphs (PG) have gained increasing popularity as the state-of-the-art (SOTA) solutions to $k$-approximate nearest neighbor ($k$-ANN) search on high-dimensional data, which serves as a fundamental function in various fields, e.g. information retrieval and retrieval-augmented generation~(RAG). Although PG-based approaches have the best $k$-ANN search performance, their index construction cost is superlinear to the number of points, since they have to identify close neighbors for each point to establish the edges. Such superlinear cost substantially limits their scalability in the era of big data. Hence, the goal of this paper is to accelerate the construction of PG-based methods without compromising their $k$-ANN search performance.
  To achieve this goal, two mainstream categories of PG are revisited: relative neighborhood graph (RNG) and navigable small world graph (NSWG). By revisiting their construction process, we find the issues of construction efficiency. To address these issues, we propose a new construction framework with a novel pruning strategy for edge selection, which accelerates RNG construction while keeping its $k$-ANN search performance. Then, we integrate this framework into NSWG construction to enhance both the construction efficiency and $k$-ANN search performance. Moreover, extensive experiments are conducted to validate our construction framework for both RNG and NSWG. The results demonstrate that it significantly reduces the PG construction cost, achieving up to 5.6x speedup while not compromising the $k$-ANN search performance.

[Arxiv](https://arxiv.org/abs/2410.01231)