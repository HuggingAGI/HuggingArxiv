# EvoPress：借助进化搜索，迈向最佳动态模型压缩

发布时间：2024年10月18日

`LLM理论` `人工智能` `计算机科学`

> EvoPress: Towards Optimal Dynamic Model Compression via Evolutionary Search

# 摘要

> 大型语言模型 (LLM) 的高计算成本催生了 LLM 压缩的研究热潮，方法包括量化、稀疏化和结构化剪枝。新前沿是 \emph{动态、非均匀} 压缩方法，它们根据每个块或层的压缩级别（如稀疏性）调整压缩，以最小化精度损失并保证全局压缩阈值。然而，现有方法依赖启发式识别层的“重要性”，基于 \emph{错误单调性} 假设，即端到端模型压缩错误与层级错误总和成比例。本文重新审视此领域，提出一种新的、通用的动态压缩方法，在给定输入范围内被证明最优。我们发现，\emph{错误单调性不适用于 LLM}：低层级错误总和的压缩模型可能表现更差。为此，我们提出新的通用进化框架 EvoPress，具有可证明的收敛性和低样本评估复杂性。实验表明，EvoPress 在 Llama、Mistral 和 Phi 模型动态压缩中表现出色，刷新了结构化剪枝、非结构化稀疏性和动态位宽量化的最先进记录。代码已开源：https://github.com/IST-DASLab/EvoPress。

> The high computational costs of large language models (LLMs) have led to a flurry of research on LLM compression, via methods such as quantization, sparsification, or structured pruning. A new frontier in this area is given by \emph{dynamic, non-uniform} compression methods, which adjust the compression levels (e.g., sparsity) per-block or even per-layer in order to minimize accuracy loss, while guaranteeing a global compression threshold. Yet, current methods rely on heuristics for identifying the "importance" of a given layer towards the loss, based on assumptions such as \emph{error monotonicity}, i.e. that the end-to-end model compression error is proportional to the sum of layer-wise errors. In this paper, we revisit this area, and propose a new and general approach for dynamic compression that is provably optimal in a given input range. We begin from the motivating observation that, in general, \emph{error monotonicity does not hold for LLMs}: compressed models with lower sum of per-layer errors can perform \emph{worse} than models with higher error sums. To address this, we propose a new general evolutionary framework for dynamic LLM compression called EvoPress, which has provable convergence, and low sample and evaluation complexity. We show that these theoretical guarantees lead to highly competitive practical performance for dynamic compression of Llama, Mistral and Phi models. Via EvoPress, we set new state-of-the-art results across all compression approaches: structural pruning (block/layer dropping), unstructured sparsity, as well as quantization with dynamic bitwidths. Our code is available at https://github.com/IST-DASLab/EvoPress.

[Arxiv](https://arxiv.org/abs/2410.14649)