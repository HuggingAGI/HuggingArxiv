# ICH-SCNet：使用 CLIP 引导的 SAM 机制的脑出血分割和预后分类网络

发布时间：2024年11月07日

`其他`

> ICH-SCNet: Intracerebral Hemorrhage Segmentation and Prognosis Classification Network Using CLIP-guided SAM mechanism

# 摘要

> 脑内出血（ICH）是中风最致命的亚型，其特点是残疾发生率高。ICH 区域的准确分割和预后预测对于制定和完善 ICH 后患者的治疗计划至关重要。然而，现有的方法独立处理这两个任务，并且主要仅关注成像数据，从而忽略了任务和模态之间的内在相关性。本文介绍了一个多任务网络 ICH-SCNet，专为 ICH 分割和预后分类而设计。具体来说，我们集成了一个 SAM-CLIP 跨模态交互机制，将医学文本和分割辅助信息与神经影像学数据相结合，以增强跨模态特征识别。此外，我们开发了一个有效的特征融合模块和一个多任务损失函数，以进一步提高性能。在 ICH 数据集上的大量实验表明，我们的方法超过了其他最先进的方法。它在分类任务的整体性能方面表现出色，并且在所有分割任务指标上都优于竞争模型。

> Intracerebral hemorrhage (ICH) is the most fatal subtype of stroke and is characterized by a high incidence of disability. Accurate segmentation of the ICH region and prognosis prediction are critically important for developing and refining treatment plans for post-ICH patients. However, existing approaches address these two tasks independently and predominantly focus on imaging data alone, thereby neglecting the intrinsic correlation between the tasks and modalities. This paper introduces a multi-task network, ICH-SCNet, designed for both ICH segmentation and prognosis classification. Specifically, we integrate a SAM-CLIP cross-modal interaction mechanism that combines medical text and segmentation auxiliary information with neuroimaging data to enhance cross-modal feature recognition. Additionally, we develop an effective feature fusion module and a multi-task loss function to improve performance further. Extensive experiments on an ICH dataset reveal that our approach surpasses other state-of-the-art methods. It excels in the overall performance of classification tasks and outperforms competing models in all segmentation task metrics.

[Arxiv](https://arxiv.org/abs/2411.04656)