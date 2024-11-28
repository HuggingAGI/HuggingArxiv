# XR-MBT：借助具有学习深度点云配准的自监督来实现 XR 的多模态全身跟踪

发布时间：2024年11月27日

`其他` `增强现实/虚拟现实` `动作跟踪`

> XR-MBT: Multi-modal Full Body Tracking for XR through Self-Supervision with Learned Depth Point Cloud Registration

# 摘要

> 跟踪 XR（增强现实/虚拟现实）设备中用户的全身动作是营造真实社交临场感的关键挑战。由于缺乏专用腿部传感器，现有的身体跟踪方法采用合成手段，依据来自头部和控制器跟踪的 3 点信号生成合理动作。为实现混合现实功能，现代 XR 设备能借助可用传感器与专用机器学习模型估算耳机周边的深度信息。但这种以自我为中心的深度感知无法直接驱动身体，因其未注册且受限于有限视野和身体自身遮挡而不完整。我们首次提议借助可用的深度感知信号与自我监督，学习一个能在 XR 设备上实时跟踪全身动作的多模态姿态估计模型。我们展示了当下的 3 点动作合成模型如何通过语义点云编码器网络结合残差网络拓展至点云模态以进行多模态姿态估计。这些模块以自我监督的方式共同训练，利用真实未注册的点云和从动作捕捉获取的模拟数据的组合。我们将我们的方法与数个 XR 身体跟踪的前沿系统作比较，结果表明我们的方法能精准跟踪各类身体动作。XR-MBT 首次在 XR 中实现腿部跟踪，而基于部分身体跟踪的传统合成方法则存在盲区。

> Tracking the full body motions of users in XR (AR/VR) devices is a fundamental challenge to bring a sense of authentic social presence. Due to the absence of dedicated leg sensors, currently available body tracking methods adopt a synthesis approach to generate plausible motions given a 3-point signal from the head and controller tracking. In order to enable mixed reality features, modern XR devices are capable of estimating depth information of the headset surroundings using available sensors combined with dedicated machine learning models. Such egocentric depth sensing cannot drive the body directly, as it is not registered and is incomplete due to limited field-of-view and body self-occlusions. For the first time, we propose to leverage the available depth sensing signal combined with self-supervision to learn a multi-modal pose estimation model capable of tracking full body motions in real time on XR devices. We demonstrate how current 3-point motion synthesis models can be extended to point cloud modalities using a semantic point cloud encoder network combined with a residual network for multi-modal pose estimation. These modules are trained jointly in a self-supervised way, leveraging a combination of real unregistered point clouds and simulated data obtained from motion capture. We compare our approach against several state-of-the-art systems for XR body tracking and show that our method accurately tracks a diverse range of body motions. XR-MBT tracks legs in XR for the first time, whereas traditional synthesis approaches based on partial body tracking are blind.

[Arxiv](https://arxiv.org/abs/2411.18377)