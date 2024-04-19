# 采用多模态热编码器技术，对金属喷墨打印机的3D打印对象质量进行精准预测。

发布时间：2024年04月17日

`分类：Agent` `3D打印` `人工智能`

> 3D object quality prediction for Metal Jet Printer with Multimodal thermal encoder

# 摘要

> 3D打印技术突飞猛进，确保打印物品的质量和尺寸精度符合客户需求至关重要。金属打印环节中，诸如功率稳定性、打印阶段参数、部件在打印床中的位置、固化阶段参数以及金属烧结过程等多个因素，都会对打印质量产生影响。惠普MetJet打印技术的海量数据，为AI技术提供了分析、学习和推断打印部件质量指标的丰富资源，进而助力提升打印成功率。打印机内置的热传感器捕获的实时热感测数据，能够揭示熔层的热特性，这些特性受到多重因素的复杂影响。本文采用多模态热编码器网络，整合视频数据、打印机控制数据以及精确的部件热签名，并通过训练有素的编码器-解码器模块进行处理。我们深入研究了数据融合技术及其阶段，优化后的端到端模型架构显著提升了部件质量预测的准确性。

> With the advancements in 3D printing technologies, it is extremely important that the quality of 3D printed objects, and dimensional accuracies should meet the customer's specifications. Various factors during metal printing affect the printed parts' quality, including the power quality, the printing stage parameters, the print part's location inside the print bed, the curing stage parameters, and the metal sintering process. With the large data gathered from HP's MetJet printing process, AI techniques can be used to analyze, learn, and effectively infer the printed part quality metrics, as well as assist in improving the print yield. In-situ thermal sensing data captured by printer-installed thermal sensors contains the part thermal signature of fusing layers. Such part thermal signature contains a convoluted impact from various factors. In this paper, we use a multimodal thermal encoder network to fuse data of a different nature including the video data vectorized printer control data, and exact part thermal signatures with a trained encoder-decoder module. We explored the data fusing techniques and stages for data fusing, the optimized end-to-end model architecture indicates an improved part quality prediction accuracy.

[Arxiv](https://arxiv.org/abs/2404.11776)