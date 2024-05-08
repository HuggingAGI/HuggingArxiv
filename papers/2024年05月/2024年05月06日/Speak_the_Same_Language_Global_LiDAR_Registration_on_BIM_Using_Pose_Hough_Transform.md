# “共语”全球激光雷达注册：利用姿态霍夫变换在BIM上的精准对接

发布时间：2024年05月06日

`Agent

这篇论文探讨了如何通过全局点云注册技术将机器人传感数据（激光雷达点云）与建筑信息模型（BIM）对齐，这是一种跨模态的注册方法，旨在实现不同技术之间的沟通和统一。这种方法涉及特征提取和姿态估算，可以被视为一种智能代理（Agent）的行为，因为它涉及到处理和解释来自不同源的数据，并执行特定的任务（如姿态估算）以实现目标（如点云与BIM的对齐）。因此，这篇论文更符合Agent分类，而不是RAG、LLM应用或LLM理论，因为它的重点在于机器人技术和建筑信息模型的集成，而不是语言模型或其理论。` `建筑信息模型` `机器人技术`

> Speak the Same Language: Global LiDAR Registration on BIM Using Pose Hough Transform

# 摘要

> 建筑与机器人传感数据源自不同源，关联于各异的参考框架。本研究旨在通过全局点云注册技术，将激光雷达点云与建筑信息模型（BIM）精准对齐，以期在两种技术间架起沟通的桥梁，实现“语言”的统一。我们设计了一种跨模态注册方法，从前端的数据提取到后端的姿态估算，一气呵成。前端，我们识别墙壁并捕捉交角以提取特征；后端，则运用霍夫变换进行姿态估算，筛选出多个候选姿态，最终通过墙壁像素相关性验证最佳姿态。为验证方法的实效性，我们在一所大学的宏伟建筑内进行了多轮实地测试，使用了两种不同类型的激光雷达传感器。我们不仅分享了研究成果，还计划将收集的数据集公之于众，以飨同行。

> The construction and robotic sensing data originate from disparate sources and are associated with distinct frames of reference. The primary objective of this study is to align LiDAR point clouds with building information modeling (BIM) using a global point cloud registration approach, aimed at establishing a shared understanding between the two modalities, i.e., ``speak the same language''. To achieve this, we design a cross-modality registration method, spanning from front end the back end. At the front end, we extract descriptors by identifying walls and capturing the intersected corners. Subsequently, for the back-end pose estimation, we employ the Hough transform for pose estimation and estimate multiple pose candidates. The final pose is verified by wall-pixel correlation. To evaluate the effectiveness of our method, we conducted real-world multi-session experiments in a large-scale university building, involving two different types of LiDAR sensors. We also report our findings and plan to make our collected dataset open-sourced.

[Arxiv](https://arxiv.org/abs/2405.03969)