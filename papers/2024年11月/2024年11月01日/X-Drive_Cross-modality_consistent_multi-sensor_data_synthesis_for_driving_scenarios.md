# X-Drive：针对驾驶场景的跨模态一致的多传感器数据合成

发布时间：2024年11月01日

`其他` `自动驾驶` `计算机视觉`

> X-Drive: Cross-modality consistent multi-sensor data synthesis for driving scenarios

# 摘要

> 近期的研究进展借助扩散模型来合成驾驶场景中的激光雷达点云或相机图像数据。虽说它们在单模态数据边际分布建模上成果斐然，但对于不同模态相互依赖以描绘复杂驾驶场景这方面，探索尚显不足。为弥补这一空缺，我们推出全新框架 X-DRIVE，通过双分支潜在扩散模型架构来为点云和多视图图像的联合分布建模。鉴于两种模态的几何空间各异，X-DRIVE 依据来自另一模态的相应局部区域来制约每种模态的合成，以保障更优的对齐效果和真实性。为进一步应对去噪时的空间模糊问题，我们基于极线设计了跨模态条件模块，以自适应学习跨模态局部对应关系。此外，X-DRIVE 支持通过包括文本、边界框、图像和点云在内的多级输入条件进行可控生成。众多结果显示，X-DRIVE 对于点云和多视图图像的合成效果都具有高保真度，既遵循输入条件，又确保了可靠的跨模态一致性。我们的代码将在 https://github.com/yichen928/X-Drive 上公开。

> Recent advancements have exploited diffusion models for the synthesis of either LiDAR point clouds or camera image data in driving scenarios. Despite their success in modeling single-modality data marginal distribution, there is an under-exploration in the mutual reliance between different modalities to describe complex driving scenes. To fill in this gap, we propose a novel framework, X-DRIVE, to model the joint distribution of point clouds and multi-view images via a dual-branch latent diffusion model architecture. Considering the distinct geometrical spaces of the two modalities, X-DRIVE conditions the synthesis of each modality on the corresponding local regions from the other modality, ensuring better alignment and realism. To further handle the spatial ambiguity during denoising, we design the cross-modality condition module based on epipolar lines to adaptively learn the cross-modality local correspondence. Besides, X-DRIVE allows for controllable generation through multi-level input conditions, including text, bounding box, image, and point clouds. Extensive results demonstrate the high-fidelity synthetic results of X-DRIVE for both point clouds and multi-view images, adhering to input conditions while ensuring reliable cross-modality consistency. Our code will be made publicly available at https://github.com/yichen928/X-Drive.

[Arxiv](https://arxiv.org/abs/2411.01123)