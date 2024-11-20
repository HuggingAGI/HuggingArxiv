# MMBind：释放物联网中多模态学习的分布式和异构数据的潜力

发布时间：2024年11月18日

`其他` `物联网` `多模态学习`

> MMBind: Unleashing the Potential of Distributed and Heterogeneous Data for Multimodal Learning in IoT

# 摘要

> 多模态传感系统在各类现实应用中愈发常见。现有的多数多模态学习方法高度依赖用大量完整的多模态数据来训练。但在现实的物联网传感应用中，这种设定并不实际，因为数据通常由具有异构数据模式的分布式节点采集，而且很少有标注。本文中，我们提出了 MMBind，这是针对分布式和异构物联网数据的多模态学习的新框架。MMBind 的核心思路是通过一个极具描述性的共享模态，把来自不同来源和不完整模态的数据绑定起来，构建用于模型训练的伪配对多模态数据集。我们证实，观察相似事件的不同模态数据，即便在不同时间和地点获取，也能有效用于多模态训练。另外，我们提出了一种能训练具有异构模态组合模型的自适应多模态学习架构，还有一种加权对比学习方法来处理不同数据间的域转移。对十个真实世界多模态数据集的评估显示，MMBind 在数据不完整和域转移各异的情况下，表现优于前沿基线，有望促进物联网应用中的多模态基础模型训练。

> Multimodal sensing systems are increasingly prevalent in various real-world applications. Most existing multimodal learning approaches heavily rely on training with a large amount of complete multimodal data. However, such a setting is impractical in real-world IoT sensing applications where data is typically collected by distributed nodes with heterogeneous data modalities, and is also rarely labeled. In this paper, we propose MMBind, a new framework for multimodal learning on distributed and heterogeneous IoT data. The key idea of MMBind is to construct a pseudo-paired multimodal dataset for model training by binding data from disparate sources and incomplete modalities through a sufficiently descriptive shared modality. We demonstrate that data of different modalities observing similar events, even captured at different times and locations, can be effectively used for multimodal training. Moreover, we propose an adaptive multimodal learning architecture capable of training models with heterogeneous modality combinations, coupled with a weighted contrastive learning approach to handle domain shifts among disparate data. Evaluations on ten real-world multimodal datasets highlight that MMBind outperforms state-of-the-art baselines under varying data incompleteness and domain shift, and holds promise for advancing multimodal foundation model training in IoT applications.

[Arxiv](https://arxiv.org/abs/2411.12126)