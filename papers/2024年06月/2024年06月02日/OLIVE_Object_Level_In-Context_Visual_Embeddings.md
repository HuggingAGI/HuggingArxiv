# OLIVE：对象级上下文视觉嵌入，一种新颖的视觉表示方法，旨在通过对象级别的上下文信息来增强视觉嵌入的表达能力。

发布时间：2024年06月02日

`Agent

理由：这篇论文介绍了一种新的方法，通过利用视觉对象向量引导大型语言模型，以实现对象级推理的可控性，并提升训练效率。这种方法涉及创建一个能够理解和处理视觉信息的智能Agent，该Agent能够在新对象出现时迅速适应，无需额外训练。这与Agent的定义相符，即一个能够感知环境并采取行动以达到目标的系统。此外，论文中提到的“全能视觉-语言模型（VLMs）”和“对象级推理”等概念，进一步强调了其在Agent领域的应用。因此，这篇论文应归类为Agent。` `计算机视觉`

> OLIVE: Object Level In-Context Visual Embeddings

# 摘要

> 全能视觉-语言模型（VLMs）虽在多模态任务中展现出卓越的推理能力，但在细粒度对象理解和定位上仍显不足。现有模型将文本与图像块隐式对齐，这不仅未能有效实现同粒度嵌入对齐，还引入了背景噪声。此外，面对未知的视觉概念，这些模型表现不佳，未经微调难以胜任特定领域任务。为此，我们创新性地利用视觉对象向量引导大型语言模型，实现了对象级推理的可控性，避免了图像块特征的冗长融合，大幅提升了训练效率。我们还引入了基于对象表示的区域级检索，使得模型能够迅速适应新对象，无需额外训练。实验结果显示，我们的方法在对象分类和描述任务中表现出色，同时具备零样本泛化能力和在复杂视觉环境中的稳健性。

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