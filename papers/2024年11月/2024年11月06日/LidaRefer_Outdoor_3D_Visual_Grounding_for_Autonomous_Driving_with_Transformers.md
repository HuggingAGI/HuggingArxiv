# LidaRefer：使用 Transformer 实现自动驾驶的户外 3D 视觉定位

发布时间：2024年11月06日

`其他` `自动驾驶` `3D 视觉`

> LidaRefer: Outdoor 3D Visual Grounding for Autonomous Driving with Transformers

# 摘要

> 3D 视觉基础（VG）旨在根据自然语言描述在 3D 场景中定位相关对象或区域。尽管用于室内 3D VG 的最新方法已成功采用基于转换器的架构来捕获全局上下文信息并实现细粒度的跨模态融合，但由于室内和室外环境中点云的分布差异，它们不适用于室外环境。具体来说，首先，大量的 LiDAR 点云由于高维视觉特征，在转换器中需要不可接受的计算和内存资源。其次，稀疏 LiDAR 点云中的主要背景点和空白空间由于其不相关的视觉信息而使跨模态融合变得复杂。为了应对这些挑战，我们提出了 LidaRefer，这是一个基于转换器的 3D VG 框架，专为大规模室外场景设计。此外，在训练期间，我们引入了一种简单而有效的定位方法，该方法监督解码器的查询，不仅定位目标对象，还定位由于场景中显示相似属性或对语言描述的错误理解而可能被混淆为目标的模糊对象。这种监督通过学习它们的空间关系和属性的差异，增强了模型将模糊对象与目标区分开的能力。LidaRefer 在用于自动驾驶的 3D VG 数据集 Talk2Car-3D 上实现了最先进的性能，并在各种评估设置下有显著改进。

> 3D visual grounding (VG) aims to locate relevant objects or regions within 3D scenes based on natural language descriptions. Although recent methods for indoor 3D VG have successfully transformer-based architectures to capture global contextual information and enable fine-grained cross-modal fusion, they are unsuitable for outdoor environments due to differences in the distribution of point clouds between indoor and outdoor settings. Specifically, first, extensive LiDAR point clouds demand unacceptable computational and memory resources within transformers due to the high-dimensional visual features. Second, dominant background points and empty spaces in sparse LiDAR point clouds complicate cross-modal fusion owing to their irrelevant visual information. To address these challenges, we propose LidaRefer, a transformer-based 3D VG framework designed for large-scale outdoor scenes. Moreover, during training, we introduce a simple and effective localization method, which supervises the decoder's queries to localize not only a target object but also ambiguous objects that might be confused as the target due to the exhibition of similar attributes in a scene or the incorrect understanding of a language description. This supervision enhances the model's ability to distinguish ambiguous objects from a target by learning the differences in their spatial relationships and attributes. LidaRefer achieves state-of-the-art performance on Talk2Car-3D, a 3D VG dataset for autonomous driving, with significant improvements under various evaluation settings.

[Arxiv](https://arxiv.org/abs/2411.04351)