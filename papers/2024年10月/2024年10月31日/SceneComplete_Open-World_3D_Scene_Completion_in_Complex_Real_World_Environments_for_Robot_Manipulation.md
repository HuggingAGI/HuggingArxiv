# SceneComplete：用于机器人操作的复杂现实世界环境中的开放世界 3D 场景补全

发布时间：2024年10月31日

`其他` `机器人` `3D 场景`

> SceneComplete: Open-World 3D Scene Completion in Complex Real World Environments for Robot Manipulation

# 摘要

> 在日常杂乱的环境中，机器人要谨慎操作，就得对 3D 场景有精准的理解，这样才能稳定可靠地抓取和放置物体，避免误撞其他物体。一般来说，我们得依据有限的输入（比如单个 RGB-D 图像）来构建这种复杂场景的 3D 解释。我们介绍了 SceneComplete，这是一个能从单一视角构建完整、分段 3D 场景模型的系统。它提供了一条新颖的途径，将通用的预训练感知模块（视觉语言、分割、图像修复、图像转 3D 以及姿态估计）加以组合，从而获取高精度的结果。我们在一个大型基准数据集中展示了它相对于真实模型的准确性和有效性，并且表明其精准的全对象重建能够促成稳健的抓取提议生成，就连灵巧手也不例外。

> Careful robot manipulation in every-day cluttered environments requires an accurate understanding of the 3D scene, in order to grasp and place objects stably and reliably and to avoid mistakenly colliding with other objects. In general, we must construct such a 3D interpretation of a complex scene based on limited input, such as a single RGB-D image. We describe SceneComplete, a system for constructing a complete, segmented, 3D model of a scene from a single view. It provides a novel pipeline for composing general-purpose pretrained perception modules (vision-language, segmentation, image-inpainting, image-to-3D, and pose-estimation) to obtain high-accuracy results. We demonstrate its accuracy and effectiveness with respect to ground-truth models in a large benchmark dataset and show that its accurate whole-object reconstruction enables robust grasp proposal generation, including for a dexterous hand.

[Arxiv](https://arxiv.org/abs/2410.23643)