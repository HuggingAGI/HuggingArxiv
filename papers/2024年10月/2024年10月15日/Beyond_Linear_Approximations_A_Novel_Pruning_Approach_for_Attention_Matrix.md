# 突破线性限制：探索注意力矩阵的新剪枝策略

发布时间：2024年10月15日

`LLM理论` `边缘计算` `人工智能`

> Beyond Linear Approximations: A Novel Pruning Approach for Attention Matrix

# 摘要

> 大型语言模型（LLM）在提升我们日常生活的多个领域展现了巨大潜力，但庞大的模型规模却成为边缘设备部署的难题。本文提出了一种创新的 LLM 权重剪枝方法，专注于优化注意力矩阵的近似，而非传统的线性近似。我们为基于梯度下降的优化方法提供了理论收敛保证，并展示了其在降低计算成本的同时保持模型性能的有效性。这一研究为 LLM 剪枝算法设计开辟了新路径，有望推动资源受限设备上更高效的 LLM 推理。

> Large Language Models (LLMs) have shown immense potential in enhancing various aspects of our daily lives, from conversational AI to search and AI assistants. However, their growing capabilities come at the cost of extremely large model sizes, making deployment on edge devices challenging due to memory and computational constraints. This paper introduces a novel approach to LLM weight pruning that directly optimizes for approximating the attention matrix, a core component of transformer architectures. Unlike existing methods that focus on linear approximations, our approach accounts for the non-linear nature of the Softmax attention mechanism. We provide theoretical guarantees for the convergence of our Gradient Descent-based optimization method to a near-optimal pruning mask solution. Our preliminary empirical results demonstrate the effectiveness of this approach in maintaining model performance while significantly reducing computational costs. This work establishes a new theoretical foundation for pruning algorithm design in LLMs, potentially paving the way for more efficient LLM inference on resource-constrained devices.

[Arxiv](https://arxiv.org/abs/2410.11261)