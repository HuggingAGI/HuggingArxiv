# PerSense：密集图像中的个性化实例分割技术

发布时间：2024年05月22日

`Agent

理由：这篇论文介绍了一个名为PerSense的框架，该框架旨在解决密集图像中的个性化实例分割问题。它通过引入新的模块和机制，如实例检测模块（IDM）、点提示选择模块（PPSM）和反馈机制，来提高在复杂场景中的实例分割性能。这些组件和机制的集成表明，PerSense框架作为一个智能Agent，能够自主地处理和分析视觉数据，以实现更精确的实例分割。因此，这篇论文更符合Agent分类，因为它描述了一个能够执行特定任务（即个性化实例分割）的智能系统。` `计算机视觉` `实例分割`

> PerSense: Personalized Instance Segmentation in Dense Images

# 摘要

> 借助大规模预训练，视觉基础模型展现出显著的性能提升。尽管分割算法近年来取得了显著进步，但现有模型在自动识别密集拥挤场景中的个性化实例时仍显不足。这一挑战主要源于基于边界框的检测方法，这些方法在处理密集图像时，常因遮挡、背景杂乱和物体方向问题而受限。为此，我们推出了PerSense，一个端到端、无需额外训练、适用于任何模型的框架，专为解决密集图像中的个性化实例分割难题。我们的核心贡献包括：(a) 引入实例检测模块（IDM），并结合视觉语言模型、物体检测器和少量对象计数器（FSOC），设立新基准；(b) 设计点提示选择模块（PPSM），有效减少误报，将FSOC的密度图转化为个性化实例分割的点提示，并实现与框架的无缝集成；(c) 引入反馈机制，自动化样本选择过程，最大化FSOC的效能；(d) 推出专为密集图像个性化实例分割设计的PerSense-D数据集，推动该领域的算法发展。我们在PerSense-D上验证了PerSense的性能，并与当前最佳技术进行了比较，同时展示了框架在自然环境中捕获图像上的良好适应性。

> Leveraging large-scale pre-training, vision foundational models showcase notable performance benefits. While recent years have witnessed significant advancements in segmentation algorithms, existing models still face challenges to automatically segment personalized instances in dense and crowded scenarios. The primary factor behind this limitation stems from bounding box-based detections, which are constrained by occlusions, background clutter, and object orientation, particularly when dealing with dense images. To this end, we propose PerSense, an end-to-end, training-free, and model-agnostic one-shot framework to address the personalized instance segmentation in dense images. Towards developing this framework, we make following core contributions. (a) We propose an Instance Detection Module (IDM) and leverage a Vision-Language Model, a grounding object detector, and a few-shot object counter (FSOC) to realize a new baseline. (b) To tackle false positives within candidate point prompts, we design Point Prompt Selection Module (PPSM). Both IDM and PPSM transform density maps from FSOC into personalized instance-level point prompts for segmentation and offer a seamless integration in our model-agnostic framework. (c) We introduce a feedback mechanism which enables PerSense to harness the full potential of FSOC by automating the exemplar selection process. (d) To promote algorithmic advances and effective tools for this relatively underexplored task, we introduce PerSense-D, a dataset exclusive to personalized instance segmentation in dense images. We validate the effectiveness of PerSense on the task of personalized instance segmentation in dense images on PerSense-D and comparison with SOTA. Additionally, our qualitative findings demonstrate the adaptability of our framework to images captured in-the-wild.

[Arxiv](https://arxiv.org/abs/2405.13518)