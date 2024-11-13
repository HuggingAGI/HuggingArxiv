# 基于 RoPE 的 Transformer 架构的电路复杂性界限

发布时间：2024年11月12日

`LLM理论` `计算机科学`

> Circuit Complexity Bounds for RoPE-based Transformer Architecture

# 摘要

> 表征 Transformer 架构的表达能力对于理解其容量限制和缩放规律至关重要。最近的工作为类似 Transformer 的架构提供了电路复杂性界限。另一方面，旋转位置嵌入（$\mathsf{RoPE}$）已成为现代大型语言模型中的一项关键技术，与传统位置嵌入相比，在捕获位置信息方面表现出更优越的性能，在应用前景方面显示出巨大潜力，特别是对于长上下文场景。经验证据还表明，与传统 Transformer 模型相比，基于 $\mathsf{RoPE}$ 的 Transformer 架构表现出更强的泛化能力。在这项工作中，我们为具有 $\mathsf{RoPE}$ 注意力的 Transformer 建立了更严格的电路复杂性界限。我们的关键贡献在于，我们表明，除非 $\mathsf{TC}^0 = \mathsf{NC}^1$，具有 $\mathrm{poly}(n)$ 精度、$O(1)$ 层、隐藏维度 $d \leq O(n)$ 的基于 $\mathsf{RoPE}$ 的 Transformer 无法解决算术问题或布尔公式值问题。这一结果显著表明了基于 $\mathsf{RoPE}$ 的 Transformer 架构的表达能力的基本限制，尽管它在实践中取得了巨大的成功。我们的理论框架不仅建立了更严格的复杂性界限，而且可能指导基于 $\mathsf{RoPE}$ 的 Transformer 的进一步工作。

> Characterizing the express power of the Transformer architecture is critical to understanding its capacity limits and scaling law. Recent works provide the circuit complexity bounds to Transformer-like architecture. On the other hand, Rotary Position Embedding ($\mathsf{RoPE}$) has emerged as a crucial technique in modern large language models, offering superior performance in capturing positional information compared to traditional position embeddings, which shows great potential in application prospects, particularly for the long context scenario. Empirical evidence also suggests that $\mathsf{RoPE}$-based Transformer architectures demonstrate greater generalization capabilities compared to conventional Transformer models. In this work, we establish a tighter circuit complexity bound for Transformers with $\mathsf{RoPE}$ attention. Our key contribution is that we show that unless $\mathsf{TC}^0 = \mathsf{NC}^1$, a $\mathsf{RoPE}$-based Transformer with $\mathrm{poly}(n)$-precision, $O(1)$ layers, hidden dimension $d \leq O(n)$ cannot solve the arithmetic problem or the Boolean formula value problem. This result significantly demonstrates the fundamental limitation of the expressivity of the $\mathsf{RoPE}$-based Transformer architecture, although it achieves giant empirical success. Our theoretical framework not only establishes tighter complexity bounds but also may instruct further work on the $\mathsf{RoPE}$-based Transformer.

[Arxiv](https://arxiv.org/abs/2411.07602)