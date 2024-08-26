# VFM-Det：借助大型基础模型，迈向卓越的车辆检测性能

发布时间：2024年08月23日

`LLM应用` `计算机视觉`

> VFM-Det: Towards High-Performance Vehicle Detection via Large Foundation Models

# 摘要

> 当前的车辆检测器多通过在预训练骨干网络上训练典型检测器来实现，但这些方法可能因使用非专为车辆设计的大型模型而效果有限。此外，它们过度依赖视觉特征，忽视了车辆语义信息与视觉表示的匹配。为此，我们引入了基于预训练车辆模型VehicleMAE和语言模型T5的VFM-Det检测范式，通过区域提议框架和VehicleMAE增强特征。特别地，我们设计的VAtt2Vec模块能预测车辆属性并转化为特征向量，通过对比学习提升视觉特征。实验证明，VFM-Det在Cityscapes数据集上显著提升了检测性能，源代码即将在GitHub上公开。

> Existing vehicle detectors are usually obtained by training a typical detector (e.g., YOLO, RCNN, DETR series) on vehicle images based on a pre-trained backbone (e.g., ResNet, ViT). Some researchers also exploit and enhance the detection performance using pre-trained large foundation models. However, we think these detectors may only get sub-optimal results because the large models they use are not specifically designed for vehicles. In addition, their results heavily rely on visual features, and seldom of they consider the alignment between the vehicle's semantic information and visual representations. In this work, we propose a new vehicle detection paradigm based on a pre-trained foundation vehicle model (VehicleMAE) and a large language model (T5), termed VFM-Det. It follows the region proposal-based detection framework and the features of each proposal can be enhanced using VehicleMAE. More importantly, we propose a new VAtt2Vec module that predicts the vehicle semantic attributes of these proposals and transforms them into feature vectors to enhance the vision features via contrastive learning. Extensive experiments on three vehicle detection benchmark datasets thoroughly proved the effectiveness of our vehicle detector. Specifically, our model improves the baseline approach by $+5.1\%$, $+6.2\%$ on the $AP_{0.5}$, $AP_{0.75}$ metrics, respectively, on the Cityscapes dataset.The source code of this work will be released at https://github.com/Event-AHU/VFM-Det.

[Arxiv](https://arxiv.org/abs/2408.13031)