# 借助转换技术提升视觉-语言模型的性能

发布时间：2024年06月03日

`RAG

理由：这篇论文介绍了一种名为TransCLIP的创新传导方法，专门设计用于视觉语言模型，以提升预测精度。它通过即插即用模块的形式，增强现有的归纳零样本和少样本模型的性能。这种方法涉及一个特定的目标函数，该函数结合了文本编码器的知识，并通过KL散度惩罚项进行正则化。此外，论文还描述了一个迭代优化程序，用于处理大规模数据集。这些特点表明，该论文主要关注的是改进现有的视觉语言模型（如CLIP）的性能，属于模型增强或改进的范畴，因此归类为RAG（Retrieval-Augmented Generation）。RAG类别通常涉及通过引入外部知识或数据来增强模型的生成能力，这与论文中描述的通过传导方法提升模型性能的做法相符。` `视觉语言模型` `机器学习`

> Boosting Vision-Language Models with Transduction

# 摘要

> Transduction是一种强大的方法，它利用未标记数据结构来提升预测精度。我们提出的TransCLIP是一种专为视觉语言模型设计的创新且高效的传导方法。作为即插即用模块，TransCLIP能持续提升流行归纳零样本和少样本模型的性能。我们的新目标函数是一种受KL散度惩罚项约束的正则化最大似然估计，该惩罚项结合了文本编码器知识，引导传导学习过程。我们还开发了一个迭代块最大化最小化程序来优化目标，确保收敛并实现样本分配的解耦更新，从而为大规模数据集提供高效的传导。通过全面的评估、比较和消融研究，我们发现：(i) 传导能显著增强归纳预训练的零样本和少样本VLMs的泛化能力；(ii) 得益于基于KL的语言约束，TransCLIP显著超越了仅依赖视觉特征的标准传导少样本学习方法。

> Transduction is a powerful paradigm that leverages the structure of unlabeled data to boost predictive accuracy. We present TransCLIP, a novel and computationally efficient transductive approach designed for Vision-Language Models (VLMs). TransCLIP is applicable as a plug-and-play module on top of popular inductive zero- and few-shot models, consistently improving their performances. Our new objective function can be viewed as a regularized maximum-likelihood estimation, constrained by a KL divergence penalty that integrates the text-encoder knowledge and guides the transductive learning process. We further derive an iterative Block Majorize-Minimize (BMM) procedure for optimizing our objective, with guaranteed convergence and decoupled sample-assignment updates, yielding computationally efficient transduction for large-scale datasets. We report comprehensive evaluations, comparisons, and ablation studies that demonstrate: (i) Transduction can greatly enhance the generalization capabilities of inductive pretrained zero- and few-shot VLMs; (ii) TransCLIP substantially outperforms standard transductive few-shot learning methods relying solely on vision features, notably due to the KL-based language constraint.

![借助转换技术提升视觉-语言模型的性能](../../../paper_images/2406.01837/x1.png)

[Arxiv](https://arxiv.org/abs/2406.01837)