# 探究高维空间中最近邻搜索的实际意义

发布时间：2024年10月08日

`LLM理论` `计算机视觉` `机器学习`

> Exploring the Meaningfulness of Nearest Neighbor Search in High-Dimensional Space

# 摘要

> 在计算机视觉、机器学习和大型语言模型等领域，密集的高维向量正变得越来越重要，成为多模态数据的标准表示。这些向量的维度如今轻松突破数千。尽管最近邻搜索 (NNS) 在这些高维向量上的应用广泛，但其有效性仍因“维度灾难”而存疑。本文通过不同距离函数（如 $L_1$、$L_2$ 和角度距离）对各类嵌入数据集进行广泛研究，旨在揭示影响 NNS 意义性的因素。实验发现，高维文本嵌入在面对更高维度时，比随机向量更具韧性，表明其受“维度灾难”影响较小，从而在实际应用中产生更有意义的 NNS 结果。此外，距离函数的选择对 NNS 相关性影响甚微。本研究不仅验证了基于嵌入的数据表示方法的有效性，还为密集向量相关应用的优化提供了新思路。

> Dense high dimensional vectors are becoming increasingly vital in fields such as computer vision, machine learning, and large language models (LLMs), serving as standard representations for multimodal data. Now the dimensionality of these vector can exceed several thousands easily. Despite the nearest neighbor search (NNS) over these dense high dimensional vectors have been widely used for retrieval augmented generation (RAG) and many other applications, the effectiveness of NNS in such a high-dimensional space remains uncertain, given the possible challenge caused by the "curse of dimensionality." To address above question, in this paper, we conduct extensive NNS studies with different distance functions, such as $L_1$ distance, $L_2$ distance and angular-distance, across diverse embedding datasets, of varied types, dimensionality and modality. Our aim is to investigate factors influencing the meaningfulness of NNS. Our experiments reveal that high-dimensional text embeddings exhibit increased resilience as dimensionality rises to higher levels when compared to random vectors. This resilience suggests that text embeddings are less affected to the "curse of dimensionality," resulting in more meaningful NNS outcomes for practical use. Additionally, the choice of distance function has minimal impact on the relevance of NNS. Our study shows the effectiveness of the embedding-based data representation method and can offer opportunity for further optimization of dense vector-related applications.

[Arxiv](https://arxiv.org/abs/2410.05752)