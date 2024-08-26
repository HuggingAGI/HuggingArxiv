# 多层Transformer的梯度近似可在近乎线性时间内完成

发布时间：2024年08月23日

`LLM理论` `人工智能`

> Multi-Layer Transformers Gradient Can be Approximated in Almost Linear Time

# 摘要

> 在流行的transformer架构中，自注意力机制的二次计算复杂度对训练和推理效率及内存需求构成了显著挑战。为此，本文提出了一种新的快速梯度计算方法，适用于多层transformer模型。该方法能在近似线性时间$n^{1+o(1)}$内完成整个模型的梯度计算，大幅缓解了传统二次复杂度的计算瓶颈。我们的理论不仅适用于任意损失函数，且在整个模型中保持误差可控。即便在模型包含残差连接、因果掩码等多头注意力等实际子模块时，我们的分析依然成立。通过优化大型语言模型的梯度计算效率，我们期待这项工作能推动长上下文语言模型更高效地训练与部署。

> The quadratic computational complexity in the self-attention mechanism of popular transformer architectures poses significant challenges for training and inference, particularly in terms of efficiency and memory requirements. Towards addressing these challenges, this paper introduces a novel fast computation method for gradient calculation in multi-layer transformer models. Our approach enables the computation of gradients for the entire multi-layer transformer model in almost linear time $n^{1+o(1)}$, where $n$ is the input sequence length. This breakthrough significantly reduces the computational bottleneck associated with the traditional quadratic time complexity. Our theory holds for any loss function and maintains a bounded approximation error across the entire model. Furthermore, our analysis can hold when the multi-layer transformer model contains many practical sub-modules, such as residual connection, casual mask, and multi-head attention. By improving the efficiency of gradient computation in large language models, we hope that our work will facilitate the more effective training and deployment of long-context language models based on our theoretical results.

[Arxiv](https://arxiv.org/abs/2408.13233)