# 关于多模态和单模态对比学习之间的比较

发布时间：2024年11月05日

`LLM理论` `机器学习` `特征学习`

> On the Comparison between Multi-modal and Single-modal Contrastive Learning

# 摘要

> 多模态对比学习与语言监督在现代机器学习中呈现出范式转变。通过在网络规模的数据集上进行预训练，多模态对比学习可以学习到展现出令人印象深刻的鲁棒性和可转移性的高质量表示。尽管其在经验上取得了成功，但理论理解仍处于起步阶段，特别是与单模态对比学习的比较方面。在这项工作中，我们引入了一个特征学习理论框架，为理解多模态和单模态对比学习之间的差异提供了理论基础。基于由信号和噪声组成的数据生成模型，我们对使用 InfoMax 目标函数训练的 ReLU 网络进行分析。通过基于轨迹的优化分析和对下游任务的泛化特征描述，我们确定了关键因素，即信号噪声比（SNR），它影响多模态和单模态对比学习在下游任务中的泛化能力。通过两种模态之间的合作，多模态学习可以实现更好的特征学习，与单模态学习相比，在下游任务中导致性能的提升。我们的分析提供了一个统一的框架，可以表征单模态和多模态对比学习的优化和泛化。在合成和真实世界数据集上的经验实验进一步巩固了我们的理论发现。

> Multi-modal contrastive learning with language supervision has presented a paradigm shift in modern machine learning. By pre-training on a web-scale dataset, multi-modal contrastive learning can learn high-quality representations that exhibit impressive robustness and transferability. Despite its empirical success, the theoretical understanding is still in its infancy, especially regarding its comparison with single-modal contrastive learning. In this work, we introduce a feature learning theory framework that provides a theoretical foundation for understanding the differences between multi-modal and single-modal contrastive learning. Based on a data generation model consisting of signal and noise, our analysis is performed on a ReLU network trained with the InfoMax objective function. Through a trajectory-based optimization analysis and generalization characterization on downstream tasks, we identify the critical factor, which is the signal-to-noise ratio (SNR), that impacts the generalizability in downstream tasks of both multi-modal and single-modal contrastive learning. Through the cooperation between the two modalities, multi-modal learning can achieve better feature learning, leading to improvements in performance in downstream tasks compared to single-modal learning. Our analysis provides a unified framework that can characterize the optimization and generalization of both single-modal and multi-modal contrastive learning. Empirical experiments on both synthetic and real-world datasets further consolidate our theoretical findings.

[Arxiv](https://arxiv.org/abs/2411.02837)