# DynamicCity：来自动态场景的大规模激光雷达生成

发布时间：2024年10月23日

`其他` `自动驾驶` `激光雷达`

> DynamicCity: Large-Scale LiDAR Generation from Dynamic Scenes

# 摘要

> 摘要：激光雷达场景生成最近发展迅速。然而，现有的方法主要集中在生成静态和单帧场景，忽略了现实世界驾驶环境固有的动态性质。在这项工作中，我们引入了 DynamicCity，这是一个新颖的 4D 激光雷达生成框架，能够生成大规模、高质量的激光雷达场景，捕捉动态环境的时间演变。DynamicCity 主要由两个关键模型组成。1）一个用于学习 HexPlane 作为紧凑 4D 表示的 VAE 模型。DynamicCity 不是使用简单的平均操作，而是采用了一种新颖的投影模块，将 4D 激光雷达特征有效地压缩成六个 2D 特征图用于 HexPlane 构建，这显著提高了 HexPlane 的拟合质量（高达 12.56 mIoU 增益）。此外，我们利用扩展和压缩策略并行重建 3D 特征体积，与简单地查询每个 3D 点相比，这提高了网络训练效率和重建精度（高达 7.05 mIoU 增益，2.06 倍训练加速和 70.84％内存减少）。2）一个基于 DiT 的用于 HexPlane 生成的扩散模型。为了使 HexPlane 适用于 DiT 生成，提出了一种填充展开操作，将 HexPlane 的所有六个特征平面重新组织为一个方形 2D 特征图。特别是，在扩散或采样过程中可以引入各种条件，支持多种 4D 生成应用，如轨迹和命令驱动生成、修复和布局条件生成。在 CarlaSC 和 Waymo 数据集上进行的大量实验表明，DynamicCity 在多个指标上明显优于现有的最先进的 4D 激光雷达生成方法。代码将被发布以促进未来的研究。

> 
Abstract:LiDAR scene generation has been developing rapidly recently. However, existing methods primarily focus on generating static and single-frame scenes, overlooking the inherently dynamic nature of real-world driving environments. In this work, we introduce DynamicCity, a novel 4D LiDAR generation framework capable of generating large-scale, high-quality LiDAR scenes that capture the temporal evolution of dynamic environments. DynamicCity mainly consists of two key models. 1) A VAE model for learning HexPlane as the compact 4D representation. Instead of using naive averaging operations, DynamicCity employs a novel Projection Module to effectively compress 4D LiDAR features into six 2D feature maps for HexPlane construction, which significantly enhances HexPlane fitting quality (up to 12.56 mIoU gain). Furthermore, we utilize an Expansion & Squeeze Strategy to reconstruct 3D feature volumes in parallel, which improves both network training efficiency and reconstruction accuracy than naively querying each 3D point (up to 7.05 mIoU gain, 2.06x training speedup, and 70.84% memory reduction). 2) A DiT-based diffusion model for HexPlane generation. To make HexPlane feasible for DiT generation, a Padded Rollout Operation is proposed to reorganize all six feature planes of the HexPlane as a squared 2D feature map. In particular, various conditions could be introduced in the diffusion or sampling process, supporting versatile 4D generation applications, such as trajectory- and command-driven generation, inpainting, and layout-conditioned generation. Extensive experiments on the CarlaSC and Waymo datasets demonstrate that DynamicCity significantly outperforms existing state-of-the-art 4D LiDAR generation methods across multiple metrics. The code will be released to facilitate future research.
    

[Arxiv](https://arxiv.org/pdf/2410.18084)