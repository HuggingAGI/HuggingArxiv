# 迈向零-shot 相机陷阱图像分类

发布时间：2024年10月16日

`其他` `野生动物监测` `计算机视觉`

> Towards Zero-Shot Camera Trap Image Categorization

# 摘要

> 本文探索了相机陷阱图像自动分类的替代方案。首先，我们用单一模型对所有图像进行了最先进分类器的基准测试。接着，我们评估了将 MegaDetector 与多个分类器及 Segment Anything 结合的方法，以减少特定位置的过拟合。最后，我们提出了两种基于 DINOv2、BioCLIP、BLIP 和 ChatGPT 的零-shot 方法。在公开数据集（新西兰的 WCT 和美国的 CCT20）和私有数据集（中欧的 CEF）上的测试表明，结合 MegaDetector 与两个分类器的方法准确性最高，分别减少了 42%、48% 和 75% 的误差。此外，移除背景后，新位置的准确性误差减半。基于 DINOv2 和 FAISS 的零-shot 管道在 CCT20 和 CEF 上分别取得了仅 1.0% 和 4.7% 的误差，展示了零-shot 方法在相机陷阱图像分类中的巨大潜力。

> This paper describes the search for an alternative approach to the automatic categorization of camera trap images. First, we benchmark state-of-the-art classifiers using a single model for all images. Next, we evaluate methods combining MegaDetector with one or more classifiers and Segment Anything to assess their impact on reducing location-specific overfitting. Last, we propose and test two approaches using large language and foundational models, such as DINOv2, BioCLIP, BLIP, and ChatGPT, in a zero-shot scenario. Evaluation carried out on two publicly available datasets (WCT from New Zealand, CCT20 from the Southwestern US) and a private dataset (CEF from Central Europe) revealed that combining MegaDetector with two separate classifiers achieves the highest accuracy. This approach reduced the relative error of a single BEiTV2 classifier by approximately 42\% on CCT20, 48\% on CEF, and 75\% on WCT. Besides, as the background is removed, the error in terms of accuracy in new locations is reduced to half. The proposed zero-shot pipeline based on DINOv2 and FAISS achieved competitive results (1.0\% and 4.7\% smaller on CCT20, and CEF, respectively), which highlights the potential of zero-shot approaches for camera trap image categorization.

[Arxiv](https://arxiv.org/abs/2410.12769)