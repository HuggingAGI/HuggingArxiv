# ProTEA：FPGA 上的可编程 Transformer 编码器加速

发布时间：2024年09月20日

`LLM理论` `半导体` `人工智能`

> ProTEA: Programmable Transformer Encoder Acceleration on FPGA

# 摘要

> Transformer神经网络（TNN）在自然语言处理、机器翻译和计算机视觉等领域广泛应用，其成功主要得益于多头自注意力机制，这一机制能高效提取序列数据的关键特征。然而，尽管TNN广受欢迎，但针对其核心组件——多头自注意力块和前馈神经网络的硬件加速器却寥寥无几。为此，我们推出了\textit{ProTEA}，一款专为最先进Transformer编码器密集计算设计的运行时可编程加速器，旨在通过最大化并行性降低延迟。我们在Xilinx Alveo U55C加速卡上进行了实验，结果显示\textit{ProTEA}不仅支持多种流行Transformer网络，还能在特定配置下实现接近最优的性能，速度更是比NVIDIA Titan XP GPU快2.5倍，相比其他定制FPGA加速器也有显著提升。

> Transformer neural networks (TNN) have been widely utilized on a diverse range of applications, including natural language processing (NLP), machine translation, and computer vision (CV). Their widespread adoption has been primarily driven by the exceptional performance of their multi-head self-attention block used to extract key features from sequential data. The multi-head self-attention block is followed by feedforward neural networks, which play a crucial role in introducing non-linearity to assist the model in learning complex patterns. Despite the popularity of TNNs, there has been limited numbers of hardware accelerators targeting these two critical blocks. Most prior works have concentrated on sparse architectures that are not flexible for popular TNN variants. This paper introduces \textit{ProTEA}, a runtime programmable accelerator tailored for the dense computations of most of state-of-the-art transformer encoders. \textit{ProTEA} is designed to reduce latency by maximizing parallelism. We introduce an efficient tiling of large matrices that can distribute memory and computing resources across different hardware components within the FPGA. We provide run time evaluations of \textit{ProTEA} on a Xilinx Alveo U55C high-performance data center accelerator card. Experimental results demonstrate that \textit{ProTEA} can host a wide range of popular transformer networks and achieve near optimal performance with a tile size of 64 in the multi-head self-attention block and 6 in the feedforward networks block when configured with 8 parallel attention heads, 12 layers, and an embedding dimension of 768 on the U55C. Comparative results are provided showing \textit{ProTEA} is 2.5$\times$ faster than an NVIDIA Titan XP GPU. Results also show that it achieves 1.3 -- 2.8$\times$ speed up compared with current state-of-the-art custom designed FPGA accelerators.

[Arxiv](https://arxiv.org/abs/2409.13975)