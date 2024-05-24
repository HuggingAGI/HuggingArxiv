# G3：利用大型多模态模型，打造全球地理定位的高效自适应框架

发布时间：2024年05月23日

`RAG

这篇论文介绍了一个基于检索增强生成（RAG）框架的全球地理定位系统，称为G3框架。该框架通过三个步骤——地理对齐、地理多样化和地理验证——来优化全球地理定位的检索与生成过程。这种方法特别关注于解决全球范围内图像数据的地理分布异质性和视觉语义的细微差异问题。因此，这篇论文属于RAG分类，因为它主要讨论了RAG技术在地理定位任务中的应用和改进。` `地理信息系统` `图像识别`

> G3: An Effective and Adaptive Framework for Worldwide Geolocalization Using Large Multi-Modality Models

# 摘要

> 全球地理定位旨在精确定位地球上任意地点拍摄照片的坐标位置，这一任务因难以捕捉细微的位置感知视觉语义及图像数据地理分布的异质性而充满挑战。现有研究在全球范围内扩展时面临局限，容易混淆视觉内容相似但相距遥远的图像，或难以适应全球各地相关数据量不同的位置。为此，我们推出了G3框架，该框架基于检索增强生成（RAG），通过地理对齐、地理多样化、地理验证三个步骤，优化全球地理定位的检索与生成过程。在地理对齐阶段，我们联合学习图像、GPS与文本描述的多模态表示，以捕捉位置感知语义并检索附近图像。地理多样化阶段采用提示集成方法，确保对不同图像查询的检索性能保持鲁棒。最后，在地理验证阶段，结合检索与生成的GPS候选进行位置预测。实验结果显示，G3在IM2GPS3k和YFCC4k数据集上均优于其他顶尖方法。

> Worldwide geolocalization aims to locate the precise location at the coordinate level of photos taken anywhere on the Earth. It is very challenging due to 1) the difficulty of capturing subtle location-aware visual semantics, and 2) the heterogeneous geographical distribution of image data. As a result, existing studies have clear limitations when scaled to a worldwide context. They may easily confuse distant images with similar visual contents, or cannot adapt to various locations worldwide with different amounts of relevant data. To resolve these limitations, we propose G3, a novel framework based on Retrieval-Augmented Generation (RAG). In particular, G3 consists of three steps, i.e., Geo-alignment, Geo-diversification, and Geo-verification to optimize both retrieval and generation phases of worldwide geolocalization. During Geo-alignment, our solution jointly learns expressive multi-modal representations for images, GPS and textual descriptions, which allows us to capture location-aware semantics for retrieving nearby images for a given query. During Geo-diversification, we leverage a prompt ensembling method that is robust to inconsistent retrieval performance for different image queries. Finally, we combine both retrieved and generated GPS candidates in Geo-verification for location prediction. Experiments on two well-established datasets IM2GPS3k and YFCC4k verify the superiority of G3 compared to other state-of-the-art methods.

[Arxiv](https://arxiv.org/abs/2405.14702)