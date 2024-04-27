# 采用多模态热编码器对金属喷射打印技术的3D对象质量进行预测。

发布时间：2024年04月17日

`分类：Agent

这篇论文主要研究了3D打印过程中的质量预测问题，提出了一种多模态热编码器网络来整合不同来源的信息，并通过训练有素的编码器-解码器模块进行处理。这个过程涉及到了智能代理（Agent）的概念，即利用人工智能技术来模拟人类专家的决策过程，以提高打印成功率。因此，这篇论文可以归类为Agent领域。` `3D打印` `人工智能`

> 3D object quality prediction for Metal Jet Printer with Multimodal thermal encoder

# 摘要

> 3D打印技术的飞速发展要求打印出的物体不仅要质量上乘，尺寸精度也得精准符合客户需求。金属打印环节众多因素如功率稳定性、打印阶段参数、部件在打印台中的位置、固化阶段参数及金属烧结过程等，都会对成品质量产生影响。HP的MetJet打印技术所积累的海量数据，借助人工智能技术，不仅可以深入分析和学习，还能有效预测打印部件的质量指标，进而提升打印成功率。打印机内置的热传感器所捕获的实时热感测数据，记录了熔层的热特征，这些特征受到多种因素的综合影响。本文提出了一种多模态热编码器网络，用以整合视频数据、打印机控制数据以及精确的部件热签名等不同来源的信息，并通过训练有素的编码器-解码器模块进行处理。我们深入研究了数据融合的方法和阶段，最终优化出的端到端模型架构显著提高了部件质量预测的准确性。

> With the advancements in 3D printing technologies, it is extremely important that the quality of 3D printed objects, and dimensional accuracies should meet the customer's specifications. Various factors during metal printing affect the printed parts' quality, including the power quality, the printing stage parameters, the print part's location inside the print bed, the curing stage parameters, and the metal sintering process. With the large data gathered from HP's MetJet printing process, AI techniques can be used to analyze, learn, and effectively infer the printed part quality metrics, as well as assist in improving the print yield. In-situ thermal sensing data captured by printer-installed thermal sensors contains the part thermal signature of fusing layers. Such part thermal signature contains a convoluted impact from various factors. In this paper, we use a multimodal thermal encoder network to fuse data of a different nature including the video data vectorized printer control data, and exact part thermal signatures with a trained encoder-decoder module. We explored the data fusing techniques and stages for data fusing, the optimized end-to-end model architecture indicates an improved part quality prediction accuracy.

[Arxiv](https://arxiv.org/abs/2404.11776)