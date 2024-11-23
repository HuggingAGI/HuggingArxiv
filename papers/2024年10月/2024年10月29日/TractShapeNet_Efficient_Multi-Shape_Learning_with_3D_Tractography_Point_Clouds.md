# TractShapeNet：借助 3D 纤维束描记点云实现高效的多形状学习

发布时间：2024年10月29日

`其他` `脑科学`

> TractShapeNet: Efficient Multi-Shape Learning with 3D Tractography Point Clouds

# 摘要

> 脑成像研究显示，扩散磁共振成像束成像的几何形状描述符能够为大脑白质通路的研究及其与大脑功能的关联提供参考。在本项工作中，我们探究了运用深度学习模型来计算大脑白质连接形状度量的可能性。我们推出了一个全新框架——TractShapeNet，它借助束成像的点云表征来计算五项形状度量：长度、跨度、体积、总表面积以及不规则性。我们在涵盖 1065 名健康年轻成人的大型数据集上评估了该方法的表现。形状度量计算的实验表明，我们所提出的 TractShapeNet 在皮尔逊相关系数和归一化误差指标方面，均优于其他基于点云的神经网络模型。我们把推理运行时间结果与传统的形状计算工具 DSI-Studio 作了对比。我们的成果表明，深度学习方式能够实现更快速、更高效的形状度量计算。我们还在两个下游语言认知预测任务中开展了实验，结果显示来自 TractShapeNet 的形状度量与 DSI-Studio 计算所得的形状度量表现相近。我们的代码可在：https://github.com/SlicerDMRI/TractShapeNet 上获取。

> Brain imaging studies have demonstrated that diffusion MRI tractography geometric shape descriptors can inform the study of the brain's white matter pathways and their relationship to brain function. In this work, we investigate the possibility of utilizing a deep learning model to compute shape measures of the brain's white matter connections. We introduce a novel framework, TractShapeNet, that leverages a point cloud representation of tractography to compute five shape measures: length, span, volume, total surface area, and irregularity. We assess the performance of the method on a large dataset including 1065 healthy young adults. Experiments for shape measure computation demonstrate that our proposed TractShapeNet outperforms other point cloud-based neural network models in both the Pearson correlation coefficient and normalized error metrics. We compare the inference runtime results with the conventional shape computation tool DSI-Studio. Our results demonstrate that a deep learning approach enables faster and more efficient shape measure computation. We also conduct experiments on two downstream language cognition prediction tasks, showing that shape measures from TractShapeNet perform similarly to those computed by DSI-Studio. Our code will be available at: https://github.com/SlicerDMRI/TractShapeNet.

[Arxiv](https://arxiv.org/abs/2410.22099)