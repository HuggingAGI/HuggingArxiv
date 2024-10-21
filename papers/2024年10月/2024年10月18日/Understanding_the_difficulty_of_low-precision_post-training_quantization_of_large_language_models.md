# 探究大型语言模型低精度训练后量化的挑战

发布时间：2024年10月18日

`LLM理论` `人工智能` `计算机硬件`

> Understanding the difficulty of low-precision post-training quantization of large language models

# 摘要

> 高参数的大型语言模型虽然计算成本高，但通过将权重压缩至极低精度，可大幅提升效率。这可以通过训练后量化（最小化局部量化误差）或量化感知微调（最小化全局损失）实现。研究发现，在相同数据约束下，前者几乎总是逊于后者，尤其在低精度时更为明显。进一步分析表明，这种差异源于局部与全局优化目标的严重不匹配。因此，在处理大型模型和极低精度时，直接进行量化感知微调显得尤为重要。

> Large language models of high parameter counts are computationally expensive, yet can be made much more efficient by compressing their weights to very low numerical precision. This can be achieved either through post-training quantization by minimizing local, layer-wise quantization errors, or through quantization-aware fine-tuning by minimizing the global loss function. In this study, we discovered that, under the same data constraint, the former approach nearly always fared worse than the latter, a phenomenon particularly prominent when the numerical precision is very low. We further showed that this difficulty of post-training quantization arose from stark misalignment between optimization of the local and global objective functions. Our findings explains limited utility in minimization of local quantization error and the importance of direct quantization-aware fine-tuning, in the regime of large models at very low precision.

[Arxiv](https://arxiv.org/abs/2410.14570)