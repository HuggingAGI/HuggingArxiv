# 多视图自适应对比学习：信息检索中的故障定位新方法

发布时间：2024年09月19日

`LLM应用` `软件工程` `故障诊断`

> Multi-View Adaptive Contrastive Learning for Information Retrieval Based Fault Localization

# 摘要

> 大多数故障定位研究依赖于信息检索技术，通过构建错误报告和源代码文件的语义向量并进行相似性匹配。然而，这些方法往往忽略了错误报告与源代码文件的交互关系、错误报告之间的相似性关系以及源代码文件的共引用关系等有用信息。为此，我们提出了一种名为多视图自适应对比学习（MACL-IRFL）的新方法，旨在通过学习这些关系来提升故障定位效果。我们首先从不同视图生成数据增强，并利用图神经网络聚合信息，然后在视图间进行对比学习，以编码共享信息并减少噪声。实验结果显示，我们的模型在多个指标上显著优于现有最佳方法，最高提升达28.93%。

> Most studies focused on information retrieval-based techniques for fault localization, which built representations for bug reports and source code files and matched their semantic vectors through similarity measurement. However, such approaches often ignore some useful information that might help improve localization performance, such as 1) the interaction relationship between bug reports and source code files; 2) the similarity relationship between bug reports; and 3) the co-citation relationship between source code files. In this paper, we propose a novel approach named Multi-View Adaptive Contrastive Learning for Information Retrieval Fault Localization (MACL-IRFL) to learn the above-mentioned relationships for software fault localization. Specifically, we first generate data augmentations from report-code interaction view, report-report similarity view and code-code co-citation view separately, and adopt graph neural network to aggregate the information of bug reports or source code files from the three views in the embedding process. Moreover, we perform contrastive learning across these views. Our design of contrastive learning task will force the bug report representations to encode information shared by report-report and report-code views,and the source code file representations shared by code-code and report-code views, thereby alleviating the noise from auxiliary information. Finally, to evaluate the performance of our approach, we conduct extensive experiments on five open-source Java projects. The results show that our model can improve over the best baseline up to 28.93%, 25.57% and 20.35% on Accuracy@1, MAP and MRR, respectively.

[Arxiv](https://arxiv.org/abs/2409.12519)