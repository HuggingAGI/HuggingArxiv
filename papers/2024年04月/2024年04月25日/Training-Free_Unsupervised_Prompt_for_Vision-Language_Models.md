# 一种无需训练即可应用于视觉-语言模型的无监督提示技术。

发布时间：2024年04月25日

`LLM应用` `计算机视觉` `机器学习`

> Training-Free Unsupervised Prompt for Vision-Language Models

# 摘要

> 提示学习已成为适配大型预训练视觉-语言模型至下游任务的高效策略。新兴的无监督提示调整技术，例如UPL和POUF，通过伪标签提供监督信号，以微调无标签数据上的附加适应模块。但伪标签的不精确性常导致调整过程误入歧途，影响模型的表征性能。为此，我们引入了无需训练的无监督提示（TFUP），它在无需训练和标注的情况下，最大限度地保留了模型的内在表征能力，并通过残差连接强化了基于相似性预测的概率。我们融合实例置信度与原型分数，挑选出具有代表性的样本，用以定制一个可靠的特征缓存模型（FCM），实现无需训练的推理。此外，我们构建了一个多级相似性度量（MSM），综合考量特征和语义层面的相似度，以计算测试图像与缓存样本间的距离，并以此为权重生成基于相似性的预测概率。TFUP在多个分类数据集上展现了卓越的性能，甚至超越了基于训练的方法。基于TFUP，我们进一步提出了一种训练型方法（TFUP-T），在标准交叉熵损失的基础上，引入边缘分布熵损失，从宏观角度优化模型。TFUP-T在多个基准测试中刷新了无监督和少样本适应方法的分类性能记录，特别是在难度最高的Domain-Net数据集上，将POUF的分类准确率提升了3.3%。

> Prompt learning has become the most effective paradigm for adapting large pre-trained vision-language models (VLMs) to downstream tasks. Recently, unsupervised prompt tuning methods, such as UPL and POUF, directly leverage pseudo-labels as supervisory information to fine-tune additional adaptation modules on unlabeled data. However, inaccurate pseudo labels easily misguide the tuning process and result in poor representation capabilities. In light of this, we propose Training-Free Unsupervised Prompts (TFUP), which maximally preserves the inherent representation capabilities and enhances them with a residual connection to similarity-based prediction probabilities in a training-free and labeling-free manner. Specifically, we integrate both instance confidence and prototype scores to select representative samples, which are used to customize a reliable Feature Cache Model (FCM) for training-free inference. Then, we design a Multi-level Similarity Measure (MSM) that considers both feature-level and semantic-level similarities to calculate the distance between each test image and the cached sample as the weight of the corresponding cached label to generate similarity-based prediction probabilities. In this way, TFUP achieves surprising performance, even surpassing the training-base method on multiple classification datasets. Based on our TFUP, we propose a training-based approach (TFUP-T) to further boost the adaptation performance. In addition to the standard cross-entropy loss, TFUP-T adopts an additional marginal distribution entropy loss to constrain the model from a global perspective. Our TFUP-T achieves new state-of-the-art classification performance compared to unsupervised and few-shot adaptation approaches on multiple benchmarks. In particular, TFUP-T improves the classification accuracy of POUF by 3.3% on the most challenging Domain-Net dataset.

![一种无需训练即可应用于视觉-语言模型的无监督提示技术。](../../../paper_images/2404.16339/x1.png)

![一种无需训练即可应用于视觉-语言模型的无监督提示技术。](../../../paper_images/2404.16339/x2.png)

![一种无需训练即可应用于视觉-语言模型的无监督提示技术。](../../../paper_images/2404.16339/x3.png)

![一种无需训练即可应用于视觉-语言模型的无监督提示技术。](../../../paper_images/2404.16339/x4.png)

![一种无需训练即可应用于视觉-语言模型的无监督提示技术。](../../../paper_images/2404.16339/x5.png)

[Arxiv](https://arxiv.org/abs/2404.16339)