# 借助转换技术提升视觉-语言模型的性能

发布时间：2024年06月03日

`RAG

理由：这篇论文介绍了一种名为TransCLIP的新型传导方法，专门为视觉语言模型（VLMs）设计，旨在提升预测精度。它通过利用未标记数据的结构，并结合文本编码器的知识来引导学习过程。这种方法可以作为即插即用模块，提升现有归纳零样本和小样本模型的性能。由于其重点在于改进和增强视觉语言模型的性能，特别是通过传导学习方法，这与RAG（Retrieval-Augmented Generation）的概念相符，即通过增强模型来提高其性能和泛化能力。因此，将其分类为RAG是合适的。` `计算机视觉`

> Boosting Vision-Language Models with Transduction

# 摘要

> Transduction是一种强大的方法，通过利用未标记数据的结构来提升预测精度。我们提出的TransCLIP是一种创新的、计算高效的传导方法，专为视觉语言模型（VLMs）设计。TransCLIP作为即插即用模块，能够持续提升流行归纳零样本和小样本模型的性能。我们的新目标函数是一种受KL散度惩罚项约束的正则化最大似然估计，该惩罚项结合了文本编码器知识，引导传导学习过程。我们还开发了一个迭代块的Majorize-Minimize（BMM）优化程序，确保了收敛性和样本分配的解耦更新，为大规模数据集提供了高效的传导。通过全面的评估、比较和消融研究，我们发现：(i) 传导能显著增强归纳预训练的零样本和小样本VLMs的泛化能力；(ii) TransCLIP由于其基于KL的语言约束，显著优于仅依赖视觉特征的标准传导小样本学习方法。

> Transduction is a powerful paradigm that leverages the structure of unlabeled data to boost predictive accuracy. We present TransCLIP, a novel and computationally efficient transductive approach designed for Vision-Language Models (VLMs). TransCLIP is applicable as a plug-and-play module on top of popular inductive zero- and few-shot models, consistently improving their performances. Our new objective function can be viewed as a regularized maximum-likelihood estimation, constrained by a KL divergence penalty that integrates the text-encoder knowledge and guides the transductive learning process. We further derive an iterative Block Majorize-Minimize (BMM) procedure for optimizing our objective, with guaranteed convergence and decoupled sample-assignment updates, yielding computationally efficient transduction for large-scale datasets. We report comprehensive evaluations, comparisons, and ablation studies that demonstrate: (i) Transduction can greatly enhance the generalization capabilities of inductive pretrained zero- and few-shot VLMs; (ii) TransCLIP substantially outperforms standard transductive few-shot learning methods relying solely on vision features, notably due to the KL-based language constraint.

![借助转换技术提升视觉-语言模型的性能](../../../paper_images/2406.01837/x1.png)

[Arxiv](https://arxiv.org/abs/2406.01837)