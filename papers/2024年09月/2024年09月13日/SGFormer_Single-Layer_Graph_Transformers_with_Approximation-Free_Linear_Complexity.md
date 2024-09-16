# SGFormer：一种单层图变换器，具备无近似的线性复杂度。

发布时间：2024年09月13日

`LLM理论` `图神经网络` `大数据`

> SGFormer: Single-Layer Graph Transformers with Approximation-Free Linear Complexity

# 摘要

> 在大图上学习表示一直是个难题，因为它们相互依赖。最近，Transformer 凭借其全局注意力在小图上表现出色，能捕捉到超越现有结构的成对交互。现有方法多借鉴 Transformer 在语言和视觉任务中的思路，采用复杂的深度注意力层架构。本文探讨了在图上使用多层注意力层的必要性，发现这其实限制了效率。我们分析了一种通用混合传播层，发现多层传播其实可以简化为单层，且不影响表示学习能力。这为构建高效图 Transformer 提供了新思路，即简化架构而不失表达力。我们提出的简化单层图 Transformer (SGFormer)，其核心是单层全局注意力，能线性扩展并无需近似处理成对交互。实验证明，SGFormer 能处理大规模图 ogbn-papers100M，在中等图上推理速度远超同类 Transformer，且在数据有限时仍表现出色。

> Learning representations on large graphs is a long-standing challenge due to the inter-dependence nature. Transformers recently have shown promising performance on small graphs thanks to its global attention for capturing all-pair interactions beyond observed structures. Existing approaches tend to inherit the spirit of Transformers in language and vision tasks, and embrace complicated architectures by stacking deep attention-based propagation layers. In this paper, we attempt to evaluate the necessity of adopting multi-layer attentions in Transformers on graphs, which considerably restricts the efficiency. Specifically, we analyze a generic hybrid propagation layer, comprised of all-pair attention and graph-based propagation, and show that multi-layer propagation can be reduced to one-layer propagation, with the same capability for representation learning. It suggests a new technical path for building powerful and efficient Transformers on graphs, particularly through simplifying model architectures without sacrificing expressiveness. As exemplified by this work, we propose a Simplified Single-layer Graph Transformers (SGFormer), whose main component is a single-layer global attention that scales linearly w.r.t. graph sizes and requires none of any approximation for accommodating all-pair interactions. Empirically, SGFormer successfully scales to the web-scale graph ogbn-papers100M, yielding orders-of-magnitude inference acceleration over peer Transformers on medium-sized graphs, and demonstrates competitiveness with limited labeled data.

[Arxiv](https://arxiv.org/abs/2409.09007)