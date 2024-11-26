# RoboSpatial：为机器人技术中的 2D 和 3D 视觉语言模型教授空间理解

发布时间：2024年11月25日

`其他` `机器人` `空间理解`

> RoboSpatial: Teaching Spatial Understanding to 2D and 3D Vision-Language Models for Robotics

# 摘要

> 空间理解对于机器人依据所处环境做出可靠决策而言，是一项至关重要的能力。这一基础技能让机器人不仅能感知周边环境，还能在这个世界里进行有意义的推理和互动。在现代机器人技术中，视觉语言模型承担了这些能力，但由于训练数据来源的问题，在应用于空间推理场景时面临着重大挑战。这些数据来源使用的是通用图像数据集，往往缺少复杂的空间场景理解能力。比如，数据集没有解决参考框架的理解问题——空间关系需要清晰的上下文理解，不管是从自我中心、对象中心还是世界中心的角度，这样才能实现有效的现实世界交互。为解决此问题，我们推出了 RoboSpatial，这是一个大规模的空间理解数据集，由真实的室内和桌面场景以 3D 扫描和以自我为中心的图像形式捕获，并带有丰富的与机器人技术相关的空间信息注释。该数据集包含 100 万张图像、5000 次 3D 扫描和 300 万条注释的空间关系，还有配对的 2D 以自我为中心的图像和 3D 扫描，使其同时适用于 2D 和 3D 场景。我们的实验表明，用 RoboSpatial 训练的模型在诸如空间可供性预测、空间关系预测和机器人操作等下游任务上的表现优于基线。

> Spatial understanding is a crucial capability for robots to make grounded decisions based on their environment. This foundational skill enables robots not only to perceive their surroundings but also to reason about and interact meaningfully within the world. In modern robotics, these capabilities are taken on by visual language models, and they face significant challenges when applied to spatial reasoning context due to their training data sources. These sources utilize general-purpose image datasets, and they often lack sophisticated spatial scene understanding capabilities. For example, the datasets do not address reference frame comprehension - spatial relationships require clear contextual understanding, whether from an ego-centric, object-centric, or world-centric perspective, which allow for effective real-world interaction. To address this issue, we introduce RoboSpatial, a large-scale spatial understanding dataset consisting of real indoor and tabletop scenes captured as 3D scans and egocentric images, annotated with rich spatial information relevant to robotics. The dataset includes 1M images, 5K 3D scans, and 3M annotated spatial relationships, with paired 2D egocentric images and 3D scans to make it both 2D and 3D ready. Our experiments show that models trained with RoboSpatial outperform baselines on downstream tasks such as spatial affordance prediction, spatial relationship prediction, and robotics manipulation.

[Arxiv](https://arxiv.org/abs/2411.16537)