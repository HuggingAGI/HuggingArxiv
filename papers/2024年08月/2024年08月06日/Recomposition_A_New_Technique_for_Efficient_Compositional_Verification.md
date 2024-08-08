# 重组技术：高效组合验证的新方法

发布时间：2024年08月06日

`Agent` `软件工程` `模型检查`

> Recomposition: A New Technique for Efficient Compositional Verification

# 摘要

> 组合验证算法在模型检查领域研究深入，但组件选择的优化却相对被忽视。本文引入一种创新的组合验证框架，将组件选择提升为核心议题。该框架首先将系统拆解为基本组件，再通过高效重组进行验证。关键在于重组映射的优化，这决定了重组策略，从而简化了组件选择难题。面对可能的重组映射众多，我们采用启发式策略筛选出少数高效方案并行执行。实践证明，我们的技术在TLA+模型检查器中表现出色，与知名工具TLC在分布式协议测试中不相上下。

> Compositional verification algorithms are well-studied in the context of model checking. Properly selecting components for verification is important for efficiency, yet has received comparatively less attention. In this paper, we address this gap with a novel compositional verification framework that focuses on component selection as an explicit, first-class concept. The framework decomposes a system into components, which we then recompose into new components for efficient verification. At the heart of our technique is the recomposition map that determines how recomposition is performed; the component selection problem thus reduces to finding a good recomposition map. However, the space of possible recomposition maps can be large. We therefore propose heuristics to find a small portfolio of recomposition maps, which we then run in parallel. We implemented our techniques in a model checker for the TLA+ language. In our experiments, we show that our tool achieves competitive performance with TLC-a well-known model checker for TLA+-on a benchmark suite of distributed protocols.

[Arxiv](https://arxiv.org/abs/2408.03488)