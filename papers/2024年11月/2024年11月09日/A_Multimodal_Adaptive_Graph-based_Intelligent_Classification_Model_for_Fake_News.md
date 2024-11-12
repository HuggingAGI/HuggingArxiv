# 一种用于假新闻的多模态自适应基于图的智能分类模型

发布时间：2024年11月09日

`其他`

> A Multimodal Adaptive Graph-based Intelligent Classification Model for Fake News

# 摘要

> 许多研究已经被提出，以基于机器和/或深度学习检测聚焦于多模态的假新闻。然而，使用基于几何深度学习的基于图的结构的研究是缺乏的。为了应对这一挑战，我们引入了用于假新闻检测的多模态自适应基于图的智能分类（恰当地称为 MAGIC）。具体来说，来自 Transformer 的编码器表示被用于文本向量化，而 ResNet50 被用于图像。在通过 Softmax 函数对多模态输入进行分类之前，使用自适应图注意力网络构建了一个全面的信息交互图。MAGIC 在两个假新闻数据集，即 Fakeddit（英语）和多模态假新闻检测（中文）上进行了训练和测试，该模型分别达到了 98.8％和 86.3％的准确率。消融实验也揭示了 MAGIC 在两个数据集中都产生了优越的性能。研究结果表明，基于图的深度学习自适应模型在检测多模态假新闻方面是有效的，超过了最先进的方法。

> Numerous studies have been proposed to detect fake news focusing on multi-modalities based on machine and/or deep learning. However, studies focusing on graph-based structures using geometric deep learning are lacking. To address this challenge, we introduce the Multimodal Adaptive Graph-based Intelligent Classification (aptly referred to as MAGIC) for fake news detection. Specifically, the Encoder Representations from Transformers was used for text vectorization whilst ResNet50 was used for images. A comprehensive information interaction graph was built using the adaptive Graph Attention Network before classifying the multimodal input through the Softmax function. MAGIC was trained and tested on two fake news datasets, that is, Fakeddit (English) and Multimodal Fake News Detection (Chinese), with the model achieving an accuracy of 98.8\% and 86.3\%, respectively. Ablation experiments also revealed MAGIC to yield superior performance across both the datasets. Findings show that a graph-based deep learning adaptive model is effective in detecting multimodal fake news, surpassing state-of-the-art methods.

[Arxiv](https://arxiv.org/abs/2411.06097)