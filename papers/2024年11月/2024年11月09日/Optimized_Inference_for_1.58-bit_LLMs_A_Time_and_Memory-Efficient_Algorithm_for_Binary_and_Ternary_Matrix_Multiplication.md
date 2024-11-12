# 针对 1.58 位大型语言模型的优化推理：一种用于二进制和三进制矩阵乘法的时间和内存高效算法

发布时间：2024年11月09日

`LLM应用` `计算机`

> Optimized Inference for 1.58-bit LLMs: A Time and Memory-Efficient Algorithm for Binary and Ternary Matrix Multiplication

# 摘要

> 尽管大型语言模型（LLMs）取得了巨大的成功和通用性，但它们在依赖先进的计算基础设施时存在推理效率低下的问题。为了应对这些挑战并使 LLMs 更易于访问和更具成本效益，在本文中，我们提出了算法来提高具有三值权重矩阵的 1.58 位 LLMs 的推理时间和内存效率。特别关注作为推理瓶颈操作的矩阵乘法，我们观察到，一旦训练完成，模型的权重矩阵不再改变。这使我们能够预处理这些矩阵并创建索引，有助于将存储需求降低一个对数因子，同时实现我们的高效推理算法。具体而言，对于一个 n 乘 n 的权重矩阵，我们的高效算法保证时间复杂度为 O(\frac{n^2}{\log n})，相对于标准的 O(n^2) 向量 - 矩阵乘法有一个对数因子的改进。除了理论分析，我们还进行了广泛的实验来评估我们算法的实际效率。我们的结果证实了该方法在时间和内存方面的优越性，因为我们观察到推理时间最多减少 29 倍，内存使用最多减少 6 倍。

> Despite their tremendous success and versatility, Large Language Models (LLMs) suffer from inference inefficiency while relying on advanced computational infrastructure. To address these challenges and make LLMs more accessible and cost-effective, in this paper, we propose algorithms to improve the inference time and memory efficiency of 1.58-bit LLMs with ternary weight matrices. Particularly focusing on matrix multiplication as the bottle-neck operation of inference, we observe that, once trained, the weight matrices of a model no longer change. This allows us to preprocess these matrices and create indices that help reduce the storage requirements by a logarithmic factor while enabling our efficient inference algorithms. Specifically, for a $n$ by $n$ weight matrix, our efficient algorithm guarantees a time complexity of $O(\frac{n^2}{\log n})$, a logarithmic factor improvement over the standard $O(n^2)$ vector-matrix multiplication. Besides theoretical analysis, we conduct extensive experiments to evaluate the practical efficiency of our algorithms. Our results confirm the superiority of the approach both with respect to time and memory, as we observed a reduction in inference time up to 29x and memory usage up to 6x.

[Arxiv](https://arxiv.org/abs/2411.06360)