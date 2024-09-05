# MOSMOS：借助医学报告监督实现的多器官分割技术

发布时间：2024年09月03日

`LLM应用` `计算机视觉`

> MOSMOS: Multi-organ segmentation facilitated by medical report supervision

# 摘要

> 现代医疗系统中的多模态数据，如医学图像和报告，推动了医学视觉-语言预训练（Med-VLP）在粗粒度任务中的显著成就。然而，将这些知识应用于细粒度的多器官分割仍待探索。本文提出了一种创新的预训练与微调框架MOSMOS，通过全局对比学习和多标签识别，有效解决了数据标注和器官形态多样性的挑战。我们的方法不仅提高了分割模型的泛化能力，还为医学报告监督下的自动标注任务开辟了新路径。实验证明，该框架在多种疾病和模态的数据集上均表现出色，为未来的研究奠定了坚实基础。

> Owing to a large amount of multi-modal data in modern medical systems, such as medical images and reports, Medical Vision-Language Pre-training (Med-VLP) has demonstrated incredible achievements in coarse-grained downstream tasks (i.e., medical classification, retrieval, and visual question answering). However, the problem of transferring knowledge learned from Med-VLP to fine-grained multi-organ segmentation tasks has barely been investigated. Multi-organ segmentation is challenging mainly due to the lack of large-scale fully annotated datasets and the wide variation in the shape and size of the same organ between individuals with different diseases. In this paper, we propose a novel pre-training & fine-tuning framework for Multi-Organ Segmentation by harnessing Medical repOrt Supervision (MOSMOS). Specifically, we first introduce global contrastive learning to maximally align the medical image-report pairs in the pre-training stage. To remedy the granularity discrepancy, we further leverage multi-label recognition to implicitly learn the semantic correspondence between image pixels and organ tags. More importantly, our pre-trained models can be transferred to any segmentation model by introducing the pixel-tag attention maps. Different network settings, i.e., 2D U-Net and 3D UNETR, are utilized to validate the generalization. We have extensively evaluated our approach using different diseases and modalities on BTCV, AMOS, MMWHS, and BRATS datasets. Experimental results in various settings demonstrate the effectiveness of our framework. This framework can serve as the foundation to facilitate future research on automatic annotation tasks under the supervision of medical reports.

[Arxiv](https://arxiv.org/abs/2409.02418)