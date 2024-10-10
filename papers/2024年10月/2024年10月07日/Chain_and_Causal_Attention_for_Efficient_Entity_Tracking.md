# 高效实体跟踪：链与因果注意力的结合

发布时间：2024年10月07日

`LLM理论` `人工智能`

> Chain and Causal Attention for Efficient Entity Tracking

# 摘要

> 本文探讨了大型语言模型中transformer在实体跟踪任务中的局限性。我们发现，transformer至少需要 $\log_2 (n+1)$ 层来处理 $n$ 个状态变化的实体跟踪。为此，我们提出了一种高效且节约的注意力机制增强方法，使其能更有效地管理长期依赖。通过将注意力视为邻接矩阵，我们的模型仅需单层即可跟踪实体状态。实证结果表明，在保持自然语言建模竞争力的同时，实体跟踪性能显著提升。我们的改进注意力机制大幅减少了所需层数，并揭示了注意力的结构化内部表示。广泛实验验证了我们的方法。我们的贡献包括理论洞察、改进的注意力机制及实证验证。

> This paper investigates the limitations of transformers for entity-tracking tasks in large language models. We identify a theoretical constraint, showing that transformers require at least $\log_2 (n+1)$ layers to handle entity tracking with $n$ state changes. To address this issue, we propose an efficient and frugal enhancement to the standard attention mechanism, enabling it to manage long-term dependencies more efficiently. By considering attention as an adjacency matrix, our model can track entity states with a single layer. Empirical results demonstrate significant improvements in entity tracking datasets while keeping competitive performance on standard natural language modeling. Our modified attention allows us to achieve the same performance with drastically fewer layers. Additionally, our enhanced mechanism reveals structured internal representations of attention. Extensive experiments on both toy and complex datasets validate our approach. Our contributions include theoretical insights, an improved attention mechanism, and empirical validation.

[Arxiv](https://arxiv.org/abs/2410.05565)