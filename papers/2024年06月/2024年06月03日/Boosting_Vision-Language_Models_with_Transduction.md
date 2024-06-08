# 提升视觉-语言模型：转换技术的应用

发布时间：2024年06月03日

`RAG

理由：这篇论文介绍了一种名为TransCLIP的创新传导方法，专门为视觉语言模型（VLMs）设计，旨在提升预测精度。它通过即插即用模块的形式，改善了归纳零样本和小样本模型的性能。这种方法涉及特定的目标函数和优化程序，这些都是为了增强视觉语言模型的性能。因此，这篇论文更符合RAG分类，即研究如何通过特定的方法或技术来增强或改进现有的模型或系统。` `视觉语言模型` `机器学习`

> Boosting Vision-Language Models with Transduction

# 摘要

> Transduction是一种强大的方法，它利用未标记数据的结构来提升预测精度。我们提出的TransCLIP是一种创新且高效的传导方法，专为视觉语言模型（VLMs）设计。作为即插即用模块，TransCLIP能持续提升流行归纳零样本和小样本模型的性能。我们的新目标函数是一种受KL散度约束的正则化最大似然估计，它整合了文本编码器知识，引导传导学习过程。我们还开发了一个迭代块最大化-最小化（BMM）程序来优化目标，确保收敛并实现样本分配的解耦更新，适用于大规模数据集的高效传导。我们的全面评估、比较和消融研究显示：(i) 传导能大幅提升归纳预训练的零样本和小样本VLMs的泛化能力；(ii) TransCLIP由于其基于KL的语言约束，显著超越了仅依赖视觉特征的标准传导小样本学习方法。

> Transduction is a powerful paradigm that leverages the structure of unlabeled data to boost predictive accuracy. We present TransCLIP, a novel and computationally efficient transductive approach designed for Vision-Language Models (VLMs). TransCLIP is applicable as a plug-and-play module on top of popular inductive zero- and few-shot models, consistently improving their performances. Our new objective function can be viewed as a regularized maximum-likelihood estimation, constrained by a KL divergence penalty that integrates the text-encoder knowledge and guides the transductive learning process. We further derive an iterative Block Majorize-Minimize (BMM) procedure for optimizing our objective, with guaranteed convergence and decoupled sample-assignment updates, yielding computationally efficient transduction for large-scale datasets. We report comprehensive evaluations, comparisons, and ablation studies that demonstrate: (i) Transduction can greatly enhance the generalization capabilities of inductive pretrained zero- and few-shot VLMs; (ii) TransCLIP substantially outperforms standard transductive few-shot learning methods relying solely on vision features, notably due to the KL-based language constraint.

![提升视觉-语言模型：转换技术的应用](../../../paper_images/2406.01837/x1.png)

[Arxiv](https://arxiv.org/abs/2406.01837)