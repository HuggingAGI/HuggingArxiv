# “一劳永逸”：基于点云的 3D 物体检测的多领域联合训练

发布时间：2024年11月03日

`其他` `计算机视觉` `3D 检测`

> One for All: Multi-Domain Joint Training for Point Cloud Based 3D Object Detection

# 摘要

> 当下计算机视觉的潮流是运用一个通用模型来应对所有各类任务。要达成这样的通用模型，必然得融合多领域数据进行联合训练，从而在多个问题场景中学习。不过，在基于点云的 3D 对象检测里，这种多领域联合训练困难重重，因为不同数据集的点云之间存在较大的领域差距，从而引发严重的领域干扰问题。在本文中，我们提出了	extbf{OneDet3D}，这是一个通用的全能模型，在\emph{相同}的框架内，仅用\emph{一组}参数，就能解决涵盖不同室内和室外场景等不同领域的 3D 检测。我们提出了由路由机制引导的在散射和上下文中的领域感知分区，以此解决数据干扰问题，还进一步融入文本模态进行语言引导分类，以统一多数据集标签空间，并缓解类别干扰问题。完全稀疏的结构和无锚点的头部，进一步适配了规模差异显著的点云。大量实验证明，OneDet3D 具备强大的通用能力，仅用一个训练好的模型就能搞定几乎所有 3D 对象检测任务。

> The current trend in computer vision is to utilize one universal model to address all various tasks. Achieving such a universal model inevitably requires incorporating multi-domain data for joint training to learn across multiple problem scenarios. In point cloud based 3D object detection, however, such multi-domain joint training is highly challenging, because large domain gaps among point clouds from different datasets lead to the severe domain-interference problem. In this paper, we propose \textbf{OneDet3D}, a universal one-for-all model that addresses 3D detection across different domains, including diverse indoor and outdoor scenes, within the \emph{same} framework and only \emph{one} set of parameters. We propose the domain-aware partitioning in scatter and context, guided by a routing mechanism, to address the data interference issue, and further incorporate the text modality for a language-guided classification to unify the multi-dataset label spaces and mitigate the category interference issue. The fully sparse structure and anchor-free head further accommodate point clouds with significant scale disparities. Extensive experiments demonstrate the strong universal ability of OneDet3D to utilize only one trained model for addressing almost all 3D object detection tasks.

[Arxiv](https://arxiv.org/abs/2411.01584)