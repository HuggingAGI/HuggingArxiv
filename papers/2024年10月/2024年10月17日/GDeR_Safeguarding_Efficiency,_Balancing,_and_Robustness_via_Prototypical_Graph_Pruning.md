# GDeR：通过原型图剪枝技术，实现效率、平衡性和鲁棒性的全面保障。

发布时间：2024年10月17日

`其他` `机器学习` `图神经网络`

> GDeR: Safeguarding Efficiency, Balancing, and Robustness via Prototypical Graph Pruning

# 摘要

> 训练高质量深度模型需要海量数据，导致计算和内存需求激增。近期，数据剪枝、蒸馏和核心集选择等方法应运而生，通过保留、合成或精选一小部分信息丰富的数据子集，简化数据量。其中，数据剪枝成本最低，加速效果最显著，但最易受数据不平衡或偏斜影响，性能下降明显，引发对其在设备部署中的准确性和可靠性的担忧。因此，亟需一种新的数据剪枝范式，既高效又平衡且鲁棒。不同于计算机视觉和自然语言处理领域已有成熟解决方案，图神经网络（GNNs）仍面临大规模、不平衡和嘈杂数据集的挑战，缺乏统一的数据集剪枝方案。为此，我们提出了一种新型动态软剪枝方法GDeR，通过可训练原型在训练过程中动态更新训练“篮子”。GDeR首先构建图嵌入超球体，然后从中采样代表性、平衡和无偏的子集，实现图训练调试。实验表明，GDeR在减少30%~50%训练样本的情况下，性能与完整数据集相当，训练速度提升高达2.81倍，且在不平衡和嘈杂训练场景中，分别比最先进方法高出0.3%~4.3%和3.6%~7.8%。

> Training high-quality deep models necessitates vast amounts of data, resulting in overwhelming computational and memory demands. Recently, data pruning, distillation, and coreset selection have been developed to streamline data volume by retaining, synthesizing, or selecting a small yet informative subset from the full set. Among these methods, data pruning incurs the least additional training cost and offers the most practical acceleration benefits. However, it is the most vulnerable, often suffering significant performance degradation with imbalanced or biased data schema, thus raising concerns about its accuracy and reliability in on-device deployment. Therefore, there is a looming need for a new data pruning paradigm that maintains the efficiency of previous practices while ensuring balance and robustness. Unlike the fields of computer vision and natural language processing, where mature solutions have been developed to address these issues, graph neural networks (GNNs) continue to struggle with increasingly large-scale, imbalanced, and noisy datasets, lacking a unified dataset pruning solution. To achieve this, we introduce a novel dynamic soft-pruning method, GDeR, designed to update the training ``basket'' during the process using trainable prototypes. GDeR first constructs a well-modeled graph embedding hypersphere and then samples \textit{representative, balanced, and unbiased subsets} from this embedding space, which achieves the goal we called Graph Training Debugging. Extensive experiments on five datasets across three GNN backbones, demonstrate that GDeR (I) achieves or surpasses the performance of the full dataset with 30%~50% fewer training samples, (II) attains up to a 2.81x lossless training speedup, and (III) outperforms state-of-the-art pruning methods in imbalanced training and noisy training scenarios by 0.3%~4.3% and 3.6%~7.8%, respectively.

[Arxiv](https://arxiv.org/abs/2410.13761)