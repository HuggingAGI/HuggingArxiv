# DetCLIPv3 致力于实现多样化的开放词汇目标检测，旨在提升生成式目标检测的灵活性与适应性。

发布时间：2024年04月14日

`LLM应用` `计算机视觉`

> DetCLIPv3: Towards Versatile Generative Open-vocabulary Object Detection

# 摘要

> 传统的开放词汇物体检测器往往受限于用户预设的类别集，应用范围受限。本文提出了DetCLIPv3，一种不仅在开放词汇表物体检测上表现出色，还能为识别物体生成层次化标签的高性能检测器。DetCLIPv3的核心设计包括：1. 灵活的模型架构，我们构建了一个鲁棒的开放集检测框架，并通过引入标题生成模块增强其生成能力。2. 高密度信息数据，我们开发了一种自动注释流程，利用视觉大型语言模型对大规模图像文本对的标题进行精细化处理，提供详尽的多维度物体标签，以加强训练效果。3. 有效的训练策略，我们使用低分辨率输入进行预训练，让物体标题生成器能高效地从大量图像文本配对数据中学习丰富的视觉概念。之后，通过少量高分辨率样本进行微调，进一步提升检测精度。得益于这些创新设计，DetCLIPv3在开放词汇表检测方面表现卓越，例如，Swin-T骨干模型在LVIS minival基准测试中实现了47.0的零样本固定AP，超越了GLIPv2、GroundingDINO和DetCLIPv2 18.0/19.6/6.6 AP。同时，在VG数据集的密集标题任务中，DetCLIPv3以19.7 AP的成绩刷新了最高记录，彰显了其出色的生成实力。

> Existing open-vocabulary object detectors typically require a predefined set of categories from users, significantly confining their application scenarios. In this paper, we introduce DetCLIPv3, a high-performing detector that excels not only at both open-vocabulary object detection, but also generating hierarchical labels for detected objects. DetCLIPv3 is characterized by three core designs: 1. Versatile model architecture: we derive a robust open-set detection framework which is further empowered with generation ability via the integration of a caption head. 2. High information density data: we develop an auto-annotation pipeline leveraging visual large language model to refine captions for large-scale image-text pairs, providing rich, multi-granular object labels to enhance the training. 3. Efficient training strategy: we employ a pre-training stage with low-resolution inputs that enables the object captioner to efficiently learn a broad spectrum of visual concepts from extensive image-text paired data. This is followed by a fine-tuning stage that leverages a small number of high-resolution samples to further enhance detection performance. With these effective designs, DetCLIPv3 demonstrates superior open-vocabulary detection performance, \eg, our Swin-T backbone model achieves a notable 47.0 zero-shot fixed AP on the LVIS minival benchmark, outperforming GLIPv2, GroundingDINO, and DetCLIPv2 by 18.0/19.6/6.6 AP, respectively. DetCLIPv3 also achieves a state-of-the-art 19.7 AP in dense captioning task on VG dataset, showcasing its strong generative capability.

[Arxiv](https://arxiv.org/abs/2404.09216)