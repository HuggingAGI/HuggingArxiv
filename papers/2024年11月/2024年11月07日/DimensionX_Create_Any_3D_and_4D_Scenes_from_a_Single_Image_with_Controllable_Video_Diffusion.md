# DimensionX：使用可控视频扩散从单个图像创建任何 3D 和 4D 场景

发布时间：2024年11月07日

`其他` `计算机视觉` `视频生成`

> DimensionX: Create Any 3D and 4D Scenes from a Single Image with Controllable Video Diffusion

# 摘要

> 摘要：在本文中，我们介绍了 DimensionX，这是一个仅通过一张图像和视频扩散就能生成逼真的 3D 和 4D 场景的框架。我们的方法始于这样一种见解，即 3D 场景的空间结构和 4D 场景的时间演变都可以通过视频帧序列有效地表示。虽然最近的视频扩散模型在生成生动的视觉效果方面取得了显著成功，但由于在生成过程中空间和时间的可控性有限，它们在直接恢复 3D/4D 场景方面面临限制。为了克服这一点，我们提出了 ST-Director，它通过从维度变化的数据中学习维度感知的 LoRA 来解耦视频扩散中的空间和时间因素。这种可控的视频扩散方法能够精确地操纵空间结构和时间动态，使我们能够结合空间和时间维度从连续的帧中重建 3D 和 4D 表示。此外，为了弥合生成的视频与真实世界场景之间的差距，我们为 3D 生成引入了轨迹感知机制，为 4D 生成引入了保持身份的去噪策略。在各种真实世界和合成数据集上进行的大量实验表明，与以前的方法相比，DimensionX 在可控视频生成以及 3D 和 4D 场景生成方面取得了优越的结果。

> 
Abstract:In this paper, we introduce \textbf{DimensionX}, a framework designed to generate photorealistic 3D and 4D scenes from just a single image with video diffusion. Our approach begins with the insight that both the spatial structure of a 3D scene and the temporal evolution of a 4D scene can be effectively represented through sequences of video frames. While recent video diffusion models have shown remarkable success in producing vivid visuals, they face limitations in directly recovering 3D/4D scenes due to limited spatial and temporal controllability during generation. To overcome this, we propose ST-Director, which decouples spatial and temporal factors in video diffusion by learning dimension-aware LoRAs from dimension-variant data. This controllable video diffusion approach enables precise manipulation of spatial structure and temporal dynamics, allowing us to reconstruct both 3D and 4D representations from sequential frames with the combination of spatial and temporal dimensions. Additionally, to bridge the gap between generated videos and real-world scenes, we introduce a trajectory-aware mechanism for 3D generation and an identity-preserving denoising strategy for 4D generation. Extensive experiments on various real-world and synthetic datasets demonstrate that DimensionX achieves superior results in controllable video generation, as well as in 3D and 4D scene generation, compared with previous methods.
    

[Arxiv](https://arxiv.org/pdf/2411.04928)