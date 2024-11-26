# 用于鲁棒遥感视觉问答的文本引导式从粗到细融合网络

发布时间：2024年11月24日

`其他` `视觉问答`

> Text-Guided Coarse-to-Fine Fusion Network for Robust Remote Sensing Visual Question Answering

# 摘要

> 遥感视觉问答（RSVQA）备受关注。然而，当下的 RSVQA 方法受限于光学传感器的成像机制，尤其在云层覆盖和低光照这类棘手的条件下。鉴于合成孔径雷达（SAR）具备全天候、全时段的成像能力，探究光学-SAR 图像的整合对于提升 RSVQA 性能极为关键。在本项工作中，我们提出了一个文本引导的由粗到精融合网络（TGFNet），它借助问题文本与多源图像间的语义关系，引导网络在特征层面进行互补融合。具体来说，我们开发了一个文本引导的由粗到精注意力细化（CFAR）模块，用于聚焦复杂遥感图像中与问题相关的关键区域。该模块通过关键区域路由，逐步将注意力从宽泛区域转向更精细的细节，增强了模型对相关区域的关注能力。此外，我们还提出了一个自适应多专家融合（AMEF）模块，能够动态整合不同专家，实现光学和 SAR 特征的自适应融合。另外，我们创建了首个用于评估光学-SAR RSVQA 方法的大规模基准数据集，涵盖 6,008 对精准对齐的光学-SAR 图像对以及 1,036,694 对横跨 16 种不同问题类型（包括复杂的关系推理问题）的精准标注问答对。在该数据集上开展的大量实验表明，我们的 TGFNet 有效整合了光学和 SAR 图像之间的互补信息，显著提升了模型在挑战性场景中的性能。数据集获取地址：https://github.com/mmic-lcl/ 。
  索引术语：遥感视觉问答，多源数据融合，多模态，遥感，OPT-SAR。

> Remote Sensing Visual Question Answering (RSVQA) has gained significant research interest. However, current RSVQA methods are limited by the imaging mechanisms of optical sensors, particularly under challenging conditions such as cloud-covered and low-light scenarios. Given the all-time and all-weather imaging capabilities of Synthetic Aperture Radar (SAR), it is crucial to investigate the integration of optical-SAR images to improve RSVQA performance. In this work, we propose a Text-guided Coarse-to-Fine Fusion Network (TGFNet), which leverages the semantic relationships between question text and multi-source images to guide the network toward complementary fusion at the feature level. Specifically, we develop a Text-guided Coarse-to-Fine Attention Refinement (CFAR) module to focus on key areas related to the question in complex remote sensing images. This module progressively directs attention from broad areas to finer details through key region routing, enhancing the model's ability to focus on relevant regions. Furthermore, we propose an Adaptive Multi-Expert Fusion (AMEF) module that dynamically integrates different experts, enabling the adaptive fusion of optical and SAR features. In addition, we create the first large-scale benchmark dataset for evaluating optical-SAR RSVQA methods, comprising 6,008 well-aligned optical-SAR image pairs and 1,036,694 well-labeled question-answer pairs across 16 diverse question types, including complex relational reasoning questions. Extensive experiments on the proposed dataset demonstrate that our TGFNet effectively integrates complementary information between optical and SAR images, significantly improving the model's performance in challenging scenarios. The dataset is available at: https://github.com/mmic-lcl/.
  Index Terms: Remote Sensing Visual Question Answering, Multi-source Data Fusion, Multimodal, Remote Sensing, OPT-SAR.

[Arxiv](https://arxiv.org/abs/2411.15770)