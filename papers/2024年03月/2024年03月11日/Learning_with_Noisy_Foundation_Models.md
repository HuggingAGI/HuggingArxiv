# 探究噪声底层模型下的学习机制

发布时间：2024年03月11日

`LLM理论`

> Learning with Noisy Foundation Models

> 基础模型通常先在海量数据集上预训练，之后再针对下游任务微调优化。然而，那些庞大却不易获取或处理成本极高的预训练数据集，可能存在标签噪声问题，这会对模型的泛化能力和实际应用带来潜在风险。本文率先深入剖析预训练数据集中的噪声本质，并提出有效策略减轻其对下游任务的影响。实验中，我们利用含有合成噪声的ImageNet-1K、YFCC15M和CC12M数据集进行全监督和图像文本对比预训练，揭示了一个现象：少量预训练噪声虽能在训练与测试数据分布相近的领域内提升模型表现，但在分布差异显著的领域外场景下，则会导致性能下滑。该发现不受预训练数据规模、噪声类型、模型结构、预训练目标、下游微调方法及下游应用场景的影响。经过实证探究，我们发现噪声在预训练阶段对特征空间的塑造是导致这一现象的关键原因。因此，我们创新性地提出了名为NMTune的调整方法，通过调整特征空间来抑制噪声的负面影响并增强模型的泛化能力，这种方法不仅在参数高效调优方面适用，也能应用于黑盒调优场景。此外，我们还在多种广泛应用的视觉和语言模型上进行了大量实验，其中包含了基于真实噪声数据监督及自监督预训练的APIs。本研究的分析和结果充分展示了探索“噪声模型学习”这一新锐而基础研究方向的重要价值。

> Foundation models are usually pre-trained on large-scale datasets and then adapted to downstream tasks through tuning. However, the large-scale pre-training datasets, often inaccessible or too expensive to handle, can contain label noise that may adversely affect the generalization of the model and pose unexpected risks. This paper stands out as the first work to comprehensively understand and analyze the nature of noise in pre-training datasets and then effectively mitigate its impacts on downstream tasks. Specifically, through extensive experiments of fully-supervised and image-text contrastive pre-training on synthetic noisy ImageNet-1K, YFCC15M, and CC12M datasets, we demonstrate that, while slight noise in pre-training can benefit in-domain (ID) performance, where the training and testing data share a similar distribution, it always deteriorates out-of-domain (OOD) performance, where training and testing distributions are significantly different. These observations are agnostic to scales of pre-training datasets, pre-training noise types, model architectures, pre-training objectives, downstream tuning methods, and downstream applications. We empirically ascertain that the reason behind this is that the pre-training noise shapes the feature space differently. We then propose a tuning method (NMTune) to affine the feature space to mitigate the malignant effect of noise and improve generalization, which is applicable in both parameter-efficient and black-box tuning manners. We additionally conduct extensive experiments on popular vision and language models, including APIs, which are supervised and self-supervised pre-trained on realistic noisy data for evaluation. Our analysis and results demonstrate the importance of this novel and fundamental research direction, which we term as Noisy Model Learning.

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x1.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x2.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x3.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x4.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x5.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x6.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x7.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x8.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x9.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x10.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x11.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x12.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x13.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x14.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x15.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x16.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x17.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x18.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x19.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x20.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x21.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x22.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x23.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x24.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x25.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x26.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x27.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x28.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x29.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x30.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x31.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x32.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x33.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x34.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x35.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x36.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x37.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x38.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x39.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x40.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x41.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x42.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x43.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x44.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x45.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x46.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x47.png)

![探究噪声底层模型下的学习机制](../../../paper_images/2403.06869/x48.png)

[Arxiv](https://arxiv.org/abs/2403.06869)