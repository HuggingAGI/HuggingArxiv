# 借助线性定理突破大型语言模型量化的极限

发布时间：2024年11月26日

`LLM理论` `语言模型` `量化技术`

> Pushing the Limits of Large Language Model Quantization via the Linearity Theorem

# 摘要

> 量化大型语言模型已成为削减其内存与计算成本的常用手段。一般而言，现有的方法多是把问题拆解成各个层级的子问题，然后借助各种指标来将每层的误差最小化。但这种方式目前缺乏理论支撑，所采用的指标或许并非最优。在本文里，我们给出了一个“线性定理”，确立了层级的$\ell_2$重建误差和因量化而致使的模型困惑度增加之间的直接关联。这一发现带来了两个新的应用：（1）一种运用哈达玛旋转和均方误差最优网格的简便无数据 LLM 量化方法，名为 HIGGS，它比之前所有的无数据方法（比如极为流行的 NF4 量化格式）都出色；（2）通过归结为动态规划，得出了在中比特宽度范围内找到与给定压缩约束相匹配的非均匀每层量化级别的最优解。从实际角度看，我们在 Llama-3.1 和 3.2 系列模型以及 Qwen 系列模型上呈现了更优的精度 - 压缩平衡。另外，我们表明，我们的方法在不同批量大小的 GPU 内核方面能够得到有效支持，推动了 LLM 的无数据和非均匀量化。

> Quantizing large language models has become a standard way to reduce their memory and computational costs. Typically, existing methods focus on breaking down the problem into individual layer-wise sub-problems, and minimizing per-layer error, measured via various metrics. Yet, this approach currently lacks theoretical justification and the metrics employed may be sub-optimal. In this paper, we present a "linearity theorem" establishing a direct relationship between the layer-wise $\ell_2$ reconstruction error and the model perplexity increase due to quantization. This insight enables two novel applications: (1) a simple data-free LLM quantization method using Hadamard rotations and MSE-optimal grids, dubbed HIGGS, which outperforms all prior data-free approaches such as the extremely popular NF4 quantized format, and (2) an optimal solution to the problem of finding non-uniform per-layer quantization levels which match a given compression constraint in the medium-bitwidth regime, obtained by reduction to dynamic programming. On the practical side, we demonstrate improved accuracy-compression trade-offs on Llama-3.1 and 3.2-family models, as well as on Qwen-family models. Further, we show that our method can be efficiently supported in terms of GPU kernels at various batch sizes, advancing both data-free and non-uniform quantization for LLMs.

[Arxiv](https://arxiv.org/abs/2411.17525)