# Re-Mix：精调数据混合，助力大规模模仿学习

发布时间：2024年08月26日

`Agent` `机器人` `人工智能`

> Re-Mix: Optimizing Data Mixtures for Large Scale Imitation Learning

# 摘要

> 随着模仿学习数据集的不断扩大，机器人基础模型的训练目标日益明确。尽管数据选择在视觉和自然语言处理领域至关重要，但机器人领域的相关研究却鲜少探讨应基于何种数据进行模型训练。本研究聚焦于如何为机器人基础模型预训练选择和权衡不同数据子集。我们采用分布式鲁棒优化（DRO）策略，旨在提升所有潜在下游应用场景的性能。Re-Mix方法应运而生，它有效应对了DRO在机器人数据集应用中的诸多挑战，如动作空间和动态的多样性。通过早期停止、动作归一化及离散化等手段，Re-Mix确保了方法的稳健性。实验结果显示，在最大的开源机器人操作数据集Open X-Embodiment上，精心筛选的数据对下游性能影响显著。Re-Mix学得的领域权重在平均水平上较均匀权重提升38%，在训练现有通用机器人策略（RT-X模型）的数据集上，较人工选择权重提升32%。

> Increasingly large imitation learning datasets are being collected with the goal of training foundation models for robotics. However, despite the fact that data selection has been of utmost importance in vision and natural language processing, little work in robotics has questioned what data such models should actually be trained on. In this work we investigate how to weigh different subsets or ``domains'' of robotics datasets for robot foundation model pre-training. Concrete, we use distributionally robust optimization (DRO) to maximize worst-case performance across all possible downstream domains. Our method, Re-Mix, addresses the wide range of challenges that arise when applying DRO to robotics datasets including variability in action spaces and dynamics across different datasets. Re-Mix employs early stopping, action normalization, and discretization to counteract these issues. Through extensive experimentation on the largest open-source robot manipulation dataset, the Open X-Embodiment dataset, we demonstrate that data curation can have an outsized impact on downstream performance. Specifically, domain weights learned by Re-Mix outperform uniform weights by 38\% on average and outperform human-selected weights by 32\% on datasets used to train existing generalist robot policies, specifically the RT-X models.

[Arxiv](https://arxiv.org/abs/2408.14037)