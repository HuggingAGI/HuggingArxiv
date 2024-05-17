# 张量收缩路径的优化：贪婪算法与精进成本函数的双重奏

发布时间：2024年05月08日

`LLM理论

这篇论文的摘要主要讨论了在多个领域（包括语言模型）中寻找高效的张量收缩路径的问题，并提出了一种新的方法来改进这一过程。虽然它没有直接涉及Agent或RAG的概念，但它与大型语言模型（LLM）的理论和计算效率有关，因此属于LLM理论分类。这种方法的改进可能会对LLM的计算和应用产生影响，但它本身更多地关注于算法和计算效率的理论层面。` `高性能计算` `量子计算`

> Optimizing Tensor Contraction Paths: A Greedy Algorithm Approach With Improved Cost Functions

# 摘要

> 在模型计数、量子电路、图问题和语言模型等领域，寻找高效的张量收缩路径至关重要。尽管已有如 opt_einsum 的贪心算法和随机贪心算法，以及 cotengra 的贪心算法和超图划分等方法，但它们在寻找有效路径时耗时且资源消耗大。本文提出了一种基于 opt_einsum 贪心算法的新方法，它能更快地计算出高效路径，甚至能解决现代算法无法应对的大型问题。

> Finding efficient tensor contraction paths is essential for a wide range of problems, including model counting, quantum circuits, graph problems, and language models. There exist several approaches to find efficient paths, such as the greedy and random greedy algorithm by Optimized Einsum (opt_einsum), and the greedy algorithm and hypergraph partitioning approach employed in cotengra. However, these algorithms require a lot of computational time and resources to find efficient contraction paths. In this paper, we introduce a novel approach based on the greedy algorithm by opt_einsum that computes efficient contraction paths in less time. Moreover, with our approach, we are even able to compute paths for large problems where modern algorithms fail.

![张量收缩路径的优化：贪婪算法与精进成本函数的双重奏](../../../paper_images/2405.09644/x1.png)

![张量收缩路径的优化：贪婪算法与精进成本函数的双重奏](../../../paper_images/2405.09644/x2.png)

![张量收缩路径的优化：贪婪算法与精进成本函数的双重奏](../../../paper_images/2405.09644/x3.png)

![张量收缩路径的优化：贪婪算法与精进成本函数的双重奏](../../../paper_images/2405.09644/x4.png)

![张量收缩路径的优化：贪婪算法与精进成本函数的双重奏](../../../paper_images/2405.09644/x5.png)

![张量收缩路径的优化：贪婪算法与精进成本函数的双重奏](../../../paper_images/2405.09644/x6.png)

[Arxiv](https://arxiv.org/abs/2405.09644)