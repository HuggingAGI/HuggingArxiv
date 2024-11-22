# 用于减轻极端水下领域视觉干扰的去雾辅助多速率多模态姿态估计框架

发布时间：2024年11月21日

`其他` `机器人`

> Dehazing-aided Multi-Rate Multi-Modal Pose Estimation Framework for Mitigating Visual Disturbances in Extreme Underwater Domain

# 摘要

> 这篇论文深入探究了 DU-VIO 的潜能，它是一种去雾辅助的混合多速率多模态视觉-惯性里程计（VIO）估计框架，专为在极端水下环境中出色发挥而设计。先进的 DU-VIO 框架融合了基于 GAN 的预处理模块和混合 CNN-LSTM 模块，借助增强可见度的水下图像和原始 IMU 数据实现精准的姿态估计。在各类水下机器人和探索应用中，精确的姿态估计极为关键。然而，由于悬浮颗粒和衰减效应，水下可见度往往受到影响，致使视觉-惯性姿态估计成为巨大挑战。DU-VIO 致力于通过有效去除原始图像数据中的视觉干扰，提升用于姿态估计的图像特征质量，从而克服这些局限。我们通过计算平移和旋转向量相对参考值的均方根误差（RMSE）分数来验证 DU-VIO 的有效性，并将其与使用改良 AQUALOC 数据集的基础模型的分数进行对比。此项研究意义重大，有望彻底变革水下机器人和探索领域。DU-VIO 为水下可见度这一长期难题提供了有力解决方案，大幅提高了姿态估计的准确性。该研究为推动水下技术发展贡献了宝贵的见解和工具，对科学研究、环境监测及工业应用具有深远影响。

> This paper delves into the potential of DU-VIO, a dehazing-aided hybrid multi-rate multi-modal Visual-Inertial Odometry (VIO) estimation framework, designed to thrive in the challenging realm of extreme underwater environments. The cutting-edge DU-VIO framework is incorporating a GAN-based pre-processing module and a hybrid CNN-LSTM module for precise pose estimation, using visibility-enhanced underwater images and raw IMU data. Accurate pose estimation is paramount for various underwater robotics and exploration applications. However, underwater visibility is often compromised by suspended particles and attenuation effects, rendering visual-inertial pose estimation a formidable challenge. DU-VIO aims to overcome these limitations by effectively removing visual disturbances from raw image data, enhancing the quality of image features used for pose estimation. We demonstrate the effectiveness of DU-VIO by calculating RMSE scores for translation and rotation vectors in comparison to their reference values. These scores are then compared to those of a base model using a modified AQUALOC Dataset. This study's significance lies in its potential to revolutionize underwater robotics and exploration. DU-VIO offers a robust solution to the persistent challenge of underwater visibility, significantly improving the accuracy of pose estimation. This research contributes valuable insights and tools for advancing underwater technology, with far-reaching implications for scientific research, environmental monitoring, and industrial applications.

[Arxiv](https://arxiv.org/abs/2411.13988)