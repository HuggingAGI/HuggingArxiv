# 本研究提出了一种自监督的文本-视觉框架，旨在自动化地检测大脑异常。

发布时间：2024年05月04日

`分类：LLM应用

这篇论文提出了一种自监督的文本-视觉框架，通过利用神经放射学报告中的自由文本信息，学习在脑部MRI扫描中识别具有临床意义的异常。这个框架使用了专为神经放射学设计的语言模型NeuroBERT，这是一个大型语言模型（LLM）的应用实例。因此，这篇论文应该被归类为LLM应用。` `医学图像识别`

> A self-supervised text-vision framework for automated brain abnormality detection

# 摘要

> 利用大规模专家标注数据集训练的人工神经网络，在多种医学图像识别任务中堪称行业标杆。但这种按类别标注的数据集不仅制备费时，还局限于一组预设的固定类别，尤其在神经放射学领域，这成为了临床应用的一大阻碍。为解决这些问题，我们提出了一种自监督的文本-视觉框架，该框架能够通过直接利用随附的自由文本神经放射学报告中的丰富信息，学习在脑部MRI扫描中识别具有临床意义的异常。我们的训练过程分为两步：首先，一个专为神经放射学设计的语言模型——NeuroBERT，通过特定领域的自监督学习任务，被训练用来生成神经放射学报告的固定维度向量表示（共50,523份）。然后，卷积神经网络（每种MRI序列一个）通过最小化均方误差损失，学习将单个大脑扫描映射到相应的文本向量表示。训练完成后，该文本-视觉框架能够通过与适当的查询句子（如“存在急性中风”、“存在脑积水”等）进行评分，来检测未报告的大脑MRI检查中的异常，从而支持一系列基于分类的应用，包括自动分诊。此外，该框架还有潜力作为临床决策支持工具，它不仅能向放射科医生提出发现、检测初步报告中的错误，还能根据文本描述检索并展示与当前病例相关的历史上的病理学案例。

> Artificial neural networks trained on large, expert-labelled datasets are considered state-of-the-art for a range of medical image recognition tasks. However, categorically labelled datasets are time-consuming to generate and constrain classification to a pre-defined, fixed set of classes. For neuroradiological applications in particular, this represents a barrier to clinical adoption. To address these challenges, we present a self-supervised text-vision framework that learns to detect clinically relevant abnormalities in brain MRI scans by directly leveraging the rich information contained in accompanying free-text neuroradiology reports. Our training approach consisted of two-steps. First, a dedicated neuroradiological language model - NeuroBERT - was trained to generate fixed-dimensional vector representations of neuroradiology reports (N = 50,523) via domain-specific self-supervised learning tasks. Next, convolutional neural networks (one per MRI sequence) learnt to map individual brain scans to their corresponding text vector representations by optimising a mean square error loss. Once trained, our text-vision framework can be used to detect abnormalities in unreported brain MRI examinations by scoring scans against suitable query sentences (e.g., 'there is an acute stroke', 'there is hydrocephalus' etc.), enabling a range of classification-based applications including automated triage. Potentially, our framework could also serve as a clinical decision support tool, not only by suggesting findings to radiologists and detecting errors in provisional reports, but also by retrieving and displaying examples of pathologies from historical examinations that could be relevant to the current case based on textual descriptors.

[Arxiv](https://arxiv.org/abs/2405.02782)