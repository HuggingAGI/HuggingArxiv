# FAMOUS：为 UltraScale+ FPGAs 上的 Transformer 注意力机制打造的灵活加速器

发布时间：2024年09月21日

`LLM理论` `硬件加速` `计算机视觉`

> FAMOUS: Flexible Accelerator for the Attention Mechanism of Transformer on UltraScale+ FPGAs

# 摘要

> Transformer 神经网络 (TNN) 在自然语言处理 (NLP)、机器翻译和计算机视觉 (CV) 等领域得到了广泛应用。其成功主要得益于多头自注意力机制在处理序列数据和提取特征方面的卓越表现。然而，目前针对这一机制的硬件加速器仍较为稀缺。本文介绍了 \textit{FAMOUS}，一种专为 TNN 密集多头注意力 (MHA) 计算设计的灵活硬件加速器，适用于现场可编程门阵列 (FPGAs)。该加速器通过优化处理元素和片上内存的利用率，显著提升了并行性和降低了延迟。通过高效的矩阵分块技术，\textit{FAMOUS} 能够将资源合理分配到不同 FPGA 平台上的各个模块。实验结果表明，在 Xilinx Alveo U55C 和 U200 数据中心卡上，\textit{FAMOUS} 的最大吞吐量、并行注意力头数、嵌入维度和分块大小分别达到了 328 GOPS、8、768 和 64。与 Intel Xeon Gold 5220R CPU 和 NVIDIA V100 GPU 相比，\textit{FAMOUS} 分别快了 3.28 倍和 2.6 倍，甚至比当前最快的 FPGA 加速器还要快 1.3 倍。

> Transformer neural networks (TNNs) are being applied across a widening range of application domains, including natural language processing (NLP), machine translation, and computer vision (CV). Their popularity is largely attributed to the exceptional performance of their multi-head self-attention blocks when analyzing sequential data and extracting features. To date, there are limited hardware accelerators tailored for this mechanism, which is the first step before designing an accelerator for a complete model. This paper proposes \textit{FAMOUS}, a flexible hardware accelerator for dense multi-head attention (MHA) computation of TNNs on field-programmable gate arrays (FPGAs). It is optimized for high utilization of processing elements and on-chip memories to improve parallelism and reduce latency. An efficient tiling of large matrices has been employed to distribute memory and computing resources across different modules on various FPGA platforms. The design is evaluated on Xilinx Alveo U55C and U200 data center cards containing Ultrascale+ FPGAs. Experimental results are presented that show that it can attain a maximum throughput, number of parallel attention heads, embedding dimension and tile size of 328 (giga operations/second (GOPS)), 8, 768 and 64 respectively on the U55C. Furthermore, it is 3.28$\times$ and 2.6$\times$ faster than the Intel Xeon Gold 5220R CPU and NVIDIA V100 GPU respectively. It is also 1.3$\times$ faster than the fastest state-of-the-art FPGA-based accelerator.

[Arxiv](https://arxiv.org/abs/2409.14023)