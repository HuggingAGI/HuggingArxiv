# SCAN：为实现数据效率而引导的对比预训练

发布时间：2024年11月13日

`LLM应用` `计算机视觉` `预训练`

> SCAN: Bootstrapping Contrastive Pre-training for Data Efficiency

# 摘要

> 尽管对比预训练应用广泛，但其数据效率问题迄今仍未得到充分探究。现有的方法往往依赖静态的核心集选择算法来预先确定用于训练的重要数据。然而，这种静态特性致使它们无法在预训练期间动态追踪数据的有用性，致使预训练模型效果欠佳。为应对此挑战，我们的论文提出了一种新颖的动态自举数据集修剪法。它包含数据修剪准备以及数据集变异操作，二者均进行迭代和动态更新。我们将此方法应用于两个流行的对比预训练框架：	extbf{CLIP} 和 	extbf{MoCo}，分别代表视觉语言和以视觉为中心的领域。具体而言，我们在两个大规模的图像-文本对数据集上分别预训练了七个 CLIP 模型，在 ImageNet 数据集上预训练了两个 MoCo 模型，总计 16 个预训练模型。在这 16 个模型中，数据修剪率为 30 - 35％，与在完整数据集上训练的对应模型相比，我们的方法在各类下游数据集上仅有轻微的性能下降（平均小于	extbf{1％}），而且还大幅超越了几个基线。另外，我们方法的副产物，即预训练后从原始数据集中得出的核心集，在下游性能方面也显著优于其他静态核心集选择方法。

> While contrastive pre-training is widely employed, its data efficiency problem has remained relatively under-explored thus far. Existing methods often rely on static coreset selection algorithms to pre-identify important data for training. However, this static nature renders them unable to dynamically track the data usefulness throughout pre-training, leading to subpar pre-trained models. To address this challenge, our paper introduces a novel dynamic bootstrapping dataset pruning method. It involves pruning data preparation followed by dataset mutation operations, both of which undergo iterative and dynamic updates. We apply this method to two prevalent contrastive pre-training frameworks: \textbf{CLIP} and \textbf{MoCo}, representing vision-language and vision-centric domains, respectively. In particular, we individually pre-train seven CLIP models on two large-scale image-text pair datasets, and two MoCo models on the ImageNet dataset, resulting in a total of 16 pre-trained models. With a data pruning rate of 30-35\% across all 16 models, our method exhibits only marginal performance degradation (less than \textbf{1\%} on average) compared to corresponding models trained on the full dataset counterparts across various downstream datasets, and also surpasses several baselines with a large performance margin. Additionally, the byproduct from our method, \ie coresets derived from the original datasets after pre-training, also demonstrates significant superiority in terms of downstream performance over other static coreset selection approaches.

[Arxiv](https://arxiv.org/abs/2411.09126)