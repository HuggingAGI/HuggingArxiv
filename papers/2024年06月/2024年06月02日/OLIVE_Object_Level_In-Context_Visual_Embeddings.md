# OLIVE：对象级上下文视觉嵌入，一种新颖的视觉表示方法，旨在通过对象级别的上下文信息来增强视觉嵌入的表达能力。

发布时间：2024年06月02日

`Agent

这篇论文主要介绍了一种创新的方法，通过引入视觉物体向量至大型语言模型，以实现更精准的物体级推理。这种方法不仅避免了传统的图像块特征融合的繁琐过程，还提高了训练效率。此外，论文还开发了一种基于物体表示的区域级检索技术，使模型能够快速适应新的视觉概念，无需额外的训练。这些特性使得该模型在物体分类与描述任务中表现出色，并展现出零样本泛化能力和对复杂视觉环境的强鲁棒性。因此，这篇论文更符合Agent分类，因为它描述了一种能够自主进行推理和适应新环境的智能系统。` `计算机视觉`

> OLIVE: Object Level In-Context Visual Embeddings

# 摘要

> 全能视觉-语言模型（VLMs）近期在多模态任务中展现了卓越的推理能力，但在细粒度的物体理解和定位上仍显不足。现有模型通过隐式对齐文本与图像块，未能有效实现同粒度嵌入对齐，且引入了背景噪声。此外，面对未知的视觉概念，这些模型泛化能力有限，特定领域任务中未经微调则可靠性不足。为此，我们创新性地引入视觉物体向量至大型语言模型，实现精准的物体级推理，避免了繁琐的图像块特征融合，大幅提升训练效率。我们还开发了基于物体表示的区域级检索技术，使模型能迅速适应新物体，无需额外训练。实验证明，我们的方法在物体分类与描述任务中表现优异，同时具备零样本泛化能力及对复杂视觉环境的强鲁棒性。

> Recent generalist vision-language models (VLMs) have demonstrated impressive reasoning capabilities across diverse multimodal tasks. However, these models still struggle with fine-grained object-level understanding and grounding. In terms of modeling, existing VLMs implicitly align text tokens with image patch tokens, which is ineffective for embedding alignment at the same granularity and inevitably introduces noisy spurious background features. Additionally, these models struggle when generalizing to unseen visual concepts and may not be reliable for domain-specific tasks without further fine-tuning. To address these limitations, we propose a novel method to prompt large language models with in-context visual object vectors, thereby enabling controllable object-level reasoning. This eliminates the necessity of fusing a lengthy array of image patch features and significantly speeds up training. Furthermore, we propose region-level retrieval using our object representations, facilitating rapid adaptation to new objects without additional training. Our experiments reveal that our method achieves competitive referring object classification and captioning performance, while also offering zero-shot generalization and robustness to visually challenging contexts.

![OLIVE：对象级上下文视觉嵌入，一种新颖的视觉表示方法，旨在通过对象级别的上下文信息来增强视觉嵌入的表达能力。](../../../paper_images/2406.00872/x1.png)

![OLIVE：对象级上下文视觉嵌入，一种新颖的视觉表示方法，旨在通过对象级别的上下文信息来增强视觉嵌入的表达能力。](../../../paper_images/2406.00872/x2.png)

![OLIVE：对象级上下文视觉嵌入，一种新颖的视觉表示方法，旨在通过对象级别的上下文信息来增强视觉嵌入的表达能力。](../../../paper_images/2406.00872/x3.png)

![OLIVE：对象级上下文视觉嵌入，一种新颖的视觉表示方法，旨在通过对象级别的上下文信息来增强视觉嵌入的表达能力。](../../../paper_images/2406.00872/x4.png)

![OLIVE：对象级上下文视觉嵌入，一种新颖的视觉表示方法，旨在通过对象级别的上下文信息来增强视觉嵌入的表达能力。](../../../paper_images/2406.00872/x5.png)

![OLIVE：对象级上下文视觉嵌入，一种新颖的视觉表示方法，旨在通过对象级别的上下文信息来增强视觉嵌入的表达能力。](../../../paper_images/2406.00872/x6.png)

![OLIVE：对象级上下文视觉嵌入，一种新颖的视觉表示方法，旨在通过对象级别的上下文信息来增强视觉嵌入的表达能力。](../../../paper_images/2406.00872/x7.png)

![OLIVE：对象级上下文视觉嵌入，一种新颖的视觉表示方法，旨在通过对象级别的上下文信息来增强视觉嵌入的表达能力。](../../../paper_images/2406.00872/x8.png)

![OLIVE：对象级上下文视觉嵌入，一种新颖的视觉表示方法，旨在通过对象级别的上下文信息来增强视觉嵌入的表达能力。](../../../paper_images/2406.00872/x9.png)

![OLIVE：对象级上下文视觉嵌入，一种新颖的视觉表示方法，旨在通过对象级别的上下文信息来增强视觉嵌入的表达能力。](../../../paper_images/2406.00872/x10.png)

![OLIVE：对象级上下文视觉嵌入，一种新颖的视觉表示方法，旨在通过对象级别的上下文信息来增强视觉嵌入的表达能力。](../../../paper_images/2406.00872/x11.png)

![OLIVE：对象级上下文视觉嵌入，一种新颖的视觉表示方法，旨在通过对象级别的上下文信息来增强视觉嵌入的表达能力。](../../../paper_images/2406.00872/x12.png)

![OLIVE：对象级上下文视觉嵌入，一种新颖的视觉表示方法，旨在通过对象级别的上下文信息来增强视觉嵌入的表达能力。](../../../paper_images/2406.00872/x13.png)

![OLIVE：对象级上下文视觉嵌入，一种新颖的视觉表示方法，旨在通过对象级别的上下文信息来增强视觉嵌入的表达能力。](../../../paper_images/2406.00872/x14.png)

![OLIVE：对象级上下文视觉嵌入，一种新颖的视觉表示方法，旨在通过对象级别的上下文信息来增强视觉嵌入的表达能力。](../../../paper_images/2406.00872/x15.png)

[Arxiv](https://arxiv.org/abs/2406.00872)