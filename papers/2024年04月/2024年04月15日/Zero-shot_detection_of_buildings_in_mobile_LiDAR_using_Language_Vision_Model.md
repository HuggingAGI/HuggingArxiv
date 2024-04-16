# 借助语言视觉模型，实现移动激光雷达中建筑物的零次检测。

发布时间：2024年04月15日

`LLM应用` `三维数据处理` `计算机视觉`

> Zero-shot detection of buildings in mobile LiDAR using Language Vision Model

# 摘要

> 近期研究显示，语言视觉模型（LVMs）在二维图像处理上已超越现有顶尖技术，激发了将其应用于三维数据的兴趣。尽管LVMs能高效处理多种二维视觉任务，但在三维点云处理上却遭遇难题。三维数据的特征提取更为复杂，且受限于数据规模庞大和采集标注成本高昂，导致可用数据集相对匮乏。此外，针对点云的LVMs构建更是难上加难，因其对数据量和训练时间的需求巨大。为应对这些挑战，本研究致力于：一、利用基于球面投影的Grounded SAM实现三维到二维的转换；二、通过合成数据实验，评估其在连接合成数据与现实世界数据方面的效果。实验结果显示，准确度达到0.96，IoU为0.85，精确度和召回率分别为0.92和0.91，F1分数为0.92，验证了其巨大潜力。尽管如此，未来研究还需解决球面图像生成中的遮挡问题和多标签点的像素级重叠等难题。

> Recent advances have demonstrated that Language Vision Models (LVMs) surpass the existing State-of-the-Art (SOTA) in two-dimensional (2D) computer vision tasks, motivating attempts to apply LVMs to three-dimensional (3D) data. While LVMs are efficient and effective in addressing various downstream 2D vision tasks without training, they face significant challenges when it comes to point clouds, a representative format for representing 3D data. It is more difficult to extract features from 3D data and there are challenges due to large data sizes and the cost of the collection and labelling, resulting in a notably limited availability of datasets. Moreover, constructing LVMs for point clouds is even more challenging due to the requirements for large amounts of data and training time. To address these issues, our research aims to 1) apply the Grounded SAM through Spherical Projection to transfer 3D to 2D, and 2) experiment with synthetic data to evaluate its effectiveness in bridging the gap between synthetic and real-world data domains. Our approach exhibited high performance with an accuracy of 0.96, an IoU of 0.85, precision of 0.92, recall of 0.91, and an F1 score of 0.92, confirming its potential. However, challenges such as occlusion problems and pixel-level overlaps of multi-label points during spherical image generation remain to be addressed in future studies.

![借助语言视觉模型，实现移动激光雷达中建筑物的零次检测。](../../../paper_images/2404.09931/full_synthcity_final.png)

![借助语言视觉模型，实现移动激光雷达中建筑物的零次检测。](../../../paper_images/2404.09931/work_flow2.png)

![借助语言视觉模型，实现移动激光雷达中建筑物的零次检测。](../../../paper_images/2404.09931/spherical_coordinates.png)

![借助语言视觉模型，实现移动激光雷达中建筑物的零次检测。](../../../paper_images/2404.09931/table_comparison.png)

![借助语言视觉模型，实现移动激光雷达中建筑物的零次检测。](../../../paper_images/2404.09931/FP_visualization.png)

![借助语言视觉模型，实现移动激光雷达中建筑物的零次检测。](../../../paper_images/2404.09931/mapping_visualization.png)

[Arxiv](https://arxiv.org/abs/2404.09931)