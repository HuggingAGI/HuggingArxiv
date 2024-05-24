# CLIPScope：借助贝叶斯评分提升零-shot 异常检测能力

发布时间：2024年05月23日

`Agent

这篇论文主要介绍了一种名为CLIPScope的创新零-shot OOD检测技术，该技术通过类别似然性对置信度分数进行归一化，以提高检测分布外（OOD）样本的准确性。此外，CLIPScope还从庞大的词汇数据库中挖掘OOD类别，通过选择与ID类别在CLIP嵌入距离上最远和最近的类别标签，以确保OOD样本的最大覆盖。这种技术可以被视为一种智能Agent，因为它能够自主地识别和处理OOD样本，而不依赖于分布内（ID）图像。因此，这篇论文应被分类为Agent。` `机器学习安全` `图像识别`

> CLIPScope: Enhancing Zero-Shot OOD Detection with Bayesian Scoring

# 摘要

> 确保机器学习模型在现实世界中的安全部署，检测分布外（OOD）样本至关重要。得益于视觉语言基础模型的最新进展，我们现在能够不依赖分布内（ID）图像来识别OOD样本。尽管如此，这些零-shot方法往往因未充分考虑ID类别的似然性而在检测准确性上有所欠缺。为此，我们推出了CLIPScope，一种创新的零-shot OOD检测技术，它通过类别似然性对置信度分数进行归一化，类似于贝叶斯后验更新，从而提升了检测的准确性。CLIPScope还独创性地从庞大的词汇数据库中挖掘OOD类别，通过选择与ID类别在CLIP嵌入距离上最远和最近的类别标签，确保了OOD样本的最大覆盖。经过详尽的消融研究和实证评估，CLIPScope在多个OOD检测基准上展现了卓越的性能。

> Detection of out-of-distribution (OOD) samples is crucial for safe real-world deployment of machine learning models. Recent advances in vision language foundation models have made them capable of detecting OOD samples without requiring in-distribution (ID) images. However, these zero-shot methods often underperform as they do not adequately consider ID class likelihoods in their detection confidence scoring. Hence, we introduce CLIPScope, a zero-shot OOD detection approach that normalizes the confidence score of a sample by class likelihoods, akin to a Bayesian posterior update. Furthermore, CLIPScope incorporates a novel strategy to mine OOD classes from a large lexical database. It selects class labels that are farthest and nearest to ID classes in terms of CLIP embedding distance to maximize coverage of OOD samples. We conduct extensive ablation studies and empirical evaluations, demonstrating state of the art performance of CLIPScope across various OOD detection benchmarks.

[Arxiv](https://arxiv.org/abs/2405.14737)