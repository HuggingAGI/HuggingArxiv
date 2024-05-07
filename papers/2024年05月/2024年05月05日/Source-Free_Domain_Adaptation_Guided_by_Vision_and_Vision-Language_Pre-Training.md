# 视觉与视觉-语言预训练引领的无源域自适应指南

发布时间：2024年05月05日

`分类：RAG` `计算机视觉` `机器学习`

> Source-Free Domain Adaptation Guided by Vision and Vision-Language Pre-Training

# 摘要

> 无源域自适应技术（SFDA）致力于将训练有素的源模型适配至相关但未标记的目标域。源模型虽是生成目标伪标签的关键，但这些伪标签可能带有源域偏见。传统SFDA流程中，通常会使用大型数据集（如ImageNet）预训练的特征提取器来初始化源模型，然后将其弃用。这些预训练的特征提取器虽具备多样化特征以助于泛化，却可能在源域训练过程中过度适应源数据分布，导致丢失对目标域重要的知识。我们提出了一个整合框架，将这些预训练网络融入目标域的适配过程，以保留其价值。该框架设计灵活，能够将现代预训练网络整合进适配流程，从而利用其强大的表示学习功能。我们引入了Co-learn算法，通过源模型和预训练特征提取器共同提升目标伪标签的质量。借助于视觉-语言模型CLIP在零样本图像识别领域的突破，我们进一步开发了Co-learn++算法，以整合CLIP的零样本分类决策。我们在三个基准数据集上进行了评估，包括更具挑战性的开放集、部分集和开放-部分SFDA场景。实验结果显示，我们的策略显著提升了适配效果，并能与现有的SFDA方法无缝结合。

> Source-free domain adaptation (SFDA) aims to adapt a source model trained on a fully-labeled source domain to a related but unlabeled target domain. While the source model is a key avenue for acquiring target pseudolabels, the generated pseudolabels may exhibit source bias. In the conventional SFDA pipeline, a large data (e.g. ImageNet) pre-trained feature extractor is used to initialize the source model at the start of source training, and subsequently discarded. Despite having diverse features important for generalization, the pre-trained feature extractor can overfit to the source data distribution during source training and forget relevant target domain knowledge. Rather than discarding this valuable knowledge, we introduce an integrated framework to incorporate pre-trained networks into the target adaptation process. The proposed framework is flexible and allows us to plug modern pre-trained networks into the adaptation process to leverage their stronger representation learning capabilities. For adaptation, we propose the Co-learn algorithm to improve target pseudolabel quality collaboratively through the source model and a pre-trained feature extractor. Building on the recent success of the vision-language model CLIP in zero-shot image recognition, we present an extension Co-learn++ to further incorporate CLIP's zero-shot classification decisions. We evaluate on 3 benchmark datasets and include more challenging scenarios such as open-set, partial-set and open-partial SFDA. Experimental results demonstrate that our proposed strategy improves adaptation performance and can be successfully integrated with existing SFDA methods.

[Arxiv](https://arxiv.org/abs/2405.02954)