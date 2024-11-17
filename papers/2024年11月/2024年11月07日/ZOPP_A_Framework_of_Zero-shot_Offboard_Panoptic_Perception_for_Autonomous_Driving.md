# ZOPP：自动驾驶零样本离线全景感知的框架

发布时间：2024年11月07日

`其他` `自动驾驶` `自动标注`

> ZOPP: A Framework of Zero-shot Offboard Panoptic Perception for Autonomous Driving

# 摘要

> Offboard 感知致力于为自动驾驶（AD）场景自动生成高品质的 3D 标签。现有的 Offboard 方法侧重于采用封闭集分类法的 3D 对象检测，在快速演变的感知任务中难以达到人类水平的识别能力。鉴于对人类标签的高度依赖以及数据不平衡和稀疏性的普遍存在，能够满足感知任务不同需求、针对自动驾驶场景中各类元素的 Offboard 自动标注的统一框架尚未得到充分挖掘。本文中，我们为自动驾驶场景提出了一种全新的多模态零样本 Offboard 全景感知（ZOPP）框架。ZOPP 融合了视觉基础模型强大的零样本识别能力以及由点云得出的 3D 表示。据我们了解，ZOPP 在自动驾驶场景的多模态全景感知和自动标注领域堪称开创性的尝试。我们在 Waymo 开放数据集上开展了全面的实证研究和评估，以验证所提出的 ZOPP 在各种感知任务中的表现。为进一步探究我们所提出的 ZOPP 的可用性和可扩展性，我们还在下游应用中进行了实验。结果进一步彰显了我们的 ZOPP 在实际场景中的巨大潜力。

> Offboard perception aims to automatically generate high-quality 3D labels for autonomous driving (AD) scenes. Existing offboard methods focus on 3D object detection with closed-set taxonomy and fail to match human-level recognition capability on the rapidly evolving perception tasks. Due to heavy reliance on human labels and the prevalence of data imbalance and sparsity, a unified framework for offboard auto-labeling various elements in AD scenes that meets the distinct needs of perception tasks is not being fully explored. In this paper, we propose a novel multi-modal Zero-shot Offboard Panoptic Perception (ZOPP) framework for autonomous driving scenes. ZOPP integrates the powerful zero-shot recognition capabilities of vision foundation models and 3D representations derived from point clouds. To the best of our knowledge, ZOPP represents a pioneering effort in the domain of multi-modal panoptic perception and auto labeling for autonomous driving scenes. We conduct comprehensive empirical studies and evaluations on Waymo open dataset to validate the proposed ZOPP on various perception tasks. To further explore the usability and extensibility of our proposed ZOPP, we also conduct experiments in downstream applications. The results further demonstrate the great potential of our ZOPP for real-world scenarios.

[Arxiv](https://arxiv.org/abs/2411.05311)