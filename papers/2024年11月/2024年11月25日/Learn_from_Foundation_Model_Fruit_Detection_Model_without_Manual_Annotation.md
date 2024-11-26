# 从基础模型中学习：无需人工标注的水果检测模型

发布时间：2024年11月25日

`LLM应用` `水果检测`

> Learn from Foundation Model: Fruit Detection Model without Manual Annotation

# 摘要

> 近期大型基础模型的重大突破，让将在海量数据集上预训练的知识迁移到数据有限的领域成为可能，农业便是数据匮乏的领域之一。本研究提出了一个无需人工标注、能从基础模型训练出有效且特定领域小型模型的框架。我们的方法以 SDM（分割 - 描述 - 匹配）为起点，此阶段借助了两个基础模型：用于分割的 SAM2（图像和视频中的任何事物分割）以及用于零样本开放词汇分类的 OpenCLIP（开放对比语言 - 图像预训练）。在第二阶段，采用了一种新颖的知识蒸馏机制，从 SDM 中提炼出紧凑、可在边缘部署的模型，提升了推理速度和感知精度。整套方法，名为 SDM-D（分割 - 描述 - 匹配 - 蒸馏），在各类水果检测任务（对象检测、语义分割和实例分割）中表现出众，无需人工标注，其性能几乎与使用大量标签训练的模型持平。特别要指出的是，SDM-D 在所有测试的水果检测数据集中，都胜过 Grounding SAM 和 YOLO-World 等开放集检测方法。另外，我们推出了 MegaFruits，这是一个涵盖超过 25,000 张图像的综合水果分割数据集，所有代码和数据集都在 https://github.com/AgRoboticsResearch/SDM-D.git 上公开。

> Recent breakthroughs in large foundation models have enabled the possibility of transferring knowledge pre-trained on vast datasets to domains with limited data availability. Agriculture is one of the domains that lacks sufficient data. This study proposes a framework to train effective, domain-specific, small models from foundation models without manual annotation. Our approach begins with SDM (Segmentation-Description-Matching), a stage that leverages two foundation models: SAM2 (Segment Anything in Images and Videos) for segmentation and OpenCLIP (Open Contrastive Language-Image Pretraining) for zero-shot open-vocabulary classification. In the second stage, a novel knowledge distillation mechanism is utilized to distill compact, edge-deployable models from SDM, enhancing both inference speed and perception accuracy. The complete method, termed SDM-D (Segmentation-Description-Matching-Distilling), demonstrates strong performance across various fruit detection tasks object detection, semantic segmentation, and instance segmentation) without manual annotation. It nearly matches the performance of models trained with abundant labels. Notably, SDM-D outperforms open-set detection methods such as Grounding SAM and YOLO-World on all tested fruit detection datasets. Additionally, we introduce MegaFruits, a comprehensive fruit segmentation dataset encompassing over 25,000 images, and all code and datasets are made publicly available at https://github.com/AgRoboticsResearch/SDM-D.git.

[Arxiv](https://arxiv.org/abs/2411.16196)