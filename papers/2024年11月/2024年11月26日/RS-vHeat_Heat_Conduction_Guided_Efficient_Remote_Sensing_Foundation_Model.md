# RS-vHeat：由热传导引导的高效遥感基础模型

发布时间：2024年11月26日

`其他` `图像处理`

> RS-vHeat: Heat Conduction Guided Efficient Remote Sensing Foundation Model

# 摘要

> 遥感基础模型极大地突破了设计特定任务模型的传统模式，在多个任务中展现出更强的可扩展性。但它们在处理高分辨率遥感图像时，面临着计算效率低下和可解释性受限等难题。为化解这些难题，我们从模拟局部热扩散的物理过程——热传导中获取灵感。基于此，我们率先探索利用热传导的并行计算模型来模拟高分辨率遥感图像中的局部区域相关性，并推出了高效的多模态遥感基础模型 RS-vHeat。具体而言，RS-vHeat 1) 采用复杂度为 $O(N^{1.5})$ 且具有全局感受野的热传导算子（HCO），在降低计算开销的同时，捕捉遥感对象结构信息以引导热扩散；2) 借助基于频域分层掩蔽和多域重建的自监督策略，学习各类场景的频率分布表征；3) 在 4 项任务和 10 个数据集中，相比前沿技术，效率和性能大幅提升。与基于注意力的遥感基础模型相比，我们减少了 84%的内存消耗，降低了 24%的 FLOPs，将吞吐量提高了 2.7 倍。

> Remote sensing foundation models largely break away from the traditional paradigm of designing task-specific models, offering greater scalability across multiple tasks. However, they face challenges such as low computational efficiency and limited interpretability, especially when dealing with high-resolution remote sensing images. To overcome these, we draw inspiration from heat conduction, a physical process modeling local heat diffusion. Building on this idea, we are the first to explore the potential of using the parallel computing model of heat conduction to simulate the local region correlations in high-resolution remote sensing images, and introduce RS-vHeat, an efficient multi-modal remote sensing foundation model. Specifically, RS-vHeat 1) applies the Heat Conduction Operator (HCO) with a complexity of $O(N^{1.5})$ and a global receptive field, reducing computational overhead while capturing remote sensing object structure information to guide heat diffusion; 2) learns the frequency distribution representations of various scenes through a self-supervised strategy based on frequency domain hierarchical masking and multi-domain reconstruction; 3) significantly improves efficiency and performance over state-of-the-art techniques across 4 tasks and 10 datasets. Compared to attention-based remote sensing foundation models, we reduces memory consumption by 84%, decreases FLOPs by 24% and improves throughput by 2.7 times.

[Arxiv](https://arxiv.org/abs/2411.17984)