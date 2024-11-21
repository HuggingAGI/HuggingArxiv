# RAGraph：一种通用的检索增强型图学习框架

发布时间：2024年10月31日

`RAG` `图形学习` `数据处理`

> RAGraph: A General Retrieval-Augmented Graph Learning Framework

# 摘要

> 图神经网络（GNNs）在解读各领域的关系数据时已不可或缺，然而，它们在推广到与训练实例差异显著的未见图形数据时常常遭遇困难。本文中，我们推出了一个名为通用检索增强图学习（RAGraph）的新框架，将外部图形数据引入通用图形基础模型，以增强在未见场景中的模型泛化能力。我们的框架顶端是所构建的玩具图形向量库，它能捕捉关键属性，比如特征和特定任务的标签信息。在推理时，RAGraph 能依据下游任务中的关键相似点，熟练检索相似的玩具图形，并通过消息传递提示机制整合检索到的数据，以丰富学习情境。我们大量的实验评估显示，在动态和静态数据集上，RAGraph 在诸如节点分类、链接预测和图形分类等多个任务中，都显著优于前沿的图形学习方法。而且，大量测试证实，RAGraph 无需针对特定任务进行微调就能始终保持高性能，凸显了其适应性、稳健性和广泛的适用性。

> Graph Neural Networks (GNNs) have become essential in interpreting relational data across various domains, yet, they often struggle to generalize to unseen graph data that differs markedly from training instances. In this paper, we introduce a novel framework called General Retrieval-Augmented Graph Learning (RAGraph), which brings external graph data into the general graph foundation model to improve model generalization on unseen scenarios. On the top of our framework is a toy graph vector library that we established, which captures key attributes, such as features and task-specific label information. During inference, the RAGraph adeptly retrieves similar toy graphs based on key similarities in downstream tasks, integrating the retrieved data to enrich the learning context via the message-passing prompting mechanism. Our extensive experimental evaluations demonstrate that RAGraph significantly outperforms state-of-the-art graph learning methods in multiple tasks such as node classification, link prediction, and graph classification across both dynamic and static datasets. Furthermore, extensive testing confirms that RAGraph consistently maintains high performance without the need for task-specific fine-tuning, highlighting its adaptability, robustness, and broad applicability.

[Arxiv](https://arxiv.org/abs/2410.23855)