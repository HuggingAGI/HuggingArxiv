# 多模态大型语言模型并不需要二次方，我们需要的是更高效的方法。

发布时间：2024年10月08日

`LLM应用` `人工智能` `计算机视觉`

> Quadratic Is Not What You Need For Multimodal Large Language Models

# 摘要

> 过去一年，多模态大型语言模型（MLLM）在各方面能力显著提升。然而，计算量随 token 数量二次增长，效率成为扩展瓶颈。我们提出新方法：不减少输入视觉 token，而是修剪 LLM 内视觉计算。修剪后，计算增长变为线性。令人惊讶的是，修剪后 MLLM 能力与原模型相当，甚至在某些基准测试中仅用 25% 计算量表现更优。这为 MLLM 整合更密集视觉 token 提供可能。我们还分析了现有 MLLM 架构缺陷，并提出改进。这是首次研究 MLLM 中 LLM 视觉组件的计算冗余。代码和检查点即将发布。

> In the past year, the capabilities of Multimodal Large Language Models (MLLMs) have significantly improved across various aspects. However, constrained by the quadratic growth of computation in LLMs as the number of tokens increases, efficiency has become a bottleneck for further scaling MLLMs. Although recent efforts have been made to prune visual tokens or use more lightweight LLMs to reduce computation, the problem of quadratic growth in computation with the increase of visual tokens still persists. To address this, we propose a novel approach: instead of reducing the input visual tokens for LLMs, we focus on pruning vision-related computations within the LLMs. After pruning, the computation growth in the LLM is no longer quadratic with the increase of visual tokens, but linear. Surprisingly, we found that after applying such extensive pruning, the capabilities of MLLMs are comparable with the original one and even superior on some benchmarks with only 25% of the computation. This finding opens up the possibility for MLLMs to incorporate much denser visual tokens. Additionally, based on this finding, we further analyzed some architectural design deficiencies in existing MLLMs and proposed promising improvements. To the best of our knowledge, this is the first study to investigate the computational redundancy in the LLM's vision component of MLLMs. Code and checkpoints will be released soon.

[Arxiv](https://arxiv.org/abs/2410.06169)