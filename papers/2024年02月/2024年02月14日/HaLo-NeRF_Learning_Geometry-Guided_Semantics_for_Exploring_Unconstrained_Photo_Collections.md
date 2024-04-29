# HaLo-NeRF：探索自由式照片集的几何引导语义学习。

发布时间：2024年02月14日

`分类：LLM应用

这篇论文的摘要描述了一种结合了视觉与语言模型的定位系统，该系统利用互联网上的图像和文本信息来理解和导航大型旅游地标。虽然它涉及到了视觉和语言模型的应用，但主要关注的是如何利用大型语言模型（LLM）从互联网文本元数据中获取语义信息，以增强对场景的理解和导航。因此，这篇论文最符合"LLM应用"这一分类。` `3D建模`

> HaLo-NeRF: Learning Geometry-Guided Semantics for Exploring Unconstrained Photo Collections

# 摘要

> 互联网上的图片集，由众多摄影师捕捉的照片组成，为数字化探索大型旅游地标提供了可能性。但以往研究多集中于几何重建与可视化，忽略了语言在导航和精细理解中的语义界面作用。在3D领域的现有方法中，视觉与语言模型被用作2D视觉语义的强大预设，尽管这些模型对广泛的视觉语义有深刻理解，却难以应对无约束的照片集合，尤其是那些展示旅游地标的，因为它们缺少建筑学的专业知识。本研究提出了一种定位系统，该系统结合了最先进的视觉与语言模型，并对其进行了调整，以理解大型地标场景的语义，将场景的神经表示与描述场景内语义区域的文本相连接。我们利用大规模互联网数据，其中包含相似地标的图像和弱相关的文本信息，以此来丰富模型的精细知识。我们的方法基于一个前提：物理空间中的图像可以为新概念的定位提供强有力的监督信号，而这些概念的语义可能通过大型语言模型从互联网文本元数据中获得。我们利用场景视图之间的对应关系来引导空间语义的理解，并为3D兼容的分割提供指导，最终形成体积场景表示。我们的研究结果表明，HaLo-NeRF能够精确地定位与建筑地标相关的多种语义概念，超越了其他3D模型和2D分割基线的结果。项目详情可访问我们的网页 https://tau-vailab.github.io/HaLo-NeRF/。

> Internet image collections containing photos captured by crowds of photographers show promise for enabling digital exploration of large-scale tourist landmarks. However, prior works focus primarily on geometric reconstruction and visualization, neglecting the key role of language in providing a semantic interface for navigation and fine-grained understanding. In constrained 3D domains, recent methods have leveraged vision-and-language models as a strong prior of 2D visual semantics. While these models display an excellent understanding of broad visual semantics, they struggle with unconstrained photo collections depicting such tourist landmarks, as they lack expert knowledge of the architectural domain. In this work, we present a localization system that connects neural representations of scenes depicting large-scale landmarks with text describing a semantic region within the scene, by harnessing the power of SOTA vision-and-language models with adaptations for understanding landmark scene semantics. To bolster such models with fine-grained knowledge, we leverage large-scale Internet data containing images of similar landmarks along with weakly-related textual information. Our approach is built upon the premise that images physically grounded in space can provide a powerful supervision signal for localizing new concepts, whose semantics may be unlocked from Internet textual metadata with large language models. We use correspondences between views of scenes to bootstrap spatial understanding of these semantics, providing guidance for 3D-compatible segmentation that ultimately lifts to a volumetric scene representation. Our results show that HaLo-NeRF can accurately localize a variety of semantic concepts related to architectural landmarks, surpassing the results of other 3D models as well as strong 2D segmentation baselines. Our project page is at https://tau-vailab.github.io/HaLo-NeRF/.

[Arxiv](https://arxiv.org/abs/2404.16845)