# BitStack：用于在可变内存环境中对压缩大型语言模型实现细粒度大小控制

发布时间：2024年10月31日

`LLM应用` `计算机` `模型压缩`

> BitStack: Fine-Grained Size Control for Compressed Large Language Models in Variable Memory Environments

# 摘要

> 大型语言模型（LLMs）给众多应用带来了变革，然而其在本地设备的部署却因内存受限而面临挑战。缩放定律虽提升了LLM的能力，可主要瓶颈已从“能力”转为“可用性”，凸显出高效内存管理的必要性。传统压缩手段，像量化，往往需要预先设定压缩比，且针对每种设置都有单独的压缩流程，这让其在可变内存环境中的部署变得复杂。本文中，我们推出了“BitStack”，这是一种全新且无需训练的权重压缩方式，能在内存使用和模型性能之间达成兆字节级的平衡。借助权重分解，BitStack能够动态调节模型大小，且在运行内存和存储设备间的传输极少。我们的方法在考量每个参数重要性的同时，迭代分解权重矩阵，每次分解迭代会产生每个参数近似1位的残差块。这些块在存储中被排序和堆叠为基本传输单元，依据当前内存可用量加载不同数量。在众多任务中的大量实验表明，即便提供了精细的大小控制，BitStack也始终能与强大的量化基线持平甚至超越，特别是在极端压缩比的情况下。据我们所知，这是首个基于分解的方法，有效填补了与量化等实用压缩技术的差距。代码可在https://github.com/xinghaow99/BitStack获取。

> Large language models (LLMs) have revolutionized numerous applications, yet their deployment remains challenged by memory constraints on local devices. While scaling laws have enhanced LLM capabilities, the primary bottleneck has shifted from \textit{capability} to \textit{availability}, emphasizing the need for efficient memory management. Traditional compression methods, such as quantization, often require predefined compression ratios and separate compression processes for each setting, complicating deployment in variable memory environments. In this paper, we introduce \textbf{BitStack}, a novel, training-free weight compression approach that enables megabyte-level trade-offs between memory usage and model performance. By leveraging weight decomposition, BitStack can dynamically adjust the model size with minimal transmission between running memory and storage devices. Our approach iteratively decomposes weight matrices while considering the significance of each parameter, resulting in an approximately 1-bit per parameter residual block in each decomposition iteration. These blocks are sorted and stacked in storage as basic transmission units, with different quantities loaded based on current memory availability. Extensive experiments across a wide range of tasks demonstrate that, despite offering fine-grained size control, BitStack consistently matches or surpasses strong quantization baselines, particularly at extreme compression ratios. To the best of our knowledge, this is the first decomposition-based method that effectively bridges the gap to practical compression techniques like quantization. Code is available at https://github.com/xinghaow99/BitStack.

[Arxiv](https://arxiv.org/abs/2410.23918)