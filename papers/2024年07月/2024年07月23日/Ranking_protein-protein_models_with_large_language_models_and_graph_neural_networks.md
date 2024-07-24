# 结合大型语言模型与图神经网络，优化蛋白质-蛋白质模型的排序

发布时间：2024年07月23日

`LLM应用` `生物医药` `药物设计`

> Ranking protein-protein models with large language models and graph neural networks

# 摘要

> 蛋白质-蛋白质相互作用 (PPIs) 涉及多种疾病，如癌症、感染和神经退行性疾病。获取这些相互作用的三维结构信息对于干扰它们或指导药物设计至关重要。模拟这些复合物的方法多样，但通常会产生大量模型。其中，从众多模型中识别出高质量的（接近原生构象的）模型是一大挑战。为此，我们开发了 DeepRank-GNN-esm，一种基于图的深度学习算法，利用蛋白质语言模型的力量对 PPI 结构进行排序。本文通过实例详细介绍了该软件的使用方法，并可在 https://github.com/haddocking/DeepRank-GNN-esm 免费获取。

> Protein-protein interactions (PPIs) are associated with various diseases, including cancer, infections, and neurodegenerative disorders. Obtaining three-dimensional structural information on these PPIs serves as a foundation to interfere with those or to guide drug design. Various strategies can be followed to model those complexes, all typically resulting in a large number of models. A challenging step in this process is the identification of good models (near-native PPI conformations) from the large pool of generated models. To address this challenge, we previously developed DeepRank-GNN-esm, a graph-based deep learning algorithm for ranking modelled PPI structures harnessing the power of protein language models. Here, we detail the use of our software with examples. DeepRank-GNN-esm is freely available at https://github.com/haddocking/DeepRank-GNN-esm

[Arxiv](https://arxiv.org/abs/2407.16375)