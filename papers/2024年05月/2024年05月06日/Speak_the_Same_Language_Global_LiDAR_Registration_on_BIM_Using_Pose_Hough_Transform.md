# “共语”全球激光雷达注册：利用姿态霍夫变换在BIM上的精准对接

发布时间：2024年05月06日

`Agent

这篇论文主要探讨了如何通过全局点云注册技术将机器人传感数据（激光雷达点云）与建筑信息模型（BIM）对齐，以实现跨模态的信息整合。这涉及到机器人技术在建筑领域的应用，以及如何通过算法和方法来实现不同数据源之间的有效沟通。因此，这篇论文更符合Agent分类，因为它关注的是机器人系统如何与环境（建筑模型）交互，以及如何通过技术手段实现这种交互。` `建筑信息模型` `机器人技术`

> Speak the Same Language: Global LiDAR Registration on BIM Using Pose Hough Transform

# 摘要

> 建筑与机器人传感数据源自不同源泉，各自拥有独特的参考框架。本研究旨在通过全局点云注册技术，将激光雷达点云与建筑信息模型（BIM）精准对齐，以期在两者间架起沟通的桥梁，实现“语言”的统一。为此，我们精心设计了一种跨模态注册方案，贯穿前端至后端。在前端，我们通过识别墙壁并捕捉其交角来提取特征描述符。后端则采用霍夫变换进行姿态估计，并生成多个姿态候选，最终通过墙壁像素相关性验证确定最佳姿态。为验证此方法的实效性，我们在一所大学的宏伟建筑内进行了多轮实地测试，运用了两种不同型号的激光雷达传感器。此外，我们还将分享研究成果，并计划将所采集的数据集对外开放，以供同行研究。

> The construction and robotic sensing data originate from disparate sources and are associated with distinct frames of reference. The primary objective of this study is to align LiDAR point clouds with building information modeling (BIM) using a global point cloud registration approach, aimed at establishing a shared understanding between the two modalities, i.e., ``speak the same language''. To achieve this, we design a cross-modality registration method, spanning from front end the back end. At the front end, we extract descriptors by identifying walls and capturing the intersected corners. Subsequently, for the back-end pose estimation, we employ the Hough transform for pose estimation and estimate multiple pose candidates. The final pose is verified by wall-pixel correlation. To evaluate the effectiveness of our method, we conducted real-world multi-session experiments in a large-scale university building, involving two different types of LiDAR sensors. We also report our findings and plan to make our collected dataset open-sourced.

[Arxiv](https://arxiv.org/abs/2405.03969)