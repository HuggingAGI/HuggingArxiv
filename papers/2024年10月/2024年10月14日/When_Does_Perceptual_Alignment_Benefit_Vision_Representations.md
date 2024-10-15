# 何时感知对齐能提升视觉表示的效果？

发布时间：2024年10月14日

`其他` `计算机视觉`

> When Does Perceptual Alignment Benefit Vision Representations?

# 摘要

> 人类根据场景布局、主体位置和相机姿态等多种视觉属性判断相似性。现有视觉模型虽能理解广泛语义，但未能恰当权衡这些属性，导致推断与人类感知不符。尽管视觉表示在图像生成等场景中受益于对齐，但在更广泛应用中，感知对齐的效用仍不明朗。我们探讨了将视觉模型与人类感知判断对齐，如何提升其在多样计算机视觉任务中的表现。通过微调最先进模型以适应人类对图像三元组的相似性判断，并在标准基准上评估，我们发现这种对齐显著提升了模型在计数、分割、深度估计等任务中的表现，同时在医疗影像等特殊领域也保持了性能。这表明，引入人类感知知识的归纳偏置，有助于视觉模型生成更优的表示。

> Humans judge perceptual similarity according to diverse visual attributes, including scene layout, subject location, and camera pose. Existing vision models understand a wide range of semantic abstractions but improperly weigh these attributes and thus make inferences misaligned with human perception. While vision representations have previously benefited from alignment in contexts like image generation, the utility of perceptually aligned representations in more general-purpose settings remains unclear. Here, we investigate how aligning vision model representations to human perceptual judgments impacts their usability across diverse computer vision tasks. We finetune state-of-the-art models on human similarity judgments for image triplets and evaluate them across standard vision benchmarks. We find that aligning models to perceptual judgments yields representations that improve upon the original backbones across many downstream tasks, including counting, segmentation, depth estimation, instance retrieval, and retrieval-augmented generation. In addition, we find that performance is widely preserved on other tasks, including specialized out-of-distribution domains such as in medical imaging and 3D environment frames. Our results suggest that injecting an inductive bias about human perceptual knowledge into vision models can contribute to better representations.

[Arxiv](https://arxiv.org/abs/2410.10817)