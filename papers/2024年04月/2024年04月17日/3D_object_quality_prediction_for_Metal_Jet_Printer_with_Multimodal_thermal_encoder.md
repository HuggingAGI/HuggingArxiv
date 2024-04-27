# 本文介绍了一种利用多模态热编码器对金属喷射打印技术中的3D对象质量进行预测的方法。

发布时间：2024年04月17日

`分类：Agent

这篇论文主要讨论了3D打印技术中，如何利用AI技术，特别是多模态热编码器网络，来分析和预测打印部件的质量指标。这个任务涉及到实时数据的捕获、分析和预测，是一个典型的Agent任务，因为Agent需要与环境交互，实时地做出决策。在这个例子中，Agent就是AI模型，它通过分析热传感器捕获的数据，预测打印部件的质量，从而帮助提高打印成功率。` `3D打印` `人工智能`

> 3D object quality prediction for Metal Jet Printer with Multimodal thermal encoder

# 摘要

> 3D打印技术突飞猛进，确保打印物品的质量和尺寸精度符合客户需求至关重要。金属打印环节诸多因素如功率稳定性、打印阶段设置、部件在打印台中的位置、固化阶段参数及金属烧结流程均会影响成品质量。HP的MetJet打印技术积累的海量数据，借助AI技术，不仅能够分析和学习，还能有效预测打印部件的质量指标，进而提升打印成功率。打印机内置的热传感器捕获的实时热感测数据，记录了熔层的热特征，这些特征受到多重因素的复杂影响。本文采用多模态热编码器网络，整合了视频数据、打印机控制数据向量以及精确的部件热特征，并利用训练有素的编码器-解码器模块进行分析。通过探索数据融合的技术和阶段，我们优化了端到端模型架构，显著提高了部件质量预测的准确性。

> With the advancements in 3D printing technologies, it is extremely important that the quality of 3D printed objects, and dimensional accuracies should meet the customer's specifications. Various factors during metal printing affect the printed parts' quality, including the power quality, the printing stage parameters, the print part's location inside the print bed, the curing stage parameters, and the metal sintering process. With the large data gathered from HP's MetJet printing process, AI techniques can be used to analyze, learn, and effectively infer the printed part quality metrics, as well as assist in improving the print yield. In-situ thermal sensing data captured by printer-installed thermal sensors contains the part thermal signature of fusing layers. Such part thermal signature contains a convoluted impact from various factors. In this paper, we use a multimodal thermal encoder network to fuse data of a different nature including the video data vectorized printer control data, and exact part thermal signatures with a trained encoder-decoder module. We explored the data fusing techniques and stages for data fusing, the optimized end-to-end model architecture indicates an improved part quality prediction accuracy.

[Arxiv](https://arxiv.org/abs/2404.11776)