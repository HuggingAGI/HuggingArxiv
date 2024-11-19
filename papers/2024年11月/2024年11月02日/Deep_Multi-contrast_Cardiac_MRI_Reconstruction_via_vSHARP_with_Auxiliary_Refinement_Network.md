# 借助带有辅助细化网络的 vSHARP 实现深度多对比度心脏 MRI 重建

发布时间：2024年11月02日

`其他` `成像技术`

> Deep Multi-contrast Cardiac MRI Reconstruction via vSHARP with Auxiliary Refinement Network

# 摘要

> 心脏磁共振成像（CMRI）堪称基石般的成像方式，能深度洞悉心脏的结构与功能。多对比度心脏磁共振成像（MCCMRI），即获取具有不同对比度权重的序列，大大提升了诊断能力，可捕捉到丰富的心脏组织特征。不过，MCCMRI 常受采集时间长和易出现运动伪影的制约。为应对这些难题，已研发出借助在加速因子下采用不同采样方案对 k 空间进行欠采样的加速成像技术，以缩短扫描时长。在此背景下，我们提出了一种基于深度学习的 2D 动态多对比度、多方案、多加速 MRI 重建方法。我们的方法把利用半二次变量分裂和 ADMM 优化的先进 vSHARP 模型，与作为辅助精修网络（ARN）的变分网络相融合，以更好地适配 MCCMRI 数据的多样性。具体而言，欠采样的 k 空间数据输入到 ARN 中，ARN 为 vSHARP 所用的去噪步骤给出初始预测。随后，这与欠采样的 k 空间一同被 vSHARP 用于生成高质量的 2D 序列预测。我们的方法胜过传统重建技术和其他基于 vSHARP 的模型。

> Cardiac MRI (CMRI) is a cornerstone imaging modality that provides in-depth insights into cardiac structure and function. Multi-contrast CMRI (MCCMRI), which acquires sequences with varying contrast weightings, significantly enhances diagnostic capabilities by capturing a wide range of cardiac tissue characteristics. However, MCCMRI is often constrained by lengthy acquisition times and susceptibility to motion artifacts. To mitigate these challenges, accelerated imaging techniques that use k-space undersampling via different sampling schemes at acceleration factors have been developed to shorten scan durations. In this context, we propose a deep learning-based reconstruction method for 2D dynamic multi-contrast, multi-scheme, and multi-acceleration MRI. Our approach integrates the state-of-the-art vSHARP model, which utilizes half-quadratic variable splitting and ADMM optimization, with a Variational Network serving as an Auxiliary Refinement Network (ARN) to better adapt to the diverse nature of MCCMRI data. Specifically, the subsampled k-space data is fed into the ARN, which produces an initial prediction for the denoising step used by vSHARP. This, along with the subsampled k-space, is then used by vSHARP to generate high-quality 2D sequence predictions. Our method outperforms traditional reconstruction techniques and other vSHARP-based models.

[Arxiv](https://arxiv.org/abs/2411.01291)