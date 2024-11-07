# 发现数据结构：最近邻搜索及其他

发布时间：2024年11月05日

`其他` `数据结构` `搜索算法`

> Discovering Data Structures: Nearest Neighbor Search and Beyond

# 摘要

> 摘要：我们提出了一个用于端到端学习数据结构的通用框架。我们的框架适应底层数据分布，并对查询和空间复杂度提供细粒度控制。至关重要的是，数据结构是从头开始学习的，不需要仔细的初始化或用候选数据结构/算法播种。我们首先将此框架应用于最近邻搜索问题。在几种设置中，我们能够对学习到的数据结构和查询算法进行逆向工程。对于 1D 最近邻搜索，模型发现了最优分布（不）依赖算法，如二分查找和插值查找的变体。在更高维度中，模型学习到的解决方案在某些情况下类似于 k-d 树，而在其他情况下，它们具有局部敏感哈希的元素。该模型还可以学习高维数据的有用表示，并利用它们设计有效的数据结构。我们还将我们的框架应用于估计数据流频率的问题，并相信它也可能成为新问题的强大发现工具。

> 
Abstract:We propose a general framework for end-to-end learning of data structures. Our framework adapts to the underlying data distribution and provides fine-grained control over query and space complexity. Crucially, the data structure is learned from scratch, and does not require careful initialization or seeding with candidate data structures/algorithms. We first apply this framework to the problem of nearest neighbor search. In several settings, we are able to reverse-engineer the learned data structures and query algorithms. For 1D nearest neighbor search, the model discovers optimal distribution (in)dependent algorithms such as binary search and variants of interpolation search. In higher dimensions, the model learns solutions that resemble k-d trees in some regimes, while in others, they have elements of locality-sensitive hashing. The model can also learn useful representations of high-dimensional data and exploit them to design effective data structures. We also adapt our framework to the problem of estimating frequencies over a data stream, and believe it could also be a powerful discovery tool for new problems.
    

[Arxiv](https://arxiv.org/pdf/2411.03253)