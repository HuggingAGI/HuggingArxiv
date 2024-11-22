# DINO-X：用于开放世界中对象检测与理解的统一视觉模型

发布时间：2024年11月21日

`其他` `计算机视觉` `对象检测`

> DINO-X: A Unified Vision Model for Open-World Object Detection and Understanding

# 摘要

> 摘要：在本文中，我们为您介绍 DINO-X，这是由 IDEA 研究开发的统一以对象为中心的视觉模型，其拥有迄今为止最佳的开放世界对象检测性能。DINO-X 采用与 Grounding DINO 1.5 相同的基于 Transformer 的编码器 - 解码器架构，致力于实现开放世界对象理解的对象级表征。为了让长尾对象检测更轻松，DINO-X 拓展了输入选项，支持文本提示、视觉提示和自定义提示。凭借这般灵活的提示选项，我们研发出了通用对象提示，支持无提示的开放世界检测，能够在图像中检测任何对象，无需用户提供任何提示。为增强模型的核心基础能力，我们构建了一个拥有超 1 亿个高质量基础样本的大规模数据集，称作 Grounding-100M，以提升模型的开放词汇检测性能。在如此大规模的基础数据集上进行预训练，形成了基础的对象级表征，使 DINO-X 能够集成多个感知头，同时支持多项对象感知和理解任务，涵盖检测、分割、姿态估计、对象描述、基于对象的问答等。实验结果彰显了 DINO-X 的卓越性能。具体来说，DINO-X Pro 模型在 COCO、LVIS-minival 和 LVIS-val 零样本对象检测基准上分别斩获 56.0 AP、59.8 AP 和 52.4 AP 的成绩。值得注意的是，在 LVIS-minival 和 LVIS-val 基准的稀有类别上，它分别获得 63.3 AP 和 56.5 AP 的佳绩，均将此前的 SOTA 性能提升了 5.8 AP。这样的成果凸显出其在识别长尾对象方面大幅提升的能力。

> 
Abstract:In this paper, we introduce DINO-X, which is a unified object-centric vision model developed by IDEA Research with the best open-world object detection performance to date. DINO-X employs the same Transformer-based encoder-decoder architecture as Grounding DINO 1.5 to pursue an object-level representation for open-world object understanding. To make long-tailed object detection easy, DINO-X extends its input options to support text prompt, visual prompt, and customized prompt. With such flexible prompt options, we develop a universal object prompt to support prompt-free open-world detection, making it possible to detect anything in an image without requiring users to provide any prompt. To enhance the model's core grounding capability, we have constructed a large-scale dataset with over 100 million high-quality grounding samples, referred to as Grounding-100M, for advancing the model's open-vocabulary detection performance. Pre-training on such a large-scale grounding dataset leads to a foundational object-level representation, which enables DINO-X to integrate multiple perception heads to simultaneously support multiple object perception and understanding tasks, including detection, segmentation, pose estimation, object captioning, object-based QA, etc. Experimental results demonstrate the superior performance of DINO-X. Specifically, the DINO-X Pro model achieves 56.0 AP, 59.8 AP, and 52.4 AP on the COCO, LVIS-minival, and LVIS-val zero-shot object detection benchmarks, respectively. Notably, it scores 63.3 AP and 56.5 AP on the rare classes of LVIS-minival and LVIS-val benchmarks, both improving the previous SOTA performance by 5.8 AP. Such a result underscores its significantly improved capacity for recognizing long-tailed objects.
    

[Arxiv](https://arxiv.org/pdf/2411.14347)