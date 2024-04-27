# 免训练的无监督提示技术，为视觉-语言模型注入新动力。

发布时间：2024年04月25日

`LLM应用` `计算机视觉` `机器学习`

> Training-Free Unsupervised Prompt for Vision-Language Models

# 摘要

> 提示学习已经发展成为调整大型预训练视觉-语言模型以适应下游任务的最有效方法。最近，像UPL和POUF这样的无监督提示调整技术，通过伪标签提供监督信息，直接对未标记数据进行微调。但是，伪标签的不准确性往往会误导微调过程，影响模型的表示能力。为此，我们提出了一种无需训练的无监督提示方法（TFUP），它在无需训练和标注的情况下，最大限度地保持并增强了模型的固有表示能力，通过残差连接与基于相似性的预测概率相结合。具体而言，我们融合了实例置信度和原型分数来挑选具有代表性的样本，并利用这些样本定制了一个可靠的特征缓存模型（FCM），以便进行无需训练的推理。此外，我们构建了一个多级相似性度量（MSM），它同时考虑了特征层面和语义层面的相似性，以计算测试图像与缓存样本之间的距离，并将此距离作为相应缓存标签权重，用以生成基于相似性的预测概率。这种方法使得TFUP在多个分类数据集上取得了惊人的成绩，甚至超过了基于训练的方法。基于TFUP，我们还提出了一种基于训练的方法（TFUP-T），以进一步提升模型的适应性能。TFUP-T不仅采用了标准的交叉熵损失，还引入了边际分布熵损失，从宏观角度对模型进行约束。在多个基准测试中，TFUP-T与无监督和少样本适应方法相比，展现出了新的最高水平的分类性能。特别是在最具挑战性的Domain-Net数据集上，TFUP-T将POUF的分类准确率提升了3.3%。

> Prompt learning has become the most effective paradigm for adapting large pre-trained vision-language models (VLMs) to downstream tasks. Recently, unsupervised prompt tuning methods, such as UPL and POUF, directly leverage pseudo-labels as supervisory information to fine-tune additional adaptation modules on unlabeled data. However, inaccurate pseudo labels easily misguide the tuning process and result in poor representation capabilities. In light of this, we propose Training-Free Unsupervised Prompts (TFUP), which maximally preserves the inherent representation capabilities and enhances them with a residual connection to similarity-based prediction probabilities in a training-free and labeling-free manner. Specifically, we integrate both instance confidence and prototype scores to select representative samples, which are used to customize a reliable Feature Cache Model (FCM) for training-free inference. Then, we design a Multi-level Similarity Measure (MSM) that considers both feature-level and semantic-level similarities to calculate the distance between each test image and the cached sample as the weight of the corresponding cached label to generate similarity-based prediction probabilities. In this way, TFUP achieves surprising performance, even surpassing the training-base method on multiple classification datasets. Based on our TFUP, we propose a training-based approach (TFUP-T) to further boost the adaptation performance. In addition to the standard cross-entropy loss, TFUP-T adopts an additional marginal distribution entropy loss to constrain the model from a global perspective. Our TFUP-T achieves new state-of-the-art classification performance compared to unsupervised and few-shot adaptation approaches on multiple benchmarks. In particular, TFUP-T improves the classification accuracy of POUF by 3.3% on the most challenging Domain-Net dataset.

![免训练的无监督提示技术，为视觉-语言模型注入新动力。](../../../paper_images/2404.16339/x1.png)

![免训练的无监督提示技术，为视觉-语言模型注入新动力。](../../../paper_images/2404.16339/x2.png)

![免训练的无监督提示技术，为视觉-语言模型注入新动力。](../../../paper_images/2404.16339/x3.png)

![免训练的无监督提示技术，为视觉-语言模型注入新动力。](../../../paper_images/2404.16339/x4.png)

![免训练的无监督提示技术，为视觉-语言模型注入新动力。](../../../paper_images/2404.16339/x5.png)

[Arxiv](https://arxiv.org/abs/2404.16339)