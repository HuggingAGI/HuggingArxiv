# 使用未训练的神经网络进行多模态可变形图像配准

发布时间：2024年11月04日

`其他` `神经网络`

> Multi-modal deformable image registration using untrained neural networks

# 摘要

> 图像配准技术通常假定要配准的图像属于某种类型（例如单模态与多模态、2D 与 3D、刚性与可变形），并且缺乏一种适用于所有条件下数据的通用方法。我们提出了一种利用神经网络进行图像表示的配准方法。我们的方法使用具有有限表示能力的未训练网络作为隐式先验来引导良好的配准。与以前专门针对特定数据类型的方法不同，我们的方法处理刚性和非刚性以及单模态和多模态配准，而无需更改模型或目标函数。我们使用各种数据集进行了全面的评估研究，并展示了有前景的性能。

> Image registration techniques usually assume that the images to be registered are of a certain type (e.g. single- vs. multi-modal, 2D vs. 3D, rigid vs. deformable) and there lacks a general method that can work for data under all conditions. We propose a registration method that utilizes neural networks for image representation. Our method uses untrained networks with limited representation capacity as an implicit prior to guide for a good registration. Unlike previous approaches that are specialized for specific data types, our method handles both rigid and non-rigid, as well as single- and multi-modal registration, without requiring changes to the model or objective function. We have performed a comprehensive evaluation study using a variety of datasets and demonstrated promising performance.

[Arxiv](https://arxiv.org/abs/2411.02672)