# Cerberus：高效推理，结合自适应并行解码与顺序知识增强

发布时间：2024年10月17日

`LLM理论` `人工智能`

> Cerberus: Efficient Inference with Adaptive Parallel Decoding and Sequential Knowledge Enhancement

# 摘要

> 大型语言模型 (LLM) 因依赖自回归解码，常在推理速度上受限。近期，并行解码虽显潜力，但现有框架存在两大问题：解码头难以平衡准确性与并行性，且在某些复杂解码步骤中，并行解码反增开销。为此，我们推出 Cerberus，一个自适应并行解码框架，通过门控机制让 LLM 在每一步灵活选择解码策略，同时创新解码头，兼顾并行性与顺序知识。实验显示，Cerberus 比自回归解码提速 2.12 倍，且在加速与生成质量上超越 Medusa，提速 10% - 30%。

> Large language models (LLMs) often face a bottleneck in inference speed due to their reliance on auto-regressive decoding. Recently, parallel decoding has shown significant promise in enhancing inference efficiency. However, we have identified two key issues with existing parallel decoding frameworks: (1) decoding heads fail to balance prediction accuracy and the parallelism of execution, and (2) parallel decoding is not a universal solution, as it can bring unnecessary overheads at some challenging decoding steps. To address these issues, we propose Cerberus, an adaptive parallel decoding framework introduces the gating mechanism to enable the LLMs to adaptively choose appropriate decoding approaches at each decoding step, along with introducing a new paradigm of decoding heads that introduce the sequential knowledge while maintaining execution parallelism. The experiment results demonstrate that the Cerberus can achieve up to 2.12x speed up compared to auto-regressive decoding, and outperforms one of the leading parallel decoding frameworks, Medusa, with a 10% - 30% increase in acceleration and superior generation quality.

[Arxiv](https://arxiv.org/abs/2410.13344)