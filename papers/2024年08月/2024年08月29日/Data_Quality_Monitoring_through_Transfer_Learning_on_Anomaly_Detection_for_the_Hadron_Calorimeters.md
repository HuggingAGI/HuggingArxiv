# 利用迁移学习在异常检测中监控强子量热计的数据质量

发布时间：2024年08月29日

`Agent` `物理学` `数据分析`

> Data Quality Monitoring through Transfer Learning on Anomaly Detection for the Hadron Calorimeters

# 摘要

> 随着传感器的大量增加，各领域产生了大量用于监测、诊断和预测等目的的空间-时间（ST）数据。然而，大量数据的整理过程耗时且成本高昂，使得在新环境中部署数据分析平台充满挑战。迁移学习（TL）通过利用预训练模型，有望缓解数据稀疏性和模型复杂性。尽管TL在计算机视觉和自然语言处理等领域取得了显著成功，但对于异常检测（AD）应用的复杂ST模型的研究仍显不足。本研究探讨了TL在CERN紧凑型μ子螺线管实验的强子量热计AD应用中的潜力，成功将ST AD模型从一个量热计部分迁移至另一部分，并研究了不同TL配置对半监督自编码器的影响。实验结果显示，TL不仅显著提升了模型学习准确性，还大幅减少了可训练参数，同时增强了模型对训练数据中异常污染的鲁棒性。

> The proliferation of sensors brings an immense volume of spatio-temporal (ST) data in many domains for various purposes, including monitoring, diagnostics, and prognostics applications. Data curation is a time-consuming process for a large volume of data, making it challenging and expensive to deploy data analytics platforms in new environments. Transfer learning (TL) mechanisms promise to mitigate data sparsity and model complexity by utilizing pre-trained models for a new task. Despite the triumph of TL in fields like computer vision and natural language processing, efforts on complex ST models for anomaly detection (AD) applications are limited. In this study, we present the potential of TL within the context of AD for the Hadron Calorimeter of the Compact Muon Solenoid experiment at CERN. We have transferred the ST AD models trained on data collected from one part of a calorimeter to another. We have investigated different configurations of TL on semi-supervised autoencoders of the ST AD models -- transferring convolutional, graph, and recurrent neural networks of both the encoder and decoder networks. The experiment results demonstrate that TL effectively enhances the model learning accuracy on a target subdetector. The TL achieves promising data reconstruction and AD performance while substantially reducing the trainable parameters of the AD models. It also improves robustness against anomaly contamination in the training data sets of the semi-supervised AD models.

[Arxiv](https://arxiv.org/abs/2408.16612)