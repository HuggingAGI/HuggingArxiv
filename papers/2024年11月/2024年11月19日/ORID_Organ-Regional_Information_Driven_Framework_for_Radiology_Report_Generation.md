# ORID：用于放射学报告生成的器官 - 区域信息驱动框架

发布时间：2024年11月19日

`LLM应用` `放射学`

> ORID: Organ-Regional Information Driven Framework for Radiology Report Generation

# 摘要

> 放射学报告生成（RRG）旨在依据放射图像自动生成连贯的疾病文本分析，以减轻放射科医生的工作负担。当下基于人工智能的RRG方法重点在于对编码器 - 解码器模型架构的改进。为推动这些方法的发展，本文引入了器官 - 区域信息驱动（ORID）框架，能有效整合多模态信息并降低来自无关器官的噪声影响。具体而言，基于LLaVA-Med，我们先是构建了一个与RRG相关的指令数据集，以增强器官 - 区域诊断描述能力，从而得到LLaVA-Med-RRG。接着，我们提出了基于器官的跨模态融合模块，能有效融合来自器官 - 区域诊断描述和放射图像的信息。为进一步降低来自无关器官的噪声对放射学报告生成的影响，我们引入了器官重要性系数分析模块，借助图神经网络（GNN）来审视每个器官区域跨模态信息的相互关联。大量实验以及与各种评估指标下的前沿方法的对比，都证明了我们所提方法的卓越性能。

> The objective of Radiology Report Generation (RRG) is to automatically generate coherent textual analyses of diseases based on radiological images, thereby alleviating the workload of radiologists. Current AI-based methods for RRG primarily focus on modifications to the encoder-decoder model architecture. To advance these approaches, this paper introduces an Organ-Regional Information Driven (ORID) framework which can effectively integrate multi-modal information and reduce the influence of noise from unrelated organs. Specifically, based on the LLaVA-Med, we first construct an RRG-related instruction dataset to improve organ-regional diagnosis description ability and get the LLaVA-Med-RRG. After that, we propose an organ-based cross-modal fusion module to effectively combine the information from the organ-regional diagnosis description and radiology image. To further reduce the influence of noise from unrelated organs on the radiology report generation, we introduce an organ importance coefficient analysis module, which leverages Graph Neural Network (GNN) to examine the interconnections of the cross-modal information of each organ region. Extensive experiments an1d comparisons with state-of-the-art methods across various evaluation metrics demonstrate the superior performance of our proposed method.

[Arxiv](https://arxiv.org/abs/2411.13025)