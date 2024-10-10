# 借助大型语言模型与布局到图像合成技术，提升少样本检测能力

发布时间：2024年10月09日

`LLM应用` `计算机视觉` `机器学习`

> Boosting Few-Shot Detection with Large Language Models and Layout-to-Image Synthesis

# 摘要

> 近期扩散模型的突破，使得生成大量高质量数据成为可能，广泛应用于各类下游任务。其中，布局到图像合成（LIS）模型，能根据空间布局生成逼真图像，尽管布局遵循度有限。如何有效利用这些模型进行小样本检测数据的扩展，仍待解答。为此，我们提出一种协作框架，结合大型语言模型（LLM）与LIS模型，旨在超越现有生成增强方法，提升小样本检测性能。我们利用LLM的推理能力，通过少量示例注释生成新的边界框，推断注释空间的空间先验。同时，引入布局感知CLIP评分，实现生成布局与图像的紧密结合。在COCO小样本基准测试中，YOLOX-S基线在5-、10-和30-shot设置下的mAP分别提升了140%、50%和35%。

> Recent advancements in diffusion models have enabled a wide range of works exploiting their ability to generate high-volume, high-quality data for use in various downstream tasks. One subclass of such models, dubbed Layout-to-Image Synthesis (LIS), learns to generate images conditioned on a spatial layout (bounding boxes, masks, poses, etc.) and has shown a promising ability to generate realistic images, albeit with limited layout-adherence. Moreover, the question of how to effectively transfer those models for scalable augmentation of few-shot detection data remains unanswered. Thus, we propose a collaborative framework employing a Large Language Model (LLM) and an LIS model for enhancing few-shot detection beyond state-of-the-art generative augmentation approaches. We leverage LLM's reasoning ability to extrapolate the spatial prior of the annotation space by generating new bounding boxes given only a few example annotations. Additionally, we introduce our novel layout-aware CLIP score for sample ranking, enabling tight coupling between generated layouts and images. Significant improvements on COCO few-shot benchmarks are observed. With our approach, a YOLOX-S baseline is boosted by more than 140%, 50%, 35% in mAP on the COCO 5-,10-, and 30-shot settings, respectively.

[Arxiv](https://arxiv.org/abs/2410.06841)