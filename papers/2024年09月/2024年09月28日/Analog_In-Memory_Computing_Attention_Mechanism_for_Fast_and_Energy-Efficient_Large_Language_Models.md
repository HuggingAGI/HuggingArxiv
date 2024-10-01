# 模拟内存计算注意力机制，为大型语言模型提供快速且节能的解决方案

发布时间：2024年09月28日

`LLM理论` `半导体` `人工智能`

> Analog In-Memory Computing Attention Mechanism for Fast and Energy-Efficient Large Language Models

# 摘要

> Transformer 神经网络依赖自注意力机制，是基础和大型语言模型的核心。在生成式 Transformer 中，自注意力机制通过缓存内存存储标记投影，避免重复计算。然而，GPU 存储的投影需加载到 SRAM 中，导致长序列生成时的延迟和能耗瓶颈。为此，我们提出了一种基于增益单元内存的模拟内存计算方法，实现快速且节能的自注意力机制。易失性增益单元内存能高效存储新标记，并进行模拟有符号权重乘法，计算自注意力所需的点积。我们采用滑动窗口注意力，保持有限过去步骤的记忆，并通过电荷到脉冲转换器消除模拟到数字转换的需求。通过协同设计的初始化算法，我们实现了与 ChatGPT-2 相当的 NLP 性能，训练迭代次数极少。我们的端到端硬件设计包括数字控制，显著减少了注意力延迟和能耗，为大型语言模型中的超快速、低功耗序列生成迈出了重要一步。

> Transformer neural networks, driven by self-attention mechanisms, are core components of foundational and Large Language Models. In generative transformers, self-attention uses cache memory to store token projections, avoiding recomputation at each time step. However, GPU-stored projections must be loaded into SRAM for each new generation step, causing latency and energy bottlenecks for long sequences. In this work, we propose a fast and energy-efficient hardware implementation of self-attention using analog in-memory computing based on gain cell memories. Volatile gain cell memories can be efficiently written to store new tokens during sequence generation, while performing analog signed weight multiplications to compute the dot-products required for self-attention. We implement Sliding Window Attention, which keeps memory of a finite set of past steps. A charge-to-pulse converter for array readout eliminates the need for analog-to-digital conversion between self-attention stages. Using a co-designed initialization algorithm to adapt pre-trained weights to gain cell non-idealities, we achieve NLP performance comparable to ChatGPT-2 with minimal training iterations, despite hardware constraints. Our end-to-end hardware design includes digital controls, estimating area, latency, and energy. The system reduces attention latency by up to two orders of magnitude and energy consumption by up to five orders compared to GPUs, marking a significant step toward ultra-fast, low-power sequence generation in Large Language Models.

[Arxiv](https://arxiv.org/abs/2409.19315)