# V2X-R：用于 3D 物体检测的协同激光雷达 - 4D 雷达融合与去噪扩散

发布时间：2024年11月13日

`其他` `车联网` `自动驾驶`

> V2X-R: Cooperative LiDAR-4D Radar Fusion for 3D Object Detection with Denoising Diffusion

# 摘要

> 当前的车联网（V2X）系统利用激光雷达和相机数据显著增强了 3D 物体检测。然而，这些方法在恶劣天气条件下会出现性能下降。抗天气干扰的 4D 雷达提供了多普勒和其他几何信息，增加了解决这一挑战的可能性。为此，我们提出了 V2X-R，这是第一个结合激光雷达、相机和 4D 雷达的模拟 V2X 数据集。V2X-R 包含 12,079 个场景，有 37,727 帧激光雷达和 4D 雷达点云、150,908 张图像以及 170,859 个标注的 3D 车辆边界框。随后，我们提出了一种用于 3D 物体检测的新型协同激光雷达 - 4D 雷达融合管道，并通过各种融合策略实现了它。为了实现抗天气干扰的检测，我们在融合管道中还提出了一个多模态去噪扩散（MDD）模块。MDD 利用抗天气干扰的 4D 雷达特征作为条件，促使扩散模型对有噪声的激光雷达特征进行去噪。实验表明，我们的激光雷达 - 4D 雷达融合管道在 V2X-R 数据集中表现出优越的性能。除此之外，我们的 MDD 模块在雾天/雪天条件下将基本融合模型的性能进一步提高了高达 5.73%/6.70%，且几乎不影响正常性能。数据集和代码将在以下网址公开可用：https://github.com/ylwhxht/V2X-R。

> Current Vehicle-to-Everything (V2X) systems have significantly enhanced 3D object detection using LiDAR and camera data. However, these methods suffer from performance degradation in adverse weather conditions. The weatherrobust 4D radar provides Doppler and additional geometric information, raising the possibility of addressing this challenge. To this end, we present V2X-R, the first simulated V2X dataset incorporating LiDAR, camera, and 4D radar. V2X-R contains 12,079 scenarios with 37,727 frames of LiDAR and 4D radar point clouds, 150,908 images, and 170,859 annotated 3D vehicle bounding boxes. Subsequently, we propose a novel cooperative LiDAR-4D radar fusion pipeline for 3D object detection and implement it with various fusion strategies. To achieve weather-robust detection, we additionally propose a Multi-modal Denoising Diffusion (MDD) module in our fusion pipeline. MDD utilizes weather-robust 4D radar feature as a condition to prompt the diffusion model to denoise noisy LiDAR features. Experiments show that our LiDAR-4D radar fusion pipeline demonstrates superior performance in the V2X-R dataset. Over and above this, our MDD module further improved the performance of basic fusion model by up to 5.73%/6.70% in foggy/snowy conditions with barely disrupting normal performance. The dataset and code will be publicly available at: https://github.com/ylwhxht/V2X-R.

[Arxiv](https://arxiv.org/abs/2411.08402)