# 图与多模态的邂逅：多模态属性图学习的基准测试

发布时间：2024年10月11日

`其他` `社交网络`

> When Graph meets Multimodal: Benchmarking on Multimodal Attributed Graphs Learning

# 摘要

> 多模态属性图 (MAGs) 广泛应用于现实世界，包含两种知识：一是节点（如文本和图像）的属性知识，二是节点间复杂交互的拓扑知识。MAG 表示学习的关键在于这两者的无缝融合。预训练模型和图神经网络的进步推动了 MAG 学习的发展，但缺乏标准化的基准数据集和评估程序限制了其进步。为此，我们推出了多模态属性图基准 (MAGB)，涵盖从电商到社交网络的广泛领域。我们不仅提供了全新数据集，还通过多种学习方法（如 GNN 和 PLM）进行了深入实验，探讨了多模态与拓扑结合的必要性。本文概述了 MAGB 数据集、标准化评估流程及基线实验，项目代码已公开在 https://github.com/sktsherlock/ATG。

> Multimodal attributed graphs (MAGs) are prevalent in various real-world scenarios and generally contain two kinds of knowledge: (a) Attribute knowledge is mainly supported by the attributes of different modalities contained in nodes (entities) themselves, such as texts and images. (b) Topology knowledge, on the other hand, is provided by the complex interactions posed between nodes. The cornerstone of MAG representation learning lies in the seamless integration of multimodal attributes and topology. Recent advancements in Pre-trained Language/Vision models (PLMs/PVMs) and Graph neural networks (GNNs) have facilitated effective learning on MAGs, garnering increased research interest. However, the absence of meaningful benchmark datasets and standardized evaluation procedures for MAG representation learning has impeded progress in this field. In this paper, we propose Multimodal Attribute Graph Benchmark (MAGB)}, a comprehensive and diverse collection of challenging benchmark datasets for MAGs. The MAGB datasets are notably large in scale and encompass a wide range of domains, spanning from e-commerce networks to social networks. In addition to the brand-new datasets, we conduct extensive benchmark experiments over MAGB with various learning paradigms, ranging from GNN-based and PLM-based methods, to explore the necessity and feasibility of integrating multimodal attributes and graph topology. In a nutshell, we provide an overview of the MAG datasets, standardized evaluation procedures, and present baseline experiments. The entire MAGB project is publicly accessible at https://github.com/sktsherlock/ATG.

[Arxiv](https://arxiv.org/abs/2410.09132)