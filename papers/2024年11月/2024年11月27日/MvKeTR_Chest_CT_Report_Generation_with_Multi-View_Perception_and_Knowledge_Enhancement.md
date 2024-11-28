# MvKeTR：通过多视图感知和知识增强实现胸部 CT 报告生成

发布时间：2024年11月27日

`LLM应用` `CT 报告生成`

> MvKeTR: Chest CT Report Generation with Multi-View Perception and Knowledge Enhancement

# 摘要

> CT 报告生成（CTRG）旨在自动为 3D 体积生成诊断报告，以减轻临床医生的工作负担，提升患者护理水平。尽管具有临床价值，但现有的研究未能有效整合来自多个解剖视图的诊断信息，也缺乏准确可靠诊断所必需的相关临床专业知识。为克服这些局限，我们提出了一种全新的多视图感知知识增强型 Transformer（MvKeTR），以模拟临床医生的诊断工作流程。正如放射科医生会先从多个平面查看 CT 扫描，具有视图感知注意力的多视图感知聚合器（MVPA）能有效地整合来自多个解剖视图的诊断信息。接着，受放射科医生参考相关临床记录来指导诊断决策的启发，跨模态知识增强器（CMKE）会根据查询体积检索最相似的报告，将领域知识融入诊断过程。此外，我们采用具有可学习非线性激活函数的 Kolmogorov-Arnold 网络（KANs），而非传统的 MLP 作为两个模块的基础构建块，从而更好地捕捉 CT 解读中复杂的诊断模式。在公共 CTRG-Chest-548K 数据集上开展的大量实验表明，我们的方法在所有指标上均超越了先前的最先进模型。

> CT report generation (CTRG) aims to automatically generate diagnostic reports for 3D volumes, relieving clinicians' workload and improving patient care. Despite clinical value, existing works fail to effectively incorporate diagnostic information from multiple anatomical views and lack related clinical expertise essential for accurate and reliable diagnosis. To resolve these limitations, we propose a novel Multi-view perception Knowledge-enhanced Tansformer (MvKeTR) to mimic the diagnostic workflow of clinicians. Just as radiologists first examine CT scans from multiple planes, a Multi-View Perception Aggregator (MVPA) with view-aware attention effectively synthesizes diagnostic information from multiple anatomical views. Then, inspired by how radiologists further refer to relevant clinical records to guide diagnostic decision-making, a Cross-Modal Knowledge Enhancer (CMKE) retrieves the most similar reports based on the query volume to incorporate domain knowledge into the diagnosis procedure. Furthermore, instead of traditional MLPs, we employ Kolmogorov-Arnold Networks (KANs) with learnable nonlinear activation functions as the fundamental building blocks of both modules to better capture intricate diagnostic patterns in CT interpretation. Extensive experiments on the public CTRG-Chest-548K dataset demonstrate that our method outpaces prior state-of-the-art models across all metrics.

[Arxiv](https://arxiv.org/abs/2411.18309)