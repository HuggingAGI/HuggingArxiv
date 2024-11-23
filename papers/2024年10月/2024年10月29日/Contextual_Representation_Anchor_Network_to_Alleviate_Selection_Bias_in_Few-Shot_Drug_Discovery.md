# 情境表示锚定网络用于缓解少样本药物发现中的选择偏差

发布时间：2024年10月29日

`其他` `药物研发` `化学实验`

> Contextual Representation Anchor Network to Alleviate Selection Bias in Few-Shot Drug Discovery

# 摘要

> 在药物研发过程中，候选药物筛选的成功率低，常常致使标记数据匮乏，引发分子属性预测中的少样本学习难题。现有的少样本分子属性预测手段，忽视了样本选择偏差，该偏差源自化学实验中的非随机样本选取。这种数据代表性的偏差致使性能欠佳。为应对这一挑战，我们推出了一种名为上下文表示锚定网络（CRA）的新方法，其中锚定指的是分子表示的聚类中心，充当将丰富的上下文知识转移到分子表示中并增强其表现力的桥梁。CRA引入了双重增强机制，包含上下文增强，能动态检索相似的未标记分子并获取其特定任务的上下文知识以强化锚定，还有锚定增强，借助锚定来增强分子表示。我们在MoleculeNet和FS-Mol基准以及领域转移实验中对我们的方法进行了评估。结果显示，CRA在AUC和$Δ$AUC-PR指标上分别比前沿方法高出2.60％和3.28％，且展现出卓越的泛化能力。

> In the drug discovery process, the low success rate of drug candidate screening often leads to insufficient labeled data, causing the few-shot learning problem in molecular property prediction. Existing methods for few-shot molecular property prediction overlook the sample selection bias, which arises from non-random sample selection in chemical experiments. This bias in data representativeness leads to suboptimal performance. To overcome this challenge, we present a novel method named contextual representation anchor Network (CRA), where an anchor refers to a cluster center of the representations of molecules and serves as a bridge to transfer enriched contextual knowledge into molecular representations and enhance their expressiveness. CRA introduces a dual-augmentation mechanism that includes context augmentation, which dynamically retrieves analogous unlabeled molecules and captures their task-specific contextual knowledge to enhance the anchors, and anchor augmentation, which leverages the anchors to augment the molecular representations. We evaluate our approach on the MoleculeNet and FS-Mol benchmarks, as well as in domain transfer experiments. The results demonstrate that CRA outperforms the state-of-the-art by 2.60% and 3.28% in AUC and $Δ$AUC-PR metrics, respectively, and exhibits superior generalization capabilities.

[Arxiv](https://arxiv.org/abs/2410.20711)